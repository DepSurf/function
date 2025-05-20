# Function: <code>gnet_stats_basic_sync_init</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void gnet_stats_basic_sync_init(struct gnet_stats_basic_sync *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81c029a0)
Location: net/core/gen_stats.c:118
Inline: False
Direct callers:
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff81c029a0-ffffffff81c029c0: gnet_stats_basic_sync_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gnet_stats_basic_sync_init(struct gnet_stats_basic_sync *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81db1e50)
Location: net/core/gen_stats.c:118
Inline: False
Direct callers:
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff81db1e50-ffffffff81db1e70: gnet_stats_basic_sync_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gnet_stats_basic_sync_init(struct gnet_stats_basic_sync *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81e22420)
Location: net/core/gen_stats.c:118
Inline: False
Direct callers:
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff81e22420-ffffffff81e22440: gnet_stats_basic_sync_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gnet_stats_basic_sync_init(struct gnet_stats_basic_sync *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81ee0360)
Location: net/core/gen_stats.c:118
Inline: False
Direct callers:
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff81ee0360-ffffffff81ee0380: gnet_stats_basic_sync_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
