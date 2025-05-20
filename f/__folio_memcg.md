# Function: <code>__folio_memcg</code>

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
In mm/page-writeback.c (0)
Location: include/linux/memcontrol.h:399
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/memcontrol.h:399
Inline: True
```
```
In mm/vmscan.c (ffffffff8130e426)
Location: include/linux/memcontrol.h:399
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (0)
Location: include/linux/memcontrol.h:399
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/memcontrol.h:399
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/memcontrol.h:399
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/memcontrol.h:399
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/memcontrol.h:399
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/memcontrol.h:399
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/memcontrol.h:399
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/memcontrol.h:399
Inline: True
```
```
In mm/memcontrol.c (ffffffff813d3926)
Location: include/linux/memcontrol.h:399
Inline: True
Inline callers:
  - mm/memcontrol.c:get_obj_cgroup_from_page
```
```
In fs/fs-writeback.c (ffffffff81431230)
Location: include/linux/memcontrol.h:399
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
```
```
In fs/buffer.c (0)
Location: include/linux/memcontrol.h:399
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
In mm/page-writeback.c (0)
Location: include/linux/memcontrol.h:375
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/memcontrol.h:375
Inline: True
```
```
In mm/vmscan.c (ffffffff81380254)
Location: include/linux/memcontrol.h:375
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/compaction.c (0)
Location: include/linux/memcontrol.h:375
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/memcontrol.h:375
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/memcontrol.h:375
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/memcontrol.h:375
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/memcontrol.h:375
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/memcontrol.h:375
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/memcontrol.h:375
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/memcontrol.h:375
Inline: True
```
```
In mm/memcontrol.c (ffffffff814592b9)
Location: include/linux/memcontrol.h:375
Inline: True
Inline callers:
  - mm/memcontrol.c:get_obj_cgroup_from_page
```
```
In fs/fs-writeback.c (ffffffff814befbd)
Location: include/linux/memcontrol.h:375
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
```
```
In fs/buffer.c (0)
Location: include/linux/memcontrol.h:375
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
In mm/page-writeback.c (0)
Location: include/linux/memcontrol.h:381
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/memcontrol.h:381
Inline: True
```
```
In mm/vmscan.c (ffffffff813b172c)
Location: include/linux/memcontrol.h:381
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/compaction.c (0)
Location: include/linux/memcontrol.h:381
Inline: True
```
```
In mm/workingset.c (ffffffff813e129e)
Location: include/linux/memcontrol.h:381
Inline: True
Inline callers:
  - mm/workingset.c:lru_gen_refault
```
```
In mm/mlock.c (0)
Location: include/linux/memcontrol.h:381
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/memcontrol.h:381
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/memcontrol.h:381
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/memcontrol.h:381
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/memcontrol.h:381
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/memcontrol.h:381
Inline: True
```
```
In mm/memcontrol.c (ffffffff8148ef4d)
Location: include/linux/memcontrol.h:381
Inline: True
Inline callers:
  - mm/memcontrol.c:get_obj_cgroup_from_page
```
```
In fs/fs-writeback.c (ffffffff814f40d5)
Location: include/linux/memcontrol.h:381
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
```
```
In fs/buffer.c (0)
Location: include/linux/memcontrol.h:381
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
In mm/page-writeback.c (0)
Location: include/linux/memcontrol.h:385
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/memcontrol.h:385
Inline: True
```
```
In mm/vmscan.c (ffffffff813daca9)
Location: include/linux/memcontrol.h:385
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/compaction.c (0)
Location: include/linux/memcontrol.h:385
Inline: True
```
```
In mm/workingset.c (ffffffff8140bb5b)
Location: include/linux/memcontrol.h:385
Inline: True
Inline callers:
  - mm/workingset.c:lru_gen_refault
```
```
In mm/mlock.c (0)
Location: include/linux/memcontrol.h:385
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/memcontrol.h:385
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/memcontrol.h:385
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/memcontrol.h:385
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/memcontrol.h:385
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/memcontrol.h:385
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/memcontrol.h:385
Inline: True
```
```
In mm/memcontrol.c (ffffffff814be83e)
Location: include/linux/memcontrol.h:385
Inline: True
Inline callers:
  - mm/memcontrol.c:get_obj_cgroup_from_folio
  - mm/memcontrol.c:__lruvec_stat_mod_folio
```
```
In fs/fs-writeback.c (ffffffff815287e5)
Location: include/linux/memcontrol.h:385
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
```
```
In fs/buffer.c (0)
Location: include/linux/memcontrol.h:385
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
