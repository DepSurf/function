# Function: <code>sk_wmem_alloc_get</code>

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
In net/core/sock.c (ffffffff81702667)
Location: include/net/sock.h:1858
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/sock_diag.c (ffffffff81732ffc)
Location: include/net/sock.h:1858
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff8174abad)
Location: include/net/sock.h:1858
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff81775e78)
Location: include/net/sock.h:1858
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff817849db)
Location: include/net/sock.h:1858
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81787371)
Location: include/net/sock.h:1858
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff817a2271)
Location: include/net/sock.h:1858
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff817bd745)
Location: include/net/sock.h:1858
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff817e5b21)
Location: include/net/sock.h:1858
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff817f5b3b)
Location: include/net/sock.h:1858
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff8180317e)
Location: include/net/sock.h:1858
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
In net/core/sock.c (ffffffff81769897)
Location: include/net/sock.h:1828
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/sock_diag.c (ffffffff8179ea1c)
Location: include/net/sock.h:1828
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff817b77dd)
Location: include/net/sock.h:1828
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff817e2dfa)
Location: include/net/sock.h:1828
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff817f1fb9)
Location: include/net/sock.h:1828
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff817f450f)
Location: include/net/sock.h:1828
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff8180ff7f)
Location: include/net/sock.h:1828
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff8182aa14)
Location: include/net/sock.h:1828
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff81853d13)
Location: include/net/sock.h:1828
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81864c19)
Location: include/net/sock.h:1828
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff8187450e)
Location: include/net/sock.h:1828
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
In net/core/sock.c (ffffffff817967b7)
Location: include/net/sock.h:1890
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/sock_diag.c (ffffffff817cd3ec)
Location: include/net/sock.h:1890
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff817e727d)
Location: include/net/sock.h:1890
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff818134aa)
Location: include/net/sock.h:1890
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff8182116d)
Location: include/net/sock.h:1890
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_check_app_limited
```
```
In net/ipv4/raw.c (ffffffff81822da6)
Location: include/net/sock.h:1890
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff818255dc)
Location: include/net/sock.h:1890
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff818414cc)
Location: include/net/sock.h:1890
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff8185c494)
Location: include/net/sock.h:1890
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff81885a23)
Location: include/net/sock.h:1890
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff818972f9)
Location: include/net/sock.h:1890
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff818a8afe)
Location: include/net/sock.h:1890
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
In net/core/sock.c (ffffffff817b6451)
Location: include/net/sock.h:1915
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81806f88)
Location: include/net/sock.h:1915
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff81833695)
Location: include/net/sock.h:1915
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff818417bd)
Location: include/net/sock.h:1915
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81843986)
Location: include/net/sock.h:1915
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81846510)
Location: include/net/sock.h:1915
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81862d40)
Location: include/net/sock.h:1915
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff81880d86)
Location: include/net/sock.h:1915
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff818abf66)
Location: include/net/sock.h:1915
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff818bd746)
Location: include/net/sock.h:1915
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff818cf33e)
Location: include/net/sock.h:1915
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
In net/core/sock.c (ffffffff8182ea11)
Location: include/net/sock.h:1929
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81885d38)
Location: include/net/sock.h:1929
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff818b2a0a)
Location: include/net/sock.h:1929
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff818c0fdd)
Location: include/net/sock.h:1929
Inline: True
```
```
In net/ipv4/raw.c (ffffffff818c33c6)
Location: include/net/sock.h:1929
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff818c5f40)
Location: include/net/sock.h:1929
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff818e2e70)
Location: include/net/sock.h:1929
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff81901f16)
Location: include/net/sock.h:1929
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff8192ea16)
Location: include/net/sock.h:1929
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81940866)
Location: include/net/sock.h:1929
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff819542ae)
Location: include/net/sock.h:1929
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
In net/core/sock.c (ffffffff81878e8d)
Location: include/net/sock.h:1931
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff818d96f5)
Location: include/net/sock.h:1931
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff81907efe)
Location: include/net/sock.h:1931
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81916b2d)
Location: include/net/sock.h:1931
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81919036)
Location: include/net/sock.h:1931
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff8191b251)
Location: include/net/sock.h:1931
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff819397dc)
Location: include/net/sock.h:1931
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff8195c581)
Location: include/net/sock.h:1931
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff81987328)
Location: include/net/sock.h:1931
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81999734)
Location: include/net/sock.h:1931
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff819ad885)
Location: include/net/sock.h:1931
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
In net/core/sock.c (ffffffff8189983d)
Location: include/net/sock.h:2016
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81905ee5)
Location: include/net/sock.h:2016
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff819361fa)
Location: include/net/sock.h:2016
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff819452dd)
Location: include/net/sock.h:2016
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81947806)
Location: include/net/sock.h:2016
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff819497d1)
Location: include/net/sock.h:2016
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff8196946c)
Location: include/net/sock.h:2016
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff8198e161)
Location: include/net/sock.h:2016
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff819bdf68)
Location: include/net/sock.h:2016
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff819d0084)
Location: include/net/sock.h:2016
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff819e41f5)
Location: include/net/sock.h:2016
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
In net/core/sock.c (ffffffff818e3e3d)
Location: include/net/sock.h:2028
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81967171)
Location: include/net/sock.h:2028
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff8199a5b2)
Location: include/net/sock.h:2028
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff819a98dd)
Location: include/net/sock.h:2028
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819abea5)
Location: include/net/sock.h:2028
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff819ade43)
Location: include/net/sock.h:2028
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff819d00bc)
Location: include/net/sock.h:2028
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff819f96f7)
Location: include/net/sock.h:2028
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff81a2ca6c)
Location: include/net/sock.h:2028
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a3ed97)
Location: include/net/sock.h:2028
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff81a535c9)
Location: include/net/sock.h:2028
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
In net/core/sock.c (ffffffff8191601d)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff8199dc01)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff819d0fff)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff819e059d)
Location: include/net/sock.h:2038
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819e2b55)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff819e4b53)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81a06c0c)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff81a30357)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff81a6373c)
Location: include/net/sock.h:2038
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a75a07)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff81a8a1b9)
Location: include/net/sock.h:2038
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
In net/core/sock.c (ffffffff819e608c)
Location: include/net/sock.h:2087
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81a76afd)
Location: include/net/sock.h:2087
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff81abe083)
Location: include/net/sock.h:2087
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81acdb6d)
Location: include/net/sock.h:2087
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81ad0116)
Location: include/net/sock.h:2087
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sock_seq_show
```
```
In net/ipv4/udp.c (ffffffff81ad27a4)
Location: include/net/sock.h:2087
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_format_sock
```
```
In net/ipv4/ping.c (ffffffff81af664d)
Location: include/net/sock.h:2087
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_format_sock
```
```
In net/unix/af_unix.c (ffffffff81b240fc)
Location: include/net/sock.h:2087
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
```
In net/ipv6/raw.c (ffffffff81b5bb9c)
Location: include/net/sock.h:2087
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81b6fc47)
Location: include/net/sock.h:2087
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff81b84ea9)
Location: include/net/sock.h:2087
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In net/core/sock.c (ffffffff819e545d)
Location: include/net/sock.h:2106
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81a7f87d)
Location: include/net/sock.h:2106
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff81ac995f)
Location: include/net/sock.h:2106
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81ad9bcd)
Location: include/net/sock.h:2106
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81adc096)
Location: include/net/sock.h:2106
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sock_seq_show
```
```
In net/ipv4/udp.c (ffffffff81ade6e4)
Location: include/net/sock.h:2106
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_format_sock
```
```
In net/ipv4/ping.c (ffffffff81b034cd)
Location: include/net/sock.h:2106
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_format_sock
```
```
In net/unix/af_unix.c (ffffffff81b32b6e)
Location: include/net/sock.h:2106
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
```
In net/ipv6/raw.c (ffffffff81b6a3d4)
Location: include/net/sock.h:2106
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81b7e777)
Location: include/net/sock.h:2106
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff81b947ef)
Location: include/net/sock.h:2106
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In net/core/sock.c (ffffffff819cb4af)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81a68846)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff81ab480e)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81ac4c1d)
Location: include/net/sock.h:2123
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81ac6f55)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81ac9623)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81aeed4c)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff81b2082a)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff81b58704)
Location: include/net/sock.h:2123
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81b6d387)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff81b838cf)
Location: include/net/sock.h:2123
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In net/core/sock.c (ffffffff81a7ab3f)
Location: include/net/sock.h:2163
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81b21ea0)
Location: include/net/sock.h:2163
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff81b717ce)
Location: include/net/sock.h:2163
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81b833cd)
Location: include/net/sock.h:2163
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81b85775)
Location: include/net/sock.h:2163
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81b87e93)
Location: include/net/sock.h:2163
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81baf11c)
Location: include/net/sock.h:2163
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff81be5772)
Location: include/net/sock.h:2163
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff81c1fa94)
Location: include/net/sock.h:2163
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81c352a7)
Location: include/net/sock.h:2163
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff81c4f9df)
Location: include/net/sock.h:2163
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In net/core/sock.c (ffffffff81bf260d)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81caa859)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff81d00f31)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81d139dd)
Location: include/net/sock.h:2281
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81d16336)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81d19057)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81d4244e)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff81d7c721)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff81dbc74c)
Location: include/net/sock.h:2281
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81dd2c54)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff81df0485)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In net/core/sock.c (ffffffff81d9fe3d)
Location: include/net/sock.h:2316
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81e67929)
Location: include/net/sock.h:2316
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff81ec6091)
Location: include/net/sock.h:2316
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81ed99bd)
Location: include/net/sock.h:2316
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81edc506)
Location: include/net/sock.h:2316
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81edf7a7)
Location: include/net/sock.h:2316
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81f0b2be)
Location: include/net/sock.h:2316
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff81f49791)
Location: include/net/sock.h:2316
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff81f8c81c)
Location: include/net/sock.h:2316
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81fa4114)
Location: include/net/sock.h:2316
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff81fc45e5)
Location: include/net/sock.h:2316
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In net/core/sock.c (ffffffff81e0e5fd)
Location: include/net/sock.h:2304
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81ec3709)
Location: include/net/sock.h:2304
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff81f247d6)
Location: include/net/sock.h:2304
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81f38a9d)
Location: include/net/sock.h:2304
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81f3b653)
Location: include/net/sock.h:2304
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (ffffffff81f3ed94)
Location: include/net/sock.h:2304
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_ioctl
```
```
In net/ipv4/ping.c (ffffffff81f6ae9b)
Location: include/net/sock.h:2304
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff81fa942e)
Location: include/net/sock.h:2304
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff81fecda3)
Location: include/net/sock.h:2304
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/datagram.c (ffffffff820049d1)
Location: include/net/sock.h:2304
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff82025602)
Location: include/net/sock.h:2304
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In net/core/sock.c (ffffffff81ecb08d)
Location: include/net/sock.h:2294
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81f86b29)
Location: include/net/sock.h:2294
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff81fe8fae)
Location: include/net/sock.h:2294
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81ffeb7d)
Location: include/net/sock.h:2294
Inline: True
```
```
In net/ipv4/raw.c (ffffffff82001773)
Location: include/net/sock.h:2294
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (ffffffff820050f4)
Location: include/net/sock.h:2294
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_ioctl
```
```
In net/ipv4/ping.c (ffffffff8203154b)
Location: include/net/sock.h:2294
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff820768be)
Location: include/net/sock.h:2294
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff820ba9a3)
Location: include/net/sock.h:2294
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/datagram.c (ffffffff820d37a1)
Location: include/net/sock.h:2294
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff820f4f72)
Location: include/net/sock.h:2294
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
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
In net/core/sock.c (ffff800010baefc0)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffff800010c4b0dc)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffff800010c83c8c)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffff800010c942c0)
Location: include/net/sock.h:2038
Inline: True
```
```
In net/ipv4/raw.c (ffff800010c96a2c)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (ffff800010c991dc)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_ioctl
```
```
In net/ipv4/ping.c (ffff800010cbfb8c)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffff800010cf0080)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffff800010d29238)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/datagram.c (ffff800010d3e344)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffff800010d5b034)
Location: include/net/sock.h:2038
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
In net/core/sock.c (c0cccaec)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (c0d5bc2c)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (c0d92efc)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (c0da2a4c)
Location: include/net/sock.h:2038
Inline: True
```
```
In net/ipv4/raw.c (c0da50fc)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (c0da80d8)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_ioctl
```
```
In net/ipv4/ping.c (c0dcb658)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (c0df752c)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (c0e2cc80)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/datagram.c (c0e41624)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (c0e56d88)
Location: include/net/sock.h:2038
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
In net/core/sock.c (c000000000c84d00)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (c000000000d49348)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (c000000000d8f62c)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (c000000000da4990)
Location: include/net/sock.h:2038
Inline: True
```
```
In net/ipv4/raw.c (c000000000da866c)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (c000000000dabdb4)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_ioctl
```
```
In net/ipv4/ping.c (c000000000ddac34)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (c000000000e15dd0)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (c000000000e5a420)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/datagram.c (c000000000e72a9c)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (c000000000e91094)
Location: include/net/sock.h:2038
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
In net/core/sock.c (ffffffe000740aea)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffe0007b83a4)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffe0007e5772)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffe0007f37b4)
Location: include/net/sock.h:2038
Inline: True
```
```
In net/ipv4/raw.c (ffffffe0007f5c86)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (ffffffe0007f7724)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffe0008158f2)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffe00083c9fe)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffe000869aa4)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/datagram.c (ffffffe00087a93e)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffe00088e058)
Location: include/net/sock.h:2038
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
In net/core/sock.c (ffffffff818b601d)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff8193da71)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff81970e6f)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff8198040d)
Location: include/net/sock.h:2038
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819829c5)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff819849c3)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff819a69ac)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff819cf9e7)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff81a02dcc)
Location: include/net/sock.h:2038
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a15097)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff81a29849)
Location: include/net/sock.h:2038
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
In net/core/sock.c (ffffffff8186ff6d)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff818f7571)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff8192a93f)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81939ecd)
Location: include/net/sock.h:2038
Inline: True
```
```
In net/ipv4/raw.c (ffffffff8193c485)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff8193e483)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff8196046c)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff8198c7a7)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff819bfb8c)
Location: include/net/sock.h:2038
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff819d1e57)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff819e6a39)
Location: include/net/sock.h:2038
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
In net/core/sock.c (ffffffff8190701d)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff8198ec01)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff819db63f)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff819eabdd)
Location: include/net/sock.h:2038
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819ed195)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff819ef193)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81a1124c)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff81a3a467)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff81a6d84c)
Location: include/net/sock.h:2038
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a7fb17)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff81a953f9)
Location: include/net/sock.h:2038
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
In net/core/sock.c (ffffffff8192804d)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff819b14c1)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/tcp_output.c (ffffffff819e52bf)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff819f4a5d)
Location: include/net/sock.h:2038
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819f7075)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff819f9983)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81a1bbbc)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff81a45b47)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/raw.c (ffffffff81a79e6c)
Location: include/net/sock.h:2038
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a8c3d7)
Location: include/net/sock.h:2038
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/packet/af_packet.c (ffffffff81aa1819)
Location: include/net/sock.h:2038
Inline: True
```
</details>
</li>
</ul>

## Differences
