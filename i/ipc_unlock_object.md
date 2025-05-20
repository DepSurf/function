# Function: <code>ipc_unlock_object</code>

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
In ipc/util.c (ffffffff8132478a)
Location: ipc/util.h:173
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff813258a0)
Location: ipc/util.h:173
Inline: True
Inline callers:
  - ipc/msg.c:newque
  - ipc/msg.c:freeque
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
```
```
In ipc/sem.c (ffffffff81326fa9)
Location: ipc/util.h:173
Inline: True
Inline callers:
  - ipc/sem.c:newary
  - ipc/sem.c:freeary
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
```
```
In ipc/shm.c (ffffffff81329fa3)
Location: ipc/util.h:173
Inline: True
Inline callers:
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_close
  - ipc/shm.c:newseg
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
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
In ipc/util.c (ffffffff8135937a)
Location: ipc/util.h:173
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff8135b5ef)
Location: ipc/util.h:173
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff8135e91b)
Location: ipc/util.h:173
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff8136010d)
Location: ipc/util.h:173
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (ffffffff8136f867)
Location: ipc/util.h:173
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff81371bfc)
Location: ipc/util.h:173
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff813750fd)
Location: ipc/util.h:173
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff8137691e)
Location: ipc/util.h:173
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (ffffffff81382d97)
Location: ipc/util.h:160
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff81385013)
Location: ipc/util.h:160
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff81388c4d)
Location: ipc/util.h:160
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff8138a4e7)
Location: ipc/util.h:160
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (ffffffff813a6d37)
Location: ipc/util.h:174
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff813a9300)
Location: ipc/util.h:174
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff813ad928)
Location: ipc/util.h:174
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff813af657)
Location: ipc/util.h:174
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (ffffffff813d6119)
Location: ipc/util.h:186
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff813d89db)
Location: ipc/util.h:186
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff813dd393)
Location: ipc/util.h:186
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff813df4ab)
Location: ipc/util.h:186
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (ffffffff813f07c2)
Location: ipc/util.h:185
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff813f285b)
Location: ipc/util.h:185
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff813f79f3)
Location: ipc/util.h:185
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff813f9c06)
Location: ipc/util.h:185
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (ffffffff8141cae9)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff8141f90d)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff81423f11)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff8142620b)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (ffffffff81436939)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff8143972d)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff8143dc67)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff8143ff5b)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (ffffffff81486d89)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff81489750)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff8148e80e)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff81490cdb)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (ffffffff814a3d80)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff814a6d75)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff814abf4a)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff814ae428)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (ffffffff814aa360)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff814accc7)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff814b1e5e)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff814b4255)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (ffffffff81502849)
Location: ipc/util.h:214
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff815051b4)
Location: ipc/util.h:214
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff8150a41c)
Location: ipc/util.h:214
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff8150c8ef)
Location: ipc/util.h:214
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (ffffffff81593463)
Location: ipc/util.h:214
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff81596b7a)
Location: ipc/util.h:214
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff8159c191)
Location: ipc/util.h:214
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff8159e89a)
Location: ipc/util.h:214
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (ffffffff8163be33)
Location: ipc/util.h:214
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff8163fa7f)
Location: ipc/util.h:214
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff81645591)
Location: ipc/util.h:214
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff81647f5a)
Location: ipc/util.h:214
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:__shm_open
  - ipc/shm.c:__shm_open
  - ipc/shm.c:__shm_open
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
In ipc/util.c (ffffffff816742e3)
Location: ipc/util.h:212
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff81677f55)
Location: ipc/util.h:212
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff8167da7c)
Location: ipc/util.h:212
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff81680473)
Location: ipc/util.h:212
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:__shm_open
  - ipc/shm.c:__shm_open
  - ipc/shm.c:__shm_open
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
In ipc/util.c (ffffffff816b06a3)
Location: ipc/util.h:213
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff816b4315)
Location: ipc/util.h:213
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff816b9e44)
Location: ipc/util.h:213
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff816bc863)
Location: ipc/util.h:213
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:__shm_open
  - ipc/shm.c:__shm_open
  - ipc/shm.c:__shm_open
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
In ipc/util.c (ffff80001051cb8c)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffff80001051fc5c)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffff800010525aa0)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffff8000105286d0)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (c06d8f84)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (c06dba54)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:ksys_msgctl
  - ipc/msg.c:ksys_msgctl
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (c06dffa0)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (c06e1b70)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:__shm_open
  - ipc/shm.c:__shm_open
  - ipc/shm.c:__shm_open
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
In ipc/util.c (c000000000666100)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (c000000000669e84)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (c000000000670008)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (c0000000006731f4)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (ffffffe0003849c6)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffe000386128)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffe00038a18c)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffe00038bd84)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (ffffffff8142ef19)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff81431d0d)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff81436247)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff8143853b)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (ffffffff8141f999)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff8142278d)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff81426cc7)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff81428fab)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (ffffffff8142b0b9)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff8142dead)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff814323e7)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff814346db)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/util.c (ffffffff81441e30)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff814448e8)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff814494b1)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff8144b7fd)
Location: ipc/util.h:211
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
</ul>

## Differences
