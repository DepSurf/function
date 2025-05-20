# Function: <code>__skb_fill_page_desc_noacc</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
Location: include/linux/skbuff.h:2389
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In drivers/net/tun.c (ffffffff81beef9b)
Location: include/linux/skbuff.h:2389
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff81da7828)
Location: include/linux/skbuff.h:2389
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
In net/core/datagram.c (ffffffff81db00ee)
Location: include/linux/skbuff.h:2389
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81e9b554)
Location: include/linux/skbuff.h:2389
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81eaee9e)
Location: include/linux/skbuff.h:2389
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81f56db5)
Location: include/linux/skbuff.h:2389
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fcae19)
Location: include/linux/skbuff.h:2389
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81feee69)
Location: include/linux/skbuff.h:2389
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81ff5ee5)
Location: include/linux/skbuff.h:2389
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
In io_uring/net.c (ffffffff817d68f2)
Location: include/linux/skbuff.h:2434
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In drivers/net/tun.c (ffffffff81c4704a)
Location: include/linux/skbuff.h:2434
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff81e19900)
Location: include/linux/skbuff.h:2434
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
In net/core/datagram.c (ffffffff81e203c8)
Location: include/linux/skbuff.h:2434
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81efa110)
Location: include/linux/skbuff.h:2434
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81f0cfda)
Location: include/linux/skbuff.h:2434
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81f25468)
Location: include/linux/skbuff.h:2434
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81fb6809)
Location: include/linux/skbuff.h:2434
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202c0a9)
Location: include/linux/skbuff.h:2434
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8206ae07)
Location: include/linux/skbuff.h:2434
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff8207200b)
Location: include/linux/skbuff.h:2434
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
In io_uring/net.c (ffffffff8181aac2)
Location: include/linux/skbuff.h:2441
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In drivers/net/tun.c (ffffffff81cfca29)
Location: include/linux/skbuff.h:2441
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff81ed6d59)
Location: include/linux/skbuff.h:2441
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
In net/core/datagram.c (ffffffff81ede2a5)
Location: include/linux/skbuff.h:2441
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81fbe03e)
Location: include/linux/skbuff.h:2441
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81fd10da)
Location: include/linux/skbuff.h:2441
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9d29)
Location: include/linux/skbuff.h:2441
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff820840f4)
Location: include/linux/skbuff.h:2441
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fbb59)
Location: include/linux/skbuff.h:2441
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8213e789)
Location: include/linux/skbuff.h:2441
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff82146379)
Location: include/linux/skbuff.h:2441
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
