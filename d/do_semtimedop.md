# Function: <code>do_semtimedop</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813ab390)
Location: ipc/sem.c:1861
Inline: False
Direct callers:
  - ipc/sem.c:SyS_semop
  - ipc/sem.c:compat_SyS_semtimedop
  - ipc/sem.c:compat_SyS_semtimedop
  - ipc/sem.c:SyS_semtimedop
  - ipc/sem.c:SyS_semtimedop
```
**Symbols:**

```
ffffffff813ab390-ffffffff813ac44c: do_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813db9f0)
Location: ipc/sem.c:1936
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semop
  - ipc/sem.c:__x64_sys_semop
```
**Symbols:**

```
ffffffff813db9f0-ffffffff813dc969: do_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813f6060)
Location: ipc/sem.c:1943
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semop
  - ipc/sem.c:__x64_sys_semop
```
**Symbols:**

```
ffffffff813f6060-ffffffff813f6f8e: do_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81422420)
Location: ipc/sem.c:1965
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semop
  - ipc/sem.c:__x64_sys_semop
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/sem.c:ksys_semtimedop
```
**Symbols:**

```
ffffffff81422420-ffffffff81422ff7: do_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8143c1e0)
Location: ipc/sem.c:1966
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semop
  - ipc/sem.c:__x64_sys_semop
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/sem.c:ksys_semtimedop
```
**Symbols:**

```
ffffffff8143c1e0-ffffffff8143cd3c: do_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8148c910)
Location: ipc/sem.c:1982
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semop
  - ipc/sem.c:__x64_sys_semop
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:ksys_semtimedop
```
**Symbols:**

```
ffffffff8148c910-ffffffff8148d53a: do_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814a9f70)
Location: ipc/sem.c:1981
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semop
  - ipc/sem.c:__x64_sys_semop
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:ksys_semtimedop
```
**Symbols:**

```
ffffffff814a9f70-ffffffff814aac53: do_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814b0860)
Location: ipc/sem.c:1983
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semop
  - ipc/sem.c:__x64_sys_semop
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:ksys_semtimedop
```
**Symbols:**

```
ffffffff814b0860-ffffffff814b148c: do_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff815099e0)
Location: ipc/sem.c:2226
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semop
  - ipc/sem.c:__x64_sys_semop
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:ksys_semtimedop
```
**Symbols:**

```
ffffffff815099e0-ffffffff81509b52: do_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8159b690)
Location: ipc/sem.c:2223
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semop
  - ipc/sem.c:__x64_sys_semop
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:ksys_semtimedop
```
**Symbols:**

```
ffffffff8159b690-ffffffff8159b82f: do_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816449f0)
Location: ipc/sem.c:2224
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semop
  - ipc/sem.c:__x64_sys_semop
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:ksys_semtimedop
```
**Symbols:**

```
ffffffff816449f0-ffffffff81644b8f: do_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8167ced0)
Location: ipc/sem.c:2224
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semop
  - ipc/sem.c:__x64_sys_semop
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:ksys_semtimedop
```
**Symbols:**

```
ffffffff8167ced0-ffffffff8167d07f: do_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816b92a0)
Location: ipc/sem.c:2222
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semop
  - ipc/sem.c:__x64_sys_semop
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:ksys_semtimedop
```
**Symbols:**

```
ffffffff816b92a0-ffffffff816b944f: do_semtimedop (STB_LOCAL)
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
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff800010524038)
Location: ipc/sem.c:1966
Inline: False
Direct callers:
  - ipc/sem.c:__arm64_sys_semop
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/sem.c:ksys_semtimedop
```
**Symbols:**

```
ffff800010524038-ffff800010524bfc: do_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c06dedc4)
Location: ipc/sem.c:1966
Inline: False
Direct callers:
  - ipc/sem.c:__se_sys_semop
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/sem.c:ksys_semtimedop
```
**Symbols:**

```
c06dedc4-c06df870: do_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066e460)
Location: ipc/sem.c:1966
Inline: False
Direct callers:
  - ipc/sem.c:__se_sys_semop
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/sem.c:ksys_semtimedop
```
**Symbols:**

```
c00000000066e460-c00000000066f67c: do_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffe000388e86)
Location: ipc/sem.c:1966
Inline: False
Direct callers:
  - ipc/sem.c:__se_sys_semop
  - ipc/sem.c:ksys_semtimedop
```
**Symbols:**

```
ffffffe000388e86-ffffffe000389892: do_semtimedop (STB_LOCAL)
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
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814347c0)
Location: ipc/sem.c:1966
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semop
  - ipc/sem.c:__x64_sys_semop
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/sem.c:ksys_semtimedop
```
**Symbols:**

```
ffffffff814347c0-ffffffff8143531c: do_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81425240)
Location: ipc/sem.c:1966
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semop
  - ipc/sem.c:__x64_sys_semop
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/sem.c:ksys_semtimedop
```
**Symbols:**

```
ffffffff81425240-ffffffff81425d9c: do_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81430960)
Location: ipc/sem.c:1966
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semop
  - ipc/sem.c:__x64_sys_semop
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/sem.c:ksys_semtimedop
```
**Symbols:**

```
ffffffff81430960-ffffffff814314bc: do_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81446fb0)
Location: ipc/sem.c:1966
Inline: False
Direct callers:
  - ipc/sem.c:__ia32_sys_semop
  - ipc/sem.c:__x64_sys_semop
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/sem.c:ksys_semtimedop
```
**Symbols:**

```
ffffffff81446fb0-ffffffff81447b97: do_semtimedop (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct timespec *timeout</code> ➡️ <code>const struct timespec64 *timeout</code>
</li>
</ul>
</details>
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
