# Function: <code>task_tgid_vnr</code>

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
Location: include/linux/sched.h:1939
Inline: True
Inline callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:do_tkill
  - kernel/signal.c:SYSC_kill
```
```
In kernel/sys.c (ffffffff8109493f)
Location: include/linux/sched.h:1939
Inline: True
Inline callers:
  - kernel/sys.c:sys_getpid
  - kernel/sys.c:sys_getppid
```
```
In kernel/cgroup.c (ffffffff81118bd9)
Location: include/linux/sched.h:1939
Inline: True
Inline callers:
  - kernel/cgroup.c:pidlist_array_load
```
```
In kernel/audit.c (ffffffff81123771)
Location: include/linux/sched.h:1939
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/coredump.c (ffffffff8126f68e)
Location: include/linux/sched.h:1939
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In ipc/msg.c (ffffffff813263e1)
Location: include/linux/sched.h:1939
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgrcv
```
```
In ipc/sem.c (ffffffff81328550)
Location: include/linux/sched.h:1939
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:exit_sem
```
```
In ipc/shm.c (ffffffff8132a0a3)
Location: include/linux/sched.h:1939
Inline: True
Inline callers:
  - ipc/shm.c:shm_close
  - ipc/shm.c:newseg
```
```
In security/tomoyo/audit.c (ffffffff81366cb1)
Location: include/linux/sched.h:1939
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff8136ccc9)
Location: include/linux/sched.h:1939
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In net/core/scm.c (ffffffff8170e800)
Location: include/linux/sched.h:1939
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff8174cf02)
Location: include/linux/sched.h:1939
Inline: True
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
Location: include/linux/sched.h:2078
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:SYSC_kill
```
```
In kernel/sys.c (ffffffff81097ba9)
Location: include/linux/sched.h:2078
Inline: True
Inline callers:
  - kernel/sys.c:sys_getppid
  - kernel/sys.c:sys_getpid
```
```
In kernel/cgroup.c (ffffffff81120876)
Location: include/linux/sched.h:2078
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_start
```
```
In kernel/audit.c (ffffffff8112b5cd)
Location: include/linux/sched.h:2078
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/coredump.c (ffffffff8129b5d9)
Location: include/linux/sched.h:2078
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In ipc/msg.c (ffffffff8135b521)
Location: include/linux/sched.h:2078
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8135e84d)
Location: include/linux/sched.h:2078
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
```
```
In ipc/shm.c (ffffffff8135ef7c)
Location: include/linux/sched.h:2078
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In security/tomoyo/audit.c (ffffffff8139cd51)
Location: include/linux/sched.h:2078
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff813a2ee4)
Location: include/linux/sched.h:2078
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In net/core/scm.c (ffffffff81775f7e)
Location: include/linux/sched.h:2078
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff817b92d5)
Location: include/linux/sched.h:2078
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
In kernel/signal.c (ffffffff81097416)
Location: include/linux/sched.h:2165
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:SYSC_kill
```
```
In kernel/sys.c (ffffffff8109cb59)
Location: include/linux/sched.h:2165
Inline: True
Inline callers:
  - kernel/sys.c:sys_getppid
  - kernel/sys.c:sys_getpid
```
```
In kernel/cgroup.c (ffffffff81128d63)
Location: include/linux/sched.h:2165
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_start
```
```
In kernel/audit.c (ffffffff8113529a)
Location: include/linux/sched.h:2165
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/coredump.c (ffffffff812b019d)
Location: include/linux/sched.h:2165
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In ipc/msg.c (ffffffff81371b58)
Location: include/linux/sched.h:2165
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff81375024)
Location: include/linux/sched.h:2165
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
```
```
In ipc/shm.c (ffffffff8137577c)
Location: include/linux/sched.h:2165
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In security/tomoyo/audit.c (ffffffff813b3931)
Location: include/linux/sched.h:2165
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff813b9a64)
Location: include/linux/sched.h:2165
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In net/core/scm.c (ffffffff817a31fe)
Location: include/linux/sched.h:2165
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff817e8d7f)
Location: include/linux/sched.h:2165
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
In kernel/signal.c (ffffffff81094729)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:SYSC_kill
```
```
In kernel/sys.c (ffffffff81099996)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - kernel/sys.c:sys_getppid
  - kernel/sys.c:sys_getpid
