# Function: <code>static_key_true</code>

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
In kernel/sched/core.c (ffffffff810abadd)
Location: include/linux/jump_label.h:136
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810b2c5b)
Location: include/linux/jump_label.h:136
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/rt.c (ffffffff810bf61f)
Location: include/linux/jump_label.h:136
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/bpf/core.c (ffffffff8117140c)
Location: include/linux/jump_label.h:136
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
```
```
In net/core/secure_seq.c (ffffffff81710ffa)
Location: include/linux/jump_label.h:136
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_tcp_sequence_number
```
```
In net/core/flow_dissector.c (ffffffff817116a8)
Location: include/linux/jump_label.h:136
Inline: True
Inline callers:
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/ethtool.c (ffffffff8171fe1b)
Location: include/linux/jump_label.h:136
Inline: True
```
```
In net/ipv4/route.c (ffffffff817546b5)
Location: include/linux/jump_label.h:136
Inline: True
Inline callers:
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/route.c:find_exception
```
```
In net/ipv4/ip_fragment.c (ffffffff8175927e)
Location: include/linux/jump_label.h:136
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipqhashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff81761f23)
Location: include/linux/jump_label.h:136
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8178281d)
Location: include/linux/jump_label.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
```
```
In net/ipv4/udp.c (ffffffff817864cc)
Location: include/linux/jump_label.h:136
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
```
```
In net/ipv4/fib_semantics.c (ffffffff8179c02f)
Location: include/linux/jump_label.h:136
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/syncookies.c (ffffffff817aadd1)
Location: include/linux/jump_label.h:136
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
```
```
In net/ipv6/udp.c (ffffffff817e3344)
Location: include/linux/jump_label.h:136
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/reassembly.c (ffffffff817eda09)
Location: include/linux/jump_label.h:136
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
```
```
In net/ipv6/syncookies.c (ffffffff817fef15)
Location: include/linux/jump_label.h:136
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_hash
```
```
In net/ipv6/output_core.c (ffffffff81800863)
Location: include/linux/jump_label.h:136
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/ipv6/output_core.c:ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81801c74)
Location: include/linux/jump_label.h:136
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/sched/core.c (ffffffff810ae750)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810c0187)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810c2f2f)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/bpf/core.c (ffffffff8117f1dc)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
```
```
In net/core/secure_seq.c (ffffffff81778cff)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
```
```
In net/core/flow_dissector.c (ffffffff8177a056)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/core/ethtool.c (ffffffff81788a6b)
Location: include/linux/jump_label.h:128
Inline: True
```
```
In net/ipv4/route.c (ffffffff817c103a)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_fragment.c (ffffffff817c561e)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipqhashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ce233)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efead)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
```
```
In net/ipv4/udp.c (ffffffff817f36cc)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
```
```
In net/ipv4/fib_semantics.c (ffffffff81809bb4)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/syncookies.c (ffffffff818188d4)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
```
```
In net/ipv6/udp.c (ffffffff818518d3)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/reassembly.c (ffffffff8185c249)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
```
```
In net/ipv6/syncookies.c (ffffffff8186e8a5)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_hash
```
```
In net/ipv6/output_core.c (ffffffff8187204a)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81872fe3)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/sched/core.c (ffffffff810b488b)
Location: include/linux/jump_label.h:130
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810c0b65)
Location: include/linux/jump_label.h:130
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:place_entity
```
```
In kernel/sched/rt.c (ffffffff810c8f8f)
Location: include/linux/jump_label.h:130
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/bpf/core.c (ffffffff8118b04c)
Location: include/linux/jump_label.h:130
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
```
```
In net/core/secure_seq.c (ffffffff817a5e3f)
Location: include/linux/jump_label.h:130
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
```
```
In net/core/flow_dissector.c (ffffffff817a75f6)
Location: include/linux/jump_label.h:130
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/core/ethtool.c (ffffffff817b61ab)
Location: include/linux/jump_label.h:130
Inline: True
```
```
In net/ipv4/route.c (ffffffff817f063a)
Location: include/linux/jump_label.h:130
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_fragment.c (ffffffff817f511e)
Location: include/linux/jump_label.h:130
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipqhashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fdfd3)
Location: include/linux/jump_label.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818208bd)
Location: include/linux/jump_label.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
```
```
In net/ipv4/udp.c (ffffffff818244bc)
Location: include/linux/jump_label.h:130
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
```
```
In net/ipv4/fib_semantics.c (ffffffff8183ad34)
Location: include/linux/jump_label.h:130
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/syncookies.c (ffffffff8184a134)
Location: include/linux/jump_label.h:130
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
```
```
In net/ipv6/udp.c (ffffffff81883693)
Location: include/linux/jump_label.h:130
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/reassembly.c (ffffffff8188e159)
Location: include/linux/jump_label.h:130
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
```
```
In net/ipv6/syncookies.c (ffffffff818a17f5)
Location: include/linux/jump_label.h:130
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_hash
```
```
In net/ipv6/output_core.c (ffffffff818a662a)
Location: include/linux/jump_label.h:130
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7603)
Location: include/linux/jump_label.h:130
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/sched/core.c (ffffffff810b0906)
Location: include/linux/jump_label.h:144
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810ba990)
Location: include/linux/jump_label.h:144
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/rt.c (ffffffff810c3060)
Location: include/linux/jump_label.h:144
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/bpf/core.c (ffffffff8118fb6c)
Location: include/linux/jump_label.h:144
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
```
```
In net/core/secure_seq.c (ffffffff817c3e42)
Location: include/linux/jump_label.h:144
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/core/flow_dissector.c (ffffffff817c5c36)
Location: include/linux/jump_label.h:144
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/core/ethtool.c (ffffffff817d3f3b)
Location: include/linux/jump_label.h:144
Inline: True
Inline callers:
  - net/core/ethtool.c:netdev_rss_key_fill
