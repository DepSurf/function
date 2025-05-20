# Function: <code>wsum_negate</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfc3fa)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_pull_rcsum
```
```
In net/core/dev.c (ffffffff81c117cc)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81c46a6b)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/ethernet/eth.c (ffffffff81c936c6)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81d2099f)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81d47215)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d30a)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81dbe800)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81dcff40)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6501)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81de85a8)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81debd6e)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee31c)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81df986d)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/skbuff.c (ffffffff81dab2ca)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_pull_rcsum
```
```
In net/core/dev.c (ffffffff81dc1375)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81dfaf5c)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/ethernet/eth.c (ffffffff81e4edc9)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7bff)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81f10229)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b3b2)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81f8ece7)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81fa129a)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb91e7)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb551)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbf992)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc28a1)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81fcde95)
Location: include/net/checksum.h:191
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/skbuff.c (ffffffff81e1adca)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_pull_rcsum
```
```
In net/core/dev.c (ffffffff81e31195)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81e6c15d)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/ethernet/eth.c (ffffffff81eaa469)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81f47478)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81f6ff19)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb198)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81fef4a1)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff82001b8d)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019947)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff8201bc11)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020922)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff8202381f)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff820497c5)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In drivers/net/netkit.c (ffffffff81ce548f)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/netkit.c:netkit_xmit
```
```
In net/core/skbuff.c (ffffffff81ed846a)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_pull_rcsum
```
```
In net/core/dev.c (ffffffff81eed69b)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81f2ba4d)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/ethernet/eth.c (ffffffff81f6cf19)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8200d5b1)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/gre_offload.c (ffffffff82036649)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_input.c (ffffffff820885a8)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff820bcfe8)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff820d0990)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8917)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff820eabd1)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820efa52)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff820f2975)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff8211bb35)
Location: include/net/checksum.h:193
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
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
