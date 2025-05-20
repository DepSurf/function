# Function: <code>skb_ext_del</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817610e7)
Location: include/linux/skbuff.h:3974
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8189d3fe)
Location: include/linux/skbuff.h:3974
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/dev.c (ffffffff818ae9e4)
Location: include/linux/skbuff.h:3974
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/ipv4/ip_input.c (ffffffff81915799)
Location: include/linux/skbuff.h:3974
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940c00)
Location: include/linux/skbuff.h:3974
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81948ad7)
Location: include/linux/skbuff.h:3974
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194e652)
Location: include/linux/skbuff.h:3974
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff81973cbc)
Location: include/linux/skbuff.h:3974
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81982de6)
Location: include/linux/skbuff.h:3974
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a8c8)
Location: include/linux/skbuff.h:3974
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b6cb)
Location: include/linux/skbuff.h:3974
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff81999b3c)
Location: include/linux/skbuff.h:3974
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff819bf881)
Location: include/linux/skbuff.h:3974
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff819e90ce)
Location: include/linux/skbuff.h:3974
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
In drivers/net/tun.c (ffffffff8179ed6d)
Location: include/linux/skbuff.h:4081
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff818e7c7e)
Location: include/linux/skbuff.h:4081
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/dev.c (ffffffff818fa2d6)
Location: include/linux/skbuff.h:4081
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/ipv4/ip_input.c (ffffffff81977ce5)
Location: include/linux/skbuff.h:4081
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a51d3)
Location: include/linux/skbuff.h:4081
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819ad191)
Location: include/linux/skbuff.h:4081
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b2de3)
Location: include/linux/skbuff.h:4081
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/ipmr.c (ffffffff819dd7dc)
Location: include/linux/skbuff.h:4081
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ecaea)
Location: include/linux/skbuff.h:4081
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819f550f)
Location: include/linux/skbuff.h:4081
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6beb)
Location: include/linux/skbuff.h:4081
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_input.c (ffffffff81a05a78)
Location: include/linux/skbuff.h:4081
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a2e522)
Location: include/linux/skbuff.h:4081
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/packet/af_packet.c (ffffffff81a5754a)
Location: include/linux/skbuff.h:4081
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
In net/xfrm/xfrm_input.c (ffffffff81a2c1bf)
Location: include/linux/skbuff.h:4153
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d85b)
Location: include/linux/skbuff.h:4153
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/sched/cls_api.c (ffffffff81a6bee9)
Location: include/linux/skbuff.h:4193
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify_ingress
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e752)
Location: include/linux/skbuff.h:4193
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2028b)
Location: include/linux/skbuff.h:4193
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/mptcp/subflow.c (ffffffff81baf236)
Location: include/linux/skbuff.h:4193
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
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
In net/sched/cls_api.c (ffffffff81a7477d)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify_ingress
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2d022)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2ebcb)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/mptcp/subflow.c (ffffffff81bc1f51)
Location: include/linux/skbuff.h:4222
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5d311)
Location: include/linux/skbuff.h:4286
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify_ingress
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1ac65)
Location: include/linux/skbuff.h:4286
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c980)
Location: include/linux/skbuff.h:4286
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/mptcp/subflow.c (ffffffff81bb2779)
Location: include/linux/skbuff.h:4286
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff81bb1200-ffffffff81bb1217: skb_ext_del.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b168f8)
Location: include/linux/skbuff.h:4324
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdf188)
Location: include/linux/skbuff.h:4324
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be12f2)
Location: include/linux/skbuff.h:4324
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/mptcp/subflow.c (ffffffff81c80ffd)
Location: include/linux/skbuff.h:4324
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff81c7f5b0-ffffffff81c7f5c7: skb_ext_del.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9e004)
Location: include/linux/skbuff.h:4746
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify
```
```
In net/xfrm/xfrm_input.c (ffffffff81d75f02)
Location: include/linux/skbuff.h:4746
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d78224)
Location: include/linux/skbuff.h:4746
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/mptcp/subflow.c (ffffffff81e26a0f)
Location: include/linux/skbuff.h:4746
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff81e251f0-ffffffff81e25217: skb_ext_del.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5a714)
Location: include/linux/skbuff.h:4642
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f37b69)
Location: include/linux/skbuff.h:4642
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42642)
Location: include/linux/skbuff.h:4642
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44ae8)
Location: include/linux/skbuff.h:4642
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/mptcp/subflow.c (ffffffff81ffe17e)
Location: include/linux/skbuff.h:4642
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff81ffcd60-ffffffff81ffcd87: skb_ext_del.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb6325)
Location: include/linux/skbuff.h:4674
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1ef2)
Location: include/linux/skbuff.h:4674
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa42af)
Location: include/linux/skbuff.h:4674
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/mptcp/subflow.c (ffffffff8207a362)
Location: include/linux/skbuff.h:4674
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff82079030-ffffffff82079057: skb_ext_del.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f79025)
Location: include/linux/skbuff.h:4714
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f2cf)
Location: include/linux/skbuff.h:4714
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8207160d)
Location: include/linux/skbuff.h:4714
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/mptcp/subflow.c (ffffffff8214f7c2)
Location: include/linux/skbuff.h:4714
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff8214e290-ffffffff8214e2b7: skb_ext_del.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_input.c (ffff800010ceafe0)
Location: include/linux/skbuff.h:4153
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec5ec)
Location: include/linux/skbuff.h:4153
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (c0df2c9c)
Location: include/linux/skbuff.h:4153
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c0df4518)
Location: include/linux/skbuff.h:4153
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (c000000000e0ec40)
Location: include/linux/skbuff.h:4153
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c000000000e107c8)
Location: include/linux/skbuff.h:4153
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffffffe0008387ae)
Location: include/linux/skbuff.h:4153
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffe000839cd8)
Location: include/linux/skbuff.h:4153
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffffffff819cb84f)
Location: include/linux/skbuff.h:4153
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819cceeb)
Location: include/linux/skbuff.h:4153
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffffffff8198863f)
Location: include/linux/skbuff.h:4153
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81989cdb)
Location: include/linux/skbuff.h:4153
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffffffff81a362cf)
Location: include/linux/skbuff.h:4153
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a3796b)
Location: include/linux/skbuff.h:4153
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffffffff81a41c3b)
Location: include/linux/skbuff.h:4153
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a4332b)
Location: include/linux/skbuff.h:4153
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
</details>
</li>
</ul>

## Differences
