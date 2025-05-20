# Function: <code>ksys_msgrcv</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813d8cb5)
Location: ipc/msg.c:1189
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff813d91e0-ffffffff813d91f7: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813f2b35)
Location: ipc/msg.c:1199
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff813f3820-ffffffff813f3837: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8141fad5)
Location: ipc/msg.c:1224
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff8141fc70-ffffffff8141fc87: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814398f5)
Location: ipc/msg.c:1225
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff81439a90-ffffffff81439aa7: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81489a45)
Location: ipc/msg.c:1256
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff81489bf0-ffffffff81489c07: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814a7075)
Location: ipc/msg.c:1256
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff814a7220-ffffffff814a7237: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814acfb5)
Location: ipc/msg.c:1258
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff814ad150-ffffffff814ad167: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff815054a5)
Location: ipc/msg.c:1258
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff81505640-ffffffff81505657: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81596e85)
Location: ipc/msg.c:1258
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff81597090-ffffffff815970b9: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8163fde5)
Location: ipc/msg.c:1264
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff81640050-ffffffff81640079: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81678305)
Location: ipc/msg.c:1264
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff81678570-ffffffff81678599: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff816b46c5)
Location: ipc/msg.c:1264
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff816b4930-ffffffff816b4959: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffff80001051fd90)
Location: ipc/msg.c:1225
Inline: True
Inline callers:
  - ipc/msg.c:__arm64_sys_msgrcv
```
**Symbols:**

```
ffff800010521260-ffff8000105212c4: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c06dc38c)
Location: ipc/msg.c:1225
Inline: True
Inline callers:
  - ipc/msg.c:__se_sys_msgrcv
```
**Symbols:**

```
c06dc348-c06dc374: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c00000000066a350)
Location: ipc/msg.c:1225
Inline: True
Inline callers:
  - ipc/msg.c:__se_sys_msgrcv
Direct callers:
  - ipc/syscall.c:ksys_ipc
  - ipc/syscall.c:ksys_ipc
```
**Symbols:**

```
c00000000066a690-c00000000066a6ac: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffe000386fc4)
Location: ipc/msg.c:1225
Inline: True
Inline callers:
  - ipc/msg.c:__se_sys_msgrcv
```
**Symbols:**

```
ffffffe000386f54-ffffffe000386f9e: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81431ed5)
Location: ipc/msg.c:1225
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff81432070-ffffffff81432087: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81422955)
Location: ipc/msg.c:1225
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff81422af0-ffffffff81422b07: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8142e075)
Location: ipc/msg.c:1225
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff8142e210-ffffffff8142e227: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf *msgp, size_t msgsz, long int msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81444ac5)
Location: ipc/msg.c:1225
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff81445250-ffffffff81445267: ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
