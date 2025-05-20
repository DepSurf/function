# Function: <code>rt_mutex_get_top_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct task_struct *rt_mutex_get_top_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810cb730)
Location: kernel/locking/rtmutex.c:272
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810cb730-ffffffff810cb754: rt_mutex_get_top_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct task_struct *rt_mutex_get_top_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d0190)
Location: kernel/locking/rtmutex.c:274
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810d0190-ffffffff810d01b6: rt_mutex_get_top_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_struct *rt_mutex_get_top_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d6b80)
Location: kernel/locking/rtmutex.c:338
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810d6b80-ffffffff810d6ba6: rt_mutex_get_top_task (STB_GLOBAL)
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
In kernel/sched/core.c (ffffffff810ae501)
Location: include/linux/sched/rt.h:24
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810c761d)
Location: include/linux/sched/rt.h:24
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/core.c (ffffffff810b57c9)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810cebdd)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/core.c (ffffffff810bd492)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810d6515)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/core.c (ffffffff810c6652)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810e0a55)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/core.c (ffffffff810cc7ed)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810e7a95)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/core.c (ffffffff810d62e8)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810f30d5)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/core.c (ffffffff810e096b)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810fc785)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dde13)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df834)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f4944)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8111153c)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811384fc)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81147608)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
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
In kernel/sched/core.c (ffffffff81152e38)
Location: include/linux/sched/rt.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
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
In kernel/sched/core.c (ffff800010136c8c)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffff800010155370)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/core.c (c038567c)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (c03a2b1c)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/core.c (c000000000181b5c)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (c0000000001a93d8)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/core.c (ffffffe0000e7582)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffe0000fcdce)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/core.c (ffffffff810d06e2)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810ec4d5)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/core.c (ffffffff810be81c)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810dc575)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/core.c (ffffffff810ceaa6)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810e9605)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/core.c (ffffffff810d7bc2)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810f45b5)
Location: include/linux/sched/rt.h:36
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
