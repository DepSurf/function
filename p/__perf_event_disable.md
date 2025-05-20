# Function: <code>__perf_event_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __perf_event_disable(void *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117c7b0)
Location: kernel/events/core.c:1727
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pending_event
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8117c7b0-ffffffff8117c8c7: __perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118e490)
Location: kernel/events/core.c:1902
Inline: True
```
**Symbols:**

```
ffffffff8118e490-ffffffff8118e57f: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119dee0)
Location: kernel/events/core.c:1934
Inline: True
```
**Symbols:**

```
ffffffff8119dee0-ffffffff8119dfcf: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a5890)
Location: kernel/events/core.c:1947
Inline: True
```
**Symbols:**

```
ffffffff811a5890-ffffffff811a597d: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b7eb0)
Location: kernel/events/core.c:1937
Inline: True
```
**Symbols:**

```
ffffffff811b7eb0-ffffffff811b8000: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d7900)
Location: kernel/events/core.c:2134
Inline: False
```
**Symbols:**

```
ffffffff811d7900-ffffffff811d7a55: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e8380)
Location: kernel/events/core.c:2134
Inline: False
```
**Symbols:**

```
ffffffff811e8380-ffffffff811e84d5: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ffc90)
Location: kernel/events/core.c:2136
Inline: False
```
**Symbols:**

```
ffffffff811ffc90-ffffffff811ffde8: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120cdf0)
Location: kernel/events/core.c:2221
Inline: False
```
**Symbols:**

```
ffffffff8120cdf0-ffffffff8120cf48: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81236280)
Location: kernel/events/core.c:2367
Inline: False
```
**Symbols:**

```
ffffffff81236280-ffffffff8123646d: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123fdb0)
Location: kernel/events/core.c:2407
Inline: False
```
**Symbols:**

```
ffffffff8123fdb0-ffffffff8123ff9d: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81245b40)
Location: kernel/events/core.c:2409
Inline: False
```
**Symbols:**

```
ffffffff81245b40-ffffffff81245cf7: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127f2e0)
Location: kernel/events/core.c:2484
Inline: False
```
**Symbols:**

```
ffffffff8127f2e0-ffffffff8127f526: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d3c10)
Location: kernel/events/core.c:2397
Inline: False
```
**Symbols:**

```
ffffffff812d3c10-ffffffff812d3e19: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133ea40)
Location: kernel/events/core.c:2398
Inline: False
```
**Symbols:**

```
ffffffff8133ea40-ffffffff8133ec21: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136fa40)
Location: kernel/events/core.c:2398
Inline: False
```
**Symbols:**

```
ffffffff8136fa40-ffffffff8136fc17: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81398f00)
Location: kernel/events/core.c:2436
Inline: False
```
**Symbols:**

```
ffffffff81398f00-ffffffff813990e2: __perf_event_disable (STB_LOCAL)
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
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010299480)
Location: kernel/events/core.c:2221
Inline: False
```
**Symbols:**

```
ffff800010299480-ffff8000102995c0: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c8720)
Location: kernel/events/core.c:2221
Inline: False
```
**Symbols:**

```
c04c8720-c04c888c: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000348890)
Location: kernel/events/core.c:2221
Inline: False
```
**Symbols:**

```
c000000000348890-c000000000348a2c: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cc074)
Location: kernel/events/core.c:2221
Inline: False
```
**Symbols:**

```
ffffffe0001cc074-ffffffe0001cc17e: __perf_event_disable (STB_LOCAL)
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
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81205410)
Location: kernel/events/core.c:2221
Inline: False
```
**Symbols:**

```
ffffffff81205410-ffffffff81205568: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f81a0)
Location: kernel/events/core.c:2221
Inline: False
```
**Symbols:**

```
ffffffff811f81a0-ffffffff811f82f8: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812031e0)
Location: kernel/events/core.c:2221
Inline: False
```
**Symbols:**

```
ffffffff812031e0-ffffffff81203338: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81212db0)
Location: kernel/events/core.c:2221
Inline: False
```
**Symbols:**

```
ffffffff81212db0-ffffffff81212f08: __perf_event_disable (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct perf_event *event</code>
</li>
<li>
<b>Param added. </b>
<code>struct perf_cpu_context *cpuctx</code>
</li>
<li>
<b>Param added. </b>
<code>struct perf_event_context *ctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>info</code> ➡️ <code>event, cpuctx, ctx, info</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
