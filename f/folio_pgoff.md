# Function: <code>folio_pgoff</code>

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
In kernel/events/uprobes.c (ffffffff812e5e1d)
Location: include/linux/pagemap.h:838
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff8135bad1)
Location: include/linux/pagemap.h:838
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/migrate.c (ffffffff813b194e)
Location: include/linux/pagemap.h:838
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/page_idle.c (ffffffff813e635c)
Location: include/linux/pagemap.h:838
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
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
In kernel/events/uprobes.c (ffffffff8134fa7f)
Location: include/linux/pagemap.h:834
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff813d6791)
Location: include/linux/pagemap.h:834
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/migrate.c (ffffffff814323a9)
Location: include/linux/pagemap.h:834
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/page_idle.c (ffffffff8146de47)
Location: include/linux/pagemap.h:834
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
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
In kernel/events/uprobes.c (ffffffff81380c4e)
Location: include/linux/pagemap.h:855
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8138cab4)
Location: include/linux/pagemap.h:855
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
```
```
In mm/rmap.c (ffffffff8140b701)
Location: include/linux/pagemap.h:855
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/migrate.c (ffffffff81467b09)
Location: include/linux/pagemap.h:855
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/page_idle.c (ffffffff814a2947)
Location: include/linux/pagemap.h:855
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
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
In kernel/events/uprobes.c (ffffffff813aa028)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/mlock.c (ffffffff8142545d)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/rmap.c (ffffffff81437ff1)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/migrate.c (ffffffff814977d1)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/page_idle.c (ffffffff814d37f1)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
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
