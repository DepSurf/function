# Function: <code>__skb_pull</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff815f25be)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f6843)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81706a83)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff81716f75)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffffffff817258db)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ethernet/eth.c (ffffffff817401c3)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff81758a58)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff8175f0ae)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff81761ab8)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff8176cc58)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff81774645)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81782ab4)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81783251)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8178ae7f)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81794a2f)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff817a51b6)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff817b00af)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff8181715b)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/datagram.c (ffffffff817f4ace)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
```
```
In net/ipv6/ip6_offload.c (ffffffff81800bd7)
Location: include/linux/skbuff.h:1823
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff8181715b-ffffffff81817161: __skb_pull.part.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff81651e1a)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff816569c3)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81770af3)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_pull
```
```
In net/core/dev.c (ffffffff81783e5e)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffffffff8178f37b)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff8179d72b)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ethernet/eth.c (ffffffff817acf63)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff817c4e08)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff817cb31e)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cddc3)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff817dffd8)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff817e1512)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efc51)
Location: include/linux/skbuff.h:1924
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff817f07f0)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff817f8714)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff818023d1)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81812a8a)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff8181cfdf)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81834f2c)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/datagram.c (ffffffff81863e10)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6_offload.c (ffffffff8187283e)
Location: include/linux/skbuff.h:1924
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
**Symbols:**

```
ffffffff81890b5a-ffffffff81890b60: __skb_pull.part.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81197695)
Location: include/linux/skbuff.h:1939
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff816846a3)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8179ef31)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_pull
```
```
In net/core/dev.c (ffffffff817b146e)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffffffff817bcc2b)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff817cc18b)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:__bpf_redirect
```
```
In net/ethernet/eth.c (ffffffff817dc5b3)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff817f4928)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff817faf7e)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fdb23)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff818103a9)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff818119e2)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81820661)
Location: include/linux/skbuff.h:1939
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81821566)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff818295c3)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8183335f)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81843f93)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff8184e89f)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81866a62)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/datagram.c (ffffffff818964c0)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6e45)
Location: include/linux/skbuff.h:1939
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
**Symbols:**

```
ffffffff818c5174-ffffffff818c517a: __skb_pull.part.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8119f32c)
Location: include/linux/skbuff.h:1978
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81699b5c)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff817bc691)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_pull
```
```
In net/core/dev.c (ffffffff817d190e)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffffffff817db2f2)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff817eb0ad)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:__bpf_redirect
```
```
In net/ethernet/eth.c (ffffffff817fbc73)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff81814d78)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff8181b3bb)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181df64)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff818302ff)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff81831d51)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840b71)
Location: include/linux/skbuff.h:1978
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81842246)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8184a5d2)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff818546c2)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8186580e)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff8187236f)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff8188b1d5)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/datagram.c (ffffffff818bca46)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd8b0)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
**Symbols:**

```
ffffffff8188b8da-ffffffff8188b8e0: __skb_pull.part.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811b255b)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81704308)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81836d61)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_pull
```
```
In net/core/dev.c (ffffffff8184bb5e)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:do_xdp_generic
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffffffff81855ab2)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81866efd)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:__bpf_redirect
```
```
In net/ethernet/eth.c (ffffffff81879633)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff81893f41)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff8189a2eb)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189ce74)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff818aea3a)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff818b108a)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c02e1)
Location: include/linux/skbuff.h:2065
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff818c1b24)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff818ca276)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff818d4562)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff818e595e)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2d4f)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff8190c3f5)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/datagram.c (ffffffff8193fb66)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6_offload.c (ffffffff819526a0)
Location: include/linux/skbuff.h:2065
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
**Symbols:**

```
ffffffff8190cba3-ffffffff8190cba9: __skb_pull.part.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811d1bdd)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817429fb)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81880e91)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_pull
```
```
In net/core/dev.c (ffffffff81895ede)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffffffff818a15de)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff818b5dca)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/timestamping.c (ffffffff818c6dec)
Location: include/linux/skbuff.h:2076
Inline: True
```
```
In net/ethernet/eth.c (ffffffff818cb013)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff818e81c1)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff818ee7bf)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f1391)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff81904115)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff8190672e)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81915e32)
Location: include/linux/skbuff.h:2076
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819177f6)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819205d4)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8192ac3f)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8193c22f)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff819496c5)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff8196386f)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/datagram.c (ffffffff819989d7)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6_offload.c (ffffffff819abc4a)
Location: include/linux/skbuff.h:2076
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81960060-ffffffff81960066: __skb_pull.part.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811e193b)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81767275)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff818a1d31)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_pull
  - net/core/skbuff.c:skb_pull
