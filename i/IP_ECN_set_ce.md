# Function: <code>IP_ECN_set_ce</code>

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
In net/core/filter.c (ffffffff81924b58)
Location: include/net/inet_ecn.h:75
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff819f50d4)
Location: include/net/inet_ecn.h:75
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
In net/core/filter.c (ffffffff81956f88)
Location: include/net/inet_ecn.h:75
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2bd84)
Location: include/net/inet_ecn.h:75
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
In net/core/filter.c (ffffffff81a2bff5)
Location: include/net/inet_ecn.h:76
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1df6f)
Location: include/net/inet_ecn.h:76
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81a2d5d5)
Location: include/net/inet_ecn.h:77
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c83d)
Location: include/net/inet_ecn.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81a14939)
Location: include/net/inet_ecn.h:77
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a48a)
Location: include/net/inet_ecn.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81ac5499)
Location: include/net/inet_ecn.h:77
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdeaaa)
Location: include/net/inet_ecn.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81c4283d)
Location: include/net/inet_ecn.h:77
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81d75932)
Location: include/net/inet_ecn.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81df781d)
Location: include/net/inet_ecn.h:77
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41f62)
Location: include/net/inet_ecn.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81e69529)
Location: include/net/inet_ecn.h:77
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa17e3)
Location: include/net/inet_ecn.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81f28a7e)
Location: include/net/inet_ecn.h:77
Inline: True
Inline callers:
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff8206eb03)
Location: include/net/inet_ecn.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
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
In net/core/filter.c (ffff800010bf8770)
Location: include/net/inet_ecn.h:75
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffff800010cea908)
Location: include/net/inet_ecn.h:75
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
In net/core/filter.c (c0d123ac)
Location: include/net/inet_ecn.h:75
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (c0df2828)
Location: include/net/inet_ecn.h:75
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
In net/core/filter.c (c000000000cdf6c8)
Location: include/net/inet_ecn.h:75
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (c000000000e0e398)
Location: include/net/inet_ecn.h:75
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
In net/core/filter.c (ffffffe00077a446)
Location: include/net/inet_ecn.h:75
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffe000838336)
Location: include/net/inet_ecn.h:75
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
In net/core/filter.c (ffffffff818f6f58)
Location: include/net/inet_ecn.h:75
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb414)
Location: include/net/inet_ecn.h:75
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
In drivers/net/vxlan.c (ffffffff81772fc4)
Location: include/net/inet_ecn.h:75
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/core/filter.c (ffffffff818b0d88)
Location: include/net/inet_ecn.h:75
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967f1d)
Location: include/net/inet_ecn.h:75
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81988204)
Location: include/net/inet_ecn.h:75
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
In net/core/filter.c (ffffffff81947f88)
Location: include/net/inet_ecn.h:75
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35e94)
Location: include/net/inet_ecn.h:75
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
In net/core/filter.c (ffffffff81969898)
Location: include/net/inet_ecn.h:75
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41804)
Location: include/net/inet_ecn.h:75
Inline: True
```
</details>
</li>
</ul>

## Differences
