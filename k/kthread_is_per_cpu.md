# Function: <code>kthread_is_per_cpu</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
bool kthread_is_per_cpu(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cc200)
Location: kernel/kthread.c:529
Inline: False
Direct callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
```
**Symbols:**

```
ffffffff810cc200-ffffffff810cc22b: kthread_is_per_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool kthread_is_per_cpu(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cdce0)
Location: kernel/kthread.c:556
Inline: False
Direct callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:is_cpu_allowed
```
**Symbols:**

```
ffffffff810cdce0-ffffffff810cdd05: kthread_is_per_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool kthread_is_per_cpu(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e0f30)
Location: kernel/kthread.c:556
Inline: False
Direct callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:select_fallback_rq
```
**Symbols:**

```
ffffffff810e0f30-ffffffff810e0f55: kthread_is_per_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool kthread_is_per_cpu(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fb300)
Location: kernel/kthread.c:616
Inline: False
Direct callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/fair.c:can_migrate_task
```
**Symbols:**

```
ffffffff810fb300-ffffffff810fb32d: kthread_is_per_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool kthread_is_per_cpu(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111e220)
Location: kernel/kthread.c:616
Inline: False
Direct callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/fair.c:can_migrate_task
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
```
**Symbols:**

```
ffffffff8111e220-ffffffff8111e24d: kthread_is_per_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool kthread_is_per_cpu(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112b480)
Location: kernel/kthread.c:617
Inline: False
Direct callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/fair.c:can_migrate_task
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
```
**Symbols:**

```
ffffffff8112b480-ffffffff8112b4ad: kthread_is_per_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool kthread_is_per_cpu(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81135bd0)
Location: kernel/kthread.c:616
Inline: False
Direct callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/fair.c:can_migrate_task
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
```
**Symbols:**

```
ffffffff81135bd0-ffffffff81135bfd: kthread_is_per_cpu (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *p</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *k</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
