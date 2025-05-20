# Function: <code>to_compat_ipc_perm</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff813a69b0)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
ffffffff813a69b0-ffffffff813a6a2a: to_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff813d5cc0)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
ffffffff813d5cc0-ffffffff813d5d3a: to_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff813f0320)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
ffffffff813f0320-ffffffff813f039a: to_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8141c650)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
ffffffff8141c650-ffffffff8141c6ca: to_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff814364a0)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
ffffffff814364a0-ffffffff8143651a: to_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81486240)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
ffffffff81486240-ffffffff814862ba: to_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff814a3840)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
ffffffff814a3840-ffffffff814a38ba: to_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff814a9830)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
ffffffff814a9830-ffffffff814a98b1: to_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81501bc0)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
ffffffff81501bc0-ffffffff81501c41: to_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81593020)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
ffffffff81593020-ffffffff815930ab: to_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8163bb00)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
ffffffff8163bb00-ffffffff8163bb8b: to_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81674140)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
ffffffff81674140-ffffffff816741cb: to_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff816b0500)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
ffffffff816b0500-ffffffff816b058b: to_compat_ipc_perm (STB_GLOBAL)
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
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffff80001051c9f8)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
ffff80001051c9f8-ffff80001051caa8: to_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (c0000000006658d0)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
c0000000006658d0-c000000000665914: to_compat_ipc_perm (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8142ea80)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
ffffffff8142ea80-ffffffff8142eafa: to_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8141f500)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
ffffffff8141f500-ffffffff8141f57a: to_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8142ac20)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
ffffffff8142ac20-ffffffff8142ac9a: to_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void to_compat_ipc_perm(struct compat_ipc_perm *to, struct ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81441ae0)
Location: ipc/compat.c:73
Inline: False
Direct callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
**Symbols:**

```
ffffffff81441ae0-ffffffff81441b5a: to_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
