# Function: <code>gnet_stats_copy_basic_hw</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gnet_stats_copy_basic_hw(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818a6560)
Location: net/core/gen_stats.c:231
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff818a6560-ffffffff818a6576: gnet_stats_copy_basic_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gnet_stats_copy_basic_hw(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818f1ae0)
Location: net/core/gen_stats.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff818f1ae0-ffffffff818f1af6: gnet_stats_copy_basic_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gnet_stats_copy_basic_hw(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81923a30)
Location: net/core/gen_stats.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81923a30-ffffffff81923a46: gnet_stats_copy_basic_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gnet_stats_copy_basic_hw(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819f7940)
Location: net/core/gen_stats.c:231
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff819f7940-ffffffff819f7956: gnet_stats_copy_basic_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gnet_stats_copy_basic_hw(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819f73b0)
Location: net/core/gen_stats.c:231
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff819f73b0-ffffffff819f73c6: gnet_stats_copy_basic_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gnet_stats_copy_basic_hw(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819dd530)
Location: net/core/gen_stats.c:231
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff819dd530-ffffffff819dd546: gnet_stats_copy_basic_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gnet_stats_copy_basic_hw(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81a8d7c0)
Location: net/core/gen_stats.c:231
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81a8d7c0-ffffffff81a8d7d6: gnet_stats_copy_basic_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gnet_stats_copy_basic_hw(struct gnet_dump *d, struct gnet_stats_basic_sync *cpu, struct gnet_stats_basic_sync *b, bool running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81c03240)
Location: net/core/gen_stats.c:287
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81c03240-ffffffff81c03261: gnet_stats_copy_basic_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gnet_stats_copy_basic_hw(struct gnet_dump *d, struct gnet_stats_basic_sync *cpu, struct gnet_stats_basic_sync *b, bool running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81db2440)
Location: net/core/gen_stats.c:287
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81db2440-ffffffff81db2461: gnet_stats_copy_basic_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gnet_stats_copy_basic_hw(struct gnet_dump *d, struct gnet_stats_basic_sync *cpu, struct gnet_stats_basic_sync *b, bool running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81e22a10)
Location: net/core/gen_stats.c:287
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81e22a10-ffffffff81e22a31: gnet_stats_copy_basic_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gnet_stats_copy_basic_hw(struct gnet_dump *d, struct gnet_stats_basic_sync *cpu, struct gnet_stats_basic_sync *b, bool running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81ee0950)
Location: net/core/gen_stats.c:287
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81ee0950-ffffffff81ee0971: gnet_stats_copy_basic_hw (STB_GLOBAL)
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
int gnet_stats_copy_basic_hw(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffff800010bbef10)
Location: net/core/gen_stats.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffff800010bbef10-ffff800010bbef60: gnet_stats_copy_basic_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gnet_stats_copy_basic_hw(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (c0cdad74)
Location: net/core/gen_stats.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
c0cdad74-c0cdada0: gnet_stats_copy_basic_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gnet_stats_copy_basic_hw(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (c000000000c98300)
Location: net/core/gen_stats.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
c000000000c98300-c000000000c98318: gnet_stats_copy_basic_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gnet_stats_copy_basic_hw(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffe00074cd14)
Location: net/core/gen_stats.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffe00074cd14-ffffffe00074cd58: gnet_stats_copy_basic_hw (STB_GLOBAL)
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
int gnet_stats_copy_basic_hw(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818c3a30)
Location: net/core/gen_stats.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff818c3a30-ffffffff818c3a46: gnet_stats_copy_basic_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gnet_stats_copy_basic_hw(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff8187d970)
Location: net/core/gen_stats.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff8187d970-ffffffff8187d986: gnet_stats_copy_basic_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gnet_stats_copy_basic_hw(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81914a30)
Location: net/core/gen_stats.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81914a30-ffffffff81914a46: gnet_stats_copy_basic_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gnet_stats_copy_basic_hw(const seqcount_t *running, struct gnet_dump *d, struct gnet_stats_basic_cpu *cpu, struct gnet_stats_basic_packed *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81935c00)
Location: net/core/gen_stats.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81935c00-ffffffff81935c16: gnet_stats_copy_basic_hw (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
