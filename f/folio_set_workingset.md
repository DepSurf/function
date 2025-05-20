# Function: <code>folio_set_workingset</code>

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
In mm/workingset.c (ffffffff81336653)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/migrate.c (ffffffff813b08e2)
Location: include/linux/page-flags.h:504
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
In mm/swap.c (ffffffff81370a82)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff8137deac)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/workingset.c (ffffffff813ad8af)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:lru_gen_refault
```
```
In mm/migrate.c (ffffffff81431456)
Location: include/linux/page-flags.h:483
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
In mm/swap.c (ffffffff813a2c5c)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff813af8e9)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/workingset.c (ffffffff813e1dc3)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:lru_gen_refault
```
```
In mm/migrate.c (ffffffff81466dd6)
Location: include/linux/page-flags.h:477
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
In mm/swap.c (ffffffff813cc8de)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff813d9001)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/workingset.c (ffffffff8140c5db)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/madvise.c (ffffffff81461cd4)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff81496038)
Location: include/linux/page-flags.h:479
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
