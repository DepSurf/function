# Function: <code>lru_cache_add_active_or_unevictable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void lru_cache_add_active_or_unevictable(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119dfb0)
Location: mm/swap.c:711
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/swapfile.c:unuse_mm
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8119dfb0-ffffffff8119e044: lru_cache_add_active_or_unevictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void lru_cache_add_active_or_unevictable(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b3830)
Location: mm/swap.c:470
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/swapfile.c:unuse_mm
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff811b3830-ffffffff811b38d8: lru_cache_add_active_or_unevictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void lru_cache_add_active_or_unevictable(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c3ec0)
Location: mm/swap.c:471
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/swapfile.c:unuse_mm
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:khugepaged
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff811c3ec0-ffffffff811c3f68: lru_cache_add_active_or_unevictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void lru_cache_add_active_or_unevictable(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811cc2b0)
Location: mm/swap.c:482
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/swapfile.c:unuse_mm
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff811cc2b0-ffffffff811cc358: lru_cache_add_active_or_unevictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void lru_cache_add_active_or_unevictable(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811e12a0)
Location: mm/swap.c:482
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/swapfile.c:unuse_mm
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:khugepaged
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff811e12a0-ffffffff811e1348: lru_cache_add_active_or_unevictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void lru_cache_add_active_or_unevictable(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812029c0)
Location: mm/swap.c:459
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/swapfile.c:unuse_vma
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812029c0-ffffffff81202a63: lru_cache_add_active_or_unevictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void lru_cache_add_active_or_unevictable(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81215340)
Location: mm/swap.c:453
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/swapfile.c:unuse_vma
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81215340-ffffffff812153e3: lru_cache_add_active_or_unevictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void lru_cache_add_active_or_unevictable(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81224d60)
Location: mm/swap.c:454
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81224d60-ffffffff81224e05: lru_cache_add_active_or_unevictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void lru_cache_add_active_or_unevictable(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81232af0)
Location: mm/swap.c:455
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81232af0-ffffffff81232b95: lru_cache_add_active_or_unevictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void lru_cache_add_active_or_unevictable(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125ffd0)
Location: mm/swap.c:488
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/swapfile.c:unuse_pte
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic_pte
```
**Symbols:**

```
ffffffff8125ffd0-ffffffff81260072: lru_cache_add_active_or_unevictable (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void lru_cache_add_active_or_unevictable(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c2a78)
Location: mm/swap.c:455
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/swapfile.c:unuse_pte_range
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic_pte
```
**Symbols:**

```
ffff8000102c2a78-ffff8000102c2bb0: lru_cache_add_active_or_unevictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void lru_cache_add_active_or_unevictable(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04edc1c)
Location: mm/swap.c:455
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/swapfile.c:unuse_mm
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
c04edc1c-c04edcd8: lru_cache_add_active_or_unevictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void lru_cache_add_active_or_unevictable(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c00000000037cbb0)
Location: mm/swap.c:455
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/swapfile.c:unuse_pte_range
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
c00000000037cbb0-c00000000037cd08: lru_cache_add_active_or_unevictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void lru_cache_add_active_or_unevictable(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e3dc0)
Location: mm/swap.c:455
Inline: False
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/swapfile.c:unuse_pte_range
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffe0001e3dc0-ffffffe0001e3e8e: lru_cache_add_active_or_unevictable (STB_GLOBAL)
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
void lru_cache_add_active_or_unevictable(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8122b140)
Location: mm/swap.c:455
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8122b140-ffffffff8122b1e5: lru_cache_add_active_or_unevictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void lru_cache_add_active_or_unevictable(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121e250)
Location: mm/swap.c:455
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/swapfile.c:unuse_pte_range
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8121e250-ffffffff8121e2f5: lru_cache_add_active_or_unevictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void lru_cache_add_active_or_unevictable(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81228ee0)
Location: mm/swap.c:455
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81228ee0-ffffffff81228f85: lru_cache_add_active_or_unevictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void lru_cache_add_active_or_unevictable(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812382a0)
Location: mm/swap.c:455
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812382a0-ffffffff81238345: lru_cache_add_active_or_unevictable (STB_GLOBAL)
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
