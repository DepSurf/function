# Function: <code>perf_event_set_addr_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int perf_event_set_addr_filter(struct perf_event *event, char *filter_str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118baf0)
Location: kernel/events/core.c:8080
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff8118baf0-ffffffff8118bf67: perf_event_set_addr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int perf_event_set_addr_filter(struct perf_event *event, char *filter_str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119afc0)
Location: kernel/events/core.c:8269
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff8119afc0-ffffffff8119b437: perf_event_set_addr_filter (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811ab78b)
Location: kernel/events/core.c:8510
Inline: True
Inline callers:
  - kernel/events/core.c:perf_ioctl
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
In kernel/events/core.c (ffffffff811bf0b6)
Location: kernel/events/core.c:8496
Inline: True
Inline callers:
  - kernel/events/core.c:perf_ioctl
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
In kernel/events/core.c (ffffffff811df460)
Location: kernel/events/core.c:9029
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/events/core.c (ffffffff811ef898)
Location: kernel/events/core.c:9069
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/events/core.c (ffffffff811fc348)
Location: kernel/events/core.c:9372
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
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
In kernel/events/core.c (ffffffff81209418)
Location: kernel/events/core.c:9488
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
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
In kernel/events/core.c (ffffffff81238fd2)
Location: kernel/events/core.c:10036
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
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
In kernel/events/core.c (ffffffff81242f72)
Location: kernel/events/core.c:10318
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
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
In kernel/events/core.c (ffffffff8124ecb1)
Location: kernel/events/core.c:10448
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/events/core.c (ffffffff8128cb78)
Location: kernel/events/core.c:10560
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/events/core.c (ffffffff812e180d)
Location: kernel/events/core.c:10496
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/events/core.c (ffffffff81349d65)
Location: kernel/events/core.c:10862
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/events/core.c (ffffffff8137ad87)
Location: kernel/events/core.c:10902
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/events/core.c (ffffffff813a3f87)
Location: kernel/events/core.c:10972
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/events/core.c (ffff8000102943f8)
Location: kernel/events/core.c:9488
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
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
In kernel/events/core.c (c04c3d40)
Location: kernel/events/core.c:9488
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
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
In kernel/events/core.c (c000000000342da4)
Location: kernel/events/core.c:9488
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
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
In kernel/events/core.c (ffffffe0001c4b92)
Location: kernel/events/core.c:9488
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
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
In kernel/events/core.c (ffffffff81201a38)
Location: kernel/events/core.c:9488
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
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
In kernel/events/core.c (ffffffff811f4788)
Location: kernel/events/core.c:9488
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
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
In kernel/events/core.c (ffffffff811ff808)
Location: kernel/events/core.c:9488
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
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
In kernel/events/core.c (ffffffff8120e898)
Location: kernel/events/core.c:9488
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
