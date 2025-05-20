# Function: <code>pud_clear_bad</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811d03a0)
Location: mm/pgtable-generic.c:25
Inline: False
Direct callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff811d03a0-ffffffff811d03ee: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811ed550)
Location: mm/pgtable-generic.c:25
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff811ed550-ffffffff811ed59e: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811f7940)
Location: mm/pgtable-generic.c:25
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff811f7940-ffffffff811f798e: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81202ad0)
Location: mm/pgtable-generic.c:31
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff81202ad0-ffffffff81202b1e: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8121b840)
Location: mm/pgtable-generic.c:32
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff8121b840-ffffffff8121b88e: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8123d620)
Location: mm/pgtable-generic.c:32
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff8123d620-ffffffff8123d66e: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81251b70)
Location: mm/pgtable-generic.c:33
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff81251b70-ffffffff81251bbe: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81263e40)
Location: mm/pgtable-generic.c:33
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff81263e40-ffffffff81263e90: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812726b0)
Location: mm/pgtable-generic.c:33
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff812726b0-ffffffff81272700: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812a3450)
Location: mm/pgtable-generic.c:36
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
  - mm/mprotect.c:change_p4d_range
  - mm/mremap.c:get_old_pmd
  - mm/swapfile.c:unuse_p4d_range
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
**Symbols:**

```
ffffffff812a3450-ffffffff812a34a2: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812aed50)
Location: mm/pgtable-generic.c:36
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
  - mm/mprotect.c:change_p4d_range
  - mm/mremap.c:get_old_pud
  - mm/swapfile.c:unuse_p4d_range
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
**Symbols:**

```
ffffffff812aed50-ffffffff812aed98: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812b4280)
Location: mm/pgtable-generic.c:36
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
  - mm/mprotect.c:change_p4d_range
  - mm/mremap.c:get_old_pud
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/swapfile.c:unuse_vma
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
**Symbols:**

```
ffffffff812b4280-ffffffff812b42c8: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812f5e60)
Location: mm/pgtable-generic.c:36
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
  - mm/mprotect.c:change_p4d_range
  - mm/mremap.c:get_old_pud
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/swapfile.c:unuse_vma
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
**Symbols:**

```
ffffffff812f5e60-ffffffff812f5ea8: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81359dd0)
Location: mm/pgtable-generic.c:37
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:get_old_pud
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/swapfile.c:unuse_vma
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
**Symbols:**

```
ffffffff81359dd0-ffffffff81359e2f: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff813d47e0)
Location: mm/pgtable-generic.c:37
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:get_old_pud
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/swapfile.c:unuse_vma
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
**Symbols:**

```
ffffffff813d47e0-ffffffff813d483f: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff814091b0)
Location: mm/pgtable-generic.c:39
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
  - mm/mprotect.c:change_p4d_range
  - mm/mremap.c:get_old_pud
  - mm/vmalloc.c:vunmap_p4d_range
```
**Symbols:**

```
ffffffff814091b0-ffffffff8140920f: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff814359a0)
Location: mm/pgtable-generic.c:40
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
  - mm/mprotect.c:change_p4d_range
  - mm/mremap.c:get_old_pud
  - mm/vmalloc.c:vunmap_p4d_range
```
**Symbols:**

```
ffffffff814359a0-ffffffff814359ff: pud_clear_bad (STB_GLOBAL)
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
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffff800010307f30)
Location: mm/pgtable-generic.c:33
Inline: False
Direct callers:
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffff800010307f30-ffff800010307f6c: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (c0525408)
Location: mm/pgtable-generic.c:33
Inline: False
```
**Symbols:**

```
c0525408-c0525434: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (c0000000003d74b8)
Location: mm/pgtable-generic.c:33
Inline: False
Direct callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/vmalloc.c:vunmap_page_range
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
c0000000003d74b8-c0000000003d7518: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffe000212df0)
Location: mm/pgtable-generic.c:33
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffe000212df0-ffffffe000212e32: pud_clear_bad (STB_GLOBAL)
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
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8126ad00)
Location: mm/pgtable-generic.c:33
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff8126ad00-ffffffff8126ad50: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8125d1d3)
Location: mm/pgtable-generic.c:33
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff8125d1d3-ffffffff8125d208: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81268aa0)
Location: mm/pgtable-generic.c:33
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff81268aa0-ffffffff81268af0: pud_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pud_clear_bad(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81278430)
Location: mm/pgtable-generic.c:33
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff81278430-ffffffff81278480: pud_clear_bad (STB_GLOBAL)
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
