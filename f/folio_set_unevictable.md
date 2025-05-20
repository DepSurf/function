# Function: <code>folio_set_unevictable</code>

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
In mm/swap.c (ffffffff81303292)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/migrate.c (ffffffff813b09c5)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
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
In mm/swap.c (ffffffff8136ea88)
Location: include/linux/page-flags.h:556
Inline: True
Inline callers:
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff8137b6c2)
Location: include/linux/page-flags.h:556
Inline: True
Inline callers:
  - mm/vmscan.c:sort_folio
```
```
In mm/migrate.c (ffffffff81431552)
Location: include/linux/page-flags.h:556
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
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
In mm/swap.c (ffffffff813a0bb5)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813ad953)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/vmscan.c:sort_folio
```
```
In mm/mlock.c (ffffffff813f79d5)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/migrate.c (ffffffff81466ed2)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
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
In mm/swap.c (ffffffff813ca833)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813d6d63)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/vmscan.c:sort_folio
```
```
In mm/mlock.c (ffffffff814235b5)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/migrate.c (ffffffff81496145)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
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
