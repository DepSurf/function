# Function: <code>skb_reset_mac_len</code>

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
In net/core/skbuff.c (ffffffff81709b2f)
Location: include/linux/skbuff.h:1935
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff8171a118)
Location: include/linux/skbuff.h:1935
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__skb_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff818097f0)
Location: include/linux/skbuff.h:1935
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81771e8f)
Location: include/linux/skbuff.h:2060
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81783c19)
Location: include/linux/skbuff.h:2060
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__skb_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff8187b2f1)
Location: include/linux/skbuff.h:2060
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8179efa0)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff817b11b5)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff817cbc92)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/8021q/vlan_core.c (ffffffff818afbb1)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff817bc709)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff817d1592)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff817ea72c)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/8021q/vlan_core.c (ffffffff818d6360)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81836dd9)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff8184b6a6)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81865e5c)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/8021q/vlan_core.c (ffffffff8195befa)
Location: include/linux/skbuff.h:2203
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81880f1a)
Location: include/linux/skbuff.h:2214
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818959f5)
Location: include/linux/skbuff.h:2214
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff818b3eda)
Location: include/linux/skbuff.h:2214
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/af_inet.c (ffffffff8192adbd)
Location: include/linux/skbuff.h:2214
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv6/ip6_offload.c (ffffffff819abd7f)
Location: include/linux/skbuff.h:2214
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff819b5776)
Location: include/linux/skbuff.h:2214
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff818a1db1)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818b76d9)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff818dc6d8)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/af_inet.c (ffffffff8195a53b)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv6/ip6_offload.c (ffffffff819e2931)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff819eca3b)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff818ec794)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81903517)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff819297db)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/af_inet.c (ffffffff819bf0bf)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/xfrm/xfrm_device.c (ffffffff819f83a1)
Location: include/linux/skbuff.h:2380
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81a515cf)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff81a5bbfc)
Location: include/linux/skbuff.h:2380
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8191e8c4)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff819362c7)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff8195be3b)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/af_inet.c (ffffffff819f5cff)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f001)
Location: include/linux/skbuff.h:2394
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81a881ef)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff81a927eb)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff819f0666)
Location: include/linux/skbuff.h:2417
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81a0aee8)
Location: include/linux/skbuff.h:2417
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81a30eac)
Location: include/linux/skbuff.h:2417
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/ipv4/af_inet.c (ffffffff81ae41ef)
Location: include/linux/skbuff.h:2417
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/xfrm/xfrm_device.c (ffffffff81b21ba5)
Location: include/linux/skbuff.h:2417
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_offload.c (ffffffff81b836bf)
Location: include/linux/skbuff.h:2417
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff81b8dc9e)
Location: include/linux/skbuff.h:2417
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff819f03ab)
Location: include/linux/skbuff.h:2438
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81a0c131)
Location: include/linux/skbuff.h:2438
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81a3333c)
Location: include/linux/skbuff.h:2438
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/ipv4/af_inet.c (ffffffff81af111f)
Location: include/linux/skbuff.h:2438
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30575)
Location: include/linux/skbuff.h:2438
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92d7f)
Location: include/linux/skbuff.h:2438
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff81b9d96d)
Location: include/linux/skbuff.h:2438
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff819d4ced)
Location: include/linux/skbuff.h:2454
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff819f22e4)
Location: include/linux/skbuff.h:2454
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81a15cd3)
Location: include/linux/skbuff.h:2454
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/ipv4/af_inet.c (ffffffff81adc8df)
Location: include/linux/skbuff.h:2454
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e3e9)
Location: include/linux/skbuff.h:2454
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81ed0)
Location: include/linux/skbuff.h:2454
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff81b8ca96)
Location: include/linux/skbuff.h:2454
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81a84a7d)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81aa41b4)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81ac6f03)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/ipv4/af_inet.c (ffffffff81b9bcb9)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/xfrm/xfrm_device.c (ffffffff81be2ed9)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4df50)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff81c58e56)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81bfaa88)
Location: include/linux/skbuff.h:2851
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81c12110)
Location: include/linux/skbuff.h:2851
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81c43b45)
Location: include/linux/skbuff.h:2851
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro.c (ffffffff81c5418b)
Location: include/linux/skbuff.h:2851
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81d2da83)
Location: include/linux/skbuff.h:2851
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a089)
Location: include/linux/skbuff.h:2851
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee659)
Location: include/linux/skbuff.h:2851
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff81dfa4ca)
Location: include/linux/skbuff.h:2851
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81da9918)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81dc24e0)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff81df80f5)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro.c (ffffffff81e09913)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81ef5983)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/xfrm/xfrm_device.c (ffffffff81f46ed9)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc2279)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff81fcebeb)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81e18418)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81e3c233)
Location: include/linux/skbuff.h:2797
Inline: True
```
```
In net/core/filter.c (ffffffff81e6a705)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro.c (ffffffff81e7c0ea)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/gso.c (ffffffff81e7d760)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/core/gso.c:__skb_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffff81f55336)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa68d6)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_offload.c (ffffffff820231f9)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff8204a5b4)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81ed58b8)
Location: include/linux/skbuff.h:2804
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81efa74f)
Location: include/linux/skbuff.h:2804
Inline: True
```
```
In net/core/filter.c (ffffffff81f29695)
Location: include/linux/skbuff.h:2804
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro.c (ffffffff81f3c43a)
Location: include/linux/skbuff.h:2804
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/gso.c (ffffffff81f3e6dd)
Location: include/linux/skbuff.h:2804
Inline: True
Inline callers:
  - net/core/gso.c:__skb_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffff8201b5a6)
