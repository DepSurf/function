# Function: <code>ipc_lock_object</code>

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
In ipc/util.c (ffffffff8132489a)
Location: ipc/util.h:168
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff81325cb9)
Location: ipc/util.h:168
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
```
```
In ipc/sem.c (ffffffff8132803e)
Location: ipc/util.h:168
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:exit_sem
```
```
In ipc/shm.c (ffffffff8132a63a)
Location: ipc/util.h:168
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:do_shmat
```
```
In ipc/namespace.c (ffffffff8132eaea)
Location: ipc/util.h:168
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff8135948a)
Location: ipc/util.h:168
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff8135b312)
Location: ipc/util.h:168
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8135e77d)
Location: ipc/util.h:168
Inline: True
Inline callers:
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
  - ipc/sem.c:semctl_main
```
```
In ipc/shm.c (ffffffff813600f4)
Location: ipc/util.h:168
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:exit_shm
```
```
In ipc/namespace.c (ffffffff813637aa)
Location: ipc/util.h:168
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff8136f97e)
Location: ipc/util.h:168
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff81371943)
Location: ipc/util.h:168
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff81374f52)
Location: ipc/util.h:168
Inline: True
Inline callers:
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
  - ipc/sem.c:semctl_main
```
```
In ipc/shm.c (ffffffff81376905)
Location: ipc/util.h:168
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:exit_shm
```
```
In ipc/namespace.c (ffffffff81379fba)
Location: ipc/util.h:168
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff813835b5)
Location: ipc/util.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff81384cfe)
Location: ipc/util.h:155
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff81388a31)
Location: ipc/util.h:155
Inline: True
Inline callers:
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
  - ipc/sem.c:semctl_main
```
```
In ipc/shm.c (ffffffff8138a4d0)
Location: ipc/util.h:155
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:exit_shm
```
```
In ipc/namespace.c (ffffffff8138dbb2)
Location: ipc/util.h:155
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff813a79a4)
Location: ipc/util.h:169
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff813a8fd3)
Location: ipc/util.h:169
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffffffff813ad6fa)
Location: ipc/util.h:169
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
```
In ipc/shm.c (ffffffff813af640)
Location: ipc/util.h:169
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
```
```
In ipc/namespace.c (ffffffff813b3022)
Location: ipc/util.h:169
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff813d6dc4)
Location: ipc/util.h:181
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff813d88ac)
Location: ipc/util.h:181
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffffffff813dd16c)
Location: ipc/util.h:181
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff813df45d)
Location: ipc/util.h:181
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
```
```
In ipc/namespace.c (ffffffff813e3766)
Location: ipc/util.h:181
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff813f13c8)
Location: ipc/util.h:180
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff813f272c)
Location: ipc/util.h:180
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffffffff813f77cc)
Location: ipc/util.h:180
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff813f9bc2)
Location: ipc/util.h:180
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
```
In ipc/namespace.c (ffffffff813fe0a6)
Location: ipc/util.h:180
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff8141d670)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff8141f5e3)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffffffff81423cff)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff814261c5)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
```
In ipc/namespace.c (ffffffff8142a6d2)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff814374c0)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff81439403)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffffffff8143da3f)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8143ff15)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
```
In ipc/namespace.c (ffffffff81444402)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff81486572)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipc_findkey
```
```
In ipc/msg.c (ffffffff814894cb)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffffffff8148e5b4)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff81490c95)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
```
In ipc/namespace.c (ffffffff814953f2)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff814a3b6b)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipc_findkey
```
```
In ipc/msg.c (ffffffff814a6aeb)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffffffff814abcf0)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff814ae3e2)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
```
In ipc/namespace.c (ffffffff814b2e52)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff814a9b6b)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipc_findkey
```
```
In ipc/msg.c (ffffffff814aca4d)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffffffff814b1b82)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff814b420f)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
```
In ipc/namespace.c (ffffffff814b8c92)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff81501ec6)
Location: ipc/util.h:209
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipc_findkey
```
```
In ipc/msg.c (ffffffff81504f2e)
Location: ipc/util.h:209
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffffffff8150a132)
Location: ipc/util.h:209
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8150c89f)
Location: ipc/util.h:209
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
```
In ipc/namespace.c (ffffffff815114c2)
Location: ipc/util.h:209
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff8159332d)
Location: ipc/util.h:209
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipc_findkey
```
```
In ipc/msg.c (ffffffff81596887)
Location: ipc/util.h:209
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffffffff8159be8f)
Location: ipc/util.h:209
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8159e852)
Location: ipc/util.h:209
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
```
In ipc/namespace.c (ffffffff815a374f)
Location: ipc/util.h:209
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff8163bf1f)
Location: ipc/util.h:209
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipc_findkey
```
```
In ipc/msg.c (ffffffff8163f78b)
Location: ipc/util.h:209
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffffffff8164528f)
Location: ipc/util.h:209
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff81647f12)
Location: ipc/util.h:209
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_open
```
```
In ipc/namespace.c (ffffffff8164d38f)
Location: ipc/util.h:209
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff816743cf)
Location: ipc/util.h:207
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipc_findkey
```
```
In ipc/msg.c (ffffffff81677cb9)
Location: ipc/util.h:207
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffffffff8167d793)
Location: ipc/util.h:207
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff81680428)
Location: ipc/util.h:207
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_open
```
```
In ipc/namespace.c (ffffffff81685b2e)
Location: ipc/util.h:207
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff816b078f)
Location: ipc/util.h:208
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipc_findkey
```
```
In ipc/msg.c (ffffffff816b4079)
Location: ipc/util.h:208
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffffffff816b9b63)
Location: ipc/util.h:208
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff816bc818)
Location: ipc/util.h:208
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_open
```
```
In ipc/namespace.c (ffffffff816c1f4e)
Location: ipc/util.h:208
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffff80001051dcbc)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffff80001051f948)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffff8000105258b0)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffff8000105286a4)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
```
In ipc/namespace.c (ffff80001052ce5c)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (c06da10c)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (c06dba70)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:ksys_msgctl
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (c06dfd84)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In ipc/shm.c (c06e1b5c)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
  - ipc/shm.c:__shm_open
```
```
In ipc/namespace.c (c06e5734)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (c000000000667090)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (c000000000669d88)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (c00000000066fd9c)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (c0000000006731a0)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
```
In ipc/namespace.c (c000000000678ef8)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffe0003854da)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffe000386294)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffffffe00038a206)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In ipc/shm.c (ffffffe00038bd60)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
```
In ipc/namespace.c (ffffffe00038ecf6)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff8142faa0)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff814319e3)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffffffff8143601f)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff814384f5)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
```
In ipc/namespace.c (ffffffff8143c9e2)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff81420520)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff81422463)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffffffff81426a9f)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff81428f65)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
```
In ipc/namespace.c (ffffffff8142d452)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff8142bc40)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff8142db83)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffffffff814321bf)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff81434695)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
```
In ipc/namespace.c (ffffffff81438b82)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
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
In ipc/util.c (ffffffff81442c5e)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In ipc/msg.c (ffffffff81444624)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffffffff8144928a)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8144b7b7)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
```
In ipc/namespace.c (ffffffff8144fcfc)
Location: ipc/util.h:206
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
```
</details>
</li>
</ul>

## Differences
