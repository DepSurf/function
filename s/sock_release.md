# Function: <code>sock_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fcb00)
Location: net/socket.c:567
Inline: False
Direct callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:__sock_create
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_accept4
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/icmp.c:icmpv6_sk_init
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
**Symbols:**

```
ffffffff816fcb00-ffffffff816fcb75: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81763800)
Location: net/socket.c:568
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/icmp.c:icmpv6_sk_init
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
**Symbols:**

```
ffffffff81763800-ffffffff81763875: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817907f0)
Location: net/socket.c:594
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/icmp.c:icmpv6_sk_init
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
**Symbols:**

```
ffffffff817907f0-ffffffff81790865: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ade60)
Location: net/socket.c:592
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
**Symbols:**

```
ffffffff817ade60-ffffffff817aded8: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81825d70)
Location: net/socket.c:597
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SYSC_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_map_fd
  - net/socket.c:sock_alloc_file
  - net/socket.c:sock_alloc_file
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
**Symbols:**

```
ffffffff81825d70-ffffffff81825dee: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818700b7)
Location: net/socket.c:617
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
  - net/socket.c:sock_alloc_file
Direct callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
**Symbols:**

```
ffffffff8186f420-ffffffff8186f432: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81890c87)
Location: net/socket.c:597
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
**Symbols:**

```
ffffffff8188f8f0-ffffffff8188f902: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dab97)
Location: net/socket.c:608
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
**Symbols:**

```
ffffffff818d9950-ffffffff818d9962: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190cce7)
Location: net/socket.c:608
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
**Symbols:**

```
ffffffff8190b930-ffffffff8190b942: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff819dea57)
Location: net/socket.c:623
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_free
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff819e3266-ffffffff819e327e: sock_release.cold (STB_LOCAL)
ffffffff819e0960-ffffffff819e09ca: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff819de497)
Location: net/socket.c:623
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_free
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81c303ac-ffffffff81c303c4: sock_release.cold (STB_LOCAL)
ffffffff819e01b0-ffffffff819e021a: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff819c44a7)
Location: net/socket.c:625
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_free
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff81c2268a-ffffffff81c226a2: sock_release.cold (STB_LOCAL)
ffffffff819c6210-ffffffff819c627a: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff81a73517)
Location: net/socket.c:675
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_free
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff81d34a66-ffffffff81d34a7e: sock_release.cold (STB_LOCAL)
ffffffff81a74de0-ffffffff81a74e4a: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff81be6023)
Location: net/socket.c:676
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sys_socket_file
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_ring_ctx_free
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
**Symbols:**

```
ffffffff81f00f6b-ffffffff81f00f83: sock_release.cold (STB_LOCAL)
ffffffff81be7b10-ffffffff81be7b84: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d92263)
Location: net/socket.c:678
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_ring_ctx_free
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
**Symbols:**

```
ffffffff81d941a0-ffffffff81d94223: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e0061b)
Location: net/socket.c:683
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_ring_ctx_free
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
**Symbols:**

```
ffffffff81e027f0-ffffffff81e02873: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebcb7b)
Location: net/socket.c:685
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
**Symbols:**

```
ffffffff81ebf1f0-ffffffff81ebf273: sock_release (STB_GLOBAL)
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
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba1c30)
Location: net/socket.c:608
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
**Symbols:**

```
ffff800010ba0f08-ffff800010ba0f38: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc3c54)
Location: net/socket.c:608
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
**Symbols:**

```
c0cc32b4-c0cc32d4: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c76400)
Location: net/socket.c:608
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
**Symbols:**

```
c000000000c75090-c000000000c750a8: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe000739cf6)
Location: net/socket.c:608
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
**Symbols:**

```
ffffffe000738c38-ffffffe000738c64: sock_release (STB_GLOBAL)
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
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818acce7)
Location: net/socket.c:608
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
**Symbols:**

```
ffffffff818ab930-ffffffff818ab942: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81866c37)
Location: net/socket.c:608
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/udp_tunnel.c:udp_tunnel_sock_release
  - net/ipv4/udp_tunnel.c:udp_sock_create4
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
  - net/ipv6/ip6_udp_tunnel.c:udp_sock_create6
```
**Symbols:**

```
ffffffff81865880-ffffffff81865892: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fdce7)
Location: net/socket.c:608
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
**Symbols:**

```
ffffffff818fc930-ffffffff818fc942: sock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void sock_release(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191ed77)
Location: net/socket.c:608
Inline: True
Inline callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv6/ndisc.c:ndisc_net_exit
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
**Symbols:**

```
ffffffff8191d9a0-ffffffff8191d9b2: sock_release (STB_GLOBAL)
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
