# Function: <code>perf_event_set_filter</code>

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
In kernel/events/core.c (ffffffff811826a2)
Location: kernel/events/core.c:7051
Inline: True
Inline callers:
  - kernel/events/core.c:perf_ioctl
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
In kernel/events/core.c (ffffffff8119463c)
Location: kernel/events/core.c:8122
Inline: True
Inline callers:
  - kernel/events/core.c:perf_ioctl
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
In kernel/events/core.c (ffffffff811a400f)
Location: kernel/events/core.c:8311
Inline: True
Inline callers:
  - kernel/events/core.c:perf_ioctl
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
In kernel/events/core.c (ffffffff811ab555)
Location: kernel/events/core.c:8549
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
In kernel/events/core.c (ffffffff811bee75)
Location: kernel/events/core.c:8558
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
In kernel/events/core.c (ffffffff811df1a1)
Location: kernel/events/core.c:9068
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
In kernel/events/core.c (ffffffff811ef5e5)
Location: kernel/events/core.c:9108
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int perf_event_set_filter(struct perf_event *event, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fc270)
Location: kernel/events/core.c:9411
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811fc270-ffffffff811fc759: perf_event_set_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int perf_event_set_filter(struct perf_event *event, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81209340)
Location: kernel/events/core.c:9527
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81209340-ffffffff81209857: perf_event_set_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perf_event_set_filter(struct perf_event *event, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81238f00)
Location: kernel/events/core.c:10075
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81238f00-ffffffff81239110: perf_event_set_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perf_event_set_filter(struct perf_event *event, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81242ea0)
Location: kernel/events/core.c:10357
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81242ea0-ffffffff812430b0: perf_event_set_filter (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8124e8b8)
Location: kernel/events/core.c:10487
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
In kernel/events/core.c (ffffffff8128c728)
Location: kernel/events/core.c:10599
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
In kernel/events/core.c (ffffffff812e13df)
Location: kernel/events/core.c:10535
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
In kernel/events/core.c (ffffffff8134993f)
Location: kernel/events/core.c:10901
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
In kernel/events/core.c (ffffffff8137a8c6)
Location: kernel/events/core.c:10941
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
In kernel/events/core.c (ffffffff813a3ac6)
Location: kernel/events/core.c:11011
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int perf_event_set_filter(struct perf_event *event, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010294320)
Location: kernel/events/core.c:9527
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffff800010294320-ffff8000102947d4: perf_event_set_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int perf_event_set_filter(struct perf_event *event, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c3c58)
Location: kernel/events/core.c:9527
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
c04c3c58-c04c40e8: perf_event_set_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int perf_event_set_filter(struct perf_event *event, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000342c60)
Location: kernel/events/core.c:9527
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
c000000000342c60-c0000000003432a8: perf_event_set_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int perf_event_set_filter(struct perf_event *event, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c4b44)
Location: kernel/events/core.c:9527
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffe0001c4b44-ffffffe0001c4ea8: perf_event_set_filter (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int perf_event_set_filter(struct perf_event *event, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201960)
Location: kernel/events/core.c:9527
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81201960-ffffffff81201e77: perf_event_set_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int perf_event_set_filter(struct perf_event *event, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f46b0)
Location: kernel/events/core.c:9527
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811f46b0-ffffffff811f4bc7: perf_event_set_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int perf_event_set_filter(struct perf_event *event, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ff730)
Location: kernel/events/core.c:9527
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811ff730-ffffffff811ffc47: perf_event_set_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int perf_event_set_filter(struct perf_event *event, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120e7c0)
Location: kernel/events/core.c:9527
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8120e7c0-ffffffff8120ecd7: perf_event_set_filter (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
