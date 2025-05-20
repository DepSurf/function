# Function: <code>wake_up_q</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810abd70)
Location: kernel/sched/core.c:545
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/futex.c:futex_wake
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:do_futex
  - ipc/mqueue.c:SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_timedreceive
```
**Symbols:**

```
ffffffff810abd70-ffffffff810abdd7: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aea00)
Location: kernel/sched/core.c:452
Inline: False
Direct callers:
  - kernel/locking/mutex.c:__mutex_unlock_slowpath
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake
  - kernel/locking/rwsem-xadd.c:rwsem_wake
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
```
**Symbols:**

```
ffffffff810aea00-ffffffff810aea71: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b4b40)
Location: kernel/sched/core.c:452
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake
  - kernel/locking/rwsem-xadd.c:rwsem_wake
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
```
**Symbols:**

```
ffffffff810b4b40-ffffffff810b4bb1: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0c30)
Location: kernel/sched/core.c:450
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake
  - kernel/locking/rwsem-xadd.c:rwsem_wake
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810b0c30-ffffffff810b0ca2: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b8080)
Location: kernel/sched/core.c:452
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake
  - kernel/locking/rwsem-xadd.c:rwsem_wake
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810b8080-ffffffff810b80f2: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bfb80)
Location: kernel/sched/core.c:430
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake
  - kernel/locking/rwsem-xadd.c:rwsem_wake
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810bfb80-ffffffff810bfbf7: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c8f00)
Location: kernel/sched/core.c:436
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake
  - kernel/locking/rwsem-xadd.c:rwsem_wake
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810c8f00-ffffffff810c8f77: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d0ab0)
Location: kernel/sched/core.c:478
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810d0ab0-ffffffff810d0b18: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810daa60)
Location: kernel/sched/core.c:478
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810daa60-ffffffff810daac8: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e38c0)
Location: kernel/sched/core.c:481
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810e38c0-ffffffff810e395f: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1330)
Location: kernel/sched/core.c:570
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810e1330-ffffffff810e13cf: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3150)
Location: kernel/sched/core.c:580
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810e3150-ffffffff810e31ef: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f9c00)
Location: kernel/sched/core.c:933
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810f9c00-ffffffff810f9c8a: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81116180)
Location: kernel/sched/core.c:1003
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff81116180-ffffffff81116216: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113d630)
Location: kernel/sched/core.c:991
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff8113d630-ffffffff8113d6c6: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811511b0)
Location: kernel/sched/core.c:1013
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff811511b0-ffffffff81151246: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8115d040)
Location: kernel/sched/core.c:1013
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff8115d040-ffffffff8115d0d6: wake_up_q (STB_GLOBAL)
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
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013a588)
Location: kernel/sched/core.c:478
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffff80001013a588-ffff80001013a61c: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038a118)
Location: kernel/sched/core.c:478
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
c038a118-c038a1ac: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000187e60)
Location: kernel/sched/core.c:478
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
c000000000187e60-c000000000187f30: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e9f54)
Location: kernel/sched/core.c:478
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
```
**Symbols:**

```
ffffffe0000e9f54-ffffffe0000e9fd8: wake_up_q (STB_GLOBAL)
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
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4f10)
Location: kernel/sched/core.c:478
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810d4f10-ffffffff810d4f78: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c3560)
Location: kernel/sched/core.c:478
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810c3560-ffffffff810c35c8: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d1d50)
Location: kernel/sched/core.c:478
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810d1d50-ffffffff810d1db8: wake_up_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wake_up_q(struct wake_q_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc770)
Location: kernel/sched/core.c:478
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff810dc770-ffffffff810dc7d8: wake_up_q (STB_GLOBAL)
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
