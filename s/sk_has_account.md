# Function: <code>sk_has_account</code>

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
In net/core/sock.c (ffffffff817002ca)
Location: include/net/sock.h:1376
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sock.c:sock_queue_rcv_skb
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffff8170d059)
Location: include/net/sock.h:1376
Inline: True
Inline callers:
  - net/core/datagram.c:skb_free_datagram_locked
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/stream.c (ffffffff8170e1f2)
Location: include/net/sock.h:1376
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8174a3f6)
Location: include/net/sock.h:1376
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81765dca)
Location: include/net/sock.h:1376
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8176b1a5)
Location: include/net/sock.h:1376
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff817744af)
Location: include/net/sock.h:1376
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_timer.c (ffffffff81779b4a)
Location: include/net/sock.h:1376
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177c979)
Location: include/net/sock.h:1376
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81782b1a)
Location: include/net/sock.h:1376
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/udp.c (ffffffff817888c2)
Location: include/net/sock.h:1376
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/af_inet.c (ffffffff8179482d)
Location: include/net/sock.h:1376
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f0be8)
Location: include/net/sock.h:1376
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/packet/af_packet.c (ffffffff81806fe6)
Location: include/net/sock.h:1376
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81769c36)
Location: include/net/sock.h:1283
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff8177548d)
Location: include/net/sock.h:1283
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffffffff817758df)
Location: include/net/sock.h:1283
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817b7316)
Location: include/net/sock.h:1283
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff817d49d6)
Location: include/net/sock.h:1283
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff817d9b1a)
Location: include/net/sock.h:1283
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff817e135f)
Location: include/net/sock.h:1283
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffffffff817e6d1e)
Location: include/net/sock.h:1283
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea27f)
Location: include/net/sock.h:1283
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efca9)
Location: include/net/sock.h:1283
Inline: True
```
```
In net/ipv4/udp.c (ffffffff817f6212)
Location: include/net/sock.h:1283
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/af_inet.c (ffffffff8180217f)
Location: include/net/sock.h:1283
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185f7c2)
Location: include/net/sock.h:1283
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff8187a22a)
Location: include/net/sock.h:1283
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81796b76)
Location: include/net/sock.h:1339
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff817a2776)
Location: include/net/sock.h:1339
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffffffff817a2b5f)
Location: include/net/sock.h:1339
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817e6db6)
Location: include/net/sock.h:1339
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff8180472a)
Location: include/net/sock.h:1339
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff8180a4bc)
Location: include/net/sock.h:1339
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff8181182f)
Location: include/net/sock.h:1339
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffffffff8181745e)
Location: include/net/sock.h:1339
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818abc)
Location: include/net/sock.h:1339
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818206b9)
Location: include/net/sock.h:1339
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8183310f)
Location: include/net/sock.h:1339
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8189170a)
Location: include/net/sock.h:1339
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff818ab36b)
Location: include/net/sock.h:1339
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff817b4f76)
Location: include/net/sock.h:1342
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff817c0293)
Location: include/net/sock.h:1342
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffffffff817c0d2d)
Location: include/net/sock.h:1342
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/netlink/af_netlink.c (ffffffff81806769)
Location: include/net/sock.h:1342
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff8182499a)
Location: include/net/sock.h:1342
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff8182929c)
Location: include/net/sock.h:1342
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81831a9f)
Location: include/net/sock.h:1342
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffffffff818377fd)
Location: include/net/sock.h:1342
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183929b)
Location: include/net/sock.h:1342
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840bc9)
Location: include/net/sock.h:1342
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81854a7d)
Location: include/net/sock.h:1342
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b7d49)
Location: include/net/sock.h:1342
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff818d4632)
Location: include/net/sock.h:1342
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff8182d3aa)
Location: include/net/sock.h:1346
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff8183945c)
Location: include/net/sock.h:1346
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffffffff8183a74d)
Location: include/net/sock.h:1346
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/netlink/af_netlink.c (ffffffff81885439)
Location: include/net/sock.h:1346
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff818a65f8)
Location: include/net/sock.h:1346
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff818ae2d9)
Location: include/net/sock.h:1346
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff818b47fe)
Location: include/net/sock.h:1346
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffffffff818b6f42)
Location: include/net/sock.h:1346
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c033c)
Location: include/net/sock.h:1346
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff818d491d)
Location: include/net/sock.h:1346
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193abba)
Location: include/net/sock.h:1346
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81959099)
Location: include/net/sock.h:1346
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In kernel/bpf/sockmap.c (ffffffff811ccd77)
Location: include/net/sock.h:1361
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_tx_work
  - kernel/bpf/sockmap.c:smap_tx_work
  - kernel/bpf/sockmap.c:bpf_tcp_sendpage
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
  - kernel/bpf/sockmap.c:free_sg
  - kernel/bpf/sockmap.c:free_bytes_sg
  - kernel/bpf/sockmap.c:free_bytes_sg
  - kernel/bpf/sockmap.c:bpf_tcp_push
  - kernel/bpf/sockmap.c:bpf_tcp_push