```
```
In net/core/dev.c (ffffffff818b7ca4)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffffffff818c3918)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff818dae64)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/timestamping.c (ffffffff818eff39)
Location: include/linux/skbuff.h:2154
Inline: True
```
```
In net/ethernet/eth.c (ffffffff818f61c0)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff819158a9)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff8191bf6f)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191eeee)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff819332c1)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8193491c)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193f71e)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819445df)
Location: include/linux/skbuff.h:2154
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81945f30)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff8194d1a8)
Location: include/linux/skbuff.h:2154
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff8194f40a)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8195a3c3)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8196bf33)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b389)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff8199882f)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/udp.c (ffffffff819bb498)
Location: include/linux/skbuff.h:2154
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff819cf334)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6_offload.c (ffffffff819e2829)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81994e40-ffffffff81994e46: __skb_pull.part.46 (STB_LOCAL)
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
In kernel/bpf/cgroup.c (ffffffff811f8a3b)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a49de)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff818ec99c)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_pull
  - net/core/skbuff.c:skb_pull
```
```
In net/core/dev.c (ffffffff81903b21)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffffffff8190face)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81927c14)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/timestamping.c (ffffffff8194182b)
Location: include/linux/skbuff.h:2242
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81955801)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff81977e28)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff8197e28f)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff8198182f)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff81996bb4)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819985f0)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a3aec)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a8bcf)
Location: include/linux/skbuff.h:2242
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819aa560)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819b19c2)
Location: include/linux/skbuff.h:2242
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff819b3c40)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819bef41)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff819d2c7f)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e48c4)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff819f5197)
Location: include/linux/skbuff.h:2242
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819f5e5b)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a04689)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/udp.c (ffffffff81a2a0f5)
Location: include/linux/skbuff.h:2242
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a3e083)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6_offload.c (ffffffff81a514cb)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
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
In kernel/bpf/cgroup.c (ffffffff81205a6b)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c8ade)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8191ead1)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_pull
  - net/core/skbuff.c:skb_pull
```
```
In net/core/dev.c (ffffffff819368e2)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffffffff8194213e)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81959fb4)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/timestamping.c (ffffffff8197673b)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ethernet/eth.c (ffffffff8198bca1)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff819ae798)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819b4c3f)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b806f)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff819cd734)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819cf09c)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819da7ee)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819df86f)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1230)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819e873f)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff819ea970)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819f5b81)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81a097ee)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b88a)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2be47)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2cadb)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b279)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/udp.c (ffffffff81a60c36)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a74cf3)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6_offload.c (ffffffff81a880eb)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
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
In kernel/bpf/cgroup.c (ffffffff8122cc5a)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81893158)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff819f1364)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive_list
  - net/core/skbuff.c:skb_gro_receive_list