```
```
In net/ipv4/route.c (ffffffff81810a7e)
Location: include/linux/jump_label.h:144
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_fragment.c (ffffffff818155b9)
Location: include/linux/jump_label.h:144
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipqhashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181e3e9)
Location: include/linux/jump_label.h:144
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840dcd)
Location: include/linux/jump_label.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
```
```
In net/ipv4/udp.c (ffffffff818451dc)
Location: include/linux/jump_label.h:144
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
```
```
In net/ipv4/syncookies.c (ffffffff8186db6e)
Location: include/linux/jump_label.h:144
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
```
```
In net/ipv6/udp.c (ffffffff818a9923)
Location: include/linux/jump_label.h:144
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/reassembly.c (ffffffff818b47f9)
Location: include/linux/jump_label.h:144
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
```
```
In net/ipv6/syncookies.c (ffffffff818c7e65)
Location: include/linux/jump_label.h:144
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_hash
```
```
In net/ipv6/output_core.c (ffffffff818cd08a)
Location: include/linux/jump_label.h:144
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818cdf03)
Location: include/linux/jump_label.h:144
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/sched/core.c (ffffffff810b7d4c)
Location: include/linux/jump_label.h:145
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810c2d9c)
Location: include/linux/jump_label.h:145
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/rt.c (ffffffff810caa60)
Location: include/linux/jump_label.h:145
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/core.c (ffffffff810bf8b0)
Location: include/linux/jump_label.h:145
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810cbc5f)
Location: include/linux/jump_label.h:145
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/rt.c (ffffffff810d3ccf)
Location: include/linux/jump_label.h:145
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e331a)
Location: include/linux/jump_label.h:145
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff810c8bb5)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810d2243)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:place_entity
```
```
In kernel/sched/rt.c (ffffffff810dd96f)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/pelt.c (ffffffff810e7217)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810ee3b8)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff810d0592)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810dd1f3)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:place_entity
```
```
In kernel/sched/rt.c (ffffffff810e4957)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/pelt.c (ffffffff810edf75)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f5175)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff810da542)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810e7623)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:place_entity
```
```
In kernel/sched/rt.c (ffffffff810efb27)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/pelt.c (ffffffff810f9b55)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81100df5)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff810dd4f5)
Location: include/linux/jump_label.h:203
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810eddd5)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine_weight
  - kernel/sched/fair.c:wake_affine_weight
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/rt.c (ffffffff810f9507)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:do_sched_rt_period_timer
```
```
In kernel/sched/pelt.c (ffffffff81103bae)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110b605)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff810db695)
Location: include/linux/jump_label.h:203
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810ebbf5)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine_weight
  - kernel/sched/fair.c:wake_affine_weight
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/rt.c (ffffffff810f7807)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/pelt.c (ffffffff811022aa)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff811084e4)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff810e512b)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
```
In kernel/sched/fair.c (ffffffff810ed755)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:sched_slice
  - kernel/sched/fair.c:sched_slice
```
```
In kernel/sched/rt.c (ffffffff810f94b5)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/pelt.c (ffffffff8110461e)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81109c94)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff810fc0b2)
Location: include/linux/jump_label.h:215
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
```
In kernel/sched/fair.c (ffffffff81106465)
Location: include/linux/jump_label.h:215
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:sched_slice
  - kernel/sched/fair.c:sched_slice
