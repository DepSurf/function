# Function: <code>skb_headroom</code>

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
In drivers/net/tun.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f7fc2)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81707366)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff8171c289)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/core/netpoll.c (ffffffff81738b3e)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/netfilter/core.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff8175aa0f)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff817833e9)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff8178b1be)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff817a52a1)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff817a94bd)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff817ac255)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817aeef5)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff817c6cfe)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff817fa069)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff817fdcb5)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/ip6_checksum.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/ipv6/mcast_snoop.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/skbuff.h:1866
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff8180975d)
Location: include/linux/skbuff.h:1866
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
In drivers/net/tun.c (ffffffff8164e908)
Location: include/linux/skbuff.h:1967
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81651d8a)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff816581a6)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81770a32)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
```
```
In net/core/dev.c (ffffffff81784f55)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_csum_offload_chk
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8179da0b)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (ffffffff817a4e12)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/netfilter/core.c (ffffffff817bd08f)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:1967
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff817c6db7)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817c99ee)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_input.c (ffffffff817e006f)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff817e556f)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eb94f)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff817f113a)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff817f76d7)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/udp_offload.c (ffffffff817f8f27)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff817fc98f)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81806214)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff818130d2)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv4/ipmr.c (ffffffff81816cfd)
Location: include/linux/skbuff.h:1967
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff81819594)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181bde5)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_output.c (ffffffff818290c1)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81834524)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff818359cf)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff818530b5)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81853976)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81857103)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818604c5)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81866e81)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff818698cf)
Location: include/linux/skbuff.h:1967
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff8186d5fd)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff8186fb42)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/ip6_checksum.c (ffffffff818719da)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81872c4b)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818739c6)
Location: include/linux/skbuff.h:1967
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818787d9)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff8187b25e)
Location: include/linux/skbuff.h:1967
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
In drivers/net/tun.c (ffffffff8168060a)
Location: include/linux/skbuff.h:1984
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81685f36)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff8179dae6)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
```
```
In net/core/dev.c (ffffffff817b2565)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff817cb79b)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (ffffffff817d3882)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff817da057)
Location: include/linux/skbuff.h:1984
Inline: True
```
```
In net/netfilter/core.c (ffffffff817ec9cf)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:1984
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff817f68b8)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817f9976)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_input.c (ffffffff81810440)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff818159f7)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c2bf)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81821eca)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff818285e3)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/udp_offload.c (ffffffff81829df7)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff8182d8f4)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff818372a5)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff818445e2)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv4/ipmr.c (ffffffff818484cc)
Location: include/linux/skbuff.h:1984
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff8184ae3a)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184d6a5)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_output.c (ffffffff8185aaa1)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81865f84)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff818674ff)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff81884db5)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81885686)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81888f03)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81892455)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8189502e)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81899581)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff8189c71f)
Location: include/linux/skbuff.h:1984
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff818a03e8)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff818a2ab2)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a44c4)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_checksum.c (ffffffff818a5f3a)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818a726b)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a8046)
Location: include/linux/skbuff.h:1984
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818ad02b)
Location: include/linux/skbuff.h:1984
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff818afb1e)
Location: include/linux/skbuff.h:1984
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
In drivers/net/tun.c (0)
Location: include/linux/skbuff.h:2023
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:2023
Inline: True
```
```
In net/core/skbuff.c (ffffffff817bc727)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
```
```
In net/core/dev.c (ffffffff817cf9a1)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff817eacf4)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:2023
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff817f901d)
Location: include/linux/skbuff.h:2023
Inline: True
```
```
In net/netfilter/core.c (ffffffff8180cde8)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:2023
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:2023
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81819c80)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_input.c (ffffffff81830367)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff81835df2)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183cbfa)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81842b69)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff818499e4)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_set_dev_scratch
```
```
In net/ipv4/udp_offload.c (ffffffff8184af69)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff8184ed9a)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81858543)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff81865e6f)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/skbuff.h:2023
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff8186e8af)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818710e3)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_output.c (ffffffff8187eb6d)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff8188a72f)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff8188bc8e)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff818aa59a)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff818aba58)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff818af5c7)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8be1)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818bb3a6)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff818bf668)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/skbuff.h:2023
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff818c6a2e)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff818c9065)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818cabe9)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_checksum.c (ffffffff818cc914)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818cdcf7)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ce853)
Location: include/linux/skbuff.h:2023
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d487f)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff818d62e6)
Location: include/linux/skbuff.h:2023
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
In drivers/net/tun.c (0)
Location: include/linux/skbuff.h:2110
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:2110
Inline: True
```
```
In net/core/skbuff.c (ffffffff81836df7)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
```
```
In net/core/dev.c (ffffffff818492e1)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818677a4)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:2110
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff8187691d)
Location: include/linux/skbuff.h:2110
Inline: True
```
```
In net/netfilter/core.c (ffffffff8188bfc8)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:2110
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:2110
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff818982bb)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_input.c (ffffffff818af94e)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff818b53f2)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc307)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff818c24c9)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff818c9533)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_set_dev_scratch
```
```
In net/ipv4/udp_offload.c (ffffffff818cabc9)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff818ceb20)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff818d8413)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff818e5fa1)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/skbuff.h:2110
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff818ef26f)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f1ad3)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffc0d)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff8190b936)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff8190cf79)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff8192d0aa)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff8192e618)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819322dd)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193baa3)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193e3bc)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81942738)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/skbuff.h:2110
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81949e65)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff8194c705)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e31c)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/skbuff.h:2110
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff819516c7)
Location: include/linux/skbuff.h:2110
Inline: True
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81952af7)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81953703)
Location: include/linux/skbuff.h:2110
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819592eb)
Location: include/linux/skbuff.h:2110
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff8195be80)
Location: include/linux/skbuff.h:2110
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
In drivers/net/tun.c (ffffffff817401e0)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:2121
Inline: True
```
```
In net/core/skbuff.c (ffffffff81880f3a)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
```
```
In net/core/dev.c (ffffffff8189326e)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818b57f8)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:2121
Inline: True
```
```
In net/core/timestamping.c (ffffffff818c6dbb)
Location: include/linux/skbuff.h:2121
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818c8006)
Location: include/linux/skbuff.h:2121
Inline: True
```
```
In net/bpf/test_run.c (ffffffff818df4e5)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/core.c (ffffffff818dfc67)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:2121
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:2121
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff818ec5e5)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_input.c (ffffffff81905218)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff8190aab2)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81912021)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff8191810a)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff8191f83b)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_set_dev_scratch
```
```
In net/ipv4/udp_offload.c (ffffffff81920afb)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81924ee6)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff8192ed79)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff8193c7c3)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/skbuff.h:2121
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff81945c0f)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81948403)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_output.c (ffffffff819564f5)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81962ff1)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff8196435c)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff819869a6)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff819875a2)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff8198ada5)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81995025)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819972ed)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff8199b591)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/skbuff.h:2121
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff819a2dde)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff819a577b)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a72c1)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff819a8919)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff819aad42)
Location: include/linux/skbuff.h:2121
Inline: True
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819ac095)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad10b)
Location: include/linux/skbuff.h:2121
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819af266)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff819b56b9)
Location: include/linux/skbuff.h:2121
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
In drivers/net/tun.c (ffffffff81764213)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:2199
Inline: True
```
```
In net/core/skbuff.c (ffffffff818a1dce)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
```
```
In net/core/dev.c (ffffffff818b3cae)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818d72d8)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:2199
Inline: True
```
```
In net/core/timestamping.c (ffffffff818eff0b)
Location: include/linux/skbuff.h:2199
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818f1176)
Location: include/linux/skbuff.h:2199
Inline: True
```
```
In net/bpf/test_run.c (ffffffff8190bf73)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/core.c (ffffffff8190c7e7)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:2199
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:2199
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8191977c)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_input.c (ffffffff81933415)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff81938d64)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819407ea)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff8194685b)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff8194e4d3)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_set_dev_scratch
```
```
In net/ipv4/udp_offload.c (ffffffff8194fea3)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81953ce7)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff8195e1d0)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff8196c4a4)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/skbuff.h:2199
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff81975f2f)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8197a0e3)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b33c)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81997fdf)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81999c89)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819bd2b2)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff819bdbaf)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c16fd)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb908)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cdbcc)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff819d1f69)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/skbuff.h:2199
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff819d9aa9)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff819dc20b)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dde18)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff819df450)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e186c)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e2c76)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3ab8)
Location: include/linux/skbuff.h:2199
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e5c2a)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff819ec97e)
Location: include/linux/skbuff.h:2199
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
In drivers/net/tun.c (ffffffff817a1f0b)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:2287
Inline: True
```
```
In net/core/skbuff.c (ffffffff818eca4c)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff818fab5d)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81924a9a)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:2287
Inline: True
```
```
In net/core/timestamping.c (ffffffff81941800)
Location: include/linux/skbuff.h:2287
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff819434fd)
Location: include/linux/skbuff.h:2287
Inline: True
```
```
In net/bpf/test_run.c (ffffffff8196d7de)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:2287
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:2287
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8197b941)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_input.c (ffffffff81996d14)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff8199cfa8)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4d2d)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff819aaebe)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff819b2c9c)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_set_dev_scratch
```
```
In net/ipv4/udp_offload.c (ffffffff819b475a)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff819b85f2)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff819c3575)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff819d3208)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/skbuff.h:2287
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff819dfac0)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e3c13)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2287
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819f67c2)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a03fad)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a05c60)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a2bd4a)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a2c695)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a304c7)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a338)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c223)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a40d5a)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/skbuff.h:2287
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81a4865e)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81a4ae88)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4ca12)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e034)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a5062b)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a519d8)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a52826)
Location: include/linux/skbuff.h:2287
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a5568c)
Location: include/linux/skbuff.h:2287
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff81a5bb3b)
Location: include/linux/skbuff.h:2287
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
In drivers/net/tun.c (ffffffff817c2bdb)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/skbuff.c (ffffffff8191eb78)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff8192cc81)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81956eca)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/timestamping.c (ffffffff81976710)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff819784cd)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/bpf/test_run.c (ffffffff819a4249)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819b2048)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_input.c (ffffffff819cd894)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff819d3a68)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dba2d)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1b8e)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff819e9a3f)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff819eb48a)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff819ef2f2)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff819fa115)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff81a09d78)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff81a16af0)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a1ac03)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d439)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a3ab96)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c7cc)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a628ad)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a631d5)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a67017)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70ed9)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a72ea3)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a779da)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81a7f21f)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81a81a58)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a835e2)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a84c61)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a8724b)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a885d8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a89406)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a8c75c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff81a92732)
Location: include/linux/skbuff.h:2301
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
In drivers/net/tun.c (ffffffff8188ac18)
Location: include/linux/skbuff.h:2324
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8189568a)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff819f13f3)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81a012a5)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a2d420)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_proto_4_to_6
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (ffffffff81a3deae)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/timestamping.c (ffffffff81a4b470)
Location: include/linux/skbuff.h:2324
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a4d508)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/bpf/test_run.c (ffffffff81a7ed5c)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (ffffffff81a97930)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81a99d46)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a9c8e1)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:neigh_hh_output
  - net/ipv4/ip_output.c:neigh_hh_output
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_input.c (ffffffff81ab99ba)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff81ac05e9)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8b0f)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81acf1db)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81ad7a03)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ad916e)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81add244)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81ae8ac8)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff81afa540)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81b027b8)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81b07b34)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0bec3)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d65b)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1fd0f)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81b3019d)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:neigh_hh_output
  - net/ipv6/ip6_output.c:neigh_hh_output
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ip6_input.c (ffffffff81b31e15)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b5b170)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b5c125)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5fa29)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a762)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d329)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b71c72)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b760b7)
Location: include/linux/skbuff.h:2324
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81b79ed5)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81b7d0b3)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7eb80)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7fc9a)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b823ed)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b83b4e)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b84870)
Location: include/linux/skbuff.h:2324
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b87b2c)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff81b8dbdf)
Location: include/linux/skbuff.h:2324
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
In drivers/net/tun.c (ffffffff81898e24)
Location: include/linux/skbuff.h:2345
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a3dba)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff819f138a)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81a01a95)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a2ecc0)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_proto_4_to_6
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:neigh_hh_output
  - net/core/filter.c:neigh_hh_output
  - net/core/filter.c:neigh_hh_output
