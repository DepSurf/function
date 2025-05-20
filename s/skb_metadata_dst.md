# Function: <code>skb_metadata_dst</code>

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
In net/core/dev.c (ffffffff817141d2)
Location: include/net/dst_metadata.h:15
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81731b06)
Location: include/net/dst_metadata.h:15
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff8175549a)
Location: include/net/dst_metadata.h:15
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8178cdbe)
Location: include/net/dst_metadata.h:15
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff817d70a2)
Location: include/net/dst_metadata.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/dev.c (ffffffff8177bfe2)
Location: include/net/dst_metadata.h:15
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff8179baac)
Location: include/net/dst_metadata.h:15
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff817c1629)
Location: include/net/dst_metadata.h:15
Inline: True
```
```
In net/ipv4/arp.c (ffffffff817fa3e1)
Location: include/net/dst_metadata.h:15
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff818457b2)
Location: include/net/dst_metadata.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/dev.c (ffffffff817a9772)
Location: include/net/dst_metadata.h:15
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff817cbf1c)
Location: include/net/dst_metadata.h:15
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff817f1b36)
Location: include/net/dst_metadata.h:15
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_noref
```
```
In net/ipv4/arp.c (ffffffff8182b2b1)
Location: include/net/dst_metadata.h:15
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff8187751b)
Location: include/net/dst_metadata.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/dev.c (ffffffff817c7d60)
Location: include/net/dst_metadata.h:27
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff817eb81e)
Location: include/net/dst_metadata.h:27
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff818116f3)
Location: include/net/dst_metadata.h:27
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8184c551)
Location: include/net/dst_metadata.h:27
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff8189c833)
Location: include/net/dst_metadata.h:27
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (ffffffff8183e43f)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818418f0)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff818664de)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81890ca4)
Location: include/net/dst_metadata.h:28
Inline: True
```
```
In net/ipv4/arp.c (ffffffff818cc207)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff8191f3ec)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (ffffffff818885a7)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff8188bd83)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff818b5005)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff818e4aa5)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (ffffffff8192275c)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff819774c9)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (ffffffff818a90f7)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff818acf63)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff818dabe5)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81911995)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (ffffffff8195156e)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff819ad0f3)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (ffffffff818f4857)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff818f8802)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81927655)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81974108)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (ffffffff819b5e26)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81a1a259)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (ffffffff81926807)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff8192a9a2)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81959d15)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff819aab28)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (ffffffff819ecb46)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81a50ec9)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (ffffffff819fac24)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff819fe6d2)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81a2d4e5)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81a94e54)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (ffffffff81adab16)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81b48549)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (ffffffff819fa834)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff819fe2d2)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81a2ed85)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81a9ee54)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (ffffffff81ae75b6)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81b57129)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (ffffffff819e0a24)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff819e4b42)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81a16db5)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81a89dbb)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (ffffffff81ad2876)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81b44d19)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (ffffffff81a90da4)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff81a95530)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81ac8245)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81b44c4b)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (ffffffff81b914c6)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81c0be29)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (ffffffff81c06e3b)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff81c0bc92)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff81c4586e)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81cd1969)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (ffffffff81d22822)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81da6cc4)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (ffffffff81db76b2)
Location: include/net/dst_metadata.h:43
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff81dbd6c0)
Location: include/net/dst_metadata.h:43
Inline: True
Inline callers:
  - net/core/dev.c:tun_dst_unclone
```
```
In net/core/filter.c (ffffffff81df9a1e)
Location: include/net/dst_metadata.h:43
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81e91ea9)
Location: include/net/dst_metadata.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (ffffffff81ee9d7e)
Location: include/net/dst_metadata.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81f76294)
Location: include/net/dst_metadata.h:43
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (ffffffff81e27fee)
Location: include/net/dst_metadata.h:43
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff81e2df00)
Location: include/net/dst_metadata.h:43
Inline: True
Inline callers:
  - net/core/dev.c:tun_dst_unclone
```
```
In net/core/filter.c (ffffffff81e6b8fa)
Location: include/net/dst_metadata.h:43
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81ef0629)
Location: include/net/dst_metadata.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (ffffffff81f496e2)
Location: include/net/dst_metadata.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81fd6324)
Location: include/net/dst_metadata.h:43
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (ffffffff81ee6071)
Location: include/net/dst_metadata.h:43
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff81eec2e0)
Location: include/net/dst_metadata.h:43
Inline: True
Inline callers:
  - net/core/dev.c:tun_dst_unclone
```
```
In net/core/filter.c (ffffffff81f2aa4a)
Location: include/net/dst_metadata.h:43
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81fb4779)
Location: include/net/dst_metadata.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (ffffffff8200f836)
Location: include/net/dst_metadata.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff820a3cb1)
Location: include/net/dst_metadata.h:43
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (ffff800010bc2b7c)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffff800010bcdf38)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffff800010bff9f4)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffff800010c5aeb4)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (ffff800010ca2640)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffff800010d14e5c)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (c0cddeb0)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (c0ce79f8)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (c0d15c30)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (c0d6a394)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (c0daf450)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (c0e1aab4)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (c000000000c9cb58)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (c000000000ca2564)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (c000000000ce3eac)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (c000000000d5cbdc)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (c000000000db5c70)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (c000000000e41cc4)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (ffffffe00074f8a4)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffe00075384c)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffe00077df9a)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffe0007c4274)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (ffffffe0007fe58e)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffe00085a5ae)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (ffffffff818c6807)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff818ca9a2)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff818f9ce5)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff8194a998)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (ffffffff8198c92e)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff819f0559)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In drivers/net/vxlan.c (ffffffff81770395)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fill_metadata_dst
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit_one
```
```
In net/core/flow_dissector.c (ffffffff81880747)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff818848e2)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff818b3b15)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81904488)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (ffffffff819463ee)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967365)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
```
```
In net/ipv6/route.c (ffffffff819ad319)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (ffffffff81917807)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff8191b9a2)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff8194ad15)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff819b5168)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (ffffffff819f7186)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81a5afd9)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
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
In net/core/flow_dissector.c (ffffffff81938a17)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/dev.c (ffffffff8193ccf2)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/filter.c (ffffffff8196c625)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff819be8ab)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/arp.c (ffffffff81a013a6)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81a672b9)
Location: include/net/dst_metadata.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
</details>
</li>
</ul>

## Differences
