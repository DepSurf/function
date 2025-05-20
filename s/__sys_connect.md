# Function: <code>__sys_connect</code>

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
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81872d10)
Location: net/socket.c:1658
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_connect
  - net/socket.c:__x64_sys_connect
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81872d10-ffffffff81872e30: __sys_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81893660)
Location: net/socket.c:1645
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_connect
  - net/socket.c:__x64_sys_connect
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81893660-ffffffff81893780: __sys_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dd970)
Location: net/socket.c:1810
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_connect
  - net/socket.c:__x64_sys_connect
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818dd970-ffffffff818dda93: __sys_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190f9d0)
Location: net/socket.c:1810
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_connect
  - net/socket.c:__x64_sys_connect
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff8190f9d0-ffffffff8190faf3: __sys_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e13d0)
Location: net/socket.c:1860
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_connect
  - net/socket.c:__x64_sys_connect
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e13d0-ffffffff819e149a: __sys_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e0c20)
Location: net/socket.c:1841
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_connect
  - net/socket.c:__x64_sys_connect
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e0c20-ffffffff819e0cea: __sys_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c6c60)
Location: net/socket.c:1832
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_connect
  - net/socket.c:__x64_sys_connect
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819c6c60-ffffffff819c6d29: __sys_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a75fb0)
Location: net/socket.c:1905
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_connect
  - net/socket.c:__x64_sys_connect
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81a75fb0-ffffffff81a76079: __sys_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be9050)
Location: net/socket.c:1985
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_connect
  - net/socket.c:__x64_sys_connect
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81be9050-ffffffff81be9124: __sys_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d957d0)
Location: net/socket.c:1982
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_connect
  - net/socket.c:__x64_sys_connect
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81d957d0-ffffffff81d958a4: __sys_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e03e10)
Location: net/socket.c:2012
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_connect
  - net/socket.c:__x64_sys_connect
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81e03e10-ffffffff81e03ee4: __sys_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec0840)
Location: net/socket.c:2054
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_connect
  - net/socket.c:__x64_sys_connect
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81ec0840-ffffffff81ec0914: __sys_connect (STB_GLOBAL)
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
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba7b90)
Location: net/socket.c:1810
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_connect
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffff800010ba7b90-ffff800010ba7ca8: __sys_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc6554)
Location: net/socket.c:1810
Inline: False
Direct callers:
  - net/socket.c:__se_sys_connect
```
**Symbols:**

```
c0cc6554-c0cc6638: __sys_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7c1a0)
Location: net/socket.c:1810
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_connect
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
c000000000c7c1a0-c000000000c7c2fc: __sys_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073b482)
Location: net/socket.c:1810
Inline: False
Direct callers:
  - net/socket.c:__se_sys_connect
```
**Symbols:**

```
ffffffe00073b482-ffffffe00073b546: __sys_connect (STB_GLOBAL)
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
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818af9d0)
Location: net/socket.c:1810
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_connect
  - net/socket.c:__x64_sys_connect
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818af9d0-ffffffff818afaf3: __sys_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81869920)
Location: net/socket.c:1810
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_connect
  - net/socket.c:__x64_sys_connect
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81869920-ffffffff81869a43: __sys_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819009d0)
Location: net/socket.c:1810
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_connect
  - net/socket.c:__x64_sys_connect
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819009d0-ffffffff81900af3: __sys_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr *uservaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819219c0)
Location: net/socket.c:1810
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_connect
  - net/socket.c:__x64_sys_connect
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819219c0-ffffffff81921ae3: __sys_connect (STB_GLOBAL)
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
