# Function: <code>__sys_recvmmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec *timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816ff770)
Location: net/socket.c:2164
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff816ff770-ffffffff816ffa11: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec *timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81766200)
Location: net/socket.c:2163
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff81766200-ffffffff817664b9: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec *timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81793280)
Location: net/socket.c:2208
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff81793280-ffffffff8179353b: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec *timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817b16d0)
Location: net/socket.c:2258
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817b16d0-ffffffff817b198b: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec *timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81829870)
Location: net/socket.c:2251
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff81829870-ffffffff81829b2b: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec *timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81873ac0)
Location: net/socket.c:2356
Inline: False
```
**Symbols:**

```
ffffffff81873ac0-ffffffff81873daf: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81894410)
Location: net/socket.c:2454
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmmsg
  - net/compat.c:__ia32_compat_sys_recvmmsg
  - net/compat.c:__x32_compat_sys_recvmmsg_time64
  - net/compat.c:__ia32_compat_sys_recvmmsg_time64
```
**Symbols:**

```
ffffffff81894410-ffffffff8189454f: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct __kernel_timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818de7c0)
Location: net/socket.c:2665
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
  - net/compat.c:__x32_compat_sys_recvmmsg_time64
  - net/compat.c:__ia32_compat_sys_recvmmsg_time64
```
**Symbols:**

```
ffffffff818de7c0-ffffffff818de90b: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct __kernel_timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81910990)
Location: net/socket.c:2745
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
  - net/compat.c:__x32_compat_sys_recvmmsg_time64
  - net/compat.c:__ia32_compat_sys_recvmmsg_time64
```
**Symbols:**

```
ffffffff81910990-ffffffff81910adb: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct __kernel_timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e24cd)
Location: net/socket.c:2779
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
  - net/compat.c:__x32_compat_sys_recvmmsg_time64
  - net/compat.c:__ia32_compat_sys_recvmmsg_time64
```
**Symbols:**

```
ffffffff819e2cc0-ffffffff819e2e0b: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct __kernel_timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e214d)
Location: net/socket.c:2774
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
  - net/compat.c:__x32_compat_sys_recvmmsg_time64
  - net/compat.c:__ia32_compat_sys_recvmmsg_time64
```
**Symbols:**

```
ffffffff819e2940-ffffffff819e2a8b: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct __kernel_timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c81cf)
Location: net/socket.c:2758
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
  - net/compat.c:__x32_compat_sys_recvmmsg_time64
  - net/compat.c:__ia32_compat_sys_recvmmsg_time64
```
**Symbols:**

```
ffffffff819c8960-ffffffff819c8aab: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct __kernel_timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a7751f)
Location: net/socket.c:2831
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x64_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
  - net/compat.c:__x64_compat_sys_recvmmsg_time64
  - net/compat.c:__ia32_compat_sys_recvmmsg_time64
```
**Symbols:**

```
ffffffff81a77cb0-ffffffff81a77dfb: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct __kernel_timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81bea87b)
Location: net/socket.c:2907
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time64
```
**Symbols:**

```
ffffffff81beb1d0-ffffffff81beb330: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct __kernel_timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d9715b)
Location: net/socket.c:2895
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time64
```
**Symbols:**

```
ffffffff81d97b50-ffffffff81d97cb0: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct __kernel_timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e057cb)
Location: net/socket.c:2933
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time64
```
**Symbols:**

```
ffffffff81e061c0-ffffffff81e0631b: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct __kernel_timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec208b)
Location: net/socket.c:3003
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time64
```
**Symbols:**

```
ffffffff81ec2a80-ffffffff81ec2bdb: __sys_recvmmsg (STB_GLOBAL)
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
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct __kernel_timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba8bd0)
Location: net/socket.c:2745
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_recvmmsg_time32
  - net/socket.c:__arm64_sys_recvmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__arm64_compat_sys_recvmmsg_time32
  - net/compat.c:__arm64_compat_sys_recvmmsg_time64
```
**Symbols:**

```
ffff800010ba8bd0-ffff800010ba8d38: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct __kernel_timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc74e0)
Location: net/socket.c:2745
Inline: False
Direct callers:
  - net/socket.c:__se_sys_recvmmsg_time32
  - net/socket.c:__se_sys_recvmmsg
```
**Symbols:**

```
c0cc74e0-c0cc7634: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct __kernel_timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7d410)
Location: net/socket.c:2745
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_recvmmsg_time32
  - net/socket.c:__se_sys_recvmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__se_compat_sys_recvmmsg_time32
  - net/compat.c:__se_compat_sys_recvmmsg_time64
```
**Symbols:**

```
c000000000c7d410-c000000000c7d5f4: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct __kernel_timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073c1e4)
Location: net/socket.c:2745
Inline: False
Direct callers:
  - net/socket.c:__se_sys_recvmmsg
```
**Symbols:**

```
ffffffe00073c1e4-ffffffe00073c2ce: __sys_recvmmsg (STB_GLOBAL)
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
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct __kernel_timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818b0990)
Location: net/socket.c:2745
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
  - net/compat.c:__x32_compat_sys_recvmmsg_time64
  - net/compat.c:__ia32_compat_sys_recvmmsg_time64
```
**Symbols:**

```
ffffffff818b0990-ffffffff818b0adb: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct __kernel_timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186a8e0)
Location: net/socket.c:2745
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
  - net/compat.c:__x32_compat_sys_recvmmsg_time64
  - net/compat.c:__ia32_compat_sys_recvmmsg_time64
```
**Symbols:**

```
ffffffff8186a8e0-ffffffff8186aa2b: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct __kernel_timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81901990)
Location: net/socket.c:2745
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
  - net/compat.c:__x32_compat_sys_recvmmsg_time64
  - net/compat.c:__ia32_compat_sys_recvmmsg_time64
```
**Symbols:**

```
ffffffff81901990-ffffffff81901adb: __sys_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sys_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct __kernel_timespec *timeout, struct old_timespec32 *timeout32);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81922930)
Location: net/socket.c:2745
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmmsg_time32
  - net/compat.c:__ia32_compat_sys_recvmmsg_time32
  - net/compat.c:__x32_compat_sys_recvmmsg_time64
  - net/compat.c:__ia32_compat_sys_recvmmsg_time64
```
**Symbols:**

```
ffffffff81922930-ffffffff81922a7b: __sys_recvmmsg (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct old_timespec32 *timeout32</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *timeout</code> ➡️ <code>struct __kernel_timespec *timeout</code>
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