```
```
In net/core/sock.c (ffffffff81877485)
Location: include/net/sock.h:1361
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc_sg
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff81883b96)
Location: include/net/sock.h:1361
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffffffff81884e8d)
Location: include/net/sock.h:1361
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/netlink/af_netlink.c (ffffffff818d8c63)
Location: include/net/sock.h:1361
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff818fb6a5)
Location: include/net/sock.h:1361
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81903994)
Location: include/net/sock.h:1361
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81909e48)
Location: include/net/sock.h:1361
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffffffff8190c71c)
Location: include/net/sock.h:1361
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81915e98)
Location: include/net/sock.h:1361
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8192aadd)
Location: include/net/sock.h:1361
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8199424f)
Location: include/net/sock.h:1361
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff819b2e02)
Location: include/net/sock.h:1361
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff8189792a)
Location: include/net/sock.h:1399
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff818a452d)
Location: include/net/sock.h:1399
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffffffff818a58fd)
Location: include/net/sock.h:1399
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffff818d942f)
Location: include/net/sock.h:1399
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff818e63f7)
Location: include/net/sock.h:1399
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81905453)
Location: include/net/sock.h:1399
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff819295f5)
Location: include/net/sock.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81931b51)
Location: include/net/sock.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff819380f9)
Location: include/net/sock.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffffffff8193ab70)
Location: include/net/sock.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8194463f)
Location: include/net/sock.h:1399
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81959ffd)
Location: include/net/sock.h:1399
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffff819777c1)
Location: include/net/sock.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cab71)
Location: include/net/sock.h:1399
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff819e9d60)
Location: include/net/sock.h:1399
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff818e1e39)
Location: include/net/sock.h:1402
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff818efb8b)
Location: include/net/sock.h:1402
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffffffff818f0c21)
Location: include/net/sock.h:1402
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffff8192b584)
Location: include/net/sock.h:1402
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81935d72)
Location: include/net/sock.h:1402
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8196686f)
Location: include/net/sock.h:1402
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff8198c525)
Location: include/net/sock.h:1402
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff8199524c)
Location: include/net/sock.h:1402
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff8199b553)
Location: include/net/sock.h:1402
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffffffff8199ef17)
Location: include/net/sock.h:1402
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a8c2f)
Location: include/net/sock.h:1402
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff819bec63)
Location: include/net/sock.h:1402
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e12e9)
Location: include/net/sock.h:1402
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a397c5)
Location: include/net/sock.h:1402
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a5833e)
Location: include/net/sock.h:1402
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81914009)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff81921baf)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffffffff81922b6d)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffff8195d8b7)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81968a92)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8199d263)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff819c2e83)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819cbd9c)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff819d1f7b)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffffffff819d59b7)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819df8cf)
Location: include/net/sock.h:1412
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff819f5893)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a186b5)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70355)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a90acd)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff819e5be9)
Location: include/net/sock.h:1460
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff819f54a1)
Location: include/net/sock.h:1460
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffffffff819f62ab)
Location: include/net/sock.h:1460
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffff81a2ca7a)
Location: include/net/sock.h:1460
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81a3bc69)
Location: include/net/sock.h:1460
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress
  - net/core/skmsg.c:sk_psock_skb_ingress
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81a764a3)
Location: include/net/sock.h:1460
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81aae596)
Location: include/net/sock.h:1460
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81ab281f)
Location: include/net/sock.h:1460
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81abae33)
Location: include/net/sock.h:1460
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2c02)
Location: include/net/sock.h:1460
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81accd71)
Location: include/net/sock.h:1460
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81ae3be7)
Location: include/net/sock.h:1460
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b093e3)
Location: include/net/sock.h:1460
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b22555)
Location: include/net/sock.h:1460
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/xfrm/espintcp.c:handle_nonesp
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b69f68)
Location: include/net/sock.h:1460
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81b8bd02)
Location: include/net/sock.h:1460
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81baae08)
Location: include/net/sock.h:1460
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clear_xmit
  - net/mptcp/protocol.c:mptcp_clean_una
  - net/mptcp/protocol.c:mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In net/core/sock.c (ffffffff819e56b9)
