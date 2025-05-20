# Function: <code>compat_put_timespec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timespec(const struct timespec *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8110fd90)
Location: kernel/compat.c:184
Inline: True
Direct callers:
  - kernel/compat.c:compat_nanosleep_restart
  - kernel/compat.c:compat_clock_nanosleep_restart
  - kernel/compat.c:compat_SyS_nanosleep
  - kernel/compat.c:compat_SyS_clock_gettime
  - kernel/compat.c:compat_SyS_clock_getres
  - kernel/compat.c:compat_SyS_clock_nanosleep
  - kernel/compat.c:compat_SyS_sched_rr_get_interval
  - net/socket.c:compat_sock_ioctl_trans
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff8110fd90-ffffffff8110fdd6: compat_put_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_put_timespec(const struct timespec *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81117220)
Location: kernel/compat.c:184
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_sched_rr_get_interval
  - kernel/compat.c:compat_SyS_clock_nanosleep
  - kernel/compat.c:compat_clock_nanosleep_restart
  - kernel/compat.c:compat_SyS_clock_getres
  - kernel/compat.c:compat_SyS_clock_gettime
  - kernel/compat.c:compat_SyS_nanosleep
  - kernel/compat.c:compat_nanosleep_restart
  - net/socket.c:compat_sock_ioctl_trans
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff81117220-ffffffff81117266: compat_put_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_put_timespec(const struct timespec *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8111e960)
Location: kernel/compat.c:184
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_sched_rr_get_interval
  - kernel/compat.c:compat_SyS_clock_nanosleep
  - kernel/compat.c:compat_clock_nanosleep_restart
  - kernel/compat.c:compat_SyS_clock_getres
  - kernel/compat.c:compat_SyS_clock_gettime
  - kernel/compat.c:compat_SyS_nanosleep
  - kernel/compat.c:compat_nanosleep_restart
  - net/socket.c:compat_sock_ioctl_trans
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff8111e960-ffffffff8111e9a6: compat_put_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timespec(const struct timespec *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81120700)
Location: kernel/compat.c:194
Inline: True
Direct callers:
  - kernel/compat.c:compat_SyS_sched_rr_get_interval
  - net/socket.c:compat_sock_ioctl
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff81120700-ffffffff81120746: compat_put_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timespec(const struct timespec *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8112be70)
Location: kernel/compat.c:194
Inline: True
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff8112be70-ffffffff8112bee4: compat_put_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timespec(const struct timespec *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8113a630)
Location: kernel/compat.c:151
Inline: True
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff8113a630-ffffffff8113a6a4: compat_put_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timespec(const struct timespec *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81145e90)
Location: kernel/compat.c:151
Inline: True
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff81145e90-ffffffff81145f12: compat_put_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timespec(const struct timespec *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81151260)
Location: kernel/compat.c:84
Inline: True
```
**Symbols:**

```
ffffffff81151260-ffffffff811512eb: compat_put_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timespec(const struct timespec *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8115cec0)
Location: kernel/compat.c:84
Inline: True
```
**Symbols:**

```
ffffffff8115cec0-ffffffff8115cf3d: compat_put_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int compat_put_timespec(const struct timespec *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffff8000101cbb38)
Location: kernel/compat.c:84
Inline: False
```
**Symbols:**

```
ffff8000101cbb38-ffff8000101cbe14: compat_put_timespec (STB_GLOBAL)
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
int compat_put_timespec(const struct timespec *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (c000000000236620)
Location: kernel/compat.c:84
Inline: False
```
**Symbols:**

```
c000000000236620-c000000000236734: compat_put_timespec (STB_GLOBAL)
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
int compat_put_timespec(const struct timespec *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811554e0)
Location: kernel/compat.c:84
Inline: True
```
**Symbols:**

```
ffffffff811554e0-ffffffff8115555d: compat_put_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timespec(const struct timespec *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81148800)
Location: kernel/compat.c:84
Inline: True
```
**Symbols:**

```
ffffffff81148800-ffffffff8114887d: compat_put_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timespec(const struct timespec *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811532b0)
Location: kernel/compat.c:84
Inline: True
```
**Symbols:**

```
ffffffff811532b0-ffffffff8115332d: compat_put_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timespec(const struct timespec *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811601b0)
Location: kernel/compat.c:84
Inline: True
```
**Symbols:**

```
ffffffff811601b0-ffffffff8116022d: compat_put_timespec (STB_GLOBAL)
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
