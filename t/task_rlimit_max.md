# Function: <code>task_rlimit_max</code>

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
In kernel/sched/rt.c (ffffffff810c01f5)
Location: include/linux/sched.h:3179
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
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
In kernel/sched/rt.c (ffffffff810c3c25)
Location: include/linux/sched.h:3456
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In mm/mmap.c (ffffffff811e2ac6)
Location: include/linux/sched.h:3456
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
In kernel/sched/rt.c (ffffffff810c9c95)
Location: include/linux/sched.h:3641
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In mm/mmap.c (ffffffff811f2a96)
Location: include/linux/sched.h:3641
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
In kernel/sched/rt.c (ffffffff810c49a6)
Location: include/linux/sched/signal.h:596
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In mm/mmap.c (ffffffff811fda27)
Location: include/linux/sched/signal.h:596
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
In kernel/sched/rt.c (ffffffff810cc056)
Location: include/linux/sched/signal.h:597
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811159d0)
Location: include/linux/sched/signal.h:597
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In mm/mmap.c (ffffffff81215fdb)
Location: include/linux/sched/signal.h:597
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
In kernel/sched/rt.c (ffffffff810d36e6)
Location: include/linux/sched/signal.h:625
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81122197)
Location: include/linux/sched/signal.h:625
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In mm/mmap.c (ffffffff81236deb)
Location: include/linux/sched/signal.h:625
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
In kernel/sched/rt.c (ffffffff810dca99)
Location: include/linux/sched/signal.h:667
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112d8b5)
Location: include/linux/sched/signal.h:667
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In mm/mmap.c (ffffffff8124a69b)
Location: include/linux/sched/signal.h:667
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
In kernel/sched/rt.c (ffffffff810e3a41)
Location: include/linux/sched/signal.h:698
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811382a4)
Location: include/linux/sched/signal.h:698
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In mm/mmap.c (ffffffff8125ca0b)
Location: include/linux/sched/signal.h:698
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
In kernel/sched/rt.c (ffffffff810ef581)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81144246)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In mm/mmap.c (ffffffff8126b16b)
Location: include/linux/sched/signal.h:690
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
In kernel/sched/rt.c (ffffffff810f8e80)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81153596)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
```
In mm/mmap.c (ffffffff81298b22)
Location: include/linux/sched/signal.h:702
Inline: True
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
In kernel/sched/rt.c (ffffffff810f7070)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114f856)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
```
In mm/mmap.c (ffffffff812a3ca2)
Location: include/linux/sched/signal.h:717
Inline: True
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
In kernel/sched/rt.c (ffffffff810f91c0)
Location: include/linux/sched/signal.h:723
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81150d36)
Location: include/linux/sched/signal.h:723
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
```
In mm/mmap.c (ffffffff812ac17b)
Location: include/linux/sched/signal.h:723
Inline: True
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
In kernel/sched/rt.c (ffffffff81114791)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81175106)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
```
In mm/mmap.c (ffffffff812ed8b7)
Location: include/linux/sched/signal.h:727
Inline: True
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
In kernel/sched/build_policy.c (ffffffff81137f73)
Location: include/linux/sched/signal.h:767
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811aa3dd)
Location: include/linux/sched/signal.h:767
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
```
In mm/mmap.c (ffffffff81350c59)
Location: include/linux/sched/signal.h:767
Inline: True
Inline callers:
  - mm/mmap.c:may_expand_vm
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
In kernel/sched/build_policy.c (ffffffff81162633)
Location: include/linux/sched/signal.h:768
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811ea3fd)
Location: include/linux/sched/signal.h:768
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
```
In mm/mmap.c (ffffffff813ca689)
Location: include/linux/sched/signal.h:768
Inline: True
Inline callers:
  - mm/mmap.c:may_expand_vm
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
In kernel/sched/build_policy.c (ffffffff81172db3)
Location: include/linux/sched/signal.h:768
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811feb1d)
Location: include/linux/sched/signal.h:768
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
```
In mm/mmap.c (ffffffff813fec59)
Location: include/linux/sched/signal.h:768
Inline: True
Inline callers:
  - mm/mmap.c:may_expand_vm
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
In kernel/sched/build_policy.c (ffffffff811806c3)
Location: include/linux/sched/signal.h:771
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81214d95)
Location: include/linux/sched/signal.h:771
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
```
In mm/mmap.c (ffffffff8142b0c9)
Location: include/linux/sched/signal.h:771
Inline: True
Inline callers:
  - mm/mmap.c:may_expand_vm
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
In kernel/sched/rt.c (ffff8000101507dc)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ae7c8)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In mm/mmap.c (ffff800010302858)
Location: include/linux/sched/signal.h:690
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
In kernel/sched/rt.c (c039e4a0)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (c03f98a0)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In mm/mmap.c (c0520f14)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - mm/mmap.c:may_expand_vm
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
In kernel/sched/rt.c (c0000000001a48a0)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (c000000000212d74)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In mm/mmap.c (c0000000003cee98)
Location: include/linux/sched/signal.h:690
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
In kernel/sched/rt.c (ffffffe0000f8eb4)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffe00013823a)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In mm/mmap.c (ffffffe00020f6b6)
Location: include/linux/sched/signal.h:690
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
In kernel/sched/rt.c (ffffffff810e8e01)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113c9f6)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In mm/mmap.c (ffffffff812637bb)
Location: include/linux/sched/signal.h:690
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
In kernel/sched/rt.c (ffffffff810d8941)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112f46f)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In mm/mmap.c (ffffffff81255bdb)
Location: include/linux/sched/signal.h:690
Inline: True
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
In kernel/sched/rt.c (ffffffff810e5ab1)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113a716)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In mm/mmap.c (ffffffff8126155b)
Location: include/linux/sched/signal.h:690
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
In kernel/sched/rt.c (ffffffff810f0991)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811471d6)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In mm/mmap.c (ffffffff81270f2b)
Location: include/linux/sched/signal.h:690
Inline: True
```
</details>
</li>
</ul>

## Differences
