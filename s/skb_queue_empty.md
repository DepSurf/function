# Function: <code>skb_queue_empty</code>

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
In drivers/net/tun.c (0)
Location: include/linux/skbuff.h:1127
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:1127
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/skbuff.h:1127
Inline: True
```
```
In net/core/datagram.c (ffffffff8170ccf7)
Location: include/linux/skbuff.h:1127
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/core/stream.c (0)
Location: include/linux/skbuff.h:1127
Inline: True
```
```
In net/core/dev.c (ffffffff8171b95d)
Location: include/linux/skbuff.h:1127
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/skbuff.h:1127
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/skbuff.h:1127
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/skbuff.h:1127
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81769dc4)
Location: include/linux/skbuff.h:1127
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8176e972)
Location: include/linux/skbuff.h:1127
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/skbuff.h:1127
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/skbuff.h:1127
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b39e1)
Location: include/linux/skbuff.h:1127
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/unix/af_unix.c (0)
Location: include/linux/skbuff.h:1127
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:1127
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/skbuff.h:1127
Inline: True
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
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:1218
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/skbuff.h:1218
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/skbuff.h:1218
Inline: True
```
```
In net/core/dev.c (ffffffff8178343f)
Location: include/linux/skbuff.h:1218
Inline: True
Inline callers:
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:process_backlog
```
```
In net/sched/sch_generic.c (ffffffff817adbbf)
Location: include/linux/skbuff.h:1218
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_reset
```
```
In net/sched/sch_fifo.c (ffffffff817b6001)
Location: include/linux/skbuff.h:1218
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/skbuff.h:1218
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/skbuff.h:1218
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817d6667)
Location: include/linux/skbuff.h:1218
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_input.c (ffffffff817def60)
Location: include/linux/skbuff.h:1218
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/skbuff.h:1218
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/skbuff.h:1218
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81822f30)
Location: include/linux/skbuff.h:1218
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/unix/af_unix.c (0)
Location: include/linux/skbuff.h:1218
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:1218
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/skbuff.h:1218
Inline: True
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
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:1233
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/skbuff.h:1233
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/skbuff.h:1233
Inline: True
```
```
In net/core/dev.c (ffffffff817aed15)
Location: include/linux/skbuff.h:1233
Inline: True
Inline callers:
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:process_backlog
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/skbuff.h:1233
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/skbuff.h:1233
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818065b6)
Location: include/linux/skbuff.h:1233
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8180b5a7)
Location: include/linux/skbuff.h:1233
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/skbuff.h:1233
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/skbuff.h:1233
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/skbuff.h:1233
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81854873)
Location: include/linux/skbuff.h:1233
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/unix/af_unix.c (0)
Location: include/linux/skbuff.h:1233
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:1233
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/skbuff.h:1233
Inline: True
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
In drivers/net/tun.c (ffffffff81694c31)
Location: include/linux/skbuff.h:1226
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:1226
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/skbuff.h:1226
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/skbuff.h:1226
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/skbuff.h:1226
Inline: True
```
```
In net/core/dev.c (ffffffff817cf27b)
Location: include/linux/skbuff.h:1226
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/skbuff.h:1226
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/skbuff.h:1226
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81826858)
Location: include/linux/skbuff.h:1226
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff8182be28)
Location: include/linux/skbuff.h:1226
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/skbuff.h:1226
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/skbuff.h:1226
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81845d03)
Location: include/linux/skbuff.h:1226
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff81878334)
Location: include/linux/skbuff.h:1226
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/unix/af_unix.c (0)
Location: include/linux/skbuff.h:1226
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:1226
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/skbuff.h:1226
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
In drivers/net/tun.c (ffffffff816ff4c0)
Location: include/linux/skbuff.h:1328
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:1328
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/skbuff.h:1328
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/skbuff.h:1328
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/skbuff.h:1328
Inline: True
```
```
In net/core/dev.c (ffffffff81848bd6)
Location: include/linux/skbuff.h:1328
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/skbuff.h:1328
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/skbuff.h:1328
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/skbuff.h:1328
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff818ae5a6)
Location: include/linux/skbuff.h:1328
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/skbuff.h:1328
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/skbuff.h:1328
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c5730)
Location: include/linux/skbuff.h:1328
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8c44)
Location: include/linux/skbuff.h:1328
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff818feb22)
Location: include/linux/skbuff.h:1328
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/unix/af_unix.c (0)
Location: include/linux/skbuff.h:1328
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:1328
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/skbuff.h:1328
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
In kernel/bpf/sockmap.c (ffffffff811cedbd)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
```
```
In drivers/net/tun.c (ffffffff8173ee6e)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81744243)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
```
In net/core/sock.c (ffffffff818754c5)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (ffffffff818842b7)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/core/stream.c (ffffffff81884e7d)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81892c4f)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/sched/sch_generic.c (ffffffff818ccbcc)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netlink/af_netlink.c (ffffffff818d9fd5)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_output.c (ffffffff818ee2df)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818f6dfc)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81902a66)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8190c47b)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff8190c6aa)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/udp.c (ffffffff8191dde0)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194f678)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff819556a8)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81958477)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81959de0)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6_output.c (ffffffff8196219b)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (ffffffff81984142)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
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
In drivers/net/tun.c (ffffffff8176305e)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81768343)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
```
In net/core/sock.c (ffffffff81895d95)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (ffffffff818a4729)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff818a58ed)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff818b6c2f)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/sched/sch_generic.c (ffffffff818f7f3c)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netlink/af_netlink.c (ffffffff81906acf)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_output.c (ffffffff8191baaf)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8192546c)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81930db0)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8193a75b)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff8193a9d4)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/udp.c (ffffffff8194ca30)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (ffffffff81977f49)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff81982cb2)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a2b8)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff8198d077)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff8198ef35)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6_output.c (ffffffff81996bdb)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (ffffffff819ba68a)
Location: include/linux/skbuff.h:1408
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
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
In drivers/net/tun.c (ffffffff817a0bd1)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a5d29)
Location: include/linux/skbuff.h:1498
Inline: True
```
```
In net/core/sock.c (ffffffff818e02a5)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (ffffffff818efea5)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff818f0c0d)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81903e46)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/sched/sch_generic.c (ffffffff81957679)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netlink/af_netlink.c (ffffffff81967d6f)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_output.c (ffffffff8197dd8f)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8198913f)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81994410)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8199eaaf)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff8199ed84)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/udp.c (ffffffff819b11e0)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e1a7c)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ec99f)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4528)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff819f88e7)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff819fa6b0)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6_output.c (ffffffff81a03150)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (ffffffff81a29788)
Location: include/linux/skbuff.h:1498
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
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
In drivers/net/tun.c (ffffffff817c5ba1)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c9779)
Location: include/linux/skbuff.h:1495
Inline: True
```
```
In net/core/stream.c (ffffffff81922b5d)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81934fa6)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81975c12)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/sched/sch_generic.c (ffffffff8198db19)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netlink/af_netlink.c (ffffffff8199e80f)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_output.c (ffffffff819b472f)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819c1d9b)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (ffffffff819caf60)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff819d55bf)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff819d5824)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/udp.c (ffffffff819e69cb)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a18a8c)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a239af)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b1c8)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f547)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81a310e6)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6_output.c (ffffffff81a39d20)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (ffffffff81a602e4)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
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
In drivers/net/tun.c (ffffffff8188e53a)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_receive
  - drivers/net/tun.c:tun_napi_receive
  - drivers/net/tun.c:tun_napi_receive
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81895411)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
```
```
In net/core/stream.c (ffffffff819f629b)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81a09c47)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81a4ac50)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/sched/sch_generic.c (ffffffff81a655cd)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/netlink/af_netlink.c (ffffffff81a7842f)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_output.c (ffffffff81a9e8e2)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81aaa358)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (ffffffff81ab27fe)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_queue
```
```
In net/ipv4/udp.c (ffffffff81ad4154)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b099a4)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b158cc)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d848)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81b22157)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/xfrm/espintcp.c (ffffffff81b22a8d)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_poll
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/af_unix.c (ffffffff81b25834)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f550)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (ffffffff81b58dcf)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81bac344)
Location: include/linux/skbuff.h:1506
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In drivers/net/tun.c (ffffffff8189caca)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_receive
  - drivers/net/tun.c:tun_napi_receive
  - drivers/net/tun.c:tun_napi_receive
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a3b41)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
```
```
In net/core/stream.c (ffffffff819f5adb)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81a0b1ec)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/skmsg.c (ffffffff81a3f1e0)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
```
```
In net/core/drop_monitor.c (ffffffff81a50890)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/sched/sch_generic.c (ffffffff81a6d6e1)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81aa8832)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81ab5e28)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (ffffffff81abdb3e)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_queue
```
```
In net/ipv4/udp.c (ffffffff81ae0694)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17dbe)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b23d27)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c118)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30b57)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/xfrm/espintcp.c (ffffffff81b3120d)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_poll
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/af_unix.c (ffffffff81b34244)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6_output.c (ffffffff81b3dfa0)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (ffffffff81b6740c)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81bc0923)
Location: include/linux/skbuff.h:1527
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In drivers/net/tun.c (ffffffff8187f6ea)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81885851)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81887bd8)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_poll
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
```
```
In net/core/stream.c (ffffffff819dbc83)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff819f3798)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/drop_monitor.c (ffffffff81a35672)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/skmsg.c (ffffffff81a4e3a1)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_msg_wait_data
  - net/core/skmsg.c:sk_msg_wait_data
