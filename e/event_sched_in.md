# Function: <code>event_sched_in</code>

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
In kernel/events/core.c (ffffffff8117aa60)
Location: kernel/events/core.c:1875
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:__perf_event_enable
```
**Symbols:**

```
ffffffff8117aa60-ffffffff8117ad1b: event_sched_in.isra.102 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8118b790)
Location: kernel/events/core.c:2008
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
ffffffff8118b790-ffffffff8118ba17: event_sched_in.isra.105 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8119ac60)
Location: kernel/events/core.c:2046
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
ffffffff8119ac60-ffffffff8119aee3: event_sched_in.isra.106 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811a2750)
Location: kernel/events/core.c:2059
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
ffffffff811a2750-ffffffff811a298e: event_sched_in.isra.100 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811b6a2e)
Location: kernel/events/core.c:2051
Inline: True
Inline callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
ffffffff811b6800-ffffffff811b69e0: event_sched_in.isra.102.part.103 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811d62c0)
Location: kernel/events/core.c:2248
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
ffffffff811d62c0-ffffffff811d64ca: event_sched_in.isra.117 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811e6790)
Location: kernel/events/core.c:2248
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
ffffffff811e6790-ffffffff811e699a: event_sched_in.isra.117 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:2251
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
ffffffff811fe160-ffffffff811fe362: event_sched_in.isra.0 (STB_LOCAL)
ffffffff8120a0d8-ffffffff8120a0f3: event_sched_in.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8120b410)
Location: kernel/events/core.c:2336
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
ffffffff8120b410-ffffffff8120b610: event_sched_in.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int event_sched_in(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81237e30)
Location: kernel/events/core.c:2483
Inline: False
Direct callers:
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
```
**Symbols:**

```
ffffffff81237e30-ffffffff81238054: event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int event_sched_in(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81241c10)
Location: kernel/events/core.c:2523
Inline: False
Direct callers:
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
```
**Symbols:**

```
ffffffff81241c10-ffffffff81241e34: event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81245d3a)
Location: kernel/events/core.c:2525
Inline: True
Inline callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
ffffffff812456b0-ffffffff8124588a: event_sched_in.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int event_sched_in(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81280cf0)
Location: kernel/events/core.c:2566
Inline: False
Direct callers:
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
```
**Symbols:**

```
ffffffff81280cf0-ffffffff81280f51: event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int event_sched_in(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d60d0)
Location: kernel/events/core.c:2479
Inline: False
Direct callers:
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
```
**Symbols:**

```
ffffffff812d60d0-ffffffff812d6342: event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int event_sched_in(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133f0c0)
Location: kernel/events/core.c:2483
Inline: False
Direct callers:
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
```
**Symbols:**

```
ffffffff8133f0c0-ffffffff8133f2e5: event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int event_sched_in(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136ff30)
Location: kernel/events/core.c:2483
Inline: False
Direct callers:
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
```
**Symbols:**

```
ffffffff8136ff30-ffffffff81370161: event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int event_sched_in(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81399230)
Location: kernel/events/core.c:2521
Inline: False
Direct callers:
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
```
**Symbols:**

```
ffffffff81399230-ffffffff81399461: event_sched_in (STB_LOCAL)
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
In kernel/events/core.c (ffff80001029a208)
Location: kernel/events/core.c:2336
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
ffff80001029a208-ffff80001029a3cc: event_sched_in.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int event_sched_in(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c9888)
Location: kernel/events/core.c:2336
Inline: False
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
c04c9888-c04c9a90: event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int event_sched_in(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000349d20)
Location: kernel/events/core.c:2336
Inline: False
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
c000000000349d20-c000000000349f38: event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int event_sched_in(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001ccd02)
Location: kernel/events/core.c:2336
Inline: False
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
ffffffe0001ccd02-ffffffe0001cce70: event_sched_in (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81203a30)
Location: kernel/events/core.c:2336
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
ffffffff81203a30-ffffffff81203c30: event_sched_in.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811f62a0)
Location: kernel/events/core.c:2336
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
ffffffff811f62a0-ffffffff811f64a0: event_sched_in.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81201800)
Location: kernel/events/core.c:2336
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
ffffffff81201800-ffffffff81201a00: event_sched_in.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81210b90)
Location: kernel/events/core.c:2336
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
ffffffff81210b90-ffffffff81210d90: event_sched_in.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct perf_cpu_context *cpuctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>event, cpuctx, ctx</code> ➡️ <code>event, ctx</code>
</li>
</ul>
</details>
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
</ul>
