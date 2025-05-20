# Function: <code>IP6_ECN_set_ce</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81924ae5)
Location: include/net/inet_ecn.h:121
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4f7b)
Location: include/net/inet_ecn.h:121
Inline: True
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
In net/core/filter.c (ffffffff81956f15)
Location: include/net/inet_ecn.h:121
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2bc2b)
Location: include/net/inet_ecn.h:121
Inline: True
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
In net/core/filter.c (ffffffff81a2c0d1)
Location: include/net/inet_ecn.h:136
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1ddf7)
Location: include/net/inet_ecn.h:136
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81a2d6a9)
Location: include/net/inet_ecn.h:134
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c6c5)
Location: include/net/inet_ecn.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81a149dd)
Location: include/net/inet_ecn.h:134
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a320)
Location: include/net/inet_ecn.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81ac553d)
Location: include/net/inet_ecn.h:134
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde940)
Location: include/net/inet_ecn.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81c428bf)
Location: include/net/inet_ecn.h:134
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81d757a4)
Location: include/net/inet_ecn.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81df789f)
Location: include/net/inet_ecn.h:134
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41dc1)
Location: include/net/inet_ecn.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81e695aa)
Location: include/net/inet_ecn.h:134
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1652)
Location: include/net/inet_ecn.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81f28afa)
Location: include/net/inet_ecn.h:134
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff8206e972)
Location: include/net/inet_ecn.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
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
In net/core/filter.c (ffff800010bf86f8)
Location: include/net/inet_ecn.h:121
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffff800010cea808)
Location: include/net/inet_ecn.h:121
Inline: True
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
In net/core/filter.c (c0d12328)
Location: include/net/inet_ecn.h:121
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (c0df27a4)
Location: include/net/inet_ecn.h:121
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
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
In net/core/filter.c (c000000000cdf634)
Location: include/net/inet_ecn.h:121
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (c000000000e0e444)
Location: include/net/inet_ecn.h:121
Inline: True
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
In net/core/filter.c (ffffffe00077a3e6)
Location: include/net/inet_ecn.h:121
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffe000838382)
Location: include/net/inet_ecn.h:121
Inline: True
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
In net/core/filter.c (ffffffff818f6ee5)
Location: include/net/inet_ecn.h:121
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb2bb)
Location: include/net/inet_ecn.h:121
Inline: True
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
In drivers/net/vxlan.c (ffffffff81772e12)
Location: include/net/inet_ecn.h:121
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/core/filter.c (ffffffff818b0d15)
Location: include/net/inet_ecn.h:121
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967e36)
Location: include/net/inet_ecn.h:121
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff819880ab)
Location: include/net/inet_ecn.h:121
Inline: True
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
In net/core/filter.c (ffffffff81947f15)
Location: include/net/inet_ecn.h:121
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35d3b)
Location: include/net/inet_ecn.h:121
Inline: True
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
In net/core/filter.c (ffffffff81969825)
Location: include/net/inet_ecn.h:121
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81a416ab)
Location: include/net/inet_ecn.h:121
Inline: True
```
</details>
</li>
</ul>

## Differences