```
```
In kernel/cgroup/cgroup.c (ffffffff811220a6)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8112a2a9)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In fs/coredump.c (ffffffff812bd64c)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In ipc/msg.c (ffffffff81384f3e)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff81388b0a)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
```
```
In ipc/shm.c (ffffffff81389344)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In security/tomoyo/audit.c (ffffffff813ca2f8)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff813d04a2)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In net/core/scm.c (ffffffff817c12ea)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81808a36)
Location: include/linux/sched.h:1208
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
In kernel/signal.c (ffffffff8109b5c9)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:SYSC_kill
```
```
In kernel/sys.c (ffffffff810a0676)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - kernel/sys.c:sys_getppid
  - kernel/sys.c:sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81136f9b)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffffffff812e0f1b)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In ipc/msg.c (ffffffff813a921b)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff813ad7d3)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffffffff813ae094)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In security/tomoyo/audit.c (ffffffff813f0798)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff813f692d)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In net/core/scm.c (ffffffff8183acff)
Location: include/linux/sched.h:1208
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff818878e6)
Location: include/linux/sched.h:1208
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
In kernel/signal.c (ffffffff8109f5d3)
Location: include/linux/sched.h:1300
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__do_sys_kill
```
```
In kernel/sys.c (ffffffff810a30ad)
Location: include/linux/sched.h:1300
Inline: True
Inline callers:
  - kernel/sys.c:__x64_sys_getppid
  - kernel/sys.c:__x64_sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81145788)
Location: include/linux/sched.h:1300
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffffffff8130d155)
Location: include/linux/sched.h:1300
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In security/tomoyo/audit.c (ffffffff814216a0)
Location: include/linux/sched.h:1300
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff81427938)
Location: include/linux/sched.h:1300
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (ffffffff81707493)
Location: include/linux/sched.h:1300
Inline: True
```
```
In net/core/scm.c (ffffffff81885445)
Location: include/linux/sched.h:1300
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff818db337)
Location: include/linux/sched.h:1300
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
In kernel/signal.c (ffffffff810a7874)
Location: include/linux/sched.h:1302
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
```
In kernel/sys.c (ffffffff810abf1d)
Location: include/linux/sched.h:1302
Inline: True
Inline callers:
  - kernel/sys.c:__x64_sys_getppid
  - kernel/sys.c:__x64_sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81151348)
Location: include/linux/sched.h:1302
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffffffff81322a1e)
Location: include/linux/sched.h:1302
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In security/tomoyo/audit.c (ffffffff8143dd20)
Location: include/linux/sched.h:1302
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff81443fb8)
Location: include/linux/sched.h:1302
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (ffffffff81729fd3)
Location: include/linux/sched.h:1302
Inline: True
```
```
In net/core/scm.c (ffffffff818a5b75)
Location: include/linux/sched.h:1302
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81907c39)
Location: include/linux/sched.h:1302
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
In kernel/signal.c (ffffffff810ae028)
Location: include/linux/sched.h:1374
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
```
In kernel/sys.c (ffffffff810b13c9)
Location: include/linux/sched.h:1374
Inline: True
Inline callers:
  - kernel/sys.c:__x64_sys_getppid
  - kernel/sys.c:__x64_sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115c617)
