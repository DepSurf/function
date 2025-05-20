# Function: <code>__sys_recvfrom</code>

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
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81873310)
Location: net/socket.c:1830
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recv
  - net/socket.c:__x64_sys_recv
  - net/socket.c:__ia32_sys_recvfrom
  - net/socket.c:__x64_sys_recvfrom
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
```
**Symbols:**

```
ffffffff81873310-ffffffff818734ce: __sys_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81893c60)
Location: net/socket.c:1817
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recv
  - net/socket.c:__x64_sys_recv
  - net/socket.c:__ia32_sys_recvfrom
  - net/socket.c:__x64_sys_recvfrom
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
```
**Symbols:**

```
ffffffff81893c60-ffffffff81893e1e: __sys_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ddf70)
Location: net/socket.c:1982
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recv
  - net/socket.c:__x64_sys_recv
  - net/socket.c:__ia32_sys_recvfrom
  - net/socket.c:__x64_sys_recvfrom
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
```
**Symbols:**

```
ffffffff818ddf70-ffffffff818de134: __sys_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190ffd0)
Location: net/socket.c:1982
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recv
  - net/socket.c:__x64_sys_recv
  - net/socket.c:__ia32_sys_recvfrom
  - net/socket.c:__x64_sys_recvfrom
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
```
**Symbols:**

```
ffffffff8190ffd0-ffffffff81910194: __sys_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1970)
Location: net/socket.c:2025
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_recv
  - net/socket.c:__x64_sys_recv
  - net/socket.c:__ia32_sys_recvfrom
  - net/socket.c:__x64_sys_recvfrom
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
```
**Symbols:**

```
ffffffff819e1970-ffffffff819e1b34: __sys_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e11c0)
Location: net/socket.c:2005
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_recv
  - net/socket.c:__x64_sys_recv
  - net/socket.c:__ia32_sys_recvfrom
  - net/socket.c:__x64_sys_recvfrom
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
```
**Symbols:**

```
ffffffff819e11c0-ffffffff819e1384: __sys_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c7210)
Location: net/socket.c:1996
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_recv
  - net/socket.c:__x64_sys_recv
  - net/socket.c:__ia32_sys_recvfrom
  - net/socket.c:__x64_sys_recvfrom
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
```
**Symbols:**

```
ffffffff819c7210-ffffffff819c73d8: __sys_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a76560)
Location: net/socket.c:2069
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_recv
  - net/socket.c:__x64_sys_recv
  - net/socket.c:__ia32_sys_recvfrom
  - net/socket.c:__x64_sys_recvfrom
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x64_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x64_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
```
**Symbols:**

```
ffffffff81a76560-ffffffff81a76728: __sys_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be9710)
Location: net/socket.c:2149
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_recv
  - net/socket.c:__x64_sys_recv
  - net/socket.c:__ia32_sys_recvfrom
  - net/socket.c:__x64_sys_recvfrom
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recv
```
**Symbols:**

```
ffffffff81be9710-ffffffff81be988f: __sys_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d95f80)
Location: net/socket.c:2147
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_recv
  - net/socket.c:__x64_sys_recv
  - net/socket.c:__ia32_sys_recvfrom
  - net/socket.c:__x64_sys_recvfrom
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recv
```
**Symbols:**

```
ffffffff81d95f80-ffffffff81d960ff: __sys_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e045d0)
Location: net/socket.c:2180
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_recv
  - net/socket.c:__x64_sys_recv
  - net/socket.c:__ia32_sys_recvfrom
  - net/socket.c:__x64_sys_recvfrom
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recv
```
**Symbols:**

```
ffffffff81e045d0-ffffffff81e0474f: __sys_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec1080)
Location: net/socket.c:2221
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_recv
  - net/socket.c:__x64_sys_recv
  - net/socket.c:__ia32_sys_recvfrom
  - net/socket.c:__x64_sys_recvfrom
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recv
```
**Symbols:**

```
ffffffff81ec1080-ffffffff81ec11e2: __sys_recvfrom (STB_GLOBAL)
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
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba80c8)
Location: net/socket.c:1982
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_recv
  - net/socket.c:__arm64_sys_recvfrom
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__arm64_compat_sys_recvfrom
  - net/compat.c:__arm64_compat_sys_recv
```
**Symbols:**

```
ffff800010ba80c8-ffff800010ba8230: __sys_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc69c4)
Location: net/socket.c:1982
Inline: False
Direct callers:
  - net/socket.c:__se_sys_recv
  - net/socket.c:__se_sys_recvfrom
```
**Symbols:**

```
c0cc69c4-c0cc6b4c: __sys_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7c820)
Location: net/socket.c:1982
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_recv
  - net/socket.c:__se_sys_recvfrom
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__se_compat_sys_recvfrom
  - net/compat.c:__se_compat_sys_recv
```
**Symbols:**

```
c000000000c7c820-c000000000c7c9a4: __sys_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073b8e6)
Location: net/socket.c:1982
Inline: False
Direct callers:
  - net/socket.c:__se_sys_recv
  - net/socket.c:__se_sys_recvfrom
```
**Symbols:**

```
ffffffe00073b8e6-ffffffe00073b9dc: __sys_recvfrom (STB_GLOBAL)
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
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818affd0)
Location: net/socket.c:1982
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recv
  - net/socket.c:__x64_sys_recv
  - net/socket.c:__ia32_sys_recvfrom
  - net/socket.c:__x64_sys_recvfrom
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
```
**Symbols:**

```
ffffffff818affd0-ffffffff818b0194: __sys_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81869f20)
Location: net/socket.c:1982
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recv
  - net/socket.c:__x64_sys_recv
  - net/socket.c:__ia32_sys_recvfrom
  - net/socket.c:__x64_sys_recvfrom
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
```
**Symbols:**

```
ffffffff81869f20-ffffffff8186a0e4: __sys_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81900fd0)
Location: net/socket.c:1982
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recv
  - net/socket.c:__x64_sys_recv
  - net/socket.c:__ia32_sys_recvfrom
  - net/socket.c:__x64_sys_recvfrom
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
```
**Symbols:**

```
ffffffff81900fd0-ffffffff81901194: __sys_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sys_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81921fc0)
Location: net/socket.c:1982
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_recv
  - net/socket.c:__x64_sys_recv
  - net/socket.c:__ia32_sys_recvfrom
  - net/socket.c:__x64_sys_recvfrom
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_recvfrom
  - net/compat.c:__ia32_compat_sys_recvfrom
  - net/compat.c:__x32_compat_sys_recv
  - net/compat.c:__ia32_compat_sys_recv
```
**Symbols:**

```
ffffffff81921fc0-ffffffff81922184: __sys_recvfrom (STB_GLOBAL)
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
