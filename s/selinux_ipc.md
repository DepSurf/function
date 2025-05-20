# Function: <code>selinux_ipc</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a3955)
Location: security/selinux/include/objsec.h:204
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813c9755)
Location: security/selinux/include/objsec.h:208
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814149a5)
Location: security/selinux/include/objsec.h:185
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814421e5)
Location: security/selinux/include/objsec.h:182
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145bc55)
Location: security/selinux/include/objsec.h:172
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814aee15)
Location: security/selinux/include/objsec.h:176
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814cc8b5)
Location: security/selinux/include/objsec.h:175
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d2ee5)
Location: security/selinux/include/objsec.h:175
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8152bba5)
Location: security/selinux/include/objsec.h:175
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c18d5)
Location: security/selinux/include/objsec.h:175
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8166df25)
Location: security/selinux/include/objsec.h:175
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816a65f5)
Location: security/selinux/include/objsec.h:175
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e30b5)
Location: security/selinux/include/objsec.h:177
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getlsmblob
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff800010548630)
Location: security/selinux/include/objsec.h:172
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c06fe10c)
Location: security/selinux/include/objsec.h:172
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c00000000069f690)
Location: security/selinux/include/objsec.h:172
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a3888)
Location: security/selinux/include/objsec.h:172
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81454235)
Location: security/selinux/include/objsec.h:172
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81444c75)
Location: security/selinux/include/objsec.h:172
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814502d5)
Location: security/selinux/include/objsec.h:172
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81467775)
Location: security/selinux/include/objsec.h:172
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ipc_getsecid
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
```
</details>
</li>
</ul>

## Differences
