# Function: <code>__sys_socket</code>

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
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81872460)
Location: net/socket.c:1339
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81872460-ffffffff81872543: __sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81892db0)
Location: net/socket.c:1326
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81892db0-ffffffff81892e93: __sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dd0a0)
Location: net/socket.c:1491
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818dd0a0-ffffffff818dd18a: __sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190f100)
Location: net/socket.c:1491
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff8190f100-ffffffff8190f1ea: __sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e0a00)
Location: net/socket.c:1501
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e0a00-ffffffff819e0aea: __sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e0250)
Location: net/socket.c:1479
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e0250-ffffffff819e033a: __sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c62b0)
Location: net/socket.c:1470
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819c62b0-ffffffff819c639a: __sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a755d0)
Location: net/socket.c:1540
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81a755d0-ffffffff81a756ba: __sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be8500)
Location: net/socket.c:1631
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81be8500-ffffffff81be8612: __sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d94be0)
Location: net/socket.c:1631
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81d94be0-ffffffff81d94cf2: __sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e03220)
Location: net/socket.c:1660
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81e03220-ffffffff81e03332: __sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebfc50)
Location: net/socket.c:1701
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81ebfc50-ffffffff81ebfd68: __sys_socket (STB_GLOBAL)
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
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba7228)
Location: net/socket.c:1491
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_socket
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffff800010ba7228-ffff800010ba7328: __sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc5d20)
Location: net/socket.c:1491
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socket
```
**Symbols:**

```
c0cc5d20-c0cc5e30: __sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7b550)
Location: net/socket.c:1491
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_socket
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
c000000000c7b550-c000000000c7b6cc: __sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073ad4e)
Location: net/socket.c:1491
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socket
```
**Symbols:**

```
ffffffe00073ad4e-ffffffe00073ae14: __sys_socket (STB_GLOBAL)
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
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818af100)
Location: net/socket.c:1491
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818af100-ffffffff818af1ea: __sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81869050)
Location: net/socket.c:1491
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81869050-ffffffff8186913a: __sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81900100)
Location: net/socket.c:1491
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81900100-ffffffff819001ea: __sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sys_socket(int family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819210f0)
Location: net/socket.c:1491
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819210f0-ffffffff819211da: __sys_socket (STB_GLOBAL)
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
