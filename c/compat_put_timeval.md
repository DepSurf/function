# Function: <code>compat_put_timeval</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timeval(const struct timeval *tv, void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81110120)
Location: kernel/compat.c:166
Inline: True
Direct callers:
  - kernel/compat.c:compat_SyS_gettimeofday
  - net/socket.c:compat_sock_ioctl_trans
```
**Symbols:**

```
ffffffff81110120-ffffffff811101a6: compat_put_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_put_timeval(const struct timeval *tv, void *utv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811171a0)
Location: kernel/compat.c:166
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_gettimeofday
  - net/socket.c:compat_sock_ioctl_trans
```
**Symbols:**

```
ffffffff811171a0-ffffffff8111721d: compat_put_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_put_timeval(const struct timeval *tv, void *utv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8111e8e0)
Location: kernel/compat.c:166
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_gettimeofday
  - net/socket.c:compat_sock_ioctl_trans
```
**Symbols:**

```
ffffffff8111e8e0-ffffffff8111e95d: compat_put_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timeval(const struct timeval *tv, void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81120640)
Location: kernel/compat.c:176
Inline: True
Direct callers:
  - kernel/time/time.c:compat_SyS_gettimeofday
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff81120640-ffffffff811206bd: compat_put_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timeval(const struct timeval *tv, void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8112bd70)
Location: kernel/compat.c:176
Inline: True
Direct callers:
  - kernel/time/time.c:compat_SyS_gettimeofday
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff8112bd70-ffffffff8112bde4: compat_put_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timeval(const struct timeval *tv, void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8113a530)
Location: kernel/compat.c:133
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff8113a530-ffffffff8113a5a4: compat_put_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timeval(const struct timeval *tv, void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81145d80)
Location: kernel/compat.c:133
Inline: True
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff81145d80-ffffffff81145e02: compat_put_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timeval(const struct timeval *tv, void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811511d0)
Location: kernel/compat.c:66
Inline: True
```
**Symbols:**

```
ffffffff811511d0-ffffffff8115125b: compat_put_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timeval(const struct timeval *tv, void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8115ce40)
Location: kernel/compat.c:66
Inline: True
```
**Symbols:**

```
ffffffff8115ce40-ffffffff8115cebd: compat_put_timeval (STB_GLOBAL)
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
int compat_put_timeval(const struct timeval *tv, void *utv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffff8000101cb858)
Location: kernel/compat.c:66
Inline: False
```
**Symbols:**

```
ffff8000101cb858-ffff8000101cbb34: compat_put_timeval (STB_GLOBAL)
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
int compat_put_timeval(const struct timeval *tv, void *utv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (c000000000236740)
Location: kernel/compat.c:66
Inline: False
```
**Symbols:**

```
c000000000236740-c000000000236854: compat_put_timeval (STB_GLOBAL)
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
int compat_put_timeval(const struct timeval *tv, void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81155460)
Location: kernel/compat.c:66
Inline: True
```
**Symbols:**

```
ffffffff81155460-ffffffff811554dd: compat_put_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timeval(const struct timeval *tv, void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81148780)
Location: kernel/compat.c:66
Inline: True
```
**Symbols:**

```
ffffffff81148780-ffffffff811487fd: compat_put_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timeval(const struct timeval *tv, void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81153230)
Location: kernel/compat.c:66
Inline: True
```
**Symbols:**

```
ffffffff81153230-ffffffff811532ad: compat_put_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timeval(const struct timeval *tv, void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81160130)
Location: kernel/compat.c:66
Inline: True
```
**Symbols:**

```
ffffffff81160130-ffffffff811601ad: compat_put_timeval (STB_GLOBAL)
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
