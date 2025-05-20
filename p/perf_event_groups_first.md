# Function: <code>perf_event_groups_first</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d3176)
Location: kernel/events/core.c:1618
Inline: True
Inline callers:
  - kernel/events/core.c:visit_groups_merge
  - kernel/events/core.c:visit_groups_merge
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
In kernel/events/core.c (ffffffff811e3516)
Location: kernel/events/core.c:1618
Inline: True
Inline callers:
  - kernel/events/core.c:visit_groups_merge
  - kernel/events/core.c:visit_groups_merge
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
In kernel/events/core.c (ffffffff811fa6e4)
Location: kernel/events/core.c:1620
Inline: True
Inline callers:
  - kernel/events/core.c:visit_groups_merge
  - kernel/events/core.c:visit_groups_merge
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
In kernel/events/core.c (ffffffff812077b4)
Location: kernel/events/core.c:1620
Inline: True
Inline callers:
  - kernel/events/core.c:visit_groups_merge
  - kernel/events/core.c:visit_groups_merge
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
In kernel/events/core.c (ffffffff81231c70)
Location: kernel/events/core.c:1706
Inline: True
```
**Symbols:**

```
ffffffff81231c70-ffffffff81231ce0: perf_event_groups_first.isra.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8123b8e0)
Location: kernel/events/core.c:1724
Inline: True
```
**Symbols:**

```
ffffffff8123b8e0-ffffffff8123b950: perf_event_groups_first.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct perf_event *perf_event_groups_first(struct perf_event_groups *groups, int cpu, struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81240350)
Location: kernel/events/core.c:1745
Inline: False
```
**Symbols:**

```
ffffffff81240350-ffffffff812403c8: perf_event_groups_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct perf_event *perf_event_groups_first(struct perf_event_groups *groups, int cpu, struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127ad20)
Location: kernel/events/core.c:1813
Inline: False
```
**Symbols:**

```
ffffffff8127ad20-ffffffff8127ad98: perf_event_groups_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct perf_event *perf_event_groups_first(struct perf_event_groups *groups, int cpu, struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812ce9f0)
Location: kernel/events/core.c:1722
Inline: False
```
**Symbols:**

```
ffffffff812ce9f0-ffffffff812cea80: perf_event_groups_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct perf_event *perf_event_groups_first(struct perf_event_groups *groups, int cpu, struct pmu *pmu, struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81336ca0)
Location: kernel/events/core.c:1717
Inline: False
Direct callers:
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
```
**Symbols:**

```
ffffffff81336ca0-ffffffff81336d4d: perf_event_groups_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct perf_event *perf_event_groups_first(struct perf_event_groups *groups, int cpu, struct pmu *pmu, struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81367a10)
Location: kernel/events/core.c:1717
Inline: False
Direct callers:
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
```
**Symbols:**

```
ffffffff81367a10-ffffffff81367abd: perf_event_groups_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct perf_event *perf_event_groups_first(struct perf_event_groups *groups, int cpu, struct pmu *pmu, struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81390930)
Location: kernel/events/core.c:1728
Inline: False
Direct callers:
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
```
**Symbols:**

```
ffffffff81390930-ffffffff813909dd: perf_event_groups_first (STB_LOCAL)
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
In kernel/events/core.c (ffff800010291138)
Location: kernel/events/core.c:1620
Inline: True
Inline callers:
  - kernel/events/core.c:visit_groups_merge
  - kernel/events/core.c:visit_groups_merge
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
In kernel/events/core.c (c04c4548)
Location: kernel/events/core.c:1620
Inline: True
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
In kernel/events/core.c (c000000000342110)
Location: kernel/events/core.c:1620
Inline: True
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
In kernel/events/core.c (ffffffe0001c62b0)
Location: kernel/events/core.c:1620
Inline: True
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
In kernel/events/core.c (ffffffff811ffdd4)
Location: kernel/events/core.c:1620
Inline: True
Inline callers:
  - kernel/events/core.c:visit_groups_merge
  - kernel/events/core.c:visit_groups_merge
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
In kernel/events/core.c (ffffffff811f2b24)
Location: kernel/events/core.c:1620
Inline: True
Inline callers:
  - kernel/events/core.c:visit_groups_merge
  - kernel/events/core.c:visit_groups_merge
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
In kernel/events/core.c (ffffffff811fdba4)
Location: kernel/events/core.c:1620
Inline: True
Inline callers:
  - kernel/events/core.c:visit_groups_merge
  - kernel/events/core.c:visit_groups_merge
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
In kernel/events/core.c (ffffffff8120cc04)
Location: kernel/events/core.c:1620
Inline: True
Inline callers:
  - kernel/events/core.c:visit_groups_merge
  - kernel/events/core.c:visit_groups_merge
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pmu *pmu</code>
</li>
<li>
<b>Param reordered. </b>
<code>groups, cpu, cgrp</code> ➡️ <code>groups, cpu, pmu, cgrp</code>
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
