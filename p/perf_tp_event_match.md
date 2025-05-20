# Function: <code>perf_tp_event_match</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8117a4c0)
Location: kernel/events/core.c:6941
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
**Symbols:**

```
ffffffff8117a4c0-ffffffff8117a4fc: perf_tp_event_match.isra.72.part.73 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8118b31a)
Location: kernel/events/core.c:7534
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
**Symbols:**

```
ffffffff8118b1b0-ffffffff8118b1eb: perf_tp_event_match.isra.81.part.82 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8119abaa)
Location: kernel/events/core.c:7647
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
**Symbols:**

```
ffffffff8119a0e0-ffffffff8119a11b: perf_tp_event_match.isra.83.part.84 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811a25f8)
Location: kernel/events/core.c:7869
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
**Symbols:**

```
ffffffff811a1e30-ffffffff811a1e6b: perf_tp_event_match.isra.75.part.76 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811b6756)
Location: kernel/events/core.c:7866
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
**Symbols:**

```
ffffffff811b5ab0-ffffffff811b5aeb: perf_tp_event_match.isra.76.part.77 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811d6235)
Location: kernel/events/core.c:8248
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
**Symbols:**

```
ffffffff811d5190-ffffffff811d51cb: perf_tp_event_match.isra.91.part.92 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811e6de9)
Location: kernel/events/core.c:8257
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int perf_tp_event_match(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd0d0)
Location: kernel/events/core.c:8561
Inline: True
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
**Symbols:**

```
ffffffff811fd0d0-ffffffff811fd12b: perf_tp_event_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int perf_tp_event_match(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120a380)
Location: kernel/events/core.c:8677
Inline: True
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
**Symbols:**

```
ffffffff8120a380-ffffffff8120a3db: perf_tp_event_match (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81237451)
Location: kernel/events/core.c:9227
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
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
In kernel/events/core.c (ffffffff81241056)
Location: kernel/events/core.c:9493
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
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
In kernel/events/core.c (ffffffff81244e06)
Location: kernel/events/core.c:9623
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
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
In kernel/events/core.c (ffffffff8127fd62)
Location: kernel/events/core.c:9742
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int perf_tp_event_match(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d4d4e)
Location: kernel/events/core.c:9677
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
Direct callers:
  - kernel/events/core.c:perf_tp_event
```
**Symbols:**

```
ffffffff812ce260-ffffffff812ce2de: perf_tp_event_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int perf_tp_event_match(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133d56e)
Location: kernel/events/core.c:10040
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
Direct callers:
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
```
**Symbols:**

```
ffffffff81335c10-ffffffff81335c8e: perf_tp_event_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int perf_tp_event_match(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81366960)
Location: kernel/events/core.c:10075
Inline: False
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
```
**Symbols:**

```
ffffffff81366960-ffffffff813669de: perf_tp_event_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int perf_tp_event_match(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138f8c0)
Location: kernel/events/core.c:10145
Inline: False
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
```
**Symbols:**

```
ffffffff8138f8c0-ffffffff8138f93e: perf_tp_event_match (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffff800010293468)
Location: kernel/events/core.c:8677
Inline: True
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
**Symbols:**

```
ffff800010293468-ffff8000102934d8: perf_tp_event_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int perf_tp_event_match(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c39b8)
Location: kernel/events/core.c:8677
Inline: True
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
**Symbols:**

```
c04c39b8-c04c3a2c: perf_tp_event_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (c000000000341990)
Location: kernel/events/core.c:8677
Inline: True
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
**Symbols:**

```
c000000000341990-c000000000341a48: perf_tp_event_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffe0001c5c3a)
Location: kernel/events/core.c:8677
Inline: True
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
**Symbols:**

```
ffffffe0001c5c3a-ffffffe0001c5ca2: perf_tp_event_match.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int perf_tp_event_match(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812029a0)
Location: kernel/events/core.c:8677
Inline: True
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
**Symbols:**

```
ffffffff812029a0-ffffffff812029fb: perf_tp_event_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int perf_tp_event_match(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f56f0)
Location: kernel/events/core.c:8677
Inline: True
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
**Symbols:**

```
ffffffff811f56f0-ffffffff811f574b: perf_tp_event_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int perf_tp_event_match(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81200770)
Location: kernel/events/core.c:8677
Inline: True
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
**Symbols:**

```
ffffffff81200770-ffffffff812007cb: perf_tp_event_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int perf_tp_event_match(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120f800)
Location: kernel/events/core.c:8677
Inline: True
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
**Symbols:**

```
ffffffff8120f800-ffffffff8120f85b: perf_tp_event_match (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
