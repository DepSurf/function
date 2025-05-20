# Function: <code>SetPageHWPoison</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812015c5)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/memory-failure.c:set_page_hwpoison_huge_page
  - mm/memory-failure.c:soft_offline_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81227ea6)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:set_page_hwpoison_huge_page
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
In mm/memory-failure.c (ffffffff8123a450)
Location: include/linux/page-flags.h:358
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:set_page_hwpoison_huge_page
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
In mm/hugetlb.c (ffffffff81216a00)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/memory-failure.c (ffffffff812461ef)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/hugetlb.c (ffffffff812316b0)
Location: include/linux/page-flags.h:362
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/memory-failure.c (ffffffff81266339)
Location: include/linux/page-flags.h:362
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/hugetlb.c (ffffffff812545c5)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/memory-failure.c (ffffffff8128a716)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/hugetlb.c (ffffffff812689a9)
Location: include/linux/page-flags.h:381
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/memory-failure.c (ffffffff8129f680)
Location: include/linux/page-flags.h:381
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/hugetlb.c (ffffffff81283a69)
Location: include/linux/page-flags.h:414
Inline: True
```
```
In mm/memory-failure.c (ffffffff812b99d5)
Location: include/linux/page-flags.h:414
Inline: True
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
In mm/hugetlb.c (ffffffff81293609)
Location: include/linux/page-flags.h:414
Inline: True
```
```
In mm/memory-failure.c (ffffffff812cc07d)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In mm/hugetlb.c (ffffffff812c4e9d)
Location: include/linux/page-flags.h:422
Inline: True
```
```
In mm/memory-failure.c (ffffffff81300ee9)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
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
In mm/hugetlb.c (ffffffff812d2715)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/memory-failure.c (ffffffff8130dcf2)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
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
In mm/hugetlb.c (ffffffff812d915a)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/memory-failure.c (ffffffff81314032)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
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
In mm/hugetlb.c (ffffffff8131fbf6)
Location: include/linux/page-flags.h:444
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/memory-failure.c (ffffffff813601a3)
Location: include/linux/page-flags.h:444
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:page_handle_poison
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
In mm/hugetlb.c (ffffffff8138c741)
Location: include/linux/page-flags.h:597
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/memory-failure.c (ffffffff813db04e)
Location: include/linux/page-flags.h:597
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:page_handle_poison
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
In mm/memory-failure.c (ffffffff8146154a)
Location: include/linux/page-flags.h:576
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:__free_raw_hwp_pages
  - mm/memory-failure.c:mf_dax_kill_procs
  - mm/memory-failure.c:page_handle_poison
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
In mm/memory-failure.c (ffffffff81498199)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:__folio_free_raw_hwp
  - mm/memory-failure.c:mf_dax_kill_procs
  - mm/memory-failure.c:page_handle_poison
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff82220a76)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In mm/memory-failure.c (ffffffff814c780b)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:__folio_free_raw_hwp
  - mm/memory-failure.c:mf_dax_kill_procs
  - mm/memory-failure.c:page_handle_poison
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
In mm/hugetlb.c (ffff80001033175c)
Location: include/linux/page-flags.h:414
Inline: True
```
```
In mm/memory-failure.c (ffff8000103707a4)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/hugetlb.c (c00000000040a4c4)
Location: include/linux/page-flags.h:414
Inline: True
```
```
In mm/memory-failure.c (c000000000461294)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In mm/hugetlb.c (ffffffff8128bbe9)
Location: include/linux/page-flags.h:414
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c465d)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In mm/hugetlb.c (ffffffff8127da19)
Location: include/linux/page-flags.h:414
Inline: True
```
```
In mm/memory-failure.c (ffffffff812b569d)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In mm/hugetlb.c (ffffffff812899f9)
Location: include/linux/page-flags.h:414
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c246d)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In mm/hugetlb.c (ffffffff812997dd)
Location: include/linux/page-flags.h:414
Inline: True
```
```
In mm/memory-failure.c (ffffffff812d2ef8)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
</details>
</li>
</ul>

## Differences
