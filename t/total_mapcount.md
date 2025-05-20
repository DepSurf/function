# Function: <code>total_mapcount</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int total_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812168b0)
Location: mm/huge_memory.c:1878
Inline: True
Direct callers:
  - mm/rmap.c:page_referenced
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812168b0-ffffffff81216960: total_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int total_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81228e70)
Location: mm/huge_memory.c:2009
Inline: True
Direct callers:
  - mm/rmap.c:page_referenced
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff81228e70-ffffffff81228f20: total_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int total_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81234b50)
Location: mm/huge_memory.c:2333
Inline: True
Direct callers:
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
**Symbols:**

```
ffffffff81234b50-ffffffff81234bf9: total_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int total_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81254570)
Location: mm/huge_memory.c:2485
Inline: True
Direct callers:
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
**Symbols:**

```
ffffffff81254570-ffffffff81254619: total_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int total_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812783c0)
Location: mm/huge_memory.c:2477
Inline: True
Direct callers:
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
**Symbols:**

```
ffffffff812783c0-ffffffff81278469: total_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int total_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128ca00)
Location: mm/huge_memory.c:2496
Inline: True
Direct callers:
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
**Symbols:**

```
ffffffff8128ca00-ffffffff8128cab1: total_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int total_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a76f0)
Location: mm/huge_memory.c:2557
Inline: True
Direct callers:
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
**Symbols:**

```
ffffffff812a76f0-ffffffff812a77bd: total_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int total_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b8b90)
Location: mm/huge_memory.c:2580
Inline: True
Direct callers:
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
**Symbols:**

```
ffffffff812b8b90-ffffffff812b8c5d: total_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int total_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ed740)
Location: mm/huge_memory.c:2490
Inline: True
Direct callers:
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/khugepaged.c:is_refcount_suitable
```
**Symbols:**

```
ffffffff812ed740-ffffffff812ed802: total_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int total_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffffffff812f9300)
Location: mm/huge_memory.c:2546
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
Direct callers:
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/khugepaged.c:is_refcount_suitable
```
**Symbols:**

```
ffffffff812f3a90-ffffffff812f3b50: total_mapcount.part.0 (STB_LOCAL)
ffffffff812f8e60-ffffffff812f8e89: total_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int total_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ff3f0)
Location: mm/huge_memory.c:2557
Inline: True
Direct callers:
  - mm/rmap.c:page_referenced
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:is_refcount_suitable
```
**Symbols:**

```
ffffffff812ff3f0-ffffffff812ff4c6: total_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int total_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81349000)
Location: mm/huge_memory.c:2496
Inline: True
Direct callers:
  - mm/rmap.c:page_referenced
  - mm/migrate.c:migrate_misplaced_page
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:is_refcount_suitable
  - mm/memfd.c:memfd_wait_for_pins
```
**Symbols:**

```
ffffffff81349000-ffffffff813490d6: total_mapcount (STB_GLOBAL)
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
In mm/migrate.c (ffffffff813b2c86)
Location: include/linux/mm.h:832
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
```
```
In mm/huge_memory.c (ffffffff813c02c9)
Location: include/linux/mm.h:832
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813c4125)
Location: include/linux/mm.h:832
Inline: True
Inline callers:
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memfd.c (ffffffff813e9686)
Location: include/linux/mm.h:832
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
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
In mm/compaction.c (ffffffff813a7e1d)
Location: include/linux/mm.h:913
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (0)
Location: include/linux/mm.h:913
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
```
```
In mm/huge_memory.c (ffffffff814425dc)
Location: include/linux/mm.h:913
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81448045)
Location: include/linux/mm.h:913
Inline: True
Inline callers:
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memfd.c (ffffffff81471657)
Location: include/linux/mm.h:913
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
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
In mm/migrate.c (ffffffff81468a83)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
```
```
In mm/khugepaged.c (ffffffff8147da25)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memfd.c (ffffffff814a5b98)
Location: include/linux/mm.h:1158
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
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
In mm/memfd.c (ffffffff814d6b45)
Location: include/linux/mm.h:1241
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int total_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010359240)
Location: mm/huge_memory.c:2580
Inline: True
Direct callers:
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
**Symbols:**

```
ffff800010359240-ffff80001035931c: total_mapcount (STB_GLOBAL)
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
In mm/rmap.c (c0525a58)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int total_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c0000000004425e0)
Location: mm/huge_memory.c:2580
Inline: True
Direct callers:
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
**Symbols:**

```
c0000000004425e0-c000000000442764: total_mapcount (STB_GLOBAL)
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
In mm/rmap.c (ffffffe000213348)
Location: include/linux/mm.h:730
Inline: True
Inline callers:
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int total_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b1170)
Location: mm/huge_memory.c:2580
Inline: True
Direct callers:
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
**Symbols:**

```
ffffffff812b1170-ffffffff812b123d: total_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int total_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a2540)
Location: mm/huge_memory.c:2580
Inline: True
Direct callers:
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
**Symbols:**

```
ffffffff812a2540-ffffffff812a260d: total_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int total_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812aef80)
Location: mm/huge_memory.c:2580
Inline: True
Direct callers:
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
**Symbols:**

```
ffffffff812aef80-ffffffff812af04d: total_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int total_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bf2d0)
Location: mm/huge_memory.c:2580
Inline: True
Direct callers:
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
**Symbols:**

```
ffffffff812bf2d0-ffffffff812bf39d: total_mapcount (STB_GLOBAL)
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
