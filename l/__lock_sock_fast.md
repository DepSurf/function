# Function: <code>__lock_sock_fast</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7d3c0)
Location: net/core/sock.c:3235
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:skb_consume_udp
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_subflow_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_all
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
**Symbols:**

```
ffffffff81a7d3c0-ffffffff81a7d418: __lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bf0a10)
Location: net/core/sock.c:3421
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:skb_consume_udp
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
**Symbols:**

```
ffffffff81bf0a10-ffffffff81bf0a74: __lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9cff0)
Location: net/core/sock.c:3510
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:skb_consume_udp
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
**Symbols:**

```
ffffffff81d9cff0-ffffffff81d9d054: __lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0b840)
Location: net/core/sock.c:3543
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:skb_consume_udp
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
**Symbols:**

```
ffffffff81e0b840-ffffffff81e0b8a4: __lock_sock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __lock_sock_fast(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec8230)
Location: net/core/sock.c:3551
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/udp.c:udp_destroy_sock
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_send_ack
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
  - net/mptcp/sockopt.c:mptcp_set_rcvlowat
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
**Symbols:**

```
ffffffff81ec8230-ffffffff81ec8294: __lock_sock_fast (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
