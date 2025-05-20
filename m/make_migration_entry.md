# Function: <code>make_migration_entry</code>

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
In mm/rmap.c (ffffffff811cb336)
Location: include/linux/swapops.h:104
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In mm/rmap.c (ffffffff811e86bb)
Location: include/linux/swapops.h:104
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/huge_memory.c (ffffffff81216297)
Location: include/linux/swapops.h:104
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/rmap.c (ffffffff811f9970)
Location: include/linux/swapops.h:104
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/huge_memory.c (ffffffff81228843)
Location: include/linux/swapops.h:104
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/rmap.c (ffffffff8120453d)
Location: include/linux/swapops.h:104
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/huge_memory.c (ffffffff81231e6c)
Location: include/linux/swapops.h:104
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff8121d532)
Location: include/linux/swapops.h:183
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff8124b3ff)
Location: include/linux/swapops.h:183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812559c9)
Location: include/linux/swapops.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/rmap.c (ffffffff8123f518)
Location: include/linux/swapops.h:183
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff8126e3d8)
Location: include/linux/swapops.h:183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81279889)
Location: include/linux/swapops.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/rmap.c (ffffffff81253c1d)
Location: include/linux/swapops.h:179
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff81283266)
Location: include/linux/swapops.h:179
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8128debf)
Location: include/linux/swapops.h:179
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff81265e41)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/huge_memory.c (ffffffff812a8840)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff8127476e)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812ae9c9)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812b9dc0)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff812a5ac7)
Location: include/linux/swapops.h:166
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812e4102)
Location: include/linux/swapops.h:166
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812ee96f)
Location: include/linux/swapops.h:166
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff812b0f42)
Location: include/linux/swapops.h:166
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812f0137)
Location: include/linux/swapops.h:166
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812f9fdf)
Location: include/linux/swapops.h:166
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff812b650a)
Location: include/linux/swapops.h:173
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812f5814)
Location: include/linux/swapops.h:173
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81300d8b)
Location: include/linux/swapops.h:173
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/rmap.c (ffff80001030a070)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/huge_memory.c (ffff800010356064)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0526758)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
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
In mm/rmap.c (c0000000003d9e20)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (c000000000434cec)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (c0000000004441ac)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffe000213f64)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
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
In mm/rmap.c (ffffffff8126cdbe)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812a6fa9)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812b23a0)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff8125edfa)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812989e5)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812a3730)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff8126ab5e)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812a4db9)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812b01b0)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff8127a4c7)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812b5915)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812c04f0)
Location: include/linux/swapops.h:164
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
</ul>

## Differences
