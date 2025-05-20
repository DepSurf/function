# Function: <code>make_readable_migration_entry</code>

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
Location: include/linux/swapops.h:205
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:205
Inline: True
```
```
In mm/rmap.c (ffffffff812f86f7)
Location: include/linux/swapops.h:205
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:205
Inline: True
```
```
In mm/migrate.c (ffffffff813402cb)
Location: include/linux/swapops.h:205
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (0)
Location: include/linux/swapops.h:205
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
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
In mm/memory.c (0)
Location: include/linux/swapops.h:228
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:228
Inline: True
```
```
In mm/rmap.c (ffffffff8135e831)
Location: include/linux/swapops.h:228
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:228
Inline: True
```
```
In mm/migrate_device.c (ffffffff813b73bb)
Location: include/linux/swapops.h:228
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1b3c)
Location: include/linux/swapops.h:228
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
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
In mm/memory.c (0)
Location: include/linux/swapops.h:274
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:274
Inline: True
```
```
In mm/rmap.c (ffffffff813d968f)
Location: include/linux/swapops.h:274
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:274
Inline: True
```
```
In mm/migrate_device.c (ffffffff81438f07)
Location: include/linux/swapops.h:274
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443bfc)
Location: include/linux/swapops.h:274
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
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
In mm/memory.c (0)
Location: include/linux/swapops.h:274
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:274
Inline: True
```
```
In mm/rmap.c (ffffffff8140df2c)
Location: include/linux/swapops.h:274
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:274
Inline: True
```
```
In mm/migrate_device.c (ffffffff8146f742)
Location: include/linux/swapops.h:274
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81479178)
Location: include/linux/swapops.h:274
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
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
In mm/memory.c (0)
Location: include/linux/swapops.h:274
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:274
Inline: True
```
```
In mm/rmap.c (ffffffff8143a705)
Location: include/linux/swapops.h:274
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:274
Inline: True
```
```
In mm/migrate_device.c (ffffffff8149e385)
Location: include/linux/swapops.h:274
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a881f)
Location: include/linux/swapops.h:274
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
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