```
```
In net/sched/sch_generic.c (ffffffff81a55e51)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a93952)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81aa1008)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (ffffffff81aa910a)
Location: include/linux/skbuff.h:1543
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81acc680)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b059b8)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11927)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19d78)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e887)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/xfrm/espintcp.c (ffffffff81b1ef3d)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_poll
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/af_unix.c (ffffffff81b21d84)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b450)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (ffffffff81b55550)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81bb06e3)
Location: include/linux/skbuff.h:1543
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_sendmsg
```
```
In net/mptcp/subflow.c (ffffffff81bb2b6e)
Location: include/linux/skbuff.h:1543
Inline: True
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
In drivers/net/tun.c (ffffffff8191085a)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff819171e1)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8191961c)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_poll
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
```
```
In net/core/stream.c (ffffffff81a8be09)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81aa50e8)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/drop_monitor.c (ffffffff81aeb242)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/skmsg.c (ffffffff81b070b7)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
```
```
In net/sched/sch_generic.c (ffffffff81b0ec01)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81b4ed92)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81b5ce58)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (ffffffff81b64e5a)
Location: include/linux/skbuff.h:1556
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b8af10)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc8526)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81bc8a79)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd5417)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde318)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81be33c7)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/xfrm/espintcp.c (ffffffff81be3a7d)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_poll
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/af_unix.c (ffffffff81be72b4)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_dgram_disconnected
```
```
In net/unix/unix_bpf.c (ffffffff81beb7bc)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_msg_wait_data
  - net/unix/unix_bpf.c:unix_msg_wait_data
  - net/unix/unix_bpf.c:unix_msg_wait_data
  - net/unix/unix_bpf.c:unix_msg_wait_data
