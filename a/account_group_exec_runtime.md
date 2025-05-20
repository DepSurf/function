# Function: <code>account_group_exec_runtime</code>

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
In kernel/sched/fair.c (ffffffff810b4b23)
Location: kernel/sched/stats.h:253
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810bfae7)
Location: kernel/sched/stats.h:253
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c21fa)
Location: kernel/sched/stats.h:253
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810c3157)
Location: kernel/sched/stats.h:253
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff810b7693)
Location: kernel/sched/stats.h:258
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810c340e)
Location: kernel/sched/stats.h:258
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c5bcb)
Location: kernel/sched/stats.h:258
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810c6acc)
Location: kernel/sched/stats.h:258
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff810bf9a3)
Location: kernel/sched/stats.h:260
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810c947e)
Location: kernel/sched/stats.h:260
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810cbb8b)
Location: kernel/sched/stats.h:260
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810ccaac)
Location: kernel/sched/stats.h:260
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff810bb355)
Location: include/linux/sched/cputime.h:165
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810c470c)
Location: include/linux/sched/cputime.h:165
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c7e4a)
Location: include/linux/sched/cputime.h:165
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810cd964)
Location: include/linux/sched/cputime.h:165
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff810c2f12)
Location: include/linux/sched/cputime.h:167
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810cbddd)
Location: include/linux/sched/cputime.h:167
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810cf596)
Location: include/linux/sched/cputime.h:167
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810d51b1)
Location: include/linux/sched/cputime.h:167
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff810c93df)
Location: include/linux/sched/cputime.h:167
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810d3508)
Location: include/linux/sched/cputime.h:167
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810d7109)
Location: include/linux/sched/cputime.h:167
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810dd18f)
Location: include/linux/sched/cputime.h:167
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff810d37cf)
Location: include/linux/sched/cputime.h:167
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810dc8a7)
Location: include/linux/sched/cputime.h:167
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e1655)
Location: include/linux/sched/cputime.h:167
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810e6def)
Location: include/linux/sched/cputime.h:167
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff810dacc2)
Location: include/linux/sched/cputime.h:167
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e3848)
Location: include/linux/sched/cputime.h:167
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e810b)
Location: include/linux/sched/cputime.h:167
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810eda7f)
Location: include/linux/sched/cputime.h:167
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff810e4be2)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810ef27f)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f34db)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810f965f)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff810ee1f2)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f8c78)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fcbc6)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff8110376f)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff810ec005)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f6e8b)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fb0d6)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff81101e8f)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff810ee9a4)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f8fdb)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fd2de)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff811041ff)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff81106feb)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff811144d3)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff811196ae)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff81121301)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff81124177)
Location: include/linux/sched/cputime.h:170
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81136144)
Location: include/linux/sched/cputime.h:170
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff81144033)
Location: include/linux/sched/cputime.h:170
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff8114c118)
Location: include/linux/sched/cputime.h:170
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81160724)
Location: include/linux/sched/cputime.h:170
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff8116fd16)
Location: include/linux/sched/cputime.h:170
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff8115a3a8)
Location: include/linux/sched/cputime.h:161
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81170e4a)
Location: include/linux/sched/cputime.h:161
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff8117e6a6)
Location: include/linux/sched/cputime.h:161
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff81164b30)
Location: include/linux/sched/cputime.h:161
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:update_curr_common
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
In kernel/sched/fair.c (ffff800010144920)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffff8000101504a0)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffff8000101556e8)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffff80001015e010)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (c0392248)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (c039e110)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (c03a304c)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (c03a9eac)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (c000000000195b6c)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (c0000000001a4464)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (c0000000001a98f8)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (c0000000001b2c48)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffe0000f1502)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffe0000f8c2c)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffe0000fd28e)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffe000102520)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff810ded92)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e8c08)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810ec8db)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810f2a5f)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff810cdda2)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810d863f)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810dc97b)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810e2b6f)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff810db112)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e57af)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e9a0b)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810efb8f)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
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
In kernel/sched/fair.c (ffffffff810e6ddc)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810efac8)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f49bb)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810fabdf)
Location: include/linux/sched/cputime.h:169
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
</details>
</li>
</ul>

## Differences
