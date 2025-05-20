# Function: <code>sub_nr_running</code>

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
In kernel/sched/fair.c (ffffffff810b76d7)
Location: kernel/sched/sched.h:1341
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810bf8dd)
Location: kernel/sched/sched.h:1341
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c205b)
Location: kernel/sched/sched.h:1341
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810c3086)
Location: kernel/sched/sched.h:1341
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff810bb30c)
Location: kernel/sched/sched.h:1376
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810c320d)
Location: kernel/sched/sched.h:1376
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c5a97)
Location: kernel/sched/sched.h:1376
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810c6a16)
Location: kernel/sched/sched.h:1376
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff810c1658)
Location: kernel/sched/sched.h:1415
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810c926d)
Location: kernel/sched/sched.h:1415
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810cba63)
Location: kernel/sched/sched.h:1415
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810cc9f6)
Location: kernel/sched/sched.h:1415
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff810bc418)
Location: kernel/sched/sched.h:1596
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810c32fd)
Location: kernel/sched/sched.h:1596
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c58f1)
Location: kernel/sched/sched.h:1596
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810cd7a6)
Location: kernel/sched/sched.h:1596
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff810c425e)
Location: kernel/sched/sched.h:1635
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810ca959)
Location: kernel/sched/sched.h:1635
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810cd011)
Location: kernel/sched/sched.h:1635
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810d4ff6)
Location: kernel/sched/sched.h:1635
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff810ca966)
Location: kernel/sched/sched.h:1679
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810d2679)
Location: kernel/sched/sched.h:1679
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810d4f6e)
Location: kernel/sched/sched.h:1679
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810dcfc5)
Location: kernel/sched/sched.h:1679
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff810d5053)
Location: kernel/sched/sched.h:1833
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810dbfe9)
Location: kernel/sched/sched.h:1833
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810de91e)
Location: kernel/sched/sched.h:1833
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810e6c25)
Location: kernel/sched/sched.h:1833
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff810dc59b)
Location: kernel/sched/sched.h:1895
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810e2fbd)
Location: kernel/sched/sched.h:1895
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810e5a98)
Location: kernel/sched/sched.h:1895
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810ed8b5)
Location: kernel/sched/sched.h:1895
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff810e69d0)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810ed9ad)
Location: kernel/sched/sched.h:1938
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f0ebe)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810f9485)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff810f0b47)
Location: kernel/sched/sched.h:1971
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810f7755)
Location: kernel/sched/sched.h:1971
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f9fae)
Location: kernel/sched/sched.h:1971
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff811035a5)
Location: kernel/sched/sched.h:1971
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff810ef717)
Location: kernel/sched/sched.h:2080
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810f5567)
Location: kernel/sched/sched.h:2080
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f835f)
Location: kernel/sched/sched.h:2080
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff81101ce5)
Location: kernel/sched/sched.h:2080
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff810f1128)
Location: kernel/sched/sched.h:2094
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810f7637)
Location: kernel/sched/sched.h:2094
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810fa4cf)
Location: kernel/sched/sched.h:2094
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff81104055)
Location: kernel/sched/sched.h:2094
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff8110ac2f)
Location: kernel/sched/sched.h:2385
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff81111a77)
Location: kernel/sched/sched.h:2385
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_top_rt_rq
```
```
In kernel/sched/deadline.c (ffffffff8111564a)
Location: kernel/sched/sched.h:2385
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff811211a5)
Location: kernel/sched/sched.h:2385
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff81126595)
Location: kernel/sched/sched.h:2380
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/build_policy.c (ffffffff81135e5a)
Location: kernel/sched/sched.h:2380
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__dequeue_dl_entity
  - kernel/sched/build_policy.c:__dequeue_dl_entity
  - kernel/sched/build_policy.c:dequeue_top_rt_rq
  - kernel/sched/build_policy.c:dequeue_top_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff8113fbf5)
Location: kernel/sched/sched.h:2380
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff8114f9d5)
Location: kernel/sched/sched.h:2431
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/build_policy.c (ffffffff8116044c)
Location: kernel/sched/sched.h:2431
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:dequeue_top_rt_rq
  - kernel/sched/build_policy.c:dequeue_top_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff81169105)
Location: kernel/sched/sched.h:2431
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff8115e825)
Location: kernel/sched/sched.h:2477
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/build_policy.c (ffffffff81170b6c)
Location: kernel/sched/sched.h:2477
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:dequeue_top_rt_rq
  - kernel/sched/build_policy.c:dequeue_top_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff81179915)
Location: kernel/sched/sched.h:2477
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff8116ce12)
Location: kernel/sched/sched.h:2529
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/build_policy.c (ffffffff8117e456)
Location: kernel/sched/sched.h:2529
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__dequeue_dl_entity
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff8118bb25)
Location: kernel/sched/sched.h:2529
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffff8000101468f8)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffff80001014e758)
Location: kernel/sched/sched.h:1938
Inline: True
```
```
In kernel/sched/deadline.c (ffff800010152e98)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffff80001015dda0)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (c0394c28)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (c039bca0)
Location: kernel/sched/sched.h:1938
Inline: True
```
```
In kernel/sched/deadline.c (c039f8c0)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (c03a9bfc)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (c000000000197cd0)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (c0000000001a0bac)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_top_rt_rq
```
```
In kernel/sched/deadline.c (c0000000001a63d0)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (c0000000001b29b8)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffe0000f230a)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffe0000f7380)
Location: kernel/sched/sched.h:1938
Inline: True
```
```
In kernel/sched/deadline.c (ffffffe0000fa7be)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffe0001022de)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff810e0b80)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810e77ed)
Location: kernel/sched/sched.h:1938
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810ea2be)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810f2885)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff810cfc00)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810d6d73)
Location: kernel/sched/sched.h:1938
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810da271)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810e2955)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff810dcf00)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810e3edd)
Location: kernel/sched/sched.h:1938
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810e73ee)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810ef9b5)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff810e8c70)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810efa3d)
Location: kernel/sched/sched.h:1938
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f23ae)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810faa05)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
```
</details>
</li>
</ul>

## Differences
