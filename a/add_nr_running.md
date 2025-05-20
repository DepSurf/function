# Function: <code>add_nr_running</code>

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
In kernel/sched/fair.c (ffffffff810b8911)
Location: kernel/sched/sched.h:1313
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810bf5b7)
Location: kernel/sched/sched.h:1313
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c1cf0)
Location: kernel/sched/sched.h:1313
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/sched/stop_task.c (ffffffff810c31a5)
Location: kernel/sched/sched.h:1313
Inline: True
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
In kernel/sched/fair.c (ffffffff810bbf9f)
Location: kernel/sched/sched.h:1360
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810c2ec7)
Location: kernel/sched/sched.h:1360
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c5839)
Location: kernel/sched/sched.h:1360
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/sched/stop_task.c (ffffffff810c6b35)
Location: kernel/sched/sched.h:1360
Inline: True
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
In kernel/sched/fair.c (ffffffff810c253b)
Location: kernel/sched/sched.h:1399
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810c8f27)
Location: kernel/sched/sched.h:1399
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810cb825)
Location: kernel/sched/sched.h:1399
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/sched/stop_task.c (ffffffff810ccb15)
Location: kernel/sched/sched.h:1399
Inline: True
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
In kernel/sched/fair.c (ffffffff810bd180)
Location: kernel/sched/sched.h:1580
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810c2ff7)
Location: kernel/sched/sched.h:1580
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c77d8)
Location: kernel/sched/sched.h:1580
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/sched/stop_task.c (ffffffff810cd805)
Location: kernel/sched/sched.h:1580
Inline: True
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
In kernel/sched/fair.c (ffffffff810c4d32)
Location: kernel/sched/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810ca907)
Location: kernel/sched/sched.h:1619
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810cedc1)
Location: kernel/sched/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/sched/stop_task.c (ffffffff810d5055)
Location: kernel/sched/sched.h:1619
Inline: True
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
In kernel/sched/fair.c (ffffffff810cc7af)
Location: kernel/sched/sched.h:1663
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810d2dc3)
Location: kernel/sched/sched.h:1663
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810d66bf)
Location: kernel/sched/sched.h:1663
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/sched/stop_task.c (ffffffff810dd025)
Location: kernel/sched/sched.h:1663
Inline: True
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
In kernel/sched/fair.c (ffffffff810d4e5b)
Location: kernel/sched/sched.h:1817
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810dcd43)
Location: kernel/sched/sched.h:1817
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810e0bff)
Location: kernel/sched/sched.h:1817
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/sched/stop_task.c (ffffffff810e6c85)
Location: kernel/sched/sched.h:1817
Inline: True
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
In kernel/sched/fair.c (ffffffff810ddd6a)
Location: kernel/sched/sched.h:1879
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810e3cc3)
Location: kernel/sched/sched.h:1879
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810e767c)
Location: kernel/sched/sched.h:1879
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810ed925)
Location: kernel/sched/sched.h:1879
Inline: True
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
In kernel/sched/fair.c (ffffffff810e8441)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810ee473)
Location: kernel/sched/sched.h:1922
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f2c9a)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810f94f5)
Location: kernel/sched/sched.h:1922
Inline: True
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
In kernel/sched/fair.c (ffffffff810f2479)
Location: kernel/sched/sched.h:1955
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810f7a83)
Location: kernel/sched/sched.h:1955
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
```
```
In kernel/sched/deadline.c (ffffffff810fa0e6)
Location: kernel/sched/sched.h:1955
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__enqueue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff81103615)
Location: kernel/sched/sched.h:1955
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:enqueue_task_stop
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
In kernel/sched/fair.c (ffffffff810f062d)
Location: kernel/sched/sched.h:2061
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810f5c63)
Location: kernel/sched/sched.h:2061
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
```
```
In kernel/sched/deadline.c (ffffffff810f84d7)
Location: kernel/sched/sched.h:2061
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__enqueue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff81101d05)
Location: kernel/sched/sched.h:2061
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:enqueue_task_stop
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
In kernel/sched/fair.c (ffffffff810f1dff)
Location: kernel/sched/sched.h:2075
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810f7fc3)
Location: kernel/sched/sched.h:2075
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
```
```
In kernel/sched/deadline.c (ffffffff810fa658)
Location: kernel/sched/sched.h:2075
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__enqueue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff81104075)
Location: kernel/sched/sched.h:2075
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:enqueue_task_stop
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
In kernel/sched/fair.c (ffffffff8110b992)
Location: kernel/sched/sched.h:2366
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff811135f5)
Location: kernel/sched/sched.h:2366
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
```
```
In kernel/sched/deadline.c (ffffffff81115386)
Location: kernel/sched/sched.h:2366
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__enqueue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff81121145)
Location: kernel/sched/sched.h:2366
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:enqueue_task_stop
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
In kernel/sched/fair.c (ffffffff811273e6)
Location: kernel/sched/sched.h:2361
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/build_policy.c (ffffffff81135131)
Location: kernel/sched/sched.h:2361
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff8113ed15)
Location: kernel/sched/sched.h:2361
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:enqueue_task_stop
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
In kernel/sched/fair.c (ffffffff811508c1)
Location: kernel/sched/sched.h:2412
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/build_policy.c (ffffffff8115f681)
Location: kernel/sched/sched.h:2412
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff81169145)
Location: kernel/sched/sched.h:2412
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:enqueue_task_stop
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
In kernel/sched/fair.c (ffffffff8115f771)
Location: kernel/sched/sched.h:2458
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/build_policy.c (ffffffff8116fdfa)
Location: kernel/sched/sched.h:2458
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff81179955)
Location: kernel/sched/sched.h:2458
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:enqueue_task_stop
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
In kernel/sched/fair.c (ffffffff8116dd01)
Location: kernel/sched/sched.h:2510
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/build_policy.c (ffffffff8117d3e1)
Location: kernel/sched/sched.h:2510
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff8118bca5)
Location: kernel/sched/sched.h:2510
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:enqueue_task_stop
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
In kernel/sched/fair.c (ffff800010147514)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffff80001014f3b8)
Location: kernel/sched/sched.h:1922
Inline: True
```
```
In kernel/sched/deadline.c (ffff800010154f10)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/sched/stop_task.c (ffff80001015de50)
Location: kernel/sched/sched.h:1922
Inline: True
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
In kernel/sched/fair.c (c0395aa4)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (c039d638)
Location: kernel/sched/sched.h:1922
Inline: True
```
```
In kernel/sched/deadline.c (c03a23a0)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/sched/stop_task.c (c03a9d70)
Location: kernel/sched/sched.h:1922
Inline: True
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
In kernel/sched/fair.c (c000000000199b40)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (c0000000001a3628)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
```
```
In kernel/sched/deadline.c (c0000000001a8dd8)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/sched/stop_task.c (c0000000001b2b18)
Location: kernel/sched/sched.h:1922
Inline: True
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
In kernel/sched/fair.c (ffffffe0000f2d60)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffe0000f7310)
Location: kernel/sched/sched.h:1922
Inline: True
```
```
In kernel/sched/deadline.c (ffffffe0000fc9ae)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffe000102416)
Location: kernel/sched/sched.h:1922
Inline: True
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
In kernel/sched/fair.c (ffffffff810e25f1)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810e8153)
Location: kernel/sched/sched.h:1922
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810ec09a)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810f28f5)
Location: kernel/sched/sched.h:1922
Inline: True
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
In kernel/sched/fair.c (ffffffff810d16d1)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810d76d3)
Location: kernel/sched/sched.h:1922
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810dc0ba)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810e29b5)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:enqueue_task_stop
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
In kernel/sched/fair.c (ffffffff810de971)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810e49a3)
Location: kernel/sched/sched.h:1922
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810e91ca)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810efa25)
Location: kernel/sched/sched.h:1922
Inline: True
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
In kernel/sched/fair.c (ffffffff810ea481)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810f0e13)
Location: kernel/sched/sched.h:1922
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f417a)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810faa75)
Location: kernel/sched/sched.h:1922
Inline: True
```
</details>
</li>
</ul>

## Differences
