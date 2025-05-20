# Function: <code>skb_header_cloned</code>

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
In drivers/net/virtio_net.c (ffffffff815f25ee)
Location: include/linux/skbuff.h:1243
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f7f93)
Location: include/linux/skbuff.h:1243
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81708ef6)
Location: include/linux/skbuff.h:1243
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81718d6d)
Location: include/linux/skbuff.h:1243
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff8173242a)
Location: include/linux/skbuff.h:1243
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (ffffffff81738b14)
Location: include/linux/skbuff.h:1243
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/netfilter/core.c (ffffffff81751019)
Location: include/linux/skbuff.h:1243
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/8021q/vlan_core.c (ffffffff81809724)
Location: include/linux/skbuff.h:1243
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/virtio_net.c (ffffffff81651f2c)
Location: include/linux/skbuff.h:1334
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81658172)
Location: include/linux/skbuff.h:1334
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81770a21)
Location: include/linux/skbuff.h:1334
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81784f48)
Location: include/linux/skbuff.h:1334
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/netpoll.c (ffffffff817a4de8)
Location: include/linux/skbuff.h:1334
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/netfilter/core.c (ffffffff817bd045)
Location: include/linux/skbuff.h:1334
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8181278b)
Location: include/linux/skbuff.h:1334
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff8187b225)
Location: include/linux/skbuff.h:1334
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
In drivers/net/ppp/ppp_generic.c (ffffffff81685f02)
Location: include/linux/skbuff.h:1349
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff8179dacd)
Location: include/linux/skbuff.h:1349
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff817b2558)
Location: include/linux/skbuff.h:1349
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/netpoll.c (ffffffff817d3858)
Location: include/linux/skbuff.h:1349
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/netfilter/core.c (ffffffff817ec985)
Location: include/linux/skbuff.h:1349
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81843c8b)
Location: include/linux/skbuff.h:1349
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff818afae5)
Location: include/linux/skbuff.h:1349
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
In drivers/net/ppp/ppp_generic.c (ffffffff8169b345)
Location: include/linux/skbuff.h:1342
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff817bb99c)
Location: include/linux/skbuff.h:1342
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff817cfd73)
Location: include/linux/skbuff.h:1342
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/netpoll.c (ffffffff817f2c2d)
Location: include/linux/skbuff.h:1342
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/netfilter/core.c (ffffffff8180cda3)
Location: include/linux/skbuff.h:1342
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8186551d)
Location: include/linux/skbuff.h:1342
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818caed8)
Location: include/linux/skbuff.h:1342
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/8021q/vlan_core.c (ffffffff818d62ad)
Location: include/linux/skbuff.h:1342
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
In drivers/net/ppp/ppp_generic.c (ffffffff81705b45)
Location: include/linux/skbuff.h:1443
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81834a4c)
Location: include/linux/skbuff.h:1443
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818496c3)
Location: include/linux/skbuff.h:1443
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/netpoll.c (ffffffff8186e1f7)
Location: include/linux/skbuff.h:1443
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/netfilter/core.c (ffffffff8188bf83)
Location: include/linux/skbuff.h:1443
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e566d)
Location: include/linux/skbuff.h:1443
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e818)
Location: include/linux/skbuff.h:1443
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff8195be47)
Location: include/linux/skbuff.h:1443
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
In drivers/net/ppp/ppp_generic.c (ffffffff81744fe1)
Location: include/linux/skbuff.h:1454
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff8187f882)
Location: include/linux/skbuff.h:1454
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818936b5)
Location: include/linux/skbuff.h:1454
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff818b5f4c)
Location: include/linux/skbuff.h:1454
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
```
```
In net/core/netpoll.c (ffffffff818bf12d)
Location: include/linux/skbuff.h:1454
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/netfilter/core.c (ffffffff818dfc45)
Location: include/linux/skbuff.h:1454
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193bf10)
Location: include/linux/skbuff.h:1454
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7afb)
Location: include/linux/skbuff.h:1454
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff819b5691)
Location: include/linux/skbuff.h:1454
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
In drivers/net/ppp/ppp_generic.c (ffffffff817690d1)
Location: include/linux/skbuff.h:1523
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff8189fae4)
Location: include/linux/skbuff.h:1523
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818b40da)
Location: include/linux/skbuff.h:1523
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff818dafc1)
Location: include/linux/skbuff.h:1523
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
```
```
In net/core/netpoll.c (ffffffff818e7f63)
Location: include/linux/skbuff.h:1523
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/netfilter/core.c (ffffffff8190c7c8)
Location: include/linux/skbuff.h:1523
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196bc30)
Location: include/linux/skbuff.h:1523
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de64b)
Location: include/linux/skbuff.h:1523
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff819ec959)
Location: include/linux/skbuff.h:1523
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
In drivers/net/ppp/ppp_generic.c (ffffffff817a6ba9)
Location: include/linux/skbuff.h:1613
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff818ea2e8)
Location: include/linux/skbuff.h:1613
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff819009b0)
Location: include/linux/skbuff.h:1613
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81924a8a)
Location: include/linux/skbuff.h:1613
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (ffffffff819378c9)
Location: include/linux/skbuff.h:1613
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff819435fc)
Location: include/linux/skbuff.h:1613
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2976)
Location: include/linux/skbuff.h:1613
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4b16)
Location: include/linux/skbuff.h:1613
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4d1bf)
Location: include/linux/skbuff.h:1613
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff81a5bb11)
Location: include/linux/skbuff.h:1613
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
In drivers/net/ppp/ppp_generic.c (ffffffff817ca609)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff8191c47c)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81932ce0)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81956eba)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (ffffffff8196a789)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff819785d0)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a094e6)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b7c6)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83d8f)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff81a92708)
Location: include/linux/skbuff.h:1623
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
In drivers/net/ppp/ppp_generic.c (ffffffff81895659)
Location: include/linux/skbuff.h:1634
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff819f058e)
Location: include/linux/skbuff.h:1634
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81a04a04)
Location: include/linux/skbuff.h:1634
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81a2d410)
Location: include/linux/skbuff.h:1634
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/netpoll.c (ffffffff81a3de89)
Location: include/linux/skbuff.h:1634
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff81a4d4ec)
Location: include/linux/skbuff.h:1634
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8e07)
Location: include/linux/skbuff.h:1634
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d637)
Location: include/linux/skbuff.h:1634
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/ipv6/exthdrs.c (ffffffff81b6cb9d)
Location: include/linux/skbuff.h:1634
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7eb5f)
Location: include/linux/skbuff.h:1634
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff81b8dbb8)
Location: include/linux/skbuff.h:1634
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
In drivers/net/ppp/ppp_generic.c (ffffffff818a3d89)
Location: include/linux/skbuff.h:1655
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff819f02de)
Location: include/linux/skbuff.h:1655
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81a05784)
Location: include/linux/skbuff.h:1655
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81a2ecb0)
Location: include/linux/skbuff.h:1655
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/netpoll.c (ffffffff81a40ba9)
Location: include/linux/skbuff.h:1655
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff81a531a9)
Location: include/linux/skbuff.h:1655
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81a6f371)
Location: include/linux/skbuff.h:1655
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05bd7)
Location: include/linux/skbuff.h:1655
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2be57)
Location: include/linux/skbuff.h:1655
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/ipv6/exthdrs.c (ffffffff81b7b62b)
Location: include/linux/skbuff.h:1655
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8db6f)
Location: include/linux/skbuff.h:1655
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff81b9d887)
Location: include/linux/skbuff.h:1655
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
In drivers/net/ppp/ppp_generic.c (ffffffff81885a99)
Location: include/linux/skbuff.h:1671
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff819d4c1e)
Location: include/linux/skbuff.h:1671
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff819ee114)
Location: include/linux/skbuff.h:1671
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81a1630f)
Location: include/linux/skbuff.h:1671
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/netpoll.c (ffffffff81a25869)
Location: include/linux/skbuff.h:1671
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff81a389dc)
Location: include/linux/skbuff.h:1671
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81a57c50)
Location: include/linux/skbuff.h:1671
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af1454)
Location: include/linux/skbuff.h:1671
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19ac7)
Location: include/linux/skbuff.h:1671
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a0ee)
Location: include/linux/skbuff.h:1671
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7ca3f)
Location: include/linux/skbuff.h:1671
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff81b8c9b0)
Location: include/linux/skbuff.h:1671
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
In drivers/net/ppp/ppp_generic.c (ffffffff8191743b)
Location: include/linux/skbuff.h:1700
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81a849ae)
Location: include/linux/skbuff.h:1700
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81a9f3b4)
Location: include/linux/skbuff.h:1700
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81ac726f)
Location: include/linux/skbuff.h:1700
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/netpoll.c (ffffffff81ada5a9)
Location: include/linux/skbuff.h:1700
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff81aee8bc)
Location: include/linux/skbuff.h:1700
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81b10bf0)
Location: include/linux/skbuff.h:1700
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1964)
Location: include/linux/skbuff.h:1700
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/xfrm/xfrm_input.c (ffffffff81bddd97)
Location: include/linux/skbuff.h:1700
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/ipv6/exthdrs.c (ffffffff81c31f4e)
Location: include/linux/skbuff.h:1700
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47b6a)
Location: include/linux/skbuff.h:1700
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4c16f)
Location: include/linux/skbuff.h:1700
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/8021q/vlan_core.c (ffffffff81c58d70)
Location: include/linux/skbuff.h:1700
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
In drivers/net/ppp/ppp_generic.c (ffffffff81a6b852)
Location: include/linux/skbuff.h:2049
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81bfa9cf)
Location: include/linux/skbuff.h:2049
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81c1216d)
Location: include/linux/skbuff.h:2049
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81c42a73)
Location: include/linux/skbuff.h:2049
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/netpoll.c (ffffffff81c5bc70)
Location: include/linux/skbuff.h:2049
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81c7181c)
Location: include/linux/skbuff.h:2049
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81c97d94)
Location: include/linux/skbuff.h:2049
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d4500f)
Location: include/linux/skbuff.h:2049
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/xfrm/xfrm_input.c (ffffffff81d74f27)
Location: include/linux/skbuff.h:2049
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/skbuff.h:2049
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6fc6)
Location: include/linux/skbuff.h:2049
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81dec19b)
Location: include/linux/skbuff.h:2049
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee863)
Location: include/linux/skbuff.h:2049
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff81dfa41d)
Location: include/linux/skbuff.h:2049
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
In drivers/net/ppp/ppp_generic.c (ffffffff81bfe752)
Location: include/linux/skbuff.h:1907
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81da985f)
Location: include/linux/skbuff.h:1907
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81dc253d)
Location: include/linux/skbuff.h:1907
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81df7a63)
Location: include/linux/skbuff.h:1907
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/netpoll.c (ffffffff81e120c0)
Location: include/linux/skbuff.h:1907
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81e2990c)
Location: include/linux/skbuff.h:1907
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81e53d34)
Location: include/linux/skbuff.h:1907
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0e49f)
Location: include/linux/skbuff.h:1907
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42167)
Location: include/linux/skbuff.h:1907
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/skbuff.h:1907
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9e56)
Location: include/linux/skbuff.h:1907
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfdeb)
Location: include/linux/skbuff.h:1907
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc1e86)
Location: include/linux/skbuff.h:1907
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/8021q/vlan_core.c (ffffffff81fceb3e)
Location: include/linux/skbuff.h:1907
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
In drivers/net/virtio_net.c (ffffffff81c50dc9)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:xmit_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c63d8d)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81e1835f)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81e2eab0)
Location: include/linux/skbuff.h:1943
Inline: True
```
```
In net/core/filter.c (ffffffff81e6976d)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/gso.c (ffffffff81e7d7bd)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/gso.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff81e858e0)
Location: include/linux/skbuff.h:1943
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81e9ef4c)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81eaf5b4)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6e14f)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa194f)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a589)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020dc3)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff82022e06)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/8021q/vlan_core.c (ffffffff8204a4f4)
Location: include/linux/skbuff.h:1943
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
In drivers/net/virtio_net.c (ffffffff81d06e10)
Location: include/linux/skbuff.h:1950
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:xmit_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1a7ad)
Location: include/linux/skbuff.h:1950
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81ed57ff)
Location: include/linux/skbuff.h:1950
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81eed430)
Location: include/linux/skbuff.h:1950
Inline: True
```
```
In net/core/filter.c (ffffffff81f28d4d)
Location: include/linux/skbuff.h:1950
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/gso.c (ffffffff81f3e73a)
Location: include/linux/skbuff.h:1950
Inline: True
Inline callers:
  - net/core/gso.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff81f47810)