```
```
In net/core/dev.c (ffffffff81a021cd)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/dev.c:napi_frags_skb
  - net/core/dev.c:napi_frags_skb
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffffffff81a1209e)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a2da19)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/timestamping.c (ffffffff81a4b49d)
Location: include/linux/skbuff.h:2279
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81a63951)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff81a98638)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff81a9ee2a)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa2991)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff81ab98c7)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81abc0d8)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac799d)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81accd11)
Location: include/linux/skbuff.h:2279
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81ace870)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81ad668d)
Location: include/linux/skbuff.h:2279
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81ad858b)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ae4071)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81af9f5e)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c974)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1dc58)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1f6af)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
```
```
In net/ipv6/ip6_output.c (ffffffff81b30843)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/udp.c (ffffffff81b59acd)
Location: include/linux/skbuff.h:2279
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81b6ef43)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78d0d)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81b835bb)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
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
In kernel/bpf/cgroup.c (ffffffff812350f0)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a1448)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff819f12f4)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive_list
  - net/core/skbuff.c:skb_gro_receive_list
```
```
In net/core/dev.c (ffffffff81a029cd)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/core/dev.c:napi_frags_skb
  - net/core/dev.c:napi_frags_skb
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffffffff81a1243a)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a2d42c)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/timestamping.c (ffffffff81a510bd)
Location: include/linux/skbuff.h:2300
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81a6bab1)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff81aa2588)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff81aa8d6a)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aacca1)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff81ac4cbd)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ac7812)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad3376)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8d11)
Location: include/linux/skbuff.h:2300
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81ada890)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81ae2c69)
Location: include/linux/skbuff.h:2300
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81ae4a2e)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81af0fa1)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81b076be)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1aca4)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c528)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2df7f)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f473)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/udp.c (ffffffff81b6812d)
Location: include/linux/skbuff.h:2300
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81b7da73)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87c8d)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92c7b)
Location: include/linux/skbuff.h:2300
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
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
In kernel/bpf/cgroup.c (ffffffff81239867)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81883ad8)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff819d659d)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive_list
  - net/core/skbuff.c:skb_gro_receive_list
```
```
In net/core/dev.c (ffffffff819f2680)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffffffff819f906a)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a1544b)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/timestamping.c (ffffffff81a3693d)
Location: include/linux/skbuff.h:2316
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81a54241)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff81a8d288)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff81a93e8a)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a97ef1)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff81aafda9)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ab2822)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abe406)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3d80)
Location: include/linux/skbuff.h:2316
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac58c0)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81acdb8d)
Location: include/linux/skbuff.h:2316
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81acfc83)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81adc761)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81af2e5e)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b08961)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a188)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c086)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d313)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/udp.c (ffffffff81b5643d)
Location: include/linux/skbuff.h:2316
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81b6c663)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b7694a)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81dcb)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
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
In kernel/bpf/devmap.c (ffffffff8126cc4d)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
```
```
In kernel/bpf/cpumap.c (ffffffff8126e644)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In kernel/bpf/cgroup.c (ffffffff8127404c)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81915478)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81a86bed)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive_list
  - net/core/skbuff.c:skb_pull_rcsum
```
```
In net/core/dev.c (ffffffff81aa4550)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffffffff81aaac4a)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81ac646b)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/timestamping.c (ffffffff81aec68d)
Location: include/linux/skbuff.h:2345
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81b0cf53)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff81b48458)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff81b4f2ca)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b53381)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff81b6cb84)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f59e)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7bf24)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b82410)
Location: include/linux/skbuff.h:2345
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81b840d0)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81b8c55d)
Location: include/linux/skbuff.h:2345
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e6a3)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81b9bb41)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81bb336e)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb817)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde7a8)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0a12)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm4_prepare_output
```
```
In net/ipv6/ip6_output.c (ffffffff81bf34cb)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/udp.c (ffffffff81c1caad)
Location: include/linux/skbuff.h:2345
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81c34537)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c41380)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4de44)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
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
In kernel/bpf/devmap.c (ffffffff812bb94f)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
```
```
In kernel/bpf/cpumap.c (ffffffff812bd552)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In kernel/bpf/cgroup.c (ffffffff812c2266)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6ab2d)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81bfc338)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_pull_data
```
```
In net/core/dev.c (ffffffff81c19e89)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81c23b9a)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81c423db)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro.c (ffffffff81c54518)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:skb_gro_receive
  - net/core/gro.c:skb_mac_gso_segment
