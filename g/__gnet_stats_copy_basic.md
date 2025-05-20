# Function: <code>__gnet_stats_copy_basic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __gnet_stats_copy_basic(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff8170eee0)
Location: net/core/gen_stats.c:127
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_basic
Direct callers:
  - net/core/gen_estimator.c:est_timer
  - net/core/gen_estimator.c:gen_new_estimator
```
**Symbols:**

```
ffffffff8170eee0-ffffffff8170ef02: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff817766d0)
Location: net/core/gen_stats.c:133
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_basic
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
```
**Symbols:**

```
ffffffff817766d0-ffffffff8177675e: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff817a3950)
Location: net/core/gen_stats.c:133
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
```
**Symbols:**

```
ffffffff817a3950-ffffffff817a39e0: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff817c1ab0)
Location: net/core/gen_stats.c:133
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
```
**Symbols:**

```
ffffffff817c1ab0-ffffffff817c1b3f: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff8183b4c0)
Location: net/core/gen_stats.c:133
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
```
**Symbols:**

```
ffffffff8183b4c0-ffffffff8183b553: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81885bc0)
Location: net/core/gen_stats.c:145
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff81885bc0-ffffffff81885c51: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818a62f0)
Location: net/core/gen_stats.c:145
Inline: False
Direct callers:
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff818a62f0-ffffffff818a6381: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818f1830)
Location: net/core/gen_stats.c:141
Inline: False
Direct callers:
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff818f1830-ffffffff818f18b3: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81923780)
Location: net/core/gen_stats.c:141
Inline: False
Direct callers:
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff81923780-ffffffff81923803: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819f7300)
Location: net/core/gen_stats.c:140
Inline: False
Direct callers:
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff819f7300-ffffffff819f738b: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819f6d70)
Location: net/core/gen_stats.c:140
Inline: False
Direct callers:
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff819f6d70-ffffffff819f6dfb: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819dcef0)
Location: net/core/gen_stats.c:140
Inline: False
Direct callers:
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff819dcef0-ffffffff819dcf7b: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81a8d160)
Location: net/core/gen_stats.c:140
Inline: False
Direct callers:
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff81a8d160-ffffffff81a8d20d: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffff800010bbeb60)
Location: net/core/gen_stats.c:141
Inline: False
Direct callers:
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffff800010bbeb60-ffff800010bbec5c: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (c0cda788)
Location: net/core/gen_stats.c:141
Inline: False
Direct callers:
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
c0cda788-c0cda8ec: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (c000000000c97ed0)
Location: net/core/gen_stats.c:141
Inline: False
Direct callers:
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
c000000000c97ed0-c000000000c98010: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffe00074c786)
Location: net/core/gen_stats.c:141
Inline: False
Direct callers:
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffe00074c786-ffffffe00074ca54: __gnet_stats_copy_basic (STB_GLOBAL)
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
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818c3780)
Location: net/core/gen_stats.c:141
Inline: False
Direct callers:
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff818c3780-ffffffff818c3803: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff8187d6c0)
Location: net/core/gen_stats.c:141
Inline: False
Direct callers:
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff8187d6c0-ffffffff8187d743: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81914780)
Location: net/core/gen_stats.c:141
Inline: False
Direct callers:
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff81914780-ffffffff81914803: __gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t *running, struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81935950)
Location: net/core/gen_stats.c:141
Inline: False
Direct callers:
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_estimator.c:est_fetch_counters
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff81935950-ffffffff819359d3: __gnet_stats_copy_basic (STB_GLOBAL)
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
<code>const seqcount_t *running</code>
</li>
<li>
<b>Param reordered. </b>
<code>bstats, cpu, b</code> ➡️ <code>running, bstats, cpu, b</code>
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