```
```
In net/core/netpoll.c (ffffffff81a40bce)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/timestamping.c (ffffffff81a51090)
Location: include/linux/skbuff.h:2345
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a531c8)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81a6f3a0)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/bpf/test_run.c (ffffffff81a88739)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (ffffffff81aa1890)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81aa3caa)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81aa6779)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:neigh_hh_output
  - net/ipv4/ip_output.c:neigh_hh_output
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_input.c (ffffffff81ac4dc2)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff81acc04f)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4aaf)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81adb1e1)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81ae4053)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5b85)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81ae9f94)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81af59cd)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b068ee)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81b07ce9)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81b10b7f)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81b15f0d)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b1a253)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2be75)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e61f)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ec44)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:neigh_hh_output
  - net/ipv6/ip6_output.c:neigh_hh_output
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ip6_input.c (ffffffff81b40a15)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b69981)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b6a815)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b6e1c9)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b791b4)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b7bdd1)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b809a6)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b84e3b)
Location: include/linux/skbuff.h:2345
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81b88e25)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81b8c163)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8db92)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b8efca)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b91ae1)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b93200)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b941d0)
Location: include/linux/skbuff.h:2345
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b9760c)
Location: include/linux/skbuff.h:2345
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff81b9d8ae)
Location: include/linux/skbuff.h:2345
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
In drivers/net/tun.c (ffffffff8187b550)
Location: include/linux/skbuff.h:2361
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81885aca)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff819d6633)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff819e8a45)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81a1631f)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:neigh_hh_output
  - net/core/filter.c:neigh_hh_output
  - net/core/filter.c:neigh_hh_output
