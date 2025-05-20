# Function: <code>skb_peek_tail</code>

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
In net/core/sock.c (ffffffff817023e9)
Location: include/linux/skbuff.h:1416
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff81704f3d)
Location: include/linux/skbuff.h:1416
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/core/neighbour.c (ffffffff8172482f)
Location: include/linux/skbuff.h:1416
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/sched/sch_fifo.c (ffffffff81749015)
Location: include/linux/skbuff.h:1416
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_queue_drop
```
```
In net/ipv4/ip_output.c (ffffffff8175d334)
Location: include/linux/skbuff.h:1416
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81765c57)
Location: include/linux/skbuff.h:1416
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8176cc51)
Location: include/linux/skbuff.h:1416
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81776e0a)
Location: include/linux/skbuff.h:1416
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/unix/af_unix.c (ffffffff817bfa55)
Location: include/linux/skbuff.h:1416
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff817c49e3)
Location: include/linux/skbuff.h:1416
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/sock.c (ffffffff81769634)
Location: include/linux/skbuff.h:1517
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff8176bb0d)
Location: include/linux/skbuff.h:1517
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/core/neighbour.c (ffffffff8178e1ff)
Location: include/linux/skbuff.h:1517
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff817caed1)
Location: include/linux/skbuff.h:1517
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff817d349d)
Location: include/linux/skbuff.h:1517
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff817df3f1)
Location: include/linux/skbuff.h:1517
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff817e6167)
Location: include/linux/skbuff.h:1517
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffffffff8182c966)
Location: include/linux/skbuff.h:1517
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81831ab3)
Location: include/linux/skbuff.h:1517
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/sock.c (ffffffff8179653f)
Location: include/linux/skbuff.h:1532
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff81798bdd)
Location: include/linux/skbuff.h:1532
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/core/neighbour.c (ffffffff817bbbaf)
Location: include/linux/skbuff.h:1532
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff817fab31)
Location: include/linux/skbuff.h:1532
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818031f4)
Location: include/linux/skbuff.h:1532
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff8180f404)
Location: include/linux/skbuff.h:1532
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff81816887)
Location: include/linux/skbuff.h:1532
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffffffff8185e419)
Location: include/linux/skbuff.h:1532
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff818634e3)
Location: include/linux/skbuff.h:1532
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/sock.c (ffffffff817b46ff)
Location: include/linux/skbuff.h:1525
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff817b718d)
Location: include/linux/skbuff.h:1525
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/core/neighbour.c (ffffffff817da33f)
Location: include/linux/skbuff.h:1525
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff8181af2b)
Location: include/linux/skbuff.h:1525
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81823d2b)
Location: include/linux/skbuff.h:1525
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff8182f6d6)
Location: include/linux/skbuff.h:1525
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff81836b83)
Location: include/linux/skbuff.h:1525
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffffffff818837df)
Location: include/linux/skbuff.h:1525
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81887ba3)
Location: include/linux/skbuff.h:1525
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/sock.c (ffffffff8182c95f)
Location: include/linux/skbuff.h:1607
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff8182f78d)
Location: include/linux/skbuff.h:1607
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/neighbour.c (ffffffff81854adf)
Location: include/linux/skbuff.h:1607
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff81899f03)
Location: include/linux/skbuff.h:1607
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818a5763)
Location: include/linux/skbuff.h:1607
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff818af041)
Location: include/linux/skbuff.h:1607
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff818b622e)
Location: include/linux/skbuff.h:1607
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffffffff81903eeb)
Location: include/linux/skbuff.h:1607
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81908e63)
Location: include/linux/skbuff.h:1607
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/sock.c (ffffffff8187782f)
Location: include/linux/skbuff.h:1618
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff81879cad)
Location: include/linux/skbuff.h:1618
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/neighbour.c (ffffffff818a0105)
Location: include/linux/skbuff.h:1618
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff818ee3a7)
Location: include/linux/skbuff.h:1618
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818f6ed3)
Location: include/linux/skbuff.h:1618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81904888)
Location: include/linux/skbuff.h:1618
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff8190ba72)
Location: include/linux/skbuff.h:1618
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffffffff8195c01f)
Location: include/linux/skbuff.h:1618
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81960125)
Location: include/linux/skbuff.h:1618
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/sock.c (ffffffff8189894f)
Location: include/linux/skbuff.h:1698
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff8189a91d)
Location: include/linux/skbuff.h:1698
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/neighbour.c (ffffffff818c29c5)
Location: include/linux/skbuff.h:1698
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff8191bb77)
Location: include/linux/skbuff.h:1698
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81925543)
Location: include/linux/skbuff.h:1698
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81932a4a)
Location: include/linux/skbuff.h:1698
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff81939d42)
Location: include/linux/skbuff.h:1698
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffffffff81990831)
Location: include/linux/skbuff.h:1698
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81994f05)
Location: include/linux/skbuff.h:1698
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/sock.c (ffffffff818e2eeb)
Location: include/linux/skbuff.h:1788
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff818e4f44)
Location: include/linux/skbuff.h:1788
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/neighbour.c (ffffffff8190f095)
Location: include/linux/skbuff.h:1788
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff8197de57)
Location: include/linux/skbuff.h:1788
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81989240)
Location: include/linux/skbuff.h:1788
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81996572)
Location: include/linux/skbuff.h:1788
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff8199e002)
Location: include/linux/skbuff.h:1788
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffffffff819fbf1e)
Location: include/linux/skbuff.h:1788
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81a009a5)
Location: include/linux/skbuff.h:1788
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/sock.c (ffffffff819150cb)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff819170d4)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/neighbour.c (ffffffff81941705)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff819b47fb)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819c06a6)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff819cd0e8)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff819d4ac2)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffffffff81a32bae)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81a37575)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/sock.c (ffffffff819e843b)
Location: include/linux/skbuff.h:1809
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff819e9a54)
Location: include/linux/skbuff.h:1809
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/neighbour.c (ffffffff81a112f5)
Location: include/linux/skbuff.h:1809
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff81a9e9a7)
Location: include/linux/skbuff.h:1809
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aab1b9)
Location: include/linux/skbuff.h:1809
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81ab1c32)
Location: include/linux/skbuff.h:1809
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1492)
Location: include/linux/skbuff.h:1809
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_tso_should_defer
```
```
In net/unix/af_unix.c (ffffffff81b247b1)
Location: include/linux/skbuff.h:1809
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81b2ca95)
Location: include/linux/skbuff.h:1809
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
```
```
In net/mptcp/protocol.c (ffffffff81bab625)
Location: include/linux/skbuff.h:1809
Inline: True
Inline callers:
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
In net/core/sock.c (ffffffff819e80db)
Location: include/linux/skbuff.h:1830
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff819e97f4)
Location: include/linux/skbuff.h:1830
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/neighbour.c (ffffffff81a11645)
Location: include/linux/skbuff.h:1830
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff81aa88f7)
Location: include/linux/skbuff.h:1830
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ab610a)
Location: include/linux/skbuff.h:1830
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81abcbf2)
Location: include/linux/skbuff.h:1830
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81accf02)
Location: include/linux/skbuff.h:1830
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_tso_should_defer
```
```
In net/unix/af_unix.c (ffffffff81b33211)
Location: include/linux/skbuff.h:1830
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81b3b4b9)
Location: include/linux/skbuff.h:1830
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
```
```
In net/mptcp/protocol.c (ffffffff81bba08c)
Location: include/linux/skbuff.h:1830
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In net/core/sock.c (ffffffff819ce20e)
Location: include/linux/skbuff.h:1846
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff819cf914)
Location: include/linux/skbuff.h:1846
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/neighbour.c (ffffffff819f83c5)
Location: include/linux/skbuff.h:1846
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff81a93a17)
Location: include/linux/skbuff.h:1846
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aa12df)
Location: include/linux/skbuff.h:1846
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81aa8272)
Location: include/linux/skbuff.h:1846
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ab80d2)
Location: include/linux/skbuff.h:1846
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_tso_should_defer
```
```
In net/unix/af_unix.c (ffffffff81b20f4d)
Location: include/linux/skbuff.h:1846
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81b28c38)
Location: include/linux/skbuff.h:1846
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
```
```
In net/mptcp/protocol.c (ffffffff81baf7f6)
Location: include/linux/skbuff.h:1846
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In kernel/audit.c (ffffffff811acb95)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In net/core/sock.c (ffffffff81a7dabe)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff81a7f464)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:msg_zerocopy_callback
```
```
In net/core/neighbour.c (ffffffff81aaa035)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff81b4ee57)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81b5d270)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81b63e32)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81b752b2)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffffffff81be600d)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81beeb28)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
```
```
In net/mptcp/protocol.c (ffffffff81c78a25)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In kernel/audit.c (ffffffff811de755)
Location: include/linux/skbuff.h:2226
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In net/core/sock.c (ffffffff81bf115e)
Location: include/linux/skbuff.h:2226
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff81bf3794)
Location: include/linux/skbuff.h:2226
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/neighbour.c (ffffffff81c22705)
Location: include/linux/skbuff.h:2226
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff81cdc79a)
Location: include/linux/skbuff.h:2226
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81cebc71)
Location: include/linux/skbuff.h:2226
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81cf2b52)
Location: include/linux/skbuff.h:2226
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81d04b02)
Location: include/linux/skbuff.h:2226
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffffffff81d7d1fd)
Location: include/linux/skbuff.h:2226
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81d871a8)
Location: include/linux/skbuff.h:2226
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
```
```
In net/mptcp/protocol.c (ffffffff81e1eee1)
Location: include/linux/skbuff.h:2226
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In kernel/audit.c (ffffffff81224305)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In net/core/sock.c (ffffffff81d9d91e)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff81da1514)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/neighbour.c (ffffffff81dd4b85)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff81e9d1fa)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81eafb31)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81eb7152)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ec9b52)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffffffff81f4a577)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81f54cc8)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
```
```
In net/mptcp/protocol.c (ffffffff81ff5aa1)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/fastopen.c (ffffffff8200f060)
Location: include/linux/skbuff.h:2084
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_gen_msk_ackseq
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
In kernel/audit.c (ffffffff8123a8e5)
Location: include/linux/skbuff.h:2120
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In net/core/sock.c (ffffffff81e0c195)
Location: include/linux/skbuff.h:2120
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff81e0fe04)
Location: include/linux/skbuff.h:2120
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/neighbour.c (ffffffff81e457f5)
Location: include/linux/skbuff.h:2120
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff81ef9cc7)
Location: include/linux/skbuff.h:2120
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81f0df81)
Location: include/linux/skbuff.h:2120
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_eof
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81f15572)
Location: include/linux/skbuff.h:2120
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81f286a2)
Location: include/linux/skbuff.h:2120
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffffffff81faa217)
Location: include/linux/skbuff.h:2120
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/ipv6/ip6_output.c (ffffffff81fb46d8)
Location: include/linux/skbuff.h:2120
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
```
```
In net/mptcp/protocol.c (ffffffff82071b91)
Location: include/linux/skbuff.h:2120
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/fastopen.c (ffffffff8208bc50)
Location: include/linux/skbuff.h:2120
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_gen_msk_ackseq
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
In kernel/audit.c (ffffffff812545d5)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In net/core/sock.c (ffffffff81ec8b37)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff81ecc8b4)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/neighbour.c (ffffffff81f04485)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff81fbdbf7)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81fd208d)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_eof
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81fd9bd2)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81fed132)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffffffff82077637)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/ipv6/ip6_output.c (ffffffff82081f88)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
```
```
In net/mptcp/protocol.c (ffffffff82145e83)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/fastopen.c (ffffffff82161a35)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:__mptcp_fastopen_gen_msk_ackseq
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
In net/core/sock.c (ffff800010badf68)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffff800010bb3cbc)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/neighbour.c (ffff800010be2848)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffff800010c64fac)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffff800010c70b30)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffff800010c7fbe0)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffff800010c87710)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffff800010cf234c)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffff800010cf8c14)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/sock.c (c0ccba00)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (c0ccdaec)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/neighbour.c (c0cfbafc)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (c0d74bd4)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (c0d7fb98)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (c0d8ede4)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (c0d96a4c)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (c0dfa28c)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (c0dfea80)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_append_data
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
In net/core/sock.c (c000000000c83950)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (c000000000c861d4)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/neighbour.c (c000000000cc2cc4)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (c000000000d69308)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (c000000000d77bf8)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (c000000000d8a4e4)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (c000000000d94270)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (c000000000e187a0)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (c000000000e1f07c)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/sock.c (ffffffe00073ff62)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffe00074152e)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/neighbour.c (ffffffe000767bf0)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffe0007cc868)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffe0007d639e)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffe0007e1c5e)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffe0007e8a9a)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffffffe00083f47e)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffe0008435da)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/sock.c (ffffffff818b50cb)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff818b70d4)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/neighbour.c (ffffffff818e16d5)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff8195466b)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81960516)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff8196cf58)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff81974932)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffffffff819d223e)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff819d6c05)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/sock.c (ffffffff8186f01b)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff81871024)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/neighbour.c (ffffffff8189b515)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff8190e15b)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8191a006)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81926a48)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff8192e3f2)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffffffff8198effe)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff819939c5)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/sock.c (ffffffff819060cb)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff819080d4)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/neighbour.c (ffffffff81932705)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff819bee3b)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819cace6)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff819d7728)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff819df102)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffffffff81a3ccbe)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81a41685)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/sock.c (ffffffff819270fb)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
```
```
In net/core/skbuff.c (ffffffff81929114)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/neighbour.c (ffffffff81953dc5)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
```
```
In net/ipv4/ip_output.c (ffffffff819c87bb)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819d4876)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff819e1348)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff819e8da2)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/unix/af_unix.c (ffffffff81a4827a)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d2e5)
Location: include/linux/skbuff.h:1798
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
```
</details>
</li>
</ul>

## Differences