Location: include/net/sock.h:1476
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff819f4f8c)
Location: include/net/sock.h:1476
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffffffff819f5aeb)
Location: include/net/sock.h:1476
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffff81a2e02a)
Location: include/net/sock.h:1476
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81a3f639)
Location: include/net/sock.h:1476
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81a7f213)
Location: include/net/sock.h:1476
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81ab8737)
Location: include/net/sock.h:1476
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81abdb5f)
Location: include/net/sock.h:1476
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81ac61d3)
Location: include/net/sock.h:1476
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace632)
Location: include/net/sock.h:1476
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8d71)
Location: include/net/sock.h:1476
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81af0b07)
Location: include/net/sock.h:1476
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17bfd)
Location: include/net/sock.h:1476
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b30f55)
Location: include/net/sock.h:1476
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/xfrm/espintcp.c:handle_nonesp
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78a48)
Location: include/net/sock.h:1476
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81b9b175)
Location: include/net/sock.h:1476
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bbb150)
Location: include/net/sock.h:1476
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clear_xmit
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_wmem_reserve
  - net/mptcp/protocol.c:__mptcp_wmem_reserve
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_try_coalesce
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
In net/core/sock.c (ffffffff819cb7c7)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff819db115)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffffffff819dbc93)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffff81a14cf0)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81a4ea01)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81a681f3)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81aa3a37)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81aa84c8)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81ab13e3)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab97c2)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3de0)
Location: include/net/sock.h:1492
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81adc2bd)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b057ce)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81b1ec83)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/xfrm/espintcp.c:handle_nonesp
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66d52)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81b8ab6e)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81baa790)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clear_xmit
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_try_coalesce
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
In net/core/sock.c (ffffffff81a7ae57)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff81a8b7b9)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffffffff81a8be19)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffff81ac83cc)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81b07572)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81b21713)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81b5fbe7)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81b64738)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81b6e2f3)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffffffff81b76bf7)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b82470)
Location: include/net/sock.h:1502
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81b9b4dd)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc832b)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81be38f1)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e90f)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81c56c89)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81c7e609)
Location: include/net/sock.h:1502
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_try_coalesce
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
In net/core/sock.c (ffffffff81beed96)
Location: include/net/sock.h:1575
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff81c00e92)
Location: include/net/sock.h:1575
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffffffff81c01712)
Location: include/net/sock.h:1575
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffff81c448f8)
Location: include/net/sock.h:1575
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81c8ccde)
Location: include/net/sock.h:1575
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81ca9cd3)
Location: include/net/sock.h:1575
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81cee6bc)
Location: include/net/sock.h:1575
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81cf351d)
Location: include/net/sock.h:1575
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81cfd773)
Location: include/net/sock.h:1575
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffffffff81d06438)
Location: include/net/sock.h:1575
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d12970)
Location: include/net/sock.h:1575
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81d2d4e2)
Location: include/net/sock.h:1575
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5dbc6)
Location: include/net/sock.h:1575
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81d7b349)
Location: include/net/sock.h:1575
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/xfrm/espintcp.c:handle_nonesp
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcb55a)
Location: include/net/sock.h:1575
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81df6071)
Location: include/net/sock.h:1575
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81e22a2a)
Location: include/net/sock.h:1575
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:dfrag_clear
  - net/mptcp/protocol.c:__mptcp_mem_reclaim_partial
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
In io_uring/net.c (ffffffff81795ddd)
Location: include/net/sock.h:1621
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In net/core/sock.c (ffffffff81d9e4f9)
Location: include/net/sock.h:1621
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff81db023a)
Location: include/net/sock.h:1621
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/stream.c (ffffffff81db0aa4)
Location: include/net/sock.h:1621
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffff81dfeea9)
Location: include/net/sock.h:1621
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81e47b76)
Location: include/net/sock.h:1621
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81e66cd3)
Location: include/net/sock.h:1621
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81eb1891)
Location: include/net/sock.h:1621
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81eb76f0)
Location: include/net/sock.h:1621
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ec2383)
Location: include/net/sock.h:1621
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed87b0)
Location: include/net/sock.h:1621
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81ef5352)
Location: include/net/sock.h:1621
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27876)
Location: include/net/sock.h:1621
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81f483ab)
Location: include/net/sock.h:1621
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/xfrm/espintcp.c:handle_nonesp
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9c5f0)
Location: include/net/sock.h:1621
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81fca5db)
Location: include/net/sock.h:1621
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81ffb71f)
Location: include/net/sock.h:1621
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:dfrag_clear
  - net/mptcp/protocol.c:dfrag_clear
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
In io_uring/net.c (ffffffff817d6a72)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In net/core/sock.c (ffffffff81e0cd09)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff81e20556)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/stream.c (ffffffff81e20f64)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffff81e70979)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81ea32f4)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81ec2a93)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81f0ff9c)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81f15dd0)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81f20993)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f378c0)
Location: include/net/sock.h:1612
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81f54c32)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f87063)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81fa7f61)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/xfrm/espintcp.c:handle_nonesp
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffd040)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff8202b40f)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff82077aa5)
Location: include/net/sock.h:1612
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:dfrag_clear
  - net/mptcp/protocol.c:dfrag_clear
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
In io_uring/net.c (ffffffff8181ac42)
Location: include/net/sock.h:1587
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In net/core/sock.c (ffffffff81ec9699)
Location: include/net/sock.h:1587
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff81ede42a)
Location: include/net/sock.h:1587
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/stream.c (ffffffff81edee39)
Location: include/net/sock.h:1587
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffff81f30009)
Location: include/net/sock.h:1587
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81f65636)
Location: include/net/sock.h:1587
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81f85de3)
Location: include/net/sock.h:1587
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81fd419c)
Location: include/net/sock.h:1587
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81fda1ac)
Location: include/net/sock.h:1587
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81fe5093)
Location: include/net/sock.h:1587
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffd990)
Location: include/net/sock.h:1587
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8201aea2)
Location: include/net/sock.h:1587
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204e6a3)
Location: include/net/sock.h:1587
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff82075221)
Location: include/net/sock.h:1587
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/xfrm/espintcp.c:handle_nonesp
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc155)
Location: include/net/sock.h:1587
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff820faefa)
Location: include/net/sock.h:1587
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff8214cb14)
Location: include/net/sock.h:1587
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:dfrag_clear
  - net/mptcp/protocol.c:dfrag_clear
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
In net/core/sock.c (ffff800010babd54)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffff800010bbc210)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffff800010bbd460)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffff800010bfd9c4)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffff800010c0f904)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffff800010c4b92c)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffff800010c75c84)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffff800010c7e9e8)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffff800010c84b44)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffff800010c88b90)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93460)
Location: include/net/sock.h:1412
Inline: True
```
```
In net/ipv4/af_inet.c (ffff800010cab688)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3ec0)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38c8c)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffff800010d5deec)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (c0cca938)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (c0cd8688)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (c0cd98fc)
Location: include/net/sock.h:1412
Inline: True
```
```
In net/core/filter.c (c0d19e74)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (c0d26244)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (c0d5b694)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (c0d8431c)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (c0d8da10)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (c0d93e20)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (c0d97894)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_fastopen.c (c0da1c60)
Location: include/net/sock.h:1412
Inline: True
```
```
In net/ipv4/af_inet.c (c0db8500)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (c0ddddac)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (c0e3b04c)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (c0e5cce0)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (c000000000c8230c)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (c000000000c95450)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (c000000000c96b3c)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (c000000000ce95b8)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (c000000000cfa72c)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (c000000000d48b50)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (c000000000d7d528)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (c000000000d88db4)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (c000000000d909d8)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (c000000000d9574c)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_fastopen.c (c000000000da36b4)
Location: include/net/sock.h:1412
Inline: True
```
```
In net/ipv4/af_inet.c (c000000000dc1e64)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (c000000000df3270)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6b688)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (c000000000e96fc4)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffe00073f36c)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffe00074af96)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffffffe00074bc4a)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffe00077d138)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffe00078b446)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffe0007b7c0c)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffe0007d8e90)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffe0007e0cbc)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffe0007e64e4)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e98c2)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f296e)
Location: include/net/sock.h:1412
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffe000806328)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824cde)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875ea8)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffe000893f00)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff818b4009)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff818c1baf)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffffffff818c2b6d)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffff818fd887)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81908a62)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8193d0d3)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81962cf3)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff8196bc0c)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81971deb)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffffffff81975827)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197f73f)
Location: include/net/sock.h:1412
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81995633)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7d45)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0f9e5)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a3015d)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff8186df59)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff8187baef)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffffffff8187caad)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffff818b76b7)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff818c2872)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff818f6bd3)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff8191c7e3)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819256fc)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff8192b8bb)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f2e7)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819391ff)
Location: include/net/sock.h:1412
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8194f0f3)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974b35)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cc7a5)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff819ed34d)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81905009)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff81912baf)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffffffff81913b6d)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffff8194e8b7)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81959a92)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8198e263)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff819cd4c3)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819d63dc)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff819dc5bb)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffffffff819dfff7)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e9f0f)
Location: include/net/sock.h:1412
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff819ffed3)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a227c5)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7a465)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a9bd0d)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff819260d9)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/datagram.c (ffffffff81933d2f)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/core/stream.c (ffffffff81934cfd)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffff81970287)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff8197bcb2)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff819b0b03)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff819d7053)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819dfffc)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff819e623b)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffffffff819e9cb5)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f3d3f)
Location: include/net/sock.h:1412
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81a0a003)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2dba6)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a86ca5)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81aa64d8)
Location: include/net/sock.h:1412
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
</details>
</li>
</ul>

## Differences
