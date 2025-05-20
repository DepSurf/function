# Function: <code>ksys_shmdt</code>

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
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813df950)
Location: ipc/shm.c:1574
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_sys_shmdt
  - ipc/shm.c:__x64_sys_shmdt
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813df950-ffffffff813dfad9: ksys_shmdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813fa080)
Location: ipc/shm.c:1600
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_sys_shmdt
  - ipc/shm.c:__x64_sys_shmdt
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813fa080-ffffffff813fa209: ksys_shmdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81426670)
Location: ipc/shm.c:1626
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_sys_shmdt
  - ipc/shm.c:__x64_sys_shmdt
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81426670-ffffffff814267d9: ksys_shmdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814403c0)
Location: ipc/shm.c:1626
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_sys_shmdt
  - ipc/shm.c:__x64_sys_shmdt
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814403c0-ffffffff81440529: ksys_shmdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81491180)
Location: ipc/shm.c:1626
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_sys_shmdt
  - ipc/shm.c:__x64_sys_shmdt
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81491180-ffffffff814912e9: ksys_shmdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814ae970)
Location: ipc/shm.c:1624
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_sys_shmdt
  - ipc/shm.c:__x64_sys_shmdt
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814ae970-ffffffff814aeb27: ksys_shmdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814b4790)
Location: ipc/shm.c:1624
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_sys_shmdt
  - ipc/shm.c:__x64_sys_shmdt
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814b4790-ffffffff814b4944: ksys_shmdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8150ce40)
Location: ipc/shm.c:1721
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_sys_shmdt
  - ipc/shm.c:__x64_sys_shmdt
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8150ce40-ffffffff8150cff1: ksys_shmdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8159ed60)
Location: ipc/shm.c:1715
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_sys_shmdt
  - ipc/shm.c:__x64_sys_shmdt
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8159ed60-ffffffff8159ef22: ksys_shmdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81648460)
Location: ipc/shm.c:1731
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_sys_shmdt
  - ipc/shm.c:__x64_sys_shmdt
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81648460-ffffffff81648665: ksys_shmdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff816809a0)
Location: ipc/shm.c:1731
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_sys_shmdt
  - ipc/shm.c:__x64_sys_shmdt
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff816809a0-ffffffff81680bd6: ksys_shmdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff816bcdc0)
Location: ipc/shm.c:1727
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_sys_shmdt
  - ipc/shm.c:__x64_sys_shmdt
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff816bcdc0-ffffffff816bcff5: ksys_shmdt (STB_GLOBAL)
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
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffff800010528a78)
Location: ipc/shm.c:1626
Inline: False
Direct callers:
  - ipc/shm.c:__arm64_sys_shmdt
```
**Symbols:**

```
ffff800010528a78-ffff800010528be0: ksys_shmdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c06e1f6c)
Location: ipc/shm.c:1626
Inline: False
Direct callers:
  - ipc/shm.c:__se_sys_shmdt
```
**Symbols:**

```
c06e1f6c-c06e2160: ksys_shmdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c000000000673710)
Location: ipc/shm.c:1626
Inline: False
Direct callers:
  - ipc/shm.c:__se_sys_shmdt
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:ksys_ipc
```
**Symbols:**

```
c000000000673710-c000000000673900: ksys_shmdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffe00038c0bc)
Location: ipc/shm.c:1626
Inline: False
Direct callers:
  - ipc/shm.c:__se_sys_shmdt
```
**Symbols:**

```
ffffffe00038c0bc-ffffffe00038c1d0: ksys_shmdt (STB_GLOBAL)
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
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814389a0)
Location: ipc/shm.c:1626
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_sys_shmdt
  - ipc/shm.c:__x64_sys_shmdt
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814389a0-ffffffff81438b09: ksys_shmdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81429410)
Location: ipc/shm.c:1626
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_sys_shmdt
  - ipc/shm.c:__x64_sys_shmdt
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81429410-ffffffff81429579: ksys_shmdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81434b40)
Location: ipc/shm.c:1626
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_sys_shmdt
  - ipc/shm.c:__x64_sys_shmdt
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81434b40-ffffffff81434ca9: ksys_shmdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int ksys_shmdt(char *shmaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8144bc80)
Location: ipc/shm.c:1626
Inline: False
Direct callers:
  - ipc/shm.c:__ia32_sys_shmdt
  - ipc/shm.c:__x64_sys_shmdt
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8144bc80-ffffffff8144bde9: ksys_shmdt (STB_GLOBAL)
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
