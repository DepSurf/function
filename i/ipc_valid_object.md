# Function: <code>ipc_valid_object</code>

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
In ipc/util.c (0)
Location: ipc/util.h:197
Inline: True
```
```
In ipc/msg.c (0)
Location: ipc/util.h:197
Inline: True
```
```
In ipc/sem.c (0)
Location: ipc/util.h:197
Inline: True
```
```
In ipc/shm.c (0)
Location: ipc/util.h:197
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
In ipc/util.c (0)
Location: ipc/util.h:197
Inline: True
```
```
In ipc/msg.c (0)
Location: ipc/util.h:197
Inline: True
```
```
In ipc/sem.c (0)
Location: ipc/util.h:197
Inline: True
```
```
In ipc/shm.c (0)
Location: ipc/util.h:197
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
In ipc/util.c (0)
Location: ipc/util.h:197
Inline: True
```
```
In ipc/msg.c (0)
Location: ipc/util.h:197
Inline: True
```
```
In ipc/sem.c (0)
Location: ipc/util.h:197
Inline: True
```
```
In ipc/shm.c (0)
Location: ipc/util.h:197
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
In ipc/util.c (0)
Location: ipc/util.h:184
Inline: True
```
```
In ipc/msg.c (0)
Location: ipc/util.h:184
Inline: True
```
```
In ipc/sem.c (0)
Location: ipc/util.h:184
Inline: True
```
```
In ipc/shm.c (0)
Location: ipc/util.h:184
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
In ipc/util.c (0)
Location: ipc/util.h:198
Inline: True
```
```
In ipc/msg.c (0)
Location: ipc/util.h:198
Inline: True
```
```
In ipc/sem.c (0)
Location: ipc/util.h:198
Inline: True
```
```
In ipc/shm.c (0)
Location: ipc/util.h:198
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
In ipc/util.c (0)
Location: ipc/util.h:210
Inline: True
```
```
In ipc/msg.c (0)
Location: ipc/util.h:210
Inline: True
```
```
In ipc/sem.c (0)
Location: ipc/util.h:210
Inline: True
```
```
In ipc/shm.c (0)
Location: ipc/util.h:210
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
In ipc/msg.c (0)
Location: ipc/util.h:209
Inline: True
```
```
In ipc/sem.c (0)
Location: ipc/util.h:209
Inline: True
```
```
In ipc/shm.c (0)
Location: ipc/util.h:209
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
In ipc/msg.c (0)
Location: ipc/util.h:235
Inline: True
```
```
In ipc/sem.c (0)
Location: ipc/util.h:235
Inline: True
```
```
In ipc/shm.c (0)
Location: ipc/util.h:235
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
In ipc/msg.c (0)
Location: ipc/util.h:235
Inline: True
```
```
In ipc/sem.c (0)
Location: ipc/util.h:235
Inline: True
```
```
In ipc/shm.c (0)
Location: ipc/util.h:235
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
In ipc/msg.c (ffffffff814894d3)
Location: ipc/util.h:235
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8148e610)
Location: ipc/util.h:235
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff81490ca1)
Location: ipc/util.h:235
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shm_close
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
In ipc/msg.c (ffffffff814a6af3)
Location: ipc/util.h:235
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff814abd4c)
Location: ipc/util.h:235
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff814ae3ee)
Location: ipc/util.h:235
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shm_close
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
In ipc/msg.c (ffffffff814aca55)
Location: ipc/util.h:235
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff814b1bde)
Location: ipc/util.h:235
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff814b421b)
Location: ipc/util.h:235
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shm_close
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
In ipc/msg.c (ffffffff81504f36)
Location: ipc/util.h:238
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8150a18e)
Location: ipc/util.h:238
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8150c8ab)
Location: ipc/util.h:238
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
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
In ipc/msg.c (ffffffff8159688f)
Location: ipc/util.h:238
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8159bef7)
Location: ipc/util.h:238
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8159e85a)
Location: ipc/util.h:238
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
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
In ipc/msg.c (ffffffff8163f793)
Location: ipc/util.h:238
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff816452f7)
Location: ipc/util.h:238
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff81647f1a)
Location: ipc/util.h:238
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:__shm_close
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
In ipc/msg.c (ffffffff81677cc1)
Location: ipc/util.h:236
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8167d7e9)
Location: ipc/util.h:236
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff81680430)
Location: ipc/util.h:236
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:__shm_close
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
In ipc/msg.c (ffffffff816b4081)
Location: ipc/util.h:237
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff816b9bb7)
Location: ipc/util.h:237
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff816bc820)
Location: ipc/util.h:237
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:__shm_close
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
In ipc/msg.c (0)
Location: ipc/util.h:235
Inline: True
```
```
In ipc/sem.c (0)
Location: ipc/util.h:235
Inline: True
```
```
In ipc/shm.c (0)
Location: ipc/util.h:235
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
In ipc/msg.c (c06db8bc)
Location: ipc/util.h:235
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:ksys_msgctl
```
```
In ipc/sem.c (c06dfda4)
Location: ipc/util.h:235
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In ipc/shm.c (c06e1b64)
Location: ipc/util.h:235
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:shm_close
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
In ipc/msg.c (c000000000669d94)
Location: ipc/util.h:235
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (c00000000066fe1c)
Location: ipc/util.h:235
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (c0000000006731ac)
Location: ipc/util.h:235
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shm_close
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
In ipc/msg.c (ffffffe000386144)
Location: ipc/util.h:235
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffe00038a220)
Location: ipc/util.h:235
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In ipc/shm.c (ffffffe00038bd6a)
Location: ipc/util.h:235
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_close
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
In ipc/msg.c (0)
Location: ipc/util.h:235
Inline: True
```
```
In ipc/sem.c (0)
Location: ipc/util.h:235
Inline: True
```
```
In ipc/shm.c (0)
Location: ipc/util.h:235
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
In ipc/msg.c (0)
Location: ipc/util.h:235
Inline: True
```
```
In ipc/sem.c (0)
Location: ipc/util.h:235
Inline: True
```
```
In ipc/shm.c (0)
Location: ipc/util.h:235
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
In ipc/msg.c (0)
Location: ipc/util.h:235
Inline: True
```
```
In ipc/sem.c (0)
Location: ipc/util.h:235
Inline: True
```
```
In ipc/shm.c (0)
Location: ipc/util.h:235
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
In ipc/msg.c (0)
Location: ipc/util.h:235
Inline: True
```
```
In ipc/sem.c (0)
Location: ipc/util.h:235
Inline: True
```
```
In ipc/shm.c (0)
Location: ipc/util.h:235
Inline: True
```
</details>
</li>
</ul>

## Differences
