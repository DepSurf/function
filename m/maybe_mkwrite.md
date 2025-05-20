# Function: <code>maybe_mkwrite</code>

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
In mm/memory.c (0)
Location: include/linux/mm.h:572
Inline: True
```
```
In mm/migrate.c (ffffffff811f0e9c)
Location: include/linux/mm.h:572
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (0)
Location: include/linux/mm.h:572
Inline: True
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
In mm/memory.c (ffffffff811da5dc)
Location: include/linux/mm.h:621
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff8121012a)
Location: include/linux/mm.h:621
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812163ac)
Location: include/linux/mm.h:621
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/memory.c (ffffffff811ea0f8)
Location: include/linux/mm.h:608
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff81222252)
Location: include/linux/mm.h:608
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81228960)
Location: include/linux/mm.h:608
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/memory.c (ffffffff811f5098)
Location: include/linux/mm.h:664
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff8122e09c)
Location: include/linux/mm.h:664
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81231fd8)
Location: include/linux/mm.h:664
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff8120d177)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff81249e02)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81252d59)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/memory.c (ffffffff8122dd4b)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
```
```
In mm/migrate.c (ffffffff8126d506)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812771bc)
Location: include/linux/mm.h:723
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In mm/memory.c (ffffffff8124120d)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/migrate.c (ffffffff81281bf6)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81288a03)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In mm/memory.c (ffffffff81253503)
Location: include/linux/mm.h:817
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/migrate.c (ffffffff8129dea7)
Location: include/linux/mm.h:817
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a3649)
Location: include/linux/mm.h:817
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In mm/memory.c (ffffffff81261a63)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/migrate.c (ffffffff812ad757)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b4b49)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In mm/memory.c (ffffffff81291cbb)
Location: include/linux/mm.h:943
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/migrate.c (ffffffff812e2b01)
Location: include/linux/mm.h:943
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ea0ef)
Location: include/linux/mm.h:943
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff8129c582)
Location: include/linux/mm.h:984
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_pte_range
```
```
In mm/migrate.c (ffffffff812edfcd)
Location: include/linux/mm.h:984
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812f52c5)
Location: include/linux/mm.h:984
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff812a19da)
Location: include/linux/mm.h:1007
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_reuse
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_pte_range
```
```
In mm/migrate.c (ffffffff812f4158)
Location: include/linux/mm.h:1007
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812fb80e)
Location: include/linux/mm.h:1007
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff812e29aa)
Location: include/linux/mm.h:1011
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_pte_range
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/migrate.c (ffffffff8133eb9d)
Location: include/linux/mm.h:1011
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81345648)
Location: include/linux/mm.h:1011
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff81343244)
Location: include/linux/mm.h:978
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/migrate.c (ffffffff813b1d43)
Location: include/linux/mm.h:978
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff813bb623)
Location: include/linux/mm.h:978
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff813bb200)
Location: include/linux/mm.h:1108
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/migrate.c (ffffffff81432853)
Location: include/linux/mm.h:1108
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8143dbce)
Location: include/linux/mm.h:1108
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff813efcf2)
Location: include/linux/mm.h:1294
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
pte_t maybe_mkwrite(pte_t pte, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141b4a4)
Location: include/linux/mm.h:1348
Inline: True
Inline callers:
  - mm/memory.c:set_pte_range
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81414530-ffffffff81414555: maybe_mkwrite (STB_LOCAL)
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
In mm/memory.c (ffff8000102f8ec0)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/migrate.c (ffff80001034f150)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff800010355ef8)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In mm/memory.c (c051b368)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/migrate.c (c05517c0)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
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
In mm/memory.c (c0000000003c26f4)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/migrate.c (c000000000431620)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (c00000000043c3a0)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In mm/memory.c (ffffffe000208f84)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/migrate.c (ffffffe00023e346)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
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
In mm/memory.c (ffffffff8125a0b3)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/migrate.c (ffffffff812a5d37)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ad129)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In mm/memory.c (ffffffff8124c463)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/migrate.c (ffffffff812977f1)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8129e134)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In mm/memory.c (ffffffff81257e53)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/migrate.c (ffffffff812a3b47)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812aaf39)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In mm/memory.c (ffffffff8126783f)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/migrate.c (ffffffff812b4357)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812bb289)
Location: include/linux/mm.h:830
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
