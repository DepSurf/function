# Function: <code>skb_dst</code>

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
In security/selinux/hooks.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In security/selinux/xfrm.c (ffffffff8135cf67)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In drivers/net/loopback.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/core/neighbour.c (ffffffff8172892e)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/core/filter.c (ffffffff81730a36)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_route_realm
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/ipv4/route.c (ffffffff817531de)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81758753)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff8175a81a)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff8175abe7)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
```
```
In net/ipv4/ip_output.c (ffffffff8175c6f0)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177e8ab)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8178a0d3)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/arp.c (ffffffff8178c3fa)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff8178e39b)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff817a73ec)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff817ac236)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff817b0165)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b3840)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc179)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff817c4c86)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/ip6_input.c (ffffffff817c8517)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff817d3aa3)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/ndisc.c (ffffffff817de9af)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff817e802b)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff817edcf9)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f05d5)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff817f34ce)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff817f85f0)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_get_route
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff817fd018)
Location: include/linux/skbuff.h:743
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/ipv6/ip6_checksum.c (0)
Location: include/linux/skbuff.h:743
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:743
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
In security/selinux/hooks.c (0)
Location: include/linux/skbuff.h:831
Inline: True
```
```
In security/selinux/xfrm.c (ffffffff813931bf)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (0)
Location: include/linux/skbuff.h:831
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/skbuff.h:831
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:831
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:831
Inline: True
```
```
In net/core/neighbour.c (ffffffff817925f6)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/core/filter.c (ffffffff8179baac)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/skbuff.h:831
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/skbuff.h:831
Inline: True
```
```
In net/ipv4/route.c (ffffffff817c3795)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff817c4a83)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff817c60c3)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff817c6b70)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff817c7724)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff817cb8be)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/skbuff.h:831
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eba39)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/skbuff.h:831
Inline: True
```
```
In net/ipv4/raw.c (ffffffff817f2b44)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff817f740d)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/arp.c (ffffffff817fa425)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff817fc87c)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/igmp.c (ffffffff81805fcd)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/fib_frontend.c (ffffffff818086a8)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff81818285)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81819669)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/skbuff.h:831
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/skbuff.h:831
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff8181d276)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81821050)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:831
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81828f9f)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff818353a4)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff818361c6)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff818415f6)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/ndisc.c (ffffffff8184f715)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81852bf5)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81854a88)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff8185709f)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/mcast.c (ffffffff81857380)
Location: include/linux/skbuff.h:831
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff8185c88a)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860985)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff81862885)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8186b205)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/skbuff.h:831
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff8186cd36)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffff8186d5ee)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/output_core.c (ffffffff81871e01)
Location: include/linux/skbuff.h:831
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
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
In security/selinux/hooks.c (0)
Location: include/linux/skbuff.h:845
Inline: True
```
```
In security/selinux/xfrm.c (ffffffff813a9ddf)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (0)
Location: include/linux/skbuff.h:845
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/skbuff.h:845
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:845
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:845
Inline: True
```
```
In net/core/neighbour.c (ffffffff817bfec6)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/core/filter.c (ffffffff817cbf1c)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/skbuff.h:845
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff817da0c5)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/skbuff.h:845
Inline: True
```
```
In net/ipv4/route.c (ffffffff817f3152)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff817f45a3)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff817f5bc3)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff817f6670)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff817f7214)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff817fb51e)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/skbuff.h:845
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c3af)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/skbuff.h:845
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81823943)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8182832f)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/arp.c (ffffffff8182b2f5)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff8182d7df)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/igmp.c (ffffffff8183704d)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81839758)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff81849ae5)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff8184af2d)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/skbuff.h:845
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/skbuff.h:845
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff8184eb39)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81852860)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:845
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff8185a97f)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81866ed4)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81867cd6)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81873456)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/ndisc.c (ffffffff81881679)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff818848f5)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff8188678e)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81888e9f)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/mcast.c (ffffffff81889180)
Location: include/linux/skbuff.h:845
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff8188e79a)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81892959)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/exthdrs.c (ffffffff81894928)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8189e065)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/skbuff.h:845
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff8189fb29)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffff818a03d9)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a4642)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/output_core.c (ffffffff818a63e1)
Location: include/linux/skbuff.h:845
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
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
In security/selinux/hooks.c (0)
Location: include/linux/skbuff.h:798
Inline: True
```
```
In security/selinux/xfrm.c (ffffffff813c07cf)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (0)
Location: include/linux/skbuff.h:798
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/skbuff.h:798
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:798
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:798
Inline: True
```
```
In net/core/neighbour.c (ffffffff817de3e7)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/core/filter.c (ffffffff817eb81e)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/skbuff.h:798
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff817f9085)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/skbuff.h:798
Inline: True
```
```
In net/ipv4/route.c (ffffffff818135e3)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81814a12)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff81815f0e)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81816a85)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff81817676)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff8181b8ff)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/skbuff.h:798
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183cb69)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/skbuff.h:798
Inline: True
```
```
In net/ipv4/raw.c (ffffffff818443d7)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff818496cd)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:798
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8184c6e2)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff8184ed3a)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/igmp.c (ffffffff8185849f)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/fib_frontend.c (ffffffff8185acc8)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff8186d34c)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff8186e9ac)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/skbuff.h:798
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/skbuff.h:798
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff818726db)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81875990)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:798
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff8187e90f)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_device.c (ffffffff8188015f)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff8188b684)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8188c4e6)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81897e26)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/ndisc.c (ffffffff818a7709)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff818aaba3)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff818acae9)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff818af585)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/mcast.c (ffffffff818af810)
Location: include/linux/skbuff.h:798
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff818b4e41)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8f0a)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffffffff818bace7)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff818c4667)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/skbuff.h:798
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff818c613b)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffff818c6a20)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818cae54)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/output_core.c (ffffffff818cce31)
Location: include/linux/skbuff.h:798
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
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
In security/selinux/hooks.c (0)
Location: include/linux/skbuff.h:878
Inline: True
```
```
In security/selinux/xfrm.c (ffffffff813e696f)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (0)
Location: include/linux/skbuff.h:878
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/skbuff.h:878
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:878
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/skbuff.h:878
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:878
Inline: True
```
```
In net/core/neighbour.c (ffffffff81858c49)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/core/filter.c (ffffffff818664de)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/skbuff.h:878
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81876985)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/skbuff.h:878
Inline: True
```
```
In net/ipv4/route.c (ffffffff81892c33)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81893bb5)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff8189511a)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81895c45)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff818967ac)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff8189a835)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/skbuff.h:878
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc262)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/skbuff.h:878
Inline: True
```
```
In net/ipv4/raw.c (ffffffff818c3d15)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff818c90ef)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:878
Inline: True
```
```
In net/ipv4/arp.c (ffffffff818cc398)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff818ceac0)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/igmp.c (ffffffff818d836f)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/fib_frontend.c (ffffffff818dabf8)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff818edc5c)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff818ef36c)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/skbuff.h:878
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2995)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffffffff818f30db)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f6085)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff818ff446)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff818ff96f)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_device.c (ffffffff8190127f)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff8190c924)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8190d7d6)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff819191a6)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
```
```
In net/ipv6/ndisc.c (ffffffff8192a174)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff8192d5d1)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff8192f346)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff8193229b)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/mcast.c (ffffffff81932530)
Location: include/linux/skbuff.h:878
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81937bb1)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193be17)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffffffff8193dcf7)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81947907)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/skbuff.h:878
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff819494db)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffff81949e57)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e794)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8194efe5)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/output_core.c (ffffffff81951c11)
Location: include/linux/skbuff.h:878
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
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
In security/selinux/hooks.c (ffffffff813fe3c6)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (ffffffff814176bf)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (ffffffff817345be)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff8187691e)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8187bd85)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (ffffffff818885a7)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff81895917)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff818a4095)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff818b5005)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (ffffffff818c7a55)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (ffffffff818c8065)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff818e14da)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff818e6cb0)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff818e7e33)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff818e92c8)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff818e9f05)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff818ea9c9)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff818eed08)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f16ef)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911ee8)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912e7b)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (ffffffff8191991d)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8191f242)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81920666)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff8192275c)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (ffffffff81924e8f)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/igmp.c (ffffffff8192ee20)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81931b75)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff819439e8)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81945d0c)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81948c27)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_input.c (ffffffff8194946a)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffffffff819499aa)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194c272)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81955f79)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819563ef)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_device.c (ffffffff81958105)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff81960168)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81964ba8)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81970935)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff81982428)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81985f79)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81987d28)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff8198abe9)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8198c570)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/reassembly.c (ffffffff81990997)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994f70)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffffffff819960c5)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819a096d)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a1339)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/xfrm6_output.c (ffffffff819a257a)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffff819a2dd0)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7a96)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819a82f5)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/output_core.c (ffffffff819ab1a1)
Location: include/linux/skbuff.h:882
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
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
In security/selinux/hooks.c (ffffffff8141a256)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (ffffffff81433bef)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (ffffffff81757716)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff818987ae)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8189bfe5)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (ffffffff818a90f7)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff818b75e8)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff818c7503)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff818dabe5)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (ffffffff818f0bb5)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (ffffffff818f11d5)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff8190e086)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff81913b67)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819154b2)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff819163b3)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81917486)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff81917739)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff8191c4c0)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191f24f)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819406b1)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81941638)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (ffffffff819481f8)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8194deb0)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8194f49d)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff8195156e)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (ffffffff81953d12)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff8195e27e)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/fib_frontend.c (ffffffff819613d5)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff81973b58)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff8197602c)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8197a8f7)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b12f)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b66a)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81983053)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a998)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b06f)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_device.c (ffffffff8198ca65)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff81994f48)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8199a006)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff819a6565)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff819b8ad8)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819bc843)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff819be686)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c14b6)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c2ce3)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/reassembly.c (ffffffff819c70d8)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb853)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffffffff819cc9d5)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819d756d)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d7f7b)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/xfrm6_output.c (ffffffff819d91ea)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffff819d9a0d)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de5e6)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819dee45)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/output_core.c (ffffffff819e1cc1)
Location: include/linux/skbuff.h:906
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
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
In security/selinux/hooks.c (ffffffff81447cdf)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (ffffffff81461681)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (ffffffff81793ece)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff818e2d55)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818e689d)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (ffffffff818f4857)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff8190341d)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81913bd5)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81927655)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (ffffffff81942585)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (ffffffff81943758)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff8196fb3b)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff81976218)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819779e6)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81978d07)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff819793cd)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff81979e4a)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff8197e7fb)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81981b9f)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4bec)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5c39)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (ffffffff819ad29d)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819b26a2)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff819b3cd3)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff819b5e26)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (ffffffff819b8623)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff819c3649)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/fib_frontend.c (ffffffff819c5bb5)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff819dd667)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff819dfbbd)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e4640)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e4b9b)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e852b)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819f5641)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819f5c6d)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff819f8065)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/af_inet6.c (ffffffff819fe6c2)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_route_input
```
```
In net/ipv6/ip6_output.c (ffffffff81a009e8)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a05f59)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81a12d05)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff81a2758e)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a2b38a)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a2e196)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a30297)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a31bab)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/reassembly.c (ffffffff81a363e7)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a270)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffffffff81a3b4b5)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a4660d)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a47a6b)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffff81a4827c)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4d156)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a4d9b5)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/output_core.c (ffffffff81a50a82)
Location: include/linux/skbuff.h:926
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
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
In security/selinux/hooks.c (ffffffff8146186f)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (ffffffff8147b431)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (ffffffff817b79fe)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81914f35)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819189e5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (ffffffff81926807)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff819361cd)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81946245)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81959d15)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (ffffffff819774b5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (ffffffff81978751)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff819a6566)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819acc28)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819ae376)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff819af677)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff819afd68)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff819b07aa)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff819b519b)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b83df)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db8ec)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc9f9)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (ffffffff819e3f5d)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819e9442)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff819eaa03)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff819ecb46)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (ffffffff819ef323)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff819fa1e9)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/fib_frontend.c (ffffffff819fc765)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff81a14797)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81a16bed)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b650)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1bbbb)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1f53b)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2c2f1)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2c8ed)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2ecb5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/af_inet6.c (ffffffff81a352b2)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_route_input
```
```
In net/ipv6/ip6_output.c (ffffffff81a375bb)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a3cac9)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81a498f5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff81a5dfee)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a61eea)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a63c27)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a66de7)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a686fb)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/reassembly.c (ffffffff81a6cf07)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70e11)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffffffff81a72135)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a7d1fd)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a7e61b)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffff81a7ee2c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83d26)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a84585)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/output_core.c (ffffffff81a876a2)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
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
In security/selinux/hooks.c (ffffffff814b4e04)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (ffffffff814d09e1)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (ffffffff8187eb3e)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff819e8055)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb70d)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (ffffffff819fac24)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff81a009c3)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81a1669b)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81a2d4e5)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (ffffffff81a4c2a5)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (ffffffff81a4d592)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff81a8f809)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81a9672c)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81a97910)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81a9950b)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81a99c0d)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff81a9a625)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff81a9f237)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa2cf6)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5d45)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9ad8)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (ffffffff81ad090f)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ad7463)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ad8620)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81adab16)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (ffffffff81add275)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81ae89ec)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeb4d5)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff81b05717)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81b07c38)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c6ed)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b0ca3c)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81b0cda8)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15cae)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e67d)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1fac8)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/xfrm/xfrm_device.c (ffffffff81b217a5)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/af_inet6.c (ffffffff81b2a262)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_route_input
```
```
In net/ipv6/ip6_output.c (ffffffff81b2cae2)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b32169)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81b40335)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff81b56dbd)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b578d7)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b5c6a6)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5f874)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b619f9)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/reassembly.c (ffffffff81b66450)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a6a3)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffffffff81b6bce5)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b77ba9)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b790bb)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b79450)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81b79a7c)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7eaf6)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f5e5)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/output_core.c (ffffffff81b82ab2)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/mptcp/subflow.c (ffffffff81bae2e4)
Location: include/linux/skbuff.h:954
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
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
In security/selinux/hooks.c (ffffffff814d2a95)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (ffffffff814edef1)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (ffffffff8188d0be)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff819e7cc5)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb42d)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (ffffffff819fa834)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff81a00dd3)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81a16727)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81a2ed85)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (ffffffff81a51ef5)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (ffffffff81a53254)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/sched/sch_frag.c (ffffffff81a6f3e8)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81a997f9)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81aa07d2)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81aa1870)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa347b)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81aa3b5d)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff81aa4585)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff81aa9177)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aad006)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1bd5)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5a28)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (ffffffff81adc92b)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ae3ab3)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5b36)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81ae75b6)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (ffffffff81ae9fc5)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81af58ec)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81af83d5)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06bca)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/ipmr.c (ffffffff81b13937)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81b1601c)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1aa0d)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b1ad6c)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81b1b0e8)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b2411e)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2cf4d)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e3d8)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30175)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/af_inet6.c (ffffffff81b38bc2)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_route_input
```
```
In net/ipv6/ip6_output.c (ffffffff81b3b4f2)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b40d89)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81b4ed15)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff81b6542d)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b65de7)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b6aee6)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b6e014)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b7019a)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/reassembly.c (ffffffff81b74a72)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b790f4)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffffffff81b7a755)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b86b29)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b8803b)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b883e7)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81b889ca)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8db06)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b8e675)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/output_core.c (ffffffff81b92122)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/mptcp/subflow.c (ffffffff81bc1354)
Location: include/linux/skbuff.h:961
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
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
In security/selinux/hooks.c (ffffffff814d8ff5)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (ffffffff814f4c61)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (ffffffff8186f9fe)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff819cdc95)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819d193d)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (ffffffff819e0a24)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff819e7581)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff819fd330)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81a16db5)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (ffffffff81a377f5)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (ffffffff81a38a82)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/sched/sch_frag.c (ffffffff81a57cbb)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81a84b09)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81a8b702)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81a8d4ff)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e5e8)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81a8eab5)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff81a8f69f)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff81a944ec)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a98256)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abcbe5)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac0a87)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (ffffffff81ac7967)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81aceca3)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0e26)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81ad2876)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (ffffffff81ad5697)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/igmp.c (ffffffff81ae1048)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae3af5)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af22e7)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/gre_offload.c (ffffffff81af2efc)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81b01777)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81b03eaf)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b086bd)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b089d5)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81b08d98)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11d4e)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1ab90)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1be48)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1deb5)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/af_inet6.c (ffffffff81b268b2)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_route_input
```
```
In net/ipv6/ip6_output.c (ffffffff81b28c70)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b2eca9)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81b3cb45)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff81b5371e)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
```
```
In net/ipv6/udp.c (ffffffff81b53e91)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b591f8)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5c3dd)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b5cc10)
Location: include/linux/skbuff.h:967
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81b635a4)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67c32)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffffffff81b691a7)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b757ed)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b76a75)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b77117)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81b777d7)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c9d6)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7d735)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/output_core.c (ffffffff81b814a2)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/mptcp/subflow.c (ffffffff81bb1d04)
Location: include/linux/skbuff.h:967
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
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
In security/selinux/hooks.c (ffffffff815320f1)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (ffffffff8154f661)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (ffffffff818fff9e)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81a7d475)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81a8150d)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (ffffffff81a90da4)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff81a98497)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81aaf6bf)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81ac8245)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/lwtunnel.c (ffffffff81aed585)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (ffffffff81aee962)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_frag.c (ffffffff81b10c86)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f121)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81b46642)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81b486c3)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81b497d8)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81b49cc4)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff81b4a8df)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff81b4f96c)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b536b0)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b79975)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e44b)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (ffffffff81b861c4)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81b8d7df)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f843)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81b914c6)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (ffffffff81b944d3)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/igmp.c (ffffffff81ba06e8)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba3405)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81bb0667)
Location: include/linux/skbuff.h:977
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb27f7)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/gre_offload.c (ffffffff81bb340c)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81bc34f7)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81bc6188)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb5ca)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffffffff81bcb8d5)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81bcbc88)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd58cc)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdf237)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be05f8)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
```
```
In net/xfrm/xfrm_device.c (ffffffff81be29a5)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/af_inet6.c (ffffffff81bec3a2)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_route_input
```
```
In net/ipv6/ip6_output.c (ffffffff81beeb60)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4fd9)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81c034e5)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff81c1ac2e)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
```
```
In net/ipv6/udp.c (ffffffff81c1d343)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81c20802)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81c23b1b)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81c24460)
Location: include/linux/skbuff.h:977
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81c2b064)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f87c)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffffffff81c30b27)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ioam6.c (ffffffff81c38f5b)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff81c401fd)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c414d5)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81c41bb7)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81c422d1)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47db1)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81c48105)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4c0a5)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/output_core.c (ffffffff81c4d4c2)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/mptcp/subflow.c (ffffffff81c7fd91)
Location: include/linux/skbuff.h:977
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
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
In security/selinux/hooks.c (ffffffff815c94e2)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (ffffffff815e8965)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (ffffffff81a51a63)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81bf00c2)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81bf5253)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (ffffffff81c06e3b)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff81c19ab1)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81c28617)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81c4586e)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/gro.c (ffffffff81c53c5b)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/core/lwtunnel.c (ffffffff81c70415)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (ffffffff81c7198f)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_frag.c (ffffffff81c97e04)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81ccb85f)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81cd354a)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81cd5a7e)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6dcb)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81cd7295)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff81cd7720)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff81cdd3eb)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ce1104)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d096f5)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e43b)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (ffffffff81d16b19)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81d1e93e)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81d20b3d)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81d22822)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (ffffffff81d25b35)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/igmp.c (ffffffff81d32bbb)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81d35c65)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81d43b61)
Location: include/linux/skbuff.h:1267
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45fc0)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/gre_offload.c (ffffffff81d46c27)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81d58327)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81d5b489)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d61077)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffffffff81d61443)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81d61811)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6c16a)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81d75fc6)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77637)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_device.c (ffffffff81d79af5)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/af_inet6.c (ffffffff81d84902)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_route_input
```
```
In net/ipv6/ip6_output.c (ffffffff81d871e0)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81d8de27)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81d9d4a5)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff81db7222)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81db99a3)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81dbd580)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81dc0a36)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81dc30d0)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81dc8309)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dccced)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffffffff81dd04e8)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ioam6.c (ffffffff81dd700b)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff81dde805)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_output.c (ffffffff81de0013)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81de0473)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81de0b46)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de724f)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81de7605)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81dec07d)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
```
```
In net/ipv6/output_core.c (ffffffff81deda31)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/mptcp/subflow.c (ffffffff81e2578e)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
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
In security/selinux/hooks.c (ffffffff816766d2)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (ffffffff816981a5)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (ffffffff81bdaca3)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81d9c2de)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81da3773)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (ffffffff81db76b2)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff81dcaa66)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:tun_dst_unclone
```
```
In net/core/neighbour.c (ffffffff81ddb234)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81df9a1e)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/gro.c (ffffffff81e08f7a)
Location: include/linux/skbuff.h:1109
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff81e283b5)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (ffffffff81e29a7f)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_frag.c (ffffffff81e53da4)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b6af)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81e93746)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81e95f0e)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81e9735b)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81e978b6)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff81e97da0)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff81e9deaa)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea1514)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ece9c5)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3eeb)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (ffffffff81edd1e4)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ee5a6c)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7dc2)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81ee9d7e)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (ffffffff81eed3f5)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/igmp.c (ffffffff81efae4b)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81efe255)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81f0cce9)
Location: include/linux/skbuff.h:1109
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f3a0)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/gre_offload.c (ffffffff81f10477)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f227e7)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81f25919)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2b967)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffffffff81f2bd63)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81f2c191)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f374ca)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42706)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f43edb)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_device.c (ffffffff81f468e5)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/af_inet6.c (ffffffff81f52272)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_route_input
```
```
In net/ipv6/ip6_output.c (ffffffff81f54d00)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81f5bf97)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81f6c415)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff81f86ef2)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81f89a33)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81f8dabf)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffffffff81f9125d)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81f93a11)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81f99099)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9ddfb)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffffffff81fa1878)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ioam6.c (ffffffff81fa89c6)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff81fb0a35)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb2353)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81fb2803)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81fb2f86)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fba0e8)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81fba585)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfccd)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
```
```
In net/ipv6/output_core.c (ffffffff81fc1901)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/mptcp/subflow.c (ffffffff81ffd3de)
Location: include/linux/skbuff.h:1109
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
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
In security/selinux/hooks.c (ffffffff816ae9f2)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (ffffffff816d0671)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (ffffffff81c3175a)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81e0ab7d)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81e1236c)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (ffffffff81e27fee)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff81e3b677)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:tun_dst_unclone
```
```
In net/core/neighbour.c (ffffffff81e4c194)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81e6b8fa)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/gro.c (ffffffff81e7b84a)
Location: include/linux/skbuff.h:1119
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff81e9d9d5)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (ffffffff81e9f0c0)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_frag.c (ffffffff81eaf624)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81ee96ff)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81ef1eee)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81ef474e)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef5b8b)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81ef60f3)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff81ef6600)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff81efc674)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81effd20)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2d975)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32ee8)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (ffffffff81f3c434)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81f4525b)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81f4762a)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81f496e2)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (ffffffff81f4cdb5)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/igmp.c (ffffffff81f5a8dd)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5dce5)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81f6c960)
Location: include/linux/skbuff.h:1119
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f090)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/gre_offload.c (ffffffff81f70167)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f82317)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81f854a9)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b7c1)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffffffff81f8ba03)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81f8be31)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f96e19)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1f12)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa30f5)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6225)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/af_inet6.c (ffffffff81fb1c82)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_route_input
```
```
In net/ipv6/ip6_output.c (ffffffff81fb471a)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81fbbd47)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81fcc555)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff81fe7232)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81fe92e1)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81fee298)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffffffff81ff1b90)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81ff436b)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/reassembly.c (ffffffff81ff9a69)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe65f)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffffffff820020ea)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ioam6.c (ffffffff82009356)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff820110e5)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_output.c (ffffffff82012a63)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff82012f13)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff82013676)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a818)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8201acb5)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:end_flv8986_core
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020c5d)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
```
```
In net/ipv6/output_core.c (ffffffff82022881)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/mptcp/subflow.c (ffffffff820796ae)
Location: include/linux/skbuff.h:1119
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
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
In security/selinux/hooks.c (ffffffff816eba33)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (ffffffff8170cc91)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (ffffffff81ce45da)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81ec756d)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81ecf52c)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (ffffffff81ee6071)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff81ef9a32)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:tun_dst_unclone
```
```
In net/core/neighbour.c (ffffffff81f0aea1)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81f2aa4a)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/gro.c (ffffffff81f3baca)
Location: include/linux/skbuff.h:1126
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff81f60155)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (ffffffff81f61830)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_frag.c (ffffffff81f720a4)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81fad46f)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81fb603e)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81fb86ce)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9b3b)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81fba083)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff81fba590)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff81fc05b4)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc3ea7)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff2605)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_ao_sign_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:__inet_lookup_skb
  - net/ipv4/tcp_ipv4.c:__inet_lookup_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff9038)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (ffffffff8200255e)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff8200b2ec)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8200d76a)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff8200f836)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (ffffffff82012ec5)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/igmp.c (ffffffff82020e1d)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff820242a5)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff820330b0)