```
```
In kernel/sched/rt.c (ffffffff81112c75)
Location: include/linux/jump_label.h:215
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/pelt.c (ffffffff81121853)
Location: include/linux/jump_label.h:215
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81128066)
Location: include/linux/jump_label.h:215
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff811185b5)
Location: include/linux/jump_label.h:210
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
```
In kernel/sched/fair.c (ffffffff81122b24)
Location: include/linux/jump_label.h:210
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:sched_slice
  - kernel/sched/fair.c:sched_slice
```
```
In kernel/sched/build_policy.c (ffffffff81136cd3)
Location: include/linux/jump_label.h:210
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:pull_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff81145d2d)
Location: include/linux/jump_label.h:210
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
  - kernel/sched/build_utility.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff8113fca2)
Location: include/linux/jump_label.h:210
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
```
In kernel/sched/fair.c (ffffffff8114a1c3)
Location: include/linux/jump_label.h:210
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:sched_slice
  - kernel/sched/fair.c:sched_slice
```
```
In kernel/sched/build_policy.c (ffffffff81161353)
Location: include/linux/jump_label.h:210
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:pull_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff81172edd)
Location: include/linux/jump_label.h:210
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
  - kernel/sched/build_utility.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff81142455)
Location: include/linux/jump_label.h:210
Inline: True
```
```
In kernel/sched/fair.c (ffffffff8115a093)
Location: include/linux/jump_label.h:210
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:sched_slice
  - kernel/sched/fair.c:sched_slice
```
```
In kernel/sched/build_policy.c (ffffffff81171b8f)
Location: include/linux/jump_label.h:210
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:pull_rt_task
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
In kernel/sched/core.c (ffffffff81155524)
Location: include/linux/jump_label.h:210
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_can_stop_tick
```
```
In kernel/sched/fair.c (ffffffff811667e6)
Location: include/linux/jump_label.h:210
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup_fair
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:pick_eevdf
```
```
In kernel/sched/build_policy.c (ffffffff8117f49f)
Location: include/linux/jump_label.h:210
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:pull_rt_task
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
In kernel/sched/core.c (ffff80001013a018)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffff800010145dd0)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:place_entity
```
```
In kernel/sched/rt.c (ffff800010150f28)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/pelt.c (ffff80001015e4f0)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffff8000101656c0)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000187708)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (c0000000001998ac)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/rt.c (c0000000001a1d94)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/pelt.c (c0000000001b3344)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (c0000000001bca08)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
</details>
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
In kernel/sched/core.c (ffffffff810d49f2)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810e17d3)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:place_entity
```
```
In kernel/sched/rt.c (ffffffff810e9417)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/pelt.c (ffffffff810f2f55)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810fa105)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff810c3042)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810d08b3)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:place_entity
```
```
In kernel/sched/rt.c (ffffffff810d8ee7)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/pelt.c (ffffffff810e3065)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810ea2e5)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff810d1832)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810ddb53)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:place_entity
```
```
In kernel/sched/rt.c (ffffffff810e6057)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/pelt.c (ffffffff810f0085)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f72c5)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff810dc1f6)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810e9633)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:place_entity
```
```
In kernel/sched/rt.c (ffffffff810efd57)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/pelt.c (ffffffff810fb0f5)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff811023a5)
Location: include/linux/jump_label.h:203
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
</details>
</li>
</ul>

## Differences
