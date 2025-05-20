# Function: <code>csum_fold</code>

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
In arch/x86/lib/csum-partial_64.c (ffffffff813f63a5)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In net/core/skbuff.c (ffffffff81707f2e)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/datagram.c (ffffffff8170d760)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_checksum_complete_head
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (ffffffff81718223)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff8172fd41)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff817323c1)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffffffff81739448)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ip_output.c (ffffffff8175f847)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177e09b)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff8178319a)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff817865c2)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff8178b080)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/icmp.c (ffffffff8178dd01)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff817976ae)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff817a3de0)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff817a4efa)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff817a84bd)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/ipv4/inet_lro.c (ffffffff817abbdc)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff817ac3a2)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:nf_ip_checksum
```
```
In net/unix/af_unix.c (ffffffff817be5d0)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff817e8905)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f2039)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff817f8f08)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff818003b7)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81801388)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff818019f6)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81802695)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81817b4d)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
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
In arch/x86/lib/csum-partial_64.c (ffffffff8143cf75)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In net/core/skbuff.c (ffffffff817717b7)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/datagram.c (ffffffff81775290)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
```
```
In net/core/dev.c (ffffffff817803b3)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff8179a491)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff8179c890)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffffffff817a56fc)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ip_output.c (ffffffff817cbae7)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ebd52)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff817f0727)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff817f782a)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff817f84b5)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff817fca37)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81806074)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff81810b35)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff81812fb5)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81815b9d)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/ipv4/netfilter.c (ffffffff818196ef)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:nf_ip_checksum
```
```
In net/unix/af_unix.c (ffffffff8182b570)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff8185712a)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818608f8)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81866d56)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff818686f8)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81871a6b)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81872bc8)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81873997)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81891603)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
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
In arch/x86/lib/csum-partial_64.c (ffffffff81459f15)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In net/core/skbuff.c (ffffffff8179e877)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/datagram.c (ffffffff817a2580)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
```
```
In net/core/dev.c (ffffffff817add03)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff817c8231)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff817cbb30)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffffffff817d416c)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ip_output.c (ffffffff817fb762)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c6d6)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81821497)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff8182872e)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81829365)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff8182d99c)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff818370f4)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff81842040)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff818444c5)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8184734d)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/ipv4/netfilter.c (ffffffff8184afaf)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:nf_ip_checksum
```
```
In net/unix/af_unix.c (ffffffff8185cf90)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81888f2a)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818928d2)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81899456)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff8189b548)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff818a5fcb)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818a71e8)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a8017)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff818c5f13)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
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
In net/core/skbuff.c (ffffffff817bc4bf)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/datagram.c (ffffffff817bfdb5)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
```
```
In net/core/dev.c (ffffffff817cc863)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff817e6b95)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff817eac10)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffffffff817f34bc)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ip_output.c (ffffffff8181bb2b)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183cf9c)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81842177)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81849a3e)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8184ab1e)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff8184ee00)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81858749)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff818639a7)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff81865da7)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81868d3d)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/ipv4/netfilter.c (ffffffff8186ea30)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:nf_ip_checksum
```
```
In net/unix/af_unix.c (ffffffff8188179a)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff818af46f)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8ff6)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff818bf775)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff818c12f0)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff818cca55)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818cdc5b)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ce887)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff818fba65)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff818fbae3)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
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
In net/core/skbuff.c (ffffffff81836b8f)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/datagram.c (ffffffff81839965)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
```
```
In net/core/dev.c (ffffffff81845f33)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff81861ad5)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff81866e1c)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffffffff8186e8ac)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ip_output.c (ffffffff8189aa64)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc70a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff818c1a57)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff818c958d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff818ca7be)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff818ceb86)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff818d861f)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff818e3aea)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff818e5ed9)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff818e927d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/ipv4/netfilter.c (ffffffff818ef3f2)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:nf_ip_checksum
```
```
In net/unix/af_unix.c (ffffffff8190293a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81932185)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193bf0b)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81942845)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81944529)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81951841)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81952a5b)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81953737)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff819828b5)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81982933)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
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
In net/core/skbuff.c (ffffffff81880c37)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
```
```
In net/core/datagram.c (ffffffff818840a5)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
```
```
In net/core/dev.c (ffffffff8188e483)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff818ad6f6)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff818b67bd)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffffffff818bfa39)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/route.c (ffffffff818e7215)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff818eef28)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911c7d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81917727)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff8191f41d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8192031a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81924f94)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff8192edea)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff8193a2be)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff8193c832)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8193fd7d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/ipv4/netfilter.c (ffffffff81945dd0)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:nf_ip_checksum
```
```
In net/unix/af_unix.c (ffffffff81958daa)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff8198acd5)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994c9b)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff8199b613)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff8199cfe8)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819aac4f)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819ac00b)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad152)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff819dede6)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff819dee61)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
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
In net/core/skbuff.c (ffffffff818a1ae4)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (ffffffff818a5119)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (ffffffff818af430)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff818d1956)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff818db9d3)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffffffff818e8859)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff8190e85d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff8191411d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8191c718)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8194044e)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81945e64)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff8194e088)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8194f023)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81953ddb)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff8195e245)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff8196a312)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff8196c516)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8196f614)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/unix/af_unix.c (ffffffff8198d960)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff819c15c7)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb588)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff819d202a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff819d33d9)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e174f)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e2be8)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3b03)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff81a19d16)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a19d91)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
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
In net/core/skbuff.c (ffffffff818ec5ad)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (ffffffff818efc9f)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (ffffffff818fb270)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff8191ebe6)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff81928e63)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffffffff8193806b)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff819703b2)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff819764f3)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8197ea43)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a498c)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff819aa495)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819b2896)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819b3813)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff819b86fa)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff819c360e)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff819d0d9b)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff819d326e)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff819d8d58)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/unix/af_unix.c (ffffffff819f900f)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a303a6)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39ffe)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a40e0d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a42422)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a5050d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a51938)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a52873)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff81a89a36)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a89ab1)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
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
In net/core/skbuff.c (ffffffff8191e6dd)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (ffffffff81921cbf)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (ffffffff8192d3c0)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff81950e60)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff8195b543)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffffffff8196af2b)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff819a6da2)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff819acf03)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff819b53d5)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db68c)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1165)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819e9636)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819ea543)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff819ef3fa)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff819fa1ae)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff81a078f5)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff81a09dde)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a0fa8a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/unix/af_unix.c (ffffffff81a2fc5f)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a66ef6)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70b8e)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a77a8d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a79082)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a8712d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a88538)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a89453)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff81ac0cd6)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81ac0d51)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
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
In arch/x86/lib/csum-partial_64.c (ffffffff815fd126)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff815fd1a1)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
```
```
In net/core/skbuff.c (ffffffff819f1e99)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (ffffffff819f59e3)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (ffffffff81a02450)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff81a21d7d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81a2f9d3)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffffffff81a3ec94)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff81a9011a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81a923ed)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a9f636)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8756)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81ace755)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81ad33e1)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ad8219)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81add34c)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81ae8b27)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff81af713a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff81afa456)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81b0334a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/unix/af_unix.c (ffffffff81b25a87)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_mkname
```
```
In net/ipv6/icmp.c (ffffffff81b5f8db)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a388)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b71d03)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81b76c72)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b8255f)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b83ad8)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b8489d)
Location: arch/x86/include/asm/checksum_64.h:23
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
In arch/x86/lib/csum-partial_64.c (ffffffff81621f26)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81621f91)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
```
```
In net/core/skbuff.c (ffffffff819f1b39)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (ffffffff819f54a3)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (ffffffff81a02c50)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff81a220fd)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81a322a3)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffffffff81a41a34)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff81a99fea)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81a9c28d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/ip_output.c (ffffffff81aa9576)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad46f6)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81ada775)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81adf7dd)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ae48b9)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81ae8c68)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884_validate
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81af5a2c)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff81b03fde)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff81b07c00)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81b114aa)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/unix/af_unix.c (ffffffff81b34497)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_mkname
```
```
In net/ipv6/icmp.c (ffffffff81b6e07b)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78e61)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b80a38)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81b85a42)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b91c53)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b93190)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b941fd)
Location: arch/x86/include/asm/checksum_64.h:23
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
In arch/x86/lib/csum-partial_64.c (ffffffff81605836)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff816058a0)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
```
```
In net/core/skbuff.c (ffffffff819d6db9)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (ffffffff819db63f)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (ffffffff819e94ce)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff81a0943d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81a19401)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffffffff81a264f7)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81a36361)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netfilter/utils.c (ffffffff81a852d1)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81a8728d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a94743)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf7e8)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac57f5)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81aca6e2)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81acfb06)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81ad429f)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81ae1193)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff81aefc6a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff81af340c)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81aff0da)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/unix/af_unix.c (ffffffff81b21fc7)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_mkname
```
```
In net/ipv6/icmp.c (ffffffff81b5c47f)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b679d1)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f659)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81b746f2)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b80ea1)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b8222a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b8330b)
Location: arch/x86/include/asm/checksum_64.h:23
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
In arch/x86/lib/csum-partial_64.c (ffffffff81674126)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81674190)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
```
```
In net/core/skbuff.c (ffffffff81a87409)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (ffffffff81a8aeaf)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (ffffffff81a9758a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff81abb91d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81aca1b1)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffffffff81adb272)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81aec03c)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netfilter/utils.c (ffffffff81b3f9c1)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81b41a4d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/ip_output.c (ffffffff81b4fbc3)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d351)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81b84005)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81b88fbf)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e526)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81b92f8f)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81ba0833)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff81bafc7a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff81bb391c)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81bc22ba)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/unix/af_unix.c (ffffffff81be4c6f)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_mkname
```
```
In net/ipv6/icmp.c (ffffffff81c23d40)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f61d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81c37716)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81c3efdc)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81c4cebe)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e2da)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f3db)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81c7792a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81c809f4)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
```
```
In net/mptcp/options.c (ffffffff81c850ca)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In arch/x86/lib/csum-partial_64.c (ffffffff8178e7c0)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8178e840)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
```
```
In net/core/skbuff.c (ffffffff81bfcbae)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (ffffffff81c0050b)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (ffffffff81c12293)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff81c362ee)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81c46d22)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/gro.c (ffffffff81c5366a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/gro.c:__skb_gro_checksum_complete
```
```
In net/core/netpoll.c (ffffffff81c5c776)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81c6e9db)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netfilter/utils.c (ffffffff81ccc1d2)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81cd3914)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81cdd639)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d277)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81d147c3)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81d1aa2e)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81d1f746)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81d25186)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81d32d1d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff81d43242)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff81d4714d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81d52bd4)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/unix/af_unix.c (ffffffff81d803ab)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_find_other
```
```
In net/ipv6/icmp.c (ffffffff81dc0c69)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc9a5)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81dd5314)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81dd9d5f)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81ded330)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81deeb88)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81defe44)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81e1cb9a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/options.c (ffffffff81e2b1ff)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In net/core/skbuff.c (ffffffff81dabade)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (ffffffff81daf93b)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (ffffffff81dc2673)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff81de99be)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81dfb262)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/gro.c (ffffffff81e08d0a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/gro.c:__skb_gro_checksum_complete
```
```
In net/core/netpoll.c (ffffffff81e12e66)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81e2670b)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netfilter/utils.c (ffffffff81e8c0a2)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81e93b2d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81e9e0f5)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2cd9)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81eda8f3)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81ee175e)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ee6926)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81eec766)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81efafad)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff81f0c222)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff81f10072)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f1cf24)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/unix/af_unix.c (ffffffff81f4ce20)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_find_other
```
```
In net/ipv6/icmp.c (ffffffff81f912f3)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9db19)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81fa6a1d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81fab9b6)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81fc1140)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2bd8)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc3f54)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81ff402a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/options.c (ffffffff820033af)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff8204c0b0)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8204c150)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
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
In net/core/skbuff.c (ffffffff81e1b5e6)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (ffffffff81e1fbab)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (ffffffff81e3a293)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff81e5b1cd)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81e6cfe9)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/gro.c (ffffffff81e7b42a)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/gro.c:__skb_gro_checksum_complete
```
```
In net/core/netpoll.c (ffffffff81e86790)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81e9bcac)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netfilter/utils.c (ffffffff81eea0e7)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81ef2330)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81efc8c3)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f319c0)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81f399d3)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81f41170)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81f46166)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81f4c556)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81f5aa3b)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff81f6beb4)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6ea60)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff81f6fd62)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f7ca04)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/unix/af_unix.c (ffffffff81fac7a0)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_find_other
```
```
In net/ipv6/icmp.c (ffffffff81ff1bf6)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe59a)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff820071f6)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff8200c156)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff820220a6)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff82023b67)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff82024f73)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff8207063a)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/options.c (ffffffff8207f53f)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff820ca9a0)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff820caa40)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
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
In net/core/skbuff.c (ffffffff81ed8ba6)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (ffffffff81edd25b)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (ffffffff81ef85a5)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff81f1a58d)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81f2c859)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/gro.c (ffffffff81f3b6ba)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/gro.c:__skb_gro_checksum_complete
```
```
In net/core/netpoll.c (ffffffff81f4879d)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81f5e40c)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netfilter/utils.c (ffffffff81fade97)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81fb6495)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81fc0803)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7bac)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81fffac3)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff82006dc0)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8200c2a6)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff82012666)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff82020f7b)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff82032484)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035180)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv4/gre_offload.c (ffffffff82036492)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff82043104)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/unix/af_unix.c (ffffffff82079bc0)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_find_other
```
```
In net/ipv6/icmp.c (ffffffff820bf7f5)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd46d)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff820d6056)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff820db120)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff820f11c6)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff820f2cc7)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f4253)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff8214459a)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/options.c (ffffffff82154a32)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff821a51e0)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff821a5280)
Location: arch/x86/include/asm/checksum_64.h:22
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
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
In drivers/net/slip/slhc.c (ffff800010a05b5c)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
```
```
In net/core/skbuff.c (ffff800010bb8e40)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (ffff800010bbc350)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (ffff800010bc9450)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffff800010bf2a90)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffff800010bfc538)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffff800010c116c0)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffff800010c1f3bc)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netfilter/utils.c (ffff800010c56794)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffff800010c5cf78)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_input.c (ffff800010c5e100)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
```
```
In net/ipv4/ip_output.c (ffff800010c65ae8)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ea54)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffff800010c95194)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffff800010c97cf4)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9ef34)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffff800010ca0110)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffff800010ca5180)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (ffff800010caa2d4)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffff800010cae680)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffff800010cc07e4)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffff800010cc313c)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffff800010ccca94)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/xfrm/xfrm_input.c (ffff800010cea4cc)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
```
```
In net/unix/af_unix.c (ffff800010cef25c)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
```
```
In net/ipv6/icmp.c (ffff800010d2cd78)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39058)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffff800010d410cc)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffff800010d45fc8)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffff800010d539f8)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:csum_ipv6_magic
```
```
In net/ipv6/tcpv6_offload.c (ffff800010d550e0)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffff800010d56208)
Location: arch/arm64/include/asm/checksum.h:10
Inline: True
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
In block/t10-pi.c (c07c64fc)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_ip_fn
```
```
In drivers/net/slip/slhc.c (c0ae0e54)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
```
```
In net/core/skbuff.c (c0cd57dc)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (c0cd87b4)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (c0ce66d4)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (c0d0b2c8)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (c0d17320)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (c0d29438)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (c0d36f74)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netfilter/utils.c (c0d66290)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (c0d6c6fc)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_input.c (c0d6da0c)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_output.c (c0d75758)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/tcp_ipv4.c (c0d9d9d0)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (c0da38e8)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (c0da5b08)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (c0dac174)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (c0dad05c)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (c0db1a98)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (c0db6a88)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (c0dbc990)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ping.c (c0dccaf8)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (c0dce98c)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (c0dd7078)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/xfrm/xfrm_input.c (c0df25f8)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/unix/af_unix.c (c0df85a0)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_mkname
```
```
In net/ipv6/ndisc.c (c0e25034)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c0e28400)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/raw.c (c0e2e6dc)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c0e30aa8)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (c0e33874)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (c0e3ba90)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/udp_offload.c (c0e435f0)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (c0e47c14)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (c0e53fec)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (c0e555a8)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (c0e567b4)
Location: arch/arm/include/asm/checksum.h:46
Inline: True
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
In block/t10-pi.c (c0000000007be3bc)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_ip_fn
```
```
In drivers/net/slip/slhc.c (c000000000aacd2c)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
```
```
In net/core/skbuff.c (c000000000c912d8)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (c000000000c9562c)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (c000000000ca705c)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (c000000000cd86f8)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (c000000000ce4e3c)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (c000000000cfe430)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (c000000000d1127c)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/netfilter/utils.c (c000000000d572d4)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (c000000000d5f634)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_input.c (c000000000d60d3c)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_output.c (c000000000d6a298)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d8f4)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (c000000000da6130)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (c000000000da8c6c)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
```
```
In net/ipv4/udp.c (c000000000db1ca4)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (c000000000db2b9c)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (c000000000db8f64)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/af_inet.c (c000000000dc0338)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (c000000000dc6a6c)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/ping.c (c000000000ddbb58)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (c000000000dde888)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (c000000000de76a0)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/xfrm/xfrm_input.c (c000000000e0e078)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
```
```
In net/unix/af_unix.c (c000000000e17b44)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/icmp.c (c000000000e5eb14)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c9c4)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (c000000000e759d0)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (c000000000e7ba98)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (c000000000e8c294)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (c000000000e8de1c)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f414)
Location: arch/powerpc/include/asm/checksum.h:40
Inline: True
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
In net/core/skbuff.c (ffffffe0007484e2)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (ffffffe00074b090)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (ffffffe0007560f0)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffe0007744ca)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffe00077923c)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffffffe00078d8e2)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffe0007c07f0)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffe0007c5d1e)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffe0007cd224)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ef062)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f43b4)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffe0007fbe36)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffe0007fc858)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffe000800ac4)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffe00080a30a)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffe000816f4e)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffe000818544)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffe00081e306)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/unix/af_unix.c (ffffffe00083dc04)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/icmp.c (ffffffe00086d0f0)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000876750)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffe00087c822)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffe00087de60)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b6a4)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:csum_ipv6_magic
```
```
In net/ipv6/tcpv6_offload.c (ffffffe00088c918)
Location: include/asm-generic/checksum.h:54
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088db08)
Location: include/asm-generic/checksum.h:54
Inline: True
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
In net/core/skbuff.c (ffffffff818be6dd)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (ffffffff818c1cbf)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (ffffffff818cd3c0)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff818f0e30)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff818fb513)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffffffff8190aefb)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff81946c12)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff8194cd73)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81955245)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b4fc)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81980fd5)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819894a6)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8198a3b3)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff8198f19a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81999f4e)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff819a7695)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff819a9b7e)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff819af4e8)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/unix/af_unix.c (ffffffff819cf2ef)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a06586)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a1021e)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a1711d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a18712)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a267bd)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a27bc8)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28ae3)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff81a5fb26)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a5fba1)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
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
In drivers/net/vxlan.c (ffffffff81772bd4)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
```
```
In net/core/skbuff.c (ffffffff8187861d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (ffffffff8187bbff)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (ffffffff818874e0)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff818aac70)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff818b5343)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffffffff818c4c96)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff81900702)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81906863)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8190ed35)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934fbc)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff8193aa95)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81942f66)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81943e73)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81948c5a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81953a0e)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff81961155)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff8196363e)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8196bb18)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/unix/af_unix.c (ffffffff8198c0af)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff819c3346)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ccfde)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff819d3edd)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff819d54d2)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e357d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e4988)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5cd3)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff81a1cbf6)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a1cc71)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
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
In net/core/skbuff.c (ffffffff8190f6dd)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (ffffffff81912cbf)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (ffffffff8191e3c0)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff81941e60)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff8194c543)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffffffff8195bf2b)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff81997da2)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff819b7543)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff819bfa15)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5ccc)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff819eb7a5)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819f3c76)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819f4b83)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff819f9a3a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81a047ee)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff81a11f35)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff81a1441e)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a19d88)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/unix/af_unix.c (ffffffff81a39d6f)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a71006)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7ac9e)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a81b9d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a83192)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9236d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a93778)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a94693)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff81acbf16)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81acbf91)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
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
In net/core/skbuff.c (ffffffff8193080d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
```
```
In net/core/datagram.c (ffffffff81933e3f)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/core/dev.c (ffffffff8193fa50)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/utils.c (ffffffff81963760)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff8196df03)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/core/netpoll.c (ffffffff8197e30b)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff819baa82)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff819c0dd2)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff819c9394)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef98c)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5655)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819fde36)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819fed53)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81a03d2a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81a0ed6e)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff81a1c8ac)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/gre_offload.c (ffffffff81a1ee20)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a24b7a)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
```
```
In net/unix/af_unix.c (ffffffff81a463af)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a7d616)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a874de)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a8e49d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a8fa5f)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9e41d)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9f8c8)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa07f3)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff81ad8466)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81ad84e1)
Location: arch/x86/include/asm/checksum_64.h:23
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
```
</details>
</li>
</ul>

## Differences
