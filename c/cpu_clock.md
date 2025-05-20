# Function: <code>cpu_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 cpu_clock(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b1450)
Location: kernel/sched/clock.c:371
Inline: False
Direct callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
**Symbols:**

```
ffffffff810b1450-ffffffff810b1467: cpu_clock (STB_GLOBAL)
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
In kernel/sched/debug.c (ffffffff810cc8f3)
Location: include/linux/sched.h:2468
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/debug.c (ffffffff810d2913)
Location: include/linux/sched.h:2564
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/debug.c (ffffffff810d1a66)
Location: include/linux/sched/clock.h:76
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/debug.c (ffffffff810d9607)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/debug.c (ffffffff810e061c)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/debug.c (ffffffff810eadd2)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/sched/psi.c (ffffffff810ef415)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:update_stats
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
In kernel/sched/fair.c (ffffffff810d7a6c)
Location: include/linux/sched/clock.h:77
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810f1bef)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/sched/psi.c (ffffffff810f5c95)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/fair.c (ffffffff810e2083)
Location: include/linux/sched/clock.h:77
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810fd8af)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/sched/psi.c (ffffffff81101a25)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/fair.c (ffffffff810e9f61)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
```
```
In kernel/sched/debug.c (ffffffff811080ab)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/sched/psi.c (ffffffff8110c2b5)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/psi.c:record_times
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
In kernel/sched/fair.c (ffffffff810e7cc1)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
```
```
In kernel/sched/debug.c (ffffffff811068bb)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/sched/psi.c (ffffffff811094c6)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/psi.c:record_times
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
In kernel/sched/fair.c (ffffffff810ebdfc)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
```
```
In kernel/sched/debug.c (ffffffff81108901)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/sched/psi.c (ffffffff8110c6bc)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/fair.c (ffffffff81103a92)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
```
```
In kernel/sched/debug.c (ffffffff81126a71)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/sched/psi.c (ffffffff8112b733)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/fair.c (ffffffff8111fa7d)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
```
```
In kernel/sched/build_utility.c (ffffffff8114be7a)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
  - kernel/sched/build_utility.c:collect_percpu_times
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
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
In kernel/sched/fair.c (ffffffff81145c45)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
```
```
In kernel/sched/build_utility.c (ffffffff8117b05f)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
  - kernel/sched/build_utility.c:get_recent_times
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
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
In kernel/sched/fair.c (ffffffff81156a0e)
Location: include/linux/sched/clock.h:91
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
```
```
In kernel/sched/build_utility.c (ffffffff8118bb9d)
Location: include/linux/sched/clock.h:91
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
  - kernel/sched/build_utility.c:get_recent_times
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
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
In kernel/sched/build_utility.c (ffffffff8119a4fd)
Location: include/linux/sched/clock.h:91
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
  - kernel/sched/build_utility.c:get_recent_times
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
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
In kernel/sched/fair.c (ffff800010142f80)
Location: include/linux/sched/clock.h:43
Inline: True
```
```
In kernel/sched/debug.c (ffff8000101630bc)
Location: include/linux/sched/clock.h:43
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/sched/psi.c (ffff800010166d54)
Location: include/linux/sched/clock.h:43
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/fair.c (c0396318)
Location: include/linux/sched/clock.h:43
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/debug.c (c03af76c)
Location: include/linux/sched/clock.h:43
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/sched/psi.c (c03b2bb4)
Location: include/linux/sched/clock.h:43
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/fair.c (c0000000001911a8)
Location: include/linux/sched/clock.h:43
Inline: True
```
```
In kernel/sched/debug.c (c0000000001b98b0)
Location: include/linux/sched/clock.h:43
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/sched/psi.c (c0000000001bdefc)
Location: include/linux/sched/clock.h:43
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/fair.c (ffffffe0000ef34a)
Location: include/linux/sched/clock.h:43
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/debug.c (ffffffe000106c8a)
Location: include/linux/sched/clock.h:43
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/sched/psi.c (ffffffe000108b12)
Location: include/linux/sched/clock.h:43
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/fair.c (ffffffff810dc233)
Location: include/linux/sched/clock.h:77
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810f6bcf)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/sched/psi.c (ffffffff810fad35)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/fair.c (ffffffff810cb243)
Location: include/linux/sched/clock.h:77
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810e6d9f)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/sched/psi.c (ffffffff810eaf55)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/fair.c (ffffffff810d85b3)
Location: include/linux/sched/clock.h:77
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810f3ddf)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/sched/psi.c (ffffffff810f7ef5)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:collect_percpu_times
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
In kernel/sched/fair.c (ffffffff810e4053)
Location: include/linux/sched/clock.h:77
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810fedcf)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/sched/psi.c (ffffffff81103035)
Location: include/linux/sched/clock.h:77
Inline: True
Inline callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:collect_percpu_times
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
