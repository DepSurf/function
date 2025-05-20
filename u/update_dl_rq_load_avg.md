# Function: <code>update_dl_rq_load_avg</code>

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
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810e77c0)
Location: kernel/sched/pelt.c:341
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff810e77c0-ffffffff810e79d7: update_dl_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810ee6a0)
Location: kernel/sched/pelt.c:341
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff810ee6a0-ffffffff810ee955: update_dl_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810fa280)
Location: kernel/sched/pelt.c:341
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff810fa280-ffffffff810fa535: update_dl_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff81104560)
Location: kernel/sched/pelt.c:380
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff81104560-ffffffff811048cc: update_dl_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff81102bf0)
Location: kernel/sched/pelt.c:376
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff81102bf0-ffffffff81102f44: update_dl_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff81104f40)
Location: kernel/sched/pelt.c:376
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff81104f40-ffffffff81105281: update_dl_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff81122930)
Location: kernel/sched/pelt.c:376
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff81122930-ffffffff81122ef6: update_dl_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81138640)
Location: kernel/sched/pelt.c:372
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff81138640-ffffffff81138c16: update_dl_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81162cd0)
Location: kernel/sched/pelt.c:372
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff81162cd0-ffffffff811632a6: update_dl_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81173450)
Location: kernel/sched/pelt.c:372
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff81173450-ffffffff81173a75: update_dl_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81180d80)
Location: kernel/sched/pelt.c:372
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff81180d80-ffffffff811813a5: update_dl_rq_load_avg (STB_GLOBAL)
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
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffff80001015ec60)
Location: kernel/sched/pelt.c:341
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffff80001015ec60-ffff80001015ef18: update_dl_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (c03ab32c)
Location: kernel/sched/pelt.c:341
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
c03ab32c-c03ab7f0: update_dl_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (c0000000001b3e80)
Location: kernel/sched/pelt.c:341
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
c0000000001b3e80-c0000000001b4294: update_dl_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffe00010301a)
Location: kernel/sched/pelt.c:341
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffe00010301a-ffffffe0001032a0: update_dl_rq_load_avg (STB_GLOBAL)
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
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810f3680)
Location: kernel/sched/pelt.c:341
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff810f3680-ffffffff810f3935: update_dl_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810e3790)
Location: kernel/sched/pelt.c:341
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff810e3790-ffffffff810e3a45: update_dl_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810f07b0)
Location: kernel/sched/pelt.c:341
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff810f07b0-ffffffff810f0a65: update_dl_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int update_dl_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810fb850)
Location: kernel/sched/pelt.c:341
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff810fb850-ffffffff810fbb14: update_dl_rq_load_avg (STB_GLOBAL)
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
