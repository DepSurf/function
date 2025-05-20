# Function: <code>__sys_getsockname</code>

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
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81872e70)
Location: net/socket.c:1695
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getsockname
  - net/socket.c:__x64_sys_getsockname
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81872e70-ffffffff81872f41: __sys_getsockname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818937c0)
Location: net/socket.c:1682
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getsockname
  - net/socket.c:__x64_sys_getsockname
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818937c0-ffffffff81893891: __sys_getsockname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ddae0)
Location: net/socket.c:1847
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getsockname
  - net/socket.c:__x64_sys_getsockname
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818ddae0-ffffffff818ddbb1: __sys_getsockname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190fb40)
Location: net/socket.c:1847
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getsockname
  - net/socket.c:__x64_sys_getsockname
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff8190fb40-ffffffff8190fc11: __sys_getsockname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e14e0)
Location: net/socket.c:1890
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getsockname
  - net/socket.c:__x64_sys_getsockname
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e14e0-ffffffff819e15b1: __sys_getsockname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e0d30)
Location: net/socket.c:1870
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getsockname
  - net/socket.c:__x64_sys_getsockname
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e0d30-ffffffff819e0e01: __sys_getsockname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c6d70)
Location: net/socket.c:1861
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getsockname
  - net/socket.c:__x64_sys_getsockname
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819c6d70-ffffffff819c6e41: __sys_getsockname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a760c0)
Location: net/socket.c:1934
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getsockname
  - net/socket.c:__x64_sys_getsockname
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81a760c0-ffffffff81a76191: __sys_getsockname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be9190)
Location: net/socket.c:2014
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getsockname
  - net/socket.c:__x64_sys_getsockname
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81be9190-ffffffff81be9294: __sys_getsockname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d95940)
Location: net/socket.c:2011
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getsockname
  - net/socket.c:__x64_sys_getsockname
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81d95940-ffffffff81d95a44: __sys_getsockname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e03f80)
Location: net/socket.c:2041
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getsockname
  - net/socket.c:__x64_sys_getsockname
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81e03f80-ffffffff81e04084: __sys_getsockname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec09b0)
Location: net/socket.c:2083
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getsockname
  - net/socket.c:__x64_sys_getsockname
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81ec09b0-ffffffff81ec0ab4: __sys_getsockname (STB_GLOBAL)
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
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba7ce0)
Location: net/socket.c:1847
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_getsockname
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffff800010ba7ce0-ffff800010ba7db0: __sys_getsockname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc6654)
Location: net/socket.c:1847
Inline: False
Direct callers:
  - net/socket.c:__se_sys_getsockname
```
**Symbols:**

```
c0cc6654-c0cc6728: __sys_getsockname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7c340)
Location: net/socket.c:1847
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_getsockname
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
c000000000c7c340-c000000000c7c448: __sys_getsockname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073b584)
Location: net/socket.c:1847
Inline: False
Direct callers:
  - net/socket.c:__se_sys_getsockname
```
**Symbols:**

```
ffffffe00073b584-ffffffe00073b626: __sys_getsockname (STB_GLOBAL)
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
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818afb40)
Location: net/socket.c:1847
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getsockname
  - net/socket.c:__x64_sys_getsockname
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818afb40-ffffffff818afc11: __sys_getsockname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81869a90)
Location: net/socket.c:1847
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getsockname
  - net/socket.c:__x64_sys_getsockname
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81869a90-ffffffff81869b61: __sys_getsockname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81900b40)
Location: net/socket.c:1847
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getsockname
  - net/socket.c:__x64_sys_getsockname
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81900b40-ffffffff81900c11: __sys_getsockname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81921b30)
Location: net/socket.c:1847
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getsockname
  - net/socket.c:__x64_sys_getsockname
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81921b30-ffffffff81921c01: __sys_getsockname (STB_GLOBAL)
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
