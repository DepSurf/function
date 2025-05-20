# Function: <code>group_sched_out</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void group_sched_out(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117c520)
Location: kernel/events/core.c:1608
Inline: True
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_enable
```
**Symbols:**

```
ffffffff8117c520-ffffffff8117c5d1: group_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void group_sched_out(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118e120)
Location: kernel/events/core.c:1833
Inline: True
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
```
**Symbols:**

```
ffffffff8118e120-ffffffff8118e1d4: group_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void group_sched_out(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119db30)
Location: kernel/events/core.c:1841
Inline: False
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
```
**Symbols:**

```
ffffffff8119db30-ffffffff8119dc36: group_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void group_sched_out(struct perf_event *group_event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a5580)
Location: kernel/events/core.c:1854
Inline: False
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
```
**Symbols:**

```
ffffffff811a5580-ffffffff811a5672: group_sched_out (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811b613e)
Location: kernel/events/core.c:1837
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
```
**Symbols:**

```
ffffffff811b5f70-ffffffff811b604f: group_sched_out.part.92 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811d5939)
Location: kernel/events/core.c:2034
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
ffffffff811d5770-ffffffff811d5843: group_sched_out.part.108 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811e5fd9)
Location: kernel/events/core.c:2034
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
ffffffff811e5e10-ffffffff811e5ee3: group_sched_out.part.108 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811fd7d8)
Location: kernel/events/core.c:2036
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
ffffffff811fd600-ffffffff811fd6d7: group_sched_out.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8120aa88)
Location: kernel/events/core.c:2121
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
ffffffff8120a8b0-ffffffff8120a987: group_sched_out.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8123ad81)
Location: kernel/events/core.c:2266
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
ffffffff81236180-ffffffff81236279: group_sched_out.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81245241)
Location: kernel/events/core.c:2309
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
ffffffff8123fcc0-ffffffff8123fda3: group_sched_out.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8124918d)
Location: kernel/events/core.c:2312
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
ffffffff81245a90-ffffffff81245b31: group_sched_out.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff812829bf)
Location: kernel/events/core.c:2380
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
ffffffff8127f1f0-ffffffff8127f2d3: group_sched_out.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff812d7fec)
Location: kernel/events/core.c:2293
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
ffffffff812d3b10-ffffffff812d3c06: group_sched_out.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void group_sched_out(struct perf_event *group_event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133e650)
Location: kernel/events/core.c:2281
Inline: True
Direct callers:
  - kernel/events/core.c:__pmu_ctx_sched_out
  - kernel/events/core.c:__pmu_ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
ffffffff8133e650-ffffffff8133e6f5: group_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void group_sched_out(struct perf_event *group_event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136f660)
Location: kernel/events/core.c:2281
Inline: True
Direct callers:
  - kernel/events/core.c:__pmu_ctx_sched_out
  - kernel/events/core.c:__pmu_ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
ffffffff8136f660-ffffffff8136f705: group_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void group_sched_out(struct perf_event *group_event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81398af0)
Location: kernel/events/core.c:2319
Inline: True
Direct callers:
  - kernel/events/core.c:__pmu_ctx_sched_out
  - kernel/events/core.c:__pmu_ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
ffffffff81398af0-ffffffff81398b95: group_sched_out (STB_LOCAL)
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
In kernel/events/core.c (ffff800010299798)
Location: kernel/events/core.c:2121
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
ffff8000102993d0-ffff800010299480: group_sched_out.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (c04c8af4)
Location: kernel/events/core.c:2121
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
c04c8694-c04c8720: group_sched_out.part.0 (STB_LOCAL)
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
In kernel/events/core.c (c000000000348cb8)
Location: kernel/events/core.c:2121
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
c0000000003487b0-c000000000348888: group_sched_out.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffe0001cc2f0)
Location: kernel/events/core.c:2121
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
ffffffe0001cbff4-ffffffe0001cc074: group_sched_out.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff812030a8)
Location: kernel/events/core.c:2121
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
ffffffff81202ed0-ffffffff81202fa7: group_sched_out.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811f5df8)
Location: kernel/events/core.c:2121
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
ffffffff811f5c20-ffffffff811f5cf7: group_sched_out.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81200e78)
Location: kernel/events/core.c:2121
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
ffffffff81200ca0-ffffffff81200d77: group_sched_out.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81210028)
Location: kernel/events/core.c:2121
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
Direct callers:
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
```
**Symbols:**

```
ffffffff8120fe50-ffffffff8120ff27: group_sched_out.part.0 (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
