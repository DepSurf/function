# Function: <code>__sys_bind</code>

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
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81872830)
Location: net/socket.c:1481
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_bind
  - net/socket.c:__x64_sys_bind
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81872830-ffffffff81872937: __sys_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81893180)
Location: net/socket.c:1468
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_bind
  - net/socket.c:__x64_sys_bind
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81893180-ffffffff81893287: __sys_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dd490)
Location: net/socket.c:1633
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_bind
  - net/socket.c:__x64_sys_bind
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818dd490-ffffffff818dd59b: __sys_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190f4f0)
Location: net/socket.c:1633
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_bind
  - net/socket.c:__x64_sys_bind
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff8190f4f0-ffffffff8190f5fb: __sys_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e0df0)
Location: net/socket.c:1643
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_bind
  - net/socket.c:__x64_sys_bind
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e0df0-ffffffff819e0efd: __sys_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e0640)
Location: net/socket.c:1621
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_bind
  - net/socket.c:__x64_sys_bind
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e0640-ffffffff819e074d: __sys_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c6690)
Location: net/socket.c:1612
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_bind
  - net/socket.c:__x64_sys_bind
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819c6690-ffffffff819c679d: __sys_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a759b0)
Location: net/socket.c:1682
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_bind
  - net/socket.c:__x64_sys_bind
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81a759b0-ffffffff81a75abd: __sys_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be8980)
Location: net/socket.c:1762
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_bind
  - net/socket.c:__x64_sys_bind
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81be8980-ffffffff81be8a8a: __sys_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d950c0)
Location: net/socket.c:1762
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_bind
  - net/socket.c:__x64_sys_bind
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81d950c0-ffffffff81d951ca: __sys_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e036e0)
Location: net/socket.c:1791
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_bind
  - net/socket.c:__x64_sys_bind
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81e036e0-ffffffff81e037ea: __sys_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec0110)
Location: net/socket.c:1833
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_bind
  - net/socket.c:__x64_sys_bind
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81ec0110-ffffffff81ec021a: __sys_bind (STB_GLOBAL)
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
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba76e8)
Location: net/socket.c:1633
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_bind
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffff800010ba76e8-ffff800010ba77f0: __sys_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc6154)
Location: net/socket.c:1633
Inline: False
Direct callers:
  - net/socket.c:__se_sys_bind
```
**Symbols:**

```
c0cc6154-c0cc6234: __sys_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7bb80)
Location: net/socket.c:1633
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_bind
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
c000000000c7bb80-c000000000c7bccc: __sys_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073b0bc)
Location: net/socket.c:1633
Inline: False
Direct callers:
  - net/socket.c:__se_sys_bind
```
**Symbols:**

```
ffffffe00073b0bc-ffffffe00073b172: __sys_bind (STB_GLOBAL)
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
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818af4f0)
Location: net/socket.c:1633
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_bind
  - net/socket.c:__x64_sys_bind
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818af4f0-ffffffff818af5fb: __sys_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81869440)
Location: net/socket.c:1633
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_bind
  - net/socket.c:__x64_sys_bind
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81869440-ffffffff8186954b: __sys_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819004f0)
Location: net/socket.c:1633
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_bind
  - net/socket.c:__x64_sys_bind
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819004f0-ffffffff819005fb: __sys_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sys_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819214e0)
Location: net/socket.c:1633
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_bind
  - net/socket.c:__x64_sys_bind
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819214e0-ffffffff819215eb: __sys_bind (STB_GLOBAL)
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
