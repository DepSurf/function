# Function: <code>ksys_msgsnd</code>

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
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813d8428)
Location: ipc/msg.c:894
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff813d9160-ffffffff813d9198: ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813f3098)
Location: ipc/msg.c:904
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff813f37a0-ffffffff813f37d8: ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8141ebf8)
Location: ipc/msg.c:929
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff8141fbf0-ffffffff8141fc28: ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81438a48)
Location: ipc/msg.c:930
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff81439a10-ffffffff81439a48: ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81488d88)
Location: ipc/msg.c:953
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff81489b60-ffffffff81489b98: ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814a63b8)
Location: ipc/msg.c:953
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff814a7190-ffffffff814a71c8: ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814ac347)
Location: ipc/msg.c:955
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff814ad0d0-ffffffff814ad10e: ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81504827)
Location: ipc/msg.c:955
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff815055c0-ffffffff815055fe: ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff815966e7)
Location: ipc/msg.c:955
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff81596fb0-ffffffff81597018: ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8163f5d7)
Location: ipc/msg.c:961
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff8163ff50-ffffffff8163ffb8: ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81677b07)
Location: ipc/msg.c:961
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff81678470-ffffffff816784d8: ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff816b3ec7)
Location: ipc/msg.c:961
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff816b4830-ffffffff816b4898: ksys_msgsnd (STB_GLOBAL)
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
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffff800010520ee8)
Location: ipc/msg.c:930
Inline: False
Direct callers:
  - ipc/msg.c:__arm64_sys_msgsnd
```
**Symbols:**

```
ffff800010520ee8-ffff800010521070: ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c06dc2a0)
Location: ipc/msg.c:930
Inline: False
Direct callers:
  - ipc/msg.c:__se_sys_msgsnd
```
**Symbols:**

```
c06dc2a0-c06dc32c: ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c00000000066a4d0)
Location: ipc/msg.c:930
Inline: False
Direct callers:
  - ipc/msg.c:__se_sys_msgsnd
  - ipc/syscall.c:ksys_ipc
```
**Symbols:**

```
c00000000066a4d0-c00000000066a578: ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffe000386e96)
Location: ipc/msg.c:930
Inline: False
Direct callers:
  - ipc/msg.c:__se_sys_msgsnd
```
**Symbols:**

```
ffffffe000386e96-ffffffe000386f0e: ksys_msgsnd (STB_GLOBAL)
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
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81431028)
Location: ipc/msg.c:930
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff81431ff0-ffffffff81432028: ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81421aa8)
Location: ipc/msg.c:930
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff81422a70-ffffffff81422aa8: ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8142d1c8)
Location: ipc/msg.c:930
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff8142e190-ffffffff8142e1c8: ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf *msgp, size_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81445078)
Location: ipc/msg.c:930
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_sys_msgsnd
  - ipc/msg.c:__x64_sys_msgsnd
```
**Symbols:**

```
ffffffff814451d0-ffffffff81445208: ksys_msgsnd (STB_GLOBAL)
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
