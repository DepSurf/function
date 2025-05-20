# Function: <code>trace_event_get_offsets_iocg_inuse_update</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815116e5)
Location: include/trace/events/iocost.h:65
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:trace_event_raw_event_iocg_inuse_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81572708)
Location: include/trace/events/iocost.h:65
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:trace_event_raw_event_iocg_inuse_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158e048)
Location: include/trace/events/iocost.h:76
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:trace_event_raw_event_iocg_inuse_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81594da8)
Location: include/trace/events/iocost.h:76
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:trace_event_raw_event_iocg_inuse_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815fc718)
Location: include/trace/events/iocost.h:76
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:trace_event_raw_event_iocg_inuse_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (ffffffff816ad340)
Location: include/trace/events/iocost.h:76
Inline: True
Direct callers:
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:trace_event_raw_event_iocg_inuse_update
```
**Symbols:**

```
ffffffff816ad340-ffffffff816ad40c: trace_event_get_offsets_iocg_inuse_update.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8176be19)
Location: include/trace/events/iocost.h:76
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:trace_event_raw_event_iocg_inuse_update
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (ffffffff817ab680)
Location: include/trace/events/iocost.h:76
Inline: True
Direct callers:
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:trace_event_raw_event_iocg_inuse_update
```
**Symbols:**

```
ffffffff817ab680-ffffffff817ab752: trace_event_get_offsets_iocg_inuse_update.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (ffffffff817ef430)
Location: include/trace/events/iocost.h:76
Inline: True
Direct callers:
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:trace_event_raw_event_iocg_inuse_update
```
**Symbols:**

```
ffffffff817ef430-ffffffff817ef502: trace_event_get_offsets_iocg_inuse_update.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010614df8)
Location: include/trace/events/iocost.h:65
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:trace_event_raw_event_iocg_inuse_update
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07c0da4)
Location: include/trace/events/iocost.h:65
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:trace_event_raw_event_iocg_inuse_update
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b507c)
Location: include/trace/events/iocost.h:65
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:trace_event_raw_event_iocg_inuse_update
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044bf6c)
Location: include/trace/events/iocost.h:65
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:trace_event_raw_event_iocg_inuse_update
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81509cc5)
Location: include/trace/events/iocost.h:65
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:trace_event_raw_event_iocg_inuse_update
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814fa225)
Location: include/trace/events/iocost.h:65
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:trace_event_raw_event_iocg_inuse_update
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81505d55)
Location: include/trace/events/iocost.h:65
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:trace_event_raw_event_iocg_inuse_update
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815215f5)
Location: include/trace/events/iocost.h:65
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:trace_event_raw_event_iocg_inuse_update
```
</details>
</li>
</ul>

## Differences