Location: include/linux/skbuff.h:1126
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff820357c0)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/gre_offload.c (ffffffff82036897)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff82048997)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv4/netfilter.c (ffffffff8204bb83)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_input.c (ffffffff820530c1)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffffffff82053303)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff82053731)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff820641b4)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f140)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff82070775)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
```
```
In net/xfrm/xfrm_device.c (ffffffff82073535)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/af_inet6.c (ffffffff8207f3a2)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_route_input
```
```
In net/ipv6/ip6_output.c (ffffffff82081fca)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff82089177)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/route.c (ffffffff82099d35)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff820b5091)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff820b5df3)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff820bbe6c)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffffffff820bf78f)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff820c0320)
Location: include/linux/skbuff.h:1126
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff820c76d9)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ccf7f)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:__inet6_lookup_skb
```
```
In net/ipv6/exthdrs.c (ffffffff820d0eea)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ioam6.c (ffffffff820d82f6)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff820e0075)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_output.c (ffffffff820e1bc3)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff820e2073)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff820e27d9)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e97d8)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff820e9c75)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:end_flv8986_core
  - net/ipv6/seg6_local.c:input_action_end_x_core
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820efd8d)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
```
```
In net/ipv6/output_core.c (ffffffff820f19a1)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/mptcp/subflow.c (ffffffff8214eafe)
Location: include/linux/skbuff.h:1126
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
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
In security/selinux/hooks.c (ffff80001054efe0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (ffff80001056bd7c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (ffff8000109d025c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffff800010badd2c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffff800010bb4790)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (ffff800010bc2b7c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffff800010bd484c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffff800010be6398)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffff800010bff9f4)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (ffff800010c1dec0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (ffff800010c1f3f8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffff800010c55de8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffff800010c5ccf8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffff800010c5e87c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffff800010c5fe8c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffff800010c60420)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffff800010c60db8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffff800010c6595c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffff800010c69788)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8bb0c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f964)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (ffff800010c98930)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffff800010c9ed04)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffff800010ca057c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffff800010ca2640)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (ffff800010ca5114)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffff800010cb183c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/fib_frontend.c (ffff800010cb4bb0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffff800010ccf9a0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffff800010cd2830)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd78c8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7e80)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdb4e0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffff800010ceaf68)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010ceb55c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffff800010cedb0c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/af_inet6.c (ffff800010cf5bc8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_route_input
```
```
In net/ipv6/ip6_output.c (ffff800010cf8c44)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffff800010cfde2c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffff800010d12088)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffff800010d230a0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffff800010d26edc)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffff800010d29c8c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffff800010d2cd40)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffff800010d2d2e0)
Location: include/linux/skbuff.h:922
Inline: True
```
```
In net/ipv6/reassembly.c (ffff800010d35a70)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d3931c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffff800010d3b28c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffff800010d47ea8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_forward2_finish
  - net/ipv6/ip6mr.c:ip6mr_forward2_finish
  - net/ipv6/ip6mr.c:ip6mr_forward2_finish
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_output.c (ffff800010d49ad0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffff800010d4a780)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4fa88)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffff800010d50538)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/output_core.c (ffff800010d53f7c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
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
In security/selinux/hooks.c (c07089b0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (c071f6a0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (c0ab8478)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (c0ccb834)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c0cd0544)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (c0cddeb0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (c0ceee10)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (c0cfe95c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (c0d15c30)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (c0d35ae8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (c0d3704c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (c0d657e0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (c0d6c464)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (c0d6df3c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (c0d6f4e4)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (c0d6fc28)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (c0d7077c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (c0d755a8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (c0d789bc)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (c0d9c24c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (c0d9ea24)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (c0da5c78)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c0dabf78)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (c0dad7cc)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (c0daf450)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (c0db1a2c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (c0dbd434)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/fib_frontend.c (c0dc054c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (c0dda014)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (c0ddc73c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_input.c (c0de1444)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (c0de1958)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (c0dea29c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (c0df2e94)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c0df3438)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (c0df5bd0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/af_inet6.c (c0dfc67c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_route_input
```
```
In net/ipv6/ip6_output.c (c0dfead0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c0e058b8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (c0e12f04)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (c0e276f4)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c0e28354)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (c0e2da5c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c0e30da4)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c0e339f8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/reassembly.c (c0e37dd4)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (c0e3be9c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (c0e3d06c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (c0e49908)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_output.c (c0e4add0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (c0e4b648)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (c0e507cc)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c0e510dc)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/output_core.c (c0e54730)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
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
In security/selinux/hooks.c (c0000000006b028c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (c0000000006cfd58)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (c000000000a8f16c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (c000000000c83730)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c000000000c8675c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (c000000000c9cb58)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (c000000000cb3928)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (c000000000cc794c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (c000000000ce3eac)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (c000000000d0f5bc)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (c000000000d112e0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (c000000000d56544)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (c000000000d5f2d0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (c000000000d61198)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (c000000000d62c40)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (c000000000d63380)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (c000000000d64030)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (c000000000d6a0b8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (c000000000d6e4a0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (c000000000d97308)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e98c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (c000000000daa0dc)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c000000000db1564)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (c000000000db2d5c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (c000000000db5c70)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (c000000000db8e50)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (c000000000dc86e8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/fib_frontend.c (c000000000dcbdcc)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (c000000000dedaf8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (c000000000df0ed0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_input.c (c000000000df7794)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (c000000000df7f64)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (c000000000e00500)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (c000000000e0eb80)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c000000000e0f350)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (c000000000e12460)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/af_inet6.c (c000000000e1c17c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_route_input
```
```
In net/ipv6/ip6_output.c (c000000000e1f0f4)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c000000000e260d8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (c000000000e380b0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (c000000000e52fe0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c000000000e57cd0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (c000000000e5aacc)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c000000000e5e834)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c000000000e5ef14)
Location: include/linux/skbuff.h:922
Inline: True
```
```
In net/ipv6/reassembly.c (c000000000e67bac)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c8fc)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (c000000000e6dfe0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (c000000000e7d318)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_output.c (c000000000e7f244)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (c000000000e80058)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e87240)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c000000000e8809c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/output_core.c (c000000000e8c964)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
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
In security/selinux/hooks.c (ffffffe0003a8f58)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (ffffffe0003c09d0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (ffffffe00061ccec)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffe00073fe0a)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffe000742502)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (ffffffe00074f8a4)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffe00075e65c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffe00076ad0e)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffe00077df9a)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (ffffffe0007979d2)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (ffffffe000798afa)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffe0007c0126)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffe0007c5b08)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffe0007c6f6e)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c7f80)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffe0007c86b0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffe0007c8fac)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffe0007cd0ae)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf5ee)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eef4a)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efca8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (ffffffe0007f69de)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_rcv
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffe0007fb83e)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffe0007fcc3c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffe0007fe58e)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (ffffffe000800a1e)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffe00080a272)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/fib_frontend.c (ffffffe00080c762)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffe000821b7a)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffe000823b52)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_input.c (ffffffe000827ffa)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffffffe000828442)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082cdf2)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffe000838650)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffe000838f46)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b0c4)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/af_inet6.c (ffffffe00084169a)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_route_input
```
```
In net/ipv6/ip6_output.c (ffffffe000843602)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffe00084829c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffe000854066)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffe000864afc)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffe000868e46)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffe00086a4ac)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffe00086cf9c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffe00086d39e)
Location: include/linux/skbuff.h:922
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffe000872f22)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087667e)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffffffe00087770c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffe000881a74)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_output.c (ffffffe000882e8a)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffe000883658)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe0008881ca)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffe000888b2e)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/output_core.c (ffffffe00088ba8a)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
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
In security/selinux/hooks.c (ffffffff81459e4f)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (ffffffff81473a11)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (ffffffff8177c4d6)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff818b4f35)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818b89e5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (ffffffff818c6807)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff818d619d)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff818e6215)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff818f9ce5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (ffffffff81917325)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (ffffffff819185c1)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff819463d6)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff8194ca98)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff8194e1e6)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff8194f4e7)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff8194fbd8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff8195061a)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff8195500b)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff8195824f)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b75c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c869)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (ffffffff81983dcd)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819892b2)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8198a873)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff8198c92e)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (ffffffff8198f0c3)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81999f89)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/fib_frontend.c (ffffffff8199c505)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff819b3e57)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff819b627d)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_input.c (ffffffff819bace0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb24b)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bebcb)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb981)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819cbf7d)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce345)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/af_inet6.c (ffffffff819d4942)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_route_input
```
```
In net/ipv6/ip6_output.c (ffffffff819d6c4b)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff819dc159)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff819e8f85)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff819fd67e)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a0157a)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a032b7)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a06477)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a07d8b)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/reassembly.c (ffffffff81a0c597)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a104a1)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffffffff81a117c5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a1c88d)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a1dcab)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffff81a1e4bc)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a233b6)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a23c15)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/output_core.c (ffffffff81a26d32)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
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
In security/selinux/hooks.c (ffffffff8144a87f)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (ffffffff81464431)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (ffffffff8175c286)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/vxlan.c (ffffffff81770395)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fill_metadata_dst
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/core/sock.c (ffffffff8186ee85)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81872935)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (ffffffff81880747)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff8188ffdd)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff818a0055)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff818b3b15)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (ffffffff818d10d5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (ffffffff818d2371)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff818ffec6)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff81906588)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81907cd6)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81908fd7)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff819096c8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff8190a10a)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff8190eafb)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81911d3f)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193521c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81936329)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (ffffffff8193d88d)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81942d72)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81944333)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff819463ee)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (ffffffff81948b83)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81953a49)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81955fc5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967354)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
```
```
In net/ipv4/ipmr.c (ffffffff81970487)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff8197306d)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977ad0)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197803b)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197b9bb)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81988771)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81988d6d)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b135)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/af_inet6.c (ffffffff81991702)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_route_input
```
```
In net/ipv6/ip6_output.c (ffffffff81993a0b)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81998f19)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff819a5d45)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff819ba43e)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819be33a)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff819c0077)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c3237)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c4b4b)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/reassembly.c (ffffffff819c9357)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd261)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffffffff819ce585)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819d964d)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_output.c (ffffffff819daa6b)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffff819db27c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819e0176)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819e09d5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/output_core.c (ffffffff819e3af2)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_udp_tunnel.c (ffffffff819e5b44)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_udp_tunnel.c:udp_tunnel6_xmit_skb
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
In security/selinux/hooks.c (ffffffff81455eef)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (ffffffff8146fab1)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (ffffffff817ac87e)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81905f35)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819099e5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (ffffffff81917807)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff819271cd)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81937245)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff8194ad15)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (ffffffff819684b5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (ffffffff81969751)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff81997566)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819b7268)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819b89b6)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9cb7)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff819ba3a8)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff819badea)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff819bf7db)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c2a1f)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5f2c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e7039)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (ffffffff819ee59d)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819f3a82)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff819f5043)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff819f7186)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (ffffffff819f9963)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81a04829)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81a06da5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff81a1e6f7)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81a20b1d)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a25760)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25ccb)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2964b)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a36401)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a369fd)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81a38dc5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/af_inet6.c (ffffffff81a3f3c2)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_route_input
```
```
In net/ipv6/ip6_output.c (ffffffff81a416cb)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a46bd9)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81a53a05)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff81a680fe)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a6bffa)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a6dd37)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a70ef7)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a7280b)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/reassembly.c (ffffffff81a77017)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7af21)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffffffff81a7c245)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a8730d)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a8872b)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffff81a88f3c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8de36)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a8e695)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/output_core.c (ffffffff81a928e2)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
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
In security/selinux/hooks.c (ffffffff814711df)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/xfrm.c (ffffffff81487321)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid
```
```
In drivers/net/loopback.c (ffffffff817c680e)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81926f65)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8192aae5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/flow_dissector.c (ffffffff81938a17)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff81948837)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81958a20)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff8196c625)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_get_route_realm
```
```
In net/core/lwtunnel.c (ffffffff8198a7d5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_input
  - net/core/lwtunnel.c:lwtunnel_xmit
  - net/core/lwtunnel.c:lwtunnel_output
```
```
In net/core/lwt_bpf.c (ffffffff8198bb31)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_output
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff819ba246)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819c0aed)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819c2229)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff819c36f5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff819c3c98)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (ffffffff819c46f2)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff819c9157)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cc41f)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819efbec)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0d07)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/raw.c (ffffffff819f85fd)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819fdc42)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff819ff24b)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81a013a6)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_error_report
```
```
In net/ipv4/icmp.c (ffffffff81a03c53)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81a0eda9)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81a11455)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff81a29a87)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81a2c051)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30be2)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a3116c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a34bdb)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41d52)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a4236e)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81a447e5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/af_inet6.c (ffffffff81a4aec2)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_route_input
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d32b)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a5294a)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81a5f9f5)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff81a746ee)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_error_report
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a7860a)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a7a357)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a7d507)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a7ee8d)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/reassembly.c (ffffffff81a83637)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87765)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/exthdrs.c (ffffffff81a88a95)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a93edd)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a9537c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffff81a95b9c)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9ab66)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a9b405)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
```
In net/ipv6/output_core.c (ffffffff81a9e9e2)
Location: include/linux/skbuff.h:922
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:__ip6_local_out
```
</details>
</li>
</ul>

## Differences
