# Function: <code>wake_q_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa290)
Location: kernel/sched/core.c:521
Inline: False
Direct callers:
  - kernel/futex.c:mark_wake_futex
  - ipc/mqueue.c:SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_timedreceive
```
**Symbols:**

```
ffffffff810aa290-ffffffff810aa2c8: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810acef0)
Location: kernel/sched/core.c:428
Inline: False
Direct callers:
  - kernel/locking/mutex.c:__mutex_unlock_slowpath
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rwsem-xadd.c:__rwsem_mark_wake
  - kernel/locking/rwsem-xadd.c:__rwsem_mark_wake
  - kernel/futex.c:mark_wake_futex
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
```
**Symbols:**

```
ffffffff810acef0-ffffffff810acf28: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2f80)
Location: kernel/sched/core.c:428
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/futex.c:mark_wake_futex
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:ss_wakeup
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
```
**Symbols:**

```
ffffffff810b2f80-ffffffff810b2fb8: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aeea0)
Location: kernel/sched/core.c:426
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/futex.c:mark_wake_futex
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:ss_wakeup
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810aeea0-ffffffff810aeed8: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b60f0)
Location: kernel/sched/core.c:428
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/futex.c:mark_wake_futex
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:ss_wakeup
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810b60f0-ffffffff810b6128: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bdf50)
Location: kernel/sched/core.c:406
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/futex.c:mark_wake_futex
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:ss_wakeup
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810bdf50-ffffffff810bdf86: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c7200)
Location: kernel/sched/core.c:411
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rwsem-xadd.c:__rwsem_mark_wake
  - kernel/locking/rwsem-xadd.c:__rwsem_mark_wake
  - kernel/futex.c:mark_wake_futex
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:ss_wakeup
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810c7200-ffffffff810c7238: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cd710)
Location: kernel/sched/core.c:449
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:ss_wakeup
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810cd710-ffffffff810cd74c: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d7240)
Location: kernel/sched/core.c:449
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:ss_wakeup
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810d7240-ffffffff810d727c: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1c60)
Location: kernel/sched/core.c:452
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:ss_wakeup
```
**Symbols:**

```
ffffffff810e1c60-ffffffff810e1cc4: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df040)
Location: kernel/sched/core.c:541
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:ss_wakeup
```
**Symbols:**

```
ffffffff810df040-ffffffff810df0a4: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0ce0)
Location: kernel/sched/core.c:551
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:ss_wakeup
```
**Symbols:**

```
ffffffff810e0ce0-ffffffff810e0d44: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f5c20)
Location: kernel/sched/core.c:904
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:ss_wakeup
```
**Symbols:**

```
ffffffff810f5c20-ffffffff810f5c84: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81110d10)
Location: kernel/sched/core.c:974
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:ss_wakeup
```
**Symbols:**

```
ffffffff81110d10-ffffffff81110dac: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81137ca0)
Location: kernel/sched/core.c:962
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:ss_wakeup
```
**Symbols:**

```
ffffffff81137ca0-ffffffff81137d3c: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81146dc0)
Location: kernel/sched/core.c:984
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:ss_wakeup
```
**Symbols:**

```
ffffffff81146dc0-ffffffff81146e5c: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811525f0)
Location: kernel/sched/core.c:984
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:ss_wakeup
```
**Symbols:**

```
ffffffff811525f0-ffffffff8115268c: wake_q_add (STB_GLOBAL)
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
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010137d30)
Location: kernel/sched/core.c:449
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffff800010137d30-ffff800010137dac: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038679c)
Location: kernel/sched/core.c:449
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
c038679c-c0386800: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000183230)
Location: kernel/sched/core.c:449
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
c000000000183230-c000000000183288: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e7f6a)
Location: kernel/sched/core.c:449
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
```
**Symbols:**

```
ffffffe0000e7f6a-ffffffe0000e7fbc: wake_q_add (STB_GLOBAL)
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
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d1710)
Location: kernel/sched/core.c:449
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:ss_wakeup
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810d1710-ffffffff810d174c: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bfcd0)
Location: kernel/sched/core.c:449
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:ss_wakeup
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810bfcd0-ffffffff810bfd0c: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf8d0)
Location: kernel/sched/core.c:449
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:ss_wakeup
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810cf8d0-ffffffff810cf90c: wake_q_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head *head, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8df0)
Location: kernel/sched/core.c:449
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:ss_wakeup
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810d8df0-ffffffff810d8e2c: wake_q_add (STB_GLOBAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
