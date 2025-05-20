# Function: <code>has_aux</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: include/linux/perf_event.h:1031
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/perf_event.h:1031
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81188ad8)
Location: include/linux/perf_event.h:1191
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/perf_event.h:1191
Inline: True
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
In kernel/events/core.c (ffffffff81197eb8)
Location: include/linux/perf_event.h:1214
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/perf_event.h:1214
Inline: True
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
In kernel/events/core.c (ffffffff8119f9c8)
Location: include/linux/perf_event.h:1210
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/perf_event.h:1210
Inline: True
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
In kernel/events/core.c (ffffffff811b3338)
Location: include/linux/perf_event.h:1200
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/perf_event.h:1200
Inline: True
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
In kernel/events/core.c (ffffffff811dde3e)
Location: include/linux/perf_event.h:1228
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (ffffffff811e2aee)
Location: include/linux/perf_event.h:1228
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (ffffffff811ee23f)
Location: include/linux/perf_event.h:1233
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (ffffffff811f2f5e)
Location: include/linux/perf_event.h:1233
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (ffffffff81205c80)
Location: include/linux/perf_event.h:1276
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (ffffffff8120ac5a)
Location: include/linux/perf_event.h:1276
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (ffffffff81213010)
Location: include/linux/perf_event.h:1290
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (ffffffff81217f3a)
Location: include/linux/perf_event.h:1290
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (ffffffff8123316d)
Location: include/linux/perf_event.h:1359
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (ffffffff81243a8a)
Location: include/linux/perf_event.h:1359
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (ffffffff8123cf3d)
Location: include/linux/perf_event.h:1375
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (ffffffff8124e11a)
Location: include/linux/perf_event.h:1375
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (ffffffff812419bd)
Location: include/linux/perf_event.h:1376
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (ffffffff81252a4e)
Location: include/linux/perf_event.h:1376
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (ffffffff8127c3ad)
Location: include/linux/perf_event.h:1381
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (ffffffff8128e31c)
Location: include/linux/perf_event.h:1381
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (ffffffff812d2470)
Location: include/linux/perf_event.h:1423
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:perf_get_aux_event
```
```
In kernel/events/ring_buffer.c (ffffffff812e319c)
Location: include/linux/perf_event.h:1423
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (ffffffff8133419f)
Location: include/linux/perf_event.h:1522
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:perf_get_aux_event
```
```
In kernel/events/ring_buffer.c (ffffffff8134b80c)
Location: include/linux/perf_event.h:1522
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (ffffffff81364f0f)
Location: include/linux/perf_event.h:1635
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:perf_get_aux_event
```
```
In kernel/events/ring_buffer.c (ffffffff8137c85c)
Location: include/linux/perf_event.h:1635
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (ffffffff8138dedf)
Location: include/linux/perf_event.h:1677
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:perf_get_aux_event
```
```
In kernel/events/ring_buffer.c (ffffffff813a5a9c)
Location: include/linux/perf_event.h:1677
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (ffff80001029d3c8)
Location: include/linux/perf_event.h:1290
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (ffff8000102a2a2c)
Location: include/linux/perf_event.h:1290
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (c04ccb44)
Location: include/linux/perf_event.h:1290
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (c04d257c)
Location: include/linux/perf_event.h:1290
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (c00000000034de68)
Location: include/linux/perf_event.h:1290
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (c000000000354c60)
Location: include/linux/perf_event.h:1290
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (ffffffe0001c6144)
Location: include/linux/perf_event.h:1290
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (ffffffe0001d15a4)
Location: include/linux/perf_event.h:1290
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (ffffffff8120b660)
Location: include/linux/perf_event.h:1290
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (ffffffff8121058a)
Location: include/linux/perf_event.h:1290
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (ffffffff811fe430)
Location: include/linux/perf_event.h:1290
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (ffffffff8120331a)
Location: include/linux/perf_event.h:1290
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (ffffffff81209400)
Location: include/linux/perf_event.h:1290
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (ffffffff8120e32a)
Location: include/linux/perf_event.h:1290
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
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
In kernel/events/core.c (ffffffff812181a0)
Location: include/linux/perf_event.h:1290
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:perf_event_set_output
  - kernel/events/core.c:__perf_event_output_stop
  - kernel/events/core.c:ring_buffer_attach
```
```
In kernel/events/ring_buffer.c (ffffffff8121d23a)
Location: include/linux/perf_event.h:1290
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
</details>
</li>
</ul>

## Differences
