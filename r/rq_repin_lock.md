# Function: <code>rq_repin_lock</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3da5)
Location: kernel/sched/sched.h:938
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
```
```
In kernel/sched/fair.c (ffffffff810c109b)
Location: kernel/sched/sched.h:938
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810c4bc4)
Location: kernel/sched/sched.h:938
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810c8204)
Location: kernel/sched/sched.h:938
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/core.c (ffffffff810bb04d)
Location: kernel/sched/sched.h:952
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
```
```
In kernel/sched/fair.c (ffffffff810c8805)
Location: kernel/sched/sched.h:952
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810cc274)
Location: kernel/sched/sched.h:952
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810cf9ea)
Location: kernel/sched/sched.h:952
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/core.c (ffffffff810c251e)
Location: kernel/sched/sched.h:1035
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
```
```
In kernel/sched/fair.c (ffffffff810d100d)
Location: kernel/sched/sched.h:1035
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810d3f99)
Location: kernel/sched/sched.h:1035
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810d7593)
Location: kernel/sched/sched.h:1035
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/core.c (ffffffff810cb80e)
Location: kernel/sched/sched.h:1093
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
```
```
In kernel/sched/fair.c (ffffffff810da674)
Location: kernel/sched/sched.h:1093
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810ddc39)
Location: kernel/sched/sched.h:1093
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810e1b8d)
Location: kernel/sched/sched.h:1093
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/core.c (ffffffff810d382f)
Location: kernel/sched/sched.h:1151
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
```
```
In kernel/sched/fair.c (ffffffff810e1b51)
Location: kernel/sched/sched.h:1151
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810e4c3c)
Location: kernel/sched/sched.h:1151
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810e8666)
Location: kernel/sched/sched.h:1151
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/core.c (ffffffff810ddd78)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
```
```
In kernel/sched/fair.c (ffffffff810ec321)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffffffff810efe49)
Location: kernel/sched/sched.h:1159
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f21c9)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/core.c (ffffffff810e3059)
Location: kernel/sched/sched.h:1207
Inline: True
Inline callers:
  - kernel/sched/core.c:migrate_tasks
  - kernel/sched/core.c:migrate_tasks
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_wakeup
```
```
In kernel/sched/fair.c (ffffffff810f5fa4)
Location: kernel/sched/sched.h:1207
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffffffff810f9799)
Location: kernel/sched/sched.h:1207
Inline: True
Inline callers:
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff810fd489)
Location: kernel/sched/sched.h:1207
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/core.c (ffffffff810e24f4)
Location: kernel/sched/sched.h:1265
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_wakeup
```
```
In kernel/sched/fair.c (ffffffff810f40fe)
Location: kernel/sched/sched.h:1265
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffffffff810f7b55)
Location: kernel/sched/sched.h:1265
Inline: True
Inline callers:
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff810fba53)
Location: kernel/sched/sched.h:1265
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/core.c (ffffffff810e42a6)
Location: kernel/sched/sched.h:1278
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_wakeup
```
```
In kernel/sched/fair.c (ffffffff810f5a57)
Location: kernel/sched/sched.h:1278
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffffffff810f9945)
Location: kernel/sched/sched.h:1278
Inline: True
Inline callers:
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff810fdd73)
Location: kernel/sched/sched.h:1278
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/core.c (ffffffff810fafb6)
Location: kernel/sched/sched.h:1565
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_wakeup
```
```
In kernel/sched/fair.c (ffffffff8110f533)
Location: kernel/sched/sched.h:1565
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffffffff811131a5)
Location: kernel/sched/sched.h:1565
Inline: True
Inline callers:
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff811162b3)
Location: kernel/sched/sched.h:1565
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/core.c (ffffffff8111740f)
Location: kernel/sched/sched.h:1546
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_wakeup
```
```
In kernel/sched/fair.c (ffffffff8112b653)
Location: kernel/sched/sched.h:1546
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/build_policy.c (ffffffff8112fece)
Location: kernel/sched/sched.h:1546
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:balance_rt
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
In kernel/sched/core.c (ffffffff8113e93d)
Location: kernel/sched/sched.h:1592
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_wakeup
```
```
In kernel/sched/fair.c (ffffffff81155023)
Location: kernel/sched/sched.h:1592
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/build_policy.c (ffffffff81159f9e)
Location: kernel/sched/sched.h:1592
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:balance_rt
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
In kernel/sched/core.c (ffffffff811514d5)
Location: kernel/sched/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff811651cf)
Location: kernel/sched/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/build_policy.c (ffffffff8116a1ae)
Location: kernel/sched/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:balance_rt
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
In kernel/sched/core.c (ffffffff8115d368)
Location: kernel/sched/sched.h:1638
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff81171f1f)
Location: kernel/sched/sched.h:1638
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/build_policy.c (ffffffff8117786e)
Location: kernel/sched/sched.h:1638
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:balance_rt
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
In kernel/sched/core.c (ffff80001013d6cc)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
```
```
In kernel/sched/fair.c (ffff80001014c7ec)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffff800010151404)
Location: kernel/sched/sched.h:1159
Inline: True
```
```
In kernel/sched/deadline.c (ffff800010153e18)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/core.c (c038d6f8)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
```
```
In kernel/sched/fair.c (c039a4ac)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (c039c648)
Location: kernel/sched/sched.h:1159
Inline: True
```
```
In kernel/sched/deadline.c (c03a0138)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/core.c (c00000000018c538)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
```
```
In kernel/sched/fair.c (c00000000019f238)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (c0000000001a22c8)
Location: kernel/sched/sched.h:1159
Inline: True
```
```
In kernel/sched/deadline.c (c0000000001a6c94)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/core.c (ffffffe0000eac8e)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
```
```
In kernel/sched/fair.c (ffffffe0000f5d18)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffffffe0000f96fe)
Location: kernel/sched/sched.h:1159
Inline: True
```
```
In kernel/sched/deadline.c (ffffffe0000fbace)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/core.c (ffffffff810d7f68)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
```
```
In kernel/sched/fair.c (ffffffff810e6481)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffffffff810e9739)
Location: kernel/sched/sched.h:1159
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810eb5c9)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/core.c (ffffffff810c6939)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
```
```
In kernel/sched/fair.c (ffffffff810d5621)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffffffff810d9209)
Location: kernel/sched/sched.h:1159
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810db5e9)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/core.c (ffffffff810d4758)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
```
```
In kernel/sched/fair.c (ffffffff810e2851)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffffffff810e6379)
Location: kernel/sched/sched.h:1159
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810e86f9)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/core.c (ffffffff810dfb61)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
```
```
In kernel/sched/fair.c (ffffffff810ee294)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffffffff810f0099)
Location: kernel/sched/sched.h:1159
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f29e9)
Location: kernel/sched/sched.h:1159
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
```
</details>
</li>
</ul>

## Differences
