# Function: <code>blk_rq_trace_sector</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81175abf)
Location: include/linux/blktrace_api.h:111
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffffffff81420d4d)
Location: include/linux/blktrace_api.h:111
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (ffffffff81183137)
Location: include/linux/blktrace_api.h:117
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffffffff8144b8cb)
Location: include/linux/blktrace_api.h:117
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (ffffffff811922a2)
Location: include/linux/blktrace_api.h:117
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffffffff8147ebaa)
Location: include/linux/blktrace_api.h:117
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (ffffffff8119fb26)
Location: include/linux/blktrace_api.h:117
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffffffff8149c1fa)
Location: include/linux/blktrace_api.h:117
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (ffffffff811ad877)
Location: include/linux/blktrace_api.h:117
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffffffff814ca2f6)
Location: include/linux/blktrace_api.h:117
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (ffffffff811b90f2)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffffffff814e34d6)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (ffffffff811d23c7)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffffffff8154352d)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (ffffffff811cee8b)
Location: include/linux/blktrace_api.h:124
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffffffff8155fd7d)
Location: include/linux/blktrace_api.h:124
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (ffffffff811d061b)
Location: include/linux/blktrace_api.h:122
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffffffff81568a6d)
Location: include/linux/blktrace_api.h:122
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (ffffffff811fcf4b)
Location: include/linux/blktrace_api.h:122
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
```
In block/blk-core.c (ffffffff815cb80d)
Location: include/linux/blktrace_api.h:122
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (ffffffff8123701e)
Location: include/linux/blktrace_api.h:120
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffffffff816775dd)
Location: include/linux/blktrace_api.h:120
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (ffffffff81283d6e)
Location: include/linux/blktrace_api.h:111
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffffffff81733a6a)
Location: include/linux/blktrace_api.h:111
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (ffffffff812a0a1e)
Location: include/linux/blktrace_api.h:115
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffffffff8176fe8a)
Location: include/linux/blktrace_api.h:115
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (ffffffff812bc14e)
Location: include/linux/blktrace_api.h:115
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffffffff817b20f7)
Location: include/linux/blktrace_api.h:115
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
</details>
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
In kernel/trace/blktrace.c (ffff800010237c8c)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffff8000105e2a88)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (c04732e0)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (c078d638)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (c0000000002c36ec)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (c00000000077325c)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (ffffffe00018e60a)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffffffe000422e20)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (ffffffff811b1712)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffffffff814dbab6)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (ffffffff811a46b2)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffffffff814cc466)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (ffffffff811af4e2)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffffffff814d7b46)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
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
In kernel/trace/blktrace.c (ffffffff811bd4cd)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/blk-core.c (ffffffff814f0756)
Location: include/linux/blktrace_api.h:125
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
</details>
</li>
</ul>

## Differences
