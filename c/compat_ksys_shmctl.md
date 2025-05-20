# Function: <code>compat_ksys_shmctl</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
long int compat_ksys_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813defb0)
Location: ipc/shm.c:1293
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_shmctl
  - ipc/shm.c:__ia32_compat_sys_shmctl
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813defb0-ffffffff813df27a: compat_ksys_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int compat_ksys_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813f96e0)
Location: ipc/shm.c:1322
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_shmctl
  - ipc/shm.c:__ia32_compat_sys_shmctl
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813f96e0-ffffffff813f99e4: compat_ksys_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int compat_ksys_shmctl(int shmid, int cmd, void *uptr, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81425c60)
Location: ipc/shm.c:1335
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
  - ipc/shm.c:__x32_compat_sys_shmctl
  - ipc/shm.c:__ia32_compat_sys_shmctl
```
**Symbols:**

```
ffffffff81425c60-ffffffff81425f6d: compat_ksys_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int compat_ksys_shmctl(int shmid, int cmd, void *uptr, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8143f9b0)
Location: ipc/shm.c:1335
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
  - ipc/shm.c:__x32_compat_sys_shmctl
  - ipc/shm.c:__ia32_compat_sys_shmctl
```
**Symbols:**

```
ffffffff8143f9b0-ffffffff8143fcbd: compat_ksys_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int compat_ksys_shmctl(int shmid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81490000)
Location: ipc/shm.c:1335
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
  - ipc/shm.c:__x32_compat_sys_shmctl
  - ipc/shm.c:__ia32_compat_sys_shmctl
```
**Symbols:**

```
ffffffff81490000-ffffffff8149032f: compat_ksys_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int compat_ksys_shmctl(int shmid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814ad720)
Location: ipc/shm.c:1334
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
  - ipc/shm.c:__x32_compat_sys_shmctl
  - ipc/shm.c:__ia32_compat_sys_shmctl
```
**Symbols:**

```
ffffffff814ad720-ffffffff814ada4f: compat_ksys_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int compat_ksys_shmctl(int shmid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814b35a0)
Location: ipc/shm.c:1334
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
  - ipc/shm.c:__x32_compat_sys_shmctl
  - ipc/shm.c:__ia32_compat_sys_shmctl
```
**Symbols:**

```
ffffffff814b35a0-ffffffff814b38ab: compat_ksys_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int compat_ksys_shmctl(int shmid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8150bc10)
Location: ipc/shm.c:1430
Inline: False
Direct callers:
  - ipc/shm.c:__x64_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
  - ipc/shm.c:__x64_compat_sys_shmctl
  - ipc/shm.c:__ia32_compat_sys_shmctl
```
**Symbols:**

```
ffffffff8150bc10-ffffffff8150bf1b: compat_ksys_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int compat_ksys_shmctl(int shmid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8159dd30)
Location: ipc/shm.c:1424
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_shmctl
```
**Symbols:**

```
ffffffff8159dd30-ffffffff8159e04b: compat_ksys_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int compat_ksys_shmctl(int shmid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81647320)
Location: ipc/shm.c:1440
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_shmctl
```
**Symbols:**

```
ffffffff81647320-ffffffff8164763b: compat_ksys_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int compat_ksys_shmctl(int shmid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8167f860)
Location: ipc/shm.c:1440
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_shmctl
```
**Symbols:**

```
ffffffff8167f860-ffffffff8167fb68: compat_ksys_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int compat_ksys_shmctl(int shmid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff816bbc50)
Location: ipc/shm.c:1436
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_shmctl
```
**Symbols:**

```
ffffffff816bbc50-ffffffff816bbf58: compat_ksys_shmctl (STB_LOCAL)
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
long int compat_ksys_shmctl(int shmid, int cmd, void *uptr, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffff800010528128)
Location: ipc/shm.c:1335
Inline: False
Direct callers:
  - ipc/shm.c:__arm64_compat_sys_old_shmctl
  - ipc/shm.c:__arm64_compat_sys_shmctl
```
**Symbols:**

```
ffff800010528128-ffff800010528474: compat_ksys_shmctl (STB_GLOBAL)
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
long int compat_ksys_shmctl(int shmid, int cmd, void *uptr, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c000000000672b90)
Location: ipc/shm.c:1335
Inline: False
Direct callers:
  - ipc/shm.c:__se_compat_sys_old_shmctl
  - ipc/shm.c:__se_compat_sys_shmctl
```
**Symbols:**

```
c000000000672b90-c000000000672ef8: compat_ksys_shmctl (STB_GLOBAL)
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
long int compat_ksys_shmctl(int shmid, int cmd, void *uptr, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81437f90)
Location: ipc/shm.c:1335
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
  - ipc/shm.c:__x32_compat_sys_shmctl
  - ipc/shm.c:__ia32_compat_sys_shmctl
```
**Symbols:**

```
ffffffff81437f90-ffffffff8143829d: compat_ksys_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int compat_ksys_shmctl(int shmid, int cmd, void *uptr, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81428a00)
Location: ipc/shm.c:1335
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
  - ipc/shm.c:__x32_compat_sys_shmctl
  - ipc/shm.c:__ia32_compat_sys_shmctl
```
**Symbols:**

```
ffffffff81428a00-ffffffff81428d0d: compat_ksys_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int compat_ksys_shmctl(int shmid, int cmd, void *uptr, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81434130)
Location: ipc/shm.c:1335
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
  - ipc/shm.c:__x32_compat_sys_shmctl
  - ipc/shm.c:__ia32_compat_sys_shmctl
```
**Symbols:**

```
ffffffff81434130-ffffffff8143443d: compat_ksys_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int compat_ksys_shmctl(int shmid, int cmd, void *uptr, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8144b240)
Location: ipc/shm.c:1335
Inline: False
Direct callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
  - ipc/shm.c:__x32_compat_sys_shmctl
  - ipc/shm.c:__ia32_compat_sys_shmctl
```
**Symbols:**

```
ffffffff8144b240-ffffffff8144b54d: compat_ksys_shmctl (STB_GLOBAL)
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
<b>Param added. </b>
<code>int version</code>
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
