# Function: <code>__sk_mem_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817029f0)
Location: net/core/sock.c:2067
Inline: False
Direct callers:
  - net/core/sock.c:sock_queue_rcv_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
**Symbols:**

```
ffffffff817029f0-ffffffff81702e84: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81767ec0)
Location: net/core/sock.c:2125
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
**Symbols:**

```
ffffffff81767ec0-ffffffff81768203: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81795200)
Location: net/core/sock.c:2205
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
**Symbols:**

```
ffffffff81795200-ffffffff81795242: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b3910)
Location: net/core/sock.c:2364
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
**Symbols:**

```
ffffffff817b3910-ffffffff817b3952: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182bd40)
Location: net/core/sock.c:2404
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
**Symbols:**

```
ffffffff8182bd40-ffffffff8182bd82: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81875880)
Location: net/core/sock.c:2485
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:smap_tx_work
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
  - net/core/sock.c:sk_alloc_sg
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
**Symbols:**

```
ffffffff81875880-ffffffff818758c2: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818961c0)
Location: net/core/sock.c:2429
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff818961c0-ffffffff81896202: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e06c0)
Location: net/core/sock.c:2572
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff818e06c0-ffffffff818e0700: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81912890)
Location: net/core/sock.c:2587
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81912890-ffffffff819128d0: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e5dfd)
Location: net/core/sock.c:2695
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
Direct callers:
  - net/core/skmsg.c:sk_psock_skb_ingress
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/xfrm/espintcp.c:handle_nonesp
```
**Symbols:**

```
ffffffff819e46e0-ffffffff819e4720: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e58d1)
Location: net/core/sock.c:2687
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/xfrm/espintcp.c:handle_nonesp
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_wmem_reserve
  - net/mptcp/protocol.c:__mptcp_wmem_reserve
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
```
**Symbols:**

```
ffffffff819e3f50-ffffffff819e3f90: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819cb9e1)
Location: net/core/sock.c:2710
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/xfrm/espintcp.c:handle_nonesp
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
```
**Symbols:**

```
ffffffff819c9fd0-ffffffff819ca012: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7b0a1)
Location: net/core/sock.c:2841
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
```
**Symbols:**

```
ffffffff81a79510-ffffffff81a79552: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bee6ba)
Location: net/core/sock.c:3004
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/xfrm/espintcp.c:handle_nonesp
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
**Symbols:**

```
ffffffff81bed990-ffffffff81bed9de: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9e17a)
Location: net/core/sock.c:3085
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/xfrm/espintcp.c:handle_nonesp
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
**Symbols:**

```
ffffffff81d9dfd0-ffffffff81d9e01d: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0c9f3)
Location: net/core/sock.c:3146
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/xfrm/espintcp.c:handle_nonesp
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
**Symbols:**

```
ffffffff81e0c840-ffffffff81e0c88d: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec936b)
Location: net/core/sock.c:3156
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/xfrm/espintcp.c:handle_nonesp
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
**Symbols:**

```
ffffffff81ec91a0-ffffffff81ec91ff: __sk_mem_schedule (STB_GLOBAL)
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
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010bacee0)
Location: net/core/sock.c:2587
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffff800010bacee0-ffff800010bacf4c: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc8aa4)
Location: net/core/sock.c:2587
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
c0cc8aa4-c0cc8af8: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c7fde0)
Location: net/core/sock.c:2587
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
c000000000c7fde0-c000000000c7fe54: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073d7bc)
Location: net/core/sock.c:2587
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffe00073d7bc-ffffffe00073d822: __sk_mem_schedule (STB_GLOBAL)
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
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b2890)
Location: net/core/sock.c:2587
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff818b2890-ffffffff818b28d0: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186c7e0)
Location: net/core/sock.c:2587
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff8186c7e0-ffffffff8186c820: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81903890)
Location: net/core/sock.c:2587
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81903890-ffffffff819038d0: __sk_mem_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock *sk, int size, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81924890)
Location: net/core/sock.c:2587
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81924890-ffffffff819248d0: __sk_mem_schedule (STB_GLOBAL)
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
