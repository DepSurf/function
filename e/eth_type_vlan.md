# Function: <code>eth_type_vlan</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179f0ac)
Location: include/linux/if_vlan.h:281
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/flow_dissector.c (ffffffff817a6c82)
Location: include/linux/if_vlan.h:281
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff817b234c)
Location: include/linux/if_vlan.h:281
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff817ce739)
Location: include/linux/if_vlan.h:281
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
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
In net/core/skbuff.c (ffffffff817bc80c)
Location: include/linux/if_vlan.h:281
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/flow_dissector.c (ffffffff817c517a)
Location: include/linux/if_vlan.h:281
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff817cfb57)
Location: include/linux/if_vlan.h:281
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff817edbe9)
Location: include/linux/if_vlan.h:281
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
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
In net/core/skbuff.c (ffffffff81836edc)
Location: include/linux/if_vlan.h:281
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/flow_dissector.c (ffffffff8183ec98)
Location: include/linux/if_vlan.h:281
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818494a7)
Location: include/linux/if_vlan.h:281
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff81869e29)
Location: include/linux/if_vlan.h:281
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
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
In net/core/skbuff.c (0)
Location: include/linux/if_vlan.h:305
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/if_vlan.h:305
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/if_vlan.h:305
Inline: True
```
```
In net/core/tso.c (0)
Location: include/linux/if_vlan.h:305
Inline: True
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
In net/core/skbuff.c (ffffffff818a1eae)
Location: include/linux/if_vlan.h:316
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff818b3e9f)
Location: include/linux/if_vlan.h:316
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff818e08b9)
Location: include/linux/if_vlan.h:316
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
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
In net/core/skbuff.c (ffffffff818ec88e)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff819006f8)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff8192ef49)
Location: include/linux/if_vlan.h:311
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
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
In net/core/skbuff.c (ffffffff8191e9be)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81932a28)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff819611b9)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
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
In net/core/skbuff.c (ffffffff819f123e)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81a07ad1)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81a2d38b)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81a346cc)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:302
Inline: True
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
In net/core/skbuff.c (ffffffff819f1530)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81a090f0)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81a2ec2b)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81a369cd)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81a6f65b)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:302
Inline: True
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
In net/core/skbuff.c (ffffffff819d67c0)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff819ef9fd)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81a1628a)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81a1db49)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81a57f2f)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:302
Inline: True
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
In net/core/skbuff.c (ffffffff81a86e10)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81aa0e1d)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81ac71ea)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81ad15e9)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81b10eff)
Location: include/linux/if_vlan.h:302
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:302
Inline: True
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
In net/core/skbuff.c (ffffffff81bfc570)
Location: include/linux/if_vlan.h:307
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81c18c0e)
Location: include/linux/if_vlan.h:307
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81c4294b)
Location: include/linux/if_vlan.h:307
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81c4eedd)
Location: include/linux/if_vlan.h:307
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81c97fc1)
Location: include/linux/if_vlan.h:307
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:307
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df3603)
Location: include/linux/if_vlan.h:307
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
  - net/packet/af_packet.c:packet_parse_headers
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
In net/core/skbuff.c (ffffffff81dab461)
Location: include/linux/if_vlan.h:307
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81dc9bdc)
Location: include/linux/if_vlan.h:307
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81df793b)
Location: include/linux/if_vlan.h:307
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81e03f8d)
Location: include/linux/if_vlan.h:307
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81e53f71)
Location: include/linux/if_vlan.h:307
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:307
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc83d3)
Location: include/linux/if_vlan.h:307
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
  - net/packet/af_packet.c:packet_parse_headers
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
In net/core/skbuff.c (ffffffff81e1af61)
Location: include/linux/if_vlan.h:315
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81e3a74c)
Location: include/linux/if_vlan.h:315
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81e6963b)
Location: include/linux/if_vlan.h:315
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81e7677a)
Location: include/linux/if_vlan.h:315
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81eaf7f1)
Location: include/linux/if_vlan.h:315
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:315
Inline: True
```
```
In net/packet/af_packet.c (ffffffff82028ef3)
Location: include/linux/if_vlan.h:315
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
  - net/packet/af_packet.c:packet_parse_headers
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
In net/core/skbuff.c (ffffffff81ed7f51)
Location: include/linux/if_vlan.h:315
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81ef8ae0)
Location: include/linux/if_vlan.h:315
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81f28c1b)
Location: include/linux/if_vlan.h:315
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81f3673d)
Location: include/linux/if_vlan.h:315
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81f72271)
Location: include/linux/if_vlan.h:315
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:315
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820f8933)
Location: include/linux/if_vlan.h:315
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
  - net/packet/af_packet.c:packet_parse_headers
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
In net/core/skbuff.c (ffff800010bb9180)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffff800010bd0aac)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffff800010c04a7c)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
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
In net/core/skbuff.c (c0cd5c40)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (c0ceb664)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (c0d1dee0)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
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
In net/core/skbuff.c (c000000000c916b4)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (c000000000caea38)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (c000000000ceea28)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
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
In net/core/skbuff.c (ffffffe00074875c)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffe00075b172)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffe000783676)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
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
In net/core/skbuff.c (ffffffff818be9be)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff818d2a28)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff81901189)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
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
In net/core/skbuff.c (ffffffff818788fe)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff8188c8b8)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff818bafb9)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
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
In net/core/skbuff.c (ffffffff8190f9be)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81923a28)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff819521b9)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
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
In net/core/skbuff.c (ffffffff81930aee)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81944e98)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff81973bf9)
Location: include/linux/if_vlan.h:300
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
</details>
</li>
</ul>

## Differences
