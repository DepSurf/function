# Function: <code>lru_gen_from_seq</code>

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
In mm/swap.c (ffffffff8136d996)
Location: include/linux/mm_inline.h:125
Inline: True
Inline callers:
  - mm/swap.c:lru_gen_add_folio
  - mm/swap.c:lru_gen_add_folio
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff8137ed93)
Location: include/linux/mm_inline.h:125
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:should_run_aging
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:reset_batch_size
  - mm/vmscan.c:reset_batch_size
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:lru_gen_add_folio
  - mm/vmscan.c:lru_gen_add_folio
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/compaction.c (ffffffff813a54cf)
Location: include/linux/mm_inline.h:125
Inline: True
```
```
In mm/mlock.c (ffffffff813c1fcf)
Location: include/linux/mm_inline.h:125
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
In mm/swap.c (ffffffff8139fbda)
Location: include/linux/mm_inline.h:125
Inline: True
Inline callers:
  - mm/swap.c:lru_gen_add_folio
  - mm/swap.c:lru_gen_add_folio
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff813b0343)
Location: include/linux/mm_inline.h:125
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:try_to_shrink_lruvec
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:lruvec_is_sizable
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:reset_batch_size
  - mm/vmscan.c:reset_batch_size
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:lru_gen_add_folio
  - mm/vmscan.c:lru_gen_add_folio
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/compaction.c (ffffffff813d8b1f)
Location: include/linux/mm_inline.h:125
Inline: True
```
```
In mm/mlock.c (ffffffff813f691f)
Location: include/linux/mm_inline.h:125
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
In mm/swap.c (ffffffff813c983c)
Location: include/linux/mm_inline.h:126
Inline: True
Inline callers:
  - mm/swap.c:lru_gen_add_folio
  - mm/swap.c:lru_gen_add_folio
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff813d9833)
Location: include/linux/mm_inline.h:126
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:try_to_shrink_lruvec
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:lruvec_is_sizable
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:reset_batch_size
  - mm/vmscan.c:reset_batch_size
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:lru_gen_add_folio
  - mm/vmscan.c:lru_gen_add_folio
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/compaction.c (ffffffff8140289f)
Location: include/linux/mm_inline.h:126
Inline: True
```
```
In mm/mlock.c (ffffffff81422aff)
Location: include/linux/mm_inline.h:126
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
