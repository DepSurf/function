# Function: <code>compat_ksys_msgsnd</code>

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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813d84b6)
Location: ipc/msg.c:917
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
Direct callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813d91a0-ffffffff813d91dc: compat_ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813f3126)
Location: ipc/msg.c:927
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
Direct callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813f37e0-ffffffff813f381c: compat_ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8141ec89)
Location: ipc/msg.c:952
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8141fc30-ffffffff8141fc6a: compat_ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81438ad9)
Location: ipc/msg.c:953
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81439a50-ffffffff81439a8a: compat_ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81488ce8)
Location: ipc/msg.c:976
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81489ba0-ffffffff81489be1: compat_ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814a62d8)
Location: ipc/msg.c:976
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814a71d0-ffffffff814a7211: compat_ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814ac262)
Location: ipc/msg.c:978
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814ad110-ffffffff814ad14d: compat_ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff815047d2)
Location: ipc/msg.c:978
Inline: True
Inline callers:
  - ipc/msg.c:__x64_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81505600-ffffffff8150563d: compat_ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81596602)
Location: ipc/msg.c:978
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgsnd
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81597020-ffffffff81597087: compat_ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8163f4d2)
Location: ipc/msg.c:984
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgsnd
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8163ffd0-ffffffff81640037: compat_ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81677a02)
Location: ipc/msg.c:984
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgsnd
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff816784f0-ffffffff81678557: compat_ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff816b3dc2)
Location: ipc/msg.c:984
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgsnd
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff816b48b0-ffffffff816b4917: compat_ksys_msgsnd (STB_GLOBAL)
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffff8000105210a8)
Location: ipc/msg.c:953
Inline: False
Direct callers:
  - ipc/msg.c:__arm64_compat_sys_msgsnd
```
**Symbols:**

```
ffff8000105210a8-ffff800010521228: compat_ksys_msgsnd (STB_GLOBAL)
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c00000000066a5a0)
Location: ipc/msg.c:953
Inline: False
Direct callers:
  - ipc/msg.c:__se_compat_sys_msgsnd
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
c00000000066a5a0-c00000000066a658: compat_ksys_msgsnd (STB_GLOBAL)
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814310b9)
Location: ipc/msg.c:953
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81432030-ffffffff8143206a: compat_ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81421b39)
Location: ipc/msg.c:953
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81422ab0-ffffffff81422aea: compat_ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8142d259)
Location: ipc/msg.c:953
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8142e1d0-ffffffff8142e20a: compat_ksys_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81445109)
Location: ipc/msg.c:953
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81445210-ffffffff8144524a: compat_ksys_msgsnd (STB_GLOBAL)
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
