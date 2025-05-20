# Function: <code>event_sched_out</code>

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
In kernel/events/core.c (ffffffff8117c210)
Location: kernel/events/core.c:1555
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
ffffffff8117c210-ffffffff8117c51a: event_sched_out.isra.91 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8118ddc0)
Location: kernel/events/core.c:1783
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
```
**Symbols:**

```
ffffffff8118ddc0-ffffffff8118e113: event_sched_out.isra.94 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8119d7c0)
Location: kernel/events/core.c:1791
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_out
  - kernel/events/core.c:group_sched_out
```
**Symbols:**

```
ffffffff8119d7c0-ffffffff8119db22: event_sched_out.isra.95 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811a5150)
Location: kernel/events/core.c:1804
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_out
  - kernel/events/core.c:group_sched_out
```
**Symbols:**

```
ffffffff811a5150-ffffffff811a5473: event_sched_out.isra.89 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811b5e10)
Location: kernel/events/core.c:1801
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff811b5e10-ffffffff811b5f70: event_sched_out.isra.90 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811d5600)
Location: kernel/events/core.c:1991
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff811d5600-ffffffff811d576d: event_sched_out.isra.106 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811e5ca0)
Location: kernel/events/core.c:1991
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff811e5ca0-ffffffff811e5e0d: event_sched_out.isra.106 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811fd4b3)
Location: kernel/events/core.c:1993
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
```
**Symbols:**

```
ffffffff811fd480-ffffffff811fd5fa: event_sched_out.isra.0 (STB_LOCAL)
ffffffff8120a0c5-ffffffff8120a0d8: event_sched_out.isra.0.cold (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8120a730)
Location: kernel/events/core.c:2078
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff8120a730-ffffffff8120a8a8: event_sched_out.isra.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff812395c6)
Location: kernel/events/core.c:2222
Inline: True
Inline callers:
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
Direct callers:
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff81235fa0-ffffffff81236171: event_sched_out.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81244674)
Location: kernel/events/core.c:2265
Inline: True
Inline callers:
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
Direct callers:
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff8123fae0-ffffffff8123fcb1: event_sched_out.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void event_sched_out(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81245890)
Location: kernel/events/core.c:2268
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff81245890-ffffffff81245a8d: event_sched_out (STB_LOCAL)
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
In kernel/events/core.c (ffffffff812851a5)
Location: kernel/events/core.c:2336
Inline: True
Inline callers:
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
Direct callers:
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff8127efc0-ffffffff8127f1ef: event_sched_out.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff812d9725)
Location: kernel/events/core.c:2249
Inline: True
Inline callers:
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
Direct callers:
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff812d38e0-ffffffff812d3b0b: event_sched_out.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void event_sched_out(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133e3b0)
Location: kernel/events/core.c:2221
Inline: False
Direct callers:
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff8133e3b0-ffffffff8133e63a: event_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void event_sched_out(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136f3c0)
Location: kernel/events/core.c:2221
Inline: False
Direct callers:
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff8136f3c0-ffffffff8136f64e: event_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void event_sched_out(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81398830)
Location: kernel/events/core.c:2259
Inline: False
Direct callers:
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff81398830-ffffffff81398add: event_sched_out (STB_LOCAL)
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
In kernel/events/core.c (ffff800010299268)
Location: kernel/events/core.c:2078
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffff800010299268-ffff8000102993cc: event_sched_out.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void event_sched_out(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c8514)
Location: kernel/events/core.c:2078
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
c04c8514-c04c8694: event_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void event_sched_out(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c0000000003485e0)
Location: kernel/events/core.c:2078
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
c0000000003485e0-c0000000003487a8: event_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void event_sched_out(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cad14)
Location: kernel/events/core.c:2078
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffe0001cad14-ffffffe0001cae34: event_sched_out (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81202d50)
Location: kernel/events/core.c:2078
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff81202d50-ffffffff81202ec8: event_sched_out.isra.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811f5aa0)
Location: kernel/events/core.c:2078
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff811f5aa0-ffffffff811f5c18: event_sched_out.isra.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81200b20)
Location: kernel/events/core.c:2078
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff81200b20-ffffffff81200c98: event_sched_out.isra.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8120fcd0)
Location: kernel/events/core.c:2078
Inline: True
Direct callers:
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:group_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
```
**Symbols:**

```
ffffffff8120fcd0-ffffffff8120fe48: event_sched_out.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
