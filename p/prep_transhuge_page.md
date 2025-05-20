# Function: <code>prep_transhuge_page</code>

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
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81216d0f)
Location: mm/huge_memory.c:461
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:khugepaged_alloc_page
```
**Symbols:**

```
ffffffff81214200-ffffffff81214227: prep_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812292bd)
Location: mm/huge_memory.c:491
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:khugepaged_alloc_page
```
**Symbols:**

```
ffffffff81226640-ffffffff81226667: prep_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812350f0)
Location: mm/huge_memory.c:493
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812324e0-ffffffff81232507: prep_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812534cf)
Location: mm/huge_memory.c:493
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:new_page_node
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff8124fb90-ffffffff8124fbb7: prep_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81277adc)
Location: mm/huge_memory.c:490
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff812740f0-ffffffff81274114: prep_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128c0f9)
Location: mm/huge_memory.c:500
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff81289120-ffffffff81289144: prep_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a6cf4)
Location: mm/huge_memory.c:505
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/gup.c:new_non_cma_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff812a3dd0-ffffffff812a3df4: prep_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b819f)
Location: mm/huge_memory.c:511
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/gup.c:new_non_cma_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff812b52d0-ffffffff812b52f4: prep_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ea90b)
Location: mm/huge_memory.c:511
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff812ea770-ffffffff812ea794: prep_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f5d9a)
Location: mm/huge_memory.c:504
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/mempolicy.c:new_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_migration_target
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812f5bd0-ffffffff812f5bf4: prep_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fc1ac)
Location: mm/huge_memory.c:521
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/mempolicy.c:new_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_migration_target
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812fbfb0-ffffffff812fbfd4: prep_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81346008)
Location: mm/huge_memory.c:521
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/mempolicy.c:new_page
  - mm/migrate.c:alloc_misplaced_dst_page_thp
  - mm/migrate.c:alloc_migration_target
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81345e00-ffffffff81345e24: prep_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813bc010)
Location: mm/huge_memory.c:520
Inline: False
Direct callers:
  - mm/page_alloc.c:__folio_alloc
  - mm/mempolicy.c:folio_alloc
  - mm/mempolicy.c:vma_alloc_folio
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff813bc010-ffffffff813bc03c: prep_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8143e5a0)
Location: mm/huge_memory.c:581
Inline: False
Direct callers:
  - mm/page_alloc.c:__folio_alloc
  - mm/mempolicy.c:folio_alloc
  - mm/mempolicy.c:vma_alloc_folio
  - mm/khugepaged.c:alloc_charge_hpage
```
**Symbols:**

```
ffffffff8143e5a0-ffffffff8143e5cc: prep_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81473d80)
Location: mm/huge_memory.c:580
Inline: False
Direct callers:
  - mm/page_alloc.c:__folio_alloc
  - mm/mempolicy.c:folio_alloc
  - mm/mempolicy.c:vma_alloc_folio
  - mm/khugepaged.c:alloc_charge_hpage
```
**Symbols:**

```
ffffffff81473d80-ffffffff81473dac: prep_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff8000103587d8)
Location: mm/huge_memory.c:511
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/gup.c:new_non_cma_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:alloc_new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffff800010356810-ffff800010356848: prep_transhuge_page (STB_GLOBAL)
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
In mm/gup.c (0)
Location: include/linux/huge_mm.h:311
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/huge_mm.h:311
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c000000000441558)
Location: mm/huge_memory.c:511
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/gup.c:new_non_cma_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:alloc_new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
c00000000043db50-c00000000043db70: prep_transhuge_page (STB_GLOBAL)
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
In mm/gup.c (0)
Location: include/linux/huge_mm.h:311
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/huge_mm.h:311
Inline: True
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
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b077f)
Location: mm/huge_memory.c:511
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/gup.c:new_non_cma_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff812ad8b0-ffffffff812ad8d4: prep_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a1a11)
Location: mm/huge_memory.c:511
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/gup.c:new_non_cma_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff8129ef30-ffffffff8129ef54: prep_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ae58f)
Location: mm/huge_memory.c:511
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/gup.c:new_non_cma_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff812ab6c0-ffffffff812ab6e4: prep_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void prep_transhuge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812be8ec)
Location: mm/huge_memory.c:511
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/gup.c:new_non_cma_page
  - mm/mempolicy.c:new_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff812bba30-ffffffff812bba54: prep_transhuge_page (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
