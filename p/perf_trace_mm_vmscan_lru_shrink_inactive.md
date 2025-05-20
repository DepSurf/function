# Function: <code>perf_trace_mm_vmscan_lru_shrink_inactive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, int zid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, int priority, int reclaim_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a16e0)
Location: include/trace/events/vmscan.h:354
Inline: False
```
**Symbols:**

```
ffffffff811a16e0-ffffffff811a1814: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b5f80)
Location: include/trace/events/vmscan.h:364
Inline: False
```
**Symbols:**

```
ffffffff811b5f80-ffffffff811b60a0: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811c6590)
Location: include/trace/events/vmscan.h:364
Inline: False
```
**Symbols:**

```
ffffffff811c6590-ffffffff811c66ae: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, long unsigned int nr_dirty, long unsigned int nr_writeback, long unsigned int nr_congested, long unsigned int nr_immediate, long unsigned int nr_activate, long unsigned int nr_ref_keep, long unsigned int nr_unmap_fail, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811ce850)
Location: include/trace/events/vmscan.h:340
Inline: False
```
**Symbols:**

```
ffffffff811ce850-ffffffff811ce999: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, long unsigned int nr_dirty, long unsigned int nr_writeback, long unsigned int nr_congested, long unsigned int nr_immediate, long unsigned int nr_activate, long unsigned int nr_ref_keep, long unsigned int nr_unmap_fail, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e3c70)
Location: include/trace/events/vmscan.h:345
Inline: False
```
**Symbols:**

```
ffffffff811e3c70-ffffffff811e3db7: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812052b0)
Location: include/trace/events/vmscan.h:345
Inline: False
```
**Symbols:**

```
ffffffff812052b0-ffffffff81205402: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81217c80)
Location: include/trace/events/vmscan.h:345
Inline: False
```
**Symbols:**

```
ffffffff81217c80-ffffffff81217dd2: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812275b0)
Location: include/trace/events/vmscan.h:335
Inline: False
```
**Symbols:**

```
ffffffff812275b0-ffffffff812276f2: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81235450)
Location: include/trace/events/vmscan.h:335
Inline: False
```
**Symbols:**

```
ffffffff81235450-ffffffff81235592: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81262ad0)
Location: include/trace/events/vmscan.h:339
Inline: False
```
**Symbols:**

```
ffffffff81262ad0-ffffffff81262c18: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8126d460)
Location: include/trace/events/vmscan.h:339
Inline: False
```
**Symbols:**

```
ffffffff8126d460-ffffffff8126d5a8: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812721a0)
Location: include/trace/events/vmscan.h:339
Inline: False
```
**Symbols:**

```
ffffffff812721a0-ffffffff812722e8: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812af6a0)
Location: include/trace/events/vmscan.h:339
Inline: False
```
**Symbols:**

```
ffffffff812af6a0-ffffffff812af7e8: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130a070)
Location: include/trace/events/vmscan.h:353
Inline: False
```
**Symbols:**

```
ffffffff8130a070-ffffffff8130a1dd: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813741f0)
Location: include/trace/events/vmscan.h:353
Inline: False
```
**Symbols:**

```
ffffffff813741f0-ffffffff8137435a: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813a6e90)
Location: include/trace/events/vmscan.h:353
Inline: False
```
**Symbols:**

```
ffffffff813a6e90-ffffffff813a6ffa: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813d09f0)
Location: include/trace/events/vmscan.h:349
Inline: False
```
**Symbols:**

```
ffffffff813d09f0-ffffffff813d0b5a: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c7a80)
Location: include/trace/events/vmscan.h:335
Inline: False
```
**Symbols:**

```
ffff8000102c7a80-ffff8000102c7bbc: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f01fc)
Location: include/trace/events/vmscan.h:335
Inline: False
```
**Symbols:**

```
c04f01fc-c04f0348: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000380830)
Location: include/trace/events/vmscan.h:335
Inline: False
```
**Symbols:**

```
c000000000380830-c000000000380a08: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e5cd4)
Location: include/trace/events/vmscan.h:335
Inline: False
```
**Symbols:**

```
ffffffe0001e5cd4-ffffffe0001e5db8: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122daa0)
Location: include/trace/events/vmscan.h:335
Inline: False
```
**Symbols:**

```
ffffffff8122daa0-ffffffff8122dbe2: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81220b60)
Location: include/trace/events/vmscan.h:335
Inline: False
```
**Symbols:**

```
ffffffff81220b60-ffffffff81220ca2: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122b840)
Location: include/trace/events/vmscan.h:335
Inline: False
```
**Symbols:**

```
ffffffff8122b840-ffffffff8122b982: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_trace_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123ac30)
Location: include/trace/events/vmscan.h:335
Inline: False
```
**Symbols:**

```
ffffffff8123ac30-ffffffff8123ad72: perf_trace_mm_vmscan_lru_shrink_inactive (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int file</code>
</li>
<li>
<b>Param removed. </b>
<code>int zid</code>
</li>
<li>
<b>Param removed. </b>
<code>int reclaim_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, nid, zid, nr_scanned, nr_reclaimed, priority, reclaim_flags</code> ➡️ <code>__data, nid, nr_scanned, nr_reclaimed, priority, file</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int nr_dirty</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int nr_writeback</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int nr_congested</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int nr_immediate</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int nr_activate</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int nr_ref_keep</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int nr_unmap_fail</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, nid, nr_scanned, nr_reclaimed, priority, file</code> ➡️ <code>__data, nid, nr_scanned, nr_reclaimed, nr_dirty, nr_writeback, nr_congested, nr_immediate, nr_activate, nr_ref_keep, nr_unmap_fail, priority, file</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct reclaim_stat *stat</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_dirty</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_writeback</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_congested</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_immediate</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_activate</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_ref_keep</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_unmap_fail</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, nid, nr_scanned, nr_reclaimed, nr_dirty, nr_writeback, nr_congested, nr_immediate, nr_activate, nr_ref_keep, nr_unmap_fail, priority, file</code> ➡️ <code>__data, nid, nr_scanned, nr_reclaimed, stat, priority, file</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
