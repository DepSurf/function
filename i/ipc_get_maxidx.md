# Function: <code>ipc_get_maxidx</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813f205a)
Location: ipc/util.h:121
Inline: True
```
```
In ipc/sem.c (ffffffff813f3b79)
Location: ipc/util.h:121
Inline: True
```
```
In ipc/shm.c (ffffffff813f811c)
Location: ipc/util.h:121
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
In ipc/msg.c (ffffffff8141e34a)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/sem.c (ffffffff8141ffca)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/shm.c (ffffffff81424627)
Location: ipc/util.h:150
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
In ipc/msg.c (ffffffff8143819a)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/sem.c (ffffffff81439dca)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/shm.c (ffffffff8143e377)
Location: ipc/util.h:150
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
In ipc/msg.c (ffffffff814880f3)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/sem.c (ffffffff81489f3f)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/shm.c (ffffffff8148ef51)
Location: ipc/util.h:150
Inline: True
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
In ipc/msg.c (ffffffff814a5713)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/sem.c (ffffffff814a755e)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/shm.c (ffffffff814ac621)
Location: ipc/util.h:150
Inline: True
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
In ipc/msg.c (ffffffff814ab6d4)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/sem.c (ffffffff814ad49e)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/shm.c (ffffffff814b24c1)
Location: ipc/util.h:150
Inline: True
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
In ipc/util.c (ffffffff81501e55)
Location: ipc/util.h:153
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_find_ipc
```
```
In ipc/msg.c (ffffffff81503b94)
Location: ipc/util.h:153
Inline: True
```
```
In ipc/sem.c (ffffffff8150595e)
Location: ipc/util.h:153
Inline: True
```
```
In ipc/shm.c (ffffffff8150aa61)
Location: ipc/util.h:153
Inline: True
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
In ipc/util.c (ffffffff815932c5)
Location: ipc/util.h:153
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_find_ipc
```
```
In ipc/msg.c (ffffffff81595514)
Location: ipc/util.h:153
Inline: True
```
```
In ipc/sem.c (ffffffff8159749e)
Location: ipc/util.h:153
Inline: True
```
```
In ipc/shm.c (ffffffff8159cc63)
Location: ipc/util.h:153
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_shm_info
  - ipc/shm.c:shmctl_ipc_info
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
In ipc/msg.c (ffffffff8163e446)
Location: ipc/util.h:153
Inline: True
```
```
In ipc/sem.c (ffffffff8164057e)
Location: ipc/util.h:153
Inline: True
```
```
In ipc/shm.c (ffffffff81646123)
Location: ipc/util.h:153
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_shm_info
  - ipc/shm.c:shmctl_ipc_info
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
In ipc/msg.c (ffffffff816769a6)
Location: ipc/util.h:151
Inline: True
```
```
In ipc/sem.c (ffffffff81678ace)
Location: ipc/util.h:151
Inline: True
```
```
In ipc/shm.c (ffffffff8167e633)
Location: ipc/util.h:151
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_shm_info
  - ipc/shm.c:shmctl_ipc_info
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
In ipc/msg.c (ffffffff816b2d66)
Location: ipc/util.h:152
Inline: True
```
```
In ipc/sem.c (ffffffff816b4ebe)
Location: ipc/util.h:152
Inline: True
```
```
In ipc/shm.c (ffffffff816baa23)
Location: ipc/util.h:152
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_shm_info
  - ipc/shm.c:shmctl_ipc_info
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
In ipc/msg.c (ffff80001051ebc4)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/sem.c (ffff8000105220a0)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/shm.c (ffff800010526850)
Location: ipc/util.h:150
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
In ipc/msg.c (c06dc00c)
Location: ipc/util.h:150
Inline: True
Inline callers:
  - ipc/msg.c:ksys_msgctl
```
```
In ipc/sem.c (c06dd078)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/shm.c (c06e0f78)
Location: ipc/util.h:150
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
In ipc/msg.c (c0000000006682e0)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/sem.c (c00000000066add8)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/shm.c (c000000000670d64)
Location: ipc/util.h:150
Inline: True
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
In ipc/msg.c (ffffffe0003867f2)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/sem.c (ffffffe000387870)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/shm.c (ffffffe00038b840)
Location: ipc/util.h:150
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
In ipc/msg.c (ffffffff8143077a)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/sem.c (ffffffff814323aa)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/shm.c (ffffffff81436957)
Location: ipc/util.h:150
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
In ipc/msg.c (ffffffff814211fa)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/sem.c (ffffffff81422e2a)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/shm.c (ffffffff814273d7)
Location: ipc/util.h:150
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
In ipc/msg.c (ffffffff8142c91a)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/sem.c (ffffffff8142e54a)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/shm.c (ffffffff81432af7)
Location: ipc/util.h:150
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
In ipc/msg.c (ffffffff81443c6a)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/sem.c (ffffffff814458aa)
Location: ipc/util.h:150
Inline: True
```
```
In ipc/shm.c (ffffffff81449d77)
Location: ipc/util.h:150
Inline: True
```
</details>
</li>
</ul>

## Differences
