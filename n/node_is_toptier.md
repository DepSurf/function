# Function: <code>node_is_toptier</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff813540a1)
Location: include/linux/node.h:188
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/migrate.c (ffffffff813b60b0)
Location: include/linux/node.h:188
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff813bdc1d)
Location: include/linux/node.h:188
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool node_is_toptier(int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-tiers.c (ffffffff81437790)
Location: mm/memory-tiers.c:242
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - mm/memory.c:do_numa_page
  - mm/mprotect.c:change_pte_range
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81437790-ffffffff814377ea: node_is_toptier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool node_is_toptier(int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-tiers.c (ffffffff8146d450)
Location: mm/memory-tiers.c:242
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - mm/memory.c:do_numa_page
  - mm/mprotect.c:change_pte_range
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff8146d450-ffffffff8146d4aa: node_is_toptier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool node_is_toptier(int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-tiers.c (ffffffff8149c5c0)
Location: mm/memory-tiers.c:250
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - mm/memory.c:do_numa_page
  - mm/mprotect.c:change_pte_range
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff8149c5c0-ffffffff8149c61a: node_is_toptier (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
