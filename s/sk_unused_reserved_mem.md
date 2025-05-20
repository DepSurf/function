# Function: <code>sk_unused_reserved_mem</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bed86d)
Location: include/net/sock.h:1603
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff81c01132)
Location: include/net/sock.h:1603
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (0)
Location: include/net/sock.h:1603
Inline: True
```
```
In net/core/filter.c (ffffffff81c4491b)
Location: include/net/sock.h:1603
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
```
```
In net/core/skmsg.c (ffffffff81c8c053)
Location: include/net/sock.h:1603
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
```
```
In net/ipv4/tcp.c (ffffffff81cee6d8)
Location: include/net/sock.h:1603
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81cf3539)
Location: include/net/sock.h:1603
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81d050b7)
Location: include/net/sock.h:1603
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_trim_head
```
```
In net/ipv4/tcp_timer.c (ffffffff81d06455)
Location: include/net/sock.h:1603
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/sock.h:1603
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5c295)
Location: include/net/sock.h:1603
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81d7b363)
Location: include/net/sock.h:1603
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff81e1b92d)
Location: include/net/sock.h:1603
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:dfrag_clear
  - net/mptcp/protocol.c:__mptcp_mem_reclaim_partial
  - net/mptcp/protocol.c:__mptcp_mem_reclaim_partial
  - net/mptcp/protocol.c:mptcp_rfree
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
In net/core/sock.c (ffffffff81d9de7e)
Location: include/net/sock.h:1649
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (0)
Location: include/net/sock.h:1649
Inline: True
```
```
In net/core/filter.c (ffffffff81dfeed0)
Location: include/net/sock.h:1649
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
```
```
In net/core/skmsg.c (ffffffff81e471e2)
Location: include/net/sock.h:1649
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
```
```
In net/ipv4/tcp.c (ffffffff81eb18b1)
Location: include/net/sock.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81eb864a)
Location: include/net/sock.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81eca10d)
Location: include/net/sock.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_trim_head
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/sock.h:1649
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f2641c)
Location: include/net/sock.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81f483d4)
Location: include/net/sock.h:1649
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff81ff2eed)
Location: include/net/sock.h:1649
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:dfrag_clear
  - net/mptcp/protocol.c:mptcp_rfree
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
In net/core/sock.c (ffffffff81e0c71a)
Location: include/net/sock.h:1640
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (0)
Location: include/net/sock.h:1640
Inline: True
```
```
In net/core/filter.c (ffffffff81e709a0)
Location: include/net/sock.h:1640
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
```
```
In net/core/skmsg.c (ffffffff81ea2c75)
Location: include/net/sock.h:1640
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
```
```
In net/ipv4/tcp.c (ffffffff81f0ffbc)
Location: include/net/sock.h:1640
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81f16aba)
Location: include/net/sock.h:1640
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81f28c5d)
Location: include/net/sock.h:1640
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_trim_head
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/sock.h:1640
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f86099)
Location: include/net/sock.h:1640
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81fa7f8a)
Location: include/net/sock.h:1640
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff8206f16d)
Location: include/net/sock.h:1640
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:dfrag_clear
  - net/mptcp/protocol.c:mptcp_rfree
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
In net/core/sock.c (ffffffff81ec90d5)
Location: include/net/sock.h:1615
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (0)
Location: include/net/sock.h:1615
Inline: True
```
```
In net/core/filter.c (ffffffff81f30030)
Location: include/net/sock.h:1615
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
```
```
In net/core/skmsg.c (ffffffff81f64fa5)
Location: include/net/sock.h:1615
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
```
```
In net/ipv4/tcp.c (ffffffff81fd4f41)
Location: include/net/sock.h:1615
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_window_clamp
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81fdb92a)
Location: include/net/sock.h:1615
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81fed6fd)
Location: include/net/sock.h:1615
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_trim_head
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/sock.h:1615
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204d679)
Location: include/net/sock.h:1615
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff8207524a)
Location: include/net/sock.h:1615
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff8214326d)
Location: include/net/sock.h:1615
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:dfrag_clear
  - net/mptcp/protocol.c:mptcp_rfree
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
