# Function: <code>trace_sched_update_nr_running_tp_enabled</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ef71d)
Location: include/trace/events/sched.h:733
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810f5c74)
Location: include/trace/events/sched.h:733
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
```
```
In kernel/sched/deadline.c (ffffffff810f835f)
Location: include/trace/events/sched.h:733
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff81101ce9)
Location: include/trace/events/sched.h:733
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff810f112e)
Location: include/trace/events/sched.h:733
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810f7fd4)
Location: include/trace/events/sched.h:733
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
```
```
In kernel/sched/deadline.c (ffffffff810fa4cf)
Location: include/trace/events/sched.h:733
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff81104059)
Location: include/trace/events/sched.h:733
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff8110ac37)
Location: include/trace/events/sched.h:731
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff81113606)
Location: include/trace/events/sched.h:731
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
  - kernel/sched/rt.c:dequeue_top_rt_rq
```
```
In kernel/sched/deadline.c (ffffffff8111564a)
Location: include/trace/events/sched.h:731
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff811211a9)
Location: include/trace/events/sched.h:731
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff8112659d)
Location: include/trace/events/sched.h:734
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/build_policy.c (ffffffff8113513f)
Location: include/trace/events/sched.h:734
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:__dequeue_dl_entity
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
  - kernel/sched/build_policy.c:dequeue_top_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff8113fbf9)
Location: include/trace/events/sched.h:734
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff8114f9dd)
Location: include/trace/events/sched.h:734
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/build_policy.c (ffffffff8116044c)
Location: include/trace/events/sched.h:734
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
  - kernel/sched/build_policy.c:dequeue_top_rt_rq
  - kernel/sched/build_policy.c:dequeue_top_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff81169109)
Location: include/trace/events/sched.h:734
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff8115e82d)
Location: include/trace/events/sched.h:734
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/build_policy.c (ffffffff81170b6c)
Location: include/trace/events/sched.h:734
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
  - kernel/sched/build_policy.c:dequeue_top_rt_rq
  - kernel/sched/build_policy.c:dequeue_top_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff81179919)
Location: include/trace/events/sched.h:734
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:dequeue_task_stop
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
In kernel/sched/fair.c (ffffffff8116ce1a)
Location: include/trace/events/sched.h:783
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/build_policy.c (ffffffff8117d3e9)
Location: include/trace/events/sched.h:783
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:__dequeue_dl_entity
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff8118bb35)
Location: include/trace/events/sched.h:783
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:dequeue_task_stop
  - kernel/sched/build_utility.c:enqueue_task_stop
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
