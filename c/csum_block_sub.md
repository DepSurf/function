# Function: <code>csum_block_sub</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81775485)
Location: include/net/checksum.h:103
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffff81771f37)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff8177fe84)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8179dadf)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_output.c (ffffffff817e23d0)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81835b2b)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff8185517e)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
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
In net/core/skbuff.c (ffffffff8179f04a)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff817ad553)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff817cc53f)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_output.c (ffffffff81812a10)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff8186765b)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff81886eee)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818950a8)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a4594)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/skbuff.c (ffffffff817bc781)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff817cc103)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff817eb104)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_output.c (ffffffff81832dde)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff8188bd89)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff818ad399)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818bb3ce)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818cac61)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/skbuff.c (ffffffff81836e51)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff818457c9)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81866f54)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/tcp_output.c (ffffffff818b225f)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff8190d074)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff8192ffa9)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193e3e4)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e3bb)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff8194f98e)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff81880f71)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff8188eda9)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818b5e58)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81964444)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff81988c2d)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8199731b)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7352)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff819a8961)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff818a1e05)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff818afe49)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818d730c)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81999ccd)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff819bf5c7)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cdbfa)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819ddea9)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff819df495)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff818eca2d)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff818fbc9f)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81924dfe)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81a05c37)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a2e233)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c205)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4c9fa)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e00e)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff8191eb59)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff8192e26f)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8195722e)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c79f)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a64da3)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a72e85)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a835ca)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a84c38)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff819f142c)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff81a023fc)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a2f8a9)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81b31e65)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81b5d7c7)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d35b)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e3e5)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81b7fcea)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff819f13c3)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff81a02bfc)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a31bb9)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81b40a65)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81b6bfb7)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b7be09)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d3fc)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f01a)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff819d6665)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff819e720f)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81a18a25)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e2fb)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81b5a2d8)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a8ee)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c2a5)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81b7e050)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff81a86cb5)
Location: include/net/checksum.h:104
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff81a97bbf)
Location: include/net/checksum.h:104
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81ac9f15)
Location: include/net/checksum.h:104
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81bf45f1)
Location: include/net/checksum.h:104
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81c21953)
Location: include/net/checksum.h:104
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81c3274e)
Location: include/net/checksum.h:104
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c471a5)
Location: include/net/checksum.h:104
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81c48ec0)
Location: include/net/checksum.h:104
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4c073)
Location: include/net/checksum.h:104
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
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
In net/core/skbuff.c (ffffffff81bfe765)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/filter.c (ffffffff81c483c0)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
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
In net/core/skbuff.c (ffffffff81dad165)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/filter.c (ffffffff81dfd350)
Location: include/net/checksum.h:106
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
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
In net/core/skbuff.c (ffffffff81e1d05f)
Location: include/net/checksum.h:108
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/filter.c (ffffffff81e73261)
Location: include/net/checksum.h:108
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
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
In net/core/skbuff.c (ffffffff81eda74f)
Location: include/net/checksum.h:108
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/filter.c (ffffffff81f329e1)
Location: include/net/checksum.h:108
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
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
In net/core/skbuff.c (ffff800010bb934c)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffff800010bcd71c)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffff800010c009bc)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffff800010cfdac8)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffff800010d2ac78)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffff800010d3b9b4)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f3cc)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffff800010d50d24)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (c0cd5dfc)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (c0ce7974)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (c0d126a8)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (c0e052f0)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (c0e2ecb0)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (c0e3e120)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (c0e5011c)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (c0e51878)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (c000000000c918e8)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (c000000000ca750c)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (c000000000ce3b04)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (c000000000e25bbc)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (c000000000e5bf3c)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (c000000000e6f234)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86c44)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (c000000000e88b4c)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffe0007488ec)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffe000756e5a)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffe00077a6dc)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffe000847f52)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffe00086b2d0)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffe0008782a6)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000887ece)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffe00088905e)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff818beb59)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff818ce26f)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818f71fe)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff819dbe2f)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a04433)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a12515)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a22c5a)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a242c8)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In drivers/net/vxlan.c (ffffffff81772efe)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/core/skbuff.c (ffffffff81878a99)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff8188838f)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818b102e)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967f8a)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81998bef)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff819c11f3)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cf2d5)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dfa1a)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff819e1088)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff8190fb59)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff8191f26f)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8194822e)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81a468af)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a6eeb3)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a7cf95)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d6da)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ed48)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/core/skbuff.c (ffffffff81930c89)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff81940fcf)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81969b3e)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv6/ip6_input.c (ffffffff81a525df)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a7b4e3)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a897e5)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a3ca)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bab8)
Location: include/net/checksum.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
</details>
</li>
</ul>

## Differences