Location: include/linux/sched.h:1374
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffffffff8134a13f)
Location: include/linux/sched.h:1374
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In security/tomoyo/audit.c (ffffffff8146b8be)
Location: include/linux/sched.h:1374
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff8147205f)
Location: include/linux/sched.h:1374
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (ffffffff817656b3)
Location: include/linux/sched.h:1374
Inline: True
```
```
In net/core/scm.c (ffffffff818f0ed8)
Location: include/linux/sched.h:1374
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81968f59)
Location: include/linux/sched.h:1374
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
In kernel/signal.c (ffffffff810b4638)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
```
In kernel/sys.c (ffffffff810b7a99)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/sys.c:__x64_sys_getppid
  - kernel/sys.c:__x64_sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81167ddf)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffffffff813623df)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In security/tomoyo/audit.c (ffffffff8148569e)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff8148bdff)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (ffffffff817896a3)
Location: include/linux/sched.h:1368
Inline: True
```
```
In net/core/scm.c (ffffffff81922e18)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff8199f9f9)
Location: include/linux/sched.h:1368
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
In kernel/signal.c (ffffffff810bcb4a)
Location: include/linux/sched.h:1409
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
```
In kernel/sys.c (ffffffff810bf759)
Location: include/linux/sched.h:1409
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getppid
  - kernel/sys.c:__do_sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81179bdb)
Location: include/linux/sched.h:1409
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffffffff813a8475)
Location: include/linux/sched.h:1409
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
```
```
In security/tomoyo/audit.c (ffffffff814db86e)
Location: include/linux/sched.h:1409
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff814e2fd6)
Location: include/linux/sched.h:1409
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (ffffffff8184d4f3)
Location: include/linux/sched.h:1409
Inline: True
```
```
In net/core/scm.c (ffffffff819f6e74)
Location: include/linux/sched.h:1409
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81a78ae9)
Location: include/linux/sched.h:1409
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
In kernel/signal.c (ffffffff810b7e6a)
Location: include/linux/sched.h:1468
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
```
In kernel/sys.c (ffffffff810ba9ba)
Location: include/linux/sched.h:1468
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getppid
  - kernel/sys.c:__do_sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117694b)
Location: include/linux/sched.h:1468
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffffffff813b952c)
Location: include/linux/sched.h:1468
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
```
```
In security/tomoyo/audit.c (ffffffff814f8cde)
Location: include/linux/sched.h:1468
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff815003e1)
Location: include/linux/sched.h:1468
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (ffffffff8185f238)
Location: include/linux/sched.h:1468
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read
```
```
In net/core/scm.c (ffffffff819f68e4)
Location: include/linux/sched.h:1468
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81a81dee)
Location: include/linux/sched.h:1468
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
In kernel/signal.c (ffffffff810b93ca)
Location: include/linux/sched.h:1490
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
```
In kernel/sys.c (ffffffff810bc2ea)
Location: include/linux/sched.h:1490
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getppid
  - kernel/sys.c:__do_sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117735c)
Location: include/linux/sched.h:1490
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffffffff813c069d)
Location: include/linux/sched.h:1490
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In security/tomoyo/audit.c (ffffffff814ffa6e)
Location: include/linux/sched.h:1490
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff8150702c)
Location: include/linux/sched.h:1490
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (ffffffff818431ef)
Location: include/linux/sched.h:1490
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read
```
```
In net/core/scm.c (ffffffff819dca52)
Location: include/linux/sched.h:1490
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81a6aede)
Location: include/linux/sched.h:1490
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
In kernel/signal.c (ffffffff810cb9da)
Location: include/linux/sched.h:1588
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
```
In kernel/sys.c (ffffffff810cecda)
Location: include/linux/sched.h:1588
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getppid
  - kernel/sys.c:__do_sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119eacc)
Location: include/linux/sched.h:1588
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffffffff81410505)
Location: include/linux/sched.h:1588
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In security/tomoyo/audit.c (ffffffff8155aadf)
Location: include/linux/sched.h:1588
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff81564072)
Location: include/linux/sched.h:1588
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (ffffffff818cd068)
Location: include/linux/sched.h:1588
Inline: True
```
```
In net/core/scm.c (ffffffff81a8cc92)
Location: include/linux/sched.h:1588
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81b244de)
Location: include/linux/sched.h:1588
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
In kernel/signal.c (ffffffff810e2ab4)
Location: include/linux/sched.h:1600
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
```
In kernel/sys.c (ffffffff810e74f6)
Location: include/linux/sched.h:1600
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getppid
  - kernel/sys.c:__do_sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811cf287)
