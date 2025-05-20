# Function: <code>__sock_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fd0f0)
Location: net/socket.c:1088
Inline: False
Direct callers:
  - net/socket.c:sock_create_kern
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff816fd0f0-ffffffff816fd313: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81763c50)
Location: net/socket.c:1085
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff81763c50-ffffffff81763e46: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81790c80)
Location: net/socket.c:1128
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff81790c80-ffffffff81790e76: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ae5a0)
Location: net/socket.c:1177
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff817ae5a0-ffffffff817ae79a: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81826670)
Location: net/socket.c:1196
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff81826670-ffffffff8182686f: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1218
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff81874492-ffffffff818744d5: __sock_create.cold.25 (STB_LOCAL)
ffffffff8186fda0-ffffffff8186ff58: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1205
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff81894d62-ffffffff81894da5: __sock_create.cold.23 (STB_LOCAL)
ffffffff81890970-ffffffff81890b28: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1347
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff818df124-ffffffff818df168: __sock_create.cold (STB_LOCAL)
ffffffff818da870-ffffffff818daa31: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1347
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff819112f4-ffffffff81911338: __sock_create.cold (STB_LOCAL)
ffffffff8190c9c0-ffffffff8190cb81: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1357
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff819e3206-ffffffff819e324a: __sock_create.cold (STB_LOCAL)
ffffffff819de730-ffffffff819de8f1: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1335
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff81c3034c-ffffffff81c30390: __sock_create.cold (STB_LOCAL)
ffffffff819de170-ffffffff819de33b: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1326
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff81c2262a-ffffffff81c2266e: __sock_create.cold (STB_LOCAL)
ffffffff819c4180-ffffffff819c434b: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1396
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff81d34992-ffffffff81d349eb: __sock_create.cold (STB_LOCAL)
ffffffff81a73780-ffffffff81a739a6: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1444
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sys_socket_file
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff81f00ed3-ffffffff81f00f20: __sock_create.cold (STB_LOCAL)
ffffffff81be6520-ffffffff81be676e: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1449
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sys_socket_file
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff820aaabf-ffffffff820aaad3: __sock_create.cold (STB_LOCAL)
ffffffff81d92950-ffffffff81d92bd0: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1478
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sys_socket_file
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff8212bff5-ffffffff8212c009: __sock_create.cold (STB_LOCAL)
ffffffff81e00cc0-ffffffff81e00f40: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1500
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sys_socket_file
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff8220dca7-ffffffff8220dcbb: __sock_create.cold (STB_LOCAL)
ffffffff81ebd3c0-ffffffff81ebd640: __sock_create (STB_GLOBAL)
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
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba1840)
Location: net/socket.c:1347
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffff800010ba1840-ffff800010ba1a30: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc38b8)
Location: net/socket.c:1347
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
c0cc38b8-c0cc3ab4: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c75f50)
Location: net/socket.c:1347
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
c000000000c75f50-c000000000c761e8: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe0007399c6)
Location: net/socket.c:1347
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffe0007399c6-ffffffe000739b58: __sock_create (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1347
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff818b12f4-ffffffff818b1338: __sock_create.cold (STB_LOCAL)
ffffffff818ac9c0-ffffffff818acb81: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1347
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff8186b244-ffffffff8186b288: __sock_create.cold (STB_LOCAL)
ffffffff81866910-ffffffff81866ad1: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1347
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff819022f4-ffffffff81902338: __sock_create.cold (STB_LOCAL)
ffffffff818fd9c0-ffffffff818fdb81: __sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __sock_create(struct net *net, int family, int type, int protocol, struct socket **res, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1347
Inline: False
Direct callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:sock_create_kern
```
**Symbols:**

```
ffffffff819232b0-ffffffff819232f4: __sock_create.cold (STB_LOCAL)
ffffffff8191ea40-ffffffff8191ec18: __sock_create (STB_GLOBAL)
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
