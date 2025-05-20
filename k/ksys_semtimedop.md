# Function: <code>ksys_semtimedop</code>

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
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813dce60)
Location: ipc/sem.c:2189
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813dce60-ffffffff813dcee2: ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813f74c0)
Location: ipc/sem.c:2196
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813f74c0-ffffffff813f7542: ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct __kernel_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814239c0)
Location: ipc/sem.c:2218
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814239c0-ffffffff81423a48: ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct __kernel_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8143d700)
Location: ipc/sem.c:2219
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8143d700-ffffffff8143d788: ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct __kernel_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8148d73a)
Location: ipc/sem.c:2235
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8148e2a0-ffffffff8148e328: ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct __kernel_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814aaeea)
Location: ipc/sem.c:2234
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814ab9e0-ffffffff814aba68: ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct __kernel_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814b172d)
Location: ipc/sem.c:2236
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814b1870-ffffffff814b18f8: ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct __kernel_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81509dfd)
Location: ipc/sem.c:2260
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81509e20-ffffffff81509ea8: ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct __kernel_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8159ba83)
Location: ipc/sem.c:2257
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8159bb50-ffffffff8159bbee: ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct __kernel_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81644ef3)
Location: ipc/sem.c:2258
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81644f20-ffffffff81644fbe: ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct __kernel_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8167d323)
Location: ipc/sem.c:2258
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8167d410-ffffffff8167d4ae: ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct __kernel_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816b96f3)
Location: ipc/sem.c:2256
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff816b97e0-ffffffff816b987e: ksys_semtimedop (STB_GLOBAL)
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
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct __kernel_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff800010525548)
Location: ipc/sem.c:2219
Inline: True
Direct callers:
  - ipc/sem.c:__arm64_sys_semtimedop
```
**Symbols:**

```
ffff800010525548-ffff8000105255fc: ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct __kernel_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c06dfa5c)
Location: ipc/sem.c:2219
Inline: True
Direct callers:
  - ipc/sem.c:__se_sys_semtimedop
```
**Symbols:**

```
c06dfa5c-c06dfaf8: ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct __kernel_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066f920)
Location: ipc/sem.c:2219
Inline: True
Direct callers:
  - ipc/sem.c:__se_sys_semtimedop
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:ksys_ipc
  - ipc/syscall.c:ksys_ipc
```
**Symbols:**

```
c00000000066f920-c00000000066fa10: ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct __kernel_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffe000389f86)
Location: ipc/sem.c:2219
Inline: True
Direct callers:
  - ipc/sem.c:__se_sys_semtimedop
```
**Symbols:**

```
ffffffe000389f86-ffffffe00038a010: ksys_semtimedop (STB_GLOBAL)
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
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct __kernel_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81435ce0)
Location: ipc/sem.c:2219
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81435ce0-ffffffff81435d68: ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct __kernel_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81426760)
Location: ipc/sem.c:2219
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81426760-ffffffff814267e8: ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct __kernel_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81431e80)
Location: ipc/sem.c:2219
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81431e80-ffffffff81431f08: ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct __kernel_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81448f50)
Location: ipc/sem.c:2219
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81448f50-ffffffff81448fd8: ksys_semtimedop (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct timespec *timeout</code> ➡️ <code>const struct __kernel_timespec *timeout</code>
</li>
</ul>
</details>
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
