# Function: <code>group_sched_in</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int group_sched_in(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117ca00)
Location: kernel/events/core.c:1940
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_enable
```
**Symbols:**

```
ffffffff8117ca00-ffffffff8117cbc0: group_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int group_sched_in(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118e820)
Location: kernel/events/core.c:2075
Inline: False
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff8118e820-ffffffff8118e9ac: group_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int group_sched_in(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119e270)
Location: kernel/events/core.c:2113
Inline: False
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff8119e270-ffffffff8119e3fc: group_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int group_sched_in(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a5a70)
Location: kernel/events/core.c:2126
Inline: False
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff811a5a70-ffffffff811a5c11: group_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int group_sched_in(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b69e0)
Location: kernel/events/core.c:2111
Inline: False
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff811b69e0-ffffffff811b6b62: group_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int group_sched_in(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d6c30)
Location: kernel/events/core.c:2308
Inline: False
```
**Symbols:**

```
ffffffff811d6c30-ffffffff811d6d94: group_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int group_sched_in(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e69a0)
Location: kernel/events/core.c:2308
Inline: False
```
**Symbols:**

```
ffffffff811e69a0-ffffffff811e6b04: group_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int group_sched_in(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fe370)
Location: kernel/events/core.c:2311
Inline: False
```
**Symbols:**

```
ffffffff811fe370-ffffffff811fe4d6: group_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int group_sched_in(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120b610)
Location: kernel/events/core.c:2396
Inline: False
```
**Symbols:**

```
ffffffff8120b610-ffffffff8120b776: group_sched_in (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81239417)
Location: kernel/events/core.c:2545
Inline: True
Inline callers:
  - kernel/events/core.c:merge_sched_in
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
In kernel/events/core.c (ffffffff812444c7)
Location: kernel/events/core.c:2585
Inline: True
Inline callers:
  - kernel/events/core.c:merge_sched_in
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int group_sched_in(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81245d00)
Location: kernel/events/core.c:2587
Inline: False
Direct callers:
  - kernel/events/core.c:merge_sched_in
```
**Symbols:**

```
ffffffff81245d00-ffffffff81245e62: group_sched_in (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81285016)
Location: kernel/events/core.c:2626
Inline: True
Inline callers:
  - kernel/events/core.c:merge_sched_in
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
In kernel/events/core.c (ffffffff812d9595)
Location: kernel/events/core.c:2539
Inline: True
Inline callers:
  - kernel/events/core.c:merge_sched_in
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
In kernel/events/core.c (ffffffff81341a20)
Location: kernel/events/core.c:2541
Inline: True
Inline callers:
  - kernel/events/core.c:merge_sched_in
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
In kernel/events/core.c (ffffffff813729d3)
Location: kernel/events/core.c:2541
Inline: True
Inline callers:
  - kernel/events/core.c:merge_sched_in
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
In kernel/events/core.c (ffffffff8139bd4e)
Location: kernel/events/core.c:2579
Inline: True
Inline callers:
  - kernel/events/core.c:merge_sched_in
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
int group_sched_in(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029a3d0)
Location: kernel/events/core.c:2396
Inline: False
```
**Symbols:**

```
ffff80001029a3d0-ffff80001029a544: group_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int group_sched_in(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c9a90)
Location: kernel/events/core.c:2396
Inline: False
```
**Symbols:**

```
c04c9a90-c04c9bc0: group_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int group_sched_in(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000349f40)
Location: kernel/events/core.c:2396
Inline: False
```
**Symbols:**

```
c000000000349f40-c00000000034a150: group_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int group_sched_in(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cce70)
Location: kernel/events/core.c:2396
Inline: False
```
**Symbols:**

```
ffffffe0001cce70-ffffffe0001ccf5a: group_sched_in (STB_LOCAL)
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
int group_sched_in(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81203c30)
Location: kernel/events/core.c:2396
Inline: False
```
**Symbols:**

```
ffffffff81203c30-ffffffff81203d96: group_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int group_sched_in(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f64a0)
Location: kernel/events/core.c:2396
Inline: False
```
**Symbols:**

```
ffffffff811f64a0-ffffffff811f6606: group_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int group_sched_in(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201a00)
Location: kernel/events/core.c:2396
Inline: False
```
**Symbols:**

```
ffffffff81201a00-ffffffff81201b66: group_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int group_sched_in(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81210d90)
Location: kernel/events/core.c:2396
Inline: False
```
**Symbols:**

```
ffffffff81210d90-ffffffff81210ef6: group_sched_in (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
