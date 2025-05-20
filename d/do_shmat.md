# Function: <code>do_shmat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8132b310)
Location: ipc/shm.c:1086
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_shmat
  - ipc/shm.c:SyS_shmat
```
**Symbols:**

```
ffffffff8132b310-ffffffff8132b7e0: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8135ff70)
Location: ipc/shm.c:1088
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_shmat
  - ipc/compat.c:compat_SyS_ipc
  - ipc/shm.c:SyS_shmat
```
**Symbols:**

```
ffffffff8135ff70-ffffffff8136044b: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81376770)
Location: ipc/shm.c:1094
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_shmat
  - ipc/compat.c:compat_SyS_ipc
  - ipc/shm.c:SyS_shmat
```
**Symbols:**

```
ffffffff81376770-ffffffff81376c69: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8138a350)
Location: ipc/shm.c:1092
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_shmat
  - ipc/compat.c:compat_SyS_ipc
  - ipc/shm.c:SyS_shmat
```
**Symbols:**

```
ffffffff8138a350-ffffffff8138a7f7: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813af4c0)
Location: ipc/shm.c:1282
Inline: False
Direct callers:
  - ipc/shm.c:compat_SyS_shmat
  - ipc/shm.c:SyS_shmat
  - ipc/syscall.c:compat_SyS_ipc
```
**Symbols:**

```
ffffffff813af4c0-ffffffff813af96c: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813df2c0)
Location: ipc/shm.c:1363
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
  - ipc/shm.c:__ia32_sys_shmat
  - ipc/shm.c:__x64_sys_shmat
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813df2c0-ffffffff813df7c8: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813f9a30)
Location: ipc/shm.c:1392
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
  - ipc/shm.c:__ia32_sys_shmat
  - ipc/shm.c:__x64_sys_shmat
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813f9a30-ffffffff813f9f00: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81426040)
Location: ipc/shm.c:1418
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
  - ipc/shm.c:__ia32_sys_shmat
  - ipc/shm.c:__x64_sys_shmat
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81426040-ffffffff814264e3: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8143fd90)
Location: ipc/shm.c:1418
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
  - ipc/shm.c:__ia32_sys_shmat
  - ipc/shm.c:__x64_sys_shmat
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8143fd90-ffffffff81440233: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81490b10)
Location: ipc/shm.c:1418
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
  - ipc/shm.c:__ia32_sys_shmat
  - ipc/shm.c:__x64_sys_shmat
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81490b10-ffffffff81490ffe: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814ae250)
Location: ipc/shm.c:1416
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
  - ipc/shm.c:__ia32_sys_shmat
  - ipc/shm.c:__x64_sys_shmat
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814ae250-ffffffff814ae7ed: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814b4080)
Location: ipc/shm.c:1416
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
  - ipc/shm.c:__ia32_sys_shmat
  - ipc/shm.c:__x64_sys_shmat
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814b4080-ffffffff814b460e: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:1512
Inline: False
Direct callers:
  - ipc/shm.c:__x64_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
  - ipc/shm.c:__ia32_sys_shmat
  - ipc/shm.c:__x64_sys_shmat
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81cd2cd1-ffffffff81cd2d10: do_shmat.cold (STB_LOCAL)
ffffffff8150c710-ffffffff8150ccba: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:1506
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_compat_sys_shmat
  - ipc/shm.c:__ia32_sys_shmat
  - ipc/shm.c:__x64_sys_shmat
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81e85ea2-ffffffff81e85ecc: do_shmat.cold (STB_LOCAL)
ffffffff8159e6a0-ffffffff8159ec0a: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:1522
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_compat_sys_shmat
  - ipc/shm.c:__ia32_sys_shmat
  - ipc/shm.c:__x64_sys_shmat
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff82073010-ffffffff8207303a: do_shmat.cold (STB_LOCAL)
ffffffff81647d60-ffffffff816482c1: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:1522
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_compat_sys_shmat
  - ipc/shm.c:__ia32_sys_shmat
  - ipc/shm.c:__x64_sys_shmat
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff820f2c5c-ffffffff820f2c86: do_shmat.cold (STB_LOCAL)
ffffffff81680270-ffffffff81680809: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:1518
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_compat_sys_shmat
  - ipc/shm.c:__ia32_sys_shmat
  - ipc/shm.c:__x64_sys_shmat
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff821cfef4-ffffffff821cff1e: do_shmat.cold (STB_LOCAL)
ffffffff816bc660-ffffffff816bcc2c: do_shmat (STB_GLOBAL)
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
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffff800010528530)
Location: ipc/shm.c:1418
Inline: False
Direct callers:
  - ipc/shm.c:__arm64_compat_sys_shmat
  - ipc/shm.c:__arm64_sys_shmat
```
**Symbols:**

```
ffff800010528530-ffff800010528994: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c06e1a2c)
Location: ipc/shm.c:1418
Inline: False
Direct callers:
  - ipc/shm.c:__se_sys_shmat
```
**Symbols:**

```
c06e1a2c-c06e1f04: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c000000000672f80)
Location: ipc/shm.c:1418
Inline: False
Direct callers:
  - ipc/shm.c:__se_compat_sys_shmat
  - ipc/shm.c:__se_sys_shmat
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:ksys_ipc
```
**Symbols:**

```
c000000000672f80-c0000000006735e0: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffe00038bc3c)
Location: ipc/shm.c:1418
Inline: False
Direct callers:
  - ipc/shm.c:__se_sys_shmat
```
**Symbols:**

```
ffffffe00038bc3c-ffffffe00038c072: do_shmat (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81438370)
Location: ipc/shm.c:1418
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
  - ipc/shm.c:__ia32_sys_shmat
  - ipc/shm.c:__x64_sys_shmat
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81438370-ffffffff81438813: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81428de0)
Location: ipc/shm.c:1418
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
  - ipc/shm.c:__ia32_sys_shmat
  - ipc/shm.c:__x64_sys_shmat
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81428de0-ffffffff81429283: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81434510)
Location: ipc/shm.c:1418
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
  - ipc/shm.c:__ia32_sys_shmat
  - ipc/shm.c:__x64_sys_shmat
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81434510-ffffffff814349b3: do_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_shmat(int shmid, char *shmaddr, int shmflg, ulong *raddr, long unsigned int shmlba);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8144b620)
Location: ipc/shm.c:1418
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_shmat
  - ipc/shm.c:__ia32_compat_sys_shmat
  - ipc/shm.c:__ia32_sys_shmat
  - ipc/shm.c:__x64_sys_shmat
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8144b620-ffffffff8144bafc: do_shmat (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
