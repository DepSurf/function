# Function: <code>__page_memcg</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

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
In mm/vmscan.c (0)
Location: include/linux/memcontrol.h:399
Inline: True
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
In mm/page_io.c (ffffffff812ca679)
Location: include/linux/memcontrol.h:399
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
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
In mm/memcontrol.c (ffffffff81308c47)
Location: include/linux/memcontrol.h:399
Inline: True
Inline callers:
  - mm/memcontrol.c:lock_page_memcg
  - mm/memcontrol.c:__mod_lruvec_page_state
```
```
In fs/fs-writeback.c (ffffffff8135c597)
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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (0)
Location: include/linux/memcontrol.h:397
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/memcontrol.h:397
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/memcontrol.h:397
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/memcontrol.h:397
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/memcontrol.h:397
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/memcontrol.h:397
Inline: True
```
```
In mm/page_io.c (ffffffff8130f676)
Location: include/linux/memcontrol.h:397
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In mm/migrate.c (0)
Location: include/linux/memcontrol.h:397
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/memcontrol.h:397
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/memcontrol.h:397
Inline: True
```
```
In mm/memcontrol.c (ffffffff813529c4)
Location: include/linux/memcontrol.h:397
Inline: True
Inline callers:
  - mm/memcontrol.c:lock_page_memcg
  - mm/memcontrol.c:__mod_lruvec_page_state
```
```
In fs/fs-writeback.c (ffffffff813aaa37)
Location: include/linux/memcontrol.h:397
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
```
```
In fs/buffer.c (0)
Location: include/linux/memcontrol.h:397
Inline: True
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
