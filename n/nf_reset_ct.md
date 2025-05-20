# Function: <code>nf_reset_ct</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c353c)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81919ea0)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_input.c (ffffffff819ae65a)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dbeb6)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819e3e44)
Location: include/linux/skbuff.h:4191
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e9b69)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81a148e1)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a23aeb)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2c481)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d399)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c5dc)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a6507a)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff81a8e575)
Location: include/linux/skbuff.h:4191
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
Location: include/linux/skbuff.h:4231
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff819ec062)
Location: include/linux/skbuff.h:4231
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_input.c (ffffffff81a984fa)
Location: include/linux/skbuff.h:4231
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac900e)
Location: include/linux/skbuff.h:4231
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81ad1518)
Location: include/linux/skbuff.h:4231
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad78d6)
Location: include/linux/skbuff.h:4231
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81b05861)
Location: include/linux/skbuff.h:4231
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15936)
Location: include/linux/skbuff.h:4231
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e8f4)
Location: include/linux/skbuff.h:4231
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b20028)
Location: include/linux/skbuff.h:4231
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff81b31c7c)
Location: include/linux/skbuff.h:4231
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81b5d999)
Location: include/linux/skbuff.h:4231
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/packet/af_packet.c (ffffffff81b8b0da)
Location: include/linux/skbuff.h:4231
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
Location: include/linux/skbuff.h:4260
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff819eb872)
Location: include/linux/skbuff.h:4260
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_input.c (ffffffff81aa244a)
Location: include/linux/skbuff.h:4260
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4fae)
Location: include/linux/skbuff.h:4260
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81add598)
Location: include/linux/skbuff.h:4260
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ae3f26)
Location: include/linux/skbuff.h:4260
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81b13a81)
Location: include/linux/skbuff.h:4260
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b23d9b)
Location: include/linux/skbuff.h:4260
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2d2f7)
Location: include/linux/skbuff.h:4260
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e93d)
Location: include/linux/skbuff.h:4260
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff81b4087c)
Location: include/linux/skbuff.h:4260
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81b6c17c)
Location: include/linux/skbuff.h:4260
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/packet/af_packet.c (ffffffff81b9a0f2)
Location: include/linux/skbuff.h:4260
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
Location: include/linux/skbuff.h:4324
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff819d1e62)
Location: include/linux/skbuff.h:4324
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:napi_skb_free_stolen_head
```
```
In net/core/dev.c (ffffffff819e8ab8)
Location: include/linux/skbuff.h:4324
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
```
```
In net/ipv4/ip_input.c (ffffffff81a8d170)
Location: include/linux/skbuff.h:4324
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac0034)
Location: include/linux/skbuff.h:4324
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81ac8667)
Location: include/linux/skbuff.h:4324
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81acf108)
Location: include/linux/skbuff.h:4324
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81b018be)
Location: include/linux/skbuff.h:4324
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11a76)
Location: include/linux/skbuff.h:4324
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1af3a)
Location: include/linux/skbuff.h:4324
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c6bf)
Location: include/linux/skbuff.h:4324
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e10c)
Location: include/linux/skbuff.h:4324
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81b5a4af)
Location: include/linux/skbuff.h:4324
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/packet/af_packet.c (ffffffff81b89064)
Location: include/linux/skbuff.h:4324
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
Location: include/linux/skbuff.h:4362
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81a81ae2)
Location: include/linux/skbuff.h:4362
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:napi_skb_free_stolen_head
```
```
In net/core/dev.c (ffffffff81a962a0)
Location: include/linux/skbuff.h:4362
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
```
```
In net/ipv4/ip_input.c (ffffffff81b4830f)
Location: include/linux/skbuff.h:4362
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7dca4)
Location: include/linux/skbuff.h:4362
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81b86ed0)
Location: include/linux/skbuff.h:4362
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b8daac)
Location: include/linux/skbuff.h:4362
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81bc363e)
Location: include/linux/skbuff.h:4362
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd556a)
Location: include/linux/skbuff.h:4362
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdf4ac)
Location: include/linux/skbuff.h:4362
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be102f)
Location: include/linux/skbuff.h:4362
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff81bf43f9)
Location: include/linux/skbuff.h:4362
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81c21b2f)
Location: include/linux/skbuff.h:4362
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c4757c)
Location: include/linux/skbuff.h:4362
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81c48fa6)
Location: include/linux/skbuff.h:4362
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/packet/af_packet.c (ffffffff81c55174)
Location: include/linux/skbuff.h:4362
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
Location: include/linux/skbuff.h:4784
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81bfd946)
Location: include/linux/skbuff.h:4784
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_skb_free_stolen_head
```
```
In net/core/gro.c (ffffffff81c53825)
Location: include/linux/skbuff.h:4784
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/ipv4/ip_input.c (ffffffff81cd5587)
Location: include/linux/skbuff.h:4784
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0da8b)
Location: include/linux/skbuff.h:4784
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81d17b4a)
Location: include/linux/skbuff.h:4784
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d1ebea)
Location: include/linux/skbuff.h:4784
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81d58641)
Location: include/linux/skbuff.h:4784
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6bd69)
Location: include/linux/skbuff.h:4784
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81d76208)
Location: include/linux/skbuff.h:4784
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77edf)
Location: include/linux/skbuff.h:4784
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d10a)
Location: include/linux/skbuff.h:4784
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81dbe971)
Location: include/linux/skbuff.h:4784
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de692e)
Location: include/linux/skbuff.h:4784
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81de8691)
Location: include/linux/skbuff.h:4784
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/packet/af_packet.c (ffffffff81df48ac)
Location: include/linux/skbuff.h:4784
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
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81dae676)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_skb_free_stolen_head
```
```
In net/core/gro.c (ffffffff81e08efc)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/ipv4/ip_input.c (ffffffff81e95a59)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed3448)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81ede3eb)
Location: include/linux/skbuff.h:4680
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee5d9c)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81f22ad3)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f370a9)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42954)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f4477f)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b201)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81f8ee61)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9740)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb7d1)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/packet/af_packet.c (ffffffff81fc9b3c)
Location: include/linux/skbuff.h:4680
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
Location: include/linux/skbuff.h:4712
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/virtio_net.c (ffffffff81c50ff0)
Location: include/linux/skbuff.h:4712
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In net/core/skbuff.c (ffffffff81e1e527)
Location: include/linux/skbuff.h:4712
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_skb_free_stolen_head
```
```
In net/core/gro.c (ffffffff81e7b61d)
Location: include/linux/skbuff.h:4712
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/ipv4/ip_input.c (ffffffff81ef4299)
Location: include/linux/skbuff.h:4712
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f3214d)
Location: include/linux/skbuff.h:4712
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81f3d722)
Location: include/linux/skbuff.h:4712
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f4551b)
Location: include/linux/skbuff.h:4712
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81f82609)
Location: include/linux/skbuff.h:4712
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f9696d)
Location: include/linux/skbuff.h:4712
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa2144)
Location: include/linux/skbuff.h:4712
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3f80)
Location: include/linux/skbuff.h:4712
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb047)
Location: include/linux/skbuff.h:4712
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81fec17f)
Location: include/linux/skbuff.h:4712
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81fef2c2)
Location: include/linux/skbuff.h:4712
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffee40)
Location: include/linux/skbuff.h:4712
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019e8f)
Location: include/linux/skbuff.h:4712
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff8201be91)
Location: include/linux/skbuff.h:4712
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/packet/af_packet.c (ffffffff8202a46a)
Location: include/linux/skbuff.h:4712
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
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/virtio_net.c (ffffffff81d0702d)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In net/core/skbuff.c (ffffffff81edbbee)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_skb_free_stolen_head
```
```
In net/core/gro.c (ffffffff81f3b8ad)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/ipv4/ip_input.c (ffffffff81fb8219)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff8147)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff82003832)
Location: include/linux/skbuff.h:4752
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8200b52e)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff82048c88)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff82063d9b)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f522)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff820712b0)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff82088457)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff820b9d7d)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff820bcea2)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd9eb)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8e5f)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff820eae61)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/packet/af_packet.c (ffffffff820f9f75)
Location: include/linux/skbuff.h:4752
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
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffff800010bb3d94)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_input.c (ffff800010c5eb44)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8f13c)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffff800010c987e0)
Location: include/linux/skbuff.h:4191
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9f448)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffff800010ccfbf4)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0c4c)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffff800010cead3c)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec410)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffff800010cfd918)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffff800010d2af5c)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffff800010d5b704)
Location: include/linux/skbuff.h:4191
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
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (c0cd0d24)
Location: include/linux/skbuff.h:4191
Inline: True
```
```
In net/ipv4/ip_input.c (c0d6e1b4)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (c0d9e0bc)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (c0da6648)
Location: include/linux/skbuff.h:4191
Inline: True
```
```
In net/ipv4/udp.c (c0dac698)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (c0dda164)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (c0de9f60)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (c0df3064)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c0df42f8)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (c0e050b0)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (c0e2ee9c)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (c0e5b834)
Location: include/linux/skbuff.h:4191
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
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (c000000000c8a580)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_input.c (c000000000d61594)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9de00)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (c000000000da9f3c)
Location: include/linux/skbuff.h:4191
Inline: True
```
```
In net/ipv4/udp.c (c000000000db1d84)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (c000000000dedc9c)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (c000000000e03028)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (c000000000e0ef18)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c000000000e10544)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (c000000000e259c0)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (c000000000e5c300)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (c000000000e95cc4)
Location: include/linux/skbuff.h:4191
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
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffe0007447ce)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_input.c (ffffffe0007c7108)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ef322)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffe0007f6994)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_rcv
```
```
In net/ipv4/udp.c (ffffffe0007fbf28)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffe000821c86)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082f85c)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffe000838a8c)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffe000839b76)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffe000847de8)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffe00086b52e)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffe000892850)
Location: include/linux/skbuff.h:4191
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
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818b9ea0)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_input.c (ffffffff8194e4ca)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197bd26)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81983cb4)
Location: include/linux/skbuff.h:4191
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819899d9)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff819b3faf)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c317b)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819cbb11)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819cca29)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff819dbc6c)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a0470a)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff81a2dc05)
Location: include/linux/skbuff.h:4191
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
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff81873df0)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_input.c (ffffffff81907fba)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819357e6)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff8193d774)
Location: include/linux/skbuff.h:4191
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81943499)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff819705df)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197ff6b)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81988901)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81989819)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff81998a2c)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff819c14ca)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff819eadf5)
Location: include/linux/skbuff.h:4191
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
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8190aea0)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_input.c (ffffffff819b8c9a)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e64f6)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819ee484)
Location: include/linux/skbuff.h:4191
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f41a9)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81a1e84f)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2dbfb)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a36591)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a374a9)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff81a466ec)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a6f18a)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff81a997b5)
Location: include/linux/skbuff.h:4191
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
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8192bfa0)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_input.c (ffffffff819c251a)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819f01b6)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819f84e4)
Location: include/linux/skbuff.h:4191
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fe369)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81a29c85)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a393b7)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41ecc)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42e39)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff81a5241c)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a7b7ba)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff81aa45b7)
Location: include/linux/skbuff.h:4191
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
</details>
</li>
</ul>

## Differences
