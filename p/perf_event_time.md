# Function: <code>perf_event_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811784e5)
Location: kernel/events/core.c:1140
Inline: True
Inline callers:
  - kernel/events/core.c:update_event_times
  - kernel/events/core.c:__perf_event_mark_enabled
  - kernel/events/core.c:add_event_to_ctx
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118f02a)
Location: kernel/events/core.c:1389
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_mark_enabled
  - kernel/events/core.c:add_event_to_ctx
  - kernel/events/core.c:update_event_times
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119e5ce)
Location: kernel/events/core.c:1397
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_mark_enabled
  - kernel/events/core.c:add_event_to_ctx
  - kernel/events/core.c:update_event_times
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a6b90)
Location: kernel/events/core.c:1389
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_mark_enabled
  - kernel/events/core.c:add_event_to_ctx
  - kernel/events/core.c:update_event_times
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b71bf)
Location: kernel/events/core.c:1437
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_update_time
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d7412)
Location: kernel/events/core.c:1460
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_update_time
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e7842)
Location: kernel/events/core.c:1460
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_update_time
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ff082)
Location: kernel/events/core.c:1462
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_update_time
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120bef2)
Location: kernel/events/core.c:1462
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_update_time
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
In kernel/events/core.c (ffffffff81231554)
Location: kernel/events/core.c:1524
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
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
In kernel/events/core.c (ffffffff8123b1c4)
Location: kernel/events/core.c:1542
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
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
In kernel/events/core.c (ffffffff8123f98b)
Location: kernel/events/core.c:1540
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
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
In kernel/events/core.c (ffffffff8127a1d8)
Location: kernel/events/core.c:1588
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_update_time
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cd72d)
Location: kernel/events/core.c:1497
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_update_time
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
In kernel/events/core.c (ffffffff81335efd)
Location: kernel/events/core.c:1472
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_update_time
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81366c4d)
Location: kernel/events/core.c:1472
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_update_time
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138fbad)
Location: kernel/events/core.c:1483
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_update_time
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
In kernel/events/core.c (ffff800010298030)
Location: kernel/events/core.c:1462
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_update_time
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
In kernel/events/core.c (c04c216c)
Location: kernel/events/core.c:1462
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_update_time
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
In kernel/events/core.c (c00000000033f348)
Location: kernel/events/core.c:1462
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_update_time
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
In kernel/events/core.c (ffffffe0001c3e3e)
Location: kernel/events/core.c:1462
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_update_time
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
In kernel/events/core.c (ffffffff81204512)
Location: kernel/events/core.c:1462
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_update_time
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
In kernel/events/core.c (ffffffff811f72a2)
Location: kernel/events/core.c:1462
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_update_time
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
In kernel/events/core.c (ffffffff812022e2)
Location: kernel/events/core.c:1462
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_update_time
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
In kernel/events/core.c (ffffffff81211b32)
Location: kernel/events/core.c:1462
Inline: True
Inline callers:
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_update_time
```
</details>
</li>
</ul>

## Differences
