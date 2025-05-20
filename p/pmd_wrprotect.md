# Function: <code>pmd_wrprotect</code>

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
In mm/huge_memory.c (ffffffff811f5e7c)
Location: arch/x86/include/asm/pgtable.h:277
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81278f7c)
Location: arch/x86/include/asm/pgtable.h:277
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/huge_memory.c (ffffffff81214ca8)
Location: arch/x86/include/asm/pgtable.h:301
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff812a5828)
Location: arch/x86/include/asm/pgtable.h:301
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/huge_memory.c (ffffffff81227290)
Location: arch/x86/include/asm/pgtable.h:301
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/dax.c (ffffffff8129bb9b)
Location: arch/x86/include/asm/pgtable.h:301
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812bb172)
Location: arch/x86/include/asm/pgtable.h:301
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffff81203274)
Location: arch/x86/include/asm/pgtable.h:358
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812330ca)
Location: arch/x86/include/asm/pgtable.h:358
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/dax.c (ffffffff812aaae8)
Location: arch/x86/include/asm/pgtable.h:358
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812c689e)
Location: arch/x86/include/asm/pgtable.h:358
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
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
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
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
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
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
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:402
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
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:402
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
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:441
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ec8a6)
Location: arch/x86/include/asm/pgtable.h:441
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:441
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:441
Inline: True
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
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:440
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f7937)
Location: arch/x86/include/asm/pgtable.h:440
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:440
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:440
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
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:440
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fde1a)
Location: arch/x86/include/asm/pgtable.h:440
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:change_huge_pmd
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:440
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:440
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
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:411
Inline: True
```
```
In mm/huge_memory.c (ffffffff813479ba)
Location: arch/x86/include/asm/pgtable.h:411
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:change_huge_pmd
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:411
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:411
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
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:414
Inline: True
```
```
In mm/huge_memory.c (ffffffff813c1e2b)
Location: arch/x86/include/asm/pgtable.h:414
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:change_huge_pmd
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:414
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
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:431
Inline: True
```
```
In mm/huge_memory.c (ffffffff81443ff8)
Location: arch/x86/include/asm/pgtable.h:431
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:change_huge_pmd
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:431
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
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:405
Inline: True
```
```
In mm/huge_memory.c (ffffffff814795a0)
Location: arch/x86/include/asm/pgtable.h:405
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:change_huge_pmd
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:405
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
In mm/rmap.c (ffffffff81437b89)
Location: arch/x86/include/asm/pgtable.h:526
Inline: True
```
```
In mm/huge_memory.c (ffffffff814a8b47)
Location: arch/x86/include/asm/pgtable.h:526
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8159db23)
Location: arch/x86/include/asm/pgtable.h:526
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:402
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
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:402
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
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:402
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
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:402
Inline: True
```
</details>
</li>
</ul>

## Differences
