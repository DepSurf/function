# Function: <code>skb_peek</code>

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
In kernel/audit.c (ffffffff81121b8a)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f4b2c)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff815fb69c)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81704ecd)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff8170ddb5)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/stream.c (ffffffff8170e146)
Location: include/linux/skbuff.h:1375
Inline: True
```
```
In net/core/dev.c (ffffffff8171994d)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_callback
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81725ac6)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
```
```
In net/core/netpoll.c (ffffffff81738a32)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/sched/sch_generic.c (ffffffff81740b28)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_peek
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_reset
```
```
In net/sched/sch_fifo.c (ffffffff81748e71)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_peek_head
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_queue_drop_head
```
```
In net/netlink/af_netlink.c (ffffffff8174a6ed)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_set_ring
```
```
In net/ipv4/ip_output.c (ffffffff8175f046)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff81765b95)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_prequeue_process
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8176ae5e)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81776d51)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_xmit_retransmit_queue
  - net/ipv4/tcp_output.c:tcp_xmit_retransmit_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_timer.c (ffffffff817799a2)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:retransmits_timed_out
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177c927)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81784bc3)
Location: include/linux/skbuff.h:1375
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81788801)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/icmp.c (ffffffff8178dcb2)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff81794796)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff817a3daf)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff817aa128)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b5e5a)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/unix/af_unix.c (ffffffff817bd6ca)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffff817c274e)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff817c7d7e)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff817e5ad3)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff817e7632)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (ffffffff817fb002)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff818031fe)
Location: include/linux/skbuff.h:1375
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In kernel/audit.c (ffffffff81129aca)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81657145)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff8165b5c2)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8176ba9d)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff817754d5)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/stream.c (ffffffff81775866)
Location: include/linux/skbuff.h:1476
Inline: True
```
```
In net/core/dev.c (ffffffff81781e30)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_callback
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff817925bc)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff817a4d02)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/sched/sch_generic.c (ffffffff817ad958)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_peek
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff817b5ec1)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_peek_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_output.c (ffffffff817cbab1)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff817d4926)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_prequeue_process
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff817e0e24)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff817e64b0)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_xmit_retransmit_queue
  - net/ipv4/tcp_output.c:tcp_xmit_retransmit_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff817e74d3)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:retransmits_timed_out
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea220)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff817f2143)
Location: include/linux/skbuff.h:1476
Inline: True
```
```
In net/ipv4/udp.c (ffffffff817f61cb)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/icmp.c (ffffffff817fb2a2)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff81802116)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81810b07)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81817613)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81822e7a)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/unix/af_unix.c (ffffffff8182a63a)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffff8182f77d)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81834ebe)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff818549a3)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff81855a32)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (ffffffff8186a84f)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81874587)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In kernel/audit.c (ffffffff811337e4)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81684e25)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff816893e2)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81798f2b)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff817a1372)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/stream.c (ffffffff817a2ae6)
Location: include/linux/skbuff.h:1491
Inline: True
```
```
In net/core/dev.c (ffffffff817af730)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff817bfe8c)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff817d3772)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/ipv4/ip_output.c (ffffffff817fb72c)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81804666)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_prequeue_process
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff8181122d)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff81816bf0)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff81817a52)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:retransmits_timed_out
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818a5d)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81822f23)
Location: include/linux/skbuff.h:1491
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81826c7b)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (ffffffff8182c152)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff818330a6)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81842014)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81848e83)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff818547ba)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/unix/af_unix.c (ffffffff8185c0aa)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffff8186120e)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff818669f4)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff818866d5)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff818877f2)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (ffffffff8189d69f)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff818a8b77)
Location: include/linux/skbuff.h:1491
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In kernel/audit.c (ffffffff81134cdd)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff81694ca9)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8169a253)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff8169eb64)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff817b7539)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff817c0c86)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff817ce015)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff817de3b4)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff817f2ac2)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff817f997b)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/ipv4/ip_output.c (ffffffff8181bafd)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff818248ea)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_prequeue_process
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81831245)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff81836f3b)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff81837e7c)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183924b)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81843a87)
Location: include/linux/skbuff.h:1484
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818482e0)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (ffffffff8184d604)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff818549e6)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81863973)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff8186c4a2)
Location: include/linux/skbuff.h:1484
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8187825a)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/unix/af_unix.c (ffffffff8188342d)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffff8188594a)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff8188b11f)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff818acc45)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff818addb5)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (ffffffff818c3c11)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff818cf3b7)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In kernel/audit.c (ffffffff81141a2d)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In kernel/bpf/sockmap.c (ffffffff811b0b08)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_gc_work
```
```
In drivers/net/tun.c (ffffffff816ff53c)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81704a03)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff81709d04)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8182fb39)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff8183a6a6)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff8184ad15)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81858c16)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff8186e082)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff8187729b)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/ipv4/ip_output.c (ffffffff8189aa36)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff818a67a8)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff818b0200)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff818b6ac4)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff818b7dd8)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/raw.c (ffffffff818c3487)
Location: include/linux/skbuff.h:1566
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c7d40)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (ffffffff818cd344)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff818d4886)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff818e3ab6)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff818ecd81)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8b6c)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff818feb62)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/unix/af_unix.c (ffffffff81903b1b)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffff81906afa)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff8190c33f)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff8192f5d2)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff81930a35)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (ffffffff81946eaa)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff8195432d)
Location: include/linux/skbuff.h:1566
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In kernel/audit.c (ffffffff811503b9)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In kernel/bpf/sockmap.c (ffffffff811cff58)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_gc_work
```
```
In drivers/net/tun.c (ffffffff8173ef0e)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81743143)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff81748768)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8187a305)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81884de2)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff818950f5)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff818a405b)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff818bf054)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff818c89e2)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff818ccbf5)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff818eeefa)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff818fb884)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff819056ca)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff8190c300)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff8190d79d)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/raw.c (ffffffff81919123)
Location: include/linux/skbuff.h:1577
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8191cac5)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (ffffffff81923732)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff8192aa42)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff8193a27b)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81942c76)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194f580)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819556d9)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:1577
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819594d1)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffff8195daed)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff819637c7)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff81988287)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff81989673)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (ffffffff8199f58e)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/packet/af_packet.c (ffffffff819ad8d6)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In kernel/audit.c (ffffffff8115d076)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff8176310d)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8176797d)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff8176c818)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8189af15)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff818a5852)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff818b5bc5)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff818c74c9)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff818e74e6)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff818e7e44)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff818f3902)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff818f7f65)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff8191c6ea)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff819297e4)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81933870)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff8193a5e0)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff8193bb8b)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/raw.c (ffffffff819478f3)
Location: include/linux/skbuff.h:1646
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194b055)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (ffffffff81952522)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff81959f62)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff8196a2c9)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81972d42)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81982bbd)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a2e9)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:1646
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8198e07d)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffff8199262d)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81998787)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff819bec99)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff819bffa3)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (ffffffff819d60b5)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/packet/af_packet.c (ffffffff819e4246)
Location: include/linux/skbuff.h:1646
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In kernel/audit.c (ffffffff81169796)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff817a0c79)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a345d)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff817aa608)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff818e5296)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff818f0b72)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff818ff524)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81913b9f)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff81936e5b)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff819377a2)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff819527a0)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff819576aa)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff8197ea15)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff8198c8ab)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff819978eb)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff8199e92a)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff8199ff3a)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/raw.c (ffffffff819abf99)
Location: include/linux/skbuff.h:1736
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819af6b5)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (ffffffff819b6ded)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff819beba6)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff819d0d52)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff819dc5d5)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ec850)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4559)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:1736
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819f960d)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffff819fdc1f)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81a045d6)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff81a2dba0)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff81a2ede9)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (ffffffff81a4515a)
Location: include/linux/skbuff.h:1736
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/packet/af_packet.c (ffffffff81a535f4)
Location: include/linux/skbuff.h:1736
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
In kernel/audit.c (ffffffff81175636)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff817c5c49)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c6ead)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff817ce068)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81917426)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81922ac2)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81931884)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff8194620f)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff81969d2b)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff8196a662)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff819754a1)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81988af0)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff8198db4a)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff819b53a7)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff819c321b)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff819ce47b)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff819d543a)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff819d6afa)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/raw.c (ffffffff819e2c49)
Location: include/linux/skbuff.h:1746
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e6335)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (ffffffff819edaed)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff819f57d6)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81a078ac)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81a135c5)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2385c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b1f9)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:1746
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a3026d)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffff81a3480f)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b1c6)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff81a6470b)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff81a65939)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (ffffffff81a7bd4a)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/packet/af_packet.c (ffffffff81a8a1e4)
Location: include/linux/skbuff.h:1746
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
In kernel/audit.c (ffffffff81187d16)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In fs/io_uring.c (ffffffff81380466)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
```
```
In drivers/net/tun.c (ffffffff8188e5d9)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_receive
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81892b35)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff8189a146)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_fill_frags
```
```
In net/core/skbuff.c (ffffffff819e9cb4)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff819f61f2)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81a0704f)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81a16658)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/skmsg.c (ffffffff81a3d83b)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff81a3ddc2)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81a49ced)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81a6079d)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81a657b1)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a9f608)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81aa8e40)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81aba564)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1d7a)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac360a)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/raw.c (ffffffff81ad0229)
Location: include/linux/skbuff.h:1757
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad2e65)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (ffffffff81adb8ed)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff81ae3b16)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81af70f7)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81b02db2)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b156f2)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d879)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:1757
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b2323f)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/af_unix.c (ffffffff81b23ff4)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffff81b29633)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81b30785)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff81b5b877)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/icmp.c (ffffffff81b5e289)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (ffffffff81b764b2)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
```
```
In net/packet/af_packet.c (ffffffff81b84ed4)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
```
```
In net/mptcp/protocol.c (ffffffff81bab09b)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_recvmsg_mskq
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
```
In net/mptcp/subflow.c (ffffffff81baf851)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
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
In kernel/audit.c (ffffffff8118508b)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In fs/io_uring.c (ffffffff8138ed36)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
```
```
In drivers/net/tun.c (ffffffff8189cb69)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_receive
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a0bd5)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff818a929f)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_fill_frags
```
```
In net/core/skbuff.c (ffffffff819e9a54)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff819f5a32)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81a085ff)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81a166e3)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/skmsg.c (ffffffff81a4041b)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff81a40ae2)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81a4f58d)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81a6903d)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81a6d8c2)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81aa9548)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81ab32e0)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81ac59a4)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack_probe
```
```
In net/ipv4/tcp_output.c (ffffffff81acd7ea)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81acf07c)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/raw.c (ffffffff81adc19f)
Location: include/linux/skbuff.h:1778
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81adf2a5)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (ffffffff81ae83a1)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff81af0a36)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81b03f9b)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81b11192)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b23b12)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c149)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:1778
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b31c2f)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/af_unix.c (ffffffff81b32a64)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffff81b37f63)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f3b5)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff81b6a0c7)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/icmp.c (ffffffff81b6ca59)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (ffffffff81b85272)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
```
```
In net/packet/af_packet.c (ffffffff81b9481a)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
```
```
In net/mptcp/protocol.c (ffffffff81bbb1d7)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clear_xmit
  - net/mptcp/protocol.c:__mptcp_recvmsg_mskq
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
```
In net/mptcp/subflow.c (ffffffff81bc23a7)
Location: include/linux/skbuff.h:1778
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
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
In kernel/audit.c (ffffffff81185f1b)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In fs/io_uring.c (ffffffff8139bb6e)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_rsrc_file_put
  - fs/io_uring.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff8187f784)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81883265)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff8188c366)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff819cfb76)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff819dbbd2)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff819eed27)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff819fd2ef)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff81a25792)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81a34c66)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81a4c3fd)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81a56027)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a94715)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81a9e540)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0bb0)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81ab89aa)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81aba1bc)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/raw.c (ffffffff81ac703f)
