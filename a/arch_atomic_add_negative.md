# Function: <code>arch_atomic_add_negative</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123ea93)
Location: arch/x86/include/asm/atomic.h:147
Inline: True
```
```
In mm/huge_memory.c (ffffffff8127756d)
Location: arch/x86/include/asm/atomic.h:147
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/rmap.c (ffffffff81253023)
Location: arch/x86/include/asm/atomic.h:152
Inline: True
```
```
In mm/huge_memory.c (ffffffff81288d6a)
Location: arch/x86/include/asm/atomic.h:152
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff81265322)
Location: arch/x86/include/asm/atomic.h:152
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a39d5)
Location: arch/x86/include/asm/atomic.h:152
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff81273be5)
Location: arch/x86/include/asm/atomic.h:152
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b4ed5)
Location: arch/x86/include/asm/atomic.h:152
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff812a5008)
Location: arch/x86/include/asm/atomic.h:152
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/hugetlb.c (ffffffff812c6835)
Location: arch/x86/include/asm/atomic.h:152
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
```
```
In mm/huge_memory.c (ffffffff812ea397)
Location: arch/x86/include/asm/atomic.h:152
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff812b0544)
Location: arch/x86/include/asm/atomic.h:150
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/huge_memory.c (ffffffff812f556e)
Location: arch/x86/include/asm/atomic.h:150
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff812b5b54)
Location: arch/x86/include/asm/atomic.h:150
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/huge_memory.c (ffffffff812fbbc5)
Location: arch/x86/include/asm/atomic.h:150
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In kernel/ucount.c (ffffffff810ea46d)
Location: arch/x86/include/asm/atomic.h:150
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:alloc_ucounts
```
```
In mm/rmap.c (ffffffff812f77d4)
Location: arch/x86/include/asm/atomic.h:150
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/huge_memory.c (ffffffff813459be)
Location: arch/x86/include/asm/atomic.h:150
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In kernel/ucount.c (ffffffff8110513d)
Location: arch/x86/include/asm/atomic.h:150
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:alloc_ucounts
```
```
In mm/rmap.c (ffffffff8135d440)
Location: arch/x86/include/asm/atomic.h:150
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/huge_memory.c (ffffffff813bbaff)
Location: arch/x86/include/asm/atomic.h:150
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In kernel/ucount.c (ffffffff8112ab8d)
Location: arch/x86/include/asm/atomic.h:150
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:alloc_ucounts
```
```
In mm/rmap.c (ffffffff813d7fa4)
Location: arch/x86/include/asm/atomic.h:150
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
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
In kernel/ucount.c (ffffffff81137cf6)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:alloc_ucounts
```
```
In mm/rmap.c (ffffffff8140c985)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
```
```
In drivers/net/loopback.c (ffffffff81c31765)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81e089ce)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81e12377)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81e3b682)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/dst.c (ffffffff81e4513c)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff81e4b91c)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81e65921)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81e9f977)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81eaf632)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81ee971d)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81eee92e)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81ef6720)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81ef8ce5)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81f00666)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2d9a8)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32ef3)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f38987)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81f445fd)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81f48905)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81f4b044)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f7df52)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f96e1d)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1f1d)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3c9a)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81fb79e8)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb98a)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fcebb4)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffa8ec)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6mr.c (ffffffff8200cf10)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff82014c84)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff8201dfa9)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
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
In kernel/ucount.c (ffffffff81142f06)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:alloc_ucounts
```
```
In mm/rmap.c (ffffffff8143b232)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - mm/rmap.c:folio_remove_rmap_pmd
  - mm/rmap.c:folio_remove_rmap_ptes
```
```
In drivers/net/loopback.c (ffffffff81ce45e5)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/sock.c (ffffffff81ec543e)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81ecf537)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81ef9a3d)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/dst.c (ffffffff81f03dbc)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff81f0a63c)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81f24ad1)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81f620e7)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81f720b2)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81fad627)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81fb2a8e)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81fba6b0)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81fbcc05)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc44af)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff2638)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff9043)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffea67)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff8200a5d7)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8200ea65)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8201114e)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff820641b8)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f14b)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff82070fc7)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff82085018)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff82088dc1)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
```
```
In net/ipv6/route.c (ffffffff8209c414)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c85dc)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6mr.c (ffffffff820dbee0)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff820e3dc4)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff820ecf89)
Location: arch/x86/include/asm/atomic.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126c235)
Location: arch/x86/include/asm/atomic.h:152
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ad4b5)
Location: arch/x86/include/asm/atomic.h:152
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff8125e2a5)
Location: arch/x86/include/asm/atomic.h:152
Inline: True
```
```
In mm/huge_memory.c (ffffffff8129e46c)
Location: arch/x86/include/asm/atomic.h:152
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff81269fd5)
Location: arch/x86/include/asm/atomic.h:152
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ab2c5)
Location: arch/x86/include/asm/atomic.h:152
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/rmap.c (ffffffff81279945)
Location: arch/x86/include/asm/atomic.h:152
Inline: True
```
```
In mm/huge_memory.c (ffffffff812bb615)
Location: arch/x86/include/asm/atomic.h:152
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
</ul>

## Differences
