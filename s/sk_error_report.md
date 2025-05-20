# Function: <code>sk_error_report</code>

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
void sk_error_report(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a79c40)
Location: net/core/sock.c:337
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:msg_zerocopy_callback
  - net/core/skmsg.c:sk_psock_backlog
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_overrun
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
  - net/unix/af_unix.c:unix_dgram_disconnected
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/xdp/xsk.c:xsk_notifier
  - net/mptcp/subflow.c:__mptcp_error_report
```
**Symbols:**

```
ffffffff81a79c40-ffffffff81a79ca8: sk_error_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sk_error_report(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bedd10)
Location: net/core/sock.c:343
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__msg_zerocopy_callback
  - net/core/skmsg.c:sk_psock_backlog
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_overrun
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
  - net/unix/af_unix.c:unix_dgram_disconnected
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/xdp/xsk.c:xsk_notifier
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/subflow.c:__mptcp_error_report
```
**Symbols:**

```
ffffffff81bedd10-ffffffff81bedd9a: sk_error_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sk_error_report(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9a250)
Location: net/core/sock.c:343
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__msg_zerocopy_callback
  - net/core/skmsg.c:sk_psock_backlog
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_overrun
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
  - net/unix/af_unix.c:unix_dgram_disconnected
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/xdp/xsk.c:xsk_notifier
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/subflow.c:__mptcp_error_report
```
**Symbols:**

```
ffffffff81d9a250-ffffffff81d9a2da: sk_error_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sk_error_report(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e08af0)
Location: net/core/sock.c:347
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__msg_zerocopy_callback
  - net/core/skmsg.c:sk_psock_backlog
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_overrun
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
  - net/unix/af_unix.c:unix_dgram_disconnected
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/xdp/xsk.c:xsk_notifier
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/subflow.c:__mptcp_error_report
```
**Symbols:**

```
ffffffff81e08af0-ffffffff81e08b7a: sk_error_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sk_error_report(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec5560)
Location: net/core/sock.c:344
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__msg_zerocopy_callback
  - net/core/skmsg.c:sk_psock_backlog
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_overrun
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
  - net/unix/af_unix.c:unix_dgram_disconnected
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/xdp/xsk.c:xsk_notifier
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_error_report
```
**Symbols:**

```
ffffffff81ec5560-ffffffff81ec55ea: sk_error_report (STB_GLOBAL)
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