```
```
In net/ipv6/ip6_output.c (ffffffff81bf157f)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (ffffffff81c1e029)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81c7e69a)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
```
```
In net/mptcp/subflow.c (ffffffff81c810fe)
Location: include/linux/skbuff.h:1556
Inline: True
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
In drivers/net/tun.c (ffffffff81a66ed4)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6b5b7)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6e899)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_poll
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
```
```
In net/core/stream.c (ffffffff81c016ee)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81c1ba0d)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/drop_monitor.c (ffffffff81c6daa7)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/skmsg.c (ffffffff81c8bc96)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
```
```
In net/sched/sch_generic.c (ffffffff81c95de1)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81cdc6d2)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81ceb816)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (ffffffff81cf3d10)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/ipv4/udp.c (ffffffff81d1acf9)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5d89f)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81d5e0d2)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6bc27)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81d7510f)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a5f6)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/xfrm/espintcp.c (ffffffff81d7b01d)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_poll
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/af_unix.c (ffffffff81d7e8f0)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_dgram_disconnected
```
```
In net/unix/unix_bpf.c (ffffffff81d83aa7)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81d89dec)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (ffffffff81dba69f)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81e23a43)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
```
```
In net/mptcp/subflow.c (ffffffff81e26b1a)
Location: include/linux/skbuff.h:1905
Inline: True
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
In drivers/net/tun.c (ffffffff81bf2506)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfe467)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c0336b)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_poll
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
```
```
In net/core/stream.c (ffffffff81db0a8a)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81dcc9ce)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/drop_monitor.c (ffffffff81e25717)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/skmsg.c (ffffffff81e48020)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
```
```
In net/sched/sch_generic.c (ffffffff81e519c1)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81e9d132)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81eaf4b6)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (ffffffff81eb8719)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/ipv4/udp.c (ffffffff81ee2299)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_common
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27adf)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81f28839)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f36f67)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81f412d4)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81f47506)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/xfrm/espintcp.c (ffffffff81f47d1d)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_poll
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/af_unix.c (ffffffff81f4ba19)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_dgram_disconnected
```
```
In net/unix/unix_bpf.c (ffffffff81f512a7)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81f57d98)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (ffffffff81f8a767)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81ffb183)
Location: include/linux/skbuff.h:1763
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
```
```
In net/mptcp/subflow.c (ffffffff81ffe29a)
Location: include/linux/skbuff.h:1763
Inline: True
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
In drivers/net/tun.c (ffffffff81c4b196)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c63aa7)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c686b2)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_poll
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
```
```
In net/core/stream.c (ffffffff81e20f4a)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81e3d52e)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/drop_monitor.c (ffffffff81e9ac57)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/skmsg.c (ffffffff81ea3146)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
```
```
In net/sched/sch_generic.c (ffffffff81ead20b)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81efaec5)
Location: include/linux/skbuff.h:1799
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81f0d8c8)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (ffffffff81f16b8b)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/ipv4/udp.c (ffffffff81f41d99)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_common
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f878c5)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/ipv4/udp_bpf.c (ffffffff81f88190)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f968ed)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa0b64)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6fd6)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/xfrm/espintcp.c (ffffffff81fa781d)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_poll
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/af_unix.c (ffffffff81fab7ce)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_dgram_disconnected
```
```
In net/unix/unix_bpf.c (ffffffff81fb0b15)
Location: include/linux/skbuff.h:1799
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81fb7942)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (ffffffff81fe9e4a)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff82077503)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
```
```
In net/mptcp/subflow.c (ffffffff8207bc68)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_check_data_avail
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
In drivers/net/tun.c (ffffffff81cf8da9)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_rx_batched
  - drivers/net/tun.c:tun_rx_batched
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1a4c7)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
```
```
In net/core/skbuff.c (ffffffff81ed9417)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_purge_reason
```
```
In net/core/stream.c (ffffffff81edee1f)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81efbdce)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/drop_monitor.c (ffffffff81f5d3b0)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/skmsg.c (ffffffff81f65466)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
```
```
In net/sched/sch_generic.c (ffffffff81f6fcab)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_output.c (ffffffff81fbedc5)
Location: include/linux/skbuff.h:1806
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81fd19d8)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (ffffffff81fdb9f6)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/ipv4/udp.c (ffffffff82007c29)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_common
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204ef5b)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/ipv4/udp_bpf.c (ffffffff8204f8b0)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/xfrm/xfrm_policy.c (ffffffff82063cec)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff8206dec4)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff82074286)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/xfrm/espintcp.c (ffffffff82074add)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_poll
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/unix/af_unix.c (ffffffff82078bbe)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_dgram_disconnected
```
```
In net/unix/unix_bpf.c (ffffffff8207e1b5)
Location: include/linux/skbuff.h:1806
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff82084f72)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (ffffffff820b79b7)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff8214c533)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
```
```
In net/mptcp/subflow.c (ffffffff8215109b)
Location: include/linux/skbuff.h:1806
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_check_data_avail
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
In drivers/net/tun.c (ffff8000109e0a58)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a00720)
Location: include/linux/skbuff.h:1495
Inline: True
```
```
In net/core/stream.c (ffff800010bbd450)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffff800010bd3260)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffff800010c1c06c)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/sched/sch_generic.c (ffff800010c39208)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netlink/af_netlink.c (ffff800010c4d500)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_output.c (ffff800010c64efc)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffff800010c74b04)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (ffff800010c7d8a0)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffff800010c8826c)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffff800010c889c0)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/udp.c (ffff800010c99e04)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd4560)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0b34)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffff800010ce9a48)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffff800010cee6f4)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffff800010cf138c)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6_output.c (ffff800010cf9c34)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (ffff800010d25984)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
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
In drivers/net/tun.c (c0ac4e04)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad1058)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_overflow_check
  - drivers/net/ethernet/ti/cpts.c:cpts_overflow_check
