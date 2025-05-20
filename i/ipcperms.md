# Function: <code>ipcperms</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81324ca0)
Location: ipc/util.c:484
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgrcv
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:SyS_semctl
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81324ca0-ffffffff81324d91: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81359890)
Location: ipc/util.c:479
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81359890-ffffffff81359981: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8136fd70)
Location: ipc/util.c:479
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff8136fd70-ffffffff8136fe61: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813831f0)
Location: ipc/util.c:423
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff813831f0-ffffffff813832d1: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813a7590)
Location: ipc/util.c:486
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff813a7590-ffffffff813a7671: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813d6930)
Location: ipc/util.c:490
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff813d6930-ffffffff813d6a16: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813f0fc0)
Location: ipc/util.c:490
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff813f0fc0-ffffffff813f10a6: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8141d260)
Location: ipc/util.c:519
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff8141d260-ffffffff8141d347: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814370b0)
Location: ipc/util.c:519
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff814370b0-ffffffff81437197: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814871f0)
Location: ipc/util.c:519
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff814871f0-ffffffff814872d7: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814a4810)
Location: ipc/util.c:519
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff814a4810-ffffffff814a48f7: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814aa7d0)
Location: ipc/util.c:519
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff814aa7d0-ffffffff814aa8b7: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81502c90)
Location: ipc/util.c:553
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff81502c90-ffffffff81502d77: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81594290)
Location: ipc/util.c:553
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff81594290-ffffffff81594381: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8163cea0)
Location: ipc/util.c:553
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff8163cea0-ffffffff8163cf91: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff816753b0)
Location: ipc/util.c:553
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff816753b0-ffffffff816754a1: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff816b1770)
Location: ipc/util.c:553
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff816b1770-ffffffff816b1861: ipcperms (STB_GLOBAL)
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
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffff80001051d840)
Location: ipc/util.c:519
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffff80001051d840-ffff80001051d92c: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (c06d9c60)
Location: ipc/util.c:519
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:ksys_msgctl
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:semctl_main
  - ipc/shm.c:do_shmat
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
c06d9c60-c06d9d4c: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (c000000000666af0)
Location: ipc/util.c:519
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
c000000000666af0-c000000000666c44: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffe0003850da)
Location: ipc/util.c:519
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:semctl_main
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffe0003850da-ffffffe0003851bc: ipcperms (STB_GLOBAL)
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
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142f690)
Location: ipc/util.c:519
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff8142f690-ffffffff8142f777: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81420110)
Location: ipc/util.c:519
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff81420110-ffffffff814201f7: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142b830)
Location: ipc/util.c:519
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff8142b830-ffffffff8142b917: ipcperms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace *ns, struct kern_ipc_perm *ipcp, short int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81442840)
Location: ipc/util.c:519
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff81442840-ffffffff81442927: ipcperms (STB_GLOBAL)
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
