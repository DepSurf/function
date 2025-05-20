# Function: <code>KERNEL_SOCKPTR</code>

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
In net/socket.c (0)
Location: include/linux/sockptr.h:27
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aab3fe)
Location: include/linux/sockptr.h:27
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
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
In net/socket.c (0)
Location: include/linux/sockptr.h:27
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a965fc)
Location: include/linux/sockptr.h:27
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/mptcp/sockopt.c (ffffffff81bbc4d5)
Location: include/linux/sockptr.h:27
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
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
In net/socket.c (0)
Location: include/linux/sockptr.h:27
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b51a6f)
Location: include/linux/sockptr.h:27
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/mptcp/sockopt.c (ffffffff81c8c460)
Location: include/linux/sockptr.h:27
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
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
In net/socket.c (0)
Location: include/linux/sockptr.h:27
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdf5ec)
Location: include/linux/sockptr.h:27
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/mptcp/sockopt.c (ffffffff81e3488f)
Location: include/linux/sockptr.h:27
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
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
In net/socket.c (0)
Location: include/linux/sockptr.h:27
Inline: True
```
```
In net/core/filter.c (ffffffff81deb2df)
Location: include/linux/sockptr.h:27
Inline: True
Inline callers:
  - net/core/filter.c:sol_ipv6_sockopt
  - net/core/filter.c:sol_ipv6_sockopt
  - net/core/filter.c:sol_ipv6_sockopt
  - net/core/filter.c:sol_ip_sockopt
  - net/core/filter.c:sol_ip_sockopt
  - net/core/filter.c:sol_ip_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_socket_sockopt
  - net/core/filter.c:sol_socket_sockopt
  - net/core/filter.c:sol_socket_sockopt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9fab9)
Location: include/linux/sockptr.h:27
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/mptcp/sockopt.c (ffffffff8200d13c)
Location: include/linux/sockptr.h:27
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
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
In net/socket.c (0)
Location: include/linux/sockptr.h:27
Inline: True
```
```
In net/core/filter.c (ffffffff81e5cadf)
Location: include/linux/sockptr.h:27
Inline: True
Inline callers:
  - net/core/filter.c:sol_ipv6_sockopt
  - net/core/filter.c:sol_ipv6_sockopt
  - net/core/filter.c:sol_ipv6_sockopt
  - net/core/filter.c:sol_ip_sockopt
  - net/core/filter.c:sol_ip_sockopt
  - net/core/filter.c:sol_ip_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_socket_sockopt
  - net/core/filter.c:sol_socket_sockopt
  - net/core/filter.c:sol_socket_sockopt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efe2dd)
Location: include/linux/sockptr.h:27
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/mptcp/sockopt.c (ffffffff82089aa9)
Location: include/linux/sockptr.h:27
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
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
In io_uring/uring_cmd.c (ffffffff81819d5a)
Location: include/linux/sockptr.h:27
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd_sock
```
```
In net/socket.c (ffffffff81ebcda8)
Location: include/linux/sockptr.h:27
Inline: True
Inline callers:
  - net/socket.c:do_sock_setsockopt
```
```
In net/core/filter.c (ffffffff81f1becf)
Location: include/linux/sockptr.h:27
Inline: True
Inline callers:
  - net/core/filter.c:sol_ipv6_sockopt
  - net/core/filter.c:sol_ipv6_sockopt
  - net/core/filter.c:sol_ipv6_sockopt
  - net/core/filter.c:sol_ip_sockopt
  - net/core/filter.c:sol_ip_sockopt
  - net/core/filter.c:sol_ip_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_socket_sockopt
  - net/core/filter.c:sol_socket_sockopt
  - net/core/filter.c:sol_socket_sockopt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc24bd)
Location: include/linux/sockptr.h:27
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/mptcp/sockopt.c (ffffffff8215f596)
Location: include/linux/sockptr.h:27
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
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
