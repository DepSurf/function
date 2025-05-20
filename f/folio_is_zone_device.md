# Function: <code>folio_is_zone_device</code>

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
In mm/rmap.c (ffffffff8135f556)
Location: include/linux/mm.h:1120
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/migrate.c (0)
Location: include/linux/mm.h:1120
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
In mm/swap.c (ffffffff8136f559)
Location: include/linux/mmzone.h:1022
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__folio_put
```
```
In mm/rmap.c (ffffffff813da396)
Location: include/linux/mmzone.h:1022
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/migrate.c (0)
Location: include/linux/mmzone.h:1022
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
In mm/swap.c (ffffffff813a1679)
Location: include/linux/mmzone.h:1133
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__folio_put
```
```
In mm/mlock.c (ffffffff813f9690)
Location: include/linux/mmzone.h:1133
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/rmap.c (ffffffff8140ead6)
Location: include/linux/mmzone.h:1133
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/madvise.c (ffffffff814278b3)
Location: include/linux/mmzone.h:1133
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff8144b67b)
Location: include/linux/mmzone.h:1133
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/migrate.c (0)
Location: include/linux/mmzone.h:1133
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
In mm/swap.c (ffffffff813cb2f9)
Location: include/linux/mmzone.h:1143
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__folio_put
```
```
In mm/memory.c (ffffffff8141be92)
Location: include/linux/mmzone.h:1143
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (ffffffff8142523b)
Location: include/linux/mmzone.h:1143
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff8142ef61)
Location: include/linux/mmzone.h:1143
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8143b496)
Location: include/linux/mmzone.h:1143
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/madvise.c (ffffffff81461091)
Location: include/linux/mmzone.h:1143
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81485082)
Location: include/linux/mmzone.h:1143
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/migrate.c (ffffffff814973fd)
Location: include/linux/mmzone.h:1143
Inline: True
Inline callers:
  - mm/migrate.c:add_page_for_migration
```
```
In mm/migrate_device.c (ffffffff8149d379)
Location: include/linux/mmzone.h:1143
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
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