```
```
In net/core/netpoll.c (ffffffff81a2588e)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/timestamping.c (ffffffff81a36910)
Location: include/linux/skbuff.h:2361
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a389f8)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81a57c75)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/bpf/test_run.c (ffffffff81a71999)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (ffffffff81a8c860)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81a8ed1b)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a91862)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:neigh_hh_output
  - net/ipv4/ip_output.c:neigh_hh_output
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_input.c (ffffffff81aafeae)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff81ab7268)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abfb63)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac6234)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81acf24a)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0e75)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81ad56fb)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81ae1134)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af2001)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81af34f5)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81afe789)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81b03d7a)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b07eff)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19aeb)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c32f)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b9d5)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:neigh_hh_output
  - net/ipv6/ip6_output.c:neigh_hh_output
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e2af)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b57c8d)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b58db5)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5c5bb)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67cee)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a8bc)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f5c4)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b73aef)
Location: include/linux/skbuff.h:2361
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81b77c4b)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81b7afe3)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7ca60)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7e00a)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b80d30)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b8229b)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b832de)
Location: include/linux/skbuff.h:2361
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b86615)
Location: include/linux/skbuff.h:2361
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff81b8c9d7)
Location: include/linux/skbuff.h:2361
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
In drivers/net/tun.c (ffffffff8190c900)
Location: include/linux/skbuff.h:2390
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8191746c)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/core/skbuff.c (ffffffff81a86c83)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81a961e5)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81ac727f)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (ffffffff81ada5ce)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/timestamping.c (ffffffff81aec660)
Location: include/linux/skbuff.h:2390
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81aee8d8)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81b10c15)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/bpf/test_run.c (ffffffff81b2b0b0)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (ffffffff81b47990)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81b49f70)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81b4cc35)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_input.c (ffffffff81b6ccdd)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff81b74458)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d6d6)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81b84a44)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81b8dc76)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_read_sock
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f892)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81b945f2)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81ba07d4)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2511)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81bb3a05)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81bbff9f)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81bc6053)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bcadff)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdddbb)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0c5f)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81bf1b31)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81bf45a5)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81c1f244)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81c2036d)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81c23d0a)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f93d)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81c3271c)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81c37681)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81c3e0fa)
Location: include/linux/skbuff.h:2390
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81c4276b)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81c45ca3)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47b8f)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81c48e7a)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4c18e)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff81c4cd50)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e34b)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f3ae)
Location: include/linux/skbuff.h:2390
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c529d5)
Location: include/linux/skbuff.h:2390
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff81c58d97)
Location: include/linux/skbuff.h:2390
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
In drivers/net/tun.c (ffffffff81a6053f)
Location: include/linux/skbuff.h:2758
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6b87f)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff81a74ea5)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:bounce_skb
```
```
In net/core/skbuff.c (ffffffff81bfc3d7)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81c1a1e9)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81c42a87)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:neigh_hh_output
  - net/core/filter.c:neigh_hh_output
  - net/core/filter.c:neigh_hh_output
