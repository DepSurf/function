# Function: <code>put_compat_rusage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81110d10)
Location: kernel/compat.c:511
Inline: False
Direct callers:
  - kernel/sys.c:C_SYSC_getrusage
  - kernel/compat.c:C_SYSC_wait4
  - kernel/compat.c:C_SYSC_waitid
```
**Symbols:**

```
ffffffff81110d10-ffffffff81110eac: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81118460)
Location: kernel/compat.c:511
Inline: False
Direct callers:
  - kernel/sys.c:C_SYSC_getrusage
  - kernel/compat.c:C_SYSC_waitid
  - kernel/compat.c:C_SYSC_wait4
```
**Symbols:**

```
ffffffff81118460-ffffffff811185ef: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8111fb80)
Location: kernel/compat.c:519
Inline: False
Direct callers:
  - kernel/sys.c:C_SYSC_getrusage
  - kernel/compat.c:C_SYSC_waitid
  - kernel/compat.c:C_SYSC_wait4
```
**Symbols:**

```
ffffffff8111fb80-ffffffff8111fd0f: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81120c70)
Location: kernel/compat.c:304
Inline: False
Direct callers:
  - kernel/exit.c:C_SYSC_waitid
  - kernel/exit.c:C_SYSC_wait4
  - kernel/sys.c:C_SYSC_getrusage
```
**Symbols:**

```
ffffffff81120c70-ffffffff81120d44: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8112c350)
Location: kernel/compat.c:281
Inline: False
Direct callers:
  - kernel/exit.c:C_SYSC_waitid
  - kernel/exit.c:C_SYSC_wait4
  - kernel/sys.c:C_SYSC_getrusage
```
**Symbols:**

```
ffffffff8112c350-ffffffff8112c424: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8113ab50)
Location: kernel/compat.c:238
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/sys.c:__do_compat_sys_getrusage
```
**Symbols:**

```
ffffffff8113ab50-ffffffff8113ac24: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811463c0)
Location: kernel/compat.c:238
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/sys.c:__do_compat_sys_getrusage
```
**Symbols:**

```
ffffffff811463c0-ffffffff81146494: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81151520)
Location: kernel/compat.c:171
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/sys.c:__do_compat_sys_getrusage
```
**Symbols:**

```
ffffffff81151520-ffffffff811515f4: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8115d170)
Location: kernel/compat.c:171
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/sys.c:__do_compat_sys_getrusage
```
**Symbols:**

```
ffffffff8115d170-ffffffff8115d244: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116dbb0)
Location: kernel/compat.c:83
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/sys.c:__do_compat_sys_getrusage
```
**Symbols:**

```
ffffffff8116dbb0-ffffffff8116dc82: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116a190)
Location: kernel/compat.c:83
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/sys.c:__do_compat_sys_getrusage
```
**Symbols:**

```
ffffffff8116a190-ffffffff8116a262: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116ae60)
Location: kernel/compat.c:83
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/sys.c:__do_compat_sys_getrusage
```
**Symbols:**

```
ffffffff8116ae60-ffffffff8116af2f: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81190a60)
Location: kernel/compat.c:83
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/sys.c:__do_compat_sys_getrusage
```
**Symbols:**

```
ffffffff81190a60-ffffffff81190b2f: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811c0290)
Location: kernel/compat.c:83
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/sys.c:__do_compat_sys_getrusage
```
**Symbols:**

```
ffffffff811c0290-ffffffff811c0369: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81202630)
Location: kernel/compat.c:83
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/sys.c:__do_compat_sys_getrusage
```
**Symbols:**

```
ffffffff81202630-ffffffff81202709: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81217a10)
Location: kernel/compat.c:83
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/sys.c:__do_compat_sys_getrusage
```
**Symbols:**

```
ffffffff81217a10-ffffffff81217ae9: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8122f5d0)
Location: kernel/compat.c:83
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/sys.c:__do_compat_sys_getrusage
```
**Symbols:**

```
ffffffff8122f5d0-ffffffff8122f6a9: put_compat_rusage (STB_GLOBAL)
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
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffff8000101ccc18)
Location: kernel/compat.c:171
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/sys.c:__do_compat_sys_getrusage
```
**Symbols:**

```
ffff8000101ccc18-ffff8000101cce04: put_compat_rusage (STB_GLOBAL)
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
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (c000000000236e00)
Location: kernel/compat.c:171
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/sys.c:__do_compat_sys_getrusage
```
**Symbols:**

```
c000000000236e00-c000000000236f14: put_compat_rusage (STB_GLOBAL)
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
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81155790)
Location: kernel/compat.c:171
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/sys.c:__do_compat_sys_getrusage
```
**Symbols:**

```
ffffffff81155790-ffffffff81155864: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81148ab0)
Location: kernel/compat.c:171
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/sys.c:__do_compat_sys_getrusage
```
**Symbols:**

```
ffffffff81148ab0-ffffffff81148b84: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81153560)
Location: kernel/compat.c:171
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/sys.c:__do_compat_sys_getrusage
```
**Symbols:**

```
ffffffff81153560-ffffffff81153634: put_compat_rusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage *r, struct compat_rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81160460)
Location: kernel/compat.c:171
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/sys.c:__do_compat_sys_getrusage
```
**Symbols:**

```
ffffffff81160460-ffffffff81160534: put_compat_rusage (STB_GLOBAL)
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
