# Function: <code>lru_gen_enabled</code>

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
In mm/swap.c (ffffffff81370f3f)
Location: include/linux/mm_inline.h:112
Inline: True
Inline callers:
  - mm/swap.c:deactivate_page
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff8138561e)
Location: include/linux/mm_inline.h:112
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:lru_gen_init_lruvec
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/workingset.c (ffffffff813ad5df)
Location: include/linux/mm_inline.h:112
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff813d5db3)
Location: include/linux/mm_inline.h:112
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced_one
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
In mm/swap.c (ffffffff813a3105)
Location: include/linux/mm_inline.h:105
Inline: True
Inline callers:
  - mm/swap.c:folio_deactivate
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff813b88fe)
Location: include/linux/mm_inline.h:105
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:lru_gen_init_lruvec
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/workingset.c (ffffffff813e1c92)
Location: include/linux/mm_inline.h:105
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8140aee4)
Location: include/linux/mm_inline.h:105
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced_one
```
```
In mm/memcontrol.c (ffffffff8148f990)
Location: include/linux/mm_inline.h:105
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_check_events
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
In mm/swap.c (ffffffff813ccd7f)
Location: include/linux/mm_inline.h:106
Inline: True
Inline callers:
  - mm/swap.c:folio_deactivate
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff813e18fe)
Location: include/linux/mm_inline.h:106
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:lru_gen_init_lruvec
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/workingset.c (ffffffff8140c4dc)
Location: include/linux/mm_inline.h:106
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8143768e)
Location: include/linux/mm_inline.h:106
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced_one
```
```
In mm/memcontrol.c (ffffffff814bf1c0)
Location: include/linux/mm_inline.h:106
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_check_events
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
