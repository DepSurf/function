# Function: <code>compat_ksys_old_shmctl</code>

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
long int compat_ksys_old_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81425ffa)
Location: ipc/shm.c:1397
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81426020-ffffffff8142603e: compat_ksys_old_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8143fd4a)
Location: ipc/shm.c:1397
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8143fd70-ffffffff8143fd8e: compat_ksys_old_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814903ba)
Location: ipc/shm.c:1397
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81490af0-ffffffff81490b0e: compat_ksys_old_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814adada)
Location: ipc/shm.c:1395
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814ae230-ffffffff814ae24e: compat_ksys_old_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814b392a)
Location: ipc/shm.c:1395
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814b4060-ffffffff814b407e: compat_ksys_old_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8150bf9a)
Location: ipc/shm.c:1491
Inline: True
Inline callers:
  - ipc/shm.c:__x64_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8150c6f0-ffffffff8150c70e: compat_ksys_old_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8159e08a)
Location: ipc/shm.c:1485
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8159e670-ffffffff8159e69a: compat_ksys_old_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8164769a)
Location: ipc/shm.c:1501
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81647d20-ffffffff81647d4a: compat_ksys_old_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8167fbca)
Location: ipc/shm.c:1501
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81680230-ffffffff8168025a: compat_ksys_old_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff816bbfba)
Location: ipc/shm.c:1497
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff816bc620-ffffffff816bc64a: compat_ksys_old_shmctl (STB_GLOBAL)
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffff8000105284c8)
Location: ipc/shm.c:1397
Inline: True
Inline callers:
  - ipc/shm.c:__arm64_compat_sys_old_shmctl
```
**Symbols:**

```
ffff8000105284e8-ffff800010528530: compat_ksys_old_shmctl (STB_GLOBAL)
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c000000000672f30)
Location: ipc/shm.c:1397
Inline: True
Inline callers:
  - ipc/shm.c:__se_compat_sys_old_shmctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
c000000000672f50-c000000000672f74: compat_ksys_old_shmctl (STB_GLOBAL)
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8143832a)
Location: ipc/shm.c:1397
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81438350-ffffffff8143836e: compat_ksys_old_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81428d9a)
Location: ipc/shm.c:1397
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81428dc0-ffffffff81428dde: compat_ksys_old_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814344ca)
Location: ipc/shm.c:1397
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814344f0-ffffffff8143450e: compat_ksys_old_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8144b5da)
Location: ipc/shm.c:1397
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8144b600-ffffffff8144b61e: compat_ksys_old_shmctl (STB_GLOBAL)
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
