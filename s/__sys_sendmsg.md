# Function: <code>__sys_sendmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816ff440)
Location: net/socket.c:1971
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff816ff440-ffffffff816ff4ca: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81765e90)
Location: net/socket.c:1966
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff81765e90-ffffffff81765f1d: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81792f10)
Location: net/socket.c:2009
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff81792f10-ffffffff81792f9d: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817b1370)
Location: net/socket.c:2059
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817b1370-ffffffff817b13fd: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81829510)
Location: net/socket.c:2052
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff81829510-ffffffff8182959d: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81873670)
Location: net/socket.c:2152
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_sendmsg
  - net/socket.c:__x64_sys_sendmsg
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmsg
  - net/compat.c:__ia32_compat_sys_sendmsg
```
**Symbols:**

```
ffffffff81873670-ffffffff8187370e: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81893fc0)
Location: net/socket.c:2139
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_sendmsg
  - net/socket.c:__x64_sys_sendmsg
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmsg
  - net/compat.c:__ia32_compat_sys_sendmsg
```
**Symbols:**

```
ffffffff81893fc0-ffffffff8189405e: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818de330)
Location: net/socket.c:2342
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_sendmsg
  - net/socket.c:__x64_sys_sendmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmsg
  - net/compat.c:__ia32_compat_sys_sendmsg
```
**Symbols:**

```
ffffffff818de330-ffffffff818de3ce: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81910430)
Location: net/socket.c:2383
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_sendmsg
  - net/socket.c:__x64_sys_sendmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmsg
  - net/compat.c:__ia32_compat_sys_sendmsg
```
**Symbols:**

```
ffffffff81910430-ffffffff819104ce: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e27c0)
Location: net/socket.c:2425
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_sendmsg
  - net/socket.c:__x64_sys_sendmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmsg
  - net/compat.c:__ia32_compat_sys_sendmsg
```
**Symbols:**

```
ffffffff819e27c0-ffffffff819e286d: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e2440)
Location: net/socket.c:2418
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_sendmsg
  - net/socket.c:__x64_sys_sendmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmsg
  - net/compat.c:__ia32_compat_sys_sendmsg
```
**Symbols:**

```
ffffffff819e2440-ffffffff819e24ed: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c84c0)
Location: net/socket.c:2408
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_sendmsg
  - net/socket.c:__x64_sys_sendmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmsg
  - net/compat.c:__ia32_compat_sys_sendmsg
```
**Symbols:**

```
ffffffff819c84c0-ffffffff819c856d: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a77810)
Location: net/socket.c:2481
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_sendmsg
  - net/socket.c:__x64_sys_sendmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x64_compat_sys_sendmsg
  - net/compat.c:__ia32_compat_sys_sendmsg
```
**Symbols:**

```
ffffffff81a77810-ffffffff81a778bd: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81beabe0)
Location: net/socket.c:2557
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_sendmsg
  - net/socket.c:__x64_sys_sendmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_sendmsg
```
**Symbols:**

```
ffffffff81beabe0-ffffffff81beacc5: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d974b0)
Location: net/socket.c:2545
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_sendmsg
  - net/socket.c:__x64_sys_sendmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_sendmsg
```
**Symbols:**

```
ffffffff81d974b0-ffffffff81d97598: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e05b20)
Location: net/socket.c:2583
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_sendmsg
  - net/socket.c:__x64_sys_sendmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_sendmsg
```
**Symbols:**

```
ffffffff81e05b20-ffffffff81e05c08: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec23e0)
Location: net/socket.c:2653
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_sendmsg
  - net/socket.c:__x64_sys_sendmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_sendmsg
```
**Symbols:**

```
ffffffff81ec23e0-ffffffff81ec24c8: __sys_sendmsg (STB_GLOBAL)
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
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba8488)
Location: net/socket.c:2383
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_sendmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__arm64_compat_sys_sendmsg
```
**Symbols:**

```
ffff800010ba8488-ffff800010ba8554: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc70b0)
Location: net/socket.c:2383
Inline: False
Direct callers:
  - net/socket.c:__se_sys_sendmsg
```
**Symbols:**

```
c0cc70b0-c0cc7158: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7cc90)
Location: net/socket.c:2383
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_sendmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__se_compat_sys_sendmsg
```
**Symbols:**

```
c000000000c7cc90-c000000000c7cd8c: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073be2a)
Location: net/socket.c:2383
Inline: False
Direct callers:
  - net/socket.c:__se_sys_sendmsg
```
**Symbols:**

```
ffffffe00073be2a-ffffffe00073bea6: __sys_sendmsg (STB_GLOBAL)
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
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818b0430)
Location: net/socket.c:2383
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_sendmsg
  - net/socket.c:__x64_sys_sendmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmsg
  - net/compat.c:__ia32_compat_sys_sendmsg
```
**Symbols:**

```
ffffffff818b0430-ffffffff818b04ce: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186a380)
Location: net/socket.c:2383
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_sendmsg
  - net/socket.c:__x64_sys_sendmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmsg
  - net/compat.c:__ia32_compat_sys_sendmsg
```
**Symbols:**

```
ffffffff8186a380-ffffffff8186a41e: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81901430)
Location: net/socket.c:2383
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_sendmsg
  - net/socket.c:__x64_sys_sendmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmsg
  - net/compat.c:__ia32_compat_sys_sendmsg
```
**Symbols:**

```
ffffffff81901430-ffffffff819014ce: __sys_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81922420)
Location: net/socket.c:2383
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_sendmsg
  - net/socket.c:__x64_sys_sendmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmsg
  - net/compat.c:__ia32_compat_sys_sendmsg
```
**Symbols:**

```
ffffffff81922420-ffffffff819224be: __sys_sendmsg (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool forbid_cmsg_compat</code>
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
