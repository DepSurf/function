# Function: <code>rq_clock_skip_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aae30)
Location: kernel/sched/sched.h:730
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810b4e50)
Location: kernel/sched/sched.h:730
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/rt.c (ffffffff810bff14)
Location: kernel/sched/sched.h:730
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff810c23b3)
Location: kernel/sched/sched.h:730
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ada6e)
Location: kernel/sched/sched.h:754
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810b7963)
Location: kernel/sched/sched.h:754
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/rt.c (ffffffff810c3896)
Location: kernel/sched/sched.h:754
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff810c5dcb)
Location: kernel/sched/sched.h:754
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3b69)
Location: kernel/sched/sched.h:786
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810bfc73)
Location: kernel/sched/sched.h:786
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/rt.c (ffffffff810c98f8)
Location: kernel/sched/sched.h:786
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff810cbd8b)
Location: kernel/sched/sched.h:786
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810afaa7)
Location: kernel/sched/sched.h:896
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810bb693)
Location: kernel/sched/sched.h:896
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/rt.c (ffffffff810c38db)
Location: kernel/sched/sched.h:896
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff810c835b)
Location: kernel/sched/sched.h:896
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b6e7d)
Location: kernel/sched/sched.h:910
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810c33f3)
Location: kernel/sched/sched.h:910
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/rt.c (ffffffff810cb094)
Location: kernel/sched/sched.h:910
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffff810cfa88)
Location: kernel/sched/sched.h:910
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810be9e2)
Location: kernel/sched/sched.h:986
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810c98f3)
Location: kernel/sched/sched.h:986
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/deadline.c (ffffffff810d73b8)
Location: kernel/sched/sched.h:986
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c7c82)
Location: kernel/sched/sched.h:1044
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810d3ca3)
Location: kernel/sched/sched.h:1044
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/deadline.c (ffffffff810e18a8)
Location: kernel/sched/sched.h:1044
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf005)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810db193)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/deadline.c (ffffffff810e8368)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8dc5)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810e50a3)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/deadline.c (ffffffff810f3738)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e24b3)
Location: kernel/sched/sched.h:1158
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810ee613)
Location: kernel/sched/sched.h:1158
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/deadline.c (ffffffff810fce48)
Location: kernel/sched/sched.h:1158
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df86b)
Location: kernel/sched/sched.h:1201
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810ec453)
Location: kernel/sched/sched.h:1201
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/deadline.c (ffffffff810fb358)
Location: kernel/sched/sched.h:1201
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e165b)
Location: kernel/sched/sched.h:1214
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810eedf3)
Location: kernel/sched/sched.h:1214
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/deadline.c (ffffffff810fd5d8)
Location: kernel/sched/sched.h:1214
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f778b)
Location: kernel/sched/sched.h:1501
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff81107493)
Location: kernel/sched/sched.h:1501
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/deadline.c (ffffffff811199d8)
Location: kernel/sched/sched.h:1501
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811139a9)
Location: kernel/sched/sched.h:1482
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff811246b3)
Location: kernel/sched/sched.h:1482
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/build_policy.c (ffffffff81136458)
Location: kernel/sched/sched.h:1482
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113ab69)
Location: kernel/sched/sched.h:1528
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff8114c6b3)
Location: kernel/sched/sched.h:1528
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/build_policy.c (ffffffff81160a48)
Location: kernel/sched/sched.h:1528
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81149ec9)
Location: kernel/sched/sched.h:1533
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff8115a943)
Location: kernel/sched/sched.h:1533
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/build_policy.c (ffffffff81171188)
Location: kernel/sched/sched.h:1533
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811559c9)
Location: kernel/sched/sched.h:1552
Inline: True
Inline callers:
  - kernel/sched/core.c:wakeup_preempt
```
```
In kernel/sched/fair.c (ffffffff81164cb9)
Location: kernel/sched/sched.h:1552
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/build_policy.c (ffffffff8117e9a0)
Location: kernel/sched/sched.h:1552
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:yield_task_dl
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013904c)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffff800010145098)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/deadline.c (ffff800010155988)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c03883bc)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (c0392a04)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/deadline.c (c03a33d0)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0000000001856fc)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (c0000000001961f4)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/deadline.c (c0000000001a9bc4)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e8dc6)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffe0000f1a4a)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/deadline.c (ffffffe0000fd4b6)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3295)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810df253)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/deadline.c (ffffffff810ecb38)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c18c5)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810ce263)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/deadline.c (ffffffff810dcbd8)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d0975)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810db5d3)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/deadline.c (ffffffff810e9c68)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810daa15)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810e72c3)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_task_fair
```
```
In kernel/sched/deadline.c (ffffffff810f4c28)
Location: kernel/sched/sched.h:1110
Inline: True
Inline callers:
  - kernel/sched/deadline.c:yield_task_dl
```
</details>
</li>
</ul>

## Differences
