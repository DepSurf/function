# Function: <code>__audit_ipc_obj</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81129190)
Location: kernel/auditsc.c:2121
Inline: False
Direct callers:
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/shm.c:SyS_shmctl
```
**Symbols:**

```
ffffffff81129190-ffffffff811291ea: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81131350)
Location: kernel/auditsc.c:2125
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
  - ipc/shm.c:SyS_shmctl
```
**Symbols:**

```
ffffffff81131350-ffffffff811313aa: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113b0d0)
Location: kernel/auditsc.c:2133
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
  - ipc/shm.c:SyS_shmctl
```
**Symbols:**

```
ffffffff8113b0d0-ffffffff8113b12a: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113c6f0)
Location: kernel/auditsc.c:2142
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
  - ipc/shm.c:SyS_shmctl
```
**Symbols:**

```
ffffffff8113c6f0-ffffffff8113c74a: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81149470)
Location: kernel/auditsc.c:2165
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
```
**Symbols:**

```
ffffffff81149470-ffffffff811494ca: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81157de0)
Location: kernel/auditsc.c:2172
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff81157de0-ffffffff81157e3a: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81164de0)
Location: kernel/auditsc.c:2157
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff81164de0-ffffffff81164e3a: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811718f0)
Location: kernel/auditsc.c:2273
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff811718f0-ffffffff8117194a: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117d770)
Location: kernel/auditsc.c:2273
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff8117d770-ffffffff8117d7ca: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81190a30)
Location: kernel/auditsc.c:2325
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff81190a30-ffffffff81190a8d: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118dc50)
Location: kernel/auditsc.c:2342
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff8118dc50-ffffffff8118dcad: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118ebc0)
Location: kernel/auditsc.c:2339
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff8118ebc0-ffffffff8118ec1d: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b79d0)
Location: kernel/auditsc.c:2353
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff811b79d0-ffffffff811b7a2d: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811ea7b0)
Location: kernel/auditsc.c:2619
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff811ea7b0-ffffffff811ea872: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81230a40)
Location: kernel/auditsc.c:2597
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff81230a40-ffffffff81230b02: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff812475b0)
Location: kernel/auditsc.c:2596
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff812475b0-ffffffff812476b0: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81261420)
Location: kernel/auditsc.c:2591
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff81261420-ffffffff81261487: __audit_ipc_obj (STB_GLOBAL)
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
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101f2638)
Location: kernel/auditsc.c:2273
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffff8000101f2638-ffff8000101f2694: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c0432b30)
Location: kernel/auditsc.c:2273
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/msg.c:ksys_msgctl
  - ipc/sem.c:ksys_semctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
c0432b30-c0432b90: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c000000000266e40)
Location: kernel/auditsc.c:2273
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
c000000000266e40-c000000000266eb0: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe000165cd6)
Location: kernel/auditsc.c:2273
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/sem.c:__se_sys_semctl
```
**Symbols:**

```
ffffffe000165cd6-ffffffe000165d30: __audit_ipc_obj (STB_GLOBAL)
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
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81175d90)
Location: kernel/auditsc.c:2273
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff81175d90-ffffffff81175dea: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81168f30)
Location: kernel/auditsc.c:2273
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff81168f30-ffffffff81168f8a: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81173b60)
Location: kernel/auditsc.c:2273
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff81173b60-ffffffff81173bba: __audit_ipc_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81181420)
Location: kernel/auditsc.c:2273
Inline: False
Direct callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff81181420-ffffffff8118147a: __audit_ipc_obj (STB_GLOBAL)
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
