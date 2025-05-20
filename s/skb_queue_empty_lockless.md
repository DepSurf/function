# Function: <code>skb_queue_empty_lockless</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81912455)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (ffffffff81921ec5)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff819c059f)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff819e7ec0)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
```
```
In net/unix/af_unix.c (ffffffff81a31330)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/sock.c (ffffffff819e42d5)
Location: include/linux/skbuff.h:1518
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (ffffffff819f5105)
Location: include/linux/skbuff.h:1518
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81aab612)
Location: include/linux/skbuff.h:1518
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81ad4e30)
Location: include/linux/skbuff.h:1518
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
```
```
In net/unix/af_unix.c (ffffffff81b252ec)
Location: include/linux/skbuff.h:1518
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/sock.c (ffffffff819e3b55)
Location: include/linux/skbuff.h:1539
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (ffffffff819f4b35)
Location: include/linux/skbuff.h:1539
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/dev.c (ffffffff81a047ce)
Location: include/linux/skbuff.h:1539
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/netlink/af_netlink.c (ffffffff81a81224)
Location: include/linux/skbuff.h:1539
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/tcp.c (ffffffff81ab6af2)
Location: include/linux/skbuff.h:1539
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81ae1370)
Location: include/linux/skbuff.h:1539
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
```
```
In net/unix/af_unix.c (ffffffff81b33e5c)
Location: include/linux/skbuff.h:1539
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/mptcp/protocol.c (ffffffff81bbe0ed)
Location: include/linux/skbuff.h:1539
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In net/core/sock.c (ffffffff819c9be5)
Location: include/linux/skbuff.h:1555
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (ffffffff819dacc5)
Location: include/linux/skbuff.h:1555
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/dev.c (ffffffff819ebfe5)
Location: include/linux/skbuff.h:1555
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/netlink/af_netlink.c (ffffffff81a6999d)
Location: include/linux/skbuff.h:1555
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/tcp.c (ffffffff81aa1cb4)
Location: include/linux/skbuff.h:1555
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81acd2d0)
Location: include/linux/skbuff.h:1555
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
```
```
In net/unix/af_unix.c (ffffffff81b2180c)
Location: include/linux/skbuff.h:1555
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/mptcp/protocol.c (ffffffff81bb0377)
Location: include/linux/skbuff.h:1555
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In net/core/sock.c (ffffffff81a79085)
Location: include/linux/skbuff.h:1568
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (ffffffff81a8b345)
Location: include/linux/skbuff.h:1568
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/dev.c (ffffffff81a9cf92)
Location: include/linux/skbuff.h:1568
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/netlink/af_netlink.c (ffffffff81b22f5a)
Location: include/linux/skbuff.h:1568
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/tcp.c (ffffffff81b5e7c4)
Location: include/linux/skbuff.h:1568
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81b8bc54)
Location: include/linux/skbuff.h:1568
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
```
```
In net/unix/af_unix.c (ffffffff81be6b5c)
Location: include/linux/skbuff.h:1568
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/mptcp/protocol.c (ffffffff81c77b45)
Location: include/linux/skbuff.h:1568
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In net/core/sock.c (ffffffff81becd75)
Location: include/linux/skbuff.h:1917
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (ffffffff81c005f6)
Location: include/linux/skbuff.h:1917
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/dev.c (ffffffff81c0f703)
Location: include/linux/skbuff.h:1917
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/neighbour.c (ffffffff81c2737c)
Location: include/linux/skbuff.h:1917
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81cabb37)
Location: include/linux/skbuff.h:1917
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/tcp.c (ffffffff81ced1b8)
Location: include/linux/skbuff.h:1917
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81d1a774)
Location: include/linux/skbuff.h:1917
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
```
```
In net/unix/af_unix.c (ffffffff81d7d53f)
Location: include/linux/skbuff.h:1917
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/mptcp/protocol.c (ffffffff81e1d006)
Location: include/linux/skbuff.h:1917
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In net/core/sock.c (ffffffff81d992f5)
Location: include/linux/skbuff.h:1775
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (ffffffff81dafdf6)
Location: include/linux/skbuff.h:1775
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/dev.c (ffffffff81dc2075)
Location: include/linux/skbuff.h:1775
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/neighbour.c (ffffffff81dd9ed8)
Location: include/linux/skbuff.h:1775
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e68957)
Location: include/linux/skbuff.h:1775
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/tcp.c (ffffffff81eb10e4)
Location: include/linux/skbuff.h:1775
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81ee1494)
Location: include/linux/skbuff.h:1775
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
```
```
In net/unix/af_unix.c (ffffffff81f4ad4f)
Location: include/linux/skbuff.h:1775
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/mptcp/protocol.c (ffffffff81ff4543)
Location: include/linux/skbuff.h:1775
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In net/core/sock.c (ffffffff81e07615)
Location: include/linux/skbuff.h:1811
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (ffffffff81e20066)
Location: include/linux/skbuff.h:1811
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/dev.c (ffffffff81e315d5)
Location: include/linux/skbuff.h:1811
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/neighbour.c (ffffffff81e4ac38)
Location: include/linux/skbuff.h:1811
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec47e3)
Location: include/linux/skbuff.h:1811
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/tcp.c (ffffffff81f0f774)
Location: include/linux/skbuff.h:1811
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81f40ed4)
Location: include/linux/skbuff.h:1811
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f8640b)
Location: include/linux/skbuff.h:1811
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/unix/af_unix.c (ffffffff81faaa08)
Location: include/linux/skbuff.h:1811
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/mptcp/protocol.c (ffffffff82070f16)
Location: include/linux/skbuff.h:1811
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In net/core/sock.c (ffffffff81ec4005)
Location: include/linux/skbuff.h:1818
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ecd624)
Location: include/linux/skbuff.h:1818
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_queue_purge_reason
```
```
In net/core/datagram.c (ffffffff81eddf46)
Location: include/linux/skbuff.h:1818
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/dev.c (ffffffff81eefd55)
Location: include/linux/skbuff.h:1818
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/neighbour.c (ffffffff81f09958)
Location: include/linux/skbuff.h:1818
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f87bab)
Location: include/linux/skbuff.h:1818
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/tcp.c (ffffffff81fd3964)
Location: include/linux/skbuff.h:1818
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff82006b24)
Location: include/linux/skbuff.h:1818
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204d9fa)
Location: include/linux/skbuff.h:1818
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/unix/af_unix.c (ffffffff82077df8)
Location: include/linux/skbuff.h:1818
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/mptcp/protocol.c (ffffffff8214b4e0)
Location: include/linux/skbuff.h:1818
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In net/core/sock.c (ffff800010ba9fa4)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (ffff800010bbc580)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffff800010c70a90)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffff800010c9cc10)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
```
```
In net/unix/af_unix.c (ffff800010cf1c74)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/sock.c (c0cc8644)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (c0cd88ac)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (c0d7ff94)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (c0da9d30)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
```
```
In net/unix/af_unix.c (c0df7ae0)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/sock.c (c000000000c7f840)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (c000000000c94638)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (c000000000d77ae4)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (c000000000dad31c)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
```
```
In net/unix/af_unix.c (c000000000e1589c)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/sock.c (ffffffe00073d4e0)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (ffffffe00074a6f2)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffe0007d62f4)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffe0007fa152)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
```
```
In net/unix/af_unix.c (ffffffe00083da16)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/sock.c (ffffffff818b2455)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (ffffffff818c1ec5)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff8196040f)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81987d30)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
```
```
In net/unix/af_unix.c (ffffffff819d09c0)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/sock.c (ffffffff8186c3a5)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (ffffffff8187be05)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81919eff)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff819417f0)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
```
```
In net/unix/af_unix.c (ffffffff8198d780)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/sock.c (ffffffff81903455)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (ffffffff81912ec5)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff819cabdf)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff819f2500)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
```
```
In net/unix/af_unix.c (ffffffff81a3b440)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/core/sock.c (ffffffff81924435)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/datagram.c (ffffffff81934045)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff819d476f)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff819fc300)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
```
```
In net/unix/af_unix.c (ffffffff81a460c0)
Location: include/linux/skbuff.h:1507
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
</details>
</li>
</ul>

## Differences
