# Function: <code>vma_migratable</code>

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
In kernel/sched/fair.c (ffffffff810b2621)
Location: include/linux/mempolicy.h:175
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mempolicy.c (ffffffff811e13d0)
Location: include/linux/mempolicy.h:175
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
```
```
In mm/migrate.c (ffffffff811f2c3d)
Location: include/linux/mempolicy.h:175
Inline: True
Inline callers:
  - mm/migrate.c:SyS_move_pages
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
In kernel/sched/fair.c (ffffffff810b514a)
Location: include/linux/mempolicy.h:175
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mempolicy.c (ffffffff811ffd59)
Location: include/linux/mempolicy.h:175
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
```
```
In mm/migrate.c (ffffffff81212a19)
Location: include/linux/mempolicy.h:175
Inline: True
Inline callers:
  - mm/migrate.c:SyS_move_pages
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
In kernel/sched/fair.c (ffffffff810bb60a)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mempolicy.c (ffffffff81211879)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
```
```
In mm/migrate.c (ffffffff81224d06)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
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
In kernel/sched/fair.c (ffffffff810b5e39)
Location: include/linux/mempolicy.h:175
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mempolicy.c (ffffffff8121d199)
Location: include/linux/mempolicy.h:175
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
```
```
In mm/migrate.c (ffffffff812303ee)
Location: include/linux/mempolicy.h:175
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
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
In kernel/sched/fair.c (ffffffff810be6d9)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mempolicy.c (ffffffff81238389)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
```
```
In mm/migrate.c (ffffffff8124e07d)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
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
In kernel/sched/fair.c (ffffffff810c682a)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mempolicy.c (ffffffff8125b909)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
```
```
In mm/migrate.c (ffffffff81271bb8)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
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
In kernel/sched/fair.c (ffffffff810cedaa)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mempolicy.c (ffffffff812701c1)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812861d8)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
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
In kernel/sched/fair.c (ffffffff810d767a)
Location: include/linux/mempolicy.h:178
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mempolicy.c (ffffffff8128b7d1)
Location: include/linux/mempolicy.h:178
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a06b4)
Location: include/linux/mempolicy.h:178
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
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
In kernel/sched/fair.c (ffffffff810e1c8a)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mempolicy.c (ffffffff8129b341)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b1a59)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool vma_migratable(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812ce710)
Location: mm/mempolicy.c:1771
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_work
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:add_page_for_migration
```
**Symbols:**

```
ffffffff812ce710-ffffffff812ce7dd: vma_migratable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool vma_migratable(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812da050)
Location: mm/mempolicy.c:1747
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_work
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:add_page_for_migration
```
**Symbols:**

```
ffffffff812da050-ffffffff812da11d: vma_migratable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool vma_migratable(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e18b0)
Location: mm/mempolicy.c:1761
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_work
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:add_page_for_migration
```
**Symbols:**

```
ffffffff812e18b0-ffffffff812e197d: vma_migratable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool vma_migratable(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81328980)
Location: mm/mempolicy.c:1646
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_work
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:add_page_for_migration
```
**Symbols:**

```
ffffffff81328980-ffffffff81328a4d: vma_migratable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool vma_migratable(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81397bc0)
Location: mm/mempolicy.c:1710
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_work
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:add_page_for_migration
```
**Symbols:**

```
ffffffff81397bc0-ffffffff81397cb5: vma_migratable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool vma_migratable(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814177d0)
Location: mm/mempolicy.c:1725
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_work
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:add_page_for_migration
```
**Symbols:**

```
ffffffff814177d0-ffffffff814178c2: vma_migratable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool vma_migratable(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144ad60)
Location: mm/mempolicy.c:1736
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_work
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_pte_range
  - mm/migrate.c:add_page_for_migration
```
**Symbols:**

```
ffffffff8144ad60-ffffffff8144ae58: vma_migratable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool vma_migratable(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814847a0)
Location: mm/mempolicy.c:1720
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_work
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_pte_range
  - mm/mempolicy.c:queue_folios_pmd
  - mm/migrate.c:add_page_for_migration
```
**Symbols:**

```
ffffffff814847a0-ffffffff81484898: vma_migratable (STB_GLOBAL)
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
In kernel/sched/fair.c (ffff800010142bac)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mempolicy.c (ffff80001033a1e4)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffff8000103521a4)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
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
In kernel/sched/fair.c (c00000000019295c)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mempolicy.c (c000000000414870)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (c0000000004389e4)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
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
In kernel/sched/fair.c (ffffffff810dbe3a)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mempolicy.c (ffffffff81293921)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812aa039)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
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
In kernel/sched/fair.c (ffffffff810cae4a)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mempolicy.c (ffffffff81285531)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8129b999)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
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
In kernel/sched/fair.c (ffffffff810d81ba)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mempolicy.c (ffffffff81291731)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a7e49)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
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
In kernel/sched/fair.c (ffffffff810e3c69)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mempolicy.c (ffffffff812a1541)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b8149)
Location: include/linux/mempolicy.h:176
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
