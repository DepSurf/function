# Function: <code>requeue_rt_entity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810bf052)
Location: kernel/sched/rt.c:1284
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:task_tick_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c3cf3)
Location: kernel/sched/rt.c:1346
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c9d5f)
Location: kernel/sched/rt.c:1345
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c4a6f)
Location: kernel/sched/rt.c:1357
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810cc11f)
Location: kernel/sched/rt.c:1347
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d37b1)
Location: kernel/sched/rt.c:1356
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810dcb56)
Location: kernel/sched/rt.c:1356
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e3b01)
Location: kernel/sched/rt.c:1356
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void requeue_rt_entity(struct rt_rq *rt_rq, struct sched_rt_entity *rt_se, int head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ed2a0)
Location: kernel/sched/rt.c:1357
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
```
**Symbols:**

```
ffffffff810ed2a0-ffffffff810ed30d: requeue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f7866)
Location: kernel/sched/rt.c:1398
Inline: True
Inline callers:
  - kernel/sched/rt.c:yield_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f5a36)
Location: kernel/sched/rt.c:1400
Inline: True
Inline callers:
  - kernel/sched/rt.c:yield_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f7b06)
Location: kernel/sched/rt.c:1400
Inline: True
Inline callers:
  - kernel/sched/rt.c:yield_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff81112267)
Location: kernel/sched/rt.c:1415
Inline: True
Inline callers:
  - kernel/sched/rt.c:yield_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8112f457)
Location: kernel/sched/rt.c:1570
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:yield_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81159207)
Location: kernel/sched/rt.c:1566
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:yield_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811694c7)
Location: kernel/sched/rt.c:1566
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:yield_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81176687)
Location: kernel/sched/rt.c:1511
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:yield_task_rt
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
void requeue_rt_entity(struct rt_rq *rt_rq, struct sched_rt_entity *rt_se, int head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff80001014de00)
Location: kernel/sched/rt.c:1357
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
```
**Symbols:**

```
ffff80001014de00-ffff80001014deb4: requeue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void requeue_rt_entity(struct rt_rq *rt_rq, struct sched_rt_entity *rt_se, int head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039c978)
Location: kernel/sched/rt.c:1357
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
```
**Symbols:**

```
c039c978-c039c9ec: requeue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void requeue_rt_entity(struct rt_rq *rt_rq, struct sched_rt_entity *rt_se, int head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a0950)
Location: kernel/sched/rt.c:1357
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
```
**Symbols:**

```
c0000000001a0950-c0000000001a09ec: requeue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void requeue_rt_entity(struct rt_rq *rt_rq, struct sched_rt_entity *rt_se, int head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f6ae4)
Location: kernel/sched/rt.c:1357
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
```
**Symbols:**

```
ffffffe0000f6ae4-ffffffe0000f6b68: requeue_rt_entity (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e8ec1)
Location: kernel/sched/rt.c:1357
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void requeue_rt_entity(struct rt_rq *rt_rq, struct sched_rt_entity *rt_se, int head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d65a0)
Location: kernel/sched/rt.c:1357
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
```
**Symbols:**

```
ffffffff810d65a0-ffffffff810d660d: requeue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void requeue_rt_entity(struct rt_rq *rt_rq, struct sched_rt_entity *rt_se, int head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e37d0)
Location: kernel/sched/rt.c:1357
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
```
**Symbols:**

```
ffffffff810e37d0-ffffffff810e383d: requeue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f0a55)
Location: kernel/sched/rt.c:1357
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
</ul>
