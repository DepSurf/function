# Function: <code>lwt_tun_info</code>

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
In net/core/filter.c (ffffffff81731b5e)
Location: include/net/ip_tunnels.h:351
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff817554b6)
Location: include/net/ip_tunnels.h:351
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/ip_tunnels.h:351
Inline: True
```
```
In net/ipv6/route.c (ffffffff817d7119)
Location: include/net/ip_tunnels.h:351
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
In net/core/filter.c (ffffffff8179bb21)
Location: include/net/ip_tunnels.h:441
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff817c1648)
Location: include/net/ip_tunnels.h:441
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/ip_tunnels.h:441
Inline: True
```
```
In net/ipv6/route.c (ffffffff8184582c)
Location: include/net/ip_tunnels.h:441
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
In net/core/filter.c (ffffffff817cbf98)
Location: include/net/ip_tunnels.h:462
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff817f1b55)
Location: include/net/ip_tunnels.h:462
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_noref
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/ip_tunnels.h:462
Inline: True
```
```
In net/ipv6/route.c (ffffffff81877581)
Location: include/net/ip_tunnels.h:462
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
In net/core/filter.c (ffffffff817eb835)
Location: include/net/ip_tunnels.h:464
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff8181171a)
Location: include/net/ip_tunnels.h:464
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/ip_tunnels.h:464
Inline: True
```
```
In net/ipv6/route.c (ffffffff8189c88d)
Location: include/net/ip_tunnels.h:464
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
In net/core/flow_dissector.c (ffffffff8183e6a1)
Location: include/net/ip_tunnels.h:471
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffff818664f5)
Location: include/net/ip_tunnels.h:471
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81890cd2)
Location: include/net/ip_tunnels.h:471
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/ip_tunnels.h:471
Inline: True
```
```
In net/ipv6/route.c (ffffffff8191f450)
Location: include/net/ip_tunnels.h:471
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
In net/core/flow_dissector.c (ffffffff818885cd)
Location: include/net/ip_tunnels.h:503
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff818b502e)
Location: include/net/ip_tunnels.h:503
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff818e4ace)
Location: include/net/ip_tunnels.h:503
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193b6c5)
Location: include/net/ip_tunnels.h:503
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
```
```
In net/ipv6/route.c (ffffffff819774ed)
Location: include/net/ip_tunnels.h:503
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
In net/core/flow_dissector.c (ffffffff818a9125)
Location: include/net/ip_tunnels.h:507
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff818dac0d)
Location: include/net/ip_tunnels.h:507
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff819119be)
Location: include/net/ip_tunnels.h:507
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196b3b5)
Location: include/net/ip_tunnels.h:507
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
```
```
In net/ipv6/route.c (ffffffff819ad117)
Location: include/net/ip_tunnels.h:507
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
In net/core/flow_dissector.c (ffffffff818f4885)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81927680)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81974131)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2085)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
```
```
In net/ipv6/route.c (ffffffff81a1a27d)
Location: include/net/ip_tunnels.h:508
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
In net/core/flow_dissector.c (ffffffff81926835)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81959d40)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff819aab51)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a08bf5)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
```
```
In net/ipv6/route.c (ffffffff81a50eed)
Location: include/net/ip_tunnels.h:508
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
In net/core/flow_dissector.c (ffffffff819fac52)
Location: include/net/ip_tunnels.h:512
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81a2d510)
Location: include/net/ip_tunnels.h:512
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81a94e79)
Location: include/net/ip_tunnels.h:512
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af89a5)
Location: include/net/ip_tunnels.h:512
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_encap_nlsize
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_encap_nlsize
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/route.c (ffffffff81b4856d)
Location: include/net/ip_tunnels.h:512
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
In net/core/flow_dissector.c (ffffffff819fa862)
Location: include/net/ip_tunnels.h:514
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81a2edad)
Location: include/net/ip_tunnels.h:514
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81a9ee79)
Location: include/net/ip_tunnels.h:514
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05775)
Location: include/net/ip_tunnels.h:514
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_encap_nlsize
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_encap_nlsize
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/route.c (ffffffff81b5714d)
Location: include/net/ip_tunnels.h:514
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
In net/core/flow_dissector.c (ffffffff819e0a66)
Location: include/net/ip_tunnels.h:514
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81a17553)
Location: include/net/ip_tunnels.h:514
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81a89df1)
Location: include/net/ip_tunnels.h:514
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af0ff5)
Location: include/net/ip_tunnels.h:514
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_encap_nlsize
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_encap_nlsize
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/route.c (ffffffff81b44d4a)
Location: include/net/ip_tunnels.h:514
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
In net/core/flow_dissector.c (ffffffff81a90de6)
Location: include/net/ip_tunnels.h:515
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81ac8aa3)
Location: include/net/ip_tunnels.h:515
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81b44c81)
Location: include/net/ip_tunnels.h:515
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1705)
Location: include/net/ip_tunnels.h:515
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_encap_nlsize
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_encap_nlsize
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/route.c (ffffffff81c0be5a)
Location: include/net/ip_tunnels.h:515
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
In net/core/flow_dissector.c (ffffffff81c06e7d)
Location: include/net/ip_tunnels.h:526
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81c45e89)
Location: include/net/ip_tunnels.h:526
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81cd19a7)
Location: include/net/ip_tunnels.h:526
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d44df5)
Location: include/net/ip_tunnels.h:526
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_encap_nlsize
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_encap_nlsize
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/route.c (ffffffff81da6cf8)
Location: include/net/ip_tunnels.h:526
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
In net/core/flow_dissector.c (ffffffff81db68fb)
Location: include/net/ip_tunnels.h:538
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81df9e7f)
Location: include/net/ip_tunnels.h:538
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81e91ee7)
Location: include/net/ip_tunnels.h:538
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0e0c5)
Location: include/net/ip_tunnels.h:538
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_encap_nlsize
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_encap_nlsize
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/route.c (ffffffff81f762c8)
Location: include/net/ip_tunnels.h:538
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
In net/core/flow_dissector.c (ffffffff81e26cd1)
Location: include/net/ip_tunnels.h:542
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81e6b665)
Location: include/net/ip_tunnels.h:542
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81ef066d)
Location: include/net/ip_tunnels.h:542
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6dd75)
Location: include/net/ip_tunnels.h:542
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_encap_nlsize
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_encap_nlsize
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/route.c (ffffffff81fd635e)
Location: include/net/ip_tunnels.h:542
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
In net/core/flow_dissector.c (ffffffff81ee4c63)
Location: include/net/ip_tunnels.h:525
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81f2a745)
Location: include/net/ip_tunnels.h:525
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff81fb47bd)
Location: include/net/ip_tunnels.h:525
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034495)
Location: include/net/ip_tunnels.h:525
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_encap_nlsize
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_encap_nlsize
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/route.c (ffffffff820a3ceb)
Location: include/net/ip_tunnels.h:525
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
In net/core/flow_dissector.c (ffff800010bc2ba0)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffff800010bffa1c)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffff800010c5aedc)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc1f34)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
```
```
In net/ipv6/route.c (ffff800010d14e78)
Location: include/net/ip_tunnels.h:508
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
In net/core/flow_dissector.c (c0cddee4)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (c0d15c68)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (c0d6a3c8)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (c0dcd5c4)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
```
```
In net/ipv6/route.c (c0e1aae0)
Location: include/net/ip_tunnels.h:508
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
In net/core/flow_dissector.c (c000000000c9cb8c)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (c000000000ce3edc)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (c000000000d5cc38)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (c000000000ddd458)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
```
```
In net/ipv6/route.c (c000000000e41cec)
Location: include/net/ip_tunnels.h:508
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
In net/core/flow_dissector.c (ffffffe00074f8bc)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffe00077dfbc)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffe0007c4296)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817498)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
```
```
In net/ipv6/route.c (ffffffe00085a5ce)
Location: include/net/ip_tunnels.h:508
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
In net/core/flow_dissector.c (ffffffff818c6835)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff818f9d10)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff8194a9c1)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8995)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
```
```
In net/ipv6/route.c (ffffffff819f057d)
Location: include/net/ip_tunnels.h:508
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
In drivers/net/vxlan.c (ffffffff817703b4)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fill_metadata_dst
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit_one
```
```
In net/core/flow_dissector.c (ffffffff81880775)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff818b3b40)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff819044b1)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962455)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967381)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
```
```
In net/ipv6/route.c (ffffffff819ad33d)
Location: include/net/ip_tunnels.h:508
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
In net/core/flow_dissector.c (ffffffff81917835)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff8194ad40)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff819b5191)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13235)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
```
```
In net/ipv6/route.c (ffffffff81a5affd)
Location: include/net/ip_tunnels.h:508
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
In net/core/flow_dissector.c (ffffffff81938a45)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff8196c650)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_opt
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/route.c (ffffffff819be8d4)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1dc05)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
```
```
In net/ipv6/route.c (ffffffff81a672dd)
Location: include/net/ip_tunnels.h:508
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
</details>
</li>
</ul>

## Differences