Location: include/linux/skbuff.h:2804
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/xfrm/xfrm_device.c (ffffffff82073bc6)
Location: include/linux/skbuff.h:2804
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_offload.c (ffffffff820f2244)
Location: include/linux/skbuff.h:2804
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff8211ca20)
Location: include/linux/skbuff.h:2804
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffff800010bb908c)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffff800010bd4938)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffff800010c013a8)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/af_inet.c (ffff800010cab938)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/xfrm/xfrm_device.c (ffff800010cedd54)
Location: include/linux/skbuff.h:2394
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffff800010d54d70)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffff800010d60560)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (c0cd5b48)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (c0ceef04)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (c0d184b8)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/af_inet.c (c0db8834)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/xfrm/xfrm_device.c (c0df5f94)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_offload.c (c0e55380)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (c0e60020)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (c000000000c91564)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (c000000000cb3a50)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (c000000000ce8dd4)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/af_inet.c (c000000000dc231c)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/xfrm/xfrm_device.c (c000000000e1294c)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_offload.c (c000000000e8d9a8)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (c000000000e9b554)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffe000748686)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffe00075e708)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffe00077fe5a)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/af_inet.c (ffffffe0008065a6)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b3a0)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c664)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffe000895968)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff818be8c4)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818d6297)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff818fbe0b)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/af_inet.c (ffffffff81995a9f)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce691)
Location: include/linux/skbuff.h:2394
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81a2787f)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff81a31e7b)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81878804)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818900d7)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff818b5c3b)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/af_inet.c (ffffffff8194f55f)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b471)
Location: include/linux/skbuff.h:2394
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff819e463f)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff819ef06b)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8190f8c4)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff819272c7)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff8194ce3b)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/af_inet.c (ffffffff81a0033f)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/xfrm/xfrm_device.c (ffffffff81a39111)
Location: include/linux/skbuff.h:2394
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9342f)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff81a9da2b)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff819309f4)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81948930)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/filter.c (ffffffff8196e7fb)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/af_inet.c (ffffffff81a0a38f)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44b41)
Location: include/linux/skbuff.h:2394
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f57f)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/8021q/vlan_core.c (ffffffff81aa9c2b)
Location: include/linux/skbuff.h:2394
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
</ul>

## Differences
