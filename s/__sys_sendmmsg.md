# Function: <code>__sys_sendmmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816ff4f0)
Location: net/socket.c:1999
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff816ff4f0-ffffffff816ff69e: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81765f40)
Location: net/socket.c:1994
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff81765f40-ffffffff81766128: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81792fc0)
Location: net/socket.c:2037
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff81792fc0-ffffffff817931ae: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817b1420)
Location: net/socket.c:2087
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817b1420-ffffffff817b15fe: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818295c0)
Location: net/socket.c:2080
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff818295c0-ffffffff8182979e: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81873760)
Location: net/socket.c:2182
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmmsg
  - net/compat.c:__ia32_compat_sys_sendmmsg
```
**Symbols:**

```
ffffffff81873760-ffffffff8187396d: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818940b0)
Location: net/socket.c:2169
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmmsg
  - net/compat.c:__ia32_compat_sys_sendmmsg
```
**Symbols:**

```
ffffffff818940b0-ffffffff818942ba: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818de420)
Location: net/socket.c:2372
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmmsg
  - net/compat.c:__ia32_compat_sys_sendmmsg
```
**Symbols:**

```
ffffffff818de420-ffffffff818de61f: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81910520)
Location: net/socket.c:2413
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmmsg
  - net/compat.c:__ia32_compat_sys_sendmmsg
```
**Symbols:**

```
ffffffff81910520-ffffffff8191073d: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e28c0)
Location: net/socket.c:2455
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmmsg
  - net/compat.c:__ia32_compat_sys_sendmmsg
```
**Symbols:**

```
ffffffff819e28c0-ffffffff819e2add: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e2540)
Location: net/socket.c:2448
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmmsg
  - net/compat.c:__ia32_compat_sys_sendmmsg
```
**Symbols:**

```
ffffffff819e2540-ffffffff819e273e: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c85b0)
Location: net/socket.c:2438
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmmsg
  - net/compat.c:__ia32_compat_sys_sendmmsg
```
**Symbols:**

```
ffffffff819c85b0-ffffffff819c87aa: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a77900)
Location: net/socket.c:2511
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x64_compat_sys_sendmmsg
  - net/compat.c:__ia32_compat_sys_sendmmsg
```
**Symbols:**

```
ffffffff81a77900-ffffffff81a77afa: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81bead30)
Location: net/socket.c:2587
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_sendmmsg
```
**Symbols:**

```
ffffffff81bead30-ffffffff81beaf7e: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d97630)
Location: net/socket.c:2575
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_sendmmsg
```
**Symbols:**

```
ffffffff81d97630-ffffffff81d9787e: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e05ca0)
Location: net/socket.c:2613
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_sendmmsg
```
**Symbols:**

```
ffffffff81e05ca0-ffffffff81e05eec: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec2560)
Location: net/socket.c:2683
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_sendmmsg
```
**Symbols:**

```
ffffffff81ec2560-ffffffff81ec27ac: __sys_sendmmsg (STB_GLOBAL)
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
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba8590)
Location: net/socket.c:2413
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_sendmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__arm64_compat_sys_sendmmsg
```
**Symbols:**

```
ffff800010ba8590-ffff800010ba898c: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc7178)
Location: net/socket.c:2413
Inline: False
Direct callers:
  - net/socket.c:__se_sys_sendmmsg
```
**Symbols:**

```
c0cc7178-c0cc730c: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7cdb0)
Location: net/socket.c:2413
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_sendmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__se_compat_sys_sendmmsg
```
**Symbols:**

```
c000000000c7cdb0-c000000000c7d164: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073bee6)
Location: net/socket.c:2413
Inline: False
Direct callers:
  - net/socket.c:__se_sys_sendmmsg
```
**Symbols:**

```
ffffffe00073bee6-ffffffe00073c026: __sys_sendmmsg (STB_GLOBAL)
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
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818b0520)
Location: net/socket.c:2413
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmmsg
  - net/compat.c:__ia32_compat_sys_sendmmsg
```
**Symbols:**

```
ffffffff818b0520-ffffffff818b073d: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186a470)
Location: net/socket.c:2413
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmmsg
  - net/compat.c:__ia32_compat_sys_sendmmsg
```
**Symbols:**

```
ffffffff8186a470-ffffffff8186a68d: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81901520)
Location: net/socket.c:2413
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmmsg
  - net/compat.c:__ia32_compat_sys_sendmmsg
```
**Symbols:**

```
ffffffff81901520-ffffffff8190173d: __sys_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81922510)
Location: net/socket.c:2413
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_sendmmsg
  - net/compat.c:__ia32_compat_sys_sendmmsg
```
**Symbols:**

```
ffffffff81922510-ffffffff819226db: __sys_sendmmsg (STB_GLOBAL)
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
