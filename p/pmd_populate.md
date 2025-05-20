# Function: <code>pmd_populate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_populate(struct mm_struct *mm, pmd_t *pmd, struct page *pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bd2b6)
Location: arch/x86/include/asm/pgalloc.h:69
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff811f38d0)
Location: arch/x86/include/asm/pgalloc.h:69
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
Direct callers:
  - mm/huge_memory.c:khugepaged
```
**Symbols:**

```
ffffffff811f38d0-ffffffff811f391a: pmd_populate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_populate(struct mm_struct *mm, pmd_t *pmd, struct page *pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811da425)
Location: arch/x86/include/asm/pgalloc.h:69
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812161cb)
Location: arch/x86/include/asm/pgalloc.h:69
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8121a955)
Location: arch/x86/include/asm/pgalloc.h:69
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81213820-ffffffff81213869: pmd_populate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_populate(struct mm_struct *mm, pmd_t *pmd, struct page *pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e9f48)
Location: arch/x86/include/asm/pgalloc.h:69
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff8122877f)
Location: arch/x86/include/asm/pgalloc.h:69
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8122eca4)
Location: arch/x86/include/asm/pgalloc.h:69
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff81225b80-ffffffff81225bc6: pmd_populate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_populate(struct mm_struct *mm, pmd_t *pmd, struct page *pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f5194)
Location: arch/x86/include/asm/pgalloc.h:71
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81231e29)
Location: arch/x86/include/asm/pgalloc.h:71
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812389df)
Location: arch/x86/include/asm/pgalloc.h:71
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812310e0-ffffffff81231126: pmd_populate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_populate(struct mm_struct *mm, pmd_t *pmd, struct page *pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120d277)
Location: arch/x86/include/asm/pgalloc.h:83
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81252ba6)
Location: arch/x86/include/asm/pgalloc.h:83
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812592da)
Location: arch/x86/include/asm/pgalloc.h:83
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff8124ef30-ffffffff8124ef7d: pmd_populate (STB_LOCAL)
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
In mm/memory.c (ffffffff8122de49)
Location: arch/x86/include/asm/pgalloc.h:83
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81276ff6)
Location: arch/x86/include/asm/pgalloc.h:83
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff8127ca25)
Location: arch/x86/include/asm/pgalloc.h:83
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In mm/memory.c (ffffffff812414ab)
Location: arch/x86/include/asm/pgalloc.h:90
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff8128884e)
Location: arch/x86/include/asm/pgalloc.h:90
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812910ce)
Location: arch/x86/include/asm/pgalloc.h:90
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In mm/memory.c (ffffffff8125361d)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812a348b)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812abbd2)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In mm/memory.c (ffffffff81261b7d)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812b498b)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812bd413)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In mm/memory.c (ffffffff8128e0ec)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812e9f18)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff812f2b27)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In mm/memory.c (ffffffff81298d8c)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Inline callers:
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812f50f8)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff812fd174)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_populate(struct mm_struct *mm, pmd_t *pmd, struct page *pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125c350)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/memory.c (ffffffff812a1bee)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812fa2e3)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff81303eec)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8125c350-ffffffff8125c39d: pmd_populate (STB_LOCAL)
ffffffff812fa240-ffffffff812fa28d: pmd_populate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_populate(struct mm_struct *mm, pmd_t *pmd, struct page *pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81298200)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/memory.c (ffffffff812e2bbe)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/mremap.c (ffffffff812f205d)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
```
```
In mm/huge_memory.c (ffffffff81344143)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8134dc2d)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81298200-ffffffff8129824d: pmd_populate (STB_LOCAL)
ffffffff813440a0-ffffffff813440ed: pmd_populate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_populate(struct mm_struct *mm, pmd_t *pmd, struct page *pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8133f8c2)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Inline callers:
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff81355dca)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
```
```
In mm/huge_memory.c (ffffffff813b966e)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff813c6e79)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff813b9500-ffffffff813b9564: pmd_populate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_populate(struct mm_struct *mm, pmd_t *pmd, struct page *pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b77f2)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Inline callers:
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff813d03eb)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143b94d)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff81446e50)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8143b870-ffffffff8143b8d4: pmd_populate (STB_LOCAL)
ffffffff81446e50-ffffffff81446eb4: pmd_populate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_populate(struct mm_struct *mm, pmd_t *pmd, struct page *pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ec595)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Inline callers:
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff8140515b)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
```
```
In mm/huge_memory.c (ffffffff814712af)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8147c5d0)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff814711d0-ffffffff81471234: pmd_populate (STB_LOCAL)
ffffffff8147c5d0-ffffffff8147c634: pmd_populate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_populate(struct mm_struct *mm, pmd_t *pmd, struct page *pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81417dd5)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Inline callers:
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff8143163b)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
```
```
In mm/huge_memory.c (ffffffff814a0e3f)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff814aba20)
Location: arch/x86/include/asm/pgalloc.h:78
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff814a0b00-ffffffff814a0b64: pmd_populate (STB_LOCAL)
ffffffff814aba20-ffffffff814aba84: pmd_populate (STB_LOCAL)
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
In mm/memory.c (ffff8000102f8fc0)
Location: arch/arm64/include/asm/pgalloc.h:115
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffff800010355e80)
Location: arch/arm64/include/asm/pgalloc.h:115
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffff80001035e930)
Location: arch/arm64/include/asm/pgalloc.h:115
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051b4f8)
Location: arch/arm/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
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
In mm/memory.c (c0000000003c2858)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:158
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (c00000000043c2b0)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:158
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (c000000000447c60)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020909c)
Location: arch/riscv/include/asm/pgalloc.h:23
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
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
In mm/memory.c (ffffffff8125a1cd)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812acf6b)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b59f3)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In mm/memory.c (ffffffff8124c5f1)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff8129dfdf)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812a6c13)
Location: arch/x86/include/asm/pgalloc.h:77
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
In mm/memory.c (ffffffff81257f6d)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812aad7b)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b3803)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In mm/memory.c (ffffffff81267959)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812bb0cb)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812c3c21)
Location: arch/x86/include/asm/pgalloc.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
