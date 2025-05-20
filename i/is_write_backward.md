# Function: <code>is_write_backward</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811934ff)
Location: include/linux/perf_event.h:1196
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
```
```
In kernel/events/ring_buffer.c (ffffffff811976a0)
Location: include/linux/perf_event.h:1196
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a2cdf)
Location: include/linux/perf_event.h:1219
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
```
```
In kernel/events/ring_buffer.c (ffffffff811a7090)
Location: include/linux/perf_event.h:1219
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffff811aa2e5)
Location: include/linux/perf_event.h:1215
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
```
```
In kernel/events/ring_buffer.c (ffffffff811ae83a)
Location: include/linux/perf_event.h:1215
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffff811bdbd5)
Location: include/linux/perf_event.h:1205
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
```
```
In kernel/events/ring_buffer.c (ffffffff811c24aa)
Location: include/linux/perf_event.h:1205
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffff811dde13)
Location: include/linux/perf_event.h:1233
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff811e284f)
Location: include/linux/perf_event.h:1233
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffff811ee213)
Location: include/linux/perf_event.h:1238
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff811f2cbf)
Location: include/linux/perf_event.h:1238
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffff81205c54)
Location: include/linux/perf_event.h:1281
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8120a993)
Location: include/linux/perf_event.h:1281
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffff81212fe4)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff81217c73)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffff8123a9ac)
Location: include/linux/perf_event.h:1364
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff81243619)
Location: include/linux/perf_event.h:1364
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffff81243dd7)
Location: include/linux/perf_event.h:1380
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8124dc9b)
Location: include/linux/perf_event.h:1380
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffff81248a97)
Location: include/linux/perf_event.h:1381
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff812525db)
Location: include/linux/perf_event.h:1381
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffff8128389b)
Location: include/linux/perf_event.h:1386
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8128de8b)
Location: include/linux/perf_event.h:1386
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffff812d68ca)
Location: include/linux/perf_event.h:1428
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff812e2d1c)
Location: include/linux/perf_event.h:1428
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffff8133f697)
Location: include/linux/perf_event.h:1527
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8134b36c)
Location: include/linux/perf_event.h:1527
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffff813707c3)
Location: include/linux/perf_event.h:1640
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8137c3bc)
Location: include/linux/perf_event.h:1640
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffff81399ac3)
Location: include/linux/perf_event.h:1682
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff813a560c)
Location: include/linux/perf_event.h:1682
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffff80001029d3ac)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (ffff8000102a26a0)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (c04ccb2c)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (c04d220c)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (c00000000034de50)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
```
```
In kernel/events/ring_buffer.c (c0000000003547a0)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffe0001c6130)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
```
```
In kernel/events/ring_buffer.c (ffffffe0001d1328)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffff8120b634)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff812102c3)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffff811fe404)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff81203053)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffff812093d4)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8120e063)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
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
In kernel/events/core.c (ffffffff81218174)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8121cf50)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
```
</details>
</li>
</ul>

## Differences
