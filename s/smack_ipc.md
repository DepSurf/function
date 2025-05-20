# Function: <code>smack_ipc</code>

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
In security/smack/smack_lsm.c (ffffffff813c14e5)
Location: security/smack/smack.h:415
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smack_msg_queue_alloc_security
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smack_sem_alloc_security
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_shm_alloc_security
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
In security/smack/smack_lsm.c (ffffffff813e7675)
Location: security/smack/smack.h:415
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smack_msg_queue_alloc_security
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smack_sem_alloc_security
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_shm_alloc_security
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
In security/smack/smack_lsm.c (ffffffff81434b65)
Location: security/smack/smack.h:382
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
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
In security/smack/smack_lsm.c (ffffffff814625b5)
Location: security/smack/smack.h:370
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
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
In security/smack/smack_lsm.c (ffffffff8147c365)
Location: security/smack/smack.h:370
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
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
In security/smack/smack_lsm.c (ffffffff814d1d65)
Location: security/smack/smack.h:363
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
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
In security/smack/smack_lsm.c (ffffffff814ef205)
Location: security/smack/smack.h:356
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
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
In security/smack/smack_lsm.c (ffffffff814f6295)
Location: security/smack/smack.h:356
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
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
In security/smack/smack_lsm.c (ffffffff81550de5)
Location: security/smack/smack.h:356
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
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
In security/smack/smack_lsm.c (ffffffff815ea375)
Location: security/smack/smack.h:356
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
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
In security/smack/smack_lsm.c (ffffffff81699e65)
Location: security/smack/smack.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
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
In security/smack/smack_lsm.c (ffffffff816d2645)
Location: security/smack/smack.h:348
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
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
In security/smack/smack_lsm.c (ffffffff8170ecf5)
Location: security/smack/smack.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getlsmblob
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
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
In security/smack/smack_lsm.c (ffff80001056d054)
Location: security/smack/smack.h:370
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
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
In security/smack/smack_lsm.c (c0720838)
Location: security/smack/smack.h:370
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
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
In security/smack/smack_lsm.c (c0000000006d15d0)
Location: security/smack/smack.h:370
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
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
In security/smack/smack_lsm.c (ffffffe0003c194e)
Location: security/smack/smack.h:370
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
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
In security/smack/smack_lsm.c (ffffffff81474945)
Location: security/smack/smack.h:370
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
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
In security/smack/smack_lsm.c (ffffffff81465365)
Location: security/smack/smack.h:370
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
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
In security/smack/smack_lsm.c (ffffffff814709e5)
Location: security/smack/smack.h:370
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
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
In security/smack/smack_lsm.c (ffffffff814881c5)
Location: security/smack/smack.h:370
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipc_getsecid
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
```
</details>
</li>
</ul>

## Differences
