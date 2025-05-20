# Function: <code>task_tgid</code>

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
In kernel/signal.c (ffffffff8108f36d)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:do_tkill
  - kernel/signal.c:SYSC_kill
```
```
In kernel/sys.c (ffffffff8109493f)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - kernel/sys.c:sys_getpid
  - kernel/sys.c:sys_getppid
```
```
In kernel/pid.c (ffffffff8109dcf5)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - kernel/pid.c:task_tgid_nr_ns
```
```
In kernel/time/posix-timers.c (ffffffff810f1729)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In kernel/cgroup.c (ffffffff81118bd9)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - kernel/cgroup.c:pidlist_array_load
```
```
In kernel/audit.c (ffffffff81123771)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812529d5)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff8125f973)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_lock_ctx
```
```
In fs/coredump.c (ffffffff8126f68e)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8127e766)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - fs/proc/base.c:proc_flush_task
```
```
In fs/fuse/file.c (ffffffff81317808)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff813263e1)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgrcv
```
```
In ipc/sem.c (ffffffff81328550)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:exit_sem
```
```
In ipc/shm.c (ffffffff8132a0a3)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - ipc/shm.c:shm_close
  - ipc/shm.c:newseg
```
```
In ipc/mqueue.c (ffffffff8132ceb6)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_notify
```
```
In security/tomoyo/audit.c (ffffffff81366cb1)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff8136ccc9)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In net/core/scm.c (ffffffff8170e800)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff8174cf02)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff817be333)
Location: include/linux/sched.h:1877
Inline: True
Inline callers:
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:maybe_init_creds
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
In kernel/signal.c (ffffffff81092486)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:SYSC_kill
```
```
In kernel/sys.c (ffffffff81097ba9)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - kernel/sys.c:sys_getppid
  - kernel/sys.c:sys_getpid
```
```
In kernel/pid.c (ffffffff810a1355)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - kernel/pid.c:task_tgid_nr_ns
```
```
In kernel/time/posix-timers.c (ffffffff810f87ba)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In kernel/cgroup.c (ffffffff81120876)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_start
```
```
In kernel/audit.c (ffffffff8112b5cd)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8127b195)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff8128bb13)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_lock_ctx
```
```
In fs/coredump.c (ffffffff8129b5d9)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff812ab766)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - fs/proc/base.c:proc_flush_task
```
```
In fs/fuse/file.c (ffffffff8134c125)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff8135b521)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8135e84d)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
```
```
In ipc/shm.c (ffffffff8135ef7c)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff81362e75)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In security/tomoyo/audit.c (ffffffff8139cd51)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff813a2ee4)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In net/core/scm.c (ffffffff81775f7e)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff817ba8bd)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8182c18e)
Location: include/linux/sched.h:2016
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
In kernel/signal.c (ffffffff81097416)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:SYSC_kill
```
```
In kernel/sys.c (ffffffff8109cb59)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - kernel/sys.c:sys_getppid
  - kernel/sys.c:sys_getpid
```
```
In kernel/pid.c (ffffffff810a6415)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - kernel/pid.c:task_tgid_nr_ns
```
```
In kernel/time/posix-timers.c (ffffffff8110614a)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In kernel/cgroup.c (ffffffff81128d63)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_start
```
```
In kernel/audit.c (ffffffff8113529a)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8128ed45)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff8129f875)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_lock_ctx
```
```
In fs/coredump.c (ffffffff812b019d)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff812c1026)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - fs/proc/base.c:proc_flush_task
```
```
In fs/fuse/file.c (ffffffff81361a35)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff81371b58)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff81375024)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
```
```
In ipc/shm.c (ffffffff8137577c)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff81379655)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In security/tomoyo/audit.c (ffffffff813b3931)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff813b9a64)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In net/core/scm.c (ffffffff817a31fe)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff817ea25d)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8185dc3e)
Location: include/linux/sched.h:2103
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
In kernel/time/posix-timers.c (ffffffff811080c0)
Location: include/linux/sched.h:1113
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/audit.c (ffffffff81136747)
Location: include/linux/sched.h:1113
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8129bbb7)
Location: include/linux/sched.h:1113
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff812ae6e5)
Location: include/linux/sched.h:1113
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_lock_ctx
```
```
In fs/proc/base.c (ffffffff812ce3d6)
Location: include/linux/sched.h:1113
Inline: True
Inline callers:
  - fs/proc/base.c:proc_flush_task
