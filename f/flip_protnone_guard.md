# Function: <code>flip_protnone_guard</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122e688)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (ffffffff812392c0)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff81256e21)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/migrate.c (ffffffff81272b26)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812766ff)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff81242597)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff8124d855)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff8126b3e2)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/migrate.c (ffffffff8128722b)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8128b68a)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff81251357)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8125f85a)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff812866ba)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/migrate.c (ffffffff812a1735)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812a61ef)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff8125f907)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8126e06a)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8129629f)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/migrate.c (ffffffff812b2b43)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b76bf)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff8128fdbd)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8129e678)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff812c982a)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/migrate.c (ffffffff812e80c1)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812ec861)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff8129a83d)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff812a9a38)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff812d5594)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/migrate.c (ffffffff812f33c4)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812f78f2)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff8129fc58)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff812aeec3)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff812dc20f)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/migrate.c (ffffffff812f981f)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812fddcc)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff812e324e)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff812f06b3)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff813233a5)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/huge_memory.c (ffffffff8134796c)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff813445d0)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff81353cc0)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff81390c95)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/huge_memory.c (ffffffff813bdcbe)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff813bc704)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff813ce1a6)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8141259c)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/huge_memory.c (ffffffff81440593)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff813f10f2)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff81402a5a)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff81445b72)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/huge_memory.c (ffffffff81475d26)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff8141bde8)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8142f063)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8147f532)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/huge_memory.c (ffffffff814a0c7e)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:pmd_modify
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
In mm/memory.c (ffffffff81257f57)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff812666ba)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8128e87f)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/migrate.c (ffffffff812ab123)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812afc9f)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff8124da5a)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff81258d95)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff8128063a)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/migrate.c (ffffffff8129cb06)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812a10aa)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff81255cf7)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8126445a)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8128c68f)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/migrate.c (ffffffff812a8f33)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812adaaf)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff81265787)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff81273e1a)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8129c477)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/migrate.c (ffffffff812b924d)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812bde19)
Location: arch/x86/include/asm/pgtable-invert.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
</details>
</li>
</ul>

## Differences
