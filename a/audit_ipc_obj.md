# Function: <code>audit_ipc_obj</code>

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
In ipc/util.c (ffffffff81324ccf)
Location: include/linux/audit.h:258
Inline: True
Inline callers:
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcctl_pre_down_nolock
```
```
In ipc/shm.c (ffffffff8132b116)
Location: include/linux/audit.h:258
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
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
In ipc/util.c (ffffffff81359e77)
Location: include/linux/audit.h:361
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
```
```
In ipc/shm.c (ffffffff8135fdb6)
Location: include/linux/audit.h:361
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
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
In ipc/util.c (ffffffff81370357)
Location: include/linux/audit.h:361
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
```
```
In ipc/shm.c (ffffffff813765b6)
Location: include/linux/audit.h:361
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
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
In ipc/util.c (ffffffff81383727)
Location: include/linux/audit.h:360
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
```
```
In ipc/shm.c (ffffffff8138a12c)
Location: include/linux/audit.h:360
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
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
In ipc/util.c (ffffffff813a7b97)
Location: include/linux/audit.h:353
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
```
```
In ipc/shm.c (ffffffff813ae360)
Location: include/linux/audit.h:353
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
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
In ipc/util.c (ffffffff813d6f84)
Location: include/linux/audit.h:357
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff813d7e2d)
Location: include/linux/audit.h:357
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff813dab7a)
Location: include/linux/audit.h:357
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff813de8cc)
Location: include/linux/audit.h:357
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
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
In ipc/util.c (ffffffff813f1594)
Location: include/linux/audit.h:356
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff813f2437)
Location: include/linux/audit.h:356
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff813f51c4)
Location: include/linux/audit.h:356
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff813f8fcc)
Location: include/linux/audit.h:356
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
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
In ipc/util.c (ffffffff8141d846)
Location: include/linux/audit.h:389
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff8141ed2f)
Location: include/linux/audit.h:389
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8142153a)
Location: include/linux/audit.h:389
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff81425542)
Location: include/linux/audit.h:389
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
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
In ipc/util.c (ffffffff81437696)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff81438b7f)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8143b32a)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8143f292)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
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
In ipc/util.c (ffffffff814876e7)
Location: include/linux/audit.h:401
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff81488635)
Location: include/linux/audit.h:401
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8148b88a)
Location: include/linux/audit.h:401
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8148fe02)
Location: include/linux/audit.h:401
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
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
In ipc/util.c (ffffffff814a4d07)
Location: include/linux/audit.h:418
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff814a5c65)
Location: include/linux/audit.h:418
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff814a8ea9)
Location: include/linux/audit.h:418
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff814ad512)
Location: include/linux/audit.h:418
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
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
In ipc/util.c (ffffffff814aacc7)
Location: include/linux/audit.h:418
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff814abc35)
Location: include/linux/audit.h:418
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff814b0299)
Location: include/linux/audit.h:418
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff814b3392)
Location: include/linux/audit.h:418
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
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
In ipc/util.c (ffffffff81503166)
Location: include/linux/audit.h:418
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff815040f7)
Location: include/linux/audit.h:418
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8150835b)
Location: include/linux/audit.h:418
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8150ba02)
Location: include/linux/audit.h:418
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
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
In ipc/util.c (ffffffff815947b7)
Location: include/linux/audit.h:445
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff815959e3)
Location: include/linux/audit.h:445
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff815978aa)
Location: include/linux/audit.h:445
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8159d03c)
Location: include/linux/audit.h:445
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
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
In ipc/util.c (ffffffff8163d437)
Location: include/linux/audit.h:442
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff8163e243)
Location: include/linux/audit.h:442
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff81640a62)
Location: include/linux/audit.h:442
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8164652c)
Location: include/linux/audit.h:442
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
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
In ipc/util.c (ffffffff81675953)
Location: include/linux/audit.h:441
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff81676733)
Location: include/linux/audit.h:441
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff81678fbf)
Location: include/linux/audit.h:441
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8167ea3c)
Location: include/linux/audit.h:441
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
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
In ipc/util.c (ffffffff816b1d13)
Location: include/linux/audit.h:440
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff816b2af3)
Location: include/linux/audit.h:440
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff816b53af)
Location: include/linux/audit.h:440
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff816bae2c)
Location: include/linux/audit.h:440
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
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
In ipc/util.c (ffff80001051decc)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffff80001051f6dc)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffff800010522ef4)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffff8000105276a0)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
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
In ipc/util.c (c06da334)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (c06dbe98)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/msg.c:ksys_msgctl
```
```
In ipc/sem.c (c06de4d4)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/sem.c:ksys_semctl
```
```
In ipc/shm.c (c06e0e68)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
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
In ipc/util.c (c000000000667360)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (c000000000669130)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (c00000000066cb30)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (c000000000672084)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
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
In ipc/util.c (ffffffe000385688)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffe000386886)
Location: include/linux/audit.h:382
Inline: True
```
```
In ipc/sem.c (ffffffe000389e96)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/sem.c:__se_sys_semctl
```
```
In ipc/shm.c (ffffffe00038b600)
Location: include/linux/audit.h:382
Inline: True
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
In ipc/util.c (ffffffff8142fc76)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff8143115f)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8143390a)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff81437872)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
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
In ipc/util.c (ffffffff814206f6)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff81421bdf)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8142438a)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff814282e2)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
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
In ipc/util.c (ffffffff8142be16)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff8142d2ff)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8142faaa)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff81433a12)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
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
In ipc/util.c (ffffffff81442e36)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff8144365b)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff814453e9)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8144a16d)
Location: include/linux/audit.h:382
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
</details>
</li>
</ul>

## Differences
