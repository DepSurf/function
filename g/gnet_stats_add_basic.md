# Function: <code>gnet_stats_add_basic</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void gnet_stats_add_basic(struct gnet_stats_basic_sync *bstats, struct gnet_stats_basic_sync *cpu, struct gnet_stats_basic_sync *b, bool running);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81c029c0)
Location: net/core/gen_stats.c:149
Inline: True
Direct callers:
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff81c029c0-ffffffff81c02aba: gnet_stats_add_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void gnet_stats_add_basic(struct gnet_stats_basic_sync *bstats, struct gnet_stats_basic_sync *cpu, struct gnet_stats_basic_sync *b, bool running);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81db1e80)
Location: net/core/gen_stats.c:149
Inline: True
Direct callers:
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff81db1e80-ffffffff81db1f8a: gnet_stats_add_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void gnet_stats_add_basic(struct gnet_stats_basic_sync *bstats, struct gnet_stats_basic_sync *cpu, struct gnet_stats_basic_sync *b, bool running);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81e22450)
Location: net/core/gen_stats.c:149
Inline: True
Direct callers:
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff81e22450-ffffffff81e2255a: gnet_stats_add_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void gnet_stats_add_basic(struct gnet_stats_basic_sync *bstats, struct gnet_stats_basic_sync *cpu, struct gnet_stats_basic_sync *b, bool running);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81ee0390)
Location: net/core/gen_stats.c:149
Inline: True
Direct callers:
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff81ee0390-ffffffff81ee049a: gnet_stats_add_basic (STB_GLOBAL)
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
