# Function: <code>compaction_withdrawn</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bb235)
Location: include/linux/compaction.h:136
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811bc3e4)
Location: include/linux/compaction.h:136
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff811c3600)
Location: include/linux/compaction.h:136
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811d1008)
Location: include/linux/compaction.h:137
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff811d83d8)
Location: include/linux/compaction.h:137
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811f221e)
Location: include/linux/compaction.h:137
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff811f9017)
Location: include/linux/compaction.h:137
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8120408e)
Location: include/linux/compaction.h:137
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff8120b5c6)
Location: include/linux/compaction.h:137
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121b46c)
Location: include/linux/compaction.h:136
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff8127183a)
Location: include/linux/compaction.h:136
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812285da)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff812806d5)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81254f73)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff812b2e66)
Location: include/linux/compaction.h:150
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8125fc43)
Location: include/linux/compaction.h:146
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff812be9c3)
Location: include/linux/compaction.h:146
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (0)
Location: include/linux/compaction.h:145
Inline: True
```
```
In mm/page_alloc.c (ffffffff812c3a47)
Location: include/linux/compaction.h:145
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
In mm/oom_kill.c (0)
Location: include/linux/compaction.h:147
Inline: True
```
```
In mm/page_alloc.c (ffffffff813078e0)
Location: include/linux/compaction.h:147
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812f8782)
Location: include/linux/compaction.h:147
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff8136fbab)
Location: include/linux/compaction.h:147
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
In mm/oom_kill.c (ffffffff813621cf)
Location: include/linux/compaction.h:147
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff813ec1d5)
Location: include/linux/compaction.h:147
Inline: True
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffff8000102b6e24)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffff800010318480)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c04e2ee8)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (c0532c3c)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c00000000036d4e4)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (c0000000003eae00)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffe0001da9bc)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffe00021e506)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81220c2a)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff81278d25)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81213dda)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff8126ac15)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121e9ca)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff81276ac5)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122da1a)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff81286670)
Location: include/linux/compaction.h:150
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
</ul>

## Differences