Location: include/linux/skbuff.h:1794
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81aca1b5)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (ffffffff81ad3631)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff81adc1e6)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81aefc21)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81b0045f)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11712)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19dac)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:1794
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b1f961)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/af_unix.c (ffffffff81b20754)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffff81b25bfb)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d24e)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff81b583f7)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/icmp.c (ffffffff81b5adb9)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81b625b6)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff81b742a7)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/packet/af_packet.c (ffffffff81b838fa)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
```
```
In net/mptcp/protocol.c (ffffffff81baa817)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clear_xmit
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
```
In net/mptcp/subflow.c (ffffffff81bb2ca7)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
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
In kernel/audit.c (ffffffff811ae30b)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In fs/io_uring.c (ffffffff813e72c6)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
  - fs/io_uring.c:io_rsrc_file_put
  - fs/io_uring.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff819108f4)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81914c05)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff8191f7d9)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81a7feb6)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81a8bdb2)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81aa0096)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81aaf67b)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff81ada242)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81aea028)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81b048ad)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81b0ede0)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81b4fb95)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81b5a0f0)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81b6d9f4)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81b75bca)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81b761d5)
Location: include/linux/skbuff.h:1823
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81b8585f)
Location: include/linux/skbuff.h:1823
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b88a95)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (ffffffff81b92281)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff81b9b406)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81bafc31)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81bc254f)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd5202)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde34c)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:1823
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81be4601)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/af_unix.c (ffffffff81be578c)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffff81beb315)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81bf3405)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff81c1f787)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/icmp.c (ffffffff81c224c9)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81c2a046)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff81c3eb56)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/packet/af_packet.c (ffffffff81c4fa0a)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
```
```
In net/mptcp/protocol.c (ffffffff81c78d36)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
```
In net/mptcp/subflow.c (ffffffff81c81237)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
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
In kernel/audit.c (ffffffff811e0db0)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_send_list_thread
```
```
In io_uring/io_uring.c (ffffffff816c8c2f)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_rsrc_file_put
  - io_uring/io_uring.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff81a66f79)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6a23b)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff81a748b5)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81bf4403)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81c01692)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81c15b42)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81c28c70)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81c5b792)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81c6c854)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81c8a16e)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81c95978)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81cdd60b)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81ce87ce)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81cfce70)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81d054ca)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81d06f01)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/raw.c (ffffffff81d165d8)
