# Function: <code>skb_set_inner_network_header</code>

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
In net/ipv4/af_inet.c (ffffffff817934c4)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/ip6_offload.c (ffffffff81800aaf)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/ipv4/af_inet.c (ffffffff81800a71)
Location: include/linux/skbuff.h:2098
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/ip6_offload.c (ffffffff81872220)
Location: include/linux/skbuff.h:2098
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/ipv4/af_inet.c (ffffffff818319b1)
Location: include/linux/skbuff.h:2115
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6811)
Location: include/linux/skbuff.h:2115
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/ipv4/af_inet.c (ffffffff81852f3d)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd26b)
Location: include/linux/skbuff.h:2154
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/ipv4/af_inet.c (ffffffff818d2d81)
Location: include/linux/skbuff.h:2241
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/ip6_offload.c (ffffffff8195204f)
Location: include/linux/skbuff.h:2241
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/ipv4/af_inet.c (ffffffff8192935f)
Location: include/linux/skbuff.h:2252
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/ip6_offload.c (ffffffff819ab5eb)
Location: include/linux/skbuff.h:2252
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/ipv4/af_inet.c (ffffffff81958f9c)
Location: include/linux/skbuff.h:2330
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/ip6_offload.c (ffffffff819e20ab)
Location: include/linux/skbuff.h:2330
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff818ea3f8)
Location: include/linux/skbuff.h:2418
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/ipv4/af_inet.c (ffffffff819bda6a)
Location: include/linux/skbuff.h:2418
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6245)
Location: include/linux/skbuff.h:2418
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_offload.c (ffffffff81a50d3b)
Location: include/linux/skbuff.h:2418
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff8191c575)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/ipv4/af_inet.c (ffffffff819f4676)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2cec5)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87957)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff819f06d7)
Location: include/linux/skbuff.h:2455
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/ipv4/af_inet.c (ffffffff81ae2386)
Location: include/linux/skbuff.h:2455
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1edcd)
Location: include/linux/skbuff.h:2455
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
```
```
In net/ipv6/ip6_offload.c (ffffffff81b82e1b)
Location: include/linux/skbuff.h:2455
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff819f042c)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/ipv4/af_inet.c (ffffffff81aef20c)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2d67d)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
```
```
In net/ipv6/ip6_offload.c (ffffffff81b924a1)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff819d4d70)
Location: include/linux/skbuff.h:2492
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/ipv4/af_inet.c (ffffffff81ada96c)
Location: include/linux/skbuff.h:2492
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1b339)
Location: include/linux/skbuff.h:2492
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81b815f1)
Location: include/linux/skbuff.h:2492
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff81a84b00)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/ipv4/af_inet.c (ffffffff81b99bac)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_output.c (ffffffff81bdfba9)
Location: include/linux/skbuff.h:2521
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4d611)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff81bfaa0f)
Location: include/linux/skbuff.h:2889
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/ipv4/af_inet.c (ffffffff81d2bb48)
Location: include/linux/skbuff.h:2889
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_output.c (ffffffff81d76a8d)
Location: include/linux/skbuff.h:2889
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81dedbc3)
Location: include/linux/skbuff.h:2889
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff81da989f)
Location: include/linux/skbuff.h:2781
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/ipv4/af_inet.c (ffffffff81ef3758)
Location: include/linux/skbuff.h:2781
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_output.c (ffffffff81f432bd)
Location: include/linux/skbuff.h:2781
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc1ae3)
Location: include/linux/skbuff.h:2781
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff81e1839f)
Location: include/linux/skbuff.h:2835
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/ipv4/af_inet.c (ffffffff81f531e1)
Location: include/linux/skbuff.h:2835
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa2abd)
Location: include/linux/skbuff.h:2835
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff82022a63)
Location: include/linux/skbuff.h:2835
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff81ed583f)
Location: include/linux/skbuff.h:2842
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/ipv4/af_inet.c (ffffffff82019591)
Location: include/linux/skbuff.h:2842
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_output.c (ffffffff8206fdbd)
Location: include/linux/skbuff.h:2842
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff820f1b83)
Location: include/linux/skbuff.h:2842
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffff800010bb6ad0)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/ipv4/af_inet.c (ffff800010caa020)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_output.c (ffff800010cebb20)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_offload.c (ffff800010d5454c)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (c0cd39b8)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/ipv4/af_inet.c (c0db68e0)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_output.c (c0df3878)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_offload.c (c0e54b48)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (c000000000c8e4b0)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/ipv4/af_inet.c (c000000000dbf890)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_output.c (c000000000e0fa48)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_offload.c (c000000000e8cf34)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffe00074678c)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/ipv4/af_inet.c (ffffffe000804b36)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_output.c (ffffffe000839400)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_offload.c (ffffffe00088bedc)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff818bc575)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/ipv4/af_inet.c (ffffffff81994416)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc555)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_offload.c (ffffffff81a26fe7)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff818764b5)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/ipv4/af_inet.c (ffffffff8194ded6)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_output.c (ffffffff81989345)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_offload.c (ffffffff819e3da7)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff8190d575)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/ipv4/af_inet.c (ffffffff819fecb6)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_output.c (ffffffff81a36fd5)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_offload.c (ffffffff81a92b97)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff8192e6a5)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/ipv4/af_inet.c (ffffffff81a08d55)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42965)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9eca7)
Location: include/linux/skbuff.h:2432
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
```
</details>
</li>
</ul>

## Differences
