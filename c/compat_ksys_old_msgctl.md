# Function: <code>compat_ksys_old_msgctl</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_msgctl(int msqid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8141f2ba)
Location: ipc/msg.c:752
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8141fbd0-ffffffff8141fbee: compat_ksys_old_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_msgctl(int msqid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814390da)
Location: ipc/msg.c:753
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814399f0-ffffffff81439a0e: compat_ksys_old_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_msgctl(int msqid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8148919a)
Location: ipc/msg.c:772
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81489b40-ffffffff81489b5e: compat_ksys_old_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_msgctl(int msqid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814a67ba)
Location: ipc/msg.c:772
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814a7170-ffffffff814a718e: compat_ksys_old_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_msgctl(int msqid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814ac72a)
Location: ipc/msg.c:774
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814ad0b0-ffffffff814ad0ce: compat_ksys_old_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_msgctl(int msqid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81504c0a)
Location: ipc/msg.c:774
Inline: True
Inline callers:
  - ipc/msg.c:__x64_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff815055a0-ffffffff815055be: compat_ksys_old_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_msgctl(int msqid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81595d7a)
Location: ipc/msg.c:774
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81596f80-ffffffff81596faa: compat_ksys_old_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_msgctl(int msqid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8163ebba)
Location: ipc/msg.c:780
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8163ff10-ffffffff8163ff3a: compat_ksys_old_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_msgctl(int msqid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff816770da)
Location: ipc/msg.c:780
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81678430-ffffffff8167845a: compat_ksys_old_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_msgctl(int msqid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff816b349a)
Location: ipc/msg.c:780
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff816b47f0-ffffffff816b481a: compat_ksys_old_msgctl (STB_GLOBAL)
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffff800010520ac0)
Location: ipc/msg.c:753
Inline: True
Inline callers:
  - ipc/msg.c:__arm64_compat_sys_old_msgctl
```
**Symbols:**

```
ffff800010520ea0-ffff800010520ee8: compat_ksys_old_msgctl (STB_GLOBAL)
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c000000000669bd0)
Location: ipc/msg.c:753
Inline: True
Inline callers:
  - ipc/msg.c:__se_compat_sys_old_msgctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
c00000000066a4a0-c00000000066a4c4: compat_ksys_old_msgctl (STB_GLOBAL)
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814316ba)
Location: ipc/msg.c:753
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81431fd0-ffffffff81431fee: compat_ksys_old_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_msgctl(int msqid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8142213a)
Location: ipc/msg.c:753
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81422a50-ffffffff81422a6e: compat_ksys_old_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_msgctl(int msqid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8142d85a)
Location: ipc/msg.c:753
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8142e170-ffffffff8142e18e: compat_ksys_old_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_msgctl(int msqid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8144428a)
Location: ipc/msg.c:753
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814451b0-ffffffff814451ce: compat_ksys_old_msgctl (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