Location: include/linux/skbuff.h:1950
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81f616bc)
Location: include/linux/skbuff.h:1950
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81f72034)
Location: include/linux/skbuff.h:1950
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8203485f)
Location: include/linux/skbuff.h:1950
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/xfrm/xfrm_input.c (ffffffff8206ec6f)
Location: include/linux/skbuff.h:1950
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e9546)
Location: include/linux/skbuff.h:1950
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820efef0)
Location: include/linux/skbuff.h:1950
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_offload.c (ffffffff820f1f26)
Location: include/linux/skbuff.h:1950
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/8021q/vlan_core.c (ffffffff8211c960)
Location: include/linux/skbuff.h:1950
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
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e5fd8)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a022c4)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffff800010bb6a74)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffff800010bd0cf0)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffff800010bf8680)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (ffff800010c10b34)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffff800010c1f28c)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc2870)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffff800010cea24c)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4fae8)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffff800010d604b4)
Location: include/linux/skbuff.h:1623
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
In drivers/net/ethernet/freescale/fec_main.c (c0ac9328)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (c0adf3cc)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (c0cd38d0)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (c0ceb930)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (c0d122c8)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (c0d28a74)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (c0d36e38)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_tunnel_core.c (c0dcdfa8)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In net/xfrm/xfrm_input.c (c0df2624)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/ipv6/seg6_iptunnel.c (c0e50844)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (c0e5ff70)
Location: include/linux/skbuff.h:1623
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
In drivers/net/ppp/ppp_generic.c (c000000000aaace0)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (c000000000c8e348)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (c000000000caed6c)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (c000000000cdf5a0)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (c000000000cfd728)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (c000000000d1111c)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dde090)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In net/xfrm/xfrm_input.c (c000000000e0dd2c)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e872b4)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (c000000000e9b478)
Location: include/linux/skbuff.h:1623
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
In drivers/net/ppp/ppp_generic.c (ffffffe00062ed04)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffe000746730)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffe00075b356)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffe00077a398)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (ffffffe00078d268)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffe000798a04)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817c28)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffe000837e7a)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000888200)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffe0008958ac)
Location: include/linux/skbuff.h:1623
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
In drivers/net/ppp/ppp_generic.c (ffffffff8178f0e9)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff818bc47c)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818d2ce0)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff818f6e8a)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (ffffffff8190a759)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff81918440)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a9286)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff819cae56)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a2341f)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff81a31d98)
Location: include/linux/skbuff.h:1623
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
In drivers/net/vxlan.c (ffffffff8176bd52)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_build_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81777eb9)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff818763bc)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff8188cb70)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff818b0cba)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (ffffffff818c47a9)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff818d21f0)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962d46)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967789)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
```
```
In net/xfrm/xfrm_input.c (ffffffff81987c46)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819e01df)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff819eef88)
Location: include/linux/skbuff.h:1623
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
In drivers/net/ppp/ppp_generic.c (ffffffff817bf489)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff8190d47c)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81923ce0)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81947eba)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (ffffffff8195b789)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff819695d0)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13b26)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81a358d6)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8de9f)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff81a9d948)
Location: include/linux/skbuff.h:1623
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
In drivers/net/ppp/ppp_generic.c (ffffffff817d9719)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff8192e5ac)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81945150)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff819697ca)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/netpoll.c (ffffffff8197d9a9)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff8198b9b0)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e506)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41241)
Location: include/linux/skbuff.h:1623
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9abe3)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/8021q/vlan_core.c (ffffffff81aa9b48)
Location: include/linux/skbuff.h:1623
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
</ul>

## Differences
