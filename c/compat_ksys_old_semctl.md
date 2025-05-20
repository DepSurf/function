# Function: <code>compat_ksys_old_semctl</code>

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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8142365a)
Location: ipc/sem.c:1807
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814239a0-ffffffff814239bd: compat_ksys_old_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8143d39a)
Location: ipc/sem.c:1807
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8143d6e0-ffffffff8143d6fd: compat_ksys_old_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8148df6a)
Location: ipc/sem.c:1823
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8148e280-ffffffff8148e29d: compat_ksys_old_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814ab6aa)
Location: ipc/sem.c:1822
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814ab9c0-ffffffff814ab9dd: compat_ksys_old_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814b064a)
Location: ipc/sem.c:1824
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff814b1850-ffffffff814b186d: compat_ksys_old_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8150871a)
Location: ipc/sem.c:1827
Inline: True
Inline callers:
  - ipc/sem.c:__x64_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81508e60-ffffffff81508e7d: compat_ksys_old_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8159a70a)
Location: ipc/sem.c:1825
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_compat_sys_old_semctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8159aa60-ffffffff8159aa8c: compat_ksys_old_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816439da)
Location: ipc/sem.c:1825
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_compat_sys_old_semctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81643da0-ffffffff81643dcc: compat_ksys_old_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8167bf2a)
Location: ipc/sem.c:1825
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_compat_sys_old_semctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff8167c2e0-ffffffff8167c30c: compat_ksys_old_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816b82fa)
Location: ipc/sem.c:1825
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_compat_sys_old_semctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff816b86b0-ffffffff816b86dc: compat_ksys_old_semctl (STB_GLOBAL)
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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff8000105251e0)
Location: ipc/sem.c:1807
Inline: True
Inline callers:
  - ipc/sem.c:__arm64_compat_sys_old_semctl
```
**Symbols:**

```
ffff8000105254f8-ffff800010525548: compat_ksys_old_semctl (STB_GLOBAL)
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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066e440)
Location: ipc/sem.c:1807
Inline: True
Inline callers:
  - ipc/sem.c:__se_compat_sys_old_semctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
c00000000066f8f0-c00000000066f914: compat_ksys_old_semctl (STB_GLOBAL)
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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8143597a)
Location: ipc/sem.c:1807
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81435cc0-ffffffff81435cdd: compat_ksys_old_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814263fa)
Location: ipc/sem.c:1807
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81426740-ffffffff8142675d: compat_ksys_old_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81431b1a)
Location: ipc/sem.c:1807
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81431e60-ffffffff81431e7d: compat_ksys_old_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81448bea)
Location: ipc/sem.c:1807
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
Direct callers:
  - ipc/syscall.c:compat_ksys_ipc
```
**Symbols:**

```
ffffffff81448f30-ffffffff81448f4d: compat_ksys_old_semctl (STB_GLOBAL)
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
