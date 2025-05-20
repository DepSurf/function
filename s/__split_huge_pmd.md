# Function: <code>__split_huge_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81215d80)
Location: mm/huge_memory.c:1636
Inline: False
Direct callers:
  - mm/gup.c:follow_page_mask
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff81215d80-ffffffff812166fb: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812283a0)
Location: mm/huge_memory.c:1764
Inline: False
Direct callers:
  - mm/gup.c:follow_page_mask
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - fs/dax.c:dax_iomap_pmd_fault
```
**Symbols:**

```
ffffffff812283a0-ffffffff81228cbf: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812347d0)
Location: mm/huge_memory.c:2086
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff812347d0-ffffffff812349a2: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812526d0)
Location: mm/huge_memory.c:2224
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
  - mm/memory.c:__handle_mm_fault
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff812526d0-ffffffff812531ed: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81276ae0)
Location: mm/huge_memory.c:2216
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/mprotect.c:change_protection
  - mm/mremap.c:move_page_tables
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff81276ae0-ffffffff8127768e: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128ba20)
Location: mm/huge_memory.c:2238
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/pagewalk.c:walk_pgd_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff8128ba20-ffffffff8128bca4: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a6650)
Location: mm/huge_memory.c:2295
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/pagewalk.c:walk_pgd_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff812a6650-ffffffff812a68fa: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b7b20)
Location: mm/huge_memory.c:2300
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff812b7b20-ffffffff812b7dd0: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812eccf0)
Location: mm/huge_memory.c:2185
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/mremap.c:move_page_tables
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - fs/dax.c:dax_iomap_pmd_fault
```
**Symbols:**

```
ffffffff812eccf0-ffffffff812ed1cc: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f7f40)
Location: mm/huge_memory.c:2200
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/mremap.c:move_page_tables
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - fs/dax.c:dax_iomap_pmd_fault
```
**Symbols:**

```
ffffffff812f7f40-ffffffff812f83e8: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fe4f0)
Location: mm/huge_memory.c:2217
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/mremap.c:move_page_tables
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - fs/dax.c:dax_iomap_pmd_fault
```
**Symbols:**

```
ffffffff812fe4f0-ffffffff812fe8df: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81348090)
Location: mm/huge_memory.c:2145
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/mremap.c:move_page_tables
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - fs/dax.c:dax_iomap_pmd_fault
```
**Symbols:**

```
ffffffff81348090-ffffffff813484d9: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813be370)
Location: mm/huge_memory.c:2200
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/mremap.c:move_page_tables
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - fs/dax.c:dax_iomap_pmd_fault
```
**Symbols:**

```
ffffffff813be370-ffffffff813be636: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81440bd0)
Location: mm/huge_memory.c:2281
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/mremap.c:move_page_tables
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - fs/dax.c:dax_iomap_pmd_fault
```
**Symbols:**

```
ffffffff81440bd0-ffffffff81440ea8: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81476480)
Location: mm/huge_memory.c:2274
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/mremap.c:move_page_tables
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - fs/dax.c:dax_iomap_pmd_fault
```
**Symbols:**

```
ffffffff81476480-ffffffff8147673e: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a5d10)
Location: mm/huge_memory.c:2618
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/mremap.c:move_page_tables
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/userfaultfd.c:move_pages
  - fs/dax.c:dax_iomap_pmd_fault
```
**Symbols:**

```
ffffffff814a5d10-ffffffff814a5fc6: __split_huge_pmd (STB_GLOBAL)
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
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010358418)
Location: mm/huge_memory.c:2300
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffff800010358418-ffff8000103585e8: __split_huge_pmd (STB_GLOBAL)
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
Location: include/linux/huge_mm.h:336
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/huge_mm.h:336
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c000000000440c90)
Location: mm/huge_memory.c:2300
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:subpage_walk_pmd_entry
  - arch/powerpc/mm/book3s64/subpage_prot.c:subpage_walk_pmd_entry
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
c000000000440c90-c000000000441020: __split_huge_pmd (STB_GLOBAL)
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
In mm/memory.c (0)
Location: include/linux/huge_mm.h:336
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/huge_mm.h:336
Inline: True
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
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b0100)
Location: mm/huge_memory.c:2300
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff812b0100-ffffffff812b03b0: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a15c0)
Location: mm/huge_memory.c:2300
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/memory.c:__handle_mm_fault
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/pagewalk.c:walk_pgd_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff812a15c0-ffffffff812a1842: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812adf10)
Location: mm/huge_memory.c:2300
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff812adf10-ffffffff812ae1c0: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812be270)
Location: mm/huge_memory.c:2300
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff812be270-ffffffff812be518: __split_huge_pmd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
