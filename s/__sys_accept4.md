# Function: <code>__sys_accept4</code>

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
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81872a70)
Location: net/socket.c:1553
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
  - net/socket.c:__ia32_sys_accept4
  - net/socket.c:__x64_sys_accept4
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81872a70-ffffffff81872c80: __sys_accept4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818933c0)
Location: net/socket.c:1540
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
  - net/socket.c:__ia32_sys_accept4
  - net/socket.c:__x64_sys_accept4
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818933c0-ffffffff818935d0: __sys_accept4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dd6d0)
Location: net/socket.c:1705
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
  - net/socket.c:__ia32_sys_accept4
  - net/socket.c:__x64_sys_accept4
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818dd6d0-ffffffff818dd8d3: __sys_accept4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190f730)
Location: net/socket.c:1705
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
  - net/socket.c:__ia32_sys_accept4
  - net/socket.c:__x64_sys_accept4
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff8190f730-ffffffff8190f933: __sys_accept4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1230)
Location: net/socket.c:1797
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
  - net/socket.c:__ia32_sys_accept4
  - net/socket.c:__x64_sys_accept4
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e1230-ffffffff819e12c5: __sys_accept4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e0a80)
Location: net/socket.c:1777
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
  - net/socket.c:__ia32_sys_accept4
  - net/socket.c:__x64_sys_accept4
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e0a80-ffffffff819e0b12: __sys_accept4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c6ad0)
Location: net/socket.c:1768
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
  - net/socket.c:__ia32_sys_accept4
  - net/socket.c:__x64_sys_accept4
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819c6ad0-ffffffff819c6b62: __sys_accept4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a75e20)
Location: net/socket.c:1841
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
  - net/socket.c:__ia32_sys_accept4
  - net/socket.c:__x64_sys_accept4
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81a75e20-ffffffff81a75eb2: __sys_accept4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be8e50)
Location: net/socket.c:1921
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
  - net/socket.c:__ia32_sys_accept4
  - net/socket.c:__x64_sys_accept4
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81be8e50-ffffffff81be8f0e: __sys_accept4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d95550)
Location: net/socket.c:1919
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
  - net/socket.c:__ia32_sys_accept4
  - net/socket.c:__x64_sys_accept4
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81d95550-ffffffff81d95621: __sys_accept4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e03b80)
Location: net/socket.c:1949
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
  - net/socket.c:__ia32_sys_accept4
  - net/socket.c:__x64_sys_accept4
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81e03b80-ffffffff81e03c51: __sys_accept4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec05b0)
Location: net/socket.c:1991
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
  - net/socket.c:__ia32_sys_accept4
  - net/socket.c:__x64_sys_accept4
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81ec05b0-ffffffff81ec0681: __sys_accept4 (STB_GLOBAL)
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
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba7928)
Location: net/socket.c:1705
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_accept
  - net/socket.c:__arm64_sys_accept4
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffff800010ba7928-ffff800010ba7b20: __sys_accept4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc6330)
Location: net/socket.c:1705
Inline: False
Direct callers:
  - net/socket.c:__se_sys_accept
  - net/socket.c:__se_sys_accept4
```
**Symbols:**

```
c0cc6330-c0cc6518: __sys_accept4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7be50)
Location: net/socket.c:1705
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_accept
  - net/socket.c:__se_sys_accept4
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
c000000000c7be50-c000000000c7c114: __sys_accept4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073b274)
Location: net/socket.c:1705
Inline: False
Direct callers:
  - net/socket.c:__se_sys_accept
  - net/socket.c:__se_sys_accept4
```
**Symbols:**

```
ffffffe00073b274-ffffffe00073b3fe: __sys_accept4 (STB_GLOBAL)
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
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818af730)
Location: net/socket.c:1705
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
  - net/socket.c:__ia32_sys_accept4
  - net/socket.c:__x64_sys_accept4
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818af730-ffffffff818af933: __sys_accept4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81869680)
Location: net/socket.c:1705
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
  - net/socket.c:__ia32_sys_accept4
  - net/socket.c:__x64_sys_accept4
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81869680-ffffffff81869883: __sys_accept4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81900730)
Location: net/socket.c:1705
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
  - net/socket.c:__ia32_sys_accept4
  - net/socket.c:__x64_sys_accept4
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81900730-ffffffff81900933: __sys_accept4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sys_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81921720)
Location: net/socket.c:1705
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
  - net/socket.c:__ia32_sys_accept4
  - net/socket.c:__x64_sys_accept4
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81921720-ffffffff81921923: __sys_accept4 (STB_GLOBAL)
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
