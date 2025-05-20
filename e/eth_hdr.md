# Function: <code>eth_hdr</code>

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
In net/core/flow_dissector.c (0)
Location: include/linux/if_ether.h:26
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/if_ether.h:26
Inline: True
```
```
In net/ethernet/eth.c (0)
Location: include/linux/if_ether.h:26
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/if_ether.h:26
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/if_ether.h:26
Inline: True
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
In net/core/flow_dissector.c (ffffffff81779832)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff8177fe6e)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/ethernet/eth.c (ffffffff817aca85)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/packet/af_packet.c (ffffffff81879c87)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff8187b1c4)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/flow_dissector.c (ffffffff817a694a)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff817ad53d)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/ethernet/eth.c (ffffffff817dc075)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/packet/af_packet.c (ffffffff818ae384)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff818afa84)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/flow_dissector.c (ffffffff817c4afe)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff817cc0ed)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/ethernet/eth.c (ffffffff817fb675)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/packet/af_packet.c (ffffffff818d4d8b)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff818d624c)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/flow_dissector.c (ffffffff8183e451)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81845739)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/ethernet/eth.c (ffffffff81879025)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv6/addrconf.c (ffffffff81915f78)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81929196)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffffffff8195980d)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff8195bf14)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/flow_dissector.c (ffffffff81888c8b)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff8188ed20)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/ethernet/eth.c (ffffffff818caa15)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv6/addrconf.c (ffffffff8196f442)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff8198295f)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffffffff819b04b4)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff819b561a)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/flow_dissector.c (ffffffff818aa0a7)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818afdc0)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/ethernet/eth.c (ffffffff818f5ae5)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv6/addrconf.c (ffffffff819a4ff2)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff819b8fff)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffffffff819e7cbb)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff819ec8e5)
Location: include/linux/if_ether.h:26
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff818ea436)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/flow_dissector.c (ffffffff818f5389)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818fbc1c)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/ethernet/eth.c (ffffffff81955115)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4f33)
Location: include/linux/if_ether.h:22
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a11432)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81a27b09)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffffffff81a54852)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81a5ba8f)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8191c5b2)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/flow_dissector.c (ffffffff81927267)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff8192e1ec)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/ethernet/eth.c (ffffffff8198b5b5)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2bbe3)
Location: include/linux/if_ether.h:22
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a480a1)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81a5e569)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffffffff81a8b442)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81a92808)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff819f0709)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/flow_dissector.c (ffffffff819fb6c4)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a023a9)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/ethernet/eth.c (ffffffff81a632b5)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1ddc2)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/addrconf.c (ffffffff81b3eb6b)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81b5733f)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffffffff81b87260)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81b8dcbb)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff819f045e)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/flow_dissector.c (ffffffff819fb39d)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a02ba9)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a30fe0)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ethernet/eth.c (ffffffff81a6b405)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c690)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/addrconf.c (ffffffff81c32c15)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81c32e3c)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffffffff81b96db9)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81b9d98a)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff819d4da2)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/flow_dissector.c (ffffffff819e161b)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff819e71b7)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81a18020)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ethernet/eth.c (ffffffff81a53b25)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a2ec)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/addrconf.c (ffffffff81c24f3b)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81c2513d)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffffffff81b85dbe)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81b8cab3)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81a84b32)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/flow_dissector.c (ffffffff81a91a5c)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a97b67)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81acb730)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ethernet/eth.c (ffffffff81b0c835)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde90c)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/addrconf.c (ffffffff81d3fa4c)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81d4052a)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffffffff81c52164)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81c58e73)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81bfab18)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/flow_dissector.c (ffffffff81c07caa)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81c1171b)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81c47350)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ethernet/eth.c (ffffffff81c93165)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/xfrm/xfrm_input.c (ffffffff81d75762)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/addrconf.c (ffffffff81f0c3c0)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81f0cef5)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffffffff81df44c9)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81dfa526)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81da99a9)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/flow_dissector.c (ffffffff81db7766)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81dc12cc)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81dfb8b0)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ethernet/eth.c (ffffffff81e4e7a5)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41d7f)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/addrconf.c (ffffffff81f68a5f)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81f8470a)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffffffff81fc923c)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81fcec47)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81e184a9)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/flow_dissector.c (ffffffff81e27d12)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81e310ec)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81e6c7b0)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ethernet/eth.c (ffffffff81ea9e45)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1611)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/addrconf.c (ffffffff81fc8b3c)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81fe4a57)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffffffff8202995e)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff8204a47c)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/netkit.c (ffffffff81ce53bc)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_xmit
```
```
In net/core/skbuff.c (ffffffff81ed5949)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/flow_dissector.c (ffffffff81ee5cc2)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81eed5f9)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81f2c090)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ethernet/eth.c (ffffffff81f6c905)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/xfrm/xfrm_input.c (ffffffff8206e931)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/ipv6/addrconf.c (ffffffff8209629c)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff820b295b)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffffffff820f9425)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff8211c8e8)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffff800010bb6b94)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/flow_dissector.c (ffff800010bc37e0)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffff800010bcd648)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/ethernet/eth.c (ffff800010c36410)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/xfrm/xfrm_input.c (ffff800010cea608)
Location: include/linux/if_ether.h:22
Inline: True
```
```
In net/ipv6/addrconf.c (ffff800010d08e2c)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffff800010d222e0)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffff800010d59f48)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffff800010d60448)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (c0cd39f0)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/flow_dissector.c (c0cdeadc)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (c0ce78bc)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/ethernet/eth.c (c0d48ea0)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/xfrm/xfrm_input.c (c0df24c0)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/ipv6/addrconf.c (c0e0f3e4)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (c0e27fcc)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/packet/af_packet.c (c0e589d8)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (c0e6007c)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (c000000000c8e4f0)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/flow_dissector.c (c000000000c9d984)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (c000000000ca7410)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/ethernet/eth.c (c000000000d2e4f8)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/xfrm/xfrm_input.c (c000000000e0e224)
Location: include/linux/if_ether.h:22
Inline: True
```
```
In net/ipv6/addrconf.c (c000000000e33404)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (c000000000e51d64)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (c000000000e941cc)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (c000000000e9b670)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffe000746828)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/flow_dissector.c (ffffffe000750480)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffe000756daa)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/ethernet/eth.c (ffffffe0007a7d80)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/xfrm/xfrm_input.c (ffffffe0008381e4)
Location: include/linux/if_ether.h:22
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffe000850bb2)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffe000863ef8)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffffffe00088fe46)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffe000895978)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff818bc5b2)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/flow_dissector.c (ffffffff818c7267)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818ce1ec)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/ethernet/eth.c (ffffffff8192b425)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb273)
Location: include/linux/if_ether.h:22
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819e7731)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff819fdbf9)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffffffff81a2aad2)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81a31e98)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/vxlan.c (ffffffff81773b2d)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:route_shortcircuit
  - drivers/net/vxlan.c:route_shortcircuit
  - drivers/net/vxlan.c:route_shortcircuit
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/core/skbuff.c (ffffffff818764f2)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/flow_dissector.c (ffffffff818811a7)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff8188830c)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/ethernet/eth.c (ffffffff818e51d5)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967ec3)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81988063)
Location: include/linux/if_ether.h:22
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819a44f1)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff819ba9b9)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffffffff819e7cc2)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff819ef088)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8190d5b2)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/flow_dissector.c (ffffffff81918267)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff8191f1ec)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/ethernet/eth.c (ffffffff8197c5b5)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35cf3)
Location: include/linux/if_ether.h:22
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a521b1)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81a68679)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffffffff81a96682)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81a9da48)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8192e6e2)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/flow_dissector.c (ffffffff81939611)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81940f4c)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/ethernet/eth.c (ffffffff8199eb05)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header_parse_protocol
  - net/ethernet/eth.c:eth_header_parse
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41663)
Location: include/linux/if_ether.h:22
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a5e101)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/ndisc.c (ffffffff81a74c74)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
```
```
In net/packet/af_packet.c (ffffffff81aa32fc)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81aa9c48)
Location: include/linux/if_ether.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
</ul>

## Differences
