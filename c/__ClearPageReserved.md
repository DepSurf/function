# Function: <code>__ClearPageReserved</code>

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
In arch/x86/mm/init_64.c (ffffffff8181bb4e)
Location: include/linux/page-flags.h:222
Inline: True
```
```
In mm/page_alloc.c (ffffffff81f870f6)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:init_cma_reserved_pageblock
```
```
In mm/hugetlb.c (ffffffff811daffb)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In arch/x86/mm/init_64.c (ffffffff81895d66)
Location: include/linux/page-flags.h:276
Inline: True
```
```
In mm/page_alloc.c (ffffffff81fb0935)
Location: include/linux/page-flags.h:276
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/hugetlb.c (ffffffff811f9153)
Location: include/linux/page-flags.h:276
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In arch/x86/mm/init_64.c (ffffffff818ca486)
Location: include/linux/page-flags.h:286
Inline: True
```
```
In mm/page_alloc.c (ffffffff81fecc44)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/hugetlb.c (ffffffff81209d41)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In arch/x86/mm/init_64.c (ffffffff81901a03)
Location: include/linux/page-flags.h:286
Inline: True
```
```
In mm/page_alloc.c (ffffffff820ce89f)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/hugetlb.c (ffffffff812152e5)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In arch/x86/mm/init_64.c (ffffffff8198ba33)
Location: include/linux/page-flags.h:287
Inline: True
```
```
In mm/page_alloc.c (ffffffff826d72ba)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/hugetlb.c (ffffffff8122fe28)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In arch/x86/mm/init_64.c (ffffffff819e8327)
Location: include/linux/page-flags.h:294
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In mm/page_alloc.c (ffffffff827016f5)
Location: include/linux/page-flags.h:294
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/hugetlb.c (ffffffff81252283)
Location: include/linux/page-flags.h:294
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In arch/x86/mm/init_64.c (ffffffff81a23917)
Location: include/linux/page-flags.h:305
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In mm/page_alloc.c (ffffffff828b8d32)
Location: include/linux/page-flags.h:305
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:memblock_free_pages
  - mm/page_alloc.c:memblock_free_pages
```
```
In mm/hugetlb.c (ffffffff812664f3)
Location: include/linux/page-flags.h:305
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In arch/x86/mm/init_64.c (ffffffff81a93c43)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In mm/page_alloc.c (ffffffff828d5df5)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff81281793)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In arch/x86/mm/init_64.c (ffffffff81acb523)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In mm/page_alloc.c (ffffffff828de269)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff81290af3)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In arch/x86/mm/init_64.c (ffffffff81bc3a29)
Location: include/linux/page-flags.h:346
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In mm/page_alloc.c (ffffffff812b1618)
Location: include/linux/page-flags.h:346
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff812c3c33)
Location: include/linux/page-flags.h:346
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In arch/x86/mm/init_64.c (ffffffff81c3c95b)
Location: include/linux/page-flags.h:355
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In mm/page_alloc.c (ffffffff812bb418)
Location: include/linux/page-flags.h:355
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff812cf886)
Location: include/linux/page-flags.h:355
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In arch/x86/mm/init_64.c (ffffffff81c2ee37)
Location: include/linux/page-flags.h:355
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In mm/page_alloc.c (ffffffff812c0588)
Location: include/linux/page-flags.h:355
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff812d60d6)
Location: include/linux/page-flags.h:355
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In arch/x86/mm/init_64.c (ffffffff81d4d538)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In mm/page_alloc.c (ffffffff81303394)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff8131c9e2)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In arch/x86/mm/init_64.c (ffffffff81f1d237)
Location: include/linux/page-flags.h:519
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In mm/page_alloc.c (ffffffff8136b102)
Location: include/linux/page-flags.h:519
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff81388378)
Location: include/linux/page-flags.h:519
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__prep_compound_gigantic_page
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
In arch/x86/mm/init_64.c (ffffffff820c53a8)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In mm/page_alloc.c (ffffffff813e7402)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff814058fb)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
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
In arch/x86/mm/init_64.c (ffffffff82149408)
Location: include/linux/page-flags.h:491
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In mm/page_alloc.c (ffffffff8141c516)
Location: include/linux/page-flags.h:491
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff81438dfb)
Location: include/linux/page-flags.h:491
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
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
In arch/x86/mm/init_64.c (ffffffff8222bec8)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In mm/page_alloc.c (ffffffff81448fb6)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff814727bb)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
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
In mm/page_alloc.c (ffff800011456f28)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffff80001032e170)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (c1531888)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
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
In mm/page_alloc.c (c000000001380158)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (c000000000406ba4)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffe000015a46)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffe00022c3f0)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In arch/x86/mm/init_64.c (ffffffff81a6a393)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In mm/page_alloc.c (ffffffff828c711d)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff812890d3)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In arch/x86/mm/init_64.c (ffffffff81a26855)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In mm/page_alloc.c (ffffffff828bf842)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff8127af73)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In arch/x86/mm/init_64.c (ffffffff81ad67a3)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In mm/page_alloc.c (ffffffff828d9e9d)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff81286ee3)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In arch/x86/mm/init_64.c (ffffffff81ae2c63)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In mm/page_alloc.c (ffffffff828df2be)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff812975b3)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
```
</details>
</li>
</ul>

## Differences
