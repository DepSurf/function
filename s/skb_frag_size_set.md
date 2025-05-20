# Function: <code>skb_frag_size_set</code>

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
In drivers/net/xen-netfront.c (ffffffff815fb70e)
Location: include/linux/skbuff.h:244
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff817052f4)
Location: include/linux/skbuff.h:244
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/datagram.c (ffffffff8170d6ba)
Location: include/linux/skbuff.h:244
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff8175d5db)
Location: include/linux/skbuff.h:244
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81769347)
Location: include/linux/skbuff.h:244
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff817c5c88)
Location: include/linux/skbuff.h:244
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81807700)
Location: include/linux/skbuff.h:244
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
In drivers/net/xen-netfront.c (ffffffff8165b63b)
Location: include/linux/skbuff.h:330
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8176e29d)
Location: include/linux/skbuff.h:330
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81774cfb)
Location: include/linux/skbuff.h:330
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff817c8a79)
Location: include/linux/skbuff.h:330
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817d6ad6)
Location: include/linux/skbuff.h:330
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81832d7a)
Location: include/linux/skbuff.h:330
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81878ffe)
Location: include/linux/skbuff.h:330
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
In drivers/net/xen-netfront.c (ffffffff8168945b)
Location: include/linux/skbuff.h:330
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8179b6dd)
Location: include/linux/skbuff.h:330
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff817a1ffb)
Location: include/linux/skbuff.h:330
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff817f8664)
Location: include/linux/skbuff.h:330
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81806a76)
Location: include/linux/skbuff.h:330
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff8186480e)
Location: include/linux/skbuff.h:330
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818ad719)
Location: include/linux/skbuff.h:330
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
In drivers/net/xen-netfront.c (ffffffff8169eb83)
Location: include/linux/skbuff.h:333
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff817bd238)
Location: include/linux/skbuff.h:333
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff817c006a)
Location: include/linux/skbuff.h:333
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81818c02)
Location: include/linux/skbuff.h:333
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8182704d)
Location: include/linux/skbuff.h:333
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff8188802a)
Location: include/linux/skbuff.h:333
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d2c8a)
Location: include/linux/skbuff.h:333
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
In drivers/net/tun.c (ffffffff816ff361)
Location: include/linux/skbuff.h:333
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81709d23)
Location: include/linux/skbuff.h:333
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81833c18)
Location: include/linux/skbuff.h:333
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff818393d9)
Location: include/linux/skbuff.h:333
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81898c71)
Location: include/linux/skbuff.h:333
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818a524c)
Location: include/linux/skbuff.h:333
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff8190a46f)
Location: include/linux/skbuff.h:333
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81957bbe)
Location: include/linux/skbuff.h:333
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
In drivers/net/tun.c (ffffffff8173ead5)
Location: include/linux/skbuff.h:333
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817487d6)
Location: include/linux/skbuff.h:333
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8187e0a7)
Location: include/linux/skbuff.h:333
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81883b16)
Location: include/linux/skbuff.h:333
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff818ecd16)
Location: include/linux/skbuff.h:333
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818fac80)
Location: include/linux/skbuff.h:333
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81961823)
Location: include/linux/skbuff.h:333
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819af86b)
Location: include/linux/skbuff.h:333
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
In drivers/net/tun.c (ffffffff81762758)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8176c886)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8189ec66)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff818a44b0)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff8191a575)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81928bc6)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81996180)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e6dc0)
Location: include/linux/skbuff.h:335
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
In drivers/net/tun.c (ffffffff817a04a9)
Location: include/linux/skbuff.h:340
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817aa67f)
Location: include/linux/skbuff.h:340
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff818e94a4)
Location: include/linux/skbuff.h:340
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff818efb02)
Location: include/linux/skbuff.h:340
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff8197c78a)
Location: include/linux/skbuff.h:340
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8198bc6e)
Location: include/linux/skbuff.h:340
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81a025f6)
Location: include/linux/skbuff.h:340
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a562d7)
Location: include/linux/skbuff.h:340
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
In drivers/net/tun.c (ffffffff817c5456)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817ce0df)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8191b604)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81921b22)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff819b312a)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819c2551)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81a391ce)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a8d7b7)
Location: include/linux/skbuff.h:335
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
In drivers/net/tun.c (ffffffff8188b636)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff8189a05c)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff819ee469)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff819f5412)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81a9d11b)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aadbc1)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81b2e8fb)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b87da3)
Location: include/linux/skbuff.h:335
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
In drivers/net/tun.c (ffffffff818997da)
Location: include/linux/skbuff.h:337
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff818a91b5)
Location: include/linux/skbuff.h:337
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff819ee109)
Location: include/linux/skbuff.h:337
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff819f4e53)
Location: include/linux/skbuff.h:337
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81aa6fdb)
Location: include/linux/skbuff.h:337
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ab4faf)
Location: include/linux/skbuff.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81b3d34b)
Location: include/linux/skbuff.h:337
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b97883)
Location: include/linux/skbuff.h:337
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
In drivers/net/tun.c (ffffffff8187bc4f)
Location: include/linux/skbuff.h:338
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff8188c3d2)
Location: include/linux/skbuff.h:338
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff819d79a9)
Location: include/linux/skbuff.h:338
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff819dafdb)
Location: include/linux/skbuff.h:338
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81a9215a)
Location: include/linux/skbuff.h:338
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aa0158)
Location: include/linux/skbuff.h:338
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81b2a7ce)
Location: include/linux/skbuff.h:338
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b86882)
Location: include/linux/skbuff.h:338
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81ba5319)
Location: include/linux/skbuff.h:338
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
In drivers/net/tun.c (ffffffff8190d17f)
Location: include/linux/skbuff.h:342
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff8191f7bb)
Location: include/linux/skbuff.h:342
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81a8620a)
Location: include/linux/skbuff.h:342
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81a8b66d)
Location: include/linux/skbuff.h:342
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81b4d56a)
Location: include/linux/skbuff.h:342
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81b5bf26)
Location: include/linux/skbuff.h:342
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81bf08d0)
Location: include/linux/skbuff.h:342
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c52c42)
Location: include/linux/skbuff.h:342
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81c72ea2)
Location: include/linux/skbuff.h:342
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
In drivers/net/tun.c (ffffffff81a62b0d)
Location: include/linux/skbuff.h:553
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff81a74890)
Location: include/linux/skbuff.h:553
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81bf89b7)
Location: include/linux/skbuff.h:553
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81c00c9b)
Location: include/linux/skbuff.h:553
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/gro.c (ffffffff81c54cfb)
Location: include/linux/skbuff.h:553
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/bpf/test_run.c (ffffffff81cb5ab7)
Location: include/linux/skbuff.h:553
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
```
In net/ipv4/ip_output.c (ffffffff81cdad44)
Location: include/linux/skbuff.h:553
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ceb125)
Location: include/linux/skbuff.h:553
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81d88f9f)
Location: include/linux/skbuff.h:553
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df687c)
Location: include/linux/skbuff.h:553
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81e17ce5)
Location: include/linux/skbuff.h:553
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81e1f3a4)
Location: include/linux/skbuff.h:553
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
In io_uring/net.c (ffffffff81795c7e)
Location: include/linux/skbuff.h:376
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In drivers/net/tun.c (ffffffff81beefd6)
Location: include/linux/skbuff.h:376
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff81c08af0)
Location: include/linux/skbuff.h:376
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81da7847)
Location: include/linux/skbuff.h:376
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81db0105)
Location: include/linux/skbuff.h:376
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/gro.c (ffffffff81e0a48b)
Location: include/linux/skbuff.h:376
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/bpf/test_run.c (ffffffff81e73f87)
Location: include/linux/skbuff.h:376
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
```
In net/ipv4/ip_output.c (ffffffff81e9b566)
Location: include/linux/skbuff.h:376
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81eaeeae)
Location: include/linux/skbuff.h:376
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81f56dc7)
Location: include/linux/skbuff.h:376
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fcae3b)
Location: include/linux/skbuff.h:376
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81feee85)
Location: include/linux/skbuff.h:376
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81ff5efc)
Location: include/linux/skbuff.h:376
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
In io_uring/net.c (ffffffff817d690c)
Location: include/linux/skbuff.h:379
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In drivers/net/tun.c (ffffffff81c47068)
Location: include/linux/skbuff.h:379
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81c53b71)
Location: include/linux/skbuff.h:379
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81c6e257)
Location: include/linux/skbuff.h:379
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81e1991f)
Location: include/linux/skbuff.h:379
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81e203e7)
Location: include/linux/skbuff.h:379
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/gro.c (ffffffff81e7cc78)
Location: include/linux/skbuff.h:379
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/bpf/test_run.c (ffffffff81ecfd1e)
Location: include/linux/skbuff.h:379
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
```
In net/ipv4/ip_output.c (ffffffff81efa12f)
Location: include/linux/skbuff.h:379
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81f0cff2)
Location: include/linux/skbuff.h:379
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81f25470)
Location: include/linux/skbuff.h:379
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_clone_payload
```
```
In net/ipv6/ip6_output.c (ffffffff81fb6828)
Location: include/linux/skbuff.h:379
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202c0cd)
Location: include/linux/skbuff.h:379
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8206ae26)
Location: include/linux/skbuff.h:379
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff82072029)
Location: include/linux/skbuff.h:379
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
In io_uring/net.c (ffffffff8181aadc)
Location: include/linux/skbuff.h:378
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In drivers/net/tun.c (ffffffff81cfca47)
Location: include/linux/skbuff.h:378
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81d0a31d)
Location: include/linux/skbuff.h:378
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81d22b3f)
Location: include/linux/skbuff.h:378
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81ed6d78)
Location: include/linux/skbuff.h:378
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81ede2c4)
Location: include/linux/skbuff.h:378
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/gro.c (ffffffff81f3cfc8)
Location: include/linux/skbuff.h:378
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/bpf/test_run.c (ffffffff81f93671)
Location: include/linux/skbuff.h:378
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
```
In net/ipv4/ip_output.c (ffffffff81fbe05d)
Location: include/linux/skbuff.h:378
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81fd10f2)
Location: include/linux/skbuff.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9d31)
Location: include/linux/skbuff.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_clone_payload
```
```
In net/ipv6/ip6_output.c (ffffffff82084113)
Location: include/linux/skbuff.h:378
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fbb7d)
Location: include/linux/skbuff.h:378
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8213e7a8)
Location: include/linux/skbuff.h:378
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff82146397)
Location: include/linux/skbuff.h:378
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
In drivers/net/tun.c (ffff8000109e0640)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffff800010a088bc)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffff800010bb5ac8)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffff800010bbc17c)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffff800010c62b04)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/ipv4/tcp.c (ffff800010c75160)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffff800010cf9164)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d592a8)
Location: include/linux/skbuff.h:335
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
In drivers/net/tun.c (c0ac47e0)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (c0cd2b0c)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (c0cd860c)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (c0d734c0)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (c0d83814)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (c0e00944)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
```
```
In net/packet/af_packet.c (c0e5acd8)
Location: include/linux/skbuff.h:335
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
In drivers/net/tun.c (c000000000aa1a54)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (c000000000c8ce9c)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (c000000000c9537c)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (c000000000d6772c)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/ipv4/tcp.c (c000000000d7c864)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (c000000000e20d4c)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/packet/af_packet.c (c000000000e94e8c)
Location: include/linux/skbuff.h:335
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
In drivers/net/tun.c (ffffffe00062a50c)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffe000745a16)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffe00074aeee)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffe0007cb512)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/ipv4/tcp.c (ffffffe0007d8464)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffe000844f96)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/packet/af_packet.c (ffffffe000891594)
Location: include/linux/skbuff.h:335
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
In drivers/net/tun.c (ffffffff81789f36)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81792cff)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff818bb604)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff818c1b22)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81952f9a)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819623c1)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff819d885e)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2ce47)
Location: include/linux/skbuff.h:335
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
In drivers/net/tun.c (ffffffff81769886)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff81875544)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff8187ba62)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff8190ca8a)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8191beb1)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff8199561e)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819ea037)
Location: include/linux/skbuff.h:335
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
In drivers/net/tun.c (ffffffff817ba2d6)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817c2f5f)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8190c604)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81912b22)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff819bd76a)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819ccb91)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81a432de)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a989f7)
Location: include/linux/skbuff.h:335
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
In drivers/net/tun.c (ffffffff817d27d6)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817dd21f)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8192d734)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81933ca2)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff819c707a)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819d6721)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81a4ef7e)
Location: include/linux/skbuff.h:335
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa5091)
Location: include/linux/skbuff.h:335
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
</ul>

## Differences
