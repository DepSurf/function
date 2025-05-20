# Function: <code>skb_reset_mac_header</code>

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
In drivers/net/tun.c (ffffffff815ef280)
Location: include/linux/skbuff.h:2039
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f6b7b)
Location: include/linux/skbuff.h:2039
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/dev.c (ffffffff81719775)
Location: include/linux/skbuff.h:2039
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8173952b)
Location: include/linux/skbuff.h:2039
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff8174018d)
Location: include/linux/skbuff.h:2039
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff817406e1)
Location: include/linux/skbuff.h:2039
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/ipv4/route.c (ffffffff81757293)
Location: include/linux/skbuff.h:2039
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffff8178aec7)
Location: include/linux/skbuff.h:2039
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff817a51d3)
Location: include/linux/skbuff.h:2039
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/route.c (ffffffff817d8d1e)
Location: include/linux/skbuff.h:2039
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/packet/af_packet.c (ffffffff81807e01)
Location: include/linux/skbuff.h:2039
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff8164ddc4)
Location: include/linux/skbuff.h:2169
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81656d24)
Location: include/linux/skbuff.h:2169
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/dev.c (ffffffff81783e1d)
Location: include/linux/skbuff.h:2169
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/netpoll.c (ffffffff817a57df)
Location: include/linux/skbuff.h:2169
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff817acf2d)
Location: include/linux/skbuff.h:2169
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff817ad4c1)
Location: include/linux/skbuff.h:2169
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/ipv4/route.c (ffffffff817c3533)
Location: include/linux/skbuff.h:2169
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffff817f8765)
Location: include/linux/skbuff.h:2169
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81812bb6)
Location: include/linux/skbuff.h:2169
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/route.c (ffffffff81842766)
Location: include/linux/skbuff.h:2169
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/packet/af_packet.c (ffffffff81879c6e)
Location: include/linux/skbuff.h:2169
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff8167faec)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81684a04)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/dev.c (ffffffff817b142d)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff817cb801)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (ffffffff817d424f)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff817dc57d)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff817dcb01)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/ipv4/route.c (ffffffff817f2b27)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffff81829616)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff818440e5)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/route.c (ffffffff818744e4)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/skbuff.h:2186
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818ae36b)
Location: include/linux/skbuff.h:2186
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff81694e23)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81699cb7)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/dev.c (ffffffff817d18cd)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff817eafe9)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (ffffffff817f3591)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff817fbc3d)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff817fc18f)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/ipv4/route.c (ffffffff8181341b)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffff8184a624)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81865a3c)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff818721fa)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/xfrm6_input.c (ffffffff818c5b93)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/skbuff.h:2235
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d4d72)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff816ff62b)
Location: include/linux/skbuff.h:2322
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81704463)
Location: include/linux/skbuff.h:2322
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/dev.c (ffffffff8184bb1d)
Location: include/linux/skbuff.h:2322
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff8186665d)
Location: include/linux/skbuff.h:2322
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (ffffffff8186e981)
Location: include/linux/skbuff.h:2322
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff818795fd)
Location: include/linux/skbuff.h:2322
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff81879b4f)
Location: include/linux/skbuff.h:2322
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/ipv4/route.c (ffffffff81892a6b)
Location: include/linux/skbuff.h:2322
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffff818ca2c9)
Location: include/linux/skbuff.h:2322
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff818e5ba1)
Location: include/linux/skbuff.h:2322
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2c1e)
Location: include/linux/skbuff.h:2322
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/xfrm6_input.c (ffffffff81948ec7)
Location: include/linux/skbuff.h:2322
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e4bb)
Location: include/linux/skbuff.h:2322
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff8194fc9a)
Location: include/linux/skbuff.h:2322
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff819597f4)
Location: include/linux/skbuff.h:2322
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff8173f325)
Location: include/linux/skbuff.h:2333
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81742d84)
Location: include/linux/skbuff.h:2333
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/dev.c (ffffffff81895e9d)
Location: include/linux/skbuff.h:2333
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff818b4a11)
Location: include/linux/skbuff.h:2333
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (ffffffff818bfb0c)
Location: include/linux/skbuff.h:2333
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff818caff7)
Location: include/linux/skbuff.h:2333
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff818cb4ff)
Location: include/linux/skbuff.h:2333
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/ipv4/route.c (ffffffff818e6b32)
Location: include/linux/skbuff.h:2333
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffff81920600)
Location: include/linux/skbuff.h:2333
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8193c399)
Location: include/linux/skbuff.h:2333
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff8194954e)
Location: include/linux/skbuff.h:2333
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/xfrm6_input.c (ffffffff819a1fb7)
Location: include/linux/skbuff.h:2333
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a782a)
Location: include/linux/skbuff.h:2333
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff819a8b3c)
Location: include/linux/skbuff.h:2333
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff819b049b)
Location: include/linux/skbuff.h:2333
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff8176322b)
Location: include/linux/skbuff.h:2411
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817675c8)
Location: include/linux/skbuff.h:2411
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/dev.c (ffffffff818b7c63)
Location: include/linux/skbuff.h:2411
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff818dc304)
Location: include/linux/skbuff.h:2411
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (ffffffff818e892c)
Location: include/linux/skbuff.h:2411
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff818f1096)
Location: include/linux/skbuff.h:2411
Inline: True
```
```
In net/ethernet/eth.c (ffffffff818f61a7)
Location: include/linux/skbuff.h:2411
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff818f669f)
Location: include/linux/skbuff.h:2411
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/ipv4/route.c (ffffffff819139f8)
Location: include/linux/skbuff.h:2411
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffff8194f436)
Location: include/linux/skbuff.h:2411
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8196c091)
Location: include/linux/skbuff.h:2411
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/skbuff.h:2411
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/skbuff.h:2411
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de391)
Location: include/linux/skbuff.h:2411
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff819df666)
Location: include/linux/skbuff.h:2411
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff819e7ca2)
Location: include/linux/skbuff.h:2411
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff817a0f8f)
Location: include/linux/skbuff.h:2499
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a4e2d)
Location: include/linux/skbuff.h:2499
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff818ec9cb)
Location: include/linux/skbuff.h:2499
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff81903ad3)
Location: include/linux/skbuff.h:2499
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff8192929b)
Location: include/linux/skbuff.h:2499
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (ffffffff8193813e)
Location: include/linux/skbuff.h:2499
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81942aed)
Location: include/linux/skbuff.h:2499
Inline: True
```
```
In net/ethernet/eth.c (ffffffff819557e8)
Location: include/linux/skbuff.h:2499
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff81955d2b)
Location: include/linux/skbuff.h:2499
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/ipv4/route.c (ffffffff819760aa)
Location: include/linux/skbuff.h:2499
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffff819b3c6c)
Location: include/linux/skbuff.h:2499
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff819d2de1)
Location: include/linux/skbuff.h:2499
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/skbuff.h:2499
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2499
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819f5f79)
Location: include/linux/skbuff.h:2499
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/skbuff.h:2499
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4cef1)
Location: include/linux/skbuff.h:2499
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e1fa)
Location: include/linux/skbuff.h:2499
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81a54836)
Location: include/linux/skbuff.h:2499
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff817c5f5f)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c8f2d)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8191eafc)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff81936894)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff8195b97b)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (ffffffff8196affe)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81977a3d)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/ethernet/eth.c (ffffffff8198bc88)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff8198c1cb)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/ipv4/route.c (ffffffff819acaba)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffff819ea99c)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81a0994f)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2cbf9)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83ac1)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81a84e5a)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81a8b426)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff8188e146)
Location: include/linux/skbuff.h:2536
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81893562)
Location: include/linux/skbuff.h:2536
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff819f138f)
Location: include/linux/skbuff.h:2536
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff81a02183)
Location: include/linux/skbuff.h:2536
Inline: True
Inline callers:
  - net/core/dev.c:napi_frags_skb
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff81a2ecd6)
Location: include/linux/skbuff.h:2536
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (ffffffff81a3ed68)
Location: include/linux/skbuff.h:2536
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81a4ca75)
Location: include/linux/skbuff.h:2536
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81a63938)
Location: include/linux/skbuff.h:2536
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff81a63dcb)
Location: include/linux/skbuff.h:2536
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/ipv4/route.c (ffffffff81a9686d)
Location: include/linux/skbuff.h:2536
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ad87c3)
Location: include/linux/skbuff.h:2536
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81afa0bf)
Location: include/linux/skbuff.h:2536
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c7ef)
Location: include/linux/skbuff.h:2536
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2536
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1f80e)
Location: include/linux/skbuff.h:2536
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/skbuff.h:2536
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78b91)
Location: include/linux/skbuff.h:2536
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e89a)
Location: include/linux/skbuff.h:2536
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81b7feda)
Location: include/linux/skbuff.h:2536
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81b87244)
Location: include/linux/skbuff.h:2536
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_parse_headers
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
In drivers/net/tun.c (ffffffff8189c662)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a1852)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff819f131f)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
```
```
In net/core/dev.c (ffffffff81a02983)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/core/dev.c:napi_frags_skb
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff81a3027c)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (ffffffff81a41b08)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81a52735)
Location: include/linux/skbuff.h:2562
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81a6ba98)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff81a6bf2b)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81a6f480)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81aa0918)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ae4cf6)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06a26)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81b07884)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1ab08)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2562
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e0de)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/skbuff.h:2562
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87afa)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d8aa)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f35a)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81b96d9d)
Location: include/linux/skbuff.h:2562
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_parse_headers
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
In drivers/net/tun.c (ffffffff8187ebc6)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81883ed4)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff819d65c8)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
```
```
In net/core/dev.c (ffffffff819f2585)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff81a15cb5)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (ffffffff81a265cb)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81a36176)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/core/lwt_bpf.c (ffffffff81a37ec8)
Location: include/linux/skbuff.h:2578
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81a54228)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff81a546bb)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81a57d62)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81a8b848)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81acff13)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af2135)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81af302c)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b087b8)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2578
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c04c)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/skbuff.h:2578
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b767aa)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c75a)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81b7e0ca)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81b85da2)
Location: include/linux/skbuff.h:2578
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_parse_headers
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
In drivers/net/tun.c (ffffffff819103e0)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8191586a)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81a86c18)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
```
```
In net/core/dev.c (ffffffff81aa4455)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff81ac6ee5)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (ffffffff81adb346)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81aebe0b)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/core/lwt_bpf.c (ffffffff81aedce3)
Location: include/linux/skbuff.h:2607
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81b0cf3a)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff81b0d3ab)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81b10d29)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81b467b0)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e933)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2645)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81bb353c)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb6c3)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2607
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81be09d8)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/skbuff.h:2607
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c41235)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c475f0)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81c496ea)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/skbuff.h:2607
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c52148)
Location: include/linux/skbuff.h:2607
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_parse_headers
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
In drivers/net/tun.c (ffffffff81a6721e)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6af48)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81bfc363)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
```
```
In net/core/dev.c (ffffffff81c196bf)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff81c43b27)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/gro.c (ffffffff81c54435)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/core/netpoll.c (ffffffff81c5c848)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81c6e7a9)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/core/lwt_bpf.c (ffffffff81c70b36)
Location: include/linux/skbuff.h:2976
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81c93870)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff81c9409f)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81c97ec5)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/skbuff.h:2976
Inline: True
```
```
In net/ipv4/route.c (ffffffff81cd33d3)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffff81d20090)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45dd1)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81d46d5e)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d6118e)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2976
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81d777d4)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/skbuff.h:2976
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddf9d7)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de69d1)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81de8ed6)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/skbuff.h:2976
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df44b0)
Location: include/linux/skbuff.h:2976
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff81bf23b4)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfdd4a)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81dab233)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
```
```
In net/core/dev.c (ffffffff81dca6ff)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff81df80d7)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/gro.c (ffffffff81e09b85)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/core/netpoll.c (ffffffff81e12f38)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81e264d9)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/core/lwt_bpf.c (ffffffff81e28b62)
Location: include/linux/skbuff.h:2870
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81e4efa0)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff81e4f8df)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81e53e40)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/skbuff.h:2870
Inline: True
```
```
In net/ipv4/route.c (ffffffff81e935c3)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffff81ee728d)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f198)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81f105ae)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2ba80)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2870
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44064)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/skbuff.h:2870
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1ca1)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb97d5)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81fbc606)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/skbuff.h:2870
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc9223)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff81c4b06e)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81c4e073)
Location: include/linux/skbuff.h:2924
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c63389)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81e1ad33)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
```
```
In net/core/dev.c (ffffffff81e3b27f)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff81e6a6e7)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/gro.c (ffffffff81e7c345)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/core/gso.c (ffffffff81e7d757)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/core/gso.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff81e86862)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81e9ba79)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/core/lwt_bpf.c (ffffffff81e9e182)
Location: include/linux/skbuff.h:2924
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81eaa640)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff81eab05f)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81eaf6ba)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/skbuff.h:2924
Inline: True
```
```
In net/ipv4/route.c (ffffffff81ef1d68)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffff81f46b2f)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6ee90)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81f7029a)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b8d8)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2924
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa387b)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/skbuff.h:2924
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff82012389)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019fca)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff8201cef6)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/skbuff.h:2924
Inline: True
```
```
In net/packet/af_packet.c (ffffffff82029946)
Location: include/linux/skbuff.h:2924
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff81d009a9)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81d040d8)
Location: include/linux/skbuff.h:2931
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d19da9)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81ed83d3)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
```
```
In net/core/dev.c (ffffffff81ef9639)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff81f29677)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/gro.c (ffffffff81f3c695)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/core/gso.c (ffffffff81f3e6d4)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/core/gso.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff81f4886f)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81f5e1d9)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/core/lwt_bpf.c (ffffffff81f60902)
Location: include/linux/skbuff.h:2931
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81f6d0f0)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff81f6db0f)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81f7213a)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/skbuff.h:2931
Inline: True
```
```
In net/ipv4/route.c (ffffffff81fb5eb8)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffff8200cc6f)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff820355c2)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff820369ca)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff820531d8)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2931
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff82070bab)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/skbuff.h:2931
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e14f9)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8f9a)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff820ebed6)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/skbuff.h:2931
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820f940d)
Location: include/linux/skbuff.h:2931
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffff8000109e0f28)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a03368)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffff800010bb92c4)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffff800010bd4f54)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffff800010bfccac)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffff800010c1ee0c)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/ethernet/eth.c (ffff800010c36d10)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffff800010c371f4)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/ipv4/route.c (ffff800010c5cbf8)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffff800010ca0680)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffff800010cc2d38)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffff800010ceb85c)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffff800010d50f1c)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffff800010d59f3c)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (c0ac5468)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (c0ade1b0)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (c0cd5d8c)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (c0cef41c)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (c0d180e8)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (c0d29538)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (c0d36134)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/ethernet/eth.c (c0d49668)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (c0d49afc)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/ipv4/route.c (c0d6c344)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (c0dad770)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (c0dce504)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (c0e50594)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (c0e51a7c)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (c0e589cc)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_parse_headers
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
In drivers/net/tun.c (c000000000aa2338)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa93f0)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (c000000000c9187c)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (c000000000cb42cc)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (c000000000ce522c)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (c000000000cfe308)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (c000000000d0fdb8)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/ethernet/eth.c (c000000000d2ed04)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (c000000000d2f674)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/ipv4/route.c (c000000000d5f1b8)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (c000000000db2e84)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (c000000000ddeb84)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/xfrm/xfrm_output.c (c000000000e0f5a4)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86eb0)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (c000000000e88e10)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (c000000000e941bc)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_parse_headers
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
In drivers/net/tun.c (ffffffe00062abe2)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062d6f4)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffe000748880)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffe00075eb10)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffe00077f11e)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (ffffffe00078d7ec)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffe000797e22)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/ethernet/eth.c (ffffffe0007a86ae)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffe0007a8b0c)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/ipv4/route.c (ffffffe0007c5a20)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffe0007fcd38)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffe000818184)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffe0008391cc)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000888036)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffe0008891da)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffe00088fe3c)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_parse_headers
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
In drivers/net/tun.c (ffffffff8178aa3f)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178da0d)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff818beafc)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff818d6864)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff818fb94b)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (ffffffff8190afce)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff819178ad)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/ethernet/eth.c (ffffffff8192baf8)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff8192c03b)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/ipv4/route.c (ffffffff8194c92a)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffff8198a80c)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff819a96ef)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc289)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a23151)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81a244ea)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81a2aab6)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff8176a38f)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/vxlan.c (ffffffff81773a8d)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817767dd)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81878a3c)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff818906a4)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff818b577b)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (ffffffff818c4d69)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff818d165d)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/ethernet/eth.c (ffffffff818e58a8)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff818e5b3b)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/ipv4/route.c (ffffffff8190641a)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffff819442cc)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff819631af)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81989079)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dff11)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff819e12aa)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff819e7ca6)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff817baddf)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bddad)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8190fafc)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff81927894)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff8194c97b)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (ffffffff8195bffe)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81968a3d)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/ethernet/eth.c (ffffffff8197cc88)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff8197d1cb)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/ipv4/route.c (ffffffff819b70fa)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffff819f4fdc)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81a13f8f)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a36d09)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8dbd1)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ef6a)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81a96666)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff817d32c9)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d85dd)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81930c2c)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/dev.c (ffffffff81948f34)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/filter.c (ffffffff8196e33b)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/netpoll.c (ffffffff8197e3de)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff8198ae10)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/ethernet/eth.c (ffffffff8199f1f8)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/802/fddi.c (ffffffff8199f73b)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/802/fddi.c:fddi_type_trans
```
```
In net/ipv4/route.c (ffffffff819c097a)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/udp_offload.c (ffffffff819ff1e3)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81a1e97f)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42699)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/skbuff.h:2513
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a8d1)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bcea)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81aa32e0)
Location: include/linux/skbuff.h:2513
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
</details>
</li>
</ul>

## Differences
