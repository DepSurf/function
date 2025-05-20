# Function: <code>__sys_getpeername</code>

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
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81872f90)
Location: net/socket.c:1733
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getpeername
  - net/socket.c:__x64_sys_getpeername
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81872f90-ffffffff8187306e: __sys_getpeername (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818938e0)
Location: net/socket.c:1720
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getpeername
  - net/socket.c:__x64_sys_getpeername
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818938e0-ffffffff818939be: __sys_getpeername (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ddc00)
Location: net/socket.c:1885
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getpeername
  - net/socket.c:__x64_sys_getpeername
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818ddc00-ffffffff818ddcde: __sys_getpeername (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190fc60)
Location: net/socket.c:1885
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getpeername
  - net/socket.c:__x64_sys_getpeername
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff8190fc60-ffffffff8190fd3e: __sys_getpeername (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1600)
Location: net/socket.c:1928
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getpeername
  - net/socket.c:__x64_sys_getpeername
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e1600-ffffffff819e16de: __sys_getpeername (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e0e50)
Location: net/socket.c:1908
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getpeername
  - net/socket.c:__x64_sys_getpeername
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e0e50-ffffffff819e0f2e: __sys_getpeername (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c6e90)
Location: net/socket.c:1899
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getpeername
  - net/socket.c:__x64_sys_getpeername
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819c6e90-ffffffff819c6f7f: __sys_getpeername (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a761e0)
Location: net/socket.c:1972
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getpeername
  - net/socket.c:__x64_sys_getpeername
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81a761e0-ffffffff81a762cf: __sys_getpeername (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be9300)
Location: net/socket.c:2052
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getpeername
  - net/socket.c:__x64_sys_getpeername
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81be9300-ffffffff81be9410: __sys_getpeername (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d95ae0)
Location: net/socket.c:2049
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getpeername
  - net/socket.c:__x64_sys_getpeername
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81d95ae0-ffffffff81d95bf0: __sys_getpeername (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e04120)
Location: net/socket.c:2079
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getpeername
  - net/socket.c:__x64_sys_getpeername
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81e04120-ffffffff81e0423e: __sys_getpeername (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec0b50)
Location: net/socket.c:2121
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getpeername
  - net/socket.c:__x64_sys_getpeername
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81ec0b50-ffffffff81ec0c6e: __sys_getpeername (STB_GLOBAL)
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
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba7de8)
Location: net/socket.c:1885
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_getpeername
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffff800010ba7de8-ffff800010ba7ec0: __sys_getpeername (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc6744)
Location: net/socket.c:1885
Inline: False
Direct callers:
  - net/socket.c:__se_sys_getpeername
```
**Symbols:**

```
c0cc6744-c0cc6824: __sys_getpeername (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7c490)
Location: net/socket.c:1885
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_getpeername
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
c000000000c7c490-c000000000c7c5a4: __sys_getpeername (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073b662)
Location: net/socket.c:1885
Inline: False
Direct callers:
  - net/socket.c:__se_sys_getpeername
```
**Symbols:**

```
ffffffe00073b662-ffffffe00073b6fa: __sys_getpeername (STB_GLOBAL)
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
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818afc60)
Location: net/socket.c:1885
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getpeername
  - net/socket.c:__x64_sys_getpeername
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818afc60-ffffffff818afd3e: __sys_getpeername (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81869bb0)
Location: net/socket.c:1885
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getpeername
  - net/socket.c:__x64_sys_getpeername
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81869bb0-ffffffff81869c8e: __sys_getpeername (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81900c60)
Location: net/socket.c:1885
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getpeername
  - net/socket.c:__x64_sys_getpeername
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81900c60-ffffffff81900d3e: __sys_getpeername (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sys_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81921c50)
Location: net/socket.c:1885
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getpeername
  - net/socket.c:__x64_sys_getpeername
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81921c50-ffffffff81921d2e: __sys_getpeername (STB_GLOBAL)
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
