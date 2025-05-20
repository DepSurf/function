# Function: <code>compat_ksys_msgrcv</code>

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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813d8d15)
Location: ipc/msg.c:1216
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
Direct callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813d9200-ffffffff813d921f: compat_ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813f2b95)
Location: ipc/msg.c:1226
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
Direct callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813f3840-ffffffff813f385f: compat_ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8141fb35)
Location: ipc/msg.c:1251
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8141fc90-ffffffff8141fcaf: compat_ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81439955)
Location: ipc/msg.c:1252
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81439ab0-ffffffff81439acf: compat_ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81489aa5)
Location: ipc/msg.c:1283
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81489c10-ffffffff81489c2f: compat_ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814a70d5)
Location: ipc/msg.c:1283
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814a7240-ffffffff814a725f: compat_ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814ad015)
Location: ipc/msg.c:1285
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814ad170-ffffffff814ad18f: compat_ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81505505)
Location: ipc/msg.c:1285
Inline: True
Inline callers:
  - ipc/msg.c:__x64_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81505660-ffffffff8150567f: compat_ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81596ec5)
Location: ipc/msg.c:1285
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgrcv
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff815970c0-ffffffff815970f1: compat_ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8163fe35)
Location: ipc/msg.c:1291
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgrcv
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81640090-ffffffff816400c1: compat_ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81678355)
Location: ipc/msg.c:1291
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgrcv
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff816785b0-ffffffff816785e1: compat_ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff816b4715)
Location: ipc/msg.c:1291
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgrcv
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff816b4970-ffffffff816b49a1: compat_ksys_msgrcv (STB_GLOBAL)
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffff80001051fdd0)
Location: ipc/msg.c:1252
Inline: True
Inline callers:
  - ipc/msg.c:__arm64_compat_sys_msgrcv
```
**Symbols:**

```
ffff8000105212c8-ffff80001052132c: compat_ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c00000000066a380)
Location: ipc/msg.c:1252
Inline: True
Inline callers:
  - ipc/msg.c:__se_compat_sys_msgrcv
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
c00000000066a6b0-c00000000066a6cc: compat_ksys_msgrcv (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81431f35)
Location: ipc/msg.c:1252
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81432090-ffffffff814320af: compat_ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814229b5)
Location: ipc/msg.c:1252
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81422b10-ffffffff81422b2f: compat_ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8142e0d5)
Location: ipc/msg.c:1252
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8142e230-ffffffff8142e24f: compat_ksys_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81444b25)
Location: ipc/msg.c:1252
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81445270-ffffffff8144528f: compat_ksys_msgrcv (STB_GLOBAL)
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