```
```
In fs/fuse/file.c (ffffffff81376417)
Location: include/linux/sched.h:1113
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/mqueue.c (ffffffff8138c296)
Location: include/linux/sched.h:1113
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffffffff81809f27)
Location: include/linux/sched.h:1113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff818823e8)
Location: include/linux/sched.h:1113
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
In kernel/time/posix-timers.c (ffffffff8111326e)
Location: include/linux/sched.h:1113
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/audit.c (ffffffff811430d6)
Location: include/linux/sched.h:1113
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812befc7)
Location: include/linux/sched.h:1113
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/base.c (ffffffff812f2c36)
Location: include/linux/sched.h:1113
Inline: True
Inline callers:
  - fs/proc/base.c:proc_flush_task
```
```
In fs/fuse/file.c (ffffffff8139b1b7)
Location: include/linux/sched.h:1113
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/mqueue.c (ffffffff813b1646)
Location: include/linux/sched.h:1113
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffffffff81888ea7)
Location: include/linux/sched.h:1113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81903558)
Location: include/linux/sched.h:1113
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
In kernel/time/posix-timers.c (ffffffff8111fa8d)
Location: include/linux/sched.h:1205
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/audit.c (ffffffff81151a3e)
Location: include/linux/sched.h:1205
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812e7f18)
Location: include/linux/sched.h:1205
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/base.c (ffffffff8131fa56)
Location: include/linux/sched.h:1205
Inline: True
Inline callers:
  - fs/proc/base.c:proc_flush_task
