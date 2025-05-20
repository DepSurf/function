# Function: <code>pmd_mkdirty</code>

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
In mm/migrate.c (ffffffff811f33ef)
Location: arch/x86/include/asm/pgtable.h:282
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f57cf)
Location: arch/x86/include/asm/pgtable.h:282
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
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
In mm/memory.c (ffffffff811da73c)
Location: arch/x86/include/asm/pgtable.h:306
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff812131d2)
Location: arch/x86/include/asm/pgtable.h:306
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81216feb)
Location: arch/x86/include/asm/pgtable.h:306
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121a73d)
Location: arch/x86/include/asm/pgtable.h:306
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In mm/memory.c (ffffffff811ea258)
Location: arch/x86/include/asm/pgtable.h:306
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff8122553a)
Location: arch/x86/include/asm/pgtable.h:306
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8122959b)
Location: arch/x86/include/asm/pgtable.h:306
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122eb47)
Location: arch/x86/include/asm/pgtable.h:306
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/memory.c (ffffffff811f52be)
Location: arch/x86/include/asm/pgtable.h:363
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff81230c0b)
Location: arch/x86/include/asm/pgtable.h:363
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812343bc)
Location: arch/x86/include/asm/pgtable.h:363
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81238815)
Location: arch/x86/include/asm/pgtable.h:363
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff812c68e7)
Location: arch/x86/include/asm/pgtable.h:363
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
In mm/memory.c (ffffffff8120d3e5)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff8124e97f)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81252332)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81259c70)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/proc/task_mmu.c (ffffffff812ecdb2)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff8122dfca)
Location: arch/x86/include/asm/pgtable.h:388
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff812727a3)
Location: arch/x86/include/asm/pgtable.h:388
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8127788e)
Location: arch/x86/include/asm/pgtable.h:388
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127c5dc)
Location: arch/x86/include/asm/pgtable.h:388
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff813193f4)
Location: arch/x86/include/asm/pgtable.h:388
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff81241620)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff81286d8a)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8128beab)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81290c9f)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff81330a08)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff81253988)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff812a1313)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812a6a6c)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812aba93)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff8135882f)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff81261ee8)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff812b2733)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b7f3c)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bd28d)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff81370a7f)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff8128c925)
Location: arch/x86/include/asm/pgtable.h:446
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/migrate.c (ffffffff812e7cd0)
Location: arch/x86/include/asm/pgtable.h:446
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812ed3b6)
Location: arch/x86/include/asm/pgtable.h:446
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f29be)
Location: arch/x86/include/asm/pgtable.h:446
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:446
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff81297bbc)
Location: arch/x86/include/asm/pgtable.h:445
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/migrate.c (ffffffff812f30bc)
Location: arch/x86/include/asm/pgtable.h:445
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812f8ad6)
Location: arch/x86/include/asm/pgtable.h:445
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812fcfd5)
Location: arch/x86/include/asm/pgtable.h:445
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:445
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff812a195f)
Location: arch/x86/include/asm/pgtable.h:445
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/migrate.c (ffffffff812f9455)
Location: arch/x86/include/asm/pgtable.h:445
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812ff00e)
Location: arch/x86/include/asm/pgtable.h:445
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81303d4a)
Location: arch/x86/include/asm/pgtable.h:445
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:445
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff812e292c)
Location: arch/x86/include/asm/pgtable.h:416
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff81348c04)
Location: arch/x86/include/asm/pgtable.h:416
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134daa5)
Location: arch/x86/include/asm/pgtable.h:416
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:416
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff813431a4)
Location: arch/x86/include/asm/pgtable.h:419
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff813beccc)
Location: arch/x86/include/asm/pgtable.h:419
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c6cde)
Location: arch/x86/include/asm/pgtable.h:419
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:419
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff813bb0e5)
Location: arch/x86/include/asm/pgtable.h:436
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff81444272)
Location: arch/x86/include/asm/pgtable.h:436
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81449138)
Location: arch/x86/include/asm/pgtable.h:436
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:436
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff813efc31)
Location: arch/x86/include/asm/pgtable.h:437
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff814797ef)
Location: arch/x86/include/asm/pgtable.h:437
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147e936)
Location: arch/x86/include/asm/pgtable.h:437
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:437
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff8141b231)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff814a8cf6)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814af5ca)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff8159dae5)
Location: arch/x86/include/asm/pgtable.h:565
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
In mm/memory.c (ffffffff8125a538)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff812aad13)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b051c)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b586d)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff8136905f)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff8124c95c)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff8129c64e)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812a1cc8)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a6a7e)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff8135a30f)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff812582d8)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff812a8b23)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812ae32c)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b367d)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff81366b2f)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff81267cc4)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff812b8e43)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812be68d)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c3ae4)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff8137a185)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
</ul>

## Differences
