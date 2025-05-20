# Function: <code>update_curr_rt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810bfa80)
Location: kernel/sched/rt.c:939
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:put_prev_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff810bfa80-ffffffff810bfc4b: update_curr_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c33b0)
Location: kernel/sched/rt.c:947
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff810c33b0-ffffffff810c35d8: update_curr_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c9420)
Location: kernel/sched/rt.c:947
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff810c9420-ffffffff810c963a: update_curr_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c46a0)
Location: kernel/sched/rt.c:959
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff810c46a0-ffffffff810c4976: update_curr_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810cbd40)
Location: kernel/sched/rt.c:949
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff810cbd40-ffffffff810cc02c: update_curr_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:952
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff810d34a0-ffffffff810d36b9: update_curr_rt (STB_LOCAL)
ffffffff810d484b-ffffffff810d4869: update_curr_rt.cold.57 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:954
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff810dc840-ffffffff810dca41: update_curr_rt (STB_LOCAL)
ffffffff810de27b-ffffffff810de299: update_curr_rt.cold.58 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:954
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff810e37e0-ffffffff810e39e2: update_curr_rt (STB_LOCAL)
ffffffff810e52db-ffffffff810e52f9: update_curr_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:955
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff810ef210-ffffffff810ef527: update_curr_rt (STB_LOCAL)
ffffffff810f0775-ffffffff810f0794: update_curr_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:996
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff810f8c10-ffffffff810f8e27: update_curr_rt (STB_LOCAL)
ffffffff810f9c2c-ffffffff810f9c44: update_curr_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:997
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff810f6e20-ffffffff810f7016: update_curr_rt (STB_LOCAL)
ffffffff81bdc841-ffffffff81bdc859: update_curr_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:997
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff810f8f70-ffffffff810f9165: update_curr_rt (STB_LOCAL)
ffffffff81bce9bc-ffffffff81bce9d4: update_curr_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:1008
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff81114460-ffffffff81114732: update_curr_rt (STB_LOCAL)
ffffffff81ca68b1-ffffffff81ca68fc: update_curr_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:1045
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff81131a70-ffffffff81131d9f: update_curr_rt (STB_LOCAL)
ffffffff81e5616d-ffffffff81e561b2: update_curr_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:1045
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff8115bac0-ffffffff8115bdf7: update_curr_rt (STB_LOCAL)
ffffffff82057386-ffffffff820573b8: update_curr_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:1045
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff8116bc90-ffffffff8116bfc7: update_curr_rt (STB_LOCAL)
ffffffff820d5bac-ffffffff820d5bde: update_curr_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:1001
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff81176c60-ffffffff81176f10: update_curr_rt (STB_LOCAL)
ffffffff821b0b8c-ffffffff821b0bbe: update_curr_rt.cold (STB_LOCAL)
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
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff800010150428)
Location: kernel/sched/rt.c:955
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffff800010150428-ffff800010150788: update_curr_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039e060)
Location: kernel/sched/rt.c:955
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
c039e060-c039e44c: update_curr_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a43e0)
Location: kernel/sched/rt.c:955
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
c0000000001a43e0-c0000000001a4840: update_curr_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f8b9e)
Location: kernel/sched/rt.c:955
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffffffe0000f8b9e-ffffffe0000f8e5c: update_curr_rt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:955
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff810e8ba0-ffffffff810e8da1: update_curr_rt (STB_LOCAL)
ffffffff810e9b7c-ffffffff810e9b9a: update_curr_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:955
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff810d85d0-ffffffff810d88e7: update_curr_rt (STB_LOCAL)
ffffffff810d9b35-ffffffff810d9b54: update_curr_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:955
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff810e5740-ffffffff810e5a57: update_curr_rt (STB_LOCAL)
ffffffff810e6ca5-ffffffff810e6cc4: update_curr_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void update_curr_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:955
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
**Symbols:**

```
ffffffff810efa60-ffffffff810efc69: update_curr_rt (STB_LOCAL)
ffffffff810f1c09-ffffffff810f1c27: update_curr_rt.cold (STB_LOCAL)
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
