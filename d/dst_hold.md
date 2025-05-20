# Function: <code>dst_hold</code>

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
In net/core/sock.c (ffffffff81703c21)
Location: include/net/dst.h:246
Inline: True
Inline callers:
  - net/core/sock.c:sk_receive_skb
```
```
In net/core/dev.c (ffffffff81714266)
Location: include/net/dst.h:246
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81731bb6)
Location: include/net/dst.h:246
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/route.c (ffffffff817568c8)
Location: include/net/dst.h:246
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177cc1a)
Location: include/net/dst.h:246
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177f349)
Location: include/net/dst.h:246
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81789a4f)
Location: include/net/dst.h:246
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b24b1)
Location: include/net/dst.h:246
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_flo_get
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/anycast.c (ffffffff817c40a6)
Location: include/net/dst.h:246
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
```
```
In net/ipv6/ip6_output.c (ffffffff817c579d)
Location: include/net/dst.h:246
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/addrconf.c (ffffffff817c9c73)
Location: include/net/dst.h:246
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
```
```
In net/ipv6/route.c (ffffffff817d33d3)
Location: include/net/dst.h:246
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_purge_dflt_routers
```
```
In net/ipv6/udp.c (ffffffff817e435c)
Location: include/net/dst.h:246
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f05ef)
Location: include/net/dst.h:246
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/fib6_rules.c (ffffffff817fe445)
Location: include/net/dst.h:246
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/core/sock.c (ffffffff8176a6c0)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/dev.c (ffffffff8177c07d)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff8179ce1c)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff817aae73)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/ipv4/route.c (ffffffff817c2b33)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ec236)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ec84d)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff817f7901)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff81822b2b)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_flo_get
```
```
In net/ipv6/anycast.c (ffffffff818313f9)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/ip6_output.c (ffffffff818328da)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/addrconf.c (ffffffff81838f0d)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81846b12)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/udp.c (ffffffff81852702)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860d82)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/fib6_rules.c (ffffffff8186ddc5)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/core/sock.c (ffffffff817977de)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/dev.c (ffffffff817a980d)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff817cae2c)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff817da493)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/ipv4/route.c (ffffffff817f11ed)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181b672)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181d13d)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff818287e9)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff8185446b)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_flo_get
```
```
In net/ipv6/anycast.c (ffffffff81862e69)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/ip6_output.c (ffffffff8186435a)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/addrconf.c (ffffffff8186a92d)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff818788ee)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8188f4a9)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/fib6_rules.c (ffffffff818a0ba5)
Location: include/net/dst.h:243
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/core/dev.c (ffffffff817c7e1c)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff817e9f17)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff817f95c2)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/ipv4/route.c (ffffffff818106b7)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
```
```
In net/xfrm/xfrm_policy.c (ffffffff818777a0)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_flo_get
```
```
In net/ipv6/anycast.c (ffffffff8188764c)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/ip6_output.c (ffffffff81889937)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/addrconf.c (ffffffff8188d074)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff8189db64)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_ins_rt
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/fib6_rules.c (ffffffff818c71ef)
Location: include/net/dst.h:247
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
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
In net/core/skbuff.c (ffffffff81831962)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff818419ac)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff818655a7)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81876ed5)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/ipv4/route.c (ffffffff8188fb37)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffffffff81897a2f)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff818c67de)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff818cb698)
Location: include/net/dst.h:249
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818e9eb5)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8579)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffa96)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/anycast.c (ffffffff8190887c)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/ip6_output.c (ffffffff8190c622)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff8191d90c)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_ins_rt
```
```
In net/ipv6/ip6mr.c (ffffffff81944a24)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff8194a70f)
Location: include/net/dst.h:249
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff8194f30d)
Location: include/net/dst.h:249
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
In net/core/skbuff.c (ffffffff8187bd8e)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff8188be31)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff818b30ae)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff818c85fd)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/ipv4/route.c (ffffffff818e2d8e)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffffffff818ebd68)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff8191c012)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81921b78)
Location: include/net/dst.h:232
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819402d7)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194f02c)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_output.c (ffffffff819566ac)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81963acd)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81976812)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff8199d5e2)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff819a3a2a)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff819a8dd8)
Location: include/net/dst.h:232
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
In net/core/skbuff.c (ffffffff8189bfee)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff818ad011)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff818d7efe)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff818f3534)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/ipv4/route.c (ffffffff8190fc2e)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffffffff81919038)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff8194a5c4)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81950998)
Location: include/net/dst.h:232
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81970157)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81982546)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b1a2)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81998a77)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff819ac3f2)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff819d4142)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff819da34a)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff819df8f8)
Location: include/net/dst.h:232
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff818e68a6)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff818f88b0)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81925c7e)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff819459eb)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
Direct callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/ipv4/route.c (ffffffff81972099)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
Direct callers:
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffffffff8197b035)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff819aecc9)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819b527a)
Location: include/net/dst.h:221
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819d9a0a)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ec405)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff819f66d3)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a048e4)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a15127)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81a42fe8)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a48f40)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
Direct callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e490)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff81945c61-ffffffff81945c75: dst_hold.part.0 (STB_LOCAL)
ffffffff81976981-ffffffff81976995: dst_hold.part.0 (STB_LOCAL)
ffffffff819ed7a1-ffffffff819ed7b5: dst_hold.part.0 (STB_LOCAL)
ffffffff81a04d58-ffffffff81a04d6c: dst_hold.part.0 (STB_LOCAL)
ffffffff81a1d26c-ffffffff81a1d280: dst_hold.part.0 (STB_LOCAL)
ffffffff81a49667-ffffffff81a4967b: dst_hold.part.0 (STB_LOCAL)
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
In net/core/skbuff.c (ffffffff819189ee)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff8192aa50)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff819582ce)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff8197aa0b)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/ipv4/route.c (ffffffff819aa1b8)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffffffff819b19a5)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff819e59e6)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819ebfa8)
Location: include/net/dst.h:221
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1086a)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a233fd)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d353)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b4d5)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a4bcfe)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81a79b48)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a7fb30)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81a850f0)
Location: include/net/dst.h:221
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
In net/core/skbuff.c (ffffffff819ec839)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff819fe76d)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81a29bbe)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81a4fec7)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/ipv4/route.c (ffffffff81a957ba)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffffffff81a9c1e9)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff81ad5795)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ad9d17)
Location: include/net/dst.h:220
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b022a3)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15795)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1ef2f)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/ipv6/ip6_output.c (ffffffff81b30a94)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b316a5)
Location: include/net/dst.h:220
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b40e33)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81b747ed)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81b7a940)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f0ab)
Location: include/net/dst.h:220
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
In net/core/skbuff.c (ffffffff819ec4f9)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff819fe36d)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81a2a51e)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81a55f04)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81a6f3f1)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81a9f84a)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffffffff81aa6049)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff81ae1d33)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ae6777)
Location: include/net/dst.h:220
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b10644)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b23bed)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2d7df)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f6c4)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b40295)
Location: include/net/dst.h:220
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b4f8ef)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81b8355d)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81b89890)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81b8e03b)
Location: include/net/dst.h:220
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
In net/core/skbuff.c (ffffffff819d29e9)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff819e4bdd)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81a116be)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81a38f14)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81a57cc4)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81a8a78a)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffffffff81a91209)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff81acba06)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ad1a47)
Location: include/net/dst.h:223
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81afe254)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b117ed)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c527)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d562)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e8a5)
Location: include/net/dst.h:223
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b3d61f)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81b721d0)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81b786e0)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81b7cf5c)
Location: include/net/dst.h:223
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
In net/core/skbuff.c (ffffffff81a8265d)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/filter.c (ffffffff81ac2b9e)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81aeede4)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81b10c8c)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81b4567a)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffffffff81b4c59d)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff81b8a296)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81b90677)
Location: include/net/dst.h:223
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bbf4e4)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd52dd)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0e2c)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81bf3712)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4c74)
Location: include/net/dst.h:223
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c056af)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c680)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81c43220)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81c495e9)
Location: include/net/dst.h:223
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
In net/core/skbuff.c (ffffffff81bf7051)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/filter.c (ffffffff81c3d85d)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81c71d3e)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81c97e0e)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81cd2399)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffffffff81cd9bf1)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff81d1db79)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81d21afb)
Location: include/net/dst.h:224
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d5427e)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6bae6)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77d17)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81d89e79)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81d8da9a)
Location: include/net/dst.h:224
Inline: True
```
```
In net/ipv6/route.c (ffffffff81d9fc9f)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81ddaa5d)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81de1f9e)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81de8dc2)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In net/core/skbuff.c (ffffffff81da5fc1)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/filter.c (ffffffff81df3d3d)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81e29e3e)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81e53dae)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81e929c9)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffffffff81e9a381)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff81ee4c38)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ee8f3b)
Location: include/net/dst.h:224
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f1e45e)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f36e26)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81f444ae)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81f57e23)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81f5bbca)
Location: include/net/dst.h:224
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f6ed3f)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81fac76c)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81fb44ce)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81fbc432)
Location: include/net/dst.h:224
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In net/core/skbuff.c (ffffffff81e150ad)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/filter.c (ffffffff81e6591d)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81e9f972)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81eaf62a)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81ef1163)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffffffff81ef8cdd)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff81f445f9)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81f48900)
Location: include/net/dst.h:238
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f7df4e)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f967a4)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3c96)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81fb79e0)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb986)
Location: include/net/dst.h:238
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fcebcc)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff8200cf0c)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff82014c7f)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff8201cd2c)
Location: include/net/dst.h:238
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In net/core/skbuff.c (ffffffff81ed244d)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/filter.c (ffffffff81f24acd)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81f620e2)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81f720aa)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81fb52b3)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffffffff81fbcbfd)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff8200a5d3)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8200ea60)
Location: include/net/dst.h:231
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff82063b9d)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff82070fc3)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff82085010)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff82088dbd)
Location: include/net/dst.h:231
Inline: True
```
```
In net/ipv6/route.c (ffffffff8209c42c)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff820dbedc)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff820e3dbf)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff820ebd0c)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In net/core/skbuff.c (ffff800010bb4798)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffff800010bcdfb0)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffff800010c010f8)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffff800010c2214c)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/ipv4/route.c (ffff800010c5a364)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffff800010c62360)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffff800010c9e30c)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffff800010ca1a88)
Location: include/net/dst.h:221
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010ccb494)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce043c)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffff800010cec194)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffff800010cfc5dc)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffff800010d11244)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (ffff800010d43e2c)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffff800010d4b188)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffff800010d51168)
Location: include/net/dst.h:221
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
In net/core/skbuff.c (c0cd054c)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (c0ce7a6c)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (c0d14980)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (c0d39418)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/ipv4/route.c (c0d69970)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (c0d71b50)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (c0da9118)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (c0dae8cc)
Location: include/net/dst.h:221
Inline: True
```
```
In net/ipv4/ipmr.c (c0dd5988)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (c0de999c)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (c0df40a4)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (c0e039f4)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (c0e155c4)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (c0e45be0)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (c0e4c4ec)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (c0e51d08)
Location: include/net/dst.h:221
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
In net/core/skbuff.c (c000000000c87a90)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (c000000000ca2614)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (c000000000ce0c98)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (c000000000d14470)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/ipv4/route.c (c000000000d5be4c)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (c000000000d65620)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (c000000000db047c)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (c000000000db4d18)
Location: include/net/dst.h:221
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000de811c)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (c000000000e02654)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (c000000000e102a8)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (c000000000e240e0)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (c000000000e38560)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (c000000000e78988)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (c000000000e81520)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (c000000000e89134)
Location: include/net/dst.h:221
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
In net/core/skbuff.c (ffffffe000742506)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffe0007538bc)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffe00077f20e)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffe00079abae)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/ipv4/route.c (ffffffe0007c3900)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffffffe0007c9f20)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffe0007f81c4)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffe0007fe29e)
Location: include/net/dst.h:221
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe00081e7b8)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082f238)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffe0008399ba)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffe000846e9c)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffe000854f1e)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (ffffffe00087e9bc)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffe00088420a)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffe0008893ea)
Location: include/net/dst.h:221
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
In net/core/skbuff.c (ffffffff818b89ee)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff818caa50)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff818f829e)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff8191a87b)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/ipv4/route.c (ffffffff8194a028)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffffffff81951815)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff81985856)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8198bdd8)
Location: include/net/dst.h:221
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819b027a)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c2a8d)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc9e3)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819dab65)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff819eb38e)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81a191d8)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a1f1c0)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81a24780)
Location: include/net/dst.h:221
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
In net/core/skbuff.c (ffffffff8187293e)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81884990)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff818b20ce)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff818d462b)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/ipv4/route.c (ffffffff81903b18)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffffffff8190b305)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff8193f316)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81945898)
Location: include/net/dst.h:221
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196c8aa)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197f87d)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff819897d3)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81997925)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff819a814e)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff819d5f98)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff819dbf80)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff819e1540)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/skbuff.c (ffffffff819099ee)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff8191ba50)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff819492ce)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff8196ba0b)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/ipv4/route.c (ffffffff819b47f8)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffffffff819bbfe5)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff819f0026)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819f65e8)
Location: include/net/dst.h:221
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1ab1a)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2d50d)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81a37463)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a455e5)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a55e0e)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81a83c58)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a89c40)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f200)
Location: include/net/dst.h:221
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
In net/core/skbuff.c (ffffffff8192aaee)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff8193cda0)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff8196abde)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff8198de89)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/ipv4/route.c (ffffffff819bdf38)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/ip_output.c (ffffffff819c58f5)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/udp.c (ffffffff819fa8ad)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81a007f8)
Location: include/net/dst.h:221
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a2597a)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a38ca3)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42df3)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a512b5)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffffffff81a61e38)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81a90578)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a968a0)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bf80)
Location: include/net/dst.h:221
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
</details>
</li>
</ul>

## Differences
