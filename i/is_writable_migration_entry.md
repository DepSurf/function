# Function: <code>is_writable_migration_entry</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/linux/swapops.h:200
Inline: True
```
```
In mm/mprotect.c (ffffffff812f07c6)
Location: include/linux/swapops.h:200
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff81323551)
Location: include/linux/swapops.h:200
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff8133e943)
Location: include/linux/swapops.h:200
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8134ac92)
Location: include/linux/swapops.h:200
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:change_huge_pmd
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
In mm/mprotect.c (ffffffff81353e79)
Location: include/linux/swapops.h:213
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/migrate.c (ffffffff813b1a39)
Location: include/linux/swapops.h:213
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff813c1e21)
Location: include/linux/swapops.h:213
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
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
In mm/mprotect.c (ffffffff813ce323)
Location: include/linux/swapops.h:259
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:259
Inline: True
```
```
In mm/migrate.c (ffffffff814324d4)
Location: include/linux/swapops.h:259
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81444044)
Location: include/linux/swapops.h:259
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/mprotect.c (ffffffff81402c00)
Location: include/linux/swapops.h:259
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:259
Inline: True
```
```
In mm/migrate.c (ffffffff81467c44)
Location: include/linux/swapops.h:259
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8147958d)
Location: include/linux/swapops.h:259
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/mprotect.c (ffffffff8142f213)
Location: include/linux/swapops.h:259
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:259
Inline: True
```
```
In mm/migrate.c (ffffffff81497917)
Location: include/linux/swapops.h:259
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff814a8b1b)
Location: include/linux/swapops.h:259
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
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
