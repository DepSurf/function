# Function: <code>sk_set_socket</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81700d7e)
Location: include/net/sock.h:1651
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff8174df28)
Location: include/net/sock.h:1651
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81764a7f)
Location: include/net/sock.h:1651
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff8176a318)
Location: include/net/sock.h:1651
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff8179394d)
Location: include/net/sock.h:1651
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff817bde59)
Location: include/net/sock.h:1651
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81805a63)
Location: include/net/sock.h:1651
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8176ab52)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff817ba0db)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d0fef)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff817d6d88)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff8180115d)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff8182adc9)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81876627)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81797c72)
Location: include/net/sock.h:1668
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff817e9afd)
Location: include/net/sock.h:1668
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800eaf)
Location: include/net/sock.h:1668
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81806da8)
Location: include/net/sock.h:1668
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff818326bd)
Location: include/net/sock.h:1668
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff8185c849)
Location: include/net/sock.h:1668
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff818aaba2)
Location: include/net/sock.h:1668
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b5832)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff8180972e)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820c0f)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff8182748d)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff818539de)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81880fd9)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff818d1640)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182dcfb)
Location: include/net/sock.h:1686
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff81888682)
Location: include/net/sock.h:1686
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189fc05)
Location: include/net/sock.h:1686
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff818a6299)
Location: include/net/sock.h:1686
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff818d3864)
Location: include/net/sock.h:1686
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81902169)
Location: include/net/sock.h:1686
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81956599)
Location: include/net/sock.h:1686
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818780c9)
Location: include/net/sock.h:1697
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff818dc0a5)
Location: include/net/sock.h:1697
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f4c63)
Location: include/net/sock.h:1697
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff818fb307)
Location: include/net/sock.h:1697
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff81929d34)
Location: include/net/sock.h:1697
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81959ace)
Location: include/net/sock.h:1697
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff819b19d5)
Location: include/net/sock.h:1697
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff819cbffc)
Location: include/net/sock.h:1697
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818985a9)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff81908a72)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922163)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81929257)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff81959329)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff8198ea33)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff819e8db5)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a0522e)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e2b5d)
Location: include/net/sock.h:1794
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff81969e9e)
Location: include/net/sock.h:1794
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81985245)
Location: include/net/sock.h:1794
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff8198c17d)
Location: include/net/sock.h:1794
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff819bddfa)
Location: include/net/sock.h:1794
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff819fa19d)
Location: include/net/sock.h:1794
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a590f0)
Location: include/net/sock.h:1794
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a7486d)
Location: include/net/sock.h:1794
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81914d3d)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff819a090e)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bb335)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff819c2acd)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff819f4a0a)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81a30e19)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a8f200)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81aab2b0)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e6cdd)
Location: include/net/sock.h:1854
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff81a7a08e)
Location: include/net/sock.h:1854
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6235)
Location: include/net/sock.h:1854
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81aae0b1)
Location: include/net/sock.h:1854
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff81ae2735)
Location: include/net/sock.h:1854
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81b25242)
Location: include/net/sock.h:1854
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81b8b5f6)
Location: include/net/sock.h:1854
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba76f1)
Location: include/net/sock.h:1854
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81babf7b)
Location: include/net/sock.h:1854
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
```
```
In net/mptcp/subflow.c (ffffffff81bade48)
Location: include/net/sock.h:1854
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e650d)
Location: include/net/sock.h:1866
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff81a82eee)
Location: include/net/sock.h:1866
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0885)
Location: include/net/sock.h:1866
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81ab8334)
Location: include/net/sock.h:1866
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff81aef5d5)
Location: include/net/sock.h:1866
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81b33db2)
Location: include/net/sock.h:1866
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81b9a5c0)
Location: include/net/sock.h:1866
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81bb65d4)
Location: include/net/sock.h:1866
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81bbe484)
Location: include/net/sock.h:1866
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81bc0ec3)
Location: include/net/sock.h:1866
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_sock_destruct
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
In net/core/sock.c (ffffffff819cbf3d)
Location: include/net/sock.h:1882
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff81a6bfbe)
Location: include/net/sock.h:1882
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ba65)
Location: include/net/sock.h:1882
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81aa362e)
Location: include/net/sock.h:1882
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff81adad25)
Location: include/net/sock.h:1882
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81b21a92)
Location: include/net/sock.h:1882
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81b8952f)
Location: include/net/sock.h:1882
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba5594)
Location: include/net/sock.h:1882
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81badc1e)
Location: include/net/sock.h:1882
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81bb0fc3)
Location: include/net/sock.h:1882
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_sock_destruct
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
In net/core/sock.c (ffffffff81a7b59d)
Location: include/net/sock.h:1922
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff81b255cc)
Location: include/net/sock.h:1922
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57085)
Location: include/net/sock.h:1922
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81b5f7ce)
Location: include/net/sock.h:1922
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff81b99fa0)
Location: include/net/sock.h:1922
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81be6ab2)
Location: include/net/sock.h:1922
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81c5563f)
Location: include/net/sock.h:1922
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81c7311c)
Location: include/net/sock.h:1922
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81c7a65b)
Location: include/net/sock.h:1922
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81c7f0b0)
Location: include/net/sock.h:1922
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_sock_destruct
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
In net/core/sock.c (ffffffff81befe89)
Location: include/net/sock.h:2043
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff81cae0f3)
Location: include/net/sock.h:2043
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce4ff3)
Location: include/net/sock.h:2043
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81cee285)
Location: include/net/sock.h:2043
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff81d2bfa0)
Location: include/net/sock.h:2043
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81d7cc59)
Location: include/net/sock.h:2043
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81df53ce)
Location: include/net/sock.h:2043
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81e16e80)
Location: include/net/sock.h:2043
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81e1ed3b)
Location: include/net/sock.h:2043
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81e2498c)
Location: include/net/sock.h:2043
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
```
In net/mctp/af_mctp.c (ffffffff81e37a3f)
Location: include/net/sock.h:2043
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
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
In net/core/sock.c (ffffffff81d9c429)
Location: include/net/sock.h:2080
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff81e6b6c3)
Location: include/net/sock.h:2080
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea7c43)
Location: include/net/sock.h:2080
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81eb14e5)
Location: include/net/sock.h:2080
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff81ef3b81)
Location: include/net/sock.h:2080
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81f49d79)
Location: include/net/sock.h:2080
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81fc7d4e)
Location: include/net/sock.h:2080
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81fee850)
Location: include/net/sock.h:2080
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81ff56c7)
Location: include/net/sock.h:2080
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mctp/af_mctp.c (ffffffff82010c9a)
Location: include/net/sock.h:2080
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
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
In net/core/sock.c (ffffffff81e0ac79)
Location: include/net/sock.h:2067
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff81ec7703)
Location: include/net/sock.h:2067
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06483)
Location: include/net/sock.h:2067
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81f0fb75)
Location: include/net/sock.h:2067
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff81f559ab)
Location: include/net/sock.h:2067
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_accept
```
```
In net/unix/af_unix.c (ffffffff81fa9a18)
Location: include/net/sock.h:2067
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff82028cf2)
Location: include/net/sock.h:2067
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8206a960)
Location: include/net/sock.h:2067
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff82076370)
Location: include/net/sock.h:2067
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:__mptcp_close
```
```
In net/mctp/af_mctp.c (ffffffff8208d50a)
Location: include/net/sock.h:2067
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
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
In net/core/sock.c (ffffffff81ec7669)
Location: include/net/sock.h:2057
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff81f8aa43)
Location: include/net/sock.h:2057
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fca773)
Location: include/net/sock.h:2057
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81fd3d65)
Location: include/net/sock.h:2057
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff8201be8b)
Location: include/net/sock.h:2057
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_accept
```
```
In net/unix/af_unix.c (ffffffff82076e28)
Location: include/net/sock.h:2057
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff820f8732)
Location: include/net/sock.h:2057
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8213e591)
Location: include/net/sock.h:2057
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff8214abd6)
Location: include/net/sock.h:2057
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:__mptcp_close
```
```
In net/mctp/af_mctp.c (ffffffff821639ca)
Location: include/net/sock.h:2057
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010bada88)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffff800010c4f088)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6c944)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffff800010c758cc)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/af_inet.c (ffff800010caa920)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffff800010cf15dc)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffff800010d5c440)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffff800010d7f224)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0ccb610)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (c0d5f1e8)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (c0d7be4c)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (c0d83f80)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/af_inet.c (c0db722c)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (c0df7748)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (c0e5c45c)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c0e79368)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c833bc)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (c000000000d4d798)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72c40)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (c000000000d7d0ac)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/af_inet.c (c000000000dc0ac0)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (c000000000e14578)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (c000000000e97f20)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c000000000ebf45c)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073fc88)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffe0007bad1c)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2288)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffe0007d8a74)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/af_inet.c (ffffffe00080567e)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffe00083d740)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffe0008925cc)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffe0008ac316)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b4d3d)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff8194077e)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195b1a5)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff8196293d)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff819947aa)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff819d04a9)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a2e890)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a4a640)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186ec8d)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff818fa26e)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914c95)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff8191c42d)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff8194e26a)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff8198d269)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff819eba80)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a07230)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81905d3d)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff8199190e)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c5975)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff819cd10d)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff819ff04a)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81a3af29)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a9a440)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ab64f0)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81926d6d)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
```
```
In net/netlink/af_netlink.c (ffffffff819b43fe)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cf455)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff819d6c9d)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/af_inet.c (ffffffff81a0911a)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81a45d89)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81aa7182)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ac2610)
Location: include/net/sock.h:1804
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
</ul>

## Differences
