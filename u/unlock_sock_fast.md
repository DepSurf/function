# Function: <code>unlock_sock_fast</code>

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
In net/core/datagram.c (ffffffff8170d078)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/core/datagram.c:skb_free_datagram_locked
```
```
In net/ipv4/tcp.c (ffffffff81765aeb)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff81788170)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv6/udp.c (ffffffff817e2d4d)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/core/datagram.c (ffffffff8177469b)
Location: include/net/sock.h:1419
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_free_datagram_locked
```
```
In net/ipv4/tcp.c (ffffffff817d2014)
Location: include/net/sock.h:1419
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff817f5c5d)
Location: include/net/sock.h:1419
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv6/udp.c (ffffffff818511d2)
Location: include/net/sock.h:1419
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/core/datagram.c (ffffffff817a199b)
Location: include/net/sock.h:1475
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_free_datagram_locked
```
```
In net/ipv4/tcp.c (ffffffff818029ff)
Location: include/net/sock.h:1475
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff81824f17)
Location: include/net/sock.h:1475
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
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
In net/core/datagram.c (ffffffff817bfee8)
Location: include/net/sock.h:1478
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81822dc4)
Location: include/net/sock.h:1478
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff81847090)
Location: include/net/sock.h:1478
Inline: True
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
In net/core/datagram.c (ffffffff81839a9b)
Location: include/net/sock.h:1482
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818a1ee4)
Location: include/net/sock.h:1482
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff818c6af0)
Location: include/net/sock.h:1482
Inline: True
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
In net/core/datagram.c (ffffffff818841db)
Location: include/net/sock.h:1495
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818f9838)
Location: include/net/sock.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff8191c50f)
Location: include/net/sock.h:1495
Inline: True
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
In net/core/datagram.c (ffffffff818a465b)
Location: include/net/sock.h:1534
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81927768)
Location: include/net/sock.h:1534
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff8194aadf)
Location: include/net/sock.h:1534
Inline: True
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
In net/core/datagram.c (ffffffff818efddb)
Location: include/net/sock.h:1544
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819889d8)
Location: include/net/sock.h:1544
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff819af124)
Location: include/net/sock.h:1544
Inline: True
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
In net/core/datagram.c (ffffffff81921dfb)
Location: include/net/sock.h:1554
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819bfe28)
Location: include/net/sock.h:1554
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff819e5e34)
Location: include/net/sock.h:1554
Inline: True
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
In net/core/datagram.c (ffffffff819f4e80)
Location: include/net/sock.h:1603
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81aa8cb7)
Location: include/net/sock.h:1603
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff81ad2ca1)
Location: include/net/sock.h:1603
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:skb_consume_udp
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
In net/core/datagram.c (ffffffff819f47b0)
Location: include/net/sock.h:1618
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81ab3166)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff81adf0e1)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/mptcp/protocol.c (ffffffff81bbe4ae)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
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
In net/core/datagram.c (ffffffff819daa5b)
Location: include/net/sock.h:1634
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81a9e3c3)
Location: include/net/sock.h:1634
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff81aca137)
Location: include/net/sock.h:1634
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/mptcp/protocol.c (ffffffff81baff5b)
Location: include/net/sock.h:1634
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_send_ack
```
```
In net/mptcp/pm_netlink.c (ffffffff81bbae56)
Location: include/net/sock.h:1634
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
```
```
In net/mptcp/sockopt.c (ffffffff81bbcbed)
Location: include/net/sock.h:1634
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_all
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In net/core/datagram.c (ffffffff81a8b0db)
Location: include/net/sock.h:1673
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81b59a03)
Location: include/net/sock.h:1673
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7a1e7)
Location: include/net/sock.h:1673
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
```
```
In net/ipv4/udp.c (ffffffff81b889b7)
Location: include/net/sock.h:1673
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/mptcp/protocol.c (ffffffff81c7dd7d)
Location: include/net/sock.h:1673
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_subflow_send_ack
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8b128)
Location: include/net/sock.h:1673
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
```
```
In net/mptcp/sockopt.c (ffffffff81c8ca4d)
Location: include/net/sock.h:1673
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_all
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In net/core/datagram.c (ffffffff81c00860)
Location: include/net/sock.h:1762
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81ce7a60)
Location: include/net/sock.h:1762
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0a37f)
Location: include/net/sock.h:1762
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
```
```
In net/ipv4/udp.c (ffffffff81d19e77)
Location: include/net/sock.h:1762
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/unix/af_unix.c (ffffffff81d7ca24)
Location: include/net/sock.h:1762
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
```
```
In net/mptcp/protocol.c (ffffffff81e20a86)
Location: include/net/sock.h:1762
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
```
```
In net/mptcp/subflow.c (ffffffff81e28819)
Location: include/net/sock.h:1762
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
```
```
In net/mptcp/pm_netlink.c (ffffffff81e31595)
Location: include/net/sock.h:1762
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
```
```
In net/mptcp/sockopt.c (ffffffff81e35065)
Location: include/net/sock.h:1762
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In net/core/datagram.c (ffffffff81dafb5c)
Location: include/net/sock.h:1778
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81eab315)
Location: include/net/sock.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecfbff)
Location: include/net/sock.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
```
```
In net/ipv4/udp.c (ffffffff81ee0a57)
Location: include/net/sock.h:1778
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/unix/af_unix.c (ffffffff81f49aa4)
Location: include/net/sock.h:1778
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
```
```
In net/mptcp/protocol.c (ffffffff81ff7f16)
Location: include/net/sock.h:1778
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
```
```
In net/mptcp/pm_netlink.c (ffffffff82009ba5)
Location: include/net/sock.h:1778
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
```
```
In net/mptcp/sockopt.c (ffffffff8200dcd5)
Location: include/net/sock.h:1778
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In net/core/datagram.c (ffffffff81e1fdcc)
Location: include/net/sock.h:1769
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81f09a25)
Location: include/net/sock.h:1769
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff81f3fcd7)
Location: include/net/sock.h:1769
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/unix/af_unix.c (ffffffff81fa9701)
Location: include/net/sock.h:1769
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
```
```
In net/mptcp/protocol.c (ffffffff8207437c)
Location: include/net/sock.h:1769
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_send_ack
```
```
In net/mptcp/pm_netlink.c (ffffffff82085eb0)
Location: include/net/sock.h:1769
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
```
```
In net/mptcp/sockopt.c (ffffffff8208a6c5)
Location: include/net/sock.h:1769
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In net/core/datagram.c (ffffffff81edd47c)
Location: include/net/sock.h:1744
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81fcdd35)
Location: include/net/sock.h:1744
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff82005997)
Location: include/net/sock.h:1744
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
```
```
In net/unix/af_unix.c (ffffffff82076b91)
Location: include/net/sock.h:1744
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
```
```
In net/mptcp/protocol.c (ffffffff82147edc)
Location: include/net/sock.h:1744
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_send_ack
```
```
In net/mptcp/diag.c (ffffffff82157909)
Location: include/net/sock.h:1744
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff8215b060)
Location: include/net/sock.h:1744
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
```
```
In net/mptcp/sockopt.c (ffffffff82160271)
Location: include/net/sock.h:1744
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_set_rcvlowat
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In net/core/datagram.c (ffff800010bbc494)
Location: include/net/sock.h:1554
Inline: True
```
```
In net/ipv4/tcp.c (ffff800010c71488)
Location: include/net/sock.h:1554
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffff800010c995c0)
Location: include/net/sock.h:1554
Inline: True
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
In net/core/datagram.c (c0cd89f0)
Location: include/net/sock.h:1554
Inline: True
```
```
In net/ipv4/tcp.c (c0d7f388)
Location: include/net/sock.h:1554
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (c0da8314)
Location: include/net/sock.h:1554
Inline: True
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
In net/core/datagram.c (c000000000c94868)
Location: include/net/sock.h:1554
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_free_datagram_locked
```
```
In net/ipv4/tcp.c (c000000000d772f0)
Location: include/net/sock.h:1554
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (c000000000dab240)
Location: include/net/sock.h:1554
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
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
In net/core/datagram.c (ffffffe00074b190)
Location: include/net/sock.h:1554
Inline: True
```
```
In net/ipv4/tcp.c (ffffffe0007d5da0)
Location: include/net/sock.h:1554
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffe0007f71bc)
Location: include/net/sock.h:1554
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
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
In net/core/datagram.c (ffffffff818c1dfb)
Location: include/net/sock.h:1554
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8195fc98)
Location: include/net/sock.h:1554
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff81985ca4)
Location: include/net/sock.h:1554
Inline: True
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
In net/core/datagram.c (ffffffff8187bd3b)
Location: include/net/sock.h:1554
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81919788)
Location: include/net/sock.h:1554
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff8193f764)
Location: include/net/sock.h:1554
Inline: True
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
In net/core/datagram.c (ffffffff81912dfb)
Location: include/net/sock.h:1554
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819ca468)
Location: include/net/sock.h:1554
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff819f0474)
Location: include/net/sock.h:1554
Inline: True
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
In net/core/datagram.c (ffffffff81933f7b)
Location: include/net/sock.h:1554
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819d3fd8)
Location: include/net/sock.h:1554
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff819fadf4)
Location: include/net/sock.h:1554
Inline: True
```
</details>
</li>
</ul>

## Differences
