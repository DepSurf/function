# Function: <code>gen_new_estimator</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct gnet_stats_rate_est64 *rate_est, spinlock_t *stats_lock, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff8170f790)
Location: net/core/gen_estimator.c:207
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
```
**Symbols:**

```
ffffffff8170f790-ffffffff8170f9bf: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct gnet_stats_rate_est64 *rate_est, spinlock_t *stats_lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81777070)
Location: net/core/gen_estimator.c:212
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
```
**Symbols:**

```
ffffffff81777070-ffffffff817772de: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *stats_lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff817a4190)
Location: net/core/gen_estimator.c:127
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
```
**Symbols:**

```
ffffffff817a4190-ffffffff817a4318: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *stats_lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff817c22e0)
Location: net/core/gen_estimator.c:127
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
```
**Symbols:**

```
ffffffff817c22e0-ffffffff817c2462: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *stats_lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff8183bd00)
Location: net/core/gen_estimator.c:128
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff8183bd00-ffffffff8183beb1: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *stats_lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81886480)
Location: net/core/gen_estimator.c:128
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff81886480-ffffffff81886631: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff818a6c00)
Location: net/core/gen_estimator.c:128
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff818a6c00-ffffffff818a6dd4: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff818f2090)
Location: net/core/gen_estimator.c:124
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff818f2090-ffffffff818f2268: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81923fe0)
Location: net/core/gen_estimator.c:124
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff81923fe0-ffffffff819241b8: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff819f7b90)
Location: net/core/gen_estimator.c:124
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff819f7b90-ffffffff819f7d6c: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff819f75f0)
Location: net/core/gen_estimator.c:124
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff819f75f0-ffffffff819f77e0: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff819dd770)
Location: net/core/gen_estimator.c:124
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff819dd770-ffffffff819dd960: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/gen_estimator.c (0)
Location: net/core/gen_estimator.c:124
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff81d355e4-ffffffff81d355fd: gen_new_estimator.cold (STB_LOCAL)
ffffffff81a8da50-ffffffff81a8dc4a: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_sync *bstats, struct gnet_stats_basic_sync *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, bool running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/gen_estimator.c (0)
Location: net/core/gen_estimator.c:130
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff81f01b4f-ffffffff81f01b68: gen_new_estimator.cold (STB_LOCAL)
ffffffff81c03550-ffffffff81c03788: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_sync *bstats, struct gnet_stats_basic_sync *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, bool running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/gen_estimator.c (0)
Location: net/core/gen_estimator.c:130
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff820aaf8f-ffffffff820aafa8: gen_new_estimator.cold (STB_LOCAL)
ffffffff81db2b40-ffffffff81db2d78: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_sync *bstats, struct gnet_stats_basic_sync *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, bool running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/gen_estimator.c (0)
Location: net/core/gen_estimator.c:130
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff8212c5e7-ffffffff8212c600: gen_new_estimator.cold (STB_LOCAL)
ffffffff81e23110-ffffffff81e23346: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_sync *bstats, struct gnet_stats_basic_sync *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, bool running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/gen_estimator.c (0)
Location: net/core/gen_estimator.c:130
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff8220e30c-ffffffff8220e325: gen_new_estimator.cold (STB_LOCAL)
ffffffff81ee1050-ffffffff81ee12af: gen_new_estimator (STB_GLOBAL)
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
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffff800010bbf828)
Location: net/core/gen_estimator.c:124
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffff800010bbf828-ffff800010bbfa5c: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (c0cdb2e0)
Location: net/core/gen_estimator.c:124
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
c0cdb2e0-c0cdb4cc: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (c000000000c98bd0)
Location: net/core/gen_estimator.c:124
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
c000000000c98bd0-c000000000c98e68: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffe00074d202)
Location: net/core/gen_estimator.c:124
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffe00074d202-ffffffe00074d3a0: gen_new_estimator (STB_GLOBAL)
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
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff818c3fe0)
Location: net/core/gen_estimator.c:124
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff818c3fe0-ffffffff818c41b8: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff8187df20)
Location: net/core/gen_estimator.c:124
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff8187df20-ffffffff8187e0f8: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81914fe0)
Location: net/core/gen_estimator.c:124
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff81914fe0-ffffffff819151b8: gen_new_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gen_new_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_basic_cpu *cpu_bstats, struct net_rate_estimator **rate_est, spinlock_t *lock, seqcount_t *running, struct nlattr *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81936160)
Location: net/core/gen_estimator.c:124
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff81936160-ffffffff81936338: gen_new_estimator (STB_GLOBAL)
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
