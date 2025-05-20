# Function: <code>rcuref_get_slowpath</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool rcuref_get_slowpath(rcuref_t *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rcuref.c (0)
Location: lib/rcuref.c:192
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/neighbour.c:__neigh_event_send
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/netfilter/nf_queue.c:__nf_queue
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff820f8e4d-ffffffff820f8e62: rcuref_get_slowpath.cold (STB_LOCAL)
ffffffff8181acd0-ffffffff8181ad45: rcuref_get_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool rcuref_get_slowpath(rcuref_t *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rcuref.c (0)
Location: lib/rcuref.c:192
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/neighbour.c:__neigh_event_send
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/netfilter/nf_queue.c:__nf_queue
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/udp.c:udp_sendmsg
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff821d696e-ffffffff821d6983: rcuref_get_slowpath.cold (STB_LOCAL)
ffffffff81860050-ffffffff818600c5: rcuref_get_slowpath (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
