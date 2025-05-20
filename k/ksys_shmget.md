# Function: <code>ksys_shmget</code>

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
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813dd8b3)
Location: ipc/shm.c:706
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
Direct callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813ded80-ffffffff813dedec: ksys_shmget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813f7f33)
Location: ipc/shm.c:726
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
Direct callers:
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813f9480-ffffffff813f94ec: ksys_shmget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81424420)
Location: ipc/shm.c:726
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81425bf0-ffffffff81425c5d: ksys_shmget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8143e170)
Location: ipc/shm.c:726
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8143f940-ffffffff8143f9ad: ksys_shmget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8148f04e)
Location: ipc/shm.c:726
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81490a80-ffffffff81490aed: ksys_shmget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814ac71e)
Location: ipc/shm.c:725
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814ae1c0-ffffffff814ae22d: ksys_shmget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814b25be)
Location: ipc/shm.c:725
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814b3ff0-ffffffff814b405d: ksys_shmget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8150ab5e)
Location: ipc/shm.c:821
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8150c680-ffffffff8150c6ed: ksys_shmget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8159d2f4)
Location: ipc/shm.c:815
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8159e5f0-ffffffff8159e667: ksys_shmget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81646804)
Location: ipc/shm.c:831
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81647c90-ffffffff81647d07: ksys_shmget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8167ed24)
Location: ipc/shm.c:831
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff816801a0-ffffffff81680217: ksys_shmget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff816bb114)
Location: ipc/shm.c:827
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff816bc590-ffffffff816bc607: ksys_shmget (STB_GLOBAL)
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
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffff800010526478)
Location: ipc/shm.c:726
Inline: True
Inline callers:
  - ipc/shm.c:__arm64_sys_shmget
```
**Symbols:**

```
ffff8000105280a0-ffff800010528128: ksys_shmget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c06e1900)
Location: ipc/shm.c:726
Inline: False
Direct callers:
  - ipc/shm.c:__se_sys_shmget
```
**Symbols:**

```
c06e1900-c06e198c: ksys_shmget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c000000000670aec)
Location: ipc/shm.c:726
Inline: True
Inline callers:
  - ipc/shm.c:__se_sys_shmget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:ksys_ipc
```
**Symbols:**

```
c000000000672a80-c000000000672b08: ksys_shmget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffe00038bbc6)
Location: ipc/shm.c:726
Inline: True
Inline callers:
  - ipc/shm.c:__se_sys_shmget
```
**Symbols:**

```
ffffffe00038bb52-ffffffe00038bba8: ksys_shmget (STB_GLOBAL)
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
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81436750)
Location: ipc/shm.c:726
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81437f20-ffffffff81437f8d: ksys_shmget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814271d0)
Location: ipc/shm.c:726
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81428990-ffffffff814289fd: ksys_shmget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814328f0)
Location: ipc/shm.c:726
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814340c0-ffffffff8143412d: ksys_shmget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814499c0)
Location: ipc/shm.c:726
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8144b1d0-ffffffff8144b23d: ksys_shmget (STB_GLOBAL)
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