```
```
In net/core/timestamping.c (ffffffff81c6efd8)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/core/timestamping.c:skb_defer_rx_timestamp
```
```
In net/ethernet/eth.c (ffffffff81c93889)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff81cd57d0)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff81cdcc4e)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdfa7b)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff81cfc041)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81cfec5e)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0be08)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d12910)
Location: include/linux/skbuff.h:2704
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81d148a8)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81d1cbc6)
Location: include/linux/skbuff.h:2704
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81d1fe42)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81d2d913)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81d46b8a)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d612ca)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81d755f4)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81d7780a)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c0cf)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/udp.c (ffffffff81db9376)
Location: include/linux/skbuff.h:2704
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81dd1e35)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddfaff)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee547)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
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
In kernel/bpf/devmap.c (ffffffff8131ecdf)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
```
```
In kernel/bpf/cpumap.c (ffffffff813209f2)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In kernel/bpf/cgroup.c (ffffffff81326a66)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfd970)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81dab208)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_pull_data
```
```
In net/core/dev.c (ffffffff81dcaf09)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81dd610a)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81df856b)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro.c (ffffffff81e09c68)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:skb_gro_receive
  - net/core/gro.c:skb_mac_gso_segment
```
```
In net/core/timestamping.c (ffffffff81e26d68)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/core/timestamping.c:skb_defer_rx_timestamp
```
```
In net/ethernet/eth.c (ffffffff81e4efb9)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff81e95c30)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff81e9d6be)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9fe1b)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff81ec0bc1)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3c4e)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed0d2a)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed8750)
Location: include/linux/skbuff.h:2601
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81eda9e8)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81ee3ca6)
Location: include/linux/skbuff.h:2601
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7042)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ef5813)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81f103da)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2bbca)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41c04)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81f4409a)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a08f)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/udp.c (ffffffff81f893c6)
Location: include/linux/skbuff.h:2601
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81fa3285)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1def)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc2169)
Location: include/linux/skbuff.h:2601
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
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
In kernel/bpf/devmap.c (ffffffff8134eaff)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
```
```
In kernel/bpf/cpumap.c (ffffffff813508a2)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In kernel/bpf/cgroup.c (ffffffff81356db0)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/virtio_net.c (ffffffff81c50d98)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:xmit_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c6317f)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81e1ad08)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_pull_data
```
```
In net/core/dev.c (ffffffff81e3ba93)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81e46f4a)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81e6a4db)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro.c (ffffffff81e7c42e)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/gso.c (ffffffff81e7d505)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/core/gso.c:skb_mac_gso_segment
```
```
In net/core/timestamping.c (ffffffff81e9c308)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/core/timestamping.c:skb_defer_rx_timestamp
```
```
In net/ethernet/eth.c (ffffffff81eaa659)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff81ef4470)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff81efbe0f)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efe66b)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff81f1f131)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f304eb)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f37860)
Location: include/linux/skbuff.h:2644
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81f39ad0)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81f43516)
Location: include/linux/skbuff.h:2644
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81f468e2)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81f551c6)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81f700ca)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b60a)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa14a0)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa38b1)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81fb9d40)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/udp.c (ffffffff81fe87f6)
Location: include/linux/skbuff.h:2644
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff82003b3b)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff8200d00a)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffffffff820124fd)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff820230e9)
Location: include/linux/skbuff.h:2644
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
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
In kernel/bpf/devmap.c (ffffffff81375ffc)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
```
```
In kernel/bpf/cpumap.c (ffffffff81377cd2)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In kernel/bpf/cgroup.c (ffffffff8137f8e0)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/virtio_net.c (ffffffff81d06ddf)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:xmit_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d19b9f)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81ed83a8)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_pull_data
```
```
In net/core/dev.c (ffffffff81ef9fd3)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81f05c0a)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81f2946b)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro.c (ffffffff81f3c77e)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/gso.c (ffffffff81f3e485)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/core/gso.c:skb_mac_gso_segment
```
```
In net/core/timestamping.c (ffffffff81f5ea98)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/core/timestamping.c:skb_defer_rx_timestamp
```
```
In net/ethernet/eth.c (ffffffff81f6d109)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff81fb83f0)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff81fbfd4f)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc288e)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff81fe37df)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff63f7)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffd930)
Location: include/linux/skbuff.h:2651
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81fffbc0)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff82009476)
Location: include/linux/skbuff.h:2651
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff8200ca22)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8201b436)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff820367fa)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff82052d14)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:__xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff8206e7c0)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff82070be1)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff8208720d)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/udp.c (ffffffff820b7346)
Location: include/linux/skbuff.h:2651
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff820d28eb)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6mr.c (ffffffff820dbfda)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e0f1f)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:__xfrm6_udp_encap_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff820f20d0)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
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
In kernel/bpf/cgroup.c (ffff80001028e9d0)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e6eec)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a02f24)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffff800010bb92a4)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_pull
  - net/core/skbuff.c:skb_pull
