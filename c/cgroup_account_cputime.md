# Function: <code>cgroup_account_cputime</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c2eea)
Location: include/linux/cgroup.h:711
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810cbe27)
Location: include/linux/cgroup.h:711
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810cf5e0)
Location: include/linux/cgroup.h:711
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810d51f9)
Location: include/linux/cgroup.h:711
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
In kernel/sched/fair.c (ffffffff810c93b7)
Location: include/linux/cgroup.h:719
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810d3538)
Location: include/linux/cgroup.h:719
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810d7139)
Location: include/linux/cgroup.h:719
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810dd1d6)
Location: include/linux/cgroup.h:719
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
In kernel/sched/fair.c (ffffffff810d37a7)
Location: include/linux/cgroup.h:757
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810dc8d7)
Location: include/linux/cgroup.h:757
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e1685)
Location: include/linux/cgroup.h:757
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810e6e36)
Location: include/linux/cgroup.h:757
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
In kernel/sched/fair.c (ffffffff810dac9a)
Location: include/linux/cgroup.h:772
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e3878)
Location: include/linux/cgroup.h:772
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e813d)
Location: include/linux/cgroup.h:772
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810edaca)
Location: include/linux/cgroup.h:772
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
In kernel/sched/fair.c (ffffffff810e4bba)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810ef2ae)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f350c)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810f96a9)
Location: include/linux/cgroup.h:774
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
In kernel/sched/fair.c (ffffffff810ee1ca)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f8ca7)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fcbf7)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff811037b9)
Location: include/linux/cgroup.h:774
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
In kernel/sched/fair.c (ffffffff810ebfd8)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f6eba)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fb107)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff81101ed9)
Location: include/linux/cgroup.h:774
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
In kernel/sched/fair.c (ffffffff810ee974)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f900a)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fd30f)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff81104249)
Location: include/linux/cgroup.h:774
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
In kernel/sched/fair.c (ffffffff81106fbb)
Location: include/linux/cgroup.h:787
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff81114502)
Location: include/linux/cgroup.h:787
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff811196df)
Location: include/linux/cgroup.h:787
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff8112134b)
Location: include/linux/cgroup.h:787
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
In kernel/sched/fair.c (ffffffff8112414c)
Location: include/linux/cgroup.h:788
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81136175)
Location: include/linux/cgroup.h:788
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff8114407a)
Location: include/linux/cgroup.h:788
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
In kernel/sched/fair.c (ffffffff8114c0ed)
Location: include/linux/cgroup.h:715
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81160755)
Location: include/linux/cgroup.h:715
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff8116fd49)
Location: include/linux/cgroup.h:715
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
In kernel/sched/fair.c (ffffffff8115a37d)
Location: include/linux/cgroup.h:713
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81170e7b)
Location: include/linux/cgroup.h:713
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff8117e6d9)
Location: include/linux/cgroup.h:713
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
In kernel/sched/fair.c (ffffffff81164b5f)
Location: include/linux/cgroup.h:711
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
In kernel/sched/fair.c (ffff8000101448fc)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffff8000101504d4)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffff80001015571c)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffff80001015e054)
Location: include/linux/cgroup.h:774
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
In kernel/sched/fair.c (c0392218)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (c039e15c)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (c03a309c)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (c03a9f08)
Location: include/linux/cgroup.h:774
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
In kernel/sched/fair.c (c000000000195b3c)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (c0000000001a44a4)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (c0000000001a9938)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (c0000000001b2c98)
Location: include/linux/cgroup.h:774
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
In kernel/sched/fair.c (ffffffe0000f14e2)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffe0000f8c56)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffe0000fd2b8)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffe00010255e)
Location: include/linux/cgroup.h:774
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
In kernel/sched/fair.c (ffffffff810ded6a)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e8c37)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810ec90c)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810f2aa9)
Location: include/linux/cgroup.h:774
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
In kernel/sched/fair.c (ffffffff810cdd7a)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810d866e)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810dc9ac)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810e2bb9)
Location: include/linux/cgroup.h:774
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
In kernel/sched/fair.c (ffffffff810db0ea)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e57de)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e9a3c)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810efbd9)
Location: include/linux/cgroup.h:774
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
In kernel/sched/fair.c (ffffffff810e6daa)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810efaf7)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f49ec)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810fac29)
Location: include/linux/cgroup.h:774
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
</details>
</li>
</ul>

## Differences
