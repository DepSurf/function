# Function: <code>__skb_unlink</code>

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
In kernel/audit.c (ffffffff81121b9f)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f70ff)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff815fb6b2)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81704edb)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_unlink
```
```
In net/core/datagram.c (ffffffff8170cdf5)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/stream.c (ffffffff8170e15e)
Location: include/linux/skbuff.h:1636
Inline: True
```
```
In net/core/dev.c (ffffffff8171513a)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_cpu_callback
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81724762)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
```
```
In net/core/netpoll.c (ffffffff81738a4a)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/sched/sch_generic.c (ffffffff81740bee)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_reset
```
```
In net/sched/sch_fifo.c (ffffffff81748fc9)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/sched/sch_fifo.c:qdisc_queue_drop
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_queue_drop_head
```
```
In net/netlink/af_netlink.c (ffffffff8174a704)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_set_ring
```
```
In net/ipv4/ip_output.c (ffffffff8175decd)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81765be8)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_prequeue_process
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8176b14b)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff817773de)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_timer.c (ffffffff81779e0f)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177c943)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff81788893)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/af_inet.c (ffffffff817947a4)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff817aa142)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b5fa2)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/unix/garbage.c (ffffffff817c2039)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff817c4a01)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff817fb01a)
Location: include/linux/skbuff.h:1636
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In kernel/audit.c (ffffffff81129adf)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81657280)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff8165b5d8)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8176bc20)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff817754fe)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/core/stream.c (ffffffff8177587e)
Location: include/linux/skbuff.h:1737
Inline: True
```
```
In net/core/dev.c (ffffffff81781e49)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_callback
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff8178e132)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff817a4d13)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/sched/sch_generic.c (ffffffff817ada1e)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff817b605c)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/ipv4/ip_output.c (ffffffff817cb2d3)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff817d4937)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_prequeue_process
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_input.c (ffffffff817d9aca)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff817e65f9)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff817e702a)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea244)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff817f61e3)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/af_inet.c (ffffffff8180212e)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff8181762a)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81822fc2)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/unix/garbage.c (ffffffff8182f792)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81831ad1)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff8186a867)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In kernel/audit.c (ffffffff811337f9)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81684f60)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff816893f8)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81798f48)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff817a139f)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/core/stream.c (ffffffff817a2afe)
Location: include/linux/skbuff.h:1752
Inline: True
```
```
In net/core/dev.c (ffffffff817af749)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff817bbae2)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff817d3783)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/ipv4/ip_output.c (ffffffff817faf33)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff8180467e)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_prequeue_process
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_input.c (ffffffff818085bc)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81816d39)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff8181775c)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818a81)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff81826d4d)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff818330be)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81848e9a)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81854908)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/unix/garbage.c (ffffffff81861223)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81863501)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff8189d6b7)
Location: include/linux/skbuff.h:1752
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In kernel/audit.c (ffffffff81134ce8)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff81694cb4)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8169a342)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff8169eb25)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff817b7555)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff817bf481)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffff817c0c94)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff817ce020)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff817da26d)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff817f2acd)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff817f9990)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/ipv4/ip_output.c (ffffffff8181b323)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff818248f8)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_prequeue_process
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_input.c (ffffffff81828bcc)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81836fbc)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff81837b7e)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81839260)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff81848393)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff818549f4)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff8186c4b9)
Location: include/linux/skbuff.h:1745
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff818783b7)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/unix/garbage.c (ffffffff81885955)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81887bb7)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff818c3c2b)
Location: include/linux/skbuff.h:1745
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In kernel/audit.c (ffffffff81141a38)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In kernel/bpf/sockmap.c (ffffffff811b0b16)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_gc_work
```
```
In drivers/net/tun.c (ffffffff816ff54e)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81704af2)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81709cc5)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8182fb55)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff81838e01)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffff8183a6b4)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff8184ad20)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff81854a19)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff8186e08d)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff818772b0)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/ipv4/ip_output.c (ffffffff8189a253)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff818a67b6)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff818a80cc)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffffffff818b4239)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffffffff818c7df3)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff818d4894)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff818ecd98)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8ca9)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff818feb80)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/unix/garbage.c (ffffffff81906b05)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81908e77)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81946ec4)
Location: include/linux/skbuff.h:1827
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In kernel/audit.c (ffffffff811503c4)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In kernel/bpf/sockmap.c (ffffffff811cff66)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_gc_work
```
```
In drivers/net/tun.c (ffffffff8173ef2b)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8174322d)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff8174877e)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8187a317)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff8188354d)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffff81884df4)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81895100)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff818a1709)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff818bf05f)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff818c89ef)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff818cd456)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff818ee723)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff818fb892)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff818fd3ba)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffffffff8190977b)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffffffff8191cb83)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff8192aa54)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81942c8d)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194f6d1)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819556e0)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff819584f8)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff8195daf8)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81960147)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff8199f5a6)
Location: include/linux/skbuff.h:1838
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffff8115d081)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff8176312e)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81767a67)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In drivers/net/xen-netfront.c (ffffffff8176c82e)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8189af27)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff818a3f9d)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffff818a5864)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff818b5bd0)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff818c4649)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff818e74ed)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff818e7e4f)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff818f390f)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff818f6ff9)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff8191bed3)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff819297f2)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff8192b29a)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffffffff81937a33)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffffffff8194b110)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff81959f74)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81972d59)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81982d0b)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a2f0)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff8198d0f8)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff81992638)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81994f27)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff819d60cd)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffff811697a2)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff817a0c8f)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a3444)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
```
In drivers/net/xen-netfront.c (ffffffff817aa61e)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff818e52a8)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff818ef294)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffff818f0b84)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff818ff52f)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff81910399)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff81936e62)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff819377ad)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff819527af)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81956724)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff8197e1e3)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff8198c8ba)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8198e46a)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffffffff8199bf77)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffffffff819af770)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff819bebb4)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff819dc640)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819eca28)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4560)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff819f8968)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff819fdc2a)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a009c7)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81a451d7)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffff81175642)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff817c5c5f)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c6e94)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
```
In drivers/net/xen-netfront.c (ffffffff817ce07e)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81917438)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff81921244)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffff81922ad4)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff8193188f)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff81942a09)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff81969d32)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff8196a66d)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff819754b0)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81988aff)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff8198cbc4)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff819b4b93)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff819c322a)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819c515a)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffffffff819d29d7)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffffffff819e63f9)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff819f57e4)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81a13630)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a23a40)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b200)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f5c8)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff81a3481a)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a3759a)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81a7bdc7)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffff81187d22)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In fs/io_uring.c (ffffffff813804d4)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
```
```
In drivers/net/tun.c (ffffffff8188e5a2)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_receive
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81892af6)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
```
In drivers/net/xen-netfront.c (ffffffff8189a150)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_fill_frags
```
```
In net/core/skbuff.c (ffffffff819e9cc6)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff819f4b84)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffff819f6204)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81a07056)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff81a12b50)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/skmsg.c (ffffffff81a3d842)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff81a3ddcd)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81a49cfb)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81a60762)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81a64af1)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a9ed7c)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81aae8cb)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81ab06ea)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffffffff81abf6f5)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffffffff81ad2f2d)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff81ae3b24)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81b02dd0)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1598e)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d885)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81b221d8)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81b23249)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/garbage.c (ffffffff81b29641)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81b2caba)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81b764d0)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
```
```
In net/mptcp/protocol.c (ffffffff81bab0ac)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_recvmsg_mskq
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81baf30c)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
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
In kernel/audit.c (ffffffff8118509a)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In fs/io_uring.c (ffffffff8138eda4)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
```
```
In drivers/net/tun.c (ffffffff8189cb32)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_receive
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a0b96)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
```
In drivers/net/xen-netfront.c (ffffffff818a92a9)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_fill_frags
```
```
In net/core/skbuff.c (ffffffff819e9a66)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff819f4874)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffff819f5a44)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81a08606)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff81a12ea0)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/skmsg.c (ffffffff81a40422)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff81a40aed)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81a4f59b)
Location: include/linux/skbuff.h:2064
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
In net/core/gro_cells.c (ffffffff81a69002)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81a6cc42)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81aa8cbc)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81ab8b0b)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81abb6ca)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffffffff81acb113)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffffffff81adf36d)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff81af0a44)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81b111b0)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b23dfa)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c155)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30bd8)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81b31c39)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/garbage.c (ffffffff81b37f71)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81b3b4ca)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81b85290)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
```
```
In net/mptcp/protocol.c (ffffffff81bbb1de)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clear_xmit
  - net/mptcp/protocol.c:__mptcp_recvmsg_mskq
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81bc14ca)
Location: include/linux/skbuff.h:2064
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_discard_data
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
In kernel/audit.c (ffffffff81185f2a)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In fs/io_uring.c (ffffffff8139bc1e)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff8187f749)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81883226)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
```
In drivers/net/xen-netfront.c (ffffffff8188c378)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff819cfb88)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff819da944)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffff819dbbe7)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff819eed32)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff819fa2f0)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff81a257a0)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81a34c74)
Location: include/linux/skbuff.h:2080
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
In net/core/gro_cells.c (ffffffff81a4c3c2)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81a55442)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a93ddf)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81aa3dbb)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81aa6677)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffffffff81ab616f)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffffffff81aca27d)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff81adc1f7)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81b00471)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1198e)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19db6)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e908)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81b1f96b)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/garbage.c (ffffffff81b25c09)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81b28c4a)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/mcast.c (ffffffff81b625ce)
Location: include/linux/skbuff.h:2080
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
In net/ipv6/ip6mr.c (ffffffff81b742b9)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/mptcp/protocol.c (ffffffff81baa821)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clear_xmit
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81bb2f68)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
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
In kernel/audit.c (ffffffff811ae31a)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In fs/io_uring.c (ffffffff813e7334)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
  - fs/io_uring.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff819108b9)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81914bc6)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
```
In drivers/net/xen-netfront.c (ffffffff8191f839)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81a7fec8)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff81a8afc4)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffff81a8bdc7)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81aa00a1)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff81aad254)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff81ada250)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81aea036)
Location: include/linux/skbuff.h:2109
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
In net/core/gro_cells.c (ffffffff81b04872)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81b0dfb2)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81b4f21f)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81b5ffd0)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81b62a67)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffffffff81b731c9)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffffffff81b88b5d)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff81b9b417)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81bc2561)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd547e)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde356)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81be3448)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81be460b)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/garbage.c (ffffffff81beb323)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81beeb3a)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/mcast.c (ffffffff81c2a05e)
Location: include/linux/skbuff.h:2109
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
In net/ipv6/ip6mr.c (ffffffff81c3eb68)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/mptcp/protocol.c (ffffffff81c7b518)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81c815fd)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
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
In kernel/audit.c (ffffffff811e0200)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In io_uring/io_uring.c (ffffffff816c8c64)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff81a66f95)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6a1fc)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
```
In drivers/net/xen-netfront.c (ffffffff81a7491c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81bf4415)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff81c00746)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffff81c016a7)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81c15b50)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff81c22882)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
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
In net/core/netpoll.c (ffffffff81c5b79d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81c6c862)
Location: include/linux/skbuff.h:2460
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
In net/core/gro_cells.c (ffffffff81c8a137)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81c95982)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81cdcbb2)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81cee98b)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1247)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffffffff81d028c0)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffffffff81d1a4c5)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff81d2d437)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81d553de)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6bc80)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81d75154)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a677)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81d7ba75)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/garbage.c (ffffffff81d834d8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81d871ba)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/mcast.c (ffffffff81dc74ce)
Location: include/linux/skbuff.h:2460
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
In net/ipv6/ip6mr.c (ffffffff81ddd338)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/mptcp/protocol.c (ffffffff81e23a9c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81e26fb4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
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
In kernel/audit.c (ffffffff81225f80)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In io_uring/rsrc.c (ffffffff817a0444)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_file_put
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In drivers/net/tun.c (ffffffff81bf25bf)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfcef9)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
```
In drivers/net/xen-netfront.c (ffffffff81c08b7c)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81da2265)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff81db0465)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffff81db0a37)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81dc6f2d)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff81dd526c)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
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
In net/core/netpoll.c (ffffffff81e11acd)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81e24451)
Location: include/linux/skbuff.h:2318
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
In net/core/gro_cells.c (ffffffff81e44d27)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81e514f2)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81e9d622)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81eb1bf8)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_skb
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81eb5587)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffffffff81ec7aa6)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffffffff81ee11b5)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_common
```
```
In net/ipv4/af_inet.c (ffffffff81ef52a7)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81f1f6ee)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f36fc0)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81f4132b)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81f47587)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81f48b25)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/garbage.c (ffffffff81f50b2d)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81f54cda)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/mcast.c (ffffffff81f981ae)
Location: include/linux/skbuff.h:2318
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
In net/ipv6/ip6mr.c (ffffffff81fae7d2)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/mptcp/protocol.c (ffffffff81ffb1dc)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81ffe7f6)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
```
```
In net/mptcp/fastopen.c (ffffffff8200eeec)
Location: include/linux/skbuff.h:2318
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
In kernel/audit.c (ffffffff8123c560)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In io_uring/rsrc.c (ffffffff817e1446)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_file_scm_put
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In drivers/net/tun.c (ffffffff81c4b264)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c62579)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
```
In drivers/net/xen-netfront.c (ffffffff81c6e2e3)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81e10b35)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff81e20915)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffff81e20ef7)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81e3671d)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff81e461c1)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
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
In net/core/netpoll.c (ffffffff81e853dd)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81e99998)
Location: include/linux/skbuff.h:2354
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
In net/core/gro_cells.c (ffffffff81e9fb27)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81eacd42)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81efbd73)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81f102a6)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_skb
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81f139b7)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffffffff81f26272)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffffffff81f40c05)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_common
```
```
In net/ipv4/af_inet.c (ffffffff81f54b87)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81f7f1ee)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f96a10)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa0bbe)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa7057)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81fa8995)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/garbage.c (ffffffff81fb0493)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81fb46ea)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/mcast.c (ffffffff81ff8b9e)
Location: include/linux/skbuff.h:2354
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
In net/ipv6/ip6mr.c (ffffffff8200fc52)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/mptcp/protocol.c (ffffffff8207754d)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff8207a900)
Location: include/linux/skbuff.h:2354
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
```
```
In net/mptcp/fastopen.c (ffffffff8208bade)
Location: include/linux/skbuff.h:2354
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
In kernel/audit.c (ffffffff81256440)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list_thread
```
```
In drivers/net/tun.c (ffffffff81cf8e3c)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_rx_batched
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d18f99)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
```
In drivers/net/xen-netfront.c (ffffffff81d22b76)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In net/core/skbuff.c (ffffffff81ecd665)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_errqueue_purge
  - net/core/skbuff.c:skb_errqueue_purge
  - net/core/skbuff.c:skb_queue_purge_reason
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff81ede7e5)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffff81ededc7)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81ef4a0d)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff81f04e61)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
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
In net/core/netpoll.c (ffffffff81f47a42)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81f5c0c8)
Location: include/linux/skbuff.h:2361
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
In net/core/gro_cells.c (ffffffff81f62157)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff81f6f7d2)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81fbfcb3)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81fd4494)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81fd7e97)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffffffff81feac2f)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffffffff82006855)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_common
```
```
In net/ipv4/af_inet.c (ffffffff8201adf7)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff8204586e)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/xfrm/xfrm_policy.c (ffffffff82063e3e)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8206df1e)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff82074307)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff82075c85)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/garbage.c (ffffffff8207dafd)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff82081f9a)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/mcast.c (ffffffff820c680e)
Location: include/linux/skbuff.h:2361
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
In net/ipv6/ip6mr.c (ffffffff820debe2)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/mptcp/protocol.c (ffffffff8214c57d)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff8214fd65)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
```
```
In net/mptcp/fastopen.c (ffffffff821618de)
Location: include/linux/skbuff.h:2361
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
In kernel/audit.c (ffff8000101ea488)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffff8000109e10ac)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000109fe0a8)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
```
In drivers/net/xen-netfront.c (ffff800010a08870)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffff800010bb3e94)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffff800010bbc950)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffff800010bbd400)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffff800010bd0200)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffff800010be2a14)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/skmsg.c (ffff800010c0ff90)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffff800010c10854)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffff800010c1b2e8)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffff800010c309f0)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffff800010c381d0)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffff800010c6533c)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffff800010c75f90)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffff800010c78644)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffff800010c855e0)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffff800010c9b040)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffff800010cab628)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffff800010ccde6c)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0b94)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffff800010ce9a94)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffff800010cee794)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffff800010cf4e8c)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffff800010cf8c28)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffff800010d458d4)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (c042a220)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (c0ac4ed8)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad10bc)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_overflow_check
  - drivers/net/ethernet/ti/cpts.c:cpts_fifo_read
  - drivers/net/ethernet/ti/cpts.c:cpts_fifo_read
```
```
In drivers/net/ppp/ppp_generic.c (c0adb9e0)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
```
In net/core/skbuff.c (c0ccde04)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (c0cd7e14)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (c0cd9894)
Location: include/linux/skbuff.h:2020
Inline: True
```
```
In net/core/dev.c (c0ce64a0)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (c0cfba1c)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (c0d27d94)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (c0d28978)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (c0d33688)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (c0d47ad4)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (c0d4a3ec)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (c0d74f70)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (c0d84654)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (c0d863f4)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (c0d948e4)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (c0da9a88)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (c0db8490)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (c0dd8d0c)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c0de9fdc)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (c0df1b8c)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (c0df65d8)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (c0dfba6c)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (c0dfeaac)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (c0e484e4)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (c00000000025b63c)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (c000000000aa2230)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa5d0c)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
```
In net/core/skbuff.c (c000000000c86898)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (c000000000c94518)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (c000000000c96ab8)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (c000000000cacf70)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (c000000000cc4f0c)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (c000000000cfc2e8)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (c000000000cfd308)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (c000000000d0c0e0)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (c000000000d29abc)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (c000000000d31060)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (c000000000d698a4)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (c000000000d7d9b8)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (c000000000d8036c)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (c000000000d917dc)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (c000000000dad020)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (c000000000dc1dd8)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (c000000000dea680)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000e02f60)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (c000000000e0d3e0)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (c000000000e13438)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (c000000000e1aec0)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (c000000000e1f17c)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (c000000000e7b550)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffe00015eeec)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffe00062ab12)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062b95e)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
```
In net/core/skbuff.c (ffffffe0007418b2)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffe00074a66e)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffe00074bbda)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffe00075a236)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffe00076901c)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffe00078c47a)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffe00078cfaa)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffe000795b32)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffe0007a6bc4)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffe0007a9562)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffe0007ccb78)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffe0007d916a)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffe0007da9d8)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffffffe0007e6eee)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffffffe0007f8958)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffe0008062b4)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffe00082004e)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082f862)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffe000837924)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b912)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffe000840b1a)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffe0008435ea)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffe000880bd0)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffff8116dc62)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff8178a73f)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178b974)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
```
In drivers/net/xen-netfront.c (ffffffff81792c9e)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff818b7438)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff818c1244)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffff818c2ad4)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff818d188f)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff818e29d9)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff81909d02)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff8190a63d)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81915480)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff8192896f)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff8192ca34)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff81954a03)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff8196309a)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81964fca)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffffffff81972847)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffffffff81986269)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff81995584)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff819b2e30)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c30d0)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819ca890)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff819cec58)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff819d3eaa)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff819d6c2a)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81a1b457)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffff81160e02)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff8176a08f)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81774744)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
```
In net/core/skbuff.c (ffffffff81871388)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff8187b184)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffff8187ca14)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff8188b713)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff8189c819)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff818c3b12)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff818c44ed)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff818cf230)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff818e271f)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff818e6534)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff8190e4f3)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff8191cb8a)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8191eaba)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffffffff8192c317)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffffffff8193fd29)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff8194f044)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff8196f460)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fec0)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81987680)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff8198ba18)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff81990c6a)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff819939ea)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff819d8217)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffff8116ba32)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff817baadf)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bbd14)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
```
In drivers/net/xen-netfront.c (ffffffff817c2efe)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81908438)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff81912244)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffff81913ad4)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff8192288f)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff81933a09)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff8195ad32)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff8195b66d)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff819664b0)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81979aff)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff8197dbc4)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff819bf1d3)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff819cd86a)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819cf79a)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffffffff819dd017)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffffffff819f0a39)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff819ffe24)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81a1d6d0)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2db50)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35310)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81a396d8)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff81a3e92a)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a416aa)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81a85ed7)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/audit.c (ffffffff811791f1)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/tun.c (ffffffff817d2f30)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d5f64)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
```
In drivers/net/xen-netfront.c (ffffffff817dd1be)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81929418)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
```
```
In net/core/datagram.c (ffffffff819333e4)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (ffffffff81934c64)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81943a5f)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:flush_backlog
```
```
In net/core/neighbour.c (ffffffff81953eac)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff8197cf52)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff8197d88d)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/drop_monitor.c (ffffffff81988740)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff8199c02f)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cell_poll
```
```
In net/sched/sch_generic.c (ffffffff819a0134)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_output.c (ffffffff819c8b53)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff819d73fa)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819d932a)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse_one
```
```
In net/ipv4/tcp_output.c (ffffffff819e6c97)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/udp.c (ffffffff819fc059)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
```
In net/ipv4/af_inet.c (ffffffff81a09f54)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ipmr.c (ffffffff81a28892)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3930c)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a40c30)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81a45106)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff81a4a297)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d30a)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81a929f9)
Location: include/linux/skbuff.h:2020
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
</details>
</li>
</ul>

## Differences
