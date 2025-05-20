# Function: <code>folio_clear_active</code>

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
In mm/swap.c (ffffffff8130328d)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:pagevec_move_tail_fn
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
In mm/swap.c (ffffffff8137013d)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff81386db5)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/migrate.c (ffffffff81435097)
Location: include/linux/page-flags.h:481
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
In mm/swap.c (ffffffff813a22bd)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813b7245)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/mlock.c (ffffffff813f846a)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/mlock.c:__mlock_folio
```
```
In mm/migrate.c (ffffffff8146888e)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/migrate.c:migrate_folio_unmap
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
In mm/swap.c (ffffffff813cbf35)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813e00d5)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/mlock.c (ffffffff81424038)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/mlock.c:__mlock_folio
```
```
In mm/migrate.c (ffffffff81497f7f)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/migrate.c:migrate_folio_unmap
```
```
In mm/memory-failure.c (ffffffff814c4a06)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
