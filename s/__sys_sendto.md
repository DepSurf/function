# Function: <code>__sys_sendto</code>

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
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818730b0)
Location: net/socket.c:1769
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_send
  - net/socket.c:__x64_sys_send
  - net/socket.c:__ia32_sys_sendto
  - net/socket.c:__x64_sys_sendto
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818730b0-ffffffff81873242: __sys_sendto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81893a00)
Location: net/socket.c:1756
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_send
  - net/socket.c:__x64_sys_send
  - net/socket.c:__ia32_sys_sendto
  - net/socket.c:__x64_sys_sendto
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81893a00-ffffffff81893b92: __sys_sendto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ddd20)
Location: net/socket.c:1921
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_send
  - net/socket.c:__x64_sys_send
  - net/socket.c:__ia32_sys_sendto
  - net/socket.c:__x64_sys_sendto
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818ddd20-ffffffff818ddeb0: __sys_sendto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190fd80)
Location: net/socket.c:1921
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_send
  - net/socket.c:__x64_sys_send
  - net/socket.c:__ia32_sys_sendto
  - net/socket.c:__x64_sys_sendto
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff8190fd80-ffffffff8190ff10: __sys_sendto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1720)
Location: net/socket.c:1964
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_send
  - net/socket.c:__x64_sys_send
  - net/socket.c:__ia32_sys_sendto
  - net/socket.c:__x64_sys_sendto
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e1720-ffffffff819e18aa: __sys_sendto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e0f70)
Location: net/socket.c:1944
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_send
  - net/socket.c:__x64_sys_send
  - net/socket.c:__ia32_sys_sendto
  - net/socket.c:__x64_sys_sendto
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e0f70-ffffffff819e10fa: __sys_sendto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c6fc0)
Location: net/socket.c:1935
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_send
  - net/socket.c:__x64_sys_send
  - net/socket.c:__ia32_sys_sendto
  - net/socket.c:__x64_sys_sendto
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819c6fc0-ffffffff819c714a: __sys_sendto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a76310)
Location: net/socket.c:2008
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_send
  - net/socket.c:__x64_sys_send
  - net/socket.c:__ia32_sys_sendto
  - net/socket.c:__x64_sys_sendto
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81a76310-ffffffff81a7649a: __sys_sendto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be9470)
Location: net/socket.c:2088
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_send
  - net/socket.c:__x64_sys_send
  - net/socket.c:__ia32_sys_sendto
  - net/socket.c:__x64_sys_sendto
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81be9470-ffffffff81be960b: __sys_sendto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d95c80)
Location: net/socket.c:2085
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_send
  - net/socket.c:__x64_sys_send
  - net/socket.c:__ia32_sys_sendto
  - net/socket.c:__x64_sys_sendto
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81d95c80-ffffffff81d95e26: __sys_sendto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e042d0)
Location: net/socket.c:2117
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_send
  - net/socket.c:__x64_sys_send
  - net/socket.c:__ia32_sys_sendto
  - net/socket.c:__x64_sys_sendto
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81e042d0-ffffffff81e0447b: __sys_sendto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec0d00)
Location: net/socket.c:2159
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_send
  - net/socket.c:__x64_sys_send
  - net/socket.c:__ia32_sys_sendto
  - net/socket.c:__x64_sys_sendto
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81ec0d00-ffffffff81ec0f25: __sys_sendto (STB_GLOBAL)
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
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba7ef8)
Location: net/socket.c:1921
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_send
  - net/socket.c:__arm64_sys_sendto
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffff800010ba7ef8-ffff800010ba8048: __sys_sendto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc6840)
Location: net/socket.c:1921
Inline: False
Direct callers:
  - net/socket.c:__se_sys_send
  - net/socket.c:__se_sys_sendto
```
**Symbols:**

```
c0cc6840-c0cc6960: __sys_sendto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7c5f0)
Location: net/socket.c:1921
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_send
  - net/socket.c:__se_sys_sendto
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
c000000000c7c5f0-c000000000c7c79c: __sys_sendto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073b736)
Location: net/socket.c:1921
Inline: False
Direct callers:
  - net/socket.c:__se_sys_send
  - net/socket.c:__se_sys_sendto
```
**Symbols:**

```
ffffffe00073b736-ffffffe00073b844: __sys_sendto (STB_GLOBAL)
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
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818afd80)
Location: net/socket.c:1921
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_send
  - net/socket.c:__x64_sys_send
  - net/socket.c:__ia32_sys_sendto
  - net/socket.c:__x64_sys_sendto
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818afd80-ffffffff818aff10: __sys_sendto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81869cd0)
Location: net/socket.c:1921
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_send
  - net/socket.c:__x64_sys_send
  - net/socket.c:__ia32_sys_sendto
  - net/socket.c:__x64_sys_sendto
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81869cd0-ffffffff81869e60: __sys_sendto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81900d80)
Location: net/socket.c:1921
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_send
  - net/socket.c:__x64_sys_send
  - net/socket.c:__ia32_sys_sendto
  - net/socket.c:__x64_sys_sendto
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81900d80-ffffffff81900f10: __sys_sendto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sys_sendto(int fd, void *buff, size_t len, unsigned int flags, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81921d70)
Location: net/socket.c:1921
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_send
  - net/socket.c:__x64_sys_send
  - net/socket.c:__ia32_sys_sendto
  - net/socket.c:__x64_sys_sendto
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81921d70-ffffffff81921f00: __sys_sendto (STB_GLOBAL)
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
