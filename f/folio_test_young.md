# Function: <code>folio_test_young</code>

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
In mm/migrate.c (ffffffff813b0915)
Location: include/linux/page-flags.h:611
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff813b9bd7)
Location: include/linux/page-flags.h:611
Inline: True
```
```
In mm/khugepaged.c (ffffffff813c74f6)
Location: include/linux/page-flags.h:611
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff81499eaa)
Location: include/linux/page-flags.h:611
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffff81431489)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff8143c67f)
Location: include/linux/page-flags.h:590
Inline: True
```
```
In mm/khugepaged.c (ffffffff8144b4a3)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff8152e0e5)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffff81466e09)
Location: include/linux/page-flags.h:584
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff81471cc6)
Location: include/linux/page-flags.h:584
Inline: True
```
```
In mm/khugepaged.c (ffffffff8147f227)
Location: include/linux/page-flags.h:584
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff815664b5)
Location: include/linux/page-flags.h:584
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffff8149606c)
Location: include/linux/page-flags.h:586
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff814a2440)
Location: include/linux/page-flags.h:586
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff814afa92)
Location: include/linux/page-flags.h:586
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff8159e512)
Location: include/linux/page-flags.h:586
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
