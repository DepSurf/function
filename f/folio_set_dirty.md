# Function: <code>folio_set_dirty</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b090f)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
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
In mm/swapfile.c (ffffffff813fe69a)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/swapfile.c:folio_free_swap
```
```
In mm/migrate.c (ffffffff81431483)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
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
In mm/swapfile.c (ffffffff814315e8)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/swapfile.c:folio_free_swap
```
```
In mm/migrate.c (ffffffff81466e03)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
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
In mm/swapfile.c (ffffffff8146a9d4)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/swapfile.c:folio_free_swap
```
```
In mm/ksm.c (ffffffff814929c1)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81496066)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814a19cf)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
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