Location: include/linux/skbuff.h:2174
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d1a3f5)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (ffffffff81d23b6d)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff81d2d422)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81d431fd)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81d553af)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6ba43)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81d7514a)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:2174
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81d7ba6b)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/af_unix.c (ffffffff81d7c739)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffff81d834c9)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c01d)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff81dbc39f)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/icmp.c (ffffffff81dbf205)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81dc74b6)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff81ddd326)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/packet/af_packet.c (ffffffff81df04c1)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
```
```
In net/mptcp/protocol.c (ffffffff81e20a27)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
```
In net/mptcp/subflow.c (ffffffff81e26c6a)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
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
In kernel/audit.c (ffffffff81226bd0)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_send_list_thread
```
```
In io_uring/rsrc.c (ffffffff817a040f)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_file_put
  - io_uring/rsrc.c:io_rsrc_file_put
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In drivers/net/tun.c (ffffffff81bf25a3)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfce8e)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff81c08b15)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81da2253)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81db0a22)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81dc6f22)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81ddb910)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81e11ac2)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81e24446)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81e44d5e)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81e514e8)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81e9e0c8)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81eb2df6)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81ec1a30)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81eca5ca)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecadd5)
Location: include/linux/skbuff.h:2032
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81edc8d8)
Location: include/linux/skbuff.h:2032
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee10e5)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_common
```
```
In net/ipv4/icmp.c (ffffffff81eeb0ed)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff81ef5292)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81f0c1dd)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81f1f6bf)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f36d83)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41320)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:2032
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81f48b1b)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/af_unix.c (ffffffff81f497a9)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_show_fdinfo
```
```
In net/unix/garbage.c (ffffffff81f50b1e)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81f59fdd)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff81f8d61c)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/icmp.c (ffffffff81f8f915)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81f98196)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff81fae7c0)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/packet/af_packet.c (ffffffff81fc4621)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
```
```
In net/mptcp/protocol.c (ffffffff81ff7eb7)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
```
In net/mptcp/subflow.c (ffffffff81ffe3da)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
```
```
In net/mptcp/fastopen.c (ffffffff8200eec2)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
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
In kernel/audit.c (ffffffff8123d1c2)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_send_list_thread
```
```
In io_uring/rsrc.c (ffffffff817e1414)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_file_scm_put
  - io_uring/rsrc.c:io_rsrc_file_scm_put
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In drivers/net/tun.c (ffffffff81c4b23d)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c6250e)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff81c6e27c)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81e10b23)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81e20ee2)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81e36712)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81e4c660)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81e853d2)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81e9998a)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81e9fb5e)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/core/skmsg.c (ffffffff81ea322e)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/sched/sch_generic.c (ffffffff81eacd38)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81efc88b)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81f118e1)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81f2000d)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81f29111)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81f29915)
Location: include/linux/skbuff.h:2068
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81f3b479)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (ffffffff81f40b35)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_common
```
```
In net/ipv4/icmp.c (ffffffff81f4aa0d)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff81f54b72)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81f6be6f)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81f7f1b5)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f9672c)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa0bb0)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:2068
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81fa898b)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/af_unix.c (ffffffff81fa9401)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_show_fdinfo
```
```
In net/unix/garbage.c (ffffffff81fb04c5)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81fb9c8e)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff81fecd69)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/icmp.c (ffffffff81ff0175)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81ff8b86)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff8200fc40)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/packet/af_packet.c (ffffffff8202563e)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
```
```
In net/mptcp/protocol.c (ffffffff820743c8)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
```
In net/mptcp/subflow.c (ffffffff8207a4aa)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
```
```
In net/mptcp/fastopen.c (ffffffff8208babe)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
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
In kernel/audit.c (ffffffff812571ab)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_send_list_thread
```
```
In drivers/net/tun.c (ffffffff81cf8e31)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_rx_batched
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d18f2e)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff81d22b64)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81ecd653)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_errqueue_purge
  - net/core/skbuff.c:skb_queue_purge_reason
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81ededb2)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81ef4a02)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81f0b374)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81f47a37)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81f5c0ba)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81f6218e)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/core/skmsg.c (ffffffff81f65544)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/sched/sch_generic.c (ffffffff81f6f7c8)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81fc07cb)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81fce85e)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81fe46ed)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81fedc51)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81fee485)
Location: include/linux/skbuff.h:2075
Inline: True
```
```
In net/ipv4/raw.c (ffffffff82001599)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (ffffffff82006785)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_common
```
```
In net/ipv4/icmp.c (ffffffff82010b1d)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff8201ade2)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff8203243f)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff82045835)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/xfrm/xfrm_policy.c (ffffffff82063b1c)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8206df10)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:2075
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff82075c7b)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/af_unix.c (ffffffff82076891)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_show_fdinfo
```
```
In net/unix/garbage.c (ffffffff8207daee)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff82087155)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff820ba969)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/icmp.c (ffffffff820bdd45)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff820c67f6)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff820debd0)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/packet/af_packet.c (ffffffff820f4fae)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
```
```
In net/mptcp/protocol.c (ffffffff82147f28)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
```
In net/mptcp/subflow.c (ffffffff8214f91b)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
```
```
In net/mptcp/fastopen.c (ffffffff821618be)
Location: include/linux/skbuff.h:2075
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
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
In kernel/audit.c (ffff8000101ea448)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffff8000109e109c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000109fe0dc)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffff800010a08864)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffff800010bb3e84)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffff800010bbd3c4)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffff800010bd01b8)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffff800010be6370)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/skmsg.c (ffff800010c0ff58)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffff800010c10818)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffff800010c1b2e0)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffff800010c309f0)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffff800010c39224)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffff800010c65abc)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffff800010c75f58)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffff800010c80eec)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffff800010c880c8)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffff800010c89984)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/raw.c (ffff800010c97348)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (ffff800010c9af58)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (ffff800010ca4164)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffff800010cab5ec)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffff800010cc07a0)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffff800010ccde5c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce097c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffff800010ce9a88)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:1746
Inline: True
```
```
In net/unix/af_unix.c (ffff800010ceff50)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffff800010cf4e78)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffff800010cfc324)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffff800010d29308)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffff800010d2ba0c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (ffff800010d458c0)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/packet/af_packet.c (ffff800010d5b16c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In kernel/audit.c (c042a1dc)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (c0ac4eb8)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (c0adba1c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In net/core/skbuff.c (c0ccddf8)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (c0cd9850)
Location: include/linux/skbuff.h:1746
Inline: True
```
```
In net/core/dev.c (c0ce6454)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (c0cfe92c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (c0d27d54)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (c0d28934)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (c0d3367c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (c0d47ad4)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (c0d4b57c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (c0d7573c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (c0d84610)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (c0d9014c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (c0d973b8)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (c0d98ad4)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/raw.c (c0da4d64)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (c0da99b0)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (c0db02dc)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (c0db844c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (c0dccaa8)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (c0dd8c9c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c0de9d20)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (c0df1b84)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:1746
Inline: True
```
```
In net/unix/af_unix.c (c0df6958)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (c0dfba58)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (c0e036f8)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (c0e2ccd0)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (c0e2f870)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (c0e48474)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/packet/af_packet.c (c0e56df4)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In kernel/audit.c (c00000000025b5e0)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (c000000000aa2210)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa5d4c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In net/core/skbuff.c (c000000000c86884)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (c000000000c96a64)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (c000000000cacf10)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (c000000000cc7914)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (c000000000cfc29c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (c000000000cfd2b4)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (c000000000d0c0d0)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (c000000000d29abc)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (c000000000d323b0)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (c000000000d6a250)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (c000000000d7d968)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (c000000000d8bd78)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (c000000000d94f24)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (c000000000d96e44)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/raw.c (c000000000da889c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (c000000000dacef8)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (c000000000db6d30)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (c000000000dc1d80)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (c000000000ddbaf4)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (c000000000dea5ec)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000e02d14)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (c000000000e0d3c4)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:1746
Inline: True
```
```
In net/unix/af_unix.c (c000000000e15af0)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (c000000000e1aea8)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (c000000000e23dd4)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (c000000000e5a4cc)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (c000000000e5cf98)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (c000000000e7b4c4)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/packet/af_packet.c (c000000000e9113c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In kernel/audit.c (ffffffe00015eee0)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffe00062ab04)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062b990)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In net/core/skbuff.c (ffffffe0007418a0)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffe00074bbce)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffe00075a22e)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffe00076ace6)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffe00078c46c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffe00078cf9c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffe000795b26)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffe0007a6bc4)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffe0007aab8e)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffe0007cd20a)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffe0007d915e)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffe0007e2e50)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffe0007e934a)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea86c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/raw.c (ffffffe0007f5930)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (ffffffe0007f8888)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (ffffffe0007ff472)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffe0008062a8)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffe000816f2c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffe000820034)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082f6a4)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffe000837904)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:1746
Inline: True
```
```
In net/unix/af_unix.c (ffffffe00083c8e4)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffe000840b10)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffe000846bf6)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffe000869aee)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffe00086bd32)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (ffffffe000880bb6)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/packet/af_packet.c (ffffffe00088e0a2)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In kernel/audit.c (ffffffff8116dc56)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff8178a729)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178b98d)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff81792c88)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff818b7426)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff818c2ac2)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff818d1884)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff818e61df)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff81909cfb)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff8190a632)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81915471)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81928960)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff8192d9ba)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff81955217)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff8196308b)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff8196e2eb)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff819752aa)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff8197696a)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/raw.c (ffffffff81982ab9)
Location: include/linux/skbuff.h:1746
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819861a5)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (ffffffff8198d88d)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff81995576)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff819a764c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff819b2dc5)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c2eec)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819ca889)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:1746
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819cf8fd)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffff819d3e9f)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff819da856)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff81a03d9b)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff81a04fc9)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (ffffffff81a1b3da)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/packet/af_packet.c (ffffffff81a29874)
Location: include/linux/skbuff.h:1746
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
In kernel/audit.c (ffffffff81160df6)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff8176a079)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8177475d)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In net/core/skbuff.c (ffffffff81871376)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff8187ca02)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff8188b708)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff818a001f)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff818c3b0b)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff818c44e2)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff818cf221)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff818e2710)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff818e74ba)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff8190ed07)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff8191cb7b)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81927ddb)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff8192ed6a)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff8193042a)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/raw.c (ffffffff8193c579)
Location: include/linux/skbuff.h:1746
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8193fc65)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (ffffffff8194734d)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff8194f036)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff8196110c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff8196f3f5)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fcdc)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81987679)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:1746
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8198c6bd)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffff81990c5f)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81997616)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff819c0b5b)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff819c1d89)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (ffffffff819d819a)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/packet/af_packet.c (ffffffff819e6a64)
Location: include/linux/skbuff.h:1746
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
In kernel/audit.c (ffffffff8116ba26)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff817baac9)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bbd2d)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff817c2ee8)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81908426)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81913ac2)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81922884)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff8193720f)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff8195ad2b)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff8195b662)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff819664a1)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81979af0)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff8197eb4a)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff819bf9e7)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff819cd85b)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff819d8abb)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff819dfa7a)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff819e113a)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/raw.c (ffffffff819ed289)
Location: include/linux/skbuff.h:1746
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f0975)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (ffffffff819f812d)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff819ffe16)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81a11eec)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81a1d665)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2d96c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35309)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:1746
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a3a37d)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffff81a3e91f)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81a452d6)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff81a6e81b)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff81a6fa49)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (ffffffff81a85e5a)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/packet/af_packet.c (ffffffff81a95424)
Location: include/linux/skbuff.h:1746
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
In kernel/audit.c (ffffffff811791e5)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff817d2f1e)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d5f7d)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/xen-netfront.c (ffffffff817dd1a8)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81929406)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/stream.c (ffffffff81934c52)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81943a54)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff819589ea)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff8197cf4b)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff8197d882)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81988731)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff8199c020)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff819a10ba)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff819c9366)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff819d73eb)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff819e270b)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff819e972a)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff819eae0a)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/raw.c (ffffffff819f7169)
Location: include/linux/skbuff.h:1746
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fbf95)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/icmp.c (ffffffff81a0242d)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffffffff81a09f46)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81a1c863)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81a28827)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3912c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a40c29)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/skbuff.h:1746
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a454c9)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/unix/garbage.c (ffffffff81a4a28c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81a50fa6)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/raw.c (ffffffff81a7ae44)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff81a7c079)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/ip6mr.c (ffffffff81a9297c)
Location: include/linux/skbuff.h:1746
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/packet/af_packet.c (ffffffff81aa1844)
Location: include/linux/skbuff.h:1746
Inline: True
```
</details>
</li>
</ul>

## Differences
