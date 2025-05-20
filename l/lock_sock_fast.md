# Function: <code>lock_sock_fast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81701990)
Location: net/core/sock.c:2481
Inline: True
Direct callers:
  - net/core/datagram.c:skb_free_datagram_locked
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:first_packet_length
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81701990-ffffffff817019fb: lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81768c30)
Location: net/core/sock.c:2549
Inline: True
Direct callers:
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:first_packet_length
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81768c30-ffffffff81768c9b: lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81795b40)
Location: net/core/sock.c:2576
Inline: True
Direct callers:
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
ffffffff81795b40-ffffffff81795bab: lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b3da0)
Location: net/core/sock.c:2743
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
**Symbols:**

```
ffffffff817b3da0-ffffffff817b3e0b: lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182bfe0)
Location: net/core/sock.c:2804
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
**Symbols:**

```
ffffffff8182bfe0-ffffffff8182c04b: lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818778e0)
Location: net/core/sock.c:2879
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
**Symbols:**

```
ffffffff818778e0-ffffffff8187794b: lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81897dd0)
Location: net/core/sock.c:2828
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
**Symbols:**

```
ffffffff81897dd0-ffffffff81897e3b: lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e22f0)
Location: net/core/sock.c:2971
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
ffffffff818e22f0-ffffffff818e235b: lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819144a0)
Location: net/core/sock.c:2986
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
ffffffff819144a0-ffffffff8191450b: lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e5a50)
Location: net/core/sock.c:3115
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
ffffffff819e5a50-ffffffff819e5abb: lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e7c00)
Location: net/core/sock.c:3094
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:skb_consume_udp
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
```
**Symbols:**

```
ffffffff819e7c00-ffffffff819e7c6b: lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819cdbd0)
Location: net/core/sock.c:3117
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:skb_consume_udp
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_all
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
**Symbols:**

```
ffffffff819cdbd0-ffffffff819cdc3b: lock_sock_fast (STB_GLOBAL)
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
In net/core/datagram.c (ffffffff81a8b07c)
Location: include/net/sock.h:1649
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81b599dc)
Location: include/net/sock.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7a1d7)
Location: include/net/sock.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
```
```
In net/ipv4/udp.c (ffffffff81b8899f)
Location: include/net/sock.h:1649
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/mptcp/protocol.c (ffffffff81c7e2c3)
Location: include/net/sock.h:1649
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_subflow_send_ack
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8b0ec)
Location: include/net/sock.h:1649
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
```
```
In net/mptcp/sockopt.c (ffffffff81c8ca37)
Location: include/net/sock.h:1649
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
In net/core/datagram.c (ffffffff81c007f1)
Location: include/net/sock.h:1738
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81ce771d)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0a36f)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
```
```
In net/ipv4/udp.c (ffffffff81d19e5f)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/unix/af_unix.c (ffffffff81d7c9ab)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
```
```
In net/mptcp/protocol.c (ffffffff81e20a6c)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
```
```
In net/mptcp/pm_netlink.c (ffffffff81e3155a)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
```
```
In net/mptcp/sockopt.c (ffffffff81e35052)
Location: include/net/sock.h:1738
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
In net/core/datagram.c (ffffffff81dafb1d)
Location: include/net/sock.h:1754
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81eaafad)
Location: include/net/sock.h:1754
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecfbef)
Location: include/net/sock.h:1754
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
```
```
In net/ipv4/udp.c (ffffffff81ee0a3f)
Location: include/net/sock.h:1754
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/unix/af_unix.c (ffffffff81f49a2b)
Location: include/net/sock.h:1754
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
```
```
In net/mptcp/protocol.c (ffffffff81ff7efc)
Location: include/net/sock.h:1754
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
```
```
In net/mptcp/pm_netlink.c (ffffffff82009b6a)
Location: include/net/sock.h:1754
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
```
```
In net/mptcp/sockopt.c (ffffffff8200dcc2)
Location: include/net/sock.h:1754
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
In net/core/datagram.c (ffffffff81e1fd8d)
Location: include/net/sock.h:1745
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81f096bd)
Location: include/net/sock.h:1745
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff81f3fcbf)
Location: include/net/sock.h:1745
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/unix/af_unix.c (ffffffff81fa968b)
Location: include/net/sock.h:1745
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
```
```
In net/mptcp/protocol.c (ffffffff82074361)
Location: include/net/sock.h:1745
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_send_ack
```
```
In net/mptcp/pm_netlink.c (ffffffff82085e74)
Location: include/net/sock.h:1745
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
```
```
In net/mptcp/sockopt.c (ffffffff8208a6b2)
Location: include/net/sock.h:1745
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
In net/core/datagram.c (ffffffff81edd43d)
Location: include/net/sock.h:1720
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81fcd96d)
Location: include/net/sock.h:1720
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/udp.c (ffffffff8200597f)
Location: include/net/sock.h:1720
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
```
```
In net/unix/af_unix.c (ffffffff82076b1b)
Location: include/net/sock.h:1720
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
```
```
In net/mptcp/protocol.c (ffffffff82147ec1)
Location: include/net/sock.h:1720
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_send_ack
```
```
In net/mptcp/diag.c (ffffffff8215784e)
Location: include/net/sock.h:1720
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff8215b024)
Location: include/net/sock.h:1720
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
```
```
In net/mptcp/sockopt.c (ffffffff8216025b)
Location: include/net/sock.h:1720
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010bab7c8)
Location: net/core/sock.c:2986
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
ffff800010bab7c8-ffff800010bab888: lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc90a4)
Location: net/core/sock.c:2986
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
c0cc90a4-c0cc9114: lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c80a80)
Location: net/core/sock.c:2986
Inline: True
Direct callers:
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
c000000000c80a80-c000000000c80b60: lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073f448)
Location: net/core/sock.c:2986
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
ffffffe00073f448-ffffffe00073f4f4: lock_sock_fast (STB_GLOBAL)
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
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b44a0)
Location: net/core/sock.c:2986
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
ffffffff818b44a0-ffffffff818b450b: lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186e3f0)
Location: net/core/sock.c:2986
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
ffffffff8186e3f0-ffffffff8186e45b: lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819054a0)
Location: net/core/sock.c:2986
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
ffffffff819054a0-ffffffff8190550b: lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81924ea0)
Location: net/core/sock.c:2986
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
ffffffff81924ea0-ffffffff81924f04: lock_sock_fast (STB_GLOBAL)
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
