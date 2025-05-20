# Function: <code>__skb_fill_page_desc</code>

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
In net/core/skbuff.c (ffffffff817052c5)
Location: include/linux/skbuff.h:1715
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_try_coalesce
```
```
In net/core/datagram.c (ffffffff8170d681)
Location: include/linux/skbuff.h:1715
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff8175d5c8)
Location: include/linux/skbuff.h:1715
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81769315)
Location: include/linux/skbuff.h:1715
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff817c5c75)
Location: include/linux/skbuff.h:1715
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818076d4)
Location: include/linux/skbuff.h:1715
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/skbuff.c (ffffffff8176e27d)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81774cd1)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff817c8a71)
Location: include/linux/skbuff.h:1816
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817d6ab6)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81832d72)
Location: include/linux/skbuff.h:1816
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81878fe0)
Location: include/linux/skbuff.h:1816
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/skbuff.c (ffffffff8179b6bd)
Location: include/linux/skbuff.h:1831
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff817a1fd1)
Location: include/linux/skbuff.h:1831
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff817f865c)
Location: include/linux/skbuff.h:1831
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81806a56)
Location: include/linux/skbuff.h:1831
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81864806)
Location: include/linux/skbuff.h:1831
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818ad6fb)
Location: include/linux/skbuff.h:1831
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/skbuff.c (ffffffff817bd216)
Location: include/linux/skbuff.h:1824
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff817c0040)
Location: include/linux/skbuff.h:1824
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81818bfa)
Location: include/linux/skbuff.h:1824
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81827045)
Location: include/linux/skbuff.h:1824
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81888022)
Location: include/linux/skbuff.h:1824
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d2c6f)
Location: include/linux/skbuff.h:1824
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff816ff335)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81833bf6)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff818393b1)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81898c69)
Location: include/linux/skbuff.h:1911
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818a5244)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff8190a467)
Location: include/linux/skbuff.h:1911
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81957ba3)
Location: include/linux/skbuff.h:1911
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff8173eaa2)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff8187e084)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81883b00)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff818eccf8)
Location: include/linux/skbuff.h:1922
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818fac63)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81961805)
Location: include/linux/skbuff.h:1922
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819af841)
Location: include/linux/skbuff.h:1922
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff81762717)
Location: include/linux/skbuff.h:2000
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff8189ec43)
Location: include/linux/skbuff.h:2000
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff818a449a)
Location: include/linux/skbuff.h:2000
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff8191a558)
Location: include/linux/skbuff.h:2000
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81928ba9)
Location: include/linux/skbuff.h:2000
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81996163)
Location: include/linux/skbuff.h:2000
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e6d96)
Location: include/linux/skbuff.h:2000
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff817a0469)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff818e947c)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff818efaeb)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff8197c771)
Location: include/linux/skbuff.h:2090
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8198bc55)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81a025dd)
Location: include/linux/skbuff.h:2090
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a562ad)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff817c5416)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff8191b5dc)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81921b0b)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff819b3111)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819c2538)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81a391b5)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a8d78d)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff8188b5f7)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff819ee44f)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff819f53ff)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81a9d10a)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aadbb0)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81b2e8ea)
Location: include/linux/skbuff.h:2127
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b87d7e)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
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
In drivers/net/tun.c (ffffffff8189979b)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff819ee0ef)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff819f4e3d)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81aa6fca)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ab4fa1)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81b3d33a)
Location: include/linux/skbuff.h:2148
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b9785e)
Location: include/linux/skbuff.h:2148
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
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
In drivers/net/tun.c (ffffffff8187bc10)
Location: include/linux/skbuff.h:2164
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff819d798f)
Location: include/linux/skbuff.h:2164
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff819dafc5)
Location: include/linux/skbuff.h:2164
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81a92149)
Location: include/linux/skbuff.h:2164
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aa014a)
Location: include/linux/skbuff.h:2164
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81b2a7bd)
Location: include/linux/skbuff.h:2164
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b8685d)
Location: include/linux/skbuff.h:2164
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81ba52fa)
Location: include/linux/skbuff.h:2164
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
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
In drivers/net/tun.c (ffffffff8190d140)
Location: include/linux/skbuff.h:2193
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff81a861ea)
Location: include/linux/skbuff.h:2193
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81a8b658)
Location: include/linux/skbuff.h:2193
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81b4d559)
Location: include/linux/skbuff.h:2193
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81b5bf18)
Location: include/linux/skbuff.h:2193
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81bf08bf)
Location: include/linux/skbuff.h:2193
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c52c1d)
Location: include/linux/skbuff.h:2193
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81c72e83)
Location: include/linux/skbuff.h:2193
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
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
In drivers/net/tun.c (ffffffff81a62ad2)
Location: include/linux/skbuff.h:2544
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff81bf8998)
Location: include/linux/skbuff.h:2544
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81c00c86)
Location: include/linux/skbuff.h:2544
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81cdad33)
Location: include/linux/skbuff.h:2544
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ceb115)
Location: include/linux/skbuff.h:2544
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81d88f8e)
Location: include/linux/skbuff.h:2544
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df685a)
Location: include/linux/skbuff.h:2544
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81e17cc9)
Location: include/linux/skbuff.h:2544
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81e1f38a)
Location: include/linux/skbuff.h:2544
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In drivers/net/tun.c (ffffffff81beef9b)
Location: include/linux/skbuff.h:2430
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff81da7828)
Location: include/linux/skbuff.h:2430
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/ipv4/ip_output.c (ffffffff81e9b554)
Location: include/linux/skbuff.h:2430
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81eaee9e)
Location: include/linux/skbuff.h:2430
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81f56db5)
Location: include/linux/skbuff.h:2430
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fcae19)
Location: include/linux/skbuff.h:2430
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81feee69)
Location: include/linux/skbuff.h:2430
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81ff5ee5)
Location: include/linux/skbuff.h:2430
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In drivers/net/tun.c (ffffffff81c4704a)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff81e198ee)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/ipv4/ip_output.c (ffffffff81efa110)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81f0cfda)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81f25458)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81fb6809)
Location: include/linux/skbuff.h:2468
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202c09b)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8206ae07)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff8207200b)
Location: include/linux/skbuff.h:2468
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In drivers/net/tun.c (ffffffff81cfca29)
Location: include/linux/skbuff.h:2475
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff81ed6d59)
Location: include/linux/skbuff.h:2475
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/ipv4/ip_output.c (ffffffff81fbe03e)
Location: include/linux/skbuff.h:2475
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81fd10da)
Location: include/linux/skbuff.h:2475
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9d19)
Location: include/linux/skbuff.h:2475
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff820840f4)
Location: include/linux/skbuff.h:2475
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fbb4b)
Location: include/linux/skbuff.h:2475
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8213e789)
Location: include/linux/skbuff.h:2475
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff82146379)
Location: include/linux/skbuff.h:2475
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In drivers/net/tun.c (ffff8000109e0618)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffff800010bb5ab4)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffff800010bbc16c)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffff800010c62af0)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/ipv4/tcp.c (ffff800010c7514c)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffff800010cf9150)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d59288)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (c0ac47d0)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (c0cd2afc)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (c0cd8600)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (c0d734a8)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (c0d8380c)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (c0e0092c)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
```
```
In net/packet/af_packet.c (c0e5acb8)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (c000000000aa1a10)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (c000000000c8ce74)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (c000000000c95360)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (c000000000d6770c)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/ipv4/tcp.c (c000000000d7c84c)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (c000000000e20d2c)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/packet/af_packet.c (c000000000e94e64)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffe00062a4e8)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffe000745a00)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffe00074aee8)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffe0007cb508)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/ipv4/tcp.c (ffffffe0007d845a)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffe000844f8c)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/packet/af_packet.c (ffffffe00089157e)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff81789ef6)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff818bb5dc)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff818c1b0b)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81952f81)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819623a8)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff819d8845)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2ce1d)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff81769846)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff8187551c)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff8187ba4b)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff8190ca71)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8191be98)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81995605)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819ea00d)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff817ba296)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff8190c5dc)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81912b0b)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff819bd751)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819ccb78)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81a432c5)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a989cd)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In drivers/net/tun.c (ffffffff817d2796)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff8192d70c)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81933c8b)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff819c7061)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819d6708)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81a4ef65)
Location: include/linux/skbuff.h:2104
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa5067)
Location: include/linux/skbuff.h:2104
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
</ul>

## Differences
