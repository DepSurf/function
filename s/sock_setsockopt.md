# Function: <code>sock_setsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81704230)
Location: net/core/sock.c:688
Inline: False
Direct callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_sock_setsockopt
  - net/compat.c:compat_sock_setsockopt
  - net/compat.c:compat_sock_setsockopt
```
**Symbols:**

```
ffffffff81704230-ffffffff81704a3e: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8176ad40)
Location: net/core/sock.c:657
Inline: False
Direct callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_sock_setsockopt
  - net/compat.c:compat_sock_setsockopt
  - net/compat.c:compat_sock_setsockopt
```
**Symbols:**

```
ffffffff8176ad40-ffffffff8176b624: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81797e00)
Location: net/core/sock.c:658
Inline: False
Direct callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_sock_setsockopt
  - net/compat.c:compat_sock_setsockopt
  - net/compat.c:compat_sock_setsockopt
```
**Symbols:**

```
ffffffff81797e00-ffffffff817986f7: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b59b0)
Location: net/core/sock.c:701
Inline: False
Direct callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff817b59b0-ffffffff817b6288: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182df00)
Location: net/core/sock.c:691
Inline: False
Direct callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff8182df00-ffffffff8182e846: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818782f0)
Location: net/core/sock.c:697
Inline: False
Direct callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffffffff818782f0-ffffffff81878cc5: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81898a80)
Location: net/core/sock.c:655
Inline: False
Direct callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffffffff81898a80-ffffffff8189967a: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e3020)
Location: net/core/sock.c:722
Inline: False
Direct callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffffffff818e3020-ffffffff818e3cf1: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81915200)
Location: net/core/sock.c:722
Inline: False
Direct callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffffffff81915200-ffffffff81915ed2: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e86b0)
Location: net/core/sock.c:836
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffffffff819e86b0-ffffffff819e9424: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e8340)
Location: net/core/sock.c:823
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
  - net/mptcp/protocol.c:mptcp_setsockopt
  - net/mptcp/protocol.c:mptcp_setsockopt
```
**Symbols:**

```
ffffffff819e8340-ffffffff819e92df: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819ce470)
Location: net/core/sock.c:839
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
```
**Symbols:**

```
ffffffff819ce470-ffffffff819cf3fc: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7e0f0)
Location: net/core/sock.c:957
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
```
**Symbols:**

```
ffffffff81a7e0f0-ffffffff81a7f084: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bf12f0)
Location: net/core/sock.c:1043
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
```
**Symbols:**

```
ffffffff81bf12f0-ffffffff81bf2489: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9fdc0)
Location: net/core/sock.c:1548
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
```
**Symbols:**

```
ffffffff81d9fdc0-ffffffff81d9fde6: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0e580)
Location: net/core/sock.c:1564
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
```
**Symbols:**

```
ffffffff81e0e580-ffffffff81e0e5a6: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ecb010)
Location: net/core/sock.c:1545
Inline: False
Direct callers:
  - net/socket.c:do_sock_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
```
**Symbols:**

```
ffffffff81ecb010-ffffffff81ecb036: sock_setsockopt (STB_GLOBAL)
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
int sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010bae188)
Location: net/core/sock.c:722
Inline: False
Direct callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:__arm64_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffff800010bae188-ffff800010baee88: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0ccbb54)
Location: net/core/sock.c:722
Inline: False
Direct callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:__se_sys_setsockopt
```
**Symbols:**

```
c0ccbb54-c0ccc8e4: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c83b50)
Location: net/core/sock.c:722
Inline: False
Direct callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
c000000000c83b50-c000000000c84b70: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe0007400b6)
Location: net/core/sock.c:722
Inline: False
Direct callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:__se_sys_setsockopt
```
**Symbols:**

```
ffffffe0007400b6-ffffffe000740a14: sock_setsockopt (STB_GLOBAL)
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
int sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b5200)
Location: net/core/sock.c:722
Inline: False
Direct callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffffffff818b5200-ffffffff818b5ed2: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186f150)
Location: net/core/sock.c:722
Inline: False
Direct callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffffffff8186f150-ffffffff8186fe22: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81906200)
Location: net/core/sock.c:722
Inline: False
Direct callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffffffff81906200-ffffffff81906ed2: sock_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81927230)
Location: net/core/sock.c:722
Inline: False
Direct callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffffffff81927230-ffffffff81927f0d: sock_setsockopt (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *optval</code> ➡️ <code>sockptr_t optval</code>
</li>
</ul>
</details>
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