```
```
In fs/fuse/file.c (ffffffff813ca0f7)
Location: include/linux/sched.h:1205
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff813d8b4c)
Location: include/linux/sched.h:1205
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff813dd277)
Location: include/linux/sched.h:1205
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffffffff813de558)
Location: include/linux/sched.h:1205
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff813e1866)
Location: include/linux/sched.h:1205
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffffffff818dc95a)
Location: include/linux/sched.h:1205
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81959298)
Location: include/linux/sched.h:1205
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
Location: include/linux/sched/signal.h:581
Inline: True
```
```
In kernel/time/posix-timers.c (ffffffff8112b11a)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112c712)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:check_clock
```
```
In kernel/audit.c (ffffffff8115e6fc)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/exec.c (ffffffff812b71b9)
Location: include/linux/sched/signal.h:581
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812fcc03)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/base.c (ffffffff8133465e)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/fuse/file.c (ffffffff813e3747)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff813f29cc)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff813f78d7)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffffffff813f8c16)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff813fc436)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffffffff8190933f)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8198de48)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
Location: include/linux/sched/signal.h:612
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-timers.c (ffffffff8113619c)
Location: include/linux/sched/signal.h:612
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811370b2)
Location: include/linux/sched/signal.h:612
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:check_clock
```
```
In kernel/audit.c (ffffffff8116b67d)
Location: include/linux/sched/signal.h:612
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_receive_msg
```
```
In fs/exec.c (ffffffff812d4bb2)
Location: include/linux/sched/signal.h:612
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8131d71d)
Location: include/linux/sched/signal.h:612
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/base.c (ffffffff8135cc2c)
Location: include/linux/sched/signal.h:612
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/fuse/file.c (ffffffff8140f727)
Location: include/linux/sched/signal.h:612
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff8141f805)
Location: include/linux/sched/signal.h:612
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff81423e05)
Location: include/linux/sched/signal.h:612
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffffffff81425130)
Location: include/linux/sched/signal.h:612
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff81429094)
Location: include/linux/sched/signal.h:612
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffffffff8196a64f)
Location: include/linux/sched/signal.h:612
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff819f9cdf)
Location: include/linux/sched/signal.h:612
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-timers.c (ffffffff8114223c)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811431ab)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/audit.c (ffffffff8117755d)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_receive_msg
```
```
In fs/exec.c (ffffffff812e6732)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8133055d)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/base.c (ffffffff8137505c)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/fuse/file.c (ffffffff814291e7)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff81439625)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8143db5b)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffffffff8143ee80)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff81442ddd)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffffffff819a10bf)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81a3095f)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
In kernel/time/posix-timers.c (ffffffff81150ad6)
Location: include/linux/sched/signal.h:627
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81152b92)
Location: include/linux/sched/signal.h:627
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/audit.c (ffffffff8118a1cd)
Location: include/linux/sched/signal.h:627
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_receive_msg
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8136ab77)
Location: include/linux/sched/signal.h:627
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/fuse/file.c (ffffffff81479bb5)
Location: include/linux/sched/signal.h:627
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff8148981c)
Location: include/linux/sched/signal.h:627
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8148e6db)
Location: include/linux/sched/signal.h:627
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffffffff8148f9d5)
Location: include/linux/sched/signal.h:627
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff814936bd)
Location: include/linux/sched/signal.h:627
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffffffff81a7a9e7)
Location: include/linux/sched/signal.h:627
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81b2551e)
Location: include/linux/sched/signal.h:627
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
In kernel/usermode_driver.c (ffffffff810d555a)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_setup
```
```
In kernel/time/posix-timers.c (ffffffff8114cd56)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114ee13)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/audit.c (ffffffff811874e3)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_receive_msg
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81377e44)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/fuse/file.c (ffffffff81494af2)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff814a6e55)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff814abe17)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffffffff814ad0d5)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff814b0fbd)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffffffff81a83828)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81b337b3)
Location: include/linux/sched/signal.h:640
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
In kernel/usermode_driver.c (ffffffff810d721a)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_setup
```
```
In kernel/time/posix-timers.c (ffffffff8114f22c)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811502a3)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/audit.c (ffffffff81188553)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_receive_msg
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137e956)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137fd3d)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
```
In fs/fuse/file.c (ffffffff81499b52)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff814acdad)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff814b1cd6)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffffffff814b2f5d)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff814b6e2d)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffffffff81a6c8fb)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81b20cc3)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
In kernel/usermode_driver.c (ffffffff810eaaca)
Location: include/linux/sched/signal.h:644
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_setup
```
```
In kernel/time/posix-timers.c (ffffffff811733e0)
Location: include/linux/sched/signal.h:644
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811744f3)
Location: include/linux/sched/signal.h:644
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/audit.c (ffffffff811b0a73)
Location: include/linux/sched/signal.h:644
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_receive_msg
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cba36)
Location: include/linux/sched/signal.h:644
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cce7f)
Location: include/linux/sched/signal.h:644
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
```
In fs/fuse/file.c (ffffffff814f1572)
Location: include/linux/sched/signal.h:644
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff81505298)
Location: include/linux/sched/signal.h:644
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8150a294)
Location: include/linux/sched/signal.h:644
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffffffff8150b68f)
Location: include/linux/sched/signal.h:644
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff8150f76d)
Location: include/linux/sched/signal.h:644
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffffffff81b25f50)
Location: include/linux/sched/signal.h:644
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81be5d83)
Location: include/linux/sched/signal.h:644
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
In kernel/usermode_driver.c (ffffffff811058b2)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_setup
```
```
In kernel/time/posix-timers.c (ffffffff811a6749)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a924b)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/audit.c (ffffffff811e2c7b)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive_msg
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814540c0)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81455979)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
```
In fs/fuse/file.c (ffffffff81580c74)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff81596c5c)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8159c001)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffffffff8159d8ef)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff815a2a62)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffffffff81caeb82)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81d7f39f)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
In kernel/usermode_driver.c (ffffffff8112b3a2)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_setup
```
```
In kernel/time/posix-timers.c (ffffffff811e62e9)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e918b)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/audit.c (ffffffff81228b6b)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive_msg
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e2f70)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e48f9)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
```
In fs/fuse/file.c (ffffffff81626a54)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff8163fb61)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff81645401)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffffffff81646ebf)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_open
```
```
In ipc/mqueue.c (ffffffff8164c582)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffffffff81e6c1d2)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81f4de70)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
In kernel/usermode_driver.c (ffffffff81138692)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_setup
```
```
In kernel/time/posix-timers.c (ffffffff811fa8db)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fd77b)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/audit.c (ffffffff8123f16b)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive_msg
```
```
In fs/notify/fanotify/fanotify.c (ffffffff815197a1)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151b727)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
```
In fs/fuse/file.c (ffffffff8165f0ca)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff8167808a)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8167d8e7)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffffffff8167f3ff)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_open
```
```
In ipc/mqueue.c (ffffffff81684cc8)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffffffff81ec8232)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81fab1ab)
Location: include/linux/sched/signal.h:685
Inline: True
Inline callers:
  - net/unix/af_unix.c:init_peercred
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
In kernel/time/posix-timers.c (ffffffff81210acb)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8121397b)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/audit.c (ffffffff81258fdb)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive_msg
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154db81)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154fd27)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
```
In fs/fuse/file.c (ffffffff81698f0a)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff816b444a)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff816b9cbd)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffffffff816bb7ef)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_open
```
```
In ipc/mqueue.c (ffffffff816c1108)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In drivers/gpu/drm/drm_auth.c (ffffffff81c7ec8e)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_auth.c:drm_dropmaster_ioctl
  - drivers/gpu/drm/drm_auth.c:drm_setmaster_ioctl
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c97fb1)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_file_update_pid
  - drivers/gpu/drm/drm_file.c:drm_file_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81f8b641)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8207859b)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - net/unix/af_unix.c:init_peercred
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
In kernel/exit.c (ffff8000100faa4c)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-timers.c (ffff8000101ac334)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ad278)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/audit.c (ffff8000101ec568)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_receive_msg
```
```
In fs/exec.c (ffff80001038ea34)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/fanotify/fanotify.c (ffff8000103ed6cc)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/base.c (ffff80001043e974)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/fuse/file.c (ffff80001050d258)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffff80001051fb40)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffff8000105259c4)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffff800010526620)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffff80001052c1cc)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffff800010c4f794)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffff800010cef564)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-timers.c (c03f66fc)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (c03f8218)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/audit.c (c042c1bc)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_receive_msg
```
```
In fs/exec.c (c0574f9c)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/fanotify/fanotify.c (c05c3ec0)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/base.c (c0605b84)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/fuse/file.c (c06c8938)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (c06db904)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (c06dfea4)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:semctl_main
```
```
In ipc/shm.c (c06e0758)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:__shm_open
```
```
In ipc/mqueue.c (c06e4304)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (c0d5f918)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (c0df8e10)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:init_peercred
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
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-timers.c (c00000000020ffb8)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (c0000000002114f0)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/audit.c (c00000000025dfd0)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_receive_msg
```
```
In fs/exec.c (c000000000485964)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/fanotify/fanotify.c (c0000000004f4dac)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/base.c (c0000000005544c0)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/fuse/file.c (c000000000653dbc)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (c00000000066a130)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (c00000000066ff18)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (c000000000671a84)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (c000000000677c64)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (c000000000d4e0c0)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (c000000000e153e4)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-timers.c (ffffffe000136298)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffe0001372de)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/audit.c (ffffffe000160bf4)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_receive_msg
```
```
In fs/exec.c (ffffffe00025e506)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/fanotify/fanotify.c (ffffffe0002a1102)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/base.c (ffffffe0002d6476)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/fuse/file.c (ffffffe0003780fc)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffe000386176)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffe00038a2f4)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:semctl_main
```
```
In ipc/shm.c (ffffffe00038aed0)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffe00038e5f2)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffffffe0007bb392)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffe00083c538)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-timers.c (ffffffff8113a9ec)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113b95b)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/audit.c (ffffffff8116fb7d)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_receive_msg
```
```
In fs/exec.c (ffffffff812ded12)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81328b3d)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/base.c (ffffffff8136d63c)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/fuse/file.c (ffffffff814217c7)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff81431c05)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8143613b)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffffffff81437460)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff8143b3bd)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffffffff81940f2f)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff819cffef)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-timers.c (ffffffff8112d43c)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112e31b)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/audit.c (ffffffff81162d1d)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_receive_msg
```
```
In fs/exec.c (ffffffff812cee37)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813196dd)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/base.c (ffffffff8135e0cc)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/fuse/file.c (ffffffff81412247)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff81422685)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff81426bbb)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffffffff81427ed0)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff8142be2d)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffffffff818faa1f)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8198cdaf)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-timers.c (ffffffff8113870c)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113967b)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/audit.c (ffffffff8116d94d)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_receive_msg
```
```
In fs/exec.c (ffffffff812dcb22)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8132660d)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/base.c (ffffffff8136b10c)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/fuse/file.c (ffffffff8141d967)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff8142dda5)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff814322db)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffffffff81433600)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff8143755d)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffffffff819920bf)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81a3aa6f)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
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
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/time/posix-timers.c (ffffffff8114530f)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81146129)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/audit.c (ffffffff8117a77d)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:auditd_test_task
```
```
In fs/exec.c (ffffffff812ed8cb)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8133842d)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/base.c (ffffffff8137e953)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/fuse/file.c (ffffffff814346c7)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
```
```
In ipc/msg.c (ffffffff81444802)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff814493a4)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffffffff8144a9d0)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff8144ec5f)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_flush_file
```
```
In net/netlink/af_netlink.c (ffffffff819b4baf)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81a46fbf)
Location: include/linux/sched/signal.h:604
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:init_peercred
```
</details>
</li>
</ul>

## Differences
