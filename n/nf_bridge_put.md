# Function: <code>nf_bridge_put</code>

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
In drivers/net/tun.c (ffffffff815ee94f)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/virtio_net.c (ffffffff815f2526)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In net/core/skbuff.c (ffffffff81705451)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_input.c (ffffffff81758ab7)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff8175c603)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177eb4b)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81785ae6)
Location: include/linux/skbuff.h:3311
Inline: True
```
```
In net/ipv4/udp.c (ffffffff817896f5)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a4b7a)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff817a97e9)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b603f)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff817bbd5d)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc371)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff817c4b76)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff817c875a)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff817e6f95)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff818068ed)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv
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
In drivers/net/tun.c (ffffffff8164d50c)
Location: include/linux/skbuff.h:3518
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/virtio_net.c (ffffffff81651ea5)
Location: include/linux/skbuff.h:3518
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In net/core/skbuff.c (ffffffff8176ccb9)
Location: include/linux/skbuff.h:3518
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/ipv4/ip_input.c (ffffffff817c4e68)
Location: include/linux/skbuff.h:3518
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff817c9404)
Location: include/linux/skbuff.h:3518
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ebfb1)
Location: include/linux/skbuff.h:3518
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff817f30f6)
Location: include/linux/skbuff.h:3518
Inline: True
```
```
In net/ipv4/udp.c (ffffffff817f7d1a)
Location: include/linux/skbuff.h:3518
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/ipmr.c (ffffffff818183ba)
Location: include/linux/skbuff.h:3518
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
```
```
In net/xfrm/xfrm_policy.c (ffffffff81823060)
Location: include/linux/skbuff.h:3518
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81828d0d)
Location: include/linux/skbuff.h:3518
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81829295)
Location: include/linux/skbuff.h:3518
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81831c47)
Location: include/linux/skbuff.h:3518
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81835916)
Location: include/linux/skbuff.h:3518
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff818553a5)
Location: include/linux/skbuff.h:3518
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff8187a287)
Location: include/linux/skbuff.h:3518
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff8167f233)
Location: include/linux/skbuff.h:3570
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8179a139)
Location: include/linux/skbuff.h:3570
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/ipv4/ip_input.c (ffffffff817f4988)
Location: include/linux/skbuff.h:3570
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff817f8fa5)
Location: include/linux/skbuff.h:3570
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c93b)
Location: include/linux/skbuff.h:3570
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81823ed6)
Location: include/linux/skbuff.h:3570
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81828bea)
Location: include/linux/skbuff.h:3570
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/ipmr.c (ffffffff81849c1a)
Location: include/linux/skbuff.h:3570
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
```
```
In net/xfrm/xfrm_policy.c (ffffffff818549a9)
Location: include/linux/skbuff.h:3570
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a6ed)
Location: include/linux/skbuff.h:3570
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8185ac75)
Location: include/linux/skbuff.h:3570
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81863677)
Location: include/linux/skbuff.h:3570
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81867446)
Location: include/linux/skbuff.h:3570
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff81887115)
Location: include/linux/skbuff.h:3570
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff818aeaf7)
Location: include/linux/skbuff.h:3570
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff81694447)
Location: include/linux/skbuff.h:3628
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff817b93f0)
Location: include/linux/skbuff.h:3628
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/ipv4/ip_input.c (ffffffff81814e39)
Location: include/linux/skbuff.h:3628
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff818193c5)
Location: include/linux/skbuff.h:3628
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183d11b)
Location: include/linux/skbuff.h:3628
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81844b9e)
Location: include/linux/skbuff.h:3628
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81849e8a)
Location: include/linux/skbuff.h:3628
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/ipmr.c (ffffffff8186d56d)
Location: include/linux/skbuff.h:3628
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
```
```
In net/xfrm/xfrm_policy.c (ffffffff81878478)
Location: include/linux/skbuff.h:3628
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8187e7b0)
Location: include/linux/skbuff.h:3628
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8187ea8c)
Location: include/linux/skbuff.h:3628
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81888ad3)
Location: include/linux/skbuff.h:3628
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff8188bb9e)
Location: include/linux/skbuff.h:3628
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff818ad7a9)
Location: include/linux/skbuff.h:3628
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff818d3847)
Location: include/linux/skbuff.h:3628
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff816fe56b)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818334d7)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/ipv4/ip_input.c (ffffffff81893fff)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff81897985)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc8d8)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff818c45de)
Location: include/linux/skbuff.h:3812
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c9a96)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/ipmr.c (ffffffff818ede7d)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8d7b)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff818ff621)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffb1e)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81909c60)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff8190ce83)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff81930331)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff81958768)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff8173d72d)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8187d977)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/ipv4/ip_input.c (ffffffff818e827b)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff818ebccf)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81912428)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff8191a28e)
Location: include/linux/skbuff.h:3822
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8191f9d4)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/ipmr.c (ffffffff81943b54)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194f7b4)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81956136)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81956713)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81960ff0)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81964270)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff81988f25)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff819b21ab)
Location: include/linux/skbuff.h:3822
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
