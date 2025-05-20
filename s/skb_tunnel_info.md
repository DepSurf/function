# Function: <code>skb_tunnel_info</code>

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
In net/core/filter.c (ffffffff81731b06)
Location: include/net/dst_metadata.h:25
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff8175549a)
Location: include/net/dst_metadata.h:25
Inline: True
```
```
In net/ipv6/route.c (ffffffff817d70a2)
Location: include/net/dst_metadata.h:25
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
In net/core/filter.c (ffffffff8179baac)
Location: include/net/dst_metadata.h:25
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff817c1629)
Location: include/net/dst_metadata.h:25
Inline: True
```
```
In net/ipv6/route.c (ffffffff818457b2)
Location: include/net/dst_metadata.h:25
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
In net/core/filter.c (ffffffff817cbf1c)
Location: include/net/dst_metadata.h:25
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff817f1b36)
Location: include/net/dst_metadata.h:25
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_noref
```
```
In net/ipv6/route.c (ffffffff8187751b)
Location: include/net/dst_metadata.h:25
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
In net/core/filter.c (ffffffff817eb816)
Location: include/net/dst_metadata.h:37
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff818116f3)
Location: include/net/dst_metadata.h:37
Inline: True
```
```
In net/ipv6/route.c (ffffffff8189c833)
Location: include/net/dst_metadata.h:37
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
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffff818664d6)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81890ca4)
Location: include/net/dst_metadata.h:39
Inline: True
```
```
In net/ipv6/route.c (ffffffff8191f3ec)
Location: include/net/dst_metadata.h:39
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
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff818b5005)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff818e4aa5)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff819774c9)
Location: include/net/dst_metadata.h:39
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
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff818dabe5)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81911995)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff819ad0f3)
Location: include/net/dst_metadata.h:39
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
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81927655)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81974108)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81a1a259)
Location: include/net/dst_metadata.h:39
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
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81959d15)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff819aab28)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81a50ec9)
Location: include/net/dst_metadata.h:39
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
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81a2d4e5)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81a94e54)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81b48549)
Location: include/net/dst_metadata.h:39
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
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81a2ed85)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81a9ee54)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81b57129)
Location: include/net/dst_metadata.h:39
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
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81a16db5)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81a89dbb)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81b44d19)
Location: include/net/dst_metadata.h:39
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
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81ac8245)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81b44c4b)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81c0be29)
Location: include/net/dst_metadata.h:39
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
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81c4586e)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81cd1969)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81da6cc4)
Location: include/net/dst_metadata.h:39
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
In net/core/flow_dissector.c (ffffffff81db68bb)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81df9a1e)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81e91ea9)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81f76294)
Location: include/net/dst_metadata.h:54
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
In net/core/flow_dissector.c (ffffffff81e26c8b)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81e6b8fa)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81ef0629)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81fd6324)
Location: include/net/dst_metadata.h:54
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
In net/core/flow_dissector.c (ffffffff81ee4c1d)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81f2aa4a)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81fb4779)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff820a3cb1)
Location: include/net/dst_metadata.h:54
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
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffff800010bff9f4)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffff800010c5aeb4)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffff800010d14e5c)
Location: include/net/dst_metadata.h:39
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
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (c0d15c30)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (c0d6a394)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (c0e1aab4)
Location: include/net/dst_metadata.h:39
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
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (c000000000ce3eac)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (c000000000d5cbdc)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (c000000000e41cc4)
Location: include/net/dst_metadata.h:39
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
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffe00077df9a)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffe0007c4274)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffe00085a5ae)
Location: include/net/dst_metadata.h:39
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
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff818f9ce5)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff8194a998)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff819f0559)
Location: include/net/dst_metadata.h:39
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
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fill_metadata_dst
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit_one
```
```
In net/core/flow_dissector.c (ffffffff81880747)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff818b3b15)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81904488)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967365)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
```
```
In net/ipv6/route.c (ffffffff819ad319)
Location: include/net/dst_metadata.h:39
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
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff8194ad15)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff819b5168)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81a5afd9)
Location: include/net/dst_metadata.h:39
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
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff8196c625)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff819be8ab)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81a672b9)
Location: include/net/dst_metadata.h:39
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
</details>
</li>
</ul>

## Differences
