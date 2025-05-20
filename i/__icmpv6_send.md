# Function: <code>__icmpv6_send</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f29ba)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2d9ed)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ebdb)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b40bca)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81b4eba6)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/udp.c (ffffffff81b6986a)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81b74927)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/exthdrs.c (ffffffff81b7c334)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b88382)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b91de3)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
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
In security/smack/smack_lsm.c (ffffffff814f990d)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1bab4)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b983)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e462)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81b3c9d6)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/udp.c (ffffffff81b57b3b)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81b63447)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/exthdrs.c (ffffffff81b6ae21)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b770b2)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b81037)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
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
In security/smack/smack_lsm.c (ffffffff815544ed)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81be02e5)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81bf1a63)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81bf476a)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81c03315)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/udp.c (ffffffff81c1f145)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81c2af06)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/exthdrs.c (ffffffff81c32c81)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81c41b52)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/ip6_icmp.c (ffffffff81c4d057)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
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
In security/smack/smack_lsm.c (ffffffff815f0272)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77290)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a495)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d502)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81d9d2a0)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/udp.c (ffffffff81dbb9cd)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81dc879d)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/exthdrs.c (ffffffff81dd046e)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81de03f2)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/ip6_icmp.c (ffffffff81ded508)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
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
In security/smack/smack_lsm.c (ffffffff816a0622)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81f43b10)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81f58425)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b5ae)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81f6c1d0)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/udp.c (ffffffff81f8bad2)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81f99545)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/exthdrs.c (ffffffff81fa17fe)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81fb2782)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/ip6_icmp.c (ffffffff81fc1328)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
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
In security/smack/smack_lsm.c (ffffffff816d8f7e)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa32ec)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81fb7fa6)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb36f)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81fcc2d5)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/udp.c (ffffffff81fec20d)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81ff9f15)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/exthdrs.c (ffffffff82002070)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff82012e92)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/ip6_icmp.c (ffffffff820222a8)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
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
In security/smack/smack_lsm.c (ffffffff817159a5)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff82070972)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff820855bb)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8208877f)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff82099ab8)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/udp.c (ffffffff820b9e03)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff820c7b85)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/exthdrs.c (ffffffff820d0e70)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff820e1ff2)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/ip6_icmp.c (ffffffff820f13c8)
Location: include/linux/icmpv6.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
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
