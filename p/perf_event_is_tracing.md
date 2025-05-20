# Function: <code>perf_event_is_tracing</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811df119)
Location: kernel/events/core.c:8575
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff811ef557)
Location: kernel/events/core.c:8615
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff811fc2bb)
Location: kernel/events/core.c:8919
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff8120938b)
Location: kernel/events/core.c:9035
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff81238f3e)
Location: kernel/events/core.c:9583
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_bpf_prog
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff81242ede)
Location: kernel/events/core.c:9867
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_bpf_prog
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff8123f5df)
Location: kernel/events/core.c:9997
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_bpf_prog
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff8128c744)
Location: kernel/events/core.c:10123
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff812e13fe)
Location: kernel/events/core.c:10058
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff8134995e)
Location: kernel/events/core.c:10419
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff8137a8e2)
Location: kernel/events/core.c:10459
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff813a3ae2)
Location: kernel/events/core.c:10529
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffff800010294368)
Location: kernel/events/core.c:9035
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (c04c3ca0)
Location: kernel/events/core.c:9035
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (c000000000342cc4)
Location: kernel/events/core.c:9035
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffe0001c4b7e)
Location: kernel/events/core.c:9035
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff812019ab)
Location: kernel/events/core.c:9035
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff811f46fb)
Location: kernel/events/core.c:9035
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff811ff77b)
Location: kernel/events/core.c:9035
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff8120e80b)
Location: kernel/events/core.c:9035
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
```
</details>
</li>
</ul>

## Differences
