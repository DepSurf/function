# Function: <code>eth_proto_is_802_3</code>

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
In net/core/skbuff.c (0)
Location: include/linux/etherdevice.h:204
Inline: True
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:204
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/etherdevice.h:204
Inline: True
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
In net/core/skbuff.c (0)
Location: include/linux/etherdevice.h:204
Inline: True
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:204
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/etherdevice.h:204
Inline: True
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
In net/core/skbuff.c (0)
Location: include/linux/etherdevice.h:204
Inline: True
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:204
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/etherdevice.h:204
Inline: True
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
In net/core/skbuff.c (0)
Location: include/linux/etherdevice.h:209
Inline: True
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:209
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/etherdevice.h:209
Inline: True
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
In net/core/skbuff.c (0)
Location: include/linux/etherdevice.h:210
Inline: True
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:210
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/etherdevice.h:210
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/etherdevice.h:210
Inline: True
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
In net/core/skbuff.c (ffffffff81880ec3)
Location: include/linux/etherdevice.h:210
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (ffffffff818cb083)
Location: include/linux/etherdevice.h:210
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193c04a)
Location: include/linux/etherdevice.h:210
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff819a8b54)
Location: include/linux/etherdevice.h:210
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (ffffffff818a1d5a)
Location: include/linux/etherdevice.h:210
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (ffffffff818f6224)
Location: include/linux/etherdevice.h:210
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196bd59)
Location: include/linux/etherdevice.h:210
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff819df67e)
Location: include/linux/etherdevice.h:210
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (ffffffff818ec73d)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (ffffffff8195586c)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2aa9)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e216)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (ffffffff8191e86d)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (ffffffff8198bd0c)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a09619)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81a84e76)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (ffffffff819f10ed)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (ffffffff81a639b5)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8f39)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81b7fef6)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (ffffffff819f107d)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (ffffffff81a6bb15)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06f29)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f376)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (ffffffff819d633a)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (ffffffff81a542a5)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af2681)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81b7e0e6)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (ffffffff81a8697a)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (ffffffff81b0cfb7)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2b91)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81c49706)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (ffffffff81bfc0aa)
Location: include/linux/etherdevice.h:213
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (ffffffff81c938fc)
Location: include/linux/etherdevice.h:213
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d46360)
Location: include/linux/etherdevice.h:213
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81de8eee)
Location: include/linux/etherdevice.h:213
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (ffffffff81daaf6a)
Location: include/linux/etherdevice.h:213
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (ffffffff81e4f02c)
Location: include/linux/etherdevice.h:213
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f753)
Location: include/linux/etherdevice.h:213
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81fbc61e)
Location: include/linux/etherdevice.h:213
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (ffffffff81e1bcdd)
Location: include/linux/etherdevice.h:213
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (ffffffff81eaa6cc)
Location: include/linux/etherdevice.h:213
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f443)
Location: include/linux/etherdevice.h:213
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff8201cf0e)
Location: include/linux/etherdevice.h:213
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (ffffffff81ed929d)
Location: include/linux/etherdevice.h:213
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (ffffffff81f6d17c)
Location: include/linux/etherdevice.h:213
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035b73)
Location: include/linux/etherdevice.h:213
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff820ebeee)
Location: include/linux/etherdevice.h:213
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (ffff800010bb903c)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (ffff800010c36d8c)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc29c0)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffff800010d50f28)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (c0cd5ae8)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (c0d496ec)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (c0dce1e4)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (c0e51a8c)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (c000000000c91508)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (c000000000d2edb4)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dde244)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (c000000000e88e24)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (ffffffe00074864a)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (ffffffe0007a872a)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817e1a)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffe0008891ea)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (ffffffff818be86d)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (ffffffff8192bb7c)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a93b9)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81a24506)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (ffffffff818787ad)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (ffffffff818e592c)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962e79)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff819e12c6)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (ffffffff8190f86d)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (ffffffff8197cd0c)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13c59)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ef86)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/skbuff.c (ffffffff8193099d)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ethernet/eth.c (ffffffff8199f27c)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e639)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bd06)
Location: include/linux/etherdevice.h:206
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
</details>
</li>
</ul>

## Differences
