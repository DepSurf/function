# Function: <code>get_compat_ipc64_perm</code>

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
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff813a6890)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:C_SYSC_msgctl
  - ipc/sem.c:C_SYSC_semctl
  - ipc/shm.c:C_SYSC_shmctl
```
**Symbols:**

```
ffffffff813a6890-ffffffff813a68fa: get_compat_ipc64_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff813d5ba0)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff813d5ba0-ffffffff813d5c06: get_compat_ipc64_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff813f0200)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff813f0200-ffffffff813f0266: get_compat_ipc64_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8141c530)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8141c530-ffffffff8141c596: get_compat_ipc64_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81436380)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81436380-ffffffff814363e6: get_compat_ipc64_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81486120)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81486120-ffffffff81486185: get_compat_ipc64_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff814a3720)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814a3720-ffffffff814a3785: get_compat_ipc64_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff814a9710)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814a9710-ffffffff814a9775: get_compat_ipc64_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81501aa0)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81501aa0-ffffffff81501b05: get_compat_ipc64_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81592eb0)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81592eb0-ffffffff81592f46: get_compat_ipc64_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8163b960)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8163b960-ffffffff8163b9f6: get_compat_ipc64_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81673fa0)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81673fa0-ffffffff81674036: get_compat_ipc64_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff816b0360)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff816b0360-ffffffff816b03f6: get_compat_ipc64_perm (STB_GLOBAL)
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
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffff80001051c888)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffff80001051c888-ffff80001051c90c: get_compat_ipc64_perm (STB_GLOBAL)
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
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (c000000000665760)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
c000000000665760-c0000000006657f0: get_compat_ipc64_perm (STB_GLOBAL)
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
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8142e960)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8142e960-ffffffff8142e9c6: get_compat_ipc64_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8141f3e0)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8141f3e0-ffffffff8141f446: get_compat_ipc64_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8142ab00)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8142ab00-ffffffff8142ab66: get_compat_ipc64_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_compat_ipc64_perm(struct ipc64_perm *to, struct compat_ipc64_perm *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff814419c0)
Location: ipc/compat.c:38
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/sem.c:compat_ksys_semctl
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814419c0-ffffffff81441a26: get_compat_ipc64_perm (STB_GLOBAL)
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