```
```
In net/core/dev.c (ffff800010bd4fa0)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffff800010be1b5c)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffff800010bfbb80)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/timestamping.c (ffff800010c1cd38)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ethernet/eth.c (ffff800010c36d24)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffff800010c5ecd8)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffff800010c65380)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffff800010c69420)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffff800010c802e4)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffff800010c8200c)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8dbb4)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c933ec)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffff800010c95268)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffff800010c9db94)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/udp_offload.c (ffff800010ca0510)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffff800010cab7f8)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffff800010cc2b94)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd7b48)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffff800010cea88c)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffff800010ceb754)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffff800010cfc370)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/udp.c (ffff800010d26834)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv6/datagram.c (ffff800010d3d6d8)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6_offload.c (ffff800010d54c64)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
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
In kernel/bpf/cgroup.c (c04bdc18)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acbdc4)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
```
```
In drivers/net/ppp/ppp_generic.c (c0addd34)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (c0cd5d60)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_pull
  - net/core/skbuff.c:skb_pull
```
```
In net/core/dev.c (c0cef468)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (c0cfcb50)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (c0d16634)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/timestamping.c (c0d34c10)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ethernet/eth.c (c0d49674)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (c0d6e41c)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (c0d75000)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (c0d78618)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (c0d8f3dc)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (c0d90bb8)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (c0d9c8d8)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (c0da1be4)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/tcp_offload.c (c0da3984)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (c0dab680)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/udp_offload.c (c0dad754)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (c0db86dc)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (c0dce3bc)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (c0de1648)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (c0df28f8)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/xfrm/xfrm_output.c (c0df3644)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (c0e037a8)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/udp.c (c0e29ec0)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv6/datagram.c (c0e408c4)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6_offload.c (c0e55290)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
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
In kernel/bpf/cgroup.c (c00000000033b2f8)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa8e50)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (c000000000c91844)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_pull
```
```
In net/core/dev.c (c000000000cb4320)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (c000000000cc2ec8)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (c000000000ce6948)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/timestamping.c (c000000000d0dd20)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ethernet/eth.c (c000000000d2ed20)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (c000000000d617ac)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (c000000000d69940)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (c000000000d6dff8)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (c000000000d8ae20)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (c000000000d8ce88)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9b48c)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (c000000000da3630)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/tcp_offload.c (c000000000da6214)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (c000000000daf504)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/udp_offload.c (c000000000db2cc4)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (c000000000dc2180)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (c000000000ddea40)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (c000000000df7af0)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (c000000000e0e4e0)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/xfrm/xfrm_output.c (c000000000e0f5f8)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (c000000000e23ea0)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/udp.c (c000000000e56534)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv6/datagram.c (c000000000e71a7c)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6_offload.c (c000000000e8d868)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
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
In kernel/bpf/cgroup.c (ffffffe0001c1bd8)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062d380)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffe000748870)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_pull
  - net/core/skbuff.c:skb_pull
