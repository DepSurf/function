# Function: <code>gen_replace_estimator</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct gnet_stats_rate_est64 *rate_est, spinlock_t *stats_lock, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff8170f9c0)
Location: net/core/gen_estimator.c:299
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff8170f9c0-ffffffff8170fa0e: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct gnet_stats_rate_est64 *rate_est, spinlock_t *stats_lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff817772e0)
Location: net/core/gen_estimator.c:308
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff817772e0-ffffffff81777336: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *stats_lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff817a4320)
Location: net/core/gen_estimator.c:216
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff817a4320-ffffffff817a4330: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *stats_lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff817c2470)
Location: net/core/gen_estimator.c:216
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff817c2470-ffffffff817c2480: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *stats_lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff8183bec0)
Location: net/core/gen_estimator.c:221
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff8183bec0-ffffffff8183bed0: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *stats_lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81886640)
Location: net/core/gen_estimator.c:221
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81886640-ffffffff81886650: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff818a6de0)
Location: net/core/gen_estimator.c:226
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff818a6de0-ffffffff818a6df0: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff818f2270)
Location: net/core/gen_estimator.c:222
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff818f2270-ffffffff818f2280: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff819241c0)
Location: net/core/gen_estimator.c:222
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff819241c0-ffffffff819241d0: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff819f7d70)
Location: net/core/gen_estimator.c:222
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_change
```
**Symbols:**

```
ffffffff819f7d70-ffffffff819f7d80: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff819f77e0)
Location: net/core/gen_estimator.c:225
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_change
```
**Symbols:**

```
ffffffff819f77e0-ffffffff819f77f0: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff819dd960)
Location: net/core/gen_estimator.c:225
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff819dd960-ffffffff819dd970: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81a8dc50)
Location: net/core/gen_estimator.c:225
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81a8dc50-ffffffff81a8dc60: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_sync *bstats, struct gnet_stats_basic_sync *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, bool running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81c03790)
Location: net/core/gen_estimator.c:233
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81c03790-ffffffff81c037b6: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_sync *bstats, struct gnet_stats_basic_sync *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, bool running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81db2d90)
Location: net/core/gen_estimator.c:233
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81db2d90-ffffffff81db2db6: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_sync *bstats, struct gnet_stats_basic_sync *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, bool running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81e23360)
Location: net/core/gen_estimator.c:233
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81e23360-ffffffff81e23386: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_sync *bstats, struct gnet_stats_basic_sync *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, bool running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81ee12c0)
Location: net/core/gen_estimator.c:233
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81ee12c0-ffffffff81ee12e6: gen_replace_estimator (STB_GLOBAL)
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
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffff800010bbfa60)
Location: net/core/gen_estimator.c:222
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffff800010bbfa60-ffff800010bbfac4: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (c0cdb4cc)
Location: net/core/gen_estimator.c:222
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
c0cdb4cc-c0cdb500: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (c000000000c98e70)
Location: net/core/gen_estimator.c:222
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
c000000000c98e70-c000000000c98e84: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffe00074d3a0)
Location: net/core/gen_estimator.c:222
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffe00074d3a0-ffffffe00074d3f2: gen_replace_estimator (STB_GLOBAL)
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
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff818c41c0)
Location: net/core/gen_estimator.c:222
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff818c41c0-ffffffff818c41d0: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff8187e100)
Location: net/core/gen_estimator.c:222
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff8187e100-ffffffff8187e110: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff819151c0)
Location: net/core/gen_estimator.c:222
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff819151c0-ffffffff819151d0: gen_replace_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gen_replace_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81936340)
Location: net/core/gen_estimator.c:222
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81936340-ffffffff81936350: gen_replace_estimator (STB_GLOBAL)
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
<code>seqcount_t *running</code>
</li>
<li>
<b>Param reordered. </b>
<code>bstats, cpu_bstats, rate_est, stats_lock, opt</code> ➡️ <code>bstats, cpu_bstats, rate_est, stats_lock, running, opt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct gnet_stats_rate_est64 *rate_est</code> ➡️ <code>struct net_rate_estimator **rate_est</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>spinlock_t *lock</code>
</li>
<li>
<b>Param removed. </b>
<code>spinlock_t *stats_lock</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct gnet_stats_basic_packed *bstats</code> ➡️ <code>struct gnet_stats_basic_sync *bstats</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct gnet_stats_basic_cpu *cpu_bstats</code> ➡️ <code>struct gnet_stats_basic_sync *cpu_bstats</code>
</li>
<li>
<b>Param type changed. </b>
<code>seqcount_t *running</code> ➡️ <code>bool running</code>
</li>
</ul>
</details>
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
