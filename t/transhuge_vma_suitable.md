# Function: <code>transhuge_vma_suitable</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811da21e)
Location: mm/memory.c:2927
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e9d4e)
Location: mm/memory.c:2935
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f4e50)
Location: mm/memory.c:3131
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120cf50)
Location: mm/memory.c:3300
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122db1a)
Location: mm/memory.c:3345
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124129d)
Location: mm/memory.c:3105
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
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
In mm/memory.c (ffffffff81253754)
Location: include/linux/huge_mm.h:126
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/huge_memory.c (ffffffff812a3e36)
Location: include/linux/huge_mm.h:126
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:transparent_hugepage_enabled
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
In mm/memory.c (ffffffff81261cb4)
Location: include/linux/huge_mm.h:131
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/huge_memory.c (ffffffff812b5336)
Location: include/linux/huge_mm.h:131
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:transparent_hugepage_enabled
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
In mm/memory.c (ffffffff8128c729)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff812ea7c7)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:transparent_hugepage_enabled
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
In mm/memory.c (ffffffff812979b8)
Location: include/linux/huge_mm.h:157
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff812f5c27)
Location: include/linux/huge_mm.h:157
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:transparent_hugepage_enabled
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
In mm/memory.c (ffffffff812a1758)
Location: include/linux/huge_mm.h:118
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff812fc097)
Location: include/linux/huge_mm.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:transparent_hugepage_active
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
In mm/memory.c (ffffffff812e2728)
Location: include/linux/huge_mm.h:118
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff81345ee7)
Location: include/linux/huge_mm.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:transparent_hugepage_active
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
In mm/memory.c (ffffffff81342f29)
Location: include/linux/huge_mm.h:119
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff813bc127)
Location: include/linux/huge_mm.h:119
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:transparent_hugepage_active
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
In mm/memory.c (ffffffff813baeca)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/page_vma_mapped.c (ffffffff813d2c78)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/huge_memory.c (ffffffff8143e6e7)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:hugepage_vma_check
```
```
In mm/khugepaged.c (ffffffff81446002)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/khugepaged.c:hugepage_vma_revalidate
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
In mm/memory.c (ffffffff813ef9ea)
Location: include/linux/huge_mm.h:100
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/page_vma_mapped.c (ffffffff8140785b)
Location: include/linux/huge_mm.h:100
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/huge_memory.c (ffffffff81473ec7)
Location: include/linux/huge_mm.h:100
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:hugepage_vma_check
```
```
In mm/khugepaged.c (ffffffff8147b6e5)
Location: include/linux/huge_mm.h:100
Inline: True
Inline callers:
  - mm/khugepaged.c:hugepage_vma_revalidate
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f8c44)
Location: include/linux/huge_mm.h:131
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/huge_memory.c (ffff800010356874)
Location: include/linux/huge_mm.h:131
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c2494)
Location: include/linux/huge_mm.h:131
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/huge_memory.c (c00000000043dbdc)
Location: include/linux/huge_mm.h:131
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In mm/memory.c (ffffffff8125a304)
Location: include/linux/huge_mm.h:131
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/huge_memory.c (ffffffff812ad916)
Location: include/linux/huge_mm.h:131
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:transparent_hugepage_enabled
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
In mm/memory.c (ffffffff8124c723)
Location: include/linux/huge_mm.h:131
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/huge_memory.c (ffffffff8129ef96)
Location: include/linux/huge_mm.h:131
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:transparent_hugepage_enabled
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
In mm/memory.c (ffffffff812580a4)
Location: include/linux/huge_mm.h:131
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/huge_memory.c (ffffffff812ab726)
Location: include/linux/huge_mm.h:131
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:transparent_hugepage_enabled
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
In mm/memory.c (ffffffff81267a8e)
Location: include/linux/huge_mm.h:131
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/huge_memory.c (ffffffff812bba96)
Location: include/linux/huge_mm.h:131
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
</details>
</li>
</ul>

## Differences
