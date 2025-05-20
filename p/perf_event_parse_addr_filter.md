# Function: <code>perf_event_parse_addr_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118bb58)
Location: kernel/events/core.c:7945
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_addr_filter
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
In kernel/events/core.c (ffffffff8119b028)
Location: kernel/events/core.c:8134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_addr_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int perf_event_parse_addr_filter(struct perf_event *event, char *fstr, struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a2a60)
Location: kernel/events/core.c:8360
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff811a2a60-ffffffff811a2e05: perf_event_parse_addr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int perf_event_parse_addr_filter(struct perf_event *event, char *fstr, struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b6c40)
Location: kernel/events/core.c:8346
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff811b6c40-ffffffff811b6fe3: perf_event_parse_addr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int perf_event_parse_addr_filter(struct perf_event *event, char *fstr, struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d65a0)
Location: kernel/events/core.c:8872
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811d65a0-ffffffff811d68b1: perf_event_parse_addr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int perf_event_parse_addr_filter(struct perf_event *event, char *fstr, struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e4d10)
Location: kernel/events/core.c:8912
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811e4d10-ffffffff811e5021: perf_event_parse_addr_filter (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811fc373)
Location: kernel/events/core.c:9214
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
In kernel/events/core.c (ffffffff81209443)
Location: kernel/events/core.c:9330
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perf_event_parse_addr_filter(struct perf_event *event, char *fstr, struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81234030)
Location: kernel/events/core.c:9878
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
```
**Symbols:**

```
ffffffff81234030-ffffffff81234432: perf_event_parse_addr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perf_event_parse_addr_filter(struct perf_event *event, char *fstr, struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123e470)
Location: kernel/events/core.c:10162
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
```
**Symbols:**

```
ffffffff8123e470-ffffffff8123e86e: perf_event_parse_addr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int perf_event_parse_addr_filter(struct perf_event *event, char *fstr, struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81242a10)
Location: kernel/events/core.c:10292
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81242a10-ffffffff81242e22: perf_event_parse_addr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int perf_event_parse_addr_filter(struct perf_event *event, char *fstr, struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127d200)
Location: kernel/events/core.c:10404
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8127d200-ffffffff8127d680: perf_event_parse_addr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int perf_event_parse_addr_filter(struct perf_event *event, char *fstr, struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d1510)
Location: kernel/events/core.c:10339
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff812d1510-ffffffff812d197b: perf_event_parse_addr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int perf_event_parse_addr_filter(struct perf_event *event, char *fstr, struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133a2d0)
Location: kernel/events/core.c:10705
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8133a2d0-ffffffff8133a73b: perf_event_parse_addr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int perf_event_parse_addr_filter(struct perf_event *event, char *fstr, struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136b1b0)
Location: kernel/events/core.c:10745
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff8136b1b0-ffffffff8136b620: perf_event_parse_addr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int perf_event_parse_addr_filter(struct perf_event *event, char *fstr, struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81393df0)
Location: kernel/events/core.c:10815
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff81393df0-ffffffff81394291: perf_event_parse_addr_filter (STB_LOCAL)
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
In kernel/events/core.c (ffff800010294418)
Location: kernel/events/core.c:9330
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
In kernel/events/core.c (c04c3d60)
Location: kernel/events/core.c:9330
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
In kernel/events/core.c (c000000000342dc8)
Location: kernel/events/core.c:9330
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
In kernel/events/core.c (ffffffe0001c4bd2)
Location: kernel/events/core.c:9330
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
In kernel/events/core.c (ffffffff81201a63)
Location: kernel/events/core.c:9330
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
In kernel/events/core.c (ffffffff811f47b3)
Location: kernel/events/core.c:9330
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
In kernel/events/core.c (ffffffff811ff833)
Location: kernel/events/core.c:9330
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
In kernel/events/core.c (ffffffff8120e8c3)
Location: kernel/events/core.c:9330
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
