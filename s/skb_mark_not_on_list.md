# Function: <code>skb_mark_not_on_list</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818987b8)
Location: include/linux/skbuff.h:1391
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (ffffffff818b7799)
Location: include/linux/skbuff.h:1391
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:validate_xmit_skb_list
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff818f8003)
Location: include/linux/skbuff.h:1391
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_input.c (ffffffff81915b28)
Location: include/linux/skbuff.h:1391
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff81916b2f)
Location: include/linux/skbuff.h:1391
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff81919a16)
Location: include/linux/skbuff.h:1391
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b822)
Location: include/linux/skbuff.h:1391
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff8198ce6c)
Location: include/linux/skbuff.h:1391
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff819983e5)
Location: include/linux/skbuff.h:1391
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff8199995b)
Location: include/linux/skbuff.h:1391
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
```
In net/ipv6/reassembly.c (ffffffff819c7a69)
Location: include/linux/skbuff.h:1391
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/core/sock.c (ffffffff818e2d5f)
Location: include/linux/skbuff.h:1481
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (ffffffff81903601)
Location: include/linux/skbuff.h:1481
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:validate_xmit_skb_list
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff8195772e)
Location: include/linux/skbuff.h:1481
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_input.c (ffffffff819780b6)
Location: include/linux/skbuff.h:1481
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_output.c (ffffffff8197bafd)
Location: include/linux/skbuff.h:1481
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf246)
Location: include/linux/skbuff.h:1481
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6d4f)
Location: include/linux/skbuff.h:1481
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff819f86de)
Location: include/linux/skbuff.h:1481
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81a04228)
Location: include/linux/skbuff.h:1481
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81a0588d)
Location: include/linux/skbuff.h:1481
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
```
In net/ipv6/netfilter.c (ffffffff81a48709)
Location: include/linux/skbuff.h:1481
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/sock.c (ffffffff81914f3f)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (ffffffff819363b4)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:validate_xmit_skb_list
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff8198dbce)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_input.c (ffffffff819aea26)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_output.c (ffffffff819b21f2)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff81a05de6)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d9bf)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f33e)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81a3ae13)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c40d)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/netfilter.c (ffffffff81a7f2d1)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/sock.c (ffffffff819e805f)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (ffffffff81a0afc1)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff81a65680)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:try_bulk_dequeue_skb_slow
```
```
In net/netfilter/core.c (ffffffff81a8dd05)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/ip_input.c (ffffffff81a988af)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_output.c (ffffffff81a9ca8b)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output_gso
```
```
In net/ipv4/inet_fragment.c (ffffffff81af54f6)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/xfrm/xfrm_output.c (ffffffff81b201e9)
Location: include/linux/skbuff.h:1484
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81b21f65)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81b303d7)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81b31ac2)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/netfilter.c (ffffffff81b79f7d)
Location: include/linux/skbuff.h:1484
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/sock.c (ffffffff819e7ccf)
Location: include/linux/skbuff.h:1505
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (ffffffff81a0c216)
Location: include/linux/skbuff.h:1505
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff81a6d79c)
Location: include/linux/skbuff.h:1505
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:try_bulk_dequeue_skb_slow
```
```
In net/netfilter/core.c (ffffffff81a97cd5)
Location: include/linux/skbuff.h:1505
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/ip_input.c (ffffffff81aa283f)
Location: include/linux/skbuff.h:1505
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_output.c (ffffffff81aa6923)
Location: include/linux/skbuff.h:1505
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output_gso
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02256)
Location: include/linux/skbuff.h:1505
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2eb29)
Location: include/linux/skbuff.h:1505
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30926)
Location: include/linux/skbuff.h:1505
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ee83)
Location: include/linux/skbuff.h:1505
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81b406c2)
Location: include/linux/skbuff.h:1505
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/netfilter.c (ffffffff81b88ecd)
Location: include/linux/skbuff.h:1505
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/sock.c (ffffffff819cdc9f)
Location: include/linux/skbuff.h:1521
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (ffffffff819f23be)
Location: include/linux/skbuff.h:1521
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff81a55f0a)
Location: include/linux/skbuff.h:1521
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/netfilter/core.c (ffffffff81a83025)
Location: include/linux/skbuff.h:1521
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/ip_input.c (ffffffff81a8d91f)
Location: include/linux/skbuff.h:1521
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_output.c (ffffffff81a91a0c)
Location: include/linux/skbuff.h:1521
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff81aedb64)
Location: include/linux/skbuff.h:1521
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c8da)
Location: include/linux/skbuff.h:1521
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e653)
Location: include/linux/skbuff.h:1521
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81b2bc53)
Location: include/linux/skbuff.h:1521
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81b2eb02)
Location: include/linux/skbuff.h:1521
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/netfilter.c (ffffffff81b77cf5)
Location: include/linux/skbuff.h:1521
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In kernel/bpf/cpumap.c (ffffffff8126d174)
Location: include/linux/skbuff.h:1534
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In net/core/sock.c (ffffffff81a7d47f)
Location: include/linux/skbuff.h:1534
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (ffffffff81aa428e)
Location: include/linux/skbuff.h:1534
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff81b0ecba)
Location: include/linux/skbuff.h:1534
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/netfilter/core.c (ffffffff81b3ccb5)
Location: include/linux/skbuff.h:1534
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/ip_input.c (ffffffff81b48aef)
Location: include/linux/skbuff.h:1534
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_output.c (ffffffff81b4cdea)
Location: include/linux/skbuff.h:1534
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff81badf1d)
Location: include/linux/skbuff.h:1534
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/xfrm/xfrm_output.c (ffffffff81be124a)
Location: include/linux/skbuff.h:1534
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81be314f)
Location: include/linux/skbuff.h:1534
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81bf1db1)
Location: include/linux/skbuff.h:1534
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4e32)
Location: include/linux/skbuff.h:1534
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/netfilter.c (ffffffff81c42815)
Location: include/linux/skbuff.h:1534
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In kernel/bpf/cpumap.c (ffffffff812bc280)
Location: include/linux/skbuff.h:1883
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In net/core/sock.c (ffffffff81bf0add)
Location: include/linux/skbuff.h:1883
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (ffffffff81c1bd11)
Location: include/linux/skbuff.h:1883
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/gro.c (ffffffff81c5423a)
Location: include/linux/skbuff.h:1883
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
```
In net/sched/sch_generic.c (ffffffff81c95e9a)
Location: include/linux/skbuff.h:1883
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/netfilter/core.c (ffffffff81cc9167)
Location: include/linux/skbuff.h:1883
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/ip_input.c (ffffffff81cd5f02)
Location: include/linux/skbuff.h:1883
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_output.c (ffffffff81cda51e)
Location: include/linux/skbuff.h:1883
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff81d40fff)
Location: include/linux/skbuff.h:1883
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/xfrm/xfrm_output.c (ffffffff81d78164)
Location: include/linux/skbuff.h:1883
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a36b)
Location: include/linux/skbuff.h:1883
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a792)
Location: include/linux/skbuff.h:1883
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ip6_input.c (ffffffff81d8dc65)
Location: include/linux/skbuff.h:1883
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/netfilter.c (ffffffff81de144c)
Location: include/linux/skbuff.h:1883
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/packet/af_packet.c (ffffffff81df1707)
Location: include/linux/skbuff.h:1883
Inline: True
Inline callers:
  - net/packet/af_packet.c:nf_hook_direct_egress
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
In kernel/bpf/cpumap.c (ffffffff8131f670)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In net/core/sock.c (ffffffff81d9d14d)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (ffffffff81dccce1)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/gro.c (ffffffff81e099be)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
```
In net/sched/sch_generic.c (ffffffff81e51a7a)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/netfilter/core.c (ffffffff81e88cf7)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/ip_input.c (ffffffff81e963c2)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_output.c (ffffffff81e9acde)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff81f09d8f)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44a04)
Location: include/linux/skbuff.h:1741
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81f472c1)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81f58726)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ip6_input.c (ffffffff81f5bdb5)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/netfilter.c (ffffffff81fb38ac)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/packet/af_packet.c (ffffffff81fc56a7)
Location: include/linux/skbuff.h:1741
Inline: True
Inline callers:
  - net/packet/af_packet.c:nf_hook_direct_egress
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
In kernel/bpf/cpumap.c (ffffffff8134f4d0)
Location: include/linux/skbuff.h:1770
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In net/core/sock.c (ffffffff81e0b99d)
Location: include/linux/skbuff.h:1770
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (ffffffff81e3d841)
Location: include/linux/skbuff.h:1770
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/gro.c (ffffffff81e7c19e)
Location: include/linux/skbuff.h:1770
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
```
In net/sched/sch_generic.c (ffffffff81ead2bf)
Location: include/linux/skbuff.h:1770
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/netfilter/core.c (ffffffff81ee6c67)
Location: include/linux/skbuff.h:1770
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/ip_input.c (ffffffff81ef4bf2)
Location: include/linux/skbuff.h:1770
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_output.c (ffffffff81ef9673)
Location: include/linux/skbuff.h:1770
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6989f)
Location: include/linux/skbuff.h:1770
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa41e4)
Location: include/linux/skbuff.h:1770
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6d05)
Location: include/linux/skbuff.h:1770
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81fb8369)
Location: include/linux/skbuff.h:1770
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ip6_input.c (ffffffff81fbbb65)
Location: include/linux/skbuff.h:1770
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/netfilter.c (ffffffff82013fc7)
Location: include/linux/skbuff.h:1770
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/packet/af_packet.c (ffffffff820262b7)
Location: include/linux/skbuff.h:1770
Inline: True
Inline callers:
  - net/packet/af_packet.c:nf_hook_direct_egress
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
In kernel/bpf/cpumap.c (ffffffff81376b40)
Location: include/linux/skbuff.h:1777
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In net/core/sock.c (ffffffff81ec838d)
Location: include/linux/skbuff.h:1777
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (ffffffff81efc0e1)
Location: include/linux/skbuff.h:1777
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/gro.c (ffffffff81f3c4ee)
Location: include/linux/skbuff.h:1777
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
```
In net/sched/sch_generic.c (ffffffff81f6fd5f)
Location: include/linux/skbuff.h:1777
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/netfilter/core.c (ffffffff81faaa77)
Location: include/linux/skbuff.h:1777
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/ip_input.c (ffffffff81fb8b92)
Location: include/linux/skbuff.h:1777
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_output.c (ffffffff81fbd590)
Location: include/linux/skbuff.h:1777
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff8202ff1f)
Location: include/linux/skbuff.h:1777
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/xfrm/xfrm_output.c (ffffffff82071514)
Location: include/linux/skbuff.h:1777
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff82073fe7)
Location: include/linux/skbuff.h:1777
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff82085958)
Location: include/linux/skbuff.h:1777
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ip6_input.c (ffffffff82088f95)
Location: include/linux/skbuff.h:1777
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/netfilter.c (ffffffff820e311e)
Location: include/linux/skbuff.h:1777
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/packet/af_packet.c (ffffffff820f5cc7)
Location: include/linux/skbuff.h:1777
Inline: True
Inline callers:
  - net/packet/af_packet.c:nf_hook_direct_egress
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
In net/core/sock.c (ffff800010badd40)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (ffff800010bd4a00)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__napi_gro_flush_chain
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:validate_xmit_skb_list
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffff800010c392a0)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_input.c (ffff800010c5efa0)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_output.c (ffff800010c63f4c)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_fragment.c (ffff800010cbed70)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/xfrm/xfrm_output.c (ffff800010cec754)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffff800010cee460)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffff800010cfbea4)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffff800010cfd6d8)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/netfilter.c (ffff800010d4a550)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/sock.c (c0ccb854)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (c0ceefcc)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__napi_gro_flush_chain
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:validate_xmit_skb_list
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (c0d4b788)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_input.c (c0d6e69c)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_output.c (c0d72644)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_fragment.c (c0dca510)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/xfrm/xfrm_output.c (c0df4694)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (c0df62f8)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (c0e03160)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (c0e04ed0)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/netfilter.c (c0e4bb88)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/sock.c (c000000000c8373c)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (c000000000cb3b14)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__napi_gro_flush_chain
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:validate_xmit_skb_list
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (c000000000d32070)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_input.c (c000000000d61b44)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_output.c (c000000000d6625c)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_fragment.c (c000000000dd9448)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/xfrm/xfrm_output.c (c000000000e109a0)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (c000000000e130b8)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (c000000000e23770)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (c000000000e25778)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/netfilter.c (c000000000e80614)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/sock.c (ffffffe00073fe1c)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (ffffffe00075e7b6)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:validate_xmit_skb_list
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffffffe0007aa7f8)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_input.c (ffffffe0007c74e2)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_output.c (ffffffe0007ca7c8)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffe000814a8a)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/xfrm/xfrm_output.c (ffffffe000839e26)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b6ac)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffe000846836)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffe000847c82)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/netfilter.c (ffffffe000883a40)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/sock.c (ffffffff818b4f3f)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (ffffffff818d6384)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:validate_xmit_skb_list
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff8192da3e)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_input.c (ffffffff8194e896)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_output.c (ffffffff81952062)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff819a5b86)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/xfrm/xfrm_output.c (ffffffff819cd04f)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce9ce)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff819da4a3)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff819dba9d)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/netfilter.c (ffffffff81a1e961)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/sock.c (ffffffff8186ee8f)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (ffffffff818901c4)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:validate_xmit_skb_list
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff818e753e)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_input.c (ffffffff81908386)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_output.c (ffffffff8190bb52)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f646)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/xfrm/xfrm_output.c (ffffffff81989e3f)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b790)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81997263)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff8199885d)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/netfilter.c (ffffffff819db721)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/sock.c (ffffffff81905f3f)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (ffffffff819273b4)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:validate_xmit_skb_list
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff8197ebce)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199aa64)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_enqueue_packet
```
```
In net/ipv4/ip_input.c (ffffffff819b9066)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_output.c (ffffffff819bc832)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10426)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/xfrm/xfrm_output.c (ffffffff81a37acf)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81a3944e)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81a44f23)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81a4651d)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/netfilter.c (ffffffff81a893e1)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/sock.c (ffffffff81926f6f)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (ffffffff81948a14)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:validate_xmit_skb_list
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff819a113e)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/ip_input.c (ffffffff819c2956)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv4/ip_output.c (ffffffff819c6142)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1ac76)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/xfrm/xfrm_output.c (ffffffff81a4348f)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44e7e)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81a50be3)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81a5224d)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/netfilter.c (ffffffff81a96041)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
</details>
</li>
</ul>

## Differences
