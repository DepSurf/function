# Function: <code>skb_list_del_init</code>

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
In net/core/dev.c (ffffffff818b7788)
Location: include/linux/skbuff.h:1396
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:__netif_receive_skb_list_core
```
```
In net/ipv4/ip_input.c (ffffffff81915b21)
Location: include/linux/skbuff.h:1396
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81999951)
Location: include/linux/skbuff.h:1396
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In net/core/dev.c (ffffffff819035f0)
Location: include/linux/skbuff.h:1486
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
```
```
In net/ipv4/ip_input.c (ffffffff819780af)
Location: include/linux/skbuff.h:1486
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81a05883)
Location: include/linux/skbuff.h:1486
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In net/core/dev.c (ffffffff819363a0)
Location: include/linux/skbuff.h:1483
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
```
```
In net/ipv4/ip_input.c (ffffffff819aea1f)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c403)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
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
In net/core/dev.c (ffffffff81a0afba)
Location: include/linux/skbuff.h:1494
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
```
```
In net/netfilter/core.c (ffffffff81a8dcee)
Location: include/linux/skbuff.h:1494
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/ip_input.c (ffffffff81a988a8)
Location: include/linux/skbuff.h:1494
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81b31ab8)
Location: include/linux/skbuff.h:1494
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
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
In net/core/dev.c (ffffffff81a0c20f)
Location: include/linux/skbuff.h:1515
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
```
```
In net/netfilter/core.c (ffffffff81a97cbe)
Location: include/linux/skbuff.h:1515
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/ip_input.c (ffffffff81aa2838)
Location: include/linux/skbuff.h:1515
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81b406b8)
Location: include/linux/skbuff.h:1515
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
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
In net/core/dev.c (ffffffff819f23b7)
Location: include/linux/skbuff.h:1531
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
```
```
In net/netfilter/core.c (ffffffff81a8300e)
Location: include/linux/skbuff.h:1531
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/ip_input.c (ffffffff81a8d918)
Location: include/linux/skbuff.h:1531
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81b2eaf8)
Location: include/linux/skbuff.h:1531
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
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
In kernel/bpf/cpumap.c (ffffffff8126d164)
Location: include/linux/skbuff.h:1544
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In net/core/dev.c (ffffffff81aa4287)
Location: include/linux/skbuff.h:1544
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
```
```
In net/netfilter/core.c (ffffffff81b3cc9e)
Location: include/linux/skbuff.h:1544
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/ip_input.c (ffffffff81b48ae8)
Location: include/linux/skbuff.h:1544
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4e28)
Location: include/linux/skbuff.h:1544
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
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
In kernel/bpf/cpumap.c (ffffffff812bc272)
Location: include/linux/skbuff.h:1893
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In net/core/dev.c (ffffffff81c1bd00)
Location: include/linux/skbuff.h:1893
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
```
In net/core/gro.c (ffffffff81c54233)
Location: include/linux/skbuff.h:1893
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
```
In net/netfilter/core.c (ffffffff81cc914f)
Location: include/linux/skbuff.h:1893
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/ip_input.c (ffffffff81cd5efb)
Location: include/linux/skbuff.h:1893
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81d8dc5b)
Location: include/linux/skbuff.h:1893
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
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
In kernel/bpf/cpumap.c (ffffffff8131f662)
Location: include/linux/skbuff.h:1751
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In net/core/dev.c (ffffffff81dcccd0)
Location: include/linux/skbuff.h:1751
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
```
In net/core/gro.c (ffffffff81e099b7)
Location: include/linux/skbuff.h:1751
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
```
In net/netfilter/core.c (ffffffff81e88cdf)
Location: include/linux/skbuff.h:1751
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/ip_input.c (ffffffff81e963bb)
Location: include/linux/skbuff.h:1751
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81f5bdab)
Location: include/linux/skbuff.h:1751
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
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
In kernel/bpf/cpumap.c (ffffffff8134f4c2)
Location: include/linux/skbuff.h:1787
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In net/core/dev.c (ffffffff81e3d830)
Location: include/linux/skbuff.h:1787
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
```
In net/core/gro.c (ffffffff81e7c197)
Location: include/linux/skbuff.h:1787
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
```
In net/netfilter/core.c (ffffffff81ee6c4f)
Location: include/linux/skbuff.h:1787
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/ip_input.c (ffffffff81ef4beb)
Location: include/linux/skbuff.h:1787
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81fbbb5b)
Location: include/linux/skbuff.h:1787
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
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
In kernel/bpf/cpumap.c (ffffffff81376b32)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In net/core/dev.c (ffffffff81efc0d0)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
```
In net/core/gro.c (ffffffff81f3c4e7)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
```
In net/netfilter/core.c (ffffffff81faaa5f)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/ip_input.c (ffffffff81fb8b8b)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff82088f8b)
Location: include/linux/skbuff.h:1794
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
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
In net/core/dev.c (ffff800010bd49ec)
Location: include/linux/skbuff.h:1483
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
```
```
In net/ipv4/ip_input.c (ffff800010c5ef98)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffff800010cfd6d0)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
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
In net/core/dev.c (c0ceefb4)
Location: include/linux/skbuff.h:1483
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
```
```
In net/ipv4/ip_input.c (c0d6e694)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (c0e04ec4)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
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
In net/core/dev.c (c000000000cb3af8)
Location: include/linux/skbuff.h:1483
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
```
```
In net/ipv4/ip_input.c (c000000000d61b3c)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (c000000000e2576c)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
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
In net/core/dev.c (ffffffe00075e7a6)
Location: include/linux/skbuff.h:1483
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
```
```
In net/ipv4/ip_input.c (ffffffe0007c74d4)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffe000847c74)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
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
In net/core/dev.c (ffffffff818d6370)
Location: include/linux/skbuff.h:1483
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
```
```
In net/ipv4/ip_input.c (ffffffff8194e88f)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff819dba93)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
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
In net/core/dev.c (ffffffff818901b0)
Location: include/linux/skbuff.h:1483
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
```
```
In net/ipv4/ip_input.c (ffffffff8190837f)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81998853)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
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
In net/core/dev.c (ffffffff819273a0)
Location: include/linux/skbuff.h:1483
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
```
```
In net/ipv4/ip_input.c (ffffffff819b905f)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81a46513)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
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
In net/core/dev.c (ffffffff81948a0d)
Location: include/linux/skbuff.h:1483
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
```
```
In net/ipv4/ip_input.c (ffffffff819c294f)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81a52243)
Location: include/linux/skbuff.h:1483
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
</details>
</li>
</ul>

## Differences