```
```
In net/core/gro.c (ffffffff81c53775)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/netpoll.c (ffffffff81c5bca9)
Location: include/linux/skbuff.h:2758
Inline: True
```
```
In net/core/timestamping.c (ffffffff81c6ef9f)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/core/timestamping.c:skb_defer_rx_timestamp
```
```
In net/core/lwt_bpf.c (ffffffff81c71830)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81c97daa)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/bpf/test_run.c (ffffffff81cb52d5)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (ffffffff81cd4bf0)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81cd74db)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81cda38d)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:neigh_hh_output
  - net/ipv4/ip_output.c:neigh_hh_output
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_input.c (ffffffff81cfc174)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff81d03b60)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d68e)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81d152a2)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81d1ed9c)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_read_sock
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81d20b92)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81d25e9e)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81d32cc9)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45cc4)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81d4722a)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81d54958)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81d5b384)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d6076b)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81d74f43)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77b13)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a56f)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:neigh_hh_output
  - net/ipv6/ip6_output.c:neigh_hh_output
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d2d2)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81dbbad1)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81dbd0d4)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81dc0c3b)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dccdb9)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81dcff0b)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81dd5216)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81ddc744)
Location: include/linux/skbuff.h:2758
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81de1241)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81de4e43)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6fdf)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81de858a)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81dec1b4)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff81ded290)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (0)
Location: include/linux/skbuff.h:2758
Inline: True
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81deebf2)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81defdf9)
Location: include/linux/skbuff.h:2758
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df59b4)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff81dfa43a)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/mctp/route.c (ffffffff81e38f0e)
Location: include/linux/skbuff.h:2758
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_do_fragment_route
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
In drivers/net/tun.c (ffffffff81bebbeb)
Location: include/linux/skbuff.h:2650
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfe77f)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff81c06c03)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81dab2a7)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81dcb279)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81df7a77)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:neigh_hh_output
  - net/core/filter.c:neigh_hh_output
  - net/core/filter.c:neigh_hh_output
