# Function: <code>sock_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fd320)
Location: net/socket.c:1201
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff816fd320-ffffffff816fd352: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817666fd)
Location: net/socket.c:1194
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff81763e50-ffffffff81763e82: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8179377d)
Location: net/socket.c:1237
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff81790e80-ffffffff81790eb2: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817b1df4)
Location: net/socket.c:1286
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff817ae7a0-ffffffff817ae7d2: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81829ff7)
Location: net/socket.c:1305
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff81826870-ffffffff818268a2: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81872632)
Location: net/socket.c:1327
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff8186ff60-ffffffff8186ff92: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81892f82)
Location: net/socket.c:1314
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff81890b30-ffffffff81890b62: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dd278)
Location: net/socket.c:1467
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff818daa40-ffffffff818daa78: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190f2d8)
Location: net/socket.c:1467
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff8190cb90-ffffffff8190cbc8: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e0bd8)
Location: net/socket.c:1477
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff819de900-ffffffff819de93a: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e042e)
Location: net/socket.c:1455
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff819de340-ffffffff819de37a: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c648e)
Location: net/socket.c:1446
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff819c4350-ffffffff819c438a: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a757ae)
Location: net/socket.c:1516
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff81a739b0-ffffffff81a739ea: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be873e)
Location: net/socket.c:1564
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sys_socket_file
```
**Symbols:**

```
ffffffff81be6770-ffffffff81be67b5: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d94e4e)
Location: net/socket.c:1569
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sys_socket_file
```
**Symbols:**

```
ffffffff81d92be0-ffffffff81d92c25: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e0348f)
Location: net/socket.c:1598
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sys_socket_file
```
**Symbols:**

```
ffffffff81e00f50-ffffffff81e00f95: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebfebf)
Location: net/socket.c:1620
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sys_socket_file
```
**Symbols:**

```
ffffffff81ebd650-ffffffff81ebd695: sock_create (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba7528)
Location: net/socket.c:1467
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffff800010ba1a30-ffff800010ba1a8c: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc5f98)
Location: net/socket.c:1467
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
c0cc3ab4-c0cc3b14: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7b928)
Location: net/socket.c:1467
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
c000000000c761f0-c000000000c7622c: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073af3c)
Location: net/socket.c:1467
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffe000739b58-ffffffe000739ba2: sock_create (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818af2d8)
Location: net/socket.c:1467
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff818acb90-ffffffff818acbc8: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81869228)
Location: net/socket.c:1467
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff81866ae0-ffffffff81866b18: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819002d8)
Location: net/socket.c:1467
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff818fdb90-ffffffff818fdbc8: sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sock_create(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819212c8)
Location: net/socket.c:1467
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff8191ec20-ffffffff8191ec58: sock_create (STB_GLOBAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
