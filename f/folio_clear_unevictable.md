# Function: <code>folio_clear_unevictable</code>

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
In mm/vmscan.c (ffffffff8137e88c)
Location: include/linux/page-flags.h:556
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
```
```
In mm/migrate.c (ffffffff8143509b)
Location: include/linux/page-flags.h:556
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
In mm/vmscan.c (ffffffff813aff73)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
```
```
In mm/mlock.c (ffffffff813f8c8e)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/migrate.c (ffffffff81468892)
Location: include/linux/page-flags.h:550
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
In mm/vmscan.c (ffffffff813d945e)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
```
```
In mm/mlock.c (ffffffff81424849)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/migrate.c (ffffffff81497f84)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/migrate.c:migrate_folio_unmap
```
```
In mm/memory-failure.c (ffffffff814c4a0b)
Location: include/linux/page-flags.h:552
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
