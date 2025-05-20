# Function: <code>__sys_recvmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816ff6c0)
Location: net/socket.c:2135
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff816ff6c0-ffffffff816ff74a: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81766150)
Location: net/socket.c:2134
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff81766150-ffffffff817661da: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817931d0)
Location: net/socket.c:2179
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817931d0-ffffffff8179325a: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817b1620)
Location: net/socket.c:2229
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817b1620-ffffffff817b16aa: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818297c0)
Location: net/socket.c:2222
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff818297c0-ffffffff8182984a: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818739d0)
Location: net/socket.c:2325
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recvmsg
  - net/socket.c:__x64_sys_recvmsg
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmsg
  - net/compat.c:__ia32_compat_sys_recvmsg
```
**Symbols:**

```
ffffffff818739d0-ffffffff81873a6b: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81894320)
Location: net/socket.c:2312
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recvmsg
  - net/socket.c:__x64_sys_recvmsg
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmsg
  - net/compat.c:__ia32_compat_sys_recvmsg
```
**Symbols:**

```
ffffffff81894320-ffffffff818943bb: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818de6d0)
Location: net/socket.c:2523
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recvmsg
  - net/socket.c:__x64_sys_recvmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmsg
  - net/compat.c:__ia32_compat_sys_recvmsg
```
**Symbols:**

```
ffffffff818de6d0-ffffffff818de76b: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819108a0)
Location: net/socket.c:2603
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recvmsg
  - net/socket.c:__x64_sys_recvmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmsg
  - net/compat.c:__ia32_compat_sys_recvmsg
```
**Symbols:**

```
ffffffff819108a0-ffffffff8191093b: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e2bc0)
Location: net/socket.c:2637
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_recvmsg
  - net/socket.c:__x64_sys_recvmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmsg
  - net/compat.c:__ia32_compat_sys_recvmsg
```
**Symbols:**

```
ffffffff819e2bc0-ffffffff819e2c6a: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e2840)
Location: net/socket.c:2632
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_recvmsg
  - net/socket.c:__x64_sys_recvmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmsg
  - net/compat.c:__ia32_compat_sys_recvmsg
```
**Symbols:**

```
ffffffff819e2840-ffffffff819e28ea: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c8870)
Location: net/socket.c:2616
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_recvmsg
  - net/socket.c:__x64_sys_recvmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmsg
  - net/compat.c:__ia32_compat_sys_recvmsg
```
**Symbols:**

```
ffffffff819c8870-ffffffff819c891a: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a77bc0)
Location: net/socket.c:2689
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_recvmsg
  - net/socket.c:__x64_sys_recvmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x64_compat_sys_recvmsg
  - net/compat.c:__ia32_compat_sys_recvmsg
```
**Symbols:**

```
ffffffff81a77bc0-ffffffff81a77c6a: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81beb090)
Location: net/socket.c:2765
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_recvmsg
  - net/socket.c:__x64_sys_recvmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_recvmsg
```
**Symbols:**

```
ffffffff81beb090-ffffffff81beb16b: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d979e0)
Location: net/socket.c:2753
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_recvmsg
  - net/socket.c:__x64_sys_recvmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_recvmsg
```
**Symbols:**

```
ffffffff81d979e0-ffffffff81d97abe: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e06050)
Location: net/socket.c:2791
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_recvmsg
  - net/socket.c:__x64_sys_recvmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_recvmsg
```
**Symbols:**

```
ffffffff81e06050-ffffffff81e0612e: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec2910)
Location: net/socket.c:2861
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_recvmsg
  - net/socket.c:__x64_sys_recvmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_recvmsg
```
**Symbols:**

```
ffffffff81ec2910-ffffffff81ec29ee: __sys_recvmsg (STB_GLOBAL)
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
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba8ad0)
Location: net/socket.c:2603
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_recvmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__arm64_compat_sys_recvmsg
```
**Symbols:**

```
ffff800010ba8ad0-ffff800010ba8b98: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc741c)
Location: net/socket.c:2603
Inline: False
Direct callers:
  - net/socket.c:__se_sys_recvmsg
```
**Symbols:**

```
c0cc741c-c0cc74c0: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7d2f0)
Location: net/socket.c:2603
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_recvmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__se_compat_sys_recvmsg
```
**Symbols:**

```
c000000000c7d2f0-c000000000c7d3ec: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073c12a)
Location: net/socket.c:2603
Inline: False
Direct callers:
  - net/socket.c:__se_sys_recvmsg
```
**Symbols:**

```
ffffffe00073c12a-ffffffe00073c1a4: __sys_recvmsg (STB_GLOBAL)
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
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818b08a0)
Location: net/socket.c:2603
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recvmsg
  - net/socket.c:__x64_sys_recvmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmsg
  - net/compat.c:__ia32_compat_sys_recvmsg
```
**Symbols:**

```
ffffffff818b08a0-ffffffff818b093b: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186a7f0)
Location: net/socket.c:2603
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recvmsg
  - net/socket.c:__x64_sys_recvmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmsg
  - net/compat.c:__ia32_compat_sys_recvmsg
```
**Symbols:**

```
ffffffff8186a7f0-ffffffff8186a88b: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819018a0)
Location: net/socket.c:2603
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recvmsg
  - net/socket.c:__x64_sys_recvmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmsg
  - net/compat.c:__ia32_compat_sys_recvmsg
```
**Symbols:**

```
ffffffff819018a0-ffffffff8190193b: __sys_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr *msg, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81922840)
Location: net/socket.c:2603
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recvmsg
  - net/socket.c:__x64_sys_recvmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvmsg
  - net/compat.c:__ia32_compat_sys_recvmsg
```
**Symbols:**

```
ffffffff81922840-ffffffff819228db: __sys_recvmsg (STB_GLOBAL)
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
