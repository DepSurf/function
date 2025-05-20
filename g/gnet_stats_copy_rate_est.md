# Function: <code>gnet_stats_copy_rate_est</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, const struct gnet_stats_basic_packed *b, struct gnet_stats_rate_est64 *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff8170f3a0)
Location: net/core/gen_stats.c:190
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff8170f3a0-ffffffff8170f496: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, const struct gnet_stats_basic_packed *b, struct gnet_stats_rate_est64 *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81776c40)
Location: net/core/gen_stats.c:207
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81776c40-ffffffff81776d47: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff817a3df0)
Location: net/core/gen_stats.c:206
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff817a3df0-ffffffff817a3ee0: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff817c1f40)
Location: net/core/gen_stats.c:206
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff817c1f40-ffffffff817c2030: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff8183b940)
Location: net/core/gen_stats.c:206
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff8183b940-ffffffff8183ba30: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81885fb0)
Location: net/core/gen_stats.c:218
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81885fb0-ffffffff818860a0: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818a6840)
Location: net/core/gen_stats.c:253
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff818a6840-ffffffff818a6930: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818f1cb0)
Location: net/core/gen_stats.c:249
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff818f1cb0-ffffffff818f1da0: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81923c00)
Location: net/core/gen_stats.c:249
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81923c00-ffffffff81923cf0: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819f7510)
Location: net/core/gen_stats.c:253
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff819f7510-ffffffff819f75ff: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819f6f80)
Location: net/core/gen_stats.c:253
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff819f6f80-ffffffff819f706f: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819dd100)
Location: net/core/gen_stats.c:253
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff819dd100-ffffffff819dd1f1: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81a8d390)
Location: net/core/gen_stats.c:253
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81a8d390-ffffffff81a8d481: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81c02d50)
Location: net/core/gen_stats.c:308
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81c02d50-ffffffff81c02e68: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81db2710)
Location: net/core/gen_stats.c:308
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81db2710-ffffffff81db2828: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81e22ce0)
Location: net/core/gen_stats.c:308
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81e22ce0-ffffffff81e22df8: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81ee0c20)
Location: net/core/gen_stats.c:308
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81ee0c20-ffffffff81ee0d38: gnet_stats_copy_rate_est (STB_GLOBAL)
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
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffff800010bbf158)
Location: net/core/gen_stats.c:249
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffff800010bbf158-ffff800010bbf274: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (c0cdada0)
Location: net/core/gen_stats.c:249
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
c0cdada0-c0cdaf00: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (c000000000c985b0)
Location: net/core/gen_stats.c:249
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
c000000000c985b0-c000000000c98740: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffe00074ce26)
Location: net/core/gen_stats.c:249
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffe00074ce26-ffffffe00074cef4: gnet_stats_copy_rate_est (STB_GLOBAL)
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
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818c3c00)
Location: net/core/gen_stats.c:249
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff818c3c00-ffffffff818c3cf0: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff8187db40)
Location: net/core/gen_stats.c:249
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff8187db40-ffffffff8187dc30: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81914c00)
Location: net/core/gen_stats.c:249
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81914c00-ffffffff81914cf0: gnet_stats_copy_rate_est (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gnet_stats_copy_rate_est(struct gnet_dump *d, struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81935dd0)
Location: net/core/gen_stats.c:249
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81935dd0-ffffffff81935ec0: gnet_stats_copy_rate_est (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net_rate_estimator **rate_est</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct gnet_stats_basic_packed *b</code>
</li>
<li>
<b>Param removed. </b>
<code>struct gnet_stats_rate_est64 *r</code>
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
