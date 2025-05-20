# Function: <code>__folio_test_movable</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8138699c)
Location: include/linux/page-flags.h:664
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff81434f86)
Location: include/linux/page-flags.h:664
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
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
In mm/vmscan.c (ffffffff813b6e2c)
Location: include/linux/page-flags.h:658
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff81467fd5)
Location: include/linux/page-flags.h:658
Inline: True
Inline callers:
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
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
In mm/vmscan.c (ffffffff813dfcf7)
Location: include/linux/page-flags.h:660
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff81499ac9)
Location: include/linux/page-flags.h:660
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffffffff814c6438)
Location: include/linux/page-flags.h:660
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
```
```
In mm/page_isolation.c (ffffffff814c9c3b)
Location: include/linux/page-flags.h:660
Inline: True
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
