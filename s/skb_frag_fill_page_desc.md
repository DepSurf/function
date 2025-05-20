# Function: <code>skb_frag_fill_page_desc</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/net.c (ffffffff817d68fc)
Location: include/linux/skbuff.h:2425
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In drivers/net/tun.c (ffffffff81c47056)
Location: include/linux/skbuff.h:2425
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81c53b5d)
Location: include/linux/skbuff.h:2425
Inline: True
```
```
In net/core/skbuff.c (ffffffff81e1990a)
Location: include/linux/skbuff.h:2425
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81e203d2)
Location: include/linux/skbuff.h:2425
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/gro.c (ffffffff81e7cc58)
Location: include/linux/skbuff.h:2425
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/bpf/test_run.c (ffffffff81ecfcfb)
Location: include/linux/skbuff.h:2425
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
```
In net/ipv4/ip_output.c (ffffffff81efa11d)
Location: include/linux/skbuff.h:2425
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81f0cfe6)
Location: include/linux/skbuff.h:2425
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81f25468)
Location: include/linux/skbuff.h:2425
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81fb6816)
Location: include/linux/skbuff.h:2425
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202c0b6)
Location: include/linux/skbuff.h:2425
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8206ae14)
Location: include/linux/skbuff.h:2425
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff82072014)
Location: include/linux/skbuff.h:2425
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
In io_uring/net.c (ffffffff8181aacc)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In drivers/net/tun.c (ffffffff81cfca35)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81d0a307)
Location: include/linux/skbuff.h:2432
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ed6d63)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (ffffffff81ede2af)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/gro.c (ffffffff81f3cfa8)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/bpf/test_run.c (ffffffff81f9364e)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
```
In net/ipv4/ip_output.c (ffffffff81fbe04b)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81fd10e6)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9d29)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff82084101)
Location: include/linux/skbuff.h:2432
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fbb66)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8213e796)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff82146382)
Location: include/linux/skbuff.h:2432
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
