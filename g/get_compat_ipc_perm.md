# Function: <code>get_compat_ipc_perm</code>

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
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff813a6900)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:C_SYSC_msgctl
  - ipc/sem.c:C_SYSC_semctl
  - ipc/shm.c:C_SYSC_shmctl
```
**Symbols:**

```
ffffffff813a6900-ffffffff813a696c: get_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff813d5c10)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff813d5c10-ffffffff813d5c7c: get_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff813f0270)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff813f0270-ffffffff813f02dc: get_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8141c5a0)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8141c5a0-ffffffff8141c60c: get_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff814363f0)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814363f0-ffffffff8143645c: get_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81486190)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81486190-ffffffff814861fb: get_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff814a3790)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814a3790-ffffffff814a37fb: get_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff814a9780)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814a9780-ffffffff814a97eb: get_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81501b10)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81501b10-ffffffff81501b7b: get_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81592f50)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81592f50-ffffffff81592fd5: get_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8163ba10)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8163ba10-ffffffff8163ba95: get_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81674050)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81674050-ffffffff816740d5: get_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff816b0410)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff816b0410-ffffffff816b0495: get_compat_ipc_perm (STB_GLOBAL)
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
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffff80001051c910)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffff80001051c910-ffff80001051c998: get_compat_ipc_perm (STB_GLOBAL)
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
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (c0000000006657f0)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
c0000000006657f0-c000000000665880: get_compat_ipc_perm (STB_GLOBAL)
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
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8142e9d0)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8142e9d0-ffffffff8142ea3c: get_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8141f450)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8141f450-ffffffff8141f4bc: get_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8142ab70)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8142ab70-ffffffff8142abdc: get_compat_ipc_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_compat_ipc_perm(struct ipc64_perm *to, struct compat_ipc_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81441a30)
Location: ipc/compat.c:50
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81441a30-ffffffff81441a9c: get_compat_ipc_perm (STB_GLOBAL)
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
