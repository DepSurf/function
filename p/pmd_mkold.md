# Function: <code>pmd_mkold</code>

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
In mm/huge_memory.c (ffffffff811f5e8a)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/huge_memory.c (ffffffff812183d8)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/huge_memory.c (ffffffff8122a97c)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/huge_memory.c (ffffffff812365f1)
Location: arch/x86/include/asm/pgtable.h:348
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/huge_memory.c (ffffffff81255c81)
Location: arch/x86/include/asm/pgtable.h:363
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/huge_memory.c (ffffffff81279afe)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/huge_memory.c (ffffffff8128e0db)
Location: arch/x86/include/asm/pgtable.h:375
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a8a5d)
Location: arch/x86/include/asm/pgtable.h:392
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/madvise.c (ffffffff81285360)
Location: arch/x86/include/asm/pgtable.h:392
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff812b9fdd)
Location: arch/x86/include/asm/pgtable.h:392
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/madvise.c (ffffffff812b7957)
Location: arch/x86/include/asm/pgtable.h:431
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff812eebba)
Location: arch/x86/include/asm/pgtable.h:431
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/madvise.c (ffffffff812c2892)
Location: arch/x86/include/asm/pgtable.h:430
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff812fa21a)
Location: arch/x86/include/asm/pgtable.h:430
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/madvise.c (ffffffff812c9718)
Location: arch/x86/include/asm/pgtable.h:430
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff81300fdd)
Location: arch/x86/include/asm/pgtable.h:430
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/madvise.c (ffffffff8130e73a)
Location: arch/x86/include/asm/pgtable.h:401
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff8134ac4d)
Location: arch/x86/include/asm/pgtable.h:401
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/madvise.c (ffffffff81377b41)
Location: arch/x86/include/asm/pgtable.h:404
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff813c1ddd)
Location: arch/x86/include/asm/pgtable.h:404
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/madvise.c (ffffffff813f52e3)
Location: arch/x86/include/asm/pgtable.h:421
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff81444020)
Location: arch/x86/include/asm/pgtable.h:421
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/madvise.c (ffffffff81428496)
Location: arch/x86/include/asm/pgtable.h:427
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff814795c8)
Location: arch/x86/include/asm/pgtable.h:427
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/madvise.c (ffffffff81461d91)
Location: arch/x86/include/asm/pgtable.h:555
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff814a8b83)
Location: arch/x86/include/asm/pgtable.h:555
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
In mm/madvise.c (ffffffff8127d9b0)
Location: arch/x86/include/asm/pgtable.h:392
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff812b25bd)
Location: arch/x86/include/asm/pgtable.h:392
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/madvise.c (ffffffff8126fc68)
Location: arch/x86/include/asm/pgtable.h:392
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff812a393d)
Location: arch/x86/include/asm/pgtable.h:392
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/madvise.c (ffffffff8127b750)
Location: arch/x86/include/asm/pgtable.h:392
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff812b03cd)
Location: arch/x86/include/asm/pgtable.h:392
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/madvise.c (ffffffff8128b722)
Location: arch/x86/include/asm/pgtable.h:392
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff812c070d)
Location: arch/x86/include/asm/pgtable.h:392
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
</ul>

## Differences
