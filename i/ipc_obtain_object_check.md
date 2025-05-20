# Function: <code>ipc_obtain_object_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81324f90)
Location: ipc/util.c:617
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:exit_sem
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81324f90-ffffffff81325012: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81359b80)
Location: ipc/util.c:612
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/shm.c:do_shmat
  - ipc/shm.c:SyS_shmctl
```
**Symbols:**

```
ffffffff81359b80-ffffffff81359c02: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81370060)
Location: ipc/util.c:612
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/shm.c:do_shmat
  - ipc/shm.c:SyS_shmctl
```
**Symbols:**

```
ffffffff81370060-ffffffff813700e2: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81383480)
Location: ipc/util.c:556
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/shm.c:do_shmat
  - ipc/shm.c:SyS_shmctl
```
**Symbols:**

```
ffffffff81383480-ffffffff813834d8: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813a7830)
Location: ipc/util.c:622
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff813a7830-ffffffff813a7896: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813d6bd0)
Location: ipc/util.c:626
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff813d6bd0-ffffffff813d6c36: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813f11e0)
Location: ipc/util.c:587
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff813f11e0-ffffffff813f1238: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8141d480)
Location: ipc/util.c:616
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff8141d480-ffffffff8141d4de: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814372d0)
Location: ipc/util.c:616
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff814372d0-ffffffff8143732e: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81487665)
Location: ipc/util.c:616
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff81487410-ffffffff81487474: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814a4c89)
Location: ipc/util.c:616
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff814a4a30-ffffffff814a4a94: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814aac49)
Location: ipc/util.c:616
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff814aa9f0-ffffffff814aaa54: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/util.c (0)
Location: ipc/util.c:650
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff81cd294e-ffffffff81cd2992: ipc_obtain_object_check.cold (STB_LOCAL)
ffffffff81502ed0-ffffffff81502f4d: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/util.c (0)
Location: ipc/util.c:650
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff81e85aa4-ffffffff81e85ae8: ipc_obtain_object_check.cold (STB_LOCAL)
ffffffff815944f0-ffffffff81594585: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/util.c (0)
Location: ipc/util.c:650
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff82072cb2-ffffffff82072cf6: ipc_obtain_object_check.cold (STB_LOCAL)
ffffffff8163d140-ffffffff8163d1d5: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/util.c (0)
Location: ipc/util.c:650
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff820f2909-ffffffff820f294d: ipc_obtain_object_check.cold (STB_LOCAL)
ffffffff81675650-ffffffff816756e5: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/util.c (0)
Location: ipc/util.c:650
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff821cfbb9-ffffffff821cfbfd: ipc_obtain_object_check.cold (STB_LOCAL)
ffffffff816b1a10-ffffffff816b1aa5: ipc_obtain_object_check (STB_GLOBAL)
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
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffff80001051da88)
Location: ipc/util.c:616
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffff80001051da88-ffff80001051db14: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (c06d9f08)
Location: ipc/util.c:616
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:ksys_msgctl
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:semctl_main
  - ipc/shm.c:do_shmat
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
c06d9f08-c06d9f68: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (c000000000666df0)
Location: ipc/util.c:616
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
c000000000666df0-c000000000666e88: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffe0003852ee)
Location: ipc/util.c:616
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:semctl_main
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffe0003852ee-ffffffe000385356: ipc_obtain_object_check (STB_GLOBAL)
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
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142f8b0)
Location: ipc/util.c:616
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff8142f8b0-ffffffff8142f90e: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81420330)
Location: ipc/util.c:616
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff81420330-ffffffff8142038e: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142ba50)
Location: ipc/util.c:616
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff8142ba50-ffffffff8142baae: ipc_obtain_object_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_check(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81442a60)
Location: ipc/util.c:616
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff81442a60-ffffffff81442abe: ipc_obtain_object_check (STB_GLOBAL)
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
