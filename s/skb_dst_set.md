# Function: <code>skb_dst_set</code>

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
In net/core/dev.c (ffffffff81714273)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81731bc2)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81755612)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_options.c (ffffffff8175b3f8)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8175f358)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81774b31)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff8178512d)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8178aa4c)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff8178c319)
Location: include/linux/skbuff.h:762
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8178e357)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/igmp.c (ffffffff81796219)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a47cc)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff817a7401)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff817ac232)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b5f76)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc32c)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff817c4b35)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/route.c (ffffffff817d70ed)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff817debf8)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/raw.c (ffffffff817e613e)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff817ea4ba)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817ef1e2)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff817f8602)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/netfilter.c (ffffffff817fdca8)
Location: include/linux/skbuff.h:762
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/dev.c (ffffffff8177c08a)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff8179ce26)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff817c36d6)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_options.c (ffffffff817c7700)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff817cb5e8)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_output.c (ffffffff817e1aaf)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff817f2729)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff817f8092)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff817f9949)
Location: include/linux/skbuff.h:850
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff817fb959)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/igmp.c (ffffffff8180484c)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81812472)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff818150ed)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81819674)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff8182322e)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff8182924b)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81835209)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff8184277b)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff8184f934)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff818545b2)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff818596c3)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185dae6)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff81867de2)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/netfilter.c (ffffffff8186d5e5)
Location: include/linux/skbuff.h:850
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/dev.c (ffffffff817a981a)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff817cae36)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff817f2cf2)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
```
```
In net/ipv4/ip_options.c (ffffffff817f71f0)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff817fb248)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81811faf)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff81823578)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81828f32)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff8182a819)
Location: include/linux/skbuff.h:864
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8182c864)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/igmp.c (ffffffff81835821)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8184399b)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff818468ad)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff8184af38)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81854b7e)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff8185ac2b)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81866d47)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff818744fa)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff818818b3)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff818862d7)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff8188b4f3)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8188fb7c)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff8189ac42)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/netfilter.c (ffffffff818a03d0)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a4692)
Location: include/linux/skbuff.h:864
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/core/dev.c (ffffffff817c7e43)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff817e9f3c)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81813622)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_options.c (ffffffff818175c9)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8181b5d8)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_output.c (ffffffff818322ff)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff818441f5)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8184ba2c)
Location: include/linux/skbuff.h:817
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8184dc45)
Location: include/linux/skbuff.h:817
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81856d55)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818651fa)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff818695d1)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff8186e9b3)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff818786db)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff8187ea42)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff8188b3fa)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81899336)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff818a798d)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff818aca43)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff818b1279)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b6222)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff818c1577)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/netfilter.c (ffffffff818c6a17)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818caeaa)
Location: include/linux/skbuff.h:817
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
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
In net/core/dev.c (ffffffff818419d7)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff818655cc)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81892c7c)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_options.c (ffffffff81896789)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8189a50e)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_output.c (ffffffff818b142f)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff818c3b41)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff818cb6b6)
Location: include/linux/skbuff.h:897
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff818cd955)
Location: include/linux/skbuff.h:897
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff818d6c05)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e535a)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff818e9c1e)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff818ef373)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f9008)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffad4)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff8190c64a)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff8191d95e)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff8192a430)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff8192f2a0)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff819338c9)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81938fb8)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff819448cf)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/netfilter.c (ffffffff81949e4a)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e7ea)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff8194f2de)
Location: include/linux/skbuff.h:897
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:lookup_nexthop
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
In net/core/dev.c (ffffffff8188be48)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff818b30ca)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff818e6e3a)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_options.c (ffffffff818eaa60)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff818ee9c4)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81906c6f)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff8191979c)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81921b8d)
Location: include/linux/skbuff.h:901
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81923d5b)
Location: include/linux/skbuff.h:901
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8192d558)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193bc28)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff819402f4)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81945d28)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194fa74)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff819566d6)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81963aec)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81972752)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff8198264d)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81987c86)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff8198c23d)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8199293c)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff8199d5ff)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/netfilter.c (ffffffff819a2dbf)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7ad0)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff819a8d63)
Location: include/linux/skbuff.h:901
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/dev.c (ffffffff818ad028)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff818d7f1a)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81913cf5)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_options.c (ffffffff819177d8)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8191c164)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81934e3f)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff8194807a)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819509ad)
Location: include/linux/skbuff.h:925
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81952b45)
Location: include/linux/skbuff.h:925
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8195c9f8)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196ba84)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81970994)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81976048)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81983098)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b1cc)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81998a96)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff819a82c9)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff819b8cfa)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff819be686)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff819c2cc3)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c906d)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff819d4c9e)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/netfilter.c (ffffffff819d9a8a)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de620)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff819df883)
Location: include/linux/skbuff.h:925
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/dev.c (ffffffff818f88c7)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81925c93)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff819432c5)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff819762fc)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_options.c (ffffffff81979ee4)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8197e48d)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/tcp_output.c (ffffffff81998ddf)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff819ac327)
Location: include/linux/skbuff.h:945
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819b528f)
Location: include/linux/skbuff.h:945
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819b73bc)
Location: include/linux/skbuff.h:945
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819c16f9)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d27a1)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff819da1cb)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff819dfbdb)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ecc8d)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff819f66f6)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a048fb)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a154d4)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff81a277c2)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81a2d0cd)
Location: include/linux/skbuff.h:945
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a31ae3)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a37931)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff81a43af0)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/netfilter.c (ffffffff81a48300)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4d191)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e42a)
Location: include/linux/skbuff.h:945
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/dev.c (ffffffff8192aa67)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff819582e3)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81978247)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff819acd0c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_options.c (ffffffff819b0844)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819b4e39)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/tcp_output.c (ffffffff819cf8ff)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff819e2dc4)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819ebfb9)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819ee0bc)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819f8299)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a091a1)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a110b8)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81a16c0b)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a23c9d)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d376)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b4ec)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a4c0a4)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff81a5e222)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81a63c27)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a68633)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6e461)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff81a7a770)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/netfilter.c (ffffffff81a7eeb0)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83d61)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a8508a)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/dev.c (ffffffff819fe784)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81a29bd3)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81a4cd55)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81a967fc)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv4/ip_options.c (ffffffff81a9a6c6)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81a9f034)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/tcp_output.c (ffffffff81abc235)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff81ad069c)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81ada048)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_send
```
```
In net/ipv4/icmp.c (ffffffff81adbe80)
Location: include/linux/skbuff.h:973
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81ae5286)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8c31)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81b0292f)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81b07c56)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15ca8)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1fefc)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81b30aab)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81b45c0d)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff81b57022)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81b5c6a6)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81b61903)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b680fc)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff81b74802)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b7951d)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81b79afa)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7eb31)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f053)
Location: include/linux/skbuff.h:973
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In net/core/dev.c (ffffffff819fe384)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81a2a533)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/lwt_bpf.c (ffffffff81a52a17)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81aa08a7)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv4/ip_options.c (ffffffff81aa4625)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81aa8f74)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/tcp_output.c (ffffffff81ac7aac)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff81adc6ac)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81ae6ab8)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_send
```
```
In net/ipv4/icmp.c (ffffffff81ae89ad)
Location: include/linux/skbuff.h:980
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81af2155)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05a01)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81b10cfd)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81b1603a)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b24118)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e80c)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f6db)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81b545b2)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff81b65692)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81b6aee6)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81b70085)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b7691d)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff81b83572)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b884b4)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81b88a48)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8db41)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81b8dfe3)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In net/core/dev.c (ffffffff819e4bf4)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81a116d3)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/lwt_bpf.c (ffffffff81a3818e)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81a8b7d7)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv4/ip_options.c (ffffffff81a8f719)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81a94065)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/tcp_output.c (ffffffff81ab2b0c)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff81ac76f7)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81ad1d88)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_send
```
```
In net/ipv4/icmp.c (ffffffff81ad3c5a)
Location: include/linux/skbuff.h:986
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81add945)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af1281)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81afe8f6)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81b03ecd)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11d48)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c54b)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d579)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81b41d12)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff81b53957)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81b591f8)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81b5e348)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6529b)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff81b721e5)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b771e4)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81b777c7)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7ca11)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81b7cf15)
Location: include/linux/skbuff.h:986
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In net/core/dev.c (ffffffff81a955e2)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81ac2bb3)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/lwt_bpf.c (ffffffff81aedfce)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81b46717)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv4/ip_options.c (ffffffff81b4a959)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81b4f497)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f9d9)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff81b85f19)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81b909d8)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_send
```
```
In net/ipv4/icmp.c (ffffffff81b9291a)
Location: include/linux/skbuff.h:996
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81b9cdb8)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1491)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81bc0112)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81bc61a6)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd58a7)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0e50)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81bf3729)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81c09a42)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff81c1ae67)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81c207e1)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81c257f8)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d4f2)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c695)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81c41c84)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81c42298)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47b12)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81c4957d)
Location: include/linux/skbuff.h:996
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In net/core/dev.c (ffffffff81c0bd56)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81c3d872)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/lwt_bpf.c (ffffffff81c70e0f)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81cd361b)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv4/ip_options.c (ffffffff81cd779d)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81cdce1a)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/tcp_output.c (ffffffff81cff030)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff81d16872)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81d21ecc)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_send
```
```
In net/ipv4/icmp.c (ffffffff81d23f49)
Location: include/linux/skbuff.h:1286
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81d2ee8e)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d44b5b)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81d54b0c)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81d5b4a9)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6c0ec)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77d39)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c2df)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81da4c0f)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff81db7488)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81dbd555)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81dc2f8c)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dca8f5)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff81ddaa72)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81de0546)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81de0c9a)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6f75)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81de8d28)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81dec22b)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
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
In net/core/dev.c (ffffffff81dbd79c)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/core/dev.c:tun_dst_unclone
```
```
In net/core/filter.c (ffffffff81df3d52)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/lwt_bpf.c (ffffffff81e28e8f)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81e93817)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv4/ip_options.c (ffffffff81e97e18)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81e9d88a)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/tcp_output.c (ffffffff81ec4090)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff81edd022)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81ee932c)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_send
```
```
In net/ipv4/icmp.c (ffffffff81eeb5d9)
Location: include/linux/skbuff.h:1128
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81ef6eee)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0ddfb)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81f1ed68)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81f25939)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f3744c)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81f444d0)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a29f)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81f740bf)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff81f8715d)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81f8da94)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81f939dc)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9b966)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff81fac781)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81fb28d6)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81fb30da)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9e05)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81fbc398)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfe7b)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
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
In net/core/dev.c (ffffffff81e2dfe8)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/core/dev.c:tun_dst_unclone
```
```
In net/core/filter.c (ffffffff81e6592c)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/lwt_bpf.c (ffffffff81e9e4c3)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81ef1fc1)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv4/ip_options.c (ffffffff81ef6673)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81efbfda)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/tcp_output.c (ffffffff81f223a0)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff81f3c272)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81f48c5c)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_send
```
```
In net/ipv4/icmp.c (ffffffff81f4af06)
Location: include/linux/skbuff.h:1138
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81f5696b)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6daab)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81f7e868)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81f854c9)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f96e59)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3cb3)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81fb9f52)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81fd419f)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff81fe749d)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81fee26d)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81ff4336)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffbd20)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff8200cf1c)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff82012feb)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff820137ca)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a538)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff8201cc98)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020e53)
Location: include/linux/skbuff.h:1138
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
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
In net/core/dev.c (ffffffff81eec3c8)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/core/dev.c:tun_dst_unclone
```
```
In net/core/filter.c (ffffffff81f24adc)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/lwt_bpf.c (ffffffff81f60c3c)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81fb6111)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv4/ip_options.c (ffffffff81fba603)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81fbff1a)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/tcp_output.c (ffffffff81fe6fbf)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff8200239c)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff8200edbc)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_send
```
```
In net/ipv4/icmp.c (ffffffff8201101e)
Location: include/linux/skbuff.h:1145
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8201ce0c)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff820341fb)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff82044f0d)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/netfilter.c (ffffffff8204bba3)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff820641f4)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff82070fe0)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff820874da)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff820a1ab1)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff820b52fc)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff820bbe3b)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff820c1284)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ca434)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff820dbeec)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff820e214b)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff820e292f)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e94f8)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff820ebc78)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820eff80)
Location: include/linux/skbuff.h:1145
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
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
In net/core/dev.c (ffff800010bcdfe4)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffff800010c0119c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffff800010c1eaa4)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffff800010c5cd94)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_options.c (ffff800010c60e2c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffff800010c6559c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/tcp_output.c (ffff800010c82b2c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffff800010c97bb4)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/arp.c (ffff800010ca1abc)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/icmp.c (ffff800010ca3c54)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/igmp.c (ffff800010cafe88)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc24dc)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffff800010cccd80)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffff800010cd2830)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0efc)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffff800010cec1d0)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffff800010cfc610)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffff800010d1159c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffff800010d23264)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffff800010d29c8c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffff800010d3007c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37d84)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffff800010d44238)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/netfilter.c (ffff800010d4a770)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4fabc)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffff800010d51104)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/dev.c (c0ce7aa8)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (c0d149bc)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (c0d36afc)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (c0d6c4f8)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_options.c (c0d70800)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (c0d75208)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/tcp_output.c (c0d91504)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (c0da59ac)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (c0dae908)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/icmp.c (c0db08d8)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/igmp.c (c0dbb868)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (c0dcddb0)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (c0dd7408)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (c0ddc73c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (c0dea294)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (c0df40ec)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (c0e03a30)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (c0e159c0)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (c0e27900)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (c0e2da5c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (c0e338d4)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (c0e38a44)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (c0e4679c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/netfilter.c (c0e4b6bc)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (c0e50808)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (c0e51ca0)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/dev.c (c000000000ca2644)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (c000000000ce0cc8)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (c000000000d10c50)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (c000000000d5f3f8)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_options.c (c000000000d640e4)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (c000000000d69bbc)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/tcp_output.c (c000000000d8d93c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (c000000000da8b0c)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/arp.c (c000000000db4d48)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/icmp.c (c000000000db7614)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/igmp.c (c000000000dc5dbc)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dddbf4)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (c000000000de8a3c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (c000000000df0ed0)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (c000000000e03388)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (c000000000e102e4)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (c000000000e24110)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (c000000000e3aa3c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (c000000000e531ec)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (c000000000e5aac8)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (c000000000e61358)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (c000000000e69330)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (c000000000e7a6e4)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/netfilter.c (c000000000e80044)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e87280)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (c000000000e890b0)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/dev.c (ffffffe0007538de)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffe00077f232)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffe0007986bc)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffe0007c5b94)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_options.c (ffffffe0007c9028)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffe0007ccdc0)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/tcp_output.c (ffffffe0007e432a)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffe0007f600e)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/arp.c (ffffffe0007fe2c0)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/icmp.c (ffffffe0007ffb0a)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/igmp.c (ffffffe000808fa8)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817940)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffe00081ee18)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffe000823b52)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082faf4)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffe0008399e6)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffe000846ec0)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffe000856258)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffe000864c8a)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffe00086a4a4)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffe00086f85e)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008741e8)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffe000880166)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/netfilter.c (ffffffe000883648)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe0008881f8)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffe0008893a0)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/dev.c (ffffffff818caa67)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff818f82b3)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff819180b7)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff8194cb7c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_options.c (ffffffff819506b4)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81954ca9)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/tcp_output.c (ffffffff8196f76f)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff81982c34)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8198bde9)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8198de5c)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81998039)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8f41)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff819b0a48)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff819b629b)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c332d)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff819cca06)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819dab7c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff819eb734)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff819fd8b2)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81a032b7)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a07cc3)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0daf1)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff81a19e00)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/netfilter.c (ffffffff81a1e540)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a233f1)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a2471a)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In drivers/net/vxlan.c (ffffffff817729f4)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/core/dev.c (ffffffff818849a7)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff818b20e3)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff818d1e67)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff8190666c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_options.c (ffffffff8190a1a4)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8190e799)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/tcp_output.c (ffffffff8192923f)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff8193c6f4)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819458a9)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8194791c)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81951af9)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962a01)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967d22)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/ipv4/ipmr.c (ffffffff8196d078)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff8197308b)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff8198011d)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff819897f6)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff8199793c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff819a84f4)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff819ba672)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff819c0077)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff819c4a83)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca8b1)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff819d6bc0)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/netfilter.c (ffffffff819db300)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819e01b1)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff819e14da)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/ip6_udp_tunnel.c (ffffffff819e5a72)
Location: include/linux/skbuff.h:941
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
In net/core/dev.c (ffffffff8191ba67)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff819492e3)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff81969247)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff819b734c)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_options.c (ffffffff819bae84)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819bf479)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/tcp_output.c (ffffffff819d9f3f)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff819ed404)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819f65f9)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819f86fc)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81a028d9)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a137e1)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a1b2e8)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81a20b3b)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2ddad)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81a37486)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a455fc)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a561b4)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff81a68332)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81a6dd37)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a72743)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a78571)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff81a84880)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/netfilter.c (ffffffff81a88fc0)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8de71)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f19a)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/dev.c (ffffffff8193cdb7)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff8196abf3)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/lwt_bpf.c (ffffffff8198b627)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff819c0bd6)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_options.c (ffffffff819c4775)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819c8df9)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_mc_finish_output
```
```
In net/ipv4/tcp_output.c (ffffffff819e3baf)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/raw.c (ffffffff819f72e4)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81a00809)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81a02a2c)
Location: include/linux/skbuff.h:941
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81a0ce09)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e1b1)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a261c8)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/netfilter.c (ffffffff81a2c06f)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3958d)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42e16)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a512cc)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a621ee)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff81a74922)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/raw.c (ffffffff81a7a357)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a7edcd)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a84ce1)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6mr.c (ffffffff81a911d0)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/netfilter.c (ffffffff81a95c20)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9abb5)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bf1a)
Location: include/linux/skbuff.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
</details>
</li>
</ul>

## Differences
