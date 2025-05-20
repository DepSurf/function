# Function: <code>skb_copy_datagram_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8170d0d0)
Location: net/core/datagram.c:355
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff8170d0d0-ffffffff8170d347: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81774730)
Location: net/core/datagram.c:377
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff81774730-ffffffff81774996: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817a1a30)
Location: net/core/datagram.c:397
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff817a1a30-ffffffff817a1c96: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817bf670)
Location: net/core/datagram.c:419
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff817bf670-ffffffff817bf8fa: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81839000)
Location: net/core/datagram.c:420
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff81839000-ffffffff8183928d: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81883740)
Location: net/core/datagram.c:418
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff81883740-ffffffff818839b4: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818a5000)
Location: net/core/datagram.c:526
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff818a5000-ffffffff818a508e: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818ef740)
Location: net/core/datagram.c:525
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff818ef740-ffffffff818ef7ce: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819216f0)
Location: net/core/datagram.c:525
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff819216f0-ffffffff8192177e: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f58c0)
Location: net/core/datagram.c:529
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/xfrm/espintcp.c:espintcp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
  - net/mptcp/protocol.c:__mptcp_recvmsg_mskq
```
**Symbols:**

```
ffffffff819f58c0-ffffffff819f594e: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f5380)
Location: net/core/datagram.c:529
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/xfrm/espintcp.c:espintcp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
  - net/mptcp/protocol.c:__mptcp_recvmsg_mskq
```
**Symbols:**

```
ffffffff819f5380-ffffffff819f53fc: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819db520)
Location: net/core/datagram.c:529
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/xfrm/espintcp.c:espintcp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff819db520-ffffffff819db59c: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81a8aba0)
Location: net/core/datagram.c:529
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/xfrm/espintcp.c:espintcp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81a8aba0-ffffffff81a8ac19: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81c001c0)
Location: net/core/datagram.c:526
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/xfrm/espintcp.c:espintcp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mctp/af_mctp.c:mctp_recvmsg
```
**Symbols:**

```
ffffffff81c001c0-ffffffff81c00261: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81daf5d0)
Location: net/core/datagram.c:523
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/xfrm/espintcp.c:espintcp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mctp/af_mctp.c:mctp_recvmsg
```
**Symbols:**

```
ffffffff81daf5d0-ffffffff81daf671: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81e1f810)
Location: net/core/datagram.c:523
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/xfrm/espintcp.c:espintcp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mctp/af_mctp.c:mctp_recvmsg
```
**Symbols:**

```
ffffffff81e1f810-ffffffff81e1f8b1: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81edcec0)
Location: net/core/datagram.c:542
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/xfrm/espintcp.c:espintcp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mctp/af_mctp.c:mctp_recvmsg
```
**Symbols:**

```
ffffffff81edcec0-ffffffff81edcf61: skb_copy_datagram_iter (STB_GLOBAL)
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
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffff800010bbbd80)
Location: net/core/datagram.c:525
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffff800010bbbd80-ffff800010bbbe54: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c0cd8138)
Location: net/core/datagram.c:525
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
c0cd8138-c0cd8210: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c000000000c94d70)
Location: net/core/datagram.c:525
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
c000000000c94d70-c000000000c94e9c: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffe00074abb2)
Location: net/core/datagram.c:525
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffe00074abb2-ffffffe00074ac5c: skb_copy_datagram_iter (STB_GLOBAL)
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
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818c16f0)
Location: net/core/datagram.c:525
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff818c16f0-ffffffff818c177e: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8187b630)
Location: net/core/datagram.c:525
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff8187b630-ffffffff8187b6be: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819126f0)
Location: net/core/datagram.c:525
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff819126f0-ffffffff8191277e: skb_copy_datagram_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff *skb, int offset, struct iov_iter *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81933850)
Location: net/core/datagram.c:525
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/sock.c:sock_recv_errqueue
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff81933850-ffffffff819338f3: skb_copy_datagram_iter (STB_GLOBAL)
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