Location: include/linux/sched.h:1600
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffffffff81486002)
Location: include/linux/sched.h:1600
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In security/tomoyo/audit.c (ffffffff815f58a1)
Location: include/linux/sched.h:1600
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff815ff276)
Location: include/linux/sched.h:1600
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (ffffffff81a1adb7)
Location: include/linux/sched.h:1600
Inline: True
```
```
In net/core/scm.c (ffffffff81c02572)
Location: include/linux/sched.h:1600
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81cac6ce)
Location: include/linux/sched.h:1600
Inline: True
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
In kernel/signal.c (ffffffff81102f14)
Location: include/linux/sched.h:1622
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
```
In kernel/sys.c (ffffffff81108136)
Location: include/linux/sched.h:1622
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getppid
  - kernel/sys.c:__do_sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81212c17)
Location: include/linux/sched.h:1622
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffffffff81518e65)
Location: include/linux/sched.h:1622
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In security/tomoyo/audit.c (ffffffff816a63a1)
Location: include/linux/sched.h:1622
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff816b0116)
Location: include/linux/sched.h:1622
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (ffffffff81b9bfb7)
Location: include/linux/sched.h:1622
Inline: True
```
```
In net/core/scm.c (ffffffff81db1a02)
Location: include/linux/sched.h:1622
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81e6a2ce)
Location: include/linux/sched.h:1622
Inline: True
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
In kernel/signal.c (ffffffff8110f154)
Location: include/linux/sched.h:1631
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
```
In kernel/sys.c (ffffffff81114446)
Location: include/linux/sched.h:1631
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getppid
  - kernel/sys.c:__do_sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81228527)
Location: include/linux/sched.h:1631
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffffffff81550765)
Location: include/linux/sched.h:1631
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In security/tomoyo/audit.c (ffffffff816ded81)
Location: include/linux/sched.h:1631
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff816e866d)
Location: include/linux/sched.h:1631
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (ffffffff81bf25a7)
Location: include/linux/sched.h:1631
Inline: True
```
```
In net/core/scm.c (ffffffff81e21fa0)
Location: include/linux/sched.h:1631
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81ec628c)
Location: include/linux/sched.h:1631
Inline: True
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
In kernel/signal.c (ffffffff81118ad4)
Location: include/linux/pid.h:290
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
```
In kernel/sys.c (ffffffff8111de36)
Location: include/linux/pid.h:290
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getppid
  - kernel/sys.c:__do_sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81240328)
Location: include/linux/pid.h:290
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffffffff815865f5)
Location: include/linux/pid.h:290
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In security/tomoyo/audit.c (ffffffff8171b992)
Location: include/linux/pid.h:290
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff8172537d)
Location: include/linux/pid.h:290
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (ffffffff81c47e97)
Location: include/linux/pid.h:290
Inline: True
```
```
In net/core/scm.c (ffffffff81edfec6)
Location: include/linux/pid.h:290
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81f894fe)
Location: include/linux/pid.h:290
Inline: True
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
In kernel/signal.c (ffff8000101106f0)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__arm64_sys_pidfd_send_signal
  - kernel/signal.c:__arm64_sys_kill
```
```
In kernel/sys.c (ffff800010114168)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_getppid
  - kernel/sys.c:__arm64_sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101da8ec)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffff800010428b60)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In security/tomoyo/audit.c (ffff800010577b58)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffff80001057eda4)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (ffff80001098ef68)
Location: include/linux/sched.h:1368
Inline: True
```
```
In net/core/scm.c (ffff800010bbdb10)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffff800010c4d1b4)
Location: include/linux/sched.h:1368
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
In kernel/signal.c (c03680b0)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_kill
```
```
In kernel/sys.c (c036cd44)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/sys.c:sys_getppid
  - kernel/sys.c:sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (c041d228)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In fs/coredump.c (c05f1a40)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
```
```
In security/tomoyo/audit.c (c072a994)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (c073171c)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (c0a61990)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_check_file_access
  - drivers/scsi/sg.c:sg_check_file_access
```
```
In net/core/scm.c (c0cd9c00)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (c0d5df50)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_autobind
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
In kernel/signal.c (c000000000157ec8)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_kill
```
```
In kernel/sys.c (c00000000015bdd4)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/sys.c:sys_getppid
  - kernel/sys.c:sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (c000000000248980)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (c0000000005390bc)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In security/tomoyo/audit.c (c0000000006e1304)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (c0000000006ebf34)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (c000000000a52b50)
Location: include/linux/sched.h:1368
Inline: True
```
```
In net/core/scm.c (c000000000c96efc)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (c000000000d4c080)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_autobind
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
In kernel/signal.c (ffffffe0000d0522)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_kill
```
```
In kernel/sys.c (ffffffe0000d3b8a)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/sys.c:sys_getppid
  - kernel/sys.c:sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000152ebc)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffffffe0002c6e6e)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In security/tomoyo/audit.c (ffffffe0003ca000)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffe0003cfec0)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (ffffffe0005f4622)
Location: include/linux/sched.h:1368
Inline: True
```
```
In net/core/scm.c (ffffffe00074bee0)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffe0007b9fe4)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_autobind
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
In kernel/signal.c (ffffffff810ae9a8)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
```
In kernel/sys.c (ffffffff810b1e09)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/sys.c:__x64_sys_getppid
  - kernel/sys.c:__x64_sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811603ff)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffffffff8135a9bf)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In security/tomoyo/audit.c (ffffffff8147dc7e)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff814843df)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (ffffffff8173dd93)