```
```
In net/core/gro.c (ffffffff81e08e35)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/netpoll.c (ffffffff81e120f9)
Location: include/linux/skbuff.h:2650
Inline: True
```
```
In net/core/timestamping.c (ffffffff81e26d2f)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/core/timestamping.c:skb_defer_rx_timestamp
```
```
In net/core/lwt_bpf.c (ffffffff81e29920)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81e53d4a)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/bpf/test_run.c (ffffffff81e73833)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (ffffffff81e94f20)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81e97b0d)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81e9ab4d)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:neigh_hh_output
  - net/ipv4/ip_output.c:neigh_hh_output
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_input.c (ffffffff81ec0cf4)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff81ec8acd)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed3043)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81edb482)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81ee5e9d)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7e0c)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81eed6f6)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81efaf59)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f08b)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81f10273)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f1eb7e)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81f25814)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f2af2b)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42180)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44399)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81f584ff)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:neigh_hh_output
  - net/ipv6/ip6_output.c:neigh_hh_output
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b38c)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81f8bbc4)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81f8d0f4)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81f91317)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9dec6)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81fa1265)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81fa691f)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81fad7e0)
Location: include/linux/skbuff.h:2650
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81fb36a1)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81fb75d3)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9e6f)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb537)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfe04)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff81fc10a0)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (0)
Location: include/linux/skbuff.h:2650
Inline: True
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2c42)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc3f09)
Location: include/linux/skbuff.h:2650
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc985f)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff81fceb5b)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/mctp/route.c (ffffffff8201222e)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_do_fragment_route
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
In drivers/net/tun.c (ffffffff81c44090)
Location: include/linux/skbuff.h:2704
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81c50c16)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:xmit_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c63db4)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff81c6c2fc)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81e1ada7)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81e3be20)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81e69781)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:neigh_hh_output
  - net/core/filter.c:neigh_hh_output
  - net/core/filter.c:neigh_hh_output
