# Function: <code>wake_q_add_safe</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cd750)
Location: kernel/sched/core.c:472
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff810cd750-ffffffff810cd798: wake_q_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d7280)
Location: kernel/sched/core.c:472
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff810d7280-ffffffff810d72c8: wake_q_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1cd0)
Location: kernel/sched/core.c:475
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/futex.c:mark_wake_futex
  - ipc/msg.c:expunge_all
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810e1cd0-ffffffff810e1d36: wake_q_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df0b0)
Location: kernel/sched/core.c:564
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/futex.c:mark_wake_futex
  - ipc/msg.c:expunge_all
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810df0b0-ffffffff810df116: wake_q_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0d50)
Location: kernel/sched/core.c:574
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/futex.c:mark_wake_futex
  - ipc/msg.c:expunge_all
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810e0d50-ffffffff810e0db0: wake_q_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f5c90)
Location: kernel/sched/core.c:927
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/futex.c:mark_wake_futex
  - ipc/msg.c:expunge_all
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810f5c90-ffffffff810f5cf0: wake_q_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81110db0)
Location: kernel/sched/core.c:997
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/futex/waitwake.c:futex_wake_mark
  - ipc/msg.c:expunge_all
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff81110db0-ffffffff81110e48: wake_q_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81137d50)
Location: kernel/sched/core.c:985
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/futex/waitwake.c:futex_wake_mark
  - ipc/msg.c:expunge_all
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff81137d50-ffffffff81137de8: wake_q_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81146e70)
Location: kernel/sched/core.c:1007
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - ipc/msg.c:expunge_all
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff81146e70-ffffffff81146f08: wake_q_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811526a0)
Location: kernel/sched/core.c:1007
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/futex/waitwake.c:futex_wake_mark
  - ipc/msg.c:expunge_all
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff811526a0-ffffffff81152738: wake_q_add_safe (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010137db0)
Location: kernel/sched/core.c:472
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffff800010137db0-ffff800010137e40: wake_q_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0386800)
Location: kernel/sched/core.c:472
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
c0386800-c0386878: wake_q_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000183290)
Location: kernel/sched/core.c:472
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
c000000000183290-c000000000183330: wake_q_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e7fbc)
Location: kernel/sched/core.c:472
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffe0000e7fbc-ffffffe0000e8020: wake_q_add_safe (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d1750)
Location: kernel/sched/core.c:472
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff810d1750-ffffffff810d1798: wake_q_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bfd10)
Location: kernel/sched/core.c:472
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff810bfd10-ffffffff810bfd58: wake_q_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf910)
Location: kernel/sched/core.c:472
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff810cf910-ffffffff810cf958: wake_q_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8e30)
Location: kernel/sched/core.c:472
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff810d8e30-ffffffff810d8e78: wake_q_add_safe (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
