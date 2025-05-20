# Function: <code>skb_nfct</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (0)
Location: include/linux/skbuff.h:3605
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:3605
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:3605
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:3605
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/skbuff.h:3605
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/skbuff.h:3605
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/skbuff.h:3605
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/skbuff.h:3605
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/skbuff.h:3605
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/skbuff.h:3605
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:3605
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/skbuff.h:3605
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:3605
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/skbuff.h:3605
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/skbuff.h:3605
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/skbuff.h:3605
Inline: True
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
In drivers/net/tun.c (0)
Location: include/linux/skbuff.h:3789
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:3789
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:3789
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:3789
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/skbuff.h:3789
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/skbuff.h:3789
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/skbuff.h:3789
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/skbuff.h:3789
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/skbuff.h:3789
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/skbuff.h:3789
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:3789
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/skbuff.h:3789
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:3789
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/skbuff.h:3789
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/skbuff.h:3789
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/skbuff.h:3789
Inline: True
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
Location: include/linux/skbuff.h:3799
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8187bdcb)
Location: include/linux/skbuff.h:3799
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/netpoll.c (ffffffff818bf493)
Location: include/linux/skbuff.h:3799
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff818e825d)
Location: include/linux/skbuff.h:3799
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff818ebcbc)
Location: include/linux/skbuff.h:3799
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81912409)
Location: include/linux/skbuff.h:3799
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff8191a26f)
Location: include/linux/skbuff.h:3799
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8191f9b5)
Location: include/linux/skbuff.h:3799
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/ipmr.c (ffffffff81943b35)
Location: include/linux/skbuff.h:3799
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194f792)
Location: include/linux/skbuff.h:3799
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81956117)
Location: include/linux/skbuff.h:3799
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819566f4)
Location: include/linux/skbuff.h:3799
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81960fdd)
Location: include/linux/skbuff.h:3799
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81964251)
Location: include/linux/skbuff.h:3799
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff81988f06)
Location: include/linux/skbuff.h:3799
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff819b218c)
Location: include/linux/skbuff.h:3799
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
Location: include/linux/skbuff.h:3884
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8189d404)
Location: include/linux/skbuff.h:3884
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/netpoll.c (ffffffff818e82b2)
Location: include/linux/skbuff.h:3884
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81915780)
Location: include/linux/skbuff.h:3884
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81918f8c)
Location: include/linux/skbuff.h:3884
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940be5)
Location: include/linux/skbuff.h:3884
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81948abc)
Location: include/linux/skbuff.h:3884
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194e637)
Location: include/linux/skbuff.h:3884
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81973ca1)
Location: include/linux/skbuff.h:3884
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81982dc9)
Location: include/linux/skbuff.h:3884
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8198ad2f)
Location: include/linux/skbuff.h:3884
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b1ea)
Location: include/linux/skbuff.h:3884
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff8199588d)
Location: include/linux/skbuff.h:3884
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81999b21)
Location: include/linux/skbuff.h:3884
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff819bf866)
Location: include/linux/skbuff.h:3884
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff819e90b3)
Location: include/linux/skbuff.h:3884
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
Location: include/linux/skbuff.h:3991
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818e7c84)
Location: include/linux/skbuff.h:3991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/netpoll.c (ffffffff81937aec)
Location: include/linux/skbuff.h:3991
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81977cca)
Location: include/linux/skbuff.h:3991
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff8197b0b8)
Location: include/linux/skbuff.h:3991
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a51b6)
Location: include/linux/skbuff.h:3991
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819ad174)
Location: include/linux/skbuff.h:3991
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b2dc6)
Location: include/linux/skbuff.h:3991
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff819dd7bf)
Location: include/linux/skbuff.h:3991
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ecad3)
Location: include/linux/skbuff.h:3991
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819f57d1)
Location: include/linux/skbuff.h:3991
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6716)
Location: include/linux/skbuff.h:3991
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a01149)
Location: include/linux/skbuff.h:3991
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81a05a5d)
Location: include/linux/skbuff.h:3991
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a2e507)
Location: include/linux/skbuff.h:3991
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff81a5752d)
Location: include/linux/skbuff.h:3991
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff817c353c)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81919ea0)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/netpoll.c (ffffffff8196a9ac)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff819ae65a)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff819b1a28)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dbeb6)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819e3e44)
Location: include/linux/skbuff.h:4058
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e9b69)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81a148e1)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a23aeb)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2c481)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d399)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a37d25)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c5dc)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a6507a)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff81a8e575)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff8188e7e7)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff819ec062)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/netpoll.c (ffffffff81a3e5af)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81a984fa)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81a9c26c)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac900e)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81ad1518)
Location: include/linux/skbuff.h:4092
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad78d6)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81b05861)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15936)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e8f4)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b20028)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81b2dcf9)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b31c7c)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81b5d999)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/packet/af_packet.c (ffffffff81b8b0da)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff8189d151)
Location: include/linux/skbuff.h:4121
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff819eb872)
Location: include/linux/skbuff.h:4121
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/netpoll.c (ffffffff81a4134f)
Location: include/linux/skbuff.h:4121
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81aa244a)
Location: include/linux/skbuff.h:4121
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81aa60cc)
Location: include/linux/skbuff.h:4121
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4fae)
Location: include/linux/skbuff.h:4121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81add598)
Location: include/linux/skbuff.h:4121
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ae3f26)
Location: include/linux/skbuff.h:4121
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81b13a81)
Location: include/linux/skbuff.h:4121
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b23d9b)
Location: include/linux/skbuff.h:4121
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2d2f7)
Location: include/linux/skbuff.h:4121
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e93d)
Location: include/linux/skbuff.h:4121
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81b3c749)
Location: include/linux/skbuff.h:4121
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b4087c)
Location: include/linux/skbuff.h:4121
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81b6c17c)
Location: include/linux/skbuff.h:4121
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/packet/af_packet.c (ffffffff81b9a0f2)
Location: include/linux/skbuff.h:4121
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff8187f980)
Location: include/linux/skbuff.h:4185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff819d1e62)
Location: include/linux/skbuff.h:4185
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff819e8ab8)
Location: include/linux/skbuff.h:4185
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
```
```
In net/core/netpoll.c (ffffffff81a25fad)
Location: include/linux/skbuff.h:4185
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81a8d170)
Location: include/linux/skbuff.h:4185
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81a9128c)
Location: include/linux/skbuff.h:4185
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac0034)
Location: include/linux/skbuff.h:4185
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81ac8667)
Location: include/linux/skbuff.h:4185
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81acf108)
Location: include/linux/skbuff.h:4185
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81b018be)
Location: include/linux/skbuff.h:4185
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11a76)
Location: include/linux/skbuff.h:4185
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1af3a)
Location: include/linux/skbuff.h:4185
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c6bf)
Location: include/linux/skbuff.h:4185
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81b29ba9)
Location: include/linux/skbuff.h:4185
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e10c)
Location: include/linux/skbuff.h:4185
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81b5a4af)
Location: include/linux/skbuff.h:4185
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/packet/af_packet.c (ffffffff81b89064)
Location: include/linux/skbuff.h:4185
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff81910b09)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81a81ae2)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81a962a0)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
```
```
In net/core/netpoll.c (ffffffff81adad1d)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81b4830f)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81b4c620)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7dca4)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81b86ed0)
Location: include/linux/skbuff.h:4222
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b8daac)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81bc363e)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd556a)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdf4ac)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be102f)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81bef75f)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81bf43f9)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81c21b2f)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c4757c)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81c48fa6)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/packet/af_packet.c (ffffffff81c55174)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff81a608dd)
Location: include/linux/skbuff.h:4641
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81bf7080)
Location: include/linux/skbuff.h:4641
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/gro.c (ffffffff81c53825)
Location: include/linux/skbuff.h:4641
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/netpoll.c (ffffffff81c5b505)
Location: include/linux/skbuff.h:4641
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81cd5587)
Location: include/linux/skbuff.h:4641
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81cd9c74)
Location: include/linux/skbuff.h:4641
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0da8b)
Location: include/linux/skbuff.h:4641
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81d17b4a)
Location: include/linux/skbuff.h:4641
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d1ebea)
Location: include/linux/skbuff.h:4641
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81d58641)
Location: include/linux/skbuff.h:4641
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6bd69)
Location: include/linux/skbuff.h:4641
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81d76208)
Location: include/linux/skbuff.h:4641
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77edf)
Location: include/linux/skbuff.h:4641
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81d88247)
Location: include/linux/skbuff.h:4641
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d10a)
Location: include/linux/skbuff.h:4641
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81dbe971)
Location: include/linux/skbuff.h:4641
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de692e)
Location: include/linux/skbuff.h:4641
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81de8691)
Location: include/linux/skbuff.h:4641
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/packet/af_packet.c (ffffffff81df48ac)
Location: include/linux/skbuff.h:4641
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff81bece9e)
Location: include/linux/skbuff.h:4537
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81da5ff0)
Location: include/linux/skbuff.h:4537
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/gro.c (ffffffff81e08efc)
Location: include/linux/skbuff.h:4537
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/netpoll.c (ffffffff81e117cf)
Location: include/linux/skbuff.h:4537
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81e95a59)
Location: include/linux/skbuff.h:4537
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81e9a404)
Location: include/linux/skbuff.h:4537
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed3448)
Location: include/linux/skbuff.h:4537
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81ede3eb)
Location: include/linux/skbuff.h:4537
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee5d9c)
Location: include/linux/skbuff.h:4537
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81f22ad3)
Location: include/linux/skbuff.h:4537
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f370a9)
Location: include/linux/skbuff.h:4537
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42954)
Location: include/linux/skbuff.h:4537
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f4477f)
Location: include/linux/skbuff.h:4537
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81f55ff7)
Location: include/linux/skbuff.h:4537
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b201)
Location: include/linux/skbuff.h:4537
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81f8ee61)
Location: include/linux/skbuff.h:4537
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9740)
Location: include/linux/skbuff.h:4537
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb7d1)
Location: include/linux/skbuff.h:4537
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/packet/af_packet.c (ffffffff81fc9b3c)
Location: include/linux/skbuff.h:4537
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff81c4539f)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/virtio_net.c (ffffffff81c50ff0)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In net/core/skbuff.c (ffffffff81e150da)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/gro.c (ffffffff81e7b61d)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/netpoll.c (ffffffff81e850df)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81ef4299)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81ef8d5e)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f3214d)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81f3d722)
Location: include/linux/skbuff.h:4569
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f4551b)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81f82609)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f9696d)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa2144)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3f80)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81fb59c3)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb047)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81fec17f)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81fef2c2)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffee40)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019e8f)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff8201be91)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/packet/af_packet.c (ffffffff8202a46a)
Location: include/linux/skbuff.h:4569
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff81cfaccd)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/virtio_net.c (ffffffff81d0702d)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In net/core/skbuff.c (ffffffff81ed247a)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/gro.c (ffffffff81f3b8ad)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/netpoll.c (ffffffff81f470cf)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81fb8219)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81fbcc7e)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff8147)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff82003832)
Location: include/linux/skbuff.h:4609
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8200b52e)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff82048c88)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff82063d9b)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f522)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff820712b0)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff82083093)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff82088457)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff820b9d7d)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff820bcea2)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd9eb)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8e5f)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff820eae61)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/packet/af_packet.c (ffffffff820f9f75)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffff8000109deee4)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffff800010bb3d94)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/netpoll.c (ffff800010c10d10)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffff800010c5eb44)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffff800010c623d8)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8f13c)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffff800010c987e0)
Location: include/linux/skbuff.h:4058
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9f448)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffff800010ccfbf4)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0c4c)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffff800010cead3c)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec410)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffff800010cf8480)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffff800010cfd918)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffff800010d2af5c)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffff800010d5b704)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (c0ac2aec)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (c0cd05a0)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/netpoll.c (c0d27fe0)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (c0d6e1b4)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (c0d71bd4)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (c0d9e0bc)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (c0da6648)
Location: include/linux/skbuff.h:4058
Inline: True
```
```
In net/ipv4/udp.c (c0dac698)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (c0dda164)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (c0de9f60)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (c0df3064)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c0df42f8)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (c0dffbd8)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (c0e050b0)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (c0e2ee9c)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (c0e5b834)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (c000000000aa0848)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (c000000000c8a580)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/netpoll.c (c000000000cfc60c)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (c000000000d61594)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (c000000000d65694)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9de00)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (c000000000da9f3c)
Location: include/linux/skbuff.h:4058
Inline: True
```
```
In net/ipv4/udp.c (c000000000db1d84)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (c000000000dedc9c)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (c000000000e03028)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (c000000000e0ef18)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c000000000e10544)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (c000000000e20454)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (c000000000e259c0)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (c000000000e5c300)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (c000000000e95cc4)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffe00062813e)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffe0007447ce)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/netpoll.c (ffffffe00078c6dc)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffe0007c715e)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffe0007c9f4c)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ef322)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffe0007f6994)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_rcv
```
```
In net/ipv4/udp.c (ffffffe0007fbf28)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffe000821c86)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082f8e4)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffe000838a8c)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffe000839ba4)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffe000844238)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffe000847de8)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffe00086b52e)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffe000892850)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff81787fcd)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818b9ea0)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/netpoll.c (ffffffff8190a97c)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff8194e4ca)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81951898)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197bd26)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81983cb4)
Location: include/linux/skbuff.h:4058
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819899d9)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff819b3faf)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c317b)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819cbb11)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819cca29)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819d73b5)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff819dbc6c)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a0470a)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff81a2dc05)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff8176791d)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81873df0)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/netpoll.c (ffffffff818c3da5)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81907fba)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff8190b388)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819357e6)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff8193d774)
Location: include/linux/skbuff.h:4058
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81943499)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff819705df)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197ff6b)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81988901)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81989819)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81994175)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81998a2c)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff819c14ca)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff819eadf5)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff817b83bc)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8190aea0)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/netpoll.c (ffffffff8195b9ac)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199a755)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:__nfqnl_enqueue_packet
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199cb4b)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_attach
```
```
In net/netfilter/nf_conntrack_proto.c (ffffffff819a4943)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto.c:nf_confirm
```
```
In net/netfilter/nf_conntrack_proto_icmp.c (ffffffff819a78e3)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_inet_error
```
```
In net/ipv4/ip_input.c (ffffffff819b8c9a)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff819bc068)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e64f6)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819ee484)
Location: include/linux/skbuff.h:4058
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f41a9)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81a1e84f)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter/nf_defrag_ipv4.c (ffffffff81a20c11)
Location: include/linux/skbuff.h:4058
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2dbfb)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a36591)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a374a9)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a41e35)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81a466ec)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a6f18a)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/netfilter/nf_defrag_ipv6_hooks.c (ffffffff81a907c9)
Location: include/linux/skbuff.h:4058
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a997b5)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
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
In drivers/net/tun.c (ffffffff817d06c1)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8192bfa0)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/netpoll.c (ffffffff8197dd98)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff819c251a)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff819c5978)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819f01b6)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819f84e4)
Location: include/linux/skbuff.h:4058
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fe369)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81a29c85)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a393b7)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41ecc)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42e39)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a4dac5)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81a5241c)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a7b7ba)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff81aa45b7)
Location: include/linux/skbuff.h:4058
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
</details>
</li>
</ul>

## Differences
