# Function: <code>compat_ipc_parse_version</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8132322c)
Location: ipc/compat.c:116
Inline: True
Inline callers:
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81358449)
Location: ipc/compat.c:116
Inline: True
Inline callers:
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:do_compat_semctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8136e939)
Location: ipc/compat.c:116
Inline: True
Inline callers:
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:do_compat_semctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81381eb9)
Location: ipc/compat.c:116
Inline: True
Inline callers:
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:do_compat_semctl
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
In ipc/msg.c (ffffffff813a958c)
Location: ipc/util.h:227
Inline: True
Inline callers:
  - ipc/msg.c:C_SYSC_msgctl
```
```
In ipc/sem.c (ffffffff813ad18c)
Location: ipc/util.h:227
Inline: True
Inline callers:
  - ipc/sem.c:C_SYSC_semctl
```
```
In ipc/shm.c (ffffffff813aed3c)
Location: ipc/util.h:227
Inline: True
Inline callers:
  - ipc/shm.c:C_SYSC_shmctl
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
In ipc/msg.c (ffffffff813d8f78)
Location: ipc/util.h:239
Inline: True
Inline callers:
  - ipc/msg.c:compat_ksys_msgctl
```
```
In ipc/sem.c (ffffffff813dccb4)
Location: ipc/util.h:239
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffffffff813defe2)
Location: ipc/util.h:239
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/msg.c (ffffffff813f35b8)
Location: ipc/util.h:247
Inline: True
Inline callers:
  - ipc/msg.c:compat_ksys_msgctl
```
```
In ipc/sem.c (ffffffff813f7302)
Location: ipc/util.h:247
Inline: True
Inline callers:
  - ipc/sem.c:compat_ksys_semctl
```
```
In ipc/shm.c (ffffffff813f9712)
Location: ipc/util.h:247
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
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
In ipc/msg.c (ffffffff8141f2ba)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
```
```
In ipc/sem.c (ffffffff8142365a)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
```
```
In ipc/shm.c (ffffffff81425ffa)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/msg.c (ffffffff814390da)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
```
```
In ipc/sem.c (ffffffff8143d39a)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
```
```
In ipc/shm.c (ffffffff8143fd4a)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/msg.c (ffffffff8148919a)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
```
```
In ipc/sem.c (ffffffff8148df6a)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
```
```
In ipc/shm.c (ffffffff814903ba)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/msg.c (ffffffff814a67ba)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
```
```
In ipc/sem.c (ffffffff814ab6aa)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
```
```
In ipc/shm.c (ffffffff814adada)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/msg.c (ffffffff814ac72a)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
```
```
In ipc/sem.c (ffffffff814b064a)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
```
```
In ipc/shm.c (ffffffff814b392a)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/msg.c (ffffffff81504c0a)
Location: ipc/util.h:276
Inline: True
Inline callers:
  - ipc/msg.c:__x64_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
```
```
In ipc/sem.c (ffffffff8150871a)
Location: ipc/util.h:276
Inline: True
Inline callers:
  - ipc/sem.c:__x64_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
```
```
In ipc/shm.c (ffffffff8150bf9a)
Location: ipc/util.h:276
Inline: True
Inline callers:
  - ipc/shm.c:__x64_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/msg.c (ffffffff81595d7a)
Location: ipc/util.h:276
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
```
```
In ipc/sem.c (ffffffff8159a70a)
Location: ipc/util.h:276
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_compat_sys_old_semctl
```
```
In ipc/shm.c (ffffffff8159e08a)
Location: ipc/util.h:276
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/msg.c (ffffffff8163ebba)
Location: ipc/util.h:276
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
```
```
In ipc/sem.c (ffffffff816439da)
Location: ipc/util.h:276
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_compat_sys_old_semctl
```
```
In ipc/shm.c (ffffffff8164769a)
Location: ipc/util.h:276
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/msg.c (ffffffff816770da)
Location: ipc/util.h:274
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
```
```
In ipc/sem.c (ffffffff8167bf2a)
Location: ipc/util.h:274
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_compat_sys_old_semctl
```
```
In ipc/shm.c (ffffffff8167fbca)
Location: ipc/util.h:274
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/msg.c (ffffffff816b349a)
Location: ipc/util.h:275
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
```
```
In ipc/sem.c (ffffffff816b82fa)
Location: ipc/util.h:275
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_compat_sys_old_semctl
```
```
In ipc/shm.c (ffffffff816bbfba)
Location: ipc/util.h:275
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/msg.c (ffff800010520ec4)
Location: ipc/util.h:273
Inline: True
```
```
In ipc/sem.c (ffff8000105251e0)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/sem.c:__arm64_compat_sys_old_semctl
```
```
In ipc/shm.c (ffff80001052850c)
Location: ipc/util.h:273
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c000000000669bd0)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/msg.c:__se_compat_sys_old_msgctl
```
```
In ipc/sem.c (c00000000066e440)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/sem.c:__se_compat_sys_old_semctl
```
```
In ipc/shm.c (c000000000672f30)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/shm.c:__se_compat_sys_old_shmctl
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In ipc/msg.c (ffffffff814316ba)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
```
```
In ipc/sem.c (ffffffff8143597a)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
```
```
In ipc/shm.c (ffffffff8143832a)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/msg.c (ffffffff8142213a)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
```
```
In ipc/sem.c (ffffffff814263fa)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
```
```
In ipc/shm.c (ffffffff81428d9a)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/msg.c (ffffffff8142d85a)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
```
```
In ipc/sem.c (ffffffff81431b1a)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
```
```
In ipc/shm.c (ffffffff814344ca)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/msg.c (ffffffff8144428a)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
```
```
In ipc/sem.c (ffffffff81448bea)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
```
```
In ipc/shm.c (ffffffff8144b5da)
Location: ipc/util.h:273
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
```
</details>
</li>
</ul>

## Differences
