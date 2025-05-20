# Function: <code>__perf_event_read_cpu</code>

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
In kernel/events/core.c (ffffffff8119bdbd)
Location: kernel/events/core.c:3495
Inline: True
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
In kernel/events/core.c (ffffffff811a361d)
Location: kernel/events/core.c:3587
Inline: True
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
In kernel/events/core.c (ffffffff811b75db)
Location: kernel/events/core.c:3490
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
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
In kernel/events/core.c (ffffffff811d6feb)
Location: kernel/events/core.c:3823
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
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
In kernel/events/core.c (ffffffff811e741b)
Location: kernel/events/core.c:3818
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
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
In kernel/events/core.c (ffffffff811fea4f)
Location: kernel/events/core.c:3838
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
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
In kernel/events/core.c (ffffffff8120baaf)
Location: kernel/events/core.c:3935
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
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
In kernel/events/core.c (ffffffff81234e0d)
Location: kernel/events/core.c:4158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
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
In kernel/events/core.c (ffffffff8123f25d)
Location: kernel/events/core.c:4235
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
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
In kernel/events/core.c (ffffffff8124342d)
Location: kernel/events/core.c:4315
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
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
In kernel/events/core.c (ffffffff8127dcbe)
Location: kernel/events/core.c:4411
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
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
In kernel/events/core.c (ffffffff812d2af1)
Location: kernel/events/core.c:4309
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
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
In kernel/events/core.c (ffffffff8133bb2d)
Location: kernel/events/core.c:4429
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
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
In kernel/events/core.c (ffffffff8136c68d)
Location: kernel/events/core.c:4429
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __perf_event_read_cpu(struct perf_event *event, int event_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138dba0)
Location: kernel/events/core.c:4461
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_event_read_local
```
**Symbols:**

```
ffffffff8138dba0-ffffffff8138dc63: __perf_event_read_cpu (STB_LOCAL)
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
In kernel/events/core.c (ffff800010295b84)
Location: kernel/events/core.c:3935
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
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
In kernel/events/core.c (c04c5b80)
Location: kernel/events/core.c:3935
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
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
In kernel/events/core.c (c0000000003433b0)
Location: kernel/events/core.c:3935
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
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
In kernel/events/core.c (ffffffe0001c6a00)
Location: kernel/events/core.c:3935
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
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
In kernel/events/core.c (ffffffff812040cf)
Location: kernel/events/core.c:3935
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
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
In kernel/events/core.c (ffffffff811f6e5f)
Location: kernel/events/core.c:3935
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
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
In kernel/events/core.c (ffffffff81201e9f)
Location: kernel/events/core.c:3935
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
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
In kernel/events/core.c (ffffffff812116d6)
Location: kernel/events/core.c:3935
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
