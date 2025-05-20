# Function: <code>has_group_leader_pid</code>

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
In kernel/exit.c (ffffffff810827c9)
Location: include/linux/sched.h:2703
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f2810)
Location: include/linux/sched.h:2703
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:check_clock
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:2703
Inline: True
```
```
In fs/proc/base.c (ffffffff8127c9c4)
Location: include/linux/sched.h:2703
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
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
In kernel/exit.c (ffffffff810857f8)
Location: include/linux/sched.h:2972
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f9920)
Location: include/linux/sched.h:2972
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:check_clock
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:2972
Inline: True
```
```
In fs/proc/base.c (ffffffff812a956c)
Location: include/linux/sched.h:2972
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
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
In kernel/exit.c (ffffffff8108a776)
Location: include/linux/sched.h:3086
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811072b0)
Location: include/linux/sched.h:3086
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:check_clock
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:3086
Inline: True
```
```
In fs/proc/base.c (ffffffff812bee6c)
Location: include/linux/sched.h:3086
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
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
In kernel/exit.c (ffffffff810874d9)
Location: include/linux/sched/signal.h:546
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8110967f)
Location: include/linux/sched/signal.h:546
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In fs/exec.c (0)
Location: include/linux/sched/signal.h:546
Inline: True
```
```
In fs/proc/base.c (ffffffff812cbc3e)
Location: include/linux/sched/signal.h:546
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
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
In kernel/exit.c (ffffffff8108e269)
Location: include/linux/sched/signal.h:547
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8111484f)
Location: include/linux/sched/signal.h:547
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In fs/exec.c (0)
Location: include/linux/sched/signal.h:547
Inline: True
```
```
In fs/proc/base.c (ffffffff812f04de)
Location: include/linux/sched/signal.h:547
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
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
In kernel/exit.c (ffffffff81091d29)
Location: include/linux/sched/signal.h:575
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81120ff2)
Location: include/linux/sched/signal.h:575
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:check_clock
```
```
In fs/exec.c (ffffffff812a25da)
Location: include/linux/sched/signal.h:575
Inline: True
```
```
In fs/proc/base.c (ffffffff8131d8cc)
Location: include/linux/sched/signal.h:575
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
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
In kernel/exit.c (ffffffff8109a019)
Location: include/linux/sched/signal.h:617
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112c712)
Location: include/linux/sched/signal.h:617
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:check_clock
```
```
In fs/exec.c (ffffffff812b71b9)
Location: include/linux/sched/signal.h:617
Inline: True
```
```
In fs/proc/base.c (ffffffff8133465e)
Location: include/linux/sched/signal.h:617
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
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
In kernel/exit.c (ffffffff8109e634)
Location: include/linux/sched/signal.h:648
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811370b2)
Location: include/linux/sched/signal.h:648
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:check_clock
```
```
In fs/exec.c (ffffffff812d4bb2)
Location: include/linux/sched/signal.h:648
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffff8135cc2c)
Location: include/linux/sched/signal.h:648
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
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
In kernel/exit.c (ffffffff810a4bbd)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811431ab)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In fs/exec.c (ffffffff812e6732)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffff8137505c)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/exit.c (ffff8000100faa4c)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ad278)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In fs/exec.c (ffff80001038ea34)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffff80001043e974)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
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
In kernel/exit.c (c0358830)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-cpu-timers.c (c03f8218)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In fs/exec.c (c0574f9c)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (c0605b84)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
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
In kernel/exit.c (c000000000141da8)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-cpu-timers.c (c0000000002114f0)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In fs/exec.c (c000000000485964)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (c0000000005544c0)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
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
In kernel/exit.c (ffffffe0000c4842)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffe0001372de)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In fs/exec.c (ffffffe00025e506)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffe0002d6476)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
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
In kernel/exit.c (ffffffff8109e4dd)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113b95b)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In fs/exec.c (ffffffff812ded12)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffff8136d63c)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
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
In kernel/exit.c (ffffffff8108cefc)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112e31b)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In fs/exec.c (ffffffff812cee37)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffff8135e0cc)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
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
In kernel/exit.c (ffffffff8109e48d)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113967b)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In fs/exec.c (ffffffff812dcb22)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffff8136b10c)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
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
In kernel/exit.c (ffffffff810a63a7)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81146129)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In fs/exec.c (ffffffff812ed8cb)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffff8137e953)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
```
</details>
</li>
</ul>

## Differences
