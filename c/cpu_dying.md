# Function: <code>cpu_dying</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a7392)
Location: include/linux/cpumask.h:913
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
```
```
In kernel/sched/core.c (ffffffff810de3a8)
Location: include/linux/cpumask.h:913
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:is_cpu_allowed
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
In kernel/cpu.c (ffffffff810b8d8f)
Location: include/linux/cpumask.h:913
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/sched/core.c (ffffffff810f27cf)
Location: include/linux/cpumask.h:913
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:select_fallback_rq
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
In kernel/cpu.c (ffffffff810cf6d5)
Location: include/linux/cpumask.h:939
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/sched/core.c (ffffffff8110e6ee)
Location: include/linux/cpumask.h:939
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:migration_cpu_stop
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
In kernel/cpu.c (ffffffff810edabc)
Location: include/linux/cpumask.h:1048
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/sched/core.c (ffffffff8113548e)
Location: include/linux/cpumask.h:1048
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:migration_cpu_stop
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
In kernel/cpu.c (ffffffff810f9ba7)
Location: include/linux/cpumask.h:1100
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/sched/core.c (ffffffff8114460e)
Location: include/linux/cpumask.h:1100
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:migration_cpu_stop
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
In kernel/cpu.c (ffffffff81102fb7)
Location: include/linux/cpumask.h:1122
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/sched/core.c (ffffffff8114fb2e)
Location: include/linux/cpumask.h:1122
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:migration_cpu_stop
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
