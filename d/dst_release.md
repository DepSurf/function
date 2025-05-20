# Function: <code>dst_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81723b50)
Location: net/core/dst.c:300
Inline: False
Direct callers:
  - net/core/sock.c:__sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/ipv4/route.c:ipv4_negative_advice
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ip_tunnel_core.c:iptunnel_pull_header
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_negative_advice
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff81723b50-ffffffff81723bbb: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff8178d5a0)
Location: net/core/dst.c:300
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/dst_cache.c:dst_cache_destroy
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_negative_advice
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_negative_advice
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff8178d5a0-ffffffff8178d614: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff817bae30)
Location: net/core/dst.c:300
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/dst_cache.c:dst_cache_destroy
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_negative_advice
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_negative_advice
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff817bae30-ffffffff817baea4: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff817d9670)
Location: net/core/dst.c:178
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff817d9670-ffffffff817d96e4: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81853ce0)
Location: net/core/dst.c:178
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
  - net/xfrm/xfrm_policy.c:__xfrm_pcpu_work_fn
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:lookup_nexthop
  - net/ipv6/seg6_local.c:lookup_nexthop
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81853ce0-ffffffff81853d54: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:181
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
  - net/xfrm/xfrm_policy.c:__xfrm_pcpu_work_fn
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff8189fb41-ffffffff8189fb5f: dst_release.cold.6 (STB_LOCAL)
ffffffff8189f460-ffffffff8189f4c0: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:181
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff818c2510-ffffffff818c252e: dst_release.cold.6 (STB_LOCAL)
ffffffff818c1e20-ffffffff818c1e80: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:169
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff8190eca2-ffffffff8190ecc0: dst_release.cold (STB_LOCAL)
ffffffff8190e560-ffffffff8190e5c0: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:169
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81941312-ffffffff81941330: dst_release.cold (STB_LOCAL)
ffffffff81940c40-ffffffff81940cb5: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:169
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:skb_dst_pop
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_cork_release
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tunnel
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81a10f92-ffffffff81a10fad: dst_release.cold (STB_LOCAL)
ffffffff81a10890-ffffffff81a10910: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:169
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/sched/sch_frag.c:sch_fragment
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:refdst_drop
  - net/xfrm/xfrm_output.c:skb_dst_pop
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_cork_release
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tunnel
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
```
**Symbols:**

```
ffffffff81c3156c-ffffffff81c31587: dst_release.cold (STB_LOCAL)
ffffffff81a10c40-ffffffff81a10cc0: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:169
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/sched/sch_frag.c:sch_fragment
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:refdst_drop
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_cork_release
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tunnel
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
**Symbols:**

```
ffffffff81c23875-ffffffff81c23890: dst_release.cold (STB_LOCAL)
ffffffff819f7ab0-ffffffff819f7b30: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:167
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/sched/sch_frag.c:sch_fragment
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:refdst_drop
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_cork_release
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tunnel
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:fib6_nh_release_dsts
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
**Symbols:**

```
ffffffff81d36966-ffffffff81d3699b: dst_release.cold (STB_LOCAL)
ffffffff81aa97b0-ffffffff81aa9843: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:167
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/sched/sch_frag.c:sch_fragment
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_negative_advice
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:refdst_drop
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_cork_release
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tunnel
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
**Symbols:**

```
ffffffff81f03248-ffffffff81f0327e: dst_release.cold (STB_LOCAL)
ffffffff81c21b70-ffffffff81c21c2f: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:167
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:tun_dst_unclone
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:dst_destroy
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/sched/sch_frag.c:sch_fragment
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_negative_advice
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:refdst_drop
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_cork_release
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tunnel
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
**Symbols:**

```
ffffffff820abad3-ffffffff820abaee: dst_release.cold (STB_LOCAL)
ffffffff81dd3cf0-ffffffff81dd3dc5: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81e44c60)
Location: net/core/dst.c:164
Inline: True
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:tun_dst_unclone
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:dst_destroy
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/sched/sch_frag.c:sch_fragment
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_negative_advice
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:refdst_drop
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_cork_release
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tunnel
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
**Symbols:**

```
ffffffff81e44c60-ffffffff81e44ce8: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81f038e0)
Location: net/core/dst.c:164
Inline: True
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:tun_dst_unclone
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:dst_destroy
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/sched/sch_frag.c:sch_fragment
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_negative_advice
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:refdst_drop
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_cork_release
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
**Symbols:**

```
ffffffff81f038e0-ffffffff81f03968: dst_release (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffff800010be0f38)
Location: net/core/dst.c:169
Inline: True
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffff800010be0f38-ffff800010be1018: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (c0cfaa78)
Location: net/core/dst.c:169
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_cork_release
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
c0cfaa78-c0cfab40: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (c000000000cc1370)
Location: net/core/dst.c:169
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
c000000000cc1370-c000000000cc14ac: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffe000766d36)
Location: net/core/dst.c:169
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffe000766d36-ffffffe000766de2: dst_release (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:169
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff818e12e2-ffffffff818e1300: dst_release.cold (STB_LOCAL)
ffffffff818e0c10-ffffffff818e0c85: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:169
Inline: False
Direct callers:
  - drivers/net/vxlan.c:vxlan_fill_metadata_dst
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:encap_bypass_if_local
  - drivers/net/vxlan.c:vxlan6_get_route
  - drivers/net/vxlan.c:vxlan_get_route
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
  - net/ipv4/ip_tunnel.c:ip_tunnel_bind_dev
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff8189b122-ffffffff8189b140: dst_release.cold (STB_LOCAL)
ffffffff8189aa50-ffffffff8189aac5: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:169
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81932312-ffffffff81932330: dst_release.cold (STB_LOCAL)
ffffffff81931c40-ffffffff81931cb5: dst_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dst_release(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:169
Inline: False
Direct callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
  - net/xfrm/xfrm_policy.c:xfrm_negative_advice
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/fib6_rules.c:fib6_rule_suppress
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff819539e2-ffffffff81953a00: dst_release.cold (STB_LOCAL)
ffffffff81953310-ffffffff81953385: dst_release (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