```
```
In net/core/dev.c (ffffffe00075eb48)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffffffe000768904)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffe00077e1c4)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/timestamping.c (ffffffe000796aa2)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ethernet/eth.c (ffffffe0007a86c8)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffe0007c72ac)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffe0007ccbb0)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf314)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffe0007e2284)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffe0007e3ae6)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee11a)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f292c)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f4490)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffe0007fac76)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffe0007fcbbe)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffe000806474)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffe000817fbe)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffe0008281ae)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffe00083846e)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffe0008390bc)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffe000846c42)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/udp.c (ffffffe000866fd2)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv6/datagram.c (ffffffe000879e34)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c580)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
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
In kernel/bpf/cgroup.c (ffffffff811fe08b)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178d5be)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff818bead1)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_pull
  - net/core/skbuff.c:skb_pull
```
```
In net/core/dev.c (ffffffff818d68b2)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffffffff818e210e)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff818f9f84)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
```
In net/ethernet/eth.c (ffffffff8192bb11)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff8194e608)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81954aaf)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff81957edf)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff8196d5a4)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8196ef0c)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197a65e)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197f6df)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819810a0)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819885af)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff8198a7e0)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81995921)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff819a958e)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff819baf1a)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb4d7)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc16b)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff819da909)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/udp.c (ffffffff81a002c6)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a14383)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6_offload.c (ffffffff81a2777b)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
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
In kernel/bpf/cgroup.c (ffffffff811f0ddb)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/vxlan.c (ffffffff817740d4)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8177638e)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81878a11)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_pull
  - net/core/skbuff.c:skb_pull
```
```
In net/core/dev.c (ffffffff818906f2)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffffffff8189bf4e)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff818b3db4)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
```
In net/ethernet/eth.c (ffffffff818e58c1)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff819080f8)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8190e59f)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff819119cf)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff81927094)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819289fc)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193411e)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8193919f)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff8193ab60)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff8194206f)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff819442a0)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8194f3e1)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8196304e)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977d0a)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff819882c7)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81988f5b)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff819976c9)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/udp.c (ffffffff819bd086)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff819d1143)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6_offload.c (ffffffff819e453b)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
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
In kernel/bpf/cgroup.c (ffffffff811fbe5b)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bd95e)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8190fad1)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_pull
  - net/core/skbuff.c:skb_pull
```
```
In net/core/dev.c (ffffffff819278e2)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffffffff8193313e)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff8194afb4)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/timestamping.c (ffffffff8196773b)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ethernet/eth.c (ffffffff8197cca1)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff81999724)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff819b8dd8)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819bf27f)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c26af)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff819d7d74)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819d96dc)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e4e2e)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e9eaf)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819eb870)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819f2d7f)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff819f4fb0)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81a001c1)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81a13e2e)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a2599a)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35f57)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a36beb)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a45389)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/udp.c (ffffffff81a6ad46)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a7ee03)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9332b)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
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
In kernel/bpf/cgroup.c (ffffffff8120aa5c)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d818e)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81930c01)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_pull
  - net/core/skbuff.c:skb_pull
```
```
In net/core/dev.c (ffffffff81948f82)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/neighbour.c (ffffffff81954a6e)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff8196c8c4)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/timestamping.c (ffffffff819899cb)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ethernet/eth.c (ffffffff8199f211)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_input.c (ffffffff819c2660)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819c8bff)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cc0af)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff819e19ad)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819e333c)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ee18e)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f3cdf)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5720)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819fd28f)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff819ff1b6)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81a0a211)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81a1e81e)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30e2a)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81a418c7)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a4257b)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a51059)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/udp.c (ffffffff81a77356)
Location: include/linux/skbuff.h:2256
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a8b6c3)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f47b)
Location: include/linux/skbuff.h:2256
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
</details>
</li>
</ul>

## Differences
