# Function: <code>ClearPageHWPoison</code>

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
In mm/sparse.c (ffffffff811e38ad)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/memory-failure.c (ffffffff81201e3e)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
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
In mm/sparse.c (ffffffff812022f3)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/memory-failure.c (ffffffff81227a65)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
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
In mm/sparse.c (ffffffff81214133)
Location: include/linux/page-flags.h:358
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/memory-failure.c (ffffffff81239fef)
Location: include/linux/page-flags.h:358
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
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
In mm/hugetlb.c (ffffffff81216a05)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/sparse.c (ffffffff8121f527)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
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
In mm/hugetlb.c (ffffffff812316b5)
Location: include/linux/page-flags.h:362
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/sparse.c (ffffffff8123a75f)
Location: include/linux/page-flags.h:362
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
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
In mm/hugetlb.c (ffffffff812545ca)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/sparse.c (ffffffff8125dcde)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
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
In mm/hugetlb.c (ffffffff812689ae)
Location: include/linux/page-flags.h:381
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/sparse.c (ffffffff81272614)
Location: include/linux/page-flags.h:381
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
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
In mm/hugetlb.c (ffffffff81283a6e)
Location: include/linux/page-flags.h:414
Inline: True
```
```
In mm/sparse.c (ffffffff8128dd44)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
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
In mm/hugetlb.c (ffffffff8129360e)
Location: include/linux/page-flags.h:414
Inline: True
```
```
In mm/sparse.c (ffffffff8129da43)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
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
In mm/hugetlb.c (ffffffff812c4ea2)
Location: include/linux/page-flags.h:422
Inline: True
```
```
In mm/sparse.c (ffffffff812d16d7)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
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
In mm/hugetlb.c (ffffffff812d271a)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/sparse.c (ffffffff812dd1f7)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/memory-failure.c (ffffffff8130e7bf)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In mm/hugetlb.c (ffffffff812d915f)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/sparse.c (ffffffff812e4a4d)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/memory-failure.c (ffffffff81314c53)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In mm/hugetlb.c (ffffffff8131fbfc)
Location: include/linux/page-flags.h:444
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/sparse.c (ffffffff8132bccd)
Location: include/linux/page-flags.h:444
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/memory-failure.c (ffffffff81360cd3)
Location: include/linux/page-flags.h:444
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In mm/hugetlb.c (ffffffff8138c747)
Location: include/linux/page-flags.h:597
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/memory-failure.c (ffffffff813dd777)
Location: include/linux/page-flags.h:597
Inline: True
Inline callers:
  - mm/memory-failure.c:clear_hwpoisoned_pages
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81463511)
Location: include/linux/page-flags.h:576
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81499159)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
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
In mm/memory-failure.c (ffffffff814c8855)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
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
In mm/hugetlb.c (ffff80001033176c)
Location: include/linux/page-flags.h:414
Inline: True
```
```
In mm/sparse.c (ffff80001033cb98)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
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
In mm/hugetlb.c (c00000000040a4d8)
Location: include/linux/page-flags.h:414
Inline: True
```
```
In mm/sparse.c (c000000000417d3c)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
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
In mm/hugetlb.c (0)
Location: include/linux/page-flags.h:419
Inline: True
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
In mm/hugetlb.c (ffffffff8128bbee)
Location: include/linux/page-flags.h:414
Inline: True
```
```
In mm/sparse.c (ffffffff81296023)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
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
In mm/hugetlb.c (ffffffff8127da1e)
Location: include/linux/page-flags.h:414
Inline: True
```
```
In mm/sparse.c (ffffffff81287c33)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
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
In mm/hugetlb.c (ffffffff812899fe)
Location: include/linux/page-flags.h:414
Inline: True
```
```
In mm/sparse.c (ffffffff81293e33)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
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
In mm/hugetlb.c (ffffffff812997e2)
Location: include/linux/page-flags.h:414
Inline: True
```
```
In mm/sparse.c (ffffffff812a3c93)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
</details>
</li>
</ul>

## Differences
