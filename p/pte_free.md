# Function: <code>pte_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff811bd307)
Location: arch/x86/include/asm/pgalloc.h:48
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff811f4020)
Location: arch/x86/include/asm/pgalloc.h:48
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff811f4020-ffffffff811f4047: pte_free.isra.36 (STB_LOCAL)
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
In mm/memory.c (ffffffff811db738)
Location: arch/x86/include/asm/pgalloc.h:48
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81215987)
Location: arch/x86/include/asm/pgalloc.h:48
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121b62d)
Location: arch/x86/include/asm/pgalloc.h:48
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/memory.c (ffffffff811ead6f)
Location: arch/x86/include/asm/pgalloc.h:48
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81227f38)
Location: arch/x86/include/asm/pgalloc.h:48
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122ccad)
Location: arch/x86/include/asm/pgalloc.h:48
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/memory.c (ffffffff811f5cf0)
Location: arch/x86/include/asm/pgalloc.h:50
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812340c3)
Location: arch/x86/include/asm/pgalloc.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81239290)
Location: arch/x86/include/asm/pgalloc.h:50
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/memory.c (ffffffff8120d764)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81251cf4)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812579a3)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/memory.c (ffffffff8122e288)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81276261)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127bbfd)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/memory.c (ffffffff81242065)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff8128af41)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8128ff35)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/memory.c (ffffffff81253b21)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812a5ae4)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812ab129)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/dax.c (0)
Location: include/asm-generic/pgalloc.h:99
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
In mm/memory.c (ffffffff81262084)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812b6fa4)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bcac2)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/asm-generic/pgalloc.h:99
Inline: True
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
In mm/memory.c (ffffffff81292047)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812ec186)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f125e)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/asm-generic/pgalloc.h:99
Inline: False
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
In mm/memory.c (ffffffff8129c909)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812f71ea)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812fc954)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/asm-generic/pgalloc.h:99
Inline: True
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
In mm/memory.c (ffffffff812a200c)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812fd67c)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813036c3)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/asm-generic/pgalloc.h:99
Inline: True
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
In mm/memory.c (ffffffff812e2eec)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff813472b1)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134d42d)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/asm-generic/pgalloc.h:99
Inline: True
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
In mm/memory.c (ffffffff81343822)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff813bd594)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c3bb3)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In fs/dax.c (0)
Location: include/asm-generic/pgalloc.h:99
Inline: True
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
In mm/memory.c (ffffffff813bb8ac)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff8143fd2c)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81447392)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In fs/dax.c (0)
Location: include/asm-generic/pgalloc.h:99
Inline: True
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
In mm/memory.c (ffffffff813f0405)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81475554)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147ca6c)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In fs/dax.c (0)
Location: include/asm-generic/pgalloc.h:99
Inline: True
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
In mm/memory.c (ffffffff8141ba55)
Location: include/asm-generic/pgalloc.h:104
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/pgtable-generic.c (ffffffff81435824)
Location: include/asm-generic/pgalloc.h:104
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pte_free_now
```
```
In mm/huge_memory.c (ffffffff814a4f35)
Location: include/asm-generic/pgalloc.h:104
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/dax.c (0)
Location: include/asm-generic/pgalloc.h:104
Inline: False
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
In mm/memory.c (ffff8000102f9338)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffff800010357cf0)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035dcd4)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
In arch/arm/mm/pgd.c (c031f9a0)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - arch/arm/mm/pgd.c:pgd_free
```
```
In mm/memory.c (c051b80c)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:do_fault
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
In arch/powerpc/mm/hugetlbpage.c (0)
Location: arch/powerpc/include/asm/pgalloc.h:43
Inline: True
```
```
In mm/memory.c (c0000000003c2f2c)
Location: arch/powerpc/include/asm/pgalloc.h:43
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (c00000000043c134)
Location: arch/powerpc/include/asm/pgalloc.h:43
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (c00000000044939c)
Location: arch/powerpc/include/asm/pgalloc.h:43
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (c0000000005146fc)
Location: arch/powerpc/include/asm/pgalloc.h:43
Inline: True
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
In mm/memory.c (ffffffe000209322)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:do_fault
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
In mm/memory.c (ffffffff8125a6d4)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812af584)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b50a2)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/asm-generic/pgalloc.h:99
Inline: True
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
In mm/memory.c (ffffffff8124caf4)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812a0b75)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a60c2)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/asm-generic/pgalloc.h:99
Inline: True
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
In mm/memory.c (ffffffff81258474)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812ad394)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b2eb2)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/asm-generic/pgalloc.h:99
Inline: True
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
In mm/memory.c (ffffffff81267e54)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812bd715)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c32e6)
Location: include/asm-generic/pgalloc.h:99
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/asm-generic/pgalloc.h:99
Inline: True
```
</details>
</li>
</ul>

## Differences