Location: include/linux/sched.h:1368
Inline: True
```
```
In net/core/scm.c (ffffffff818c2e18)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff8193f869)
Location: include/linux/sched.h:1368
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
In kernel/signal.c (ffffffff8109d2f8)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
```
In kernel/sys.c (ffffffff810a0729)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/sys.c:__x64_sys_getppid
  - kernel/sys.c:__x64_sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115366f)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffffffff8134b663)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In security/tomoyo/audit.c (ffffffff8146e69e)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff81474dff)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (ffffffff8171fa33)
Location: include/linux/sched.h:1368
Inline: True
```
```
In net/core/scm.c (ffffffff8187cd58)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff818f9369)
Location: include/linux/sched.h:1368
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
In kernel/signal.c (ffffffff810adf08)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
```
In kernel/sys.c (ffffffff810b1369)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/sys.c:__x64_sys_getppid
  - kernel/sys.c:__x64_sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115e1cf)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffffffff8135848f)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In security/tomoyo/audit.c (ffffffff81479d1e)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff8148047f)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (ffffffff8177e523)
Location: include/linux/sched.h:1368
Inline: True
```
```
In net/core/scm.c (ffffffff81913e18)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff819909f9)
Location: include/linux/sched.h:1368
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
In kernel/signal.c (ffffffff810b6178)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
```
In kernel/sys.c (ffffffff810b99d6)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/sys.c:__x64_sys_getppid
  - kernel/sys.c:__x64_sys_getpid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116b5ff)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In fs/coredump.c (ffffffff8136bbb4)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In security/tomoyo/audit.c (ffffffff814917d3)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff81497fea)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In drivers/scsi/sg.c (ffffffff81798333)
Location: include/linux/sched.h:1368
Inline: True
```
```
In net/core/scm.c (ffffffff81934fa8)
Location: include/linux/sched.h:1368
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff819b333f)
Location: include/linux/sched.h:1368
Inline: True
```
</details>
</li>
</ul>

## Differences
