# Function: <code>nf_reset</code>

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
In drivers/net/tun.c (ffffffff815ee92e)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/virtio_net.c (ffffffff815f2508)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In net/core/skbuff.c (ffffffff81706337)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_input.c (ffffffff81758a96)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177eb2d)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81785acc)
Location: include/linux/skbuff.h:3322
Inline: True
```
```
In net/ipv4/udp.c (ffffffff817896d4)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a4b5c)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff817a97bf)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b6021)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff817bbd3f)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc353)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff817c873c)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff817e6f77)
Location: include/linux/skbuff.h:3322
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff818068cf)
Location: include/linux/skbuff.h:3322
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
In drivers/net/tun.c (ffffffff8164d4ee)
Location: include/linux/skbuff.h:3529
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/virtio_net.c (ffffffff81651e86)
Location: include/linux/skbuff.h:3529
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In net/core/skbuff.c (ffffffff8176cc92)
Location: include/linux/skbuff.h:3529
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_input.c (ffffffff817c4e46)
Location: include/linux/skbuff.h:3529
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ebf8b)
Location: include/linux/skbuff.h:3529
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff817f30dc)
Location: include/linux/skbuff.h:3529
Inline: True
```
```
In net/ipv4/udp.c (ffffffff817f7cfc)
Location: include/linux/skbuff.h:3529
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/ipmr.c (ffffffff81818399)
Location: include/linux/skbuff.h:3529
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
```
```
In net/xfrm/xfrm_policy.c (ffffffff81823041)
Location: include/linux/skbuff.h:3529
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81828cee)
Location: include/linux/skbuff.h:3529
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81829276)
Location: include/linux/skbuff.h:3529
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff818358f7)
Location: include/linux/skbuff.h:3529
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff8185537e)
Location: include/linux/skbuff.h:3529
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff8187a268)
Location: include/linux/skbuff.h:3529
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
In drivers/net/tun.c (ffffffff8167f214)
Location: include/linux/skbuff.h:3581
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8179a112)
Location: include/linux/skbuff.h:3581
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_input.c (ffffffff817f4966)
Location: include/linux/skbuff.h:3581
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c915)
Location: include/linux/skbuff.h:3581
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81823ebc)
Location: include/linux/skbuff.h:3581
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81828bcc)
Location: include/linux/skbuff.h:3581
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/ipmr.c (ffffffff81849bf9)
Location: include/linux/skbuff.h:3581
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
```
```
In net/xfrm/xfrm_policy.c (ffffffff8185498a)
Location: include/linux/skbuff.h:3581
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a6ce)
Location: include/linux/skbuff.h:3581
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8185ac56)
Location: include/linux/skbuff.h:3581
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff81867427)
Location: include/linux/skbuff.h:3581
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff818870ee)
Location: include/linux/skbuff.h:3581
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff818aead8)
Location: include/linux/skbuff.h:3581
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
In drivers/net/tun.c (ffffffff81694428)
Location: include/linux/skbuff.h:3639
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff817b93cd)
Location: include/linux/skbuff.h:3639
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_input.c (ffffffff81814e17)
Location: include/linux/skbuff.h:3639
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183d0f4)
Location: include/linux/skbuff.h:3639
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81844b7f)
Location: include/linux/skbuff.h:3639
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81849e6a)
Location: include/linux/skbuff.h:3639
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/ipmr.c (ffffffff8186d545)
Location: include/linux/skbuff.h:3639
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
```
```
In net/xfrm/xfrm_policy.c (ffffffff81878458)
Location: include/linux/skbuff.h:3639
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8187e78a)
Location: include/linux/skbuff.h:3639
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8187ea6c)
Location: include/linux/skbuff.h:3639
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff8188bb7e)
Location: include/linux/skbuff.h:3639
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff818ad781)
Location: include/linux/skbuff.h:3639
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff818d3827)
Location: include/linux/skbuff.h:3639
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
In drivers/net/tun.c (ffffffff816fe54c)
Location: include/linux/skbuff.h:3823
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81832253)
Location: include/linux/skbuff.h:3823
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81893fdd)
Location: include/linux/skbuff.h:3823
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc8af)
Location: include/linux/skbuff.h:3823
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff818c45bf)
Location: include/linux/skbuff.h:3823
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c9a6e)
Location: include/linux/skbuff.h:3823
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/ipmr.c (ffffffff818ede55)
Location: include/linux/skbuff.h:3823
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8d58)
Location: include/linux/skbuff.h:3823
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff818ff5f3)
Location: include/linux/skbuff.h:3823
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffafe)
Location: include/linux/skbuff.h:3823
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff8190ce63)
Location: include/linux/skbuff.h:3823
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff81930309)
Location: include/linux/skbuff.h:3823
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff81958748)
Location: include/linux/skbuff.h:3823
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
In drivers/net/tun.c (ffffffff8173d70e)
Location: include/linux/skbuff.h:3833
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8187c9f6)
Location: include/linux/skbuff.h:3833
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff818e825d)
Location: include/linux/skbuff.h:3833
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81912409)
Location: include/linux/skbuff.h:3833
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff8191a26f)
Location: include/linux/skbuff.h:3833
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8191f9b5)
Location: include/linux/skbuff.h:3833
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/ipmr.c (ffffffff81943b35)
Location: include/linux/skbuff.h:3833
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194f792)
Location: include/linux/skbuff.h:3833
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81956117)
Location: include/linux/skbuff.h:3833
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819566f4)
Location: include/linux/skbuff.h:3833
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff81964251)
Location: include/linux/skbuff.h:3833
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff81988f06)
Location: include/linux/skbuff.h:3833
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff819b218c)
Location: include/linux/skbuff.h:3833
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff817610cc)
Location: include/linux/skbuff.h:3997
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8189d404)
Location: include/linux/skbuff.h:3997
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_input.c (ffffffff81915780)
Location: include/linux/skbuff.h:3997
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940be5)
Location: include/linux/skbuff.h:3997
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81948abc)
Location: include/linux/skbuff.h:3997
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194e637)
Location: include/linux/skbuff.h:3997
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81973ca1)
Location: include/linux/skbuff.h:3997
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81982dc9)
Location: include/linux/skbuff.h:3997
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8198ad2f)
Location: include/linux/skbuff.h:3997
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b1ea)
Location: include/linux/skbuff.h:3997
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff81999b21)
Location: include/linux/skbuff.h:3997
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff819bf866)
Location: include/linux/skbuff.h:3997
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff819e90b3)
Location: include/linux/skbuff.h:3997
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff8179ed50)
Location: include/linux/skbuff.h:4104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818e7c84)
Location: include/linux/skbuff.h:4104
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_input.c (ffffffff81977cca)
Location: include/linux/skbuff.h:4104
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a51b6)
Location: include/linux/skbuff.h:4104
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819ad174)
Location: include/linux/skbuff.h:4104
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b2dc6)
Location: include/linux/skbuff.h:4104
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff819dd7bf)
Location: include/linux/skbuff.h:4104
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ecad3)
Location: include/linux/skbuff.h:4104
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819f57d1)
Location: include/linux/skbuff.h:4104
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6716)
Location: include/linux/skbuff.h:4104
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff81a05a5d)
Location: include/linux/skbuff.h:4104
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a2e507)
Location: include/linux/skbuff.h:4104
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff81a5752d)
Location: include/linux/skbuff.h:4104
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
</details>
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