```
```
In net/core/gro.c (ffffffff81e7b555)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/gso.c (ffffffff81e7d736)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/core/gso.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff81e85919)
Location: include/linux/skbuff.h:2704
Inline: True
```
```
In net/core/timestamping.c (ffffffff81e9c2cf)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/core/timestamping.c:skb_defer_rx_timestamp
```
```
In net/core/lwt_bpf.c (ffffffff81e9ef60)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81eaf5ca)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/bpf/test_run.c (ffffffff81ecf4d6)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (ffffffff81ef36f0)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81ef6353)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81ef94f0)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:neigh_hh_output
  - net/ipv4/ip_output.c:neigh_hh_output
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_input.c (ffffffff81f1f264)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff81f275f1)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31d44)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81f3a542)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81f4569a)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81f47695)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81f4d0b9)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81f5a9e8)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6ed89)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81f6ff63)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f7e67e)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff81f853a4)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f8abfb)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1968)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3b90)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81fb812e)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:neigh_hh_output
  - net/ipv6/ip6_output.c:neigh_hh_output
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb156)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81fec342)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81fed8c4)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81ff1c2c)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe93a)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff82001b67)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff82007170)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff8200df90)
Location: include/linux/skbuff.h:2704
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff82013db2)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff82017d23)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a5a2)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8201bbf7)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020ddc)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff82022033)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (0)
Location: include/linux/skbuff.h:2704
Inline: True
```
```
In net/ipv6/tcpv6_offload.c (ffffffff82023bd1)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff82024f29)
Location: include/linux/skbuff.h:2704
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202be40)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff8204a511)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/mctp/route.c (ffffffff8208f01e)
Location: include/linux/skbuff.h:2704
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_do_fragment_route
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
In drivers/net/netkit.c (ffffffff81ce546c)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_xmit
```
```
In drivers/net/tun.c (ffffffff81cf9950)
Location: include/linux/skbuff.h:2711
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81d06c56)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:xmit_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1a7d4)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff81d20cac)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81ed8447)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_ensure_writable_head_tail
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81efa360)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81f28d61)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:neigh_hh_output
  - net/core/filter.c:neigh_hh_output
  - net/core/filter.c:neigh_hh_output
