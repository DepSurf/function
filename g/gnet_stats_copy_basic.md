# Function: <code>gnet_stats_copy_basic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gnet_stats_copy_basic(struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff8170f0b0)
Location: net/core/gen_stats.c:152
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff8170f0b0-ffffffff8170f18d: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81776920)
Location: net/core/gen_stats.c:167
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81776920-ffffffff817769f4: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff817a3ba0)
Location: net/core/gen_stats.c:167
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff817a3ba0-ffffffff817a3c74: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff817c1b40)
Location: net/core/gen_stats.c:167
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff817c1b40-ffffffff817c1c13: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff8183b560)
Location: net/core/gen_stats.c:167
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff8183b560-ffffffff8183b633: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81885ed0)
Location: net/core/gen_stats.c:179
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81885ed0-ffffffff81885fa3: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818a6540)
Location: net/core/gen_stats.c:207
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff818a6540-ffffffff818a6556: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818f1ac0)
Location: net/core/gen_stats.c:203
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff818f1ac0-ffffffff818f1ad6: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81923a10)
Location: net/core/gen_stats.c:203
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81923a10-ffffffff81923a26: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819f7920)
Location: net/core/gen_stats.c:207
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff819f7920-ffffffff819f7936: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819f7390)
Location: net/core/gen_stats.c:207
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff819f7390-ffffffff819f73a6: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819dd510)
Location: net/core/gen_stats.c:207
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff819dd510-ffffffff819dd526: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81a8d7a0)
Location: net/core/gen_stats.c:207
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81a8d7a0-ffffffff81a8d7b6: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gnet_stats_copy_basic(struct gnet_dump *d, struct gnet_stats_basic_sync *cpu, struct gnet_stats_basic_sync *b, bool running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81c03270)
Location: net/core/gen_stats.c:260
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81c03270-ffffffff81c03291: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gnet_stats_copy_basic(struct gnet_dump *d, struct gnet_stats_basic_sync *cpu, struct gnet_stats_basic_sync *b, bool running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81db2480)
Location: net/core/gen_stats.c:260
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81db2480-ffffffff81db24a1: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gnet_stats_copy_basic(struct gnet_dump *d, struct gnet_stats_basic_sync *cpu, struct gnet_stats_basic_sync *b, bool running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81e22a50)
Location: net/core/gen_stats.c:260
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81e22a50-ffffffff81e22a71: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gnet_stats_copy_basic(struct gnet_dump *d, struct gnet_stats_basic_sync *cpu, struct gnet_stats_basic_sync *b, bool running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81ee0990)
Location: net/core/gen_stats.c:260
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81ee0990-ffffffff81ee09b1: gnet_stats_copy_basic (STB_GLOBAL)
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
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffff800010bbeec0)
Location: net/core/gen_stats.c:203
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffff800010bbeec0-ffff800010bbef10: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (c0cdad48)
Location: net/core/gen_stats.c:203
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
c0cdad48-c0cdad74: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (c000000000c982e0)
Location: net/core/gen_stats.c:203
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
c000000000c982e0-c000000000c982f8: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffe00074ccd0)
Location: net/core/gen_stats.c:203
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffe00074ccd0-ffffffe00074cd14: gnet_stats_copy_basic (STB_GLOBAL)
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
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818c3a10)
Location: net/core/gen_stats.c:203
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff818c3a10-ffffffff818c3a26: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff8187d950)
Location: net/core/gen_stats.c:203
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff8187d950-ffffffff8187d966: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81914a10)
Location: net/core/gen_stats.c:203
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81914a10-ffffffff81914a26: gnet_stats_copy_basic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gnet_stats_copy_basic(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81935be0)
Location: net/core/gen_stats.c:203
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81935be0-ffffffff81935bf6: gnet_stats_copy_basic (STB_GLOBAL)
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
<code>d, cpu, b</code> ➡️ <code>running, d, cpu, b</code>
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
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param reordered. </b>
<code>running, d, cpu, b</code> ➡️ <code>d, cpu, b, running</code>
</li>
<li>
<b>Param type changed. </b>
<code>const seqcount_t *running</code> ➡️ <code>bool running</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct gnet_stats_basic_cpu *cpu</code> ➡️ <code>struct gnet_stats_basic_sync *cpu</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct gnet_stats_basic_packed *b</code> ➡️ <code>struct gnet_stats_basic_sync *b</code>
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
