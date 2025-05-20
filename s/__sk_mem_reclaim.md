# Function: <code>__sk_mem_reclaim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81702870)
Location: net/core/sock.c:2150
Inline: True
Direct callers:
  - net/core/sock.c:sk_clear_memalloc
  - net/core/datagram.c:skb_free_datagram_locked
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/af_inet.c:inet_sock_destruct
```
**Symbols:**

```
ffffffff81702870-ffffffff817029a0: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81769ae0)
Location: net/core/sock.c:2211
Inline: True
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/core/datagram.c:skb_free_datagram
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/af_inet.c:inet_sock_destruct
```
**Symbols:**

```
ffffffff81769ae0-ffffffff81769bc6: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81796b9b)
Location: net/core/sock.c:2242
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/core/datagram.c:skb_free_datagram
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/af_inet.c:inet_sock_destruct
```
**Symbols:**

```
ffffffff81796ae0-ffffffff81796b00: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b4f9b)
Location: net/core/sock.c:2401
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/stream.c:sk_stream_kill_queues
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/af_inet.c:inet_sock_destruct
```
**Symbols:**

```
ffffffff817b4ed0-ffffffff817b4ef0: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182d3ce)
Location: net/core/sock.c:2441
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/stream.c:sk_stream_kill_queues
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/af_inet.c:inet_sock_destruct
```
**Symbols:**

```
ffffffff8182d300-ffffffff8182d320: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818771ae)
Location: net/core/sock.c:2522
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
  - kernel/bpf/sockmap.c:free_sg
  - kernel/bpf/sockmap.c:free_bytes_sg
  - kernel/bpf/sockmap.c:free_bytes_sg
  - kernel/bpf/sockmap.c:bpf_tcp_push
  - kernel/bpf/sockmap.c:bpf_tcp_push
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/stream.c:sk_stream_kill_queues
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/af_inet.c:inet_sock_destruct
```
**Symbols:**

```
ffffffff818770e0-ffffffff81877100: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8189794e)
Location: net/core/sock.c:2466
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81897880-ffffffff818978a0: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e1e5b)
Location: net/core/sock.c:2609
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff818e1d90-ffffffff818e1db0: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8191402b)
Location: net/core/sock.c:2624
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81913f60-ffffffff81913f80: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e5c0b)
Location: net/core/sock.c:2732
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/mptcp/protocol.c:__mptcp_clear_xmit
  - net/mptcp/protocol.c:mptcp_clean_una
  - net/mptcp/protocol.c:mptcp_clean_una
```
**Symbols:**

```
ffffffff819e5bb0-ffffffff819e5bd0: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e56db)
Location: net/core/sock.c:2724
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/mptcp/protocol.c:__mptcp_clear_xmit
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_move_skb
```
**Symbols:**

```
ffffffff819e5680-ffffffff819e56a0: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819cb7eb)
Location: net/core/sock.c:2747
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/mptcp/protocol.c:__mptcp_clear_xmit
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
```
**Symbols:**

```
ffffffff819cb790-ffffffff819cb7b0: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7ae7b)
Location: net/core/sock.c:2878
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
```
**Symbols:**

```
ffffffff81a7ae20-ffffffff81a7ae40: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81beedd3)
Location: net/core/sock.c:3041
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:dfrag_clear
  - net/mptcp/protocol.c:__mptcp_mem_reclaim_partial
```
**Symbols:**

```
ffffffff81beed50-ffffffff81beed7a: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9e540)
Location: net/core/sock.c:3121
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:dfrag_clear
```
**Symbols:**

```
ffffffff81d9e4a0-ffffffff81d9e4ca: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0cd50)
Location: net/core/sock.c:3182
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:dfrag_clear
```
**Symbols:**

```
ffffffff81e0ccb0-ffffffff81e0ccda: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec96e0)
Location: net/core/sock.c:3192
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:dfrag_clear
```
**Symbols:**

```
ffffffff81ec9630-ffffffff81ec9665: __sk_mem_reclaim (STB_GLOBAL)
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
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010babd84)
Location: net/core/sock.c:2624
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffff800010babc48-ffff800010babc8c: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cca95c)
Location: net/core/sock.c:2624
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
c0cca7ec-c0cca820: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c82334)
Location: net/core/sock.c:2624
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/core/datagram.c:skb_free_datagram
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
c000000000c82200-c000000000c82228: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073f390)
Location: net/core/sock.c:2624
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffe00073f25e-ffffffe00073f2a2: __sk_mem_reclaim (STB_GLOBAL)
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
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b402b)
Location: net/core/sock.c:2624
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff818b3f60-ffffffff818b3f80: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186df7b)
Location: net/core/sock.c:2624
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff8186deb0-ffffffff8186ded0: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8190502b)
Location: net/core/sock.c:2624
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81904f60-ffffffff81904f80: __sk_mem_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reclaim(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819260fb)
Location: net/core/sock.c:2624
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81926030-ffffffff81926050: __sk_mem_reclaim (STB_GLOBAL)
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
