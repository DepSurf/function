# Function: <code>atomic_add_negative</code>

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
In mm/rmap.c (ffffffff811cb035)
Location: arch/x86/include/asm/atomic.h:143
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
In mm/rmap.c (ffffffff811e7f73)
Location: arch/x86/include/asm/atomic.h:142
Inline: True
```
```
In mm/huge_memory.c (ffffffff812165ef)
Location: arch/x86/include/asm/atomic.h:142
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
In mm/rmap.c (ffffffff811f92f3)
Location: arch/x86/include/asm/atomic.h:142
Inline: True
```
```
In mm/huge_memory.c (ffffffff81228bb3)
Location: arch/x86/include/asm/atomic.h:142
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
In mm/rmap.c (ffffffff81203f03)
Location: arch/x86/include/asm/atomic.h:142
Inline: True
```
```
In mm/huge_memory.c (ffffffff812321ec)
Location: arch/x86/include/asm/atomic.h:142
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
In mm/rmap.c (ffffffff8121cc73)
Location: arch/x86/include/asm/atomic.h:143
Inline: True
```
```
In mm/huge_memory.c (ffffffff812530c4)
Location: arch/x86/include/asm/atomic.h:143
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
In mm/rmap.c (ffffffff8123ea93)
Location: include/asm-generic/atomic-instrumented.h:340
Inline: True
```
```
In mm/huge_memory.c (ffffffff8127756d)
Location: include/asm-generic/atomic-instrumented.h:340
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/rmap.c (ffffffff81253023)
Location: include/asm-generic/atomic-instrumented.h:395
Inline: True
```
```
In mm/huge_memory.c (ffffffff81288d6a)
Location: include/asm-generic/atomic-instrumented.h:395
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff81265322)
Location: include/asm-generic/atomic-instrumented.h:765
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a39d5)
Location: include/asm-generic/atomic-instrumented.h:765
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff81273be5)
Location: include/asm-generic/atomic-instrumented.h:765
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b4ed5)
Location: include/asm-generic/atomic-instrumented.h:765
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff812a5008)
Location: include/asm-generic/atomic-instrumented.h:766
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/hugetlb.c (ffffffff812c6835)
Location: include/asm-generic/atomic-instrumented.h:766
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
```
```
In mm/huge_memory.c (ffffffff812ea397)
Location: include/asm-generic/atomic-instrumented.h:766
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
In mm/rmap.c (ffffffff812b0544)
Location: include/asm-generic/atomic-instrumented.h:766
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/huge_memory.c (ffffffff812f556e)
Location: include/asm-generic/atomic-instrumented.h:766
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
In mm/rmap.c (ffffffff812b5b54)
Location: include/asm-generic/atomic-instrumented.h:766
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/huge_memory.c (ffffffff812fbbc5)
Location: include/asm-generic/atomic-instrumented.h:766
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
In kernel/ucount.c (ffffffff810ea46d)
Location: include/linux/atomic/atomic-instrumented.h:554
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:alloc_ucounts
```
```
In mm/rmap.c (ffffffff812f77d4)
Location: include/linux/atomic/atomic-instrumented.h:554
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/huge_memory.c (ffffffff813459be)
Location: include/linux/atomic/atomic-instrumented.h:554
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
In kernel/ucount.c (ffffffff8110513d)
Location: include/linux/atomic/atomic-instrumented.h:588
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:alloc_ucounts
```
```
In mm/rmap.c (ffffffff8135d440)
Location: include/linux/atomic/atomic-instrumented.h:588
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/huge_memory.c (ffffffff813bbaff)
Location: include/linux/atomic/atomic-instrumented.h:588
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
In kernel/ucount.c (ffffffff8112ab8d)
Location: include/linux/atomic/atomic-instrumented.h:588
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:alloc_ucounts
```
```
In mm/rmap.c (ffffffff813d7fa4)
Location: include/linux/atomic/atomic-instrumented.h:588
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
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
In kernel/ucount.c (ffffffff81137cf6)
Location: include/linux/atomic/atomic-instrumented.h:1409
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:alloc_ucounts
```
```
In mm/rmap.c (ffffffff8140c985)
Location: include/linux/atomic/atomic-instrumented.h:1409
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
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
In kernel/ucount.c (ffffffff81142f06)
Location: include/linux/atomic/atomic-instrumented.h:1409
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:alloc_ucounts
```
```
In mm/rmap.c (ffffffff8143b232)
Location: include/linux/atomic/atomic-instrumented.h:1409
Inline: True
Inline callers:
  - mm/rmap.c:folio_remove_rmap_pmd
  - mm/rmap.c:folio_remove_rmap_ptes
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
In mm/rmap.c (ffff800010309860)
Location: include/linux/atomic-fallback.h:1066
Inline: True
```
```
In mm/huge_memory.c (ffff800010355fa4)
Location: include/linux/atomic-fallback.h:1066
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (c05262c4)
Location: include/linux/atomic-fallback.h:1066
Inline: True
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
In mm/rmap.c (c0000000003d8f50)
Location: include/linux/atomic-fallback.h:1066
Inline: True
```
```
In mm/huge_memory.c (c00000000043c4b4)
Location: include/linux/atomic-fallback.h:1066
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffe000213a78)
Location: include/linux/atomic-fallback.h:1066
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
In mm/rmap.c (ffffffff8126c235)
Location: include/asm-generic/atomic-instrumented.h:765
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ad4b5)
Location: include/asm-generic/atomic-instrumented.h:765
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff8125e2a5)
Location: include/asm-generic/atomic-instrumented.h:765
Inline: True
```
```
In mm/huge_memory.c (ffffffff8129e46c)
Location: include/asm-generic/atomic-instrumented.h:765
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff81269fd5)
Location: include/asm-generic/atomic-instrumented.h:765
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ab2c5)
Location: include/asm-generic/atomic-instrumented.h:765
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff81279945)
Location: include/asm-generic/atomic-instrumented.h:765
Inline: True
```
```
In mm/huge_memory.c (ffffffff812bb615)
Location: include/asm-generic/atomic-instrumented.h:765
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
</ul>

## Differences
