# Function: <code>compaction_failed</code>

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
In mm/page_alloc.c (ffffffff811bb127)
Location: include/linux/compaction.h:123
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
In mm/oom_kill.c (ffffffff811bc3c5)
Location: include/linux/compaction.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff811c3002)
Location: include/linux/compaction.h:123
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
In mm/oom_kill.c (ffffffff811d0fe9)
Location: include/linux/compaction.h:124
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff811d7e2c)
Location: include/linux/compaction.h:124
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
In mm/oom_kill.c (ffffffff811f2213)
Location: include/linux/compaction.h:124
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff811f900e)
Location: include/linux/compaction.h:124
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
In mm/oom_kill.c (ffffffff81204083)
Location: include/linux/compaction.h:124
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff8120b5bd)
Location: include/linux/compaction.h:124
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
In mm/oom_kill.c (ffffffff8121b46a)
Location: include/linux/compaction.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff81271831)
Location: include/linux/compaction.h:123
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
In mm/oom_kill.c (ffffffff812285d8)
Location: include/linux/compaction.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff812806c1)
Location: include/linux/compaction.h:123
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
In mm/oom_kill.c (ffffffff81254f6e)
Location: include/linux/compaction.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff812b2e54)
Location: include/linux/compaction.h:123
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
In mm/oom_kill.c (ffffffff8125fc3e)
Location: include/linux/compaction.h:119
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff812be9b1)
Location: include/linux/compaction.h:119
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
In mm/oom_kill.c (ffffffff8126478a)
Location: include/linux/compaction.h:118
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff812c3a35)
Location: include/linux/compaction.h:118
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
In mm/oom_kill.c (ffffffff812a0faa)
Location: include/linux/compaction.h:120
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff813078ce)
Location: include/linux/compaction.h:120
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
In mm/oom_kill.c (ffffffff812f877d)
Location: include/linux/compaction.h:120
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff8136fb99)
Location: include/linux/compaction.h:120
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
In mm/oom_kill.c (ffffffff813621ca)
Location: include/linux/compaction.h:120
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff813ec1c3)
Location: include/linux/compaction.h:120
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
In mm/oom_kill.c (ffff8000102b6e20)
Location: include/linux/compaction.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffff800010318470)
Location: include/linux/compaction.h:123
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
In mm/oom_kill.c (c04e2ee4)
Location: include/linux/compaction.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (c0532c2c)
Location: include/linux/compaction.h:123
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
In mm/oom_kill.c (c00000000036d4e0)
Location: include/linux/compaction.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (c0000000003eadf0)
Location: include/linux/compaction.h:123
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
In mm/oom_kill.c (ffffffe0001da9b4)
Location: include/linux/compaction.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffe00021e4fa)
Location: include/linux/compaction.h:123
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
In mm/oom_kill.c (ffffffff81220c28)
Location: include/linux/compaction.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff81278d11)
Location: include/linux/compaction.h:123
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
In mm/oom_kill.c (ffffffff81213dd8)
Location: include/linux/compaction.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff8126ac01)
Location: include/linux/compaction.h:123
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
In mm/oom_kill.c (ffffffff8121e9c8)
Location: include/linux/compaction.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff81276ab1)
Location: include/linux/compaction.h:123
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
In mm/oom_kill.c (ffffffff8122da18)
Location: include/linux/compaction.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:trace_event_raw_event_compact_retry
```
```
In mm/page_alloc.c (ffffffff8128665c)
Location: include/linux/compaction.h:123
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
</ul>

## Differences
