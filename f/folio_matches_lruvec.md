# Function: <code>folio_matches_lruvec</code>

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
In mm/swap.c (ffffffff81306e84)
Location: include/linux/memcontrol.h:1590
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff8130f3fe)
Location: include/linux/memcontrol.h:1590
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/mlock.c (ffffffff8134a94f)
Location: include/linux/memcontrol.h:1590
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
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
In mm/swap.c (ffffffff8136f6a0)
Location: include/linux/memcontrol.h:1621
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:folio_batch_move_lru
```
```
In mm/vmscan.c (ffffffff8137e716)
Location: include/linux/memcontrol.h:1621
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
```
```
In mm/mlock.c (ffffffff813c353f)
Location: include/linux/memcontrol.h:1621
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
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
In mm/swap.c (ffffffff813a17c0)
Location: include/linux/memcontrol.h:1638
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:folio_batch_move_lru
```
```
In mm/vmscan.c (ffffffff813afe00)
Location: include/linux/memcontrol.h:1638
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
```
```
In mm/mlock.c (ffffffff813f8afe)
Location: include/linux/memcontrol.h:1638
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
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
In mm/swap.c (ffffffff813cb441)
Location: include/linux/memcontrol.h:1676
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:folio_batch_move_lru
```
```
In mm/vmscan.c (ffffffff813d92ed)
Location: include/linux/memcontrol.h:1676
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
```
```
In mm/mlock.c (ffffffff814246bb)
Location: include/linux/memcontrol.h:1676
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
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
