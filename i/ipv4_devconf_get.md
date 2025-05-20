# Function: <code>ipv4_devconf_get</code>

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
In net/ipv4/route.c (0)
Location: include/linux/inetdevice.h:53
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/inetdevice.h:53
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8178ce6a)
Location: include/linux/inetdevice.h:53
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/inetdevice.h:53
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81795395)
Location: include/linux/inetdevice.h:53
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/inetdevice.h:53
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/inetdevice.h:53
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/inetdevice.h:53
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
In net/ipv4/route.c (ffffffff817c25c5)
Location: include/linux/inetdevice.h:53
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/inetdevice.h:53
Inline: True
```
```
In net/ipv4/arp.c (ffffffff817fa483)
Location: include/linux/inetdevice.h:53
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/inetdevice.h:53
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81804a15)
Location: include/linux/inetdevice.h:53
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81808bd7)
Location: include/linux/inetdevice.h:53
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/inetdevice.h:53
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/inetdevice.h:53
Inline: True
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
In net/ipv4/route.c (ffffffff817f0c77)
Location: include/linux/inetdevice.h:53
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/inetdevice.h:53
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8182b353)
Location: include/linux/inetdevice.h:53
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/inetdevice.h:53
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff818359e5)
Location: include/linux/inetdevice.h:53
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81839ce0)
Location: include/linux/inetdevice.h:53
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/inetdevice.h:53
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/inetdevice.h:53
Inline: True
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
In net/ipv4/route.c (0)
Location: include/linux/inetdevice.h:54
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/inetdevice.h:54
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8184c744)
Location: include/linux/inetdevice.h:54
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/inetdevice.h:54
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81856f3e)
Location: include/linux/inetdevice.h:54
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff8185b15d)
Location: include/linux/inetdevice.h:54
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/inetdevice.h:54
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/inetdevice.h:54
Inline: True
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
In net/ipv4/route.c (0)
Location: include/linux/inetdevice.h:55
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/inetdevice.h:55
Inline: True
```
```
In net/ipv4/arp.c (ffffffff818cc3fa)
Location: include/linux/inetdevice.h:55
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/inetdevice.h:55
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff818d6dee)
Location: include/linux/inetdevice.h:55
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/inetdevice.h:55
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/inetdevice.h:55
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/inetdevice.h:55
Inline: True
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
In net/core/filter.c (ffffffff818b4147)
Location: include/linux/inetdevice.h:55
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff818e5990)
Location: include/linux/inetdevice.h:55
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff818e80b4)
Location: include/linux/inetdevice.h:55
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/arp.c (ffffffff81922a69)
Location: include/linux/inetdevice.h:55
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (ffffffff81928560)
Location: include/linux/inetdevice.h:55
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff8192d704)
Location: include/linux/inetdevice.h:55
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81931e76)
Location: include/linux/inetdevice.h:55
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81935210)
Location: include/linux/inetdevice.h:55
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff819375f3)
Location: include/linux/inetdevice.h:55
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff818d98f7)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819128a0)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81914f15)
Location: include/linux/inetdevice.h:57
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81951863)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (ffffffff819579b5)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff8195cba4)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81961636)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81964c10)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff81966fe3)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff8192a2b5)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81974fb4)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819773f7)
Location: include/linux/inetdevice.h:57
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819b6137)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (ffffffff819bc33a)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff819c18a4)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff819c5dd6)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff819ca945)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (ffffffff819cd106)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff8195c645)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819ab9d4)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819add87)
Location: include/linux/inetdevice.h:57
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819ece57)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (ffffffff819f3037)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff819f8444)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff819fc986)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81a01535)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (ffffffff81a03c5f)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff81a2de25)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a93bbd)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81a979fb)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/arp.c (ffffffff81adae02)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (ffffffff81ae1a28)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff81ae4fa6)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_rejoin_groups
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeb6f6)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81af0582)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff81af38e3)
Location: include/linux/inetdevice.h:57
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
In net/core/filter.c (ffffffff81a2fd67)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a9da6d)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81aa195b)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/arp.c (ffffffff81ae78a2)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (ffffffff81aee8c8)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff81af1e76)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_rejoin_groups
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81af8606)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81afd55a)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff81b00827)
Location: include/linux/inetdevice.h:57
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
In net/core/filter.c (ffffffff81a16eb7)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a88a09)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81a8c92c)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/arp.c (ffffffff81ad2b62)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (ffffffff81ad9fc2)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff81ade624)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae3d2d)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae8d5f)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff81aebeb2)
Location: include/linux/inetdevice.h:57
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
In net/core/filter.c (ffffffff81ac9127)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81b43179)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81b47a5c)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/arp.c (ffffffff81b917b2)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (ffffffff81b99102)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff81b9daf4)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba365d)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba8d80)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff81bac0d2)
Location: include/linux/inetdevice.h:57
Inline: True
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
In net/core/filter.c (ffffffff81c46090)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81ccfc0b)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81cd4cc5)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/arp.c (ffffffff81d20f73)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (ffffffff81d2b01e)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff81d2fd3c)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81d35ecd)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3b7df)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff81d3ef3d)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_lookup_good_nhc
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
In net/core/filter.c (ffffffff81dfa560)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81e8fe25)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81e94ff5)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/arp.c (ffffffff81ee82f3)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_accept
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (ffffffff81ef2c37)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff81ef7e2c)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81efe4cd)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81f041af)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff81f07b1d)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_lookup_good_nhc
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
In net/core/filter.c (ffffffff81e6e110)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81eee537)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81ef37c5)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/arp.c (ffffffff81f47bc5)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_accept
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (ffffffff81f525a0)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff81f578bc)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5df5d)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81f63b8f)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff81f675fd)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_lookup_good_nhc
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
In net/core/filter.c (ffffffff81f2d9e0)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81fb2697)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81fb7755)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/arp.c (ffffffff8200dd05)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_accept
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (ffffffff82018877)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff8201dd4c)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff8202451d)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff8202a15f)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff8202dbdd)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_lookup_good_nhc
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
In net/core/filter.c (ffff800010bfe47c)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffff800010c5bb80)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffff800010c5e5dc)
Location: include/linux/inetdevice.h:57
Inline: True
```
```
In net/ipv4/arp.c (ffff800010ca28bc)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (ffff800010ca93d8)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffff800010cb0078)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffff800010cb4de0)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9bbc)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (ffff800010cbc848)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (c0d18bf4)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c0d6b1b8)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (c0d6d578)
Location: include/linux/inetdevice.h:57
Inline: True
```
```
In net/ipv4/arp.c (c0daf71c)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (c0db59dc)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (c0dbba28)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (c0dc0768)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (c0dc5398)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (c0dc801c)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (c000000000ce60a8)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c000000000d5dd28)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (c000000000d60a64)
Location: include/linux/inetdevice.h:57
Inline: True
```
```
In net/ipv4/arp.c (c000000000db5ef0)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (c000000000dbe53c)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (c000000000dc606c)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (c000000000dcc0e0)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (c000000000dd2cb8)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (c000000000dd64d4)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffe0007804fe)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffe0007c4d4c)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffe0007c69ac)
Location: include/linux/inetdevice.h:57
Inline: True
```
```
In net/ipv4/arp.c (ffffffe0007fe868)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (ffffffe000803ed8)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffe000809154)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffe00080c924)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffe0008106f4)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (ffffffe000812c3a)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff818fc615)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff8194b844)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff8194dbf7)
Location: include/linux/inetdevice.h:57
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8198cc27)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (ffffffff81992dd7)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff819981e4)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff8199c726)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff819a12d5)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (ffffffff819a39ff)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff818b6445)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81905334)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819076e7)
Location: include/linux/inetdevice.h:57
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819466e7)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (ffffffff8194c897)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff81951ca4)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff819561e6)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff8195ad95)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (ffffffff8195d4bf)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff8194d645)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819b6014)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819b83c7)
Location: include/linux/inetdevice.h:57
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819f7497)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (ffffffff819fd677)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff81a02a84)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81a06fc6)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0bb75)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (ffffffff81a0e29f)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/filter.c (ffffffff8196f007)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819bf814)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819c1c27)
Location: include/linux/inetdevice.h:57
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81a016b7)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/devinet.c (ffffffff81a07a07)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff81a0cfb4)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81a11696)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81a16365)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (ffffffff81a18aaf)
Location: include/linux/inetdevice.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
</details>
</li>
</ul>

## Differences
