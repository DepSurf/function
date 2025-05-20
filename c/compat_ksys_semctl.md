# Function: <code>compat_ksys_semctl</code>

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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813dcc80)
Location: ipc/sem.c:1740
Inline: False
Direct callers:
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813dcc80-ffffffff813dce14: compat_ksys_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813f72d0)
Location: ipc/sem.c:1747
Inline: False
Direct callers:
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813f72d0-ffffffff813f747d: compat_ksys_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814233f0)
Location: ipc/sem.c:1756
Inline: False
Direct callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
```
**Symbols:**

```
ffffffff814233f0-ffffffff814235ba: compat_ksys_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8143d130)
Location: ipc/sem.c:1756
Inline: False
Direct callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
```
**Symbols:**

```
ffffffff8143d130-ffffffff8143d2fa: compat_ksys_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8148dcf0)
Location: ipc/sem.c:1772
Inline: False
Direct callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
```
**Symbols:**

```
ffffffff8148dcf0-ffffffff8148dec7: compat_ksys_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814ab430)
Location: ipc/sem.c:1771
Inline: False
Direct callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
```
**Symbols:**

```
ffffffff814ab430-ffffffff814ab607: compat_ksys_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814b03d0)
Location: ipc/sem.c:1773
Inline: False
Direct callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
```
**Symbols:**

```
ffffffff814b03d0-ffffffff814b05a7: compat_ksys_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff815084a0)
Location: ipc/sem.c:1776
Inline: False
Direct callers:
  - ipc/sem.c:__x64_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
  - ipc/sem.c:__x64_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
```
**Symbols:**

```
ffffffff815084a0-ffffffff81508677: compat_ksys_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8159a4f0)
Location: ipc/sem.c:1774
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
```
**Symbols:**

```
ffffffff8159a4f0-ffffffff8159a6bf: compat_ksys_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816437a0)
Location: ipc/sem.c:1774
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
```
**Symbols:**

```
ffffffff816437a0-ffffffff8164396f: compat_ksys_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8167bce0)
Location: ipc/sem.c:1774
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
```
**Symbols:**

```
ffffffff8167bce0-ffffffff8167beb4: compat_ksys_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816b80b0)
Location: ipc/sem.c:1774
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
```
**Symbols:**

```
ffffffff816b80b0-ffffffff816b8284: compat_ksys_semctl (STB_LOCAL)
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff800010524f98)
Location: ipc/sem.c:1756
Inline: False
Direct callers:
  - ipc/sem.c:__arm64_compat_sys_old_semctl
  - ipc/sem.c:__arm64_compat_sys_semctl
```
**Symbols:**

```
ffff800010524f98-ffff800010525178: compat_ksys_semctl (STB_LOCAL)
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066e180)
Location: ipc/sem.c:1756
Inline: False
Direct callers:
  - ipc/sem.c:__se_compat_sys_old_semctl
  - ipc/sem.c:__se_compat_sys_semctl
```
**Symbols:**

```
c00000000066e180-c00000000066e400: compat_ksys_semctl (STB_LOCAL)
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81435710)
Location: ipc/sem.c:1756
Inline: False
Direct callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
```
**Symbols:**

```
ffffffff81435710-ffffffff814358da: compat_ksys_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81426190)
Location: ipc/sem.c:1756
Inline: False
Direct callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
```
**Symbols:**

```
ffffffff81426190-ffffffff8142635a: compat_ksys_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814318b0)
Location: ipc/sem.c:1756
Inline: False
Direct callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
```
**Symbols:**

```
ffffffff814318b0-ffffffff81431a7a: compat_ksys_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81448980)
Location: ipc/sem.c:1756
Inline: False
Direct callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
```
**Symbols:**

```
ffffffff81448980-ffffffff81448b4a: compat_ksys_semctl (STB_LOCAL)
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
