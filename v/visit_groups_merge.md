# Function: <code>visit_groups_merge</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int visit_groups_merge(struct perf_event_groups *groups, int cpu, int (*func)(struct perf_event *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d3150)
Location: kernel/events/core.c:3246
Inline: False
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff811d3150-ffffffff811d32d7: visit_groups_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int visit_groups_merge(struct perf_event_groups *groups, int cpu, int (*func)(struct perf_event *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e34f0)
Location: kernel/events/core.c:3241
Inline: False
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff811e34f0-ffffffff811e3675: visit_groups_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int visit_groups_merge(struct perf_event_groups *groups, int cpu, int (*func)(struct perf_event *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fa6c0)
Location: kernel/events/core.c:3265
Inline: False
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff811fa6c0-ffffffff811fa830: visit_groups_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int visit_groups_merge(struct perf_event_groups *groups, int cpu, int (*func)(struct perf_event *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207790)
Location: kernel/events/core.c:3350
Inline: False
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff81207790-ffffffff81207900: visit_groups_merge (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81239680)
Location: kernel/events/core.c:3562
Inline: True
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff81239680-ffffffff81239afc: visit_groups_merge.constprop.0.isra.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81244720)
Location: kernel/events/core.c:3630
Inline: True
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff81244720-ffffffff81244b9c: visit_groups_merge.constprop.0.isra.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81246100)
Location: kernel/events/core.c:3652
Inline: True
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff81246100-ffffffff81246546: visit_groups_merge.constprop.0.isra.0 (STB_LOCAL)
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
In kernel/events/core.c (0)
Location: kernel/events/core.c:3715
Inline: True
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff812852a0-ffffffff812856f5: visit_groups_merge.constprop.0.isra.0 (STB_LOCAL)
ffffffff81cb9949-ffffffff81cb995e: visit_groups_merge.constprop.0.isra.0.cold (STB_LOCAL)
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
In kernel/events/core.c (0)
Location: kernel/events/core.c:3626
Inline: True
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff812d9820-ffffffff812d9ca9: visit_groups_merge.constprop.0.isra.0 (STB_LOCAL)
ffffffff81e6af21-ffffffff81e6af36: visit_groups_merge.constprop.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:3690
Inline: True
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff81341bf0-ffffffff81342125: visit_groups_merge.constprop.0.isra.0 (STB_LOCAL)
ffffffff82061e23-ffffffff82061e38: visit_groups_merge.constprop.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:3690
Inline: True
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff81372be0-ffffffff813730e5: visit_groups_merge.constprop.0.isra.0 (STB_LOCAL)
ffffffff820e15b3-ffffffff820e15d2: visit_groups_merge.constprop.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:3734
Inline: True
Direct callers:
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:ctx_groups_sched_in
```
**Symbols:**

```
ffffffff8139bf60-ffffffff8139c465: visit_groups_merge.constprop.0.isra.0 (STB_LOCAL)
ffffffff821be016-ffffffff821be035: visit_groups_merge.constprop.0.isra.0.cold (STB_LOCAL)
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
int visit_groups_merge(struct perf_event_groups *groups, int cpu, int (*func)(struct perf_event *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010291118)
Location: kernel/events/core.c:3350
Inline: False
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffff800010291118-ffff8000102912f0: visit_groups_merge (STB_LOCAL)
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
In kernel/events/core.c (c04c4518)
Location: kernel/events/core.c:3350
Inline: True
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
c04c4518-c04c4688: visit_groups_merge.constprop.0 (STB_LOCAL)
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
In kernel/events/core.c (c0000000003420d0)
Location: kernel/events/core.c:3350
Inline: True
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
c0000000003420d0-c0000000003422d0: visit_groups_merge.constprop.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffe0001c629e)
Location: kernel/events/core.c:3350
Inline: True
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffe0001c629e-ffffffe0001c6384: visit_groups_merge.constprop.0 (STB_LOCAL)
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
int visit_groups_merge(struct perf_event_groups *groups, int cpu, int (*func)(struct perf_event *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ffdb0)
Location: kernel/events/core.c:3350
Inline: False
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff811ffdb0-ffffffff811fff20: visit_groups_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int visit_groups_merge(struct perf_event_groups *groups, int cpu, int (*func)(struct perf_event *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f2b00)
Location: kernel/events/core.c:3350
Inline: False
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff811f2b00-ffffffff811f2c70: visit_groups_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int visit_groups_merge(struct perf_event_groups *groups, int cpu, int (*func)(struct perf_event *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fdb80)
Location: kernel/events/core.c:3350
Inline: False
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff811fdb80-ffffffff811fdcf0: visit_groups_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int visit_groups_merge(struct perf_event_groups *groups, int cpu, int (*func)(struct perf_event *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120cbe0)
Location: kernel/events/core.c:3350
Inline: False
Direct callers:
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
```
**Symbols:**

```
ffffffff8120cbe0-ffffffff8120cd50: visit_groups_merge (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
