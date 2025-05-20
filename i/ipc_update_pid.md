# Function: <code>ipc_update_pid</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813d8b5a)
Location: ipc/util.h:155
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (ffffffff813dd28c)
Location: ipc/util.h:155
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff813de654)
Location: ipc/util.h:155
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (ffffffff813f29da)
Location: ipc/util.h:154
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (ffffffff813f78ec)
Location: ipc/util.h:154
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff813f8d0f)
Location: ipc/util.h:154
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (ffffffff8141f813)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (ffffffff81423e1a)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff81425289)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (ffffffff81439633)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (ffffffff8143db70)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff8143efd9)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (ffffffff8148982a)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (ffffffff8148e6f0)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff8148fb9d)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (ffffffff814a6e63)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (ffffffff814abe2c)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff814ad2aa)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (ffffffff814acdbb)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (ffffffff814b1ce4)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff814b3126)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (ffffffff815052a6)
Location: ipc/util.h:186
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (ffffffff8150a2a2)
Location: ipc/util.h:186
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff8150b887)
Location: ipc/util.h:186
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (ffffffff81596c6a)
Location: ipc/util.h:186
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (ffffffff8159c00f)
Location: ipc/util.h:186
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff8159dae8)
Location: ipc/util.h:186
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (ffffffff8163fb6f)
Location: ipc/util.h:186
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (ffffffff8164540f)
Location: ipc/util.h:186
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff816470b6)
Location: ipc/util.h:186
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:__shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (ffffffff81678098)
Location: ipc/util.h:184
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (ffffffff8167d8f9)
Location: ipc/util.h:184
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff8167f5f9)
Location: ipc/util.h:184
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:__shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (ffffffff816b4458)
Location: ipc/util.h:185
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (ffffffff816b9ccc)
Location: ipc/util.h:185
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff816bb9e9)
Location: ipc/util.h:185
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:__shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (ffff80001051fb4c)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (ffff8000105259d0)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffff800010526718)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (c06db924)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (c06dfeb4)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (c06e08c0)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (c00000000066a138)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (c00000000066ff24)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (c000000000671bf0)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (ffffffe00038617a)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (ffffffe00038a2f8)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffe00038afca)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (ffffffff81431c13)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (ffffffff81436150)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff814375b9)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (ffffffff81422693)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (ffffffff81426bd0)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff81428029)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (ffffffff8142ddb3)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (ffffffff814322f0)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff81433759)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
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
In ipc/msg.c (ffffffff81444810)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In ipc/sem.c (ffffffff814493ba)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff8144ab2b)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
```
</details>
</li>
</ul>

## Differences