```
```
In drivers/net/ppp/ppp_generic.c (c0adf144)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
```
```
In net/core/stream.c (c0cd98ec)
Location: include/linux/skbuff.h:1495
Inline: True
```
```
In net/core/dev.c (c0cedf78)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (c0d33ebc)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/sched/sch_generic.c (c0d4b554)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netlink/af_netlink.c (c0d5c68c)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_output.c (c0d74b18)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (c0d831d8)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (c0d8caa4)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (c0d97544)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (c0d977a8)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/udp.c (c0daa3fc)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (c0dde6f0)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (c0de9eb4)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (c0df1b48)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (c0df6540)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (c0df83c8)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6_output.c (c0e01474)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (c0e29224)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
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
In drivers/net/tun.c (c000000000aa2164)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aaa8d4)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
```
```
In net/core/stream.c (c000000000c96b24)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (c000000000cb1cf4)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (c000000000d0a9e8)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/drop_monitor.c:__net_dm_cpu_data_fini
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/sched/sch_generic.c (c000000000d31ddc)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netlink/af_netlink.c (c000000000d4a0d0)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_output.c (c000000000d6922c)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (c000000000d7c044)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (c000000000d87720)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (c000000000d95180)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (c000000000d95498)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/udp.c (c000000000dab464)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (c000000000df26b0)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (c000000000e02e94)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (c000000000e0d380)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (c000000000e1336c)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (c000000000e16344)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6_output.c (c000000000e21e98)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (c000000000e5543c)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
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
In drivers/net/tun.c (ffffffe00062aa62)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062dec6)
Location: include/linux/skbuff.h:1495
Inline: True
```
```
In net/core/stream.c (ffffffe00074bc3e)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffe00075d57c)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffe000796134)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/sched/sch_generic.c (ffffffe0007aa66c)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netlink/af_netlink.c (ffffffe0007b929e)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_output.c (ffffffe0007cc7ea)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffe0007d7f74)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (ffffffe0007e00a6)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffe0007e94aa)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9702)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/udp.c (ffffffe0007f8fa4)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (ffffffe00082544e)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082f7ec)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffe0008378d4)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b884)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffe00083d570)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6_output.c (ffffffe0008458a8)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (ffffffe0008663f0)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
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
In drivers/net/tun.c (ffffffff8178a681)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178e259)
Location: include/linux/skbuff.h:1495
Inline: True
```
```
In net/core/stream.c (ffffffff818c2b5d)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff818d4f86)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81915be2)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/sched/sch_generic.c (ffffffff8192d989)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netlink/af_netlink.c (ffffffff8193e67f)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_output.c (ffffffff8195459f)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81961c0b)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (ffffffff8196add0)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8197542f)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff81975694)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/udp.c (ffffffff8198683b)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b811c)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c303f)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff819ca858)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff819cebd7)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff819d0776)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6_output.c (ffffffff819d93b0)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (ffffffff819ff974)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
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
In drivers/net/tun.c (ffffffff81769fd1)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81777029)
Location: include/linux/skbuff.h:1495
Inline: True
```
```
In net/core/stream.c (ffffffff8187ca9d)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff8188ee04)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff818cf992)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/sched/sch_generic.c (ffffffff818e7489)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netlink/af_netlink.c (ffffffff818f817f)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_output.c (ffffffff8190e08f)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8191b6fb)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (ffffffff819248c0)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8192eeef)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f154)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/udp.c (ffffffff819402fb)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974f0c)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fe2f)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81987648)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b997)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff8198d536)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6_output.c (ffffffff81996170)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (ffffffff819bc734)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
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
In drivers/net/tun.c (ffffffff817baa21)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817be5f9)
Location: include/linux/skbuff.h:1495
Inline: True
```
```
In net/core/stream.c (ffffffff81913b5d)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81925fa6)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81966c12)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/sched/sch_generic.c (ffffffff8197eb19)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netlink/af_netlink.c (ffffffff8198f80f)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_output.c (ffffffff819bed6f)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819cc3db)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (ffffffff819d55a0)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff819dfbff)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff819dfe64)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/udp.c (ffffffff819f100b)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a22b9c)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2dabf)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81a352d8)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81a39657)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81a3b1f6)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6_output.c (ffffffff81a43e30)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (ffffffff81a6a3f4)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
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
In drivers/net/tun.c (ffffffff817d2e7b)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d70e8)
Location: include/linux/skbuff.h:1495
Inline: True
```
```
In net/core/stream.c (ffffffff81934ced)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/dev.c (ffffffff81947557)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81988ea2)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/sched/sch_generic.c (ffffffff819a1089)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netlink/af_netlink.c (ffffffff819b20ef)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_output.c (ffffffff819c86ef)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819d5f6b)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (ffffffff819df180)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff819e98af)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff819e9b24)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/udp.c (ffffffff819f93f9)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2df60)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3927d)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81a40bf8)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81a45087)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81a489d2)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6_output.c (ffffffff81a4fad0)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
```
```
In net/ipv6/udp.c (ffffffff81a76a1f)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
</details>
</li>
</ul>

## Differences
