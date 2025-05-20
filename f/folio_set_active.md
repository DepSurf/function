# Function: <code>folio_set_active</code>

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
In mm/swap.c (ffffffff81305b8e)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:__folio_activate
```
```
In mm/vmscan.c (ffffffff8130e40c)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/workingset.c (ffffffff813364c8)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff813a6347)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff813b08d5)
Location: include/linux/page-flags.h:502
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
In mm/swap.c (ffffffff8136fba0)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff8138023a)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/workingset.c (ffffffff813ad749)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff8142789d)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff81431449)
Location: include/linux/page-flags.h:481
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
In mm/swap.c (ffffffff813a1d0c)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff813b1717)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/workingset.c (ffffffff813e1d66)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff8145ce0a)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff81466dc9)
Location: include/linux/page-flags.h:475
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
In mm/swap.c (ffffffff813cb999)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff813dac94)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/workingset.c (ffffffff8140c5a1)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff81457523)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff81496029)
Location: include/linux/page-flags.h:477
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
