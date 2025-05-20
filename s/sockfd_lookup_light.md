# Function: <code>sockfd_lookup_light</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fd3f0)
Location: net/socket.c:449
Inline: False
Direct callers:
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_getsockname
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_bind
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_sendto
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff816fd3f0-ffffffff816fd456: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81763f20)
Location: net/socket.c:449
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_sendto
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_getsockname
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_bind
```
**Symbols:**

```
ffffffff81763f20-ffffffff81763f86: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81790f50)
Location: net/socket.c:491
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_sendto
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_getsockname
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_bind
```
**Symbols:**

```
ffffffff81790f50-ffffffff81790fb6: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ae870)
Location: net/socket.c:489
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_sendto
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_getsockname
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_bind
```
**Symbols:**

```
ffffffff817ae870-ffffffff817ae8d8: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81826950)
Location: net/socket.c:495
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_sendto
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_getsockname
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_bind
```
**Symbols:**

```
ffffffff81826950-ffffffff818269b8: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186ffc0)
Location: net/socket.c:489
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffffffff8186ffc0-ffffffff81870026: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81890b90)
Location: net/socket.c:468
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffffffff81890b90-ffffffff81890bf6: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818daaa0)
Location: net/socket.c:479
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffffffff818daaa0-ffffffff818dab09: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190cbf0)
Location: net/socket.c:479
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffffffff8190cbf0-ffffffff8190cc59: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819de960)
Location: net/socket.c:494
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffffffff819de960-ffffffff819de9c7: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819de3a0)
Location: net/socket.c:494
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffffffff819de3a0-ffffffff819de407: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c43b0)
Location: net/socket.c:495
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffffffff819c43b0-ffffffff819c4417: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a73420)
Location: net/socket.c:545
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffffffff81a73420-ffffffff81a73487: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be5f10)
Location: net/socket.c:546
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffffffff81be5f10-ffffffff81be5f90: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d92140)
Location: net/socket.c:548
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffffffff81d92140-ffffffff81d921c0: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e004f0)
Location: net/socket.c:551
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffffffff81e004f0-ffffffff81e00573: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebca50)
Location: net/socket.c:553
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffffffff81ebca50-ffffffff81ebcad3: sockfd_lookup_light (STB_LOCAL)
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
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba1af0)
Location: net/socket.c:479
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__arm64_sys_getsockopt
  - net/socket.c:__arm64_sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffff800010ba1af0-ffff800010ba1b94: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc3b44)
Location: net/socket.c:479
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__se_sys_getsockopt
  - net/socket.c:__se_sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
c0cc3b44-c0cc3bc8: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c76250)
Location: net/socket.c:479
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
c000000000c76250-c000000000c76320: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe000739bee)
Location: net/socket.c:479
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__se_sys_getsockopt
  - net/socket.c:__se_sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffffffe000739bee-ffffffe000739c72: sockfd_lookup_light (STB_LOCAL)
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
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818acbf0)
Location: net/socket.c:479
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffffffff818acbf0-ffffffff818acc59: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81866b40)
Location: net/socket.c:479
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffffffff81866b40-ffffffff81866ba9: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fdbf0)
Location: net/socket.c:479
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffffffff818fdbf0-ffffffff818fdc59: sockfd_lookup_light (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct socket *sockfd_lookup_light(int fd, int *err, int *fput_needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191ec80)
Location: net/socket.c:479
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffffffff8191ec80-ffffffff8191ece9: sockfd_lookup_light (STB_LOCAL)
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
