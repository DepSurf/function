# Function: <code>USER_SOCKPTR</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e147d)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/socket.c:__sys_setsockopt
```
```
In net/ipv4/bpfilter/sockopt.c (ffffffff81b0ba6b)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c74cd)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/socket.c:__sys_setsockopt
```
```
In net/ipv4/bpfilter/sockopt.c (ffffffff81af96cb)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a7681d)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/socket.c:__sys_setsockopt
```
```
In net/ipv4/bpfilter/sockopt.c (ffffffff81bba21b)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be99bf)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/socket.c:__sys_setsockopt
```
```
In net/ipv4/bpfilter/sockopt.c (ffffffff81d4e22b)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d9627f)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/socket.c:__sys_setsockopt
```
```
In net/core/sock.c (ffffffff81da10d5)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea21a3)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff81eb4c37)
Location: include/linux/sockptr.h:32
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (ffffffff81f17bab)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f82400)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e048cf)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/socket.c:__sys_setsockopt
```
```
In net/core/sock.c (ffffffff81e0f9a5)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81f009c3)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff81f130e7)
Location: include/linux/sockptr.h:32
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (ffffffff81f7780b)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe2710)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/uring_cmd.c (ffffffff81819cfc)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd_sock
  - io_uring/uring_cmd.c:io_uring_cmd_sock
```
```
In net/socket.c (ffffffff81ec1544)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc4c63)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff81fd7477)
Location: include/linux/sockptr.h:32
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820b0630)
Location: include/linux/sockptr.h:32
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_getsockopt
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