```
```
In net/core/gro.c (ffffffff81f3b7e5)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/gso.c (ffffffff81f3e6b3)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/core/gso.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff81f47849)
Location: include/linux/skbuff.h:2711
Inline: True
```
```
In net/core/timestamping.c (ffffffff81f5ea5f)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/core/timestamping.c:skb_defer_rx_timestamp
```
```
In net/core/lwt_bpf.c (ffffffff81f616d0)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_frag.c (ffffffff81f7204a)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/bpf/test_run.c (ffffffff81f92e26)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (ffffffff81fb7680)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81fba2e6)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81fbd40d)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:neigh_hh_output
  - net/ipv4/ip_output.c:neigh_hh_output
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_input.c (ffffffff81fe391f)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff81fe94c4)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7d8b)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff82000632)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff8200b7d5)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8200d7d5)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff820131c9)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff82020f28)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff820354a9)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff82036693)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff82044d29)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff8204ba60)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8205230b)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (ffffffff8206ec88)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/xfrm/xfrm_output.c (ffffffff82070ebd)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff8208571d)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:neigh_hh_output
  - net/ipv6/ip6_output.c:neigh_hh_output
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ip6_input.c (ffffffff82088566)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff820b9f55)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff820bb4d4)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff820bf82b)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd66f)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff820d096a)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff820d5fd0)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff820dcb1d)
Location: include/linux/skbuff.h:2711
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff820e2f0c)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff820e6cf3)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e955f)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff820eabb7)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820eff09)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff820f1153)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (0)
Location: include/linux/skbuff.h:2711
Inline: True
```
```
In net/ipv6/tcpv6_offload.c (ffffffff820f2d31)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f4209)
Location: include/linux/skbuff.h:2711
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fb8f1)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff8211c97d)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/mctp/route.c (ffffffff821654fe)
Location: include/linux/skbuff.h:2711
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_do_fragment_route
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
In drivers/net/tun.c (ffff8000109dd738)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/skbuff.c (ffff800010bb9314)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffff800010bcf58c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffff800010bf8694)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/timestamping.c (ffff800010c1ccfc)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/lwt_bpf.c (ffff800010c1efe8)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/bpf/test_run.c (ffff800010c53634)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/ip_output.c (ffff800010c63da0)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_input.c (ffff800010c80204)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffff800010c8683c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ea7c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffff800010c95ba4)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffff800010c9f3c8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffff800010ca0fe4)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffff800010ca4f5c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffff800010cae1fc)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffff800010cc3114)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/netfilter.c (ffff800010cd2734)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd6ca4)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffff800010cebf44)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffff800010cfbc5c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffff800010cfda24)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffff800010d27900)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffff800010d28508)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffff800010d2ce9c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39084)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffff800010d3b984)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffff800010d41034)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv6/netfilter.c (ffff800010d4a4bc)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffff800010d4d1c4)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f328)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffff800010d50cd8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffff800010d55178)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffff800010d56284)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d57f00)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffff800010d604d8)
Location: include/linux/skbuff.h:2301
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
In drivers/net/tun.c (c0ac5f2c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/skbuff.c (c0cd5dc8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (c0ce4ba0)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (c0d122dc)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/timestamping.c (c0d34bc4)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/lwt_bpf.c (c0d36d34)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/bpf/test_run.c (c0d62f9c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/ip_output.c (c0d7231c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_input.c (c0d8f574)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (c0d95930)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (c0d9da08)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (c0da42e8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (c0dac580)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/udp_offload.c (c0dad530)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (c0db1860)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (c0dbd52c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (c0dce930)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/netfilter.c (c0ddc660)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (c0de09e4)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/xfrm/xfrm_output.c (c0df3e68)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (c0e02ce4)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c0e0510c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (c0e2c4ac)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2d5bc)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c0e30b9c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c0e3bc5c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (c0e3df1c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (c0e43a48)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv6/netfilter.c (c0e4bad4)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (c0e4e828)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (c0e50084)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (c0e51828)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (c0e54184)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (c0e55720)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (c0e567f8)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/packet/af_packet.c (c0e59e90)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (c0e5ff94)
Location: include/linux/skbuff.h:2301
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
In drivers/net/tun.c (c000000000aa3f78)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/skbuff.c (c000000000c91910)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (c000000000ca63b0)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (c000000000cdf5b8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/timestamping.c (c000000000d0dcc8)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/lwt_bpf.c (c000000000d10fcc)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/bpf/test_run.c (c000000000d52d24)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/ip_output.c (c000000000d66000)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_input.c (c000000000d8af64)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (c000000000d92acc)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d684)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (c000000000da6f10)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (c000000000db17c0)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (c000000000db3f20)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (c000000000db8d20)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (c000000000dc8794)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (c000000000dde810)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/netfilter.c (c000000000df0d34)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (c000000000df6920)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/xfrm/xfrm_output.c (c000000000e10000)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (c000000000e23480)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c000000000e25bf0)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (c000000000e58920)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (c000000000e59890)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c000000000e5e860)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c664)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (c000000000e6f254)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (c000000000e758d0)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv6/netfilter.c (c000000000e80554)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (c000000000e84230)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86d00)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (c000000000e88b80)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (c000000000e8c260)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (c000000000e8dee0)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f370)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/packet/af_packet.c (c000000000e93078)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (c000000000e9b49c)
Location: include/linux/skbuff.h:2301
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
In drivers/net/tun.c (ffffffe00062890e)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/skbuff.c (ffffffe0007488bc)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffe000755a96)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffe00077a3a8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/timestamping.c (ffffffe000796a74)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffe00079891e)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/bpf/test_run.c (ffffffe0007bdf1e)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffe0007ca63a)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_input.c (ffffffe0007e2404)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffe0007e7e3e)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eee90)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f4d8c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffe0007fb976)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd600)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffe000800952)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffe00080a2e2)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffe000818508)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffe000823a60)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffe0008275e2)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffe0008397d4)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffe0008465d4)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffe000847ee6)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffe000869286)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffe000869d84)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffe00086cfbe)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000876488)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffe000878278)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffe00087c796)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffe0008839c4)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffe000886018)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000887e48)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffe000889018)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b560)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffe00088c9b8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088daa6)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/packet/af_packet.c (ffffffe00088fb78)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffe0008958cc)
Location: include/linux/skbuff.h:2301
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
In drivers/net/tun.c (ffffffff817876ab)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/skbuff.c (ffffffff818beb78)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff818ccc81)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818f6e9a)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff8191833d)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/bpf/test_run.c (ffffffff819440b9)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81951eb8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_input.c (ffffffff8196d704)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff819738d8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b89d)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff819819fe)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff819898af)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8198b2fa)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff8198f092)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81999eb5)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff819a9b18)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff819b6180)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819ba293)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819ccac9)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819da226)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff819dbe5c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a01f3d)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a02865)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a066a7)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10569)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a12533)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a1706a)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81a1e8af)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81a210e8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a22c72)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a242f1)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a268db)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a27c68)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28a96)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2bdec)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff81a31dc2)
Location: include/linux/skbuff.h:2301
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
In drivers/net/tun.c (ffffffff81766ffb)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/vxlan.c (ffffffff8176bdcc)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_build_skb
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/skbuff.c (ffffffff81878ab8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81886d11)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818b0cca)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818d20ed)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/bpf/test_run.c (ffffffff818fdba9)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8190b9a8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_input.c (ffffffff819271f4)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff8192d3a8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193535d)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff8193b4be)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff8194336f)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81944dba)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81948b52)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81953975)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff819635d8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967ed8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff81972f70)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81977083)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819898b9)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81996fe6)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81998c1c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819becfd)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff819bf625)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c3467)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd329)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cf2f3)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff819d3e2a)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff819db66f)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff819ddea8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dfa32)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff819e10b1)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e369b)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e4a28)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5c86)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e8fdc)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff819eefb2)
Location: include/linux/skbuff.h:2301
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
In drivers/net/tun.c (ffffffff817b7a5b)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/skbuff.c (ffffffff8190fb78)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff8191dc81)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81947eca)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/timestamping.c (ffffffff81967710)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff819694cd)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81995249)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff81999b70)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819bc688)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_input.c (ffffffff819d7ed4)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff819de0a8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e606d)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff819ec1ce)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff819f407f)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff819f5aca)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff819f9932)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81a04755)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff81a143b8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff81a20a20)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a24d13)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a37549)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a44ca6)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a468dc)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a6c9bd)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a6d2e5)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a71127)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7afe9)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a7cfb3)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a81aea)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81a8932f)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81a8bb68)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d6f2)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ed71)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9248b)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a93818)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a94646)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a9799c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff81a9d972)
Location: include/linux/skbuff.h:2301
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
In drivers/net/tun.c (ffffffff817d2133)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/skbuff.c (ffffffff81930ca8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff8193f2f1)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff819697da)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/timestamping.c (ffffffff819899a0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff8198b8ad)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/bpf/test_run.c (ffffffff819b7dc9)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819c5f98)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_input.c (ffffffff819e1b0d)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff819e7d28)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819efd2d)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff819f607e)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff819fe23f)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/udp_offload.c (ffffffff819ffcca)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81a03c22)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81a0ecd5)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff81a1edba)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff81a2bf40)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a30183)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42eea)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a50966)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a5260c)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a78ff5)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a79905)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a7d737)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87829)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a89803)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a8e3ea)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/ipv6/netfilter.c (ffffffff81a95f8f)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/calipso.c (ffffffff81a989f8)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a3e2)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bae1)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9e53b)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9f968)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa07a6)
Location: include/linux/skbuff.h:2301
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa42bc)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/8021q/vlan_core.c (ffffffff81aa9b72)
Location: include/linux/skbuff.h:2301
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
</ul>

## Differences
