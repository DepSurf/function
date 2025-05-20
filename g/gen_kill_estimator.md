# Function: <code>gen_kill_estimator</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void gen_kill_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_rate_est64 *rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff8170f630)
Location: net/core/gen_estimator.c:267
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_hash_cleanup
```
**Symbols:**

```
ffffffff8170f630-ffffffff8170f6f3: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void gen_kill_estimator(struct gnet_stats_basic_packed *bstats, struct gnet_stats_rate_est64 *rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81776f10)
Location: net/core/gen_estimator.c:274
Inline: False
Direct callers:
  - net/core/gen_estimator.c:gen_replace_estimator
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_hash_cleanup
```
**Symbols:**

```
ffffffff81776f10-ffffffff81776fd7: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff817a3fd0)
Location: net/core/gen_estimator.c:190
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_hash_cleanup
```
**Symbols:**

```
ffffffff817a3fd0-ffffffff817a4001: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff817c2120)
Location: net/core/gen_estimator.c:190
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_hash_cleanup
```
**Symbols:**

```
ffffffff817c2120-ffffffff817c2151: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff8183bb20)
Location: net/core/gen_estimator.c:195
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_idr_cleanup
```
**Symbols:**

```
ffffffff8183bb20-ffffffff8183bb4e: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff818862f0)
Location: net/core/gen_estimator.c:195
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:__tcf_idr_release
```
**Symbols:**

```
ffffffff818862f0-ffffffff8188631e: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff818a6a70)
Location: net/core/gen_estimator.c:200
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
ffffffff818a6a70-ffffffff818a6a9e: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff818f1e90)
Location: net/core/gen_estimator.c:196
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
ffffffff818f1e90-ffffffff818f1ebe: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81923de0)
Location: net/core/gen_estimator.c:196
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
ffffffff81923de0-ffffffff81923e0e: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff819f7980)
Location: net/core/gen_estimator.c:196
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
ffffffff819f7980-ffffffff819f79b1: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff819f73f0)
Location: net/core/gen_estimator.c:199
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
ffffffff819f73f0-ffffffff819f7421: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff819dd570)
Location: net/core/gen_estimator.c:199
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
ffffffff819dd570-ffffffff819dd5a1: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81a8d800)
Location: net/core/gen_estimator.c:199
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
ffffffff81a8d800-ffffffff81a8d831: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81c032c0)
Location: net/core/gen_estimator.c:205
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
ffffffff81c032c0-ffffffff81c032fb: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81db2870)
Location: net/core/gen_estimator.c:205
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
ffffffff81db2870-ffffffff81db28ab: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81e22e40)
Location: net/core/gen_estimator.c:205
Inline: False
Direct callers:
  - net/sched/sch_generic.c:__qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
ffffffff81e22e40-ffffffff81e22e79: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81ee0d80)
Location: net/core/gen_estimator.c:205
Inline: False
Direct callers:
  - net/sched/sch_generic.c:__qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
ffffffff81ee0d80-ffffffff81ee0db9: gen_kill_estimator (STB_GLOBAL)
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
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffff800010bbf610)
Location: net/core/gen_estimator.c:196
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
ffff800010bbf610-ffff800010bbf670: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (c0cdb500)
Location: net/core/gen_estimator.c:196
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
c0cdb500-c0cdb554: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (c000000000c988a0)
Location: net/core/gen_estimator.c:196
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
c000000000c988a0-c000000000c98928: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffe00074cfc4)
Location: net/core/gen_estimator.c:196
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
ffffffe00074cfc4-ffffffe00074d00c: gen_kill_estimator (STB_GLOBAL)
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
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff818c3de0)
Location: net/core/gen_estimator.c:196
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
ffffffff818c3de0-ffffffff818c3e0e: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff8187dd20)
Location: net/core/gen_estimator.c:196
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
ffffffff8187dd20-ffffffff8187dd4e: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81914de0)
Location: net/core/gen_estimator.c:196
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
ffffffff81914de0-ffffffff81914e0e: gen_kill_estimator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gen_kill_estimator(struct net_rate_estimator **rate_est);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_estimator.c (ffffffff81935fb0)
Location: net/core/gen_estimator.c:196
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
ffffffff81935fb0-ffffffff81935fde: gen_kill_estimator (STB_GLOBAL)
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
<b>Param removed. </b>
<code>struct gnet_stats_basic_packed *bstats</code>
</li>
<li>
<b>Param reordered. </b>
<code>bstats, rate_est</code> ➡️ <code>rate_est</code>
</li>
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
