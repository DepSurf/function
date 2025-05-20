# Function: <code>compat_ksys_semtimedop</code>

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
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct compat_timespec *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813dcf30)
Location: ipc/sem.c:2208
Inline: True
Direct callers:
  - ipc/sem.c:__x32_compat_sys_semtimedop
  - ipc/sem.c:__ia32_compat_sys_semtimedop
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813dcf30-ffffffff813dcfb2: compat_ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct old_timespec32 *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813f7590)
Location: ipc/sem.c:2215
Inline: True
Direct callers:
  - ipc/sem.c:__x32_compat_sys_semtimedop
  - ipc/sem.c:__ia32_compat_sys_semtimedop
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813f7590-ffffffff813f7612: compat_ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct old_timespec32 *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81423a90)
Location: ipc/sem.c:2237
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81423a90-ffffffff81423b18: compat_ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct old_timespec32 *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8143d7d0)
Location: ipc/sem.c:2238
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8143d7d0-ffffffff8143d858: compat_ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct old_timespec32 *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8148d6f0)
Location: ipc/sem.c:2254
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8148e330-ffffffff8148e3b8: compat_ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct old_timespec32 *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814aaea0)
Location: ipc/sem.c:2253
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814aba70-ffffffff814abaf8: compat_ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct old_timespec32 *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814b16e1)
Location: ipc/sem.c:2255
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814b1900-ffffffff814b1988: compat_ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct old_timespec32 *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81509db1)
Location: ipc/sem.c:2279
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81509eb0-ffffffff81509f38: compat_ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct old_timespec32 *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8159ba1f)
Location: ipc/sem.c:2276
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8159bbf0-ffffffff8159bc8e: compat_ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct old_timespec32 *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81644e8f)
Location: ipc/sem.c:2277
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81644fd0-ffffffff8164506e: compat_ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct old_timespec32 *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8167d2bf)
Location: ipc/sem.c:2277
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8167d4c0-ffffffff8167d55e: compat_ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct old_timespec32 *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816b968f)
Location: ipc/sem.c:2275
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff816b9890-ffffffff816b992e: compat_ksys_semtimedop (STB_GLOBAL)
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
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct old_timespec32 *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff800010525638)
Location: ipc/sem.c:2238
Inline: True
Direct callers:
  - ipc/sem.c:__arm64_sys_semtimedop_time32
```
**Symbols:**

```
ffff800010525638-ffff8000105256ec: compat_ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct old_timespec32 *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c06dfb14)
Location: ipc/sem.c:2238
Inline: True
Direct callers:
  - ipc/sem.c:__se_sys_semtimedop_time32
```
**Symbols:**

```
c06dfb14-c06dfbb0: compat_ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct old_timespec32 *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066fa30)
Location: ipc/sem.c:2238
Inline: True
Direct callers:
  - ipc/sem.c:__se_sys_semtimedop_time32
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
c00000000066fa30-c00000000066fb20: compat_ksys_semtimedop (STB_GLOBAL)
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
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct old_timespec32 *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81435db0)
Location: ipc/sem.c:2238
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81435db0-ffffffff81435e38: compat_ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct old_timespec32 *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81426830)
Location: ipc/sem.c:2238
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81426830-ffffffff814268b8: compat_ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct old_timespec32 *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81431f50)
Location: ipc/sem.c:2238
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81431f50-ffffffff81431fd8: compat_ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf *tsems, unsigned int nsops, const struct old_timespec32 *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81449020)
Location: ipc/sem.c:2238
Inline: True
Direct callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81449020-ffffffff814490a8: compat_ksys_semtimedop (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct compat_timespec *timeout</code> ➡️ <code>const struct old_timespec32 *timeout</code>
</li>
</ul>
</details>
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
