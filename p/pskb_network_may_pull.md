# Function: <code>pskb_network_may_pull</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff817c85af)
Location: include/linux/skbuff.h:2108
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81835a31)
Location: include/linux/skbuff.h:2243
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81867561)
Location: include/linux/skbuff.h:2260
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff8188bcf4)
Location: include/linux/skbuff.h:2309
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff8190cfd5)
Location: include/linux/skbuff.h:2396
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff819643d3)
Location: include/linux/skbuff.h:2408
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
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
In net/ipv6/ip6_input.c (ffffffff81999d9e)
Location: include/linux/skbuff.h:2486
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff819d45a2)
Location: include/linux/skbuff.h:2486
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
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
In net/ipv4/route.c (ffffffff81971c18)
Location: include/linux/skbuff.h:2572
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv6/ip6_input.c (ffffffff81a05cf4)
Location: include/linux/skbuff.h:2572
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81a43418)
Location: include/linux/skbuff.h:2572
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
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
In net/ipv4/route.c (ffffffff819a86e8)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c85c)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81a79f88)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
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
In net/ipv4/route.c (ffffffff81a91d98)
Location: include/linux/skbuff.h:2609
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv6/ip6_input.c (ffffffff81b31efe)
Location: include/linux/skbuff.h:2609
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81b75d78)
Location: include/linux/skbuff.h:2609
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
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
In net/ipv4/route.c (ffffffff81a9bc2a)
Location: include/linux/skbuff.h:2635
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv6/ip6_input.c (ffffffff81b40afe)
Location: include/linux/skbuff.h:2635
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81b84ae8)
Location: include/linux/skbuff.h:2635
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
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
In net/ipv4/route.c (ffffffff81a86c9a)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e396)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81b73776)
Location: include/linux/skbuff.h:2651
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
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
In net/ipv4/route.c (ffffffff81b4145a)
Location: include/linux/skbuff.h:2680
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv6/ip6_input.c (ffffffff81bf468c)
Location: include/linux/skbuff.h:2680
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81c3dd46)
Location: include/linux/skbuff.h:2680
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
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
In net/ipv4/route.c (ffffffff81ccde74)
Location: include/linux/skbuff.h:3049
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d42a)
Location: include/linux/skbuff.h:3049
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81ddad0e)
Location: include/linux/skbuff.h:3049
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
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
In net/ipv4/route.c (ffffffff81e8de14)
Location: include/linux/skbuff.h:2943
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b511)
Location: include/linux/skbuff.h:2943
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81faca1e)
Location: include/linux/skbuff.h:2943
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
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
In net/ipv4/route.c (ffffffff81eec554)
Location: include/linux/skbuff.h:2997
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb2df)
Location: include/linux/skbuff.h:2997
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff8200d42e)
Location: include/linux/skbuff.h:2997
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
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
In net/ipv4/route.c (ffffffff81fb05a4)
Location: include/linux/skbuff.h:3004
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv6/ip6_input.c (ffffffff820886ef)
Location: include/linux/skbuff.h:3004
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff820dc3fb)
Location: include/linux/skbuff.h:3004
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
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
In net/ipv4/route.c (ffff800010c57ffc)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv6/ip6_input.c (ffff800010cfdf98)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (ffff800010d45bc4)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
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
In net/ipv4/route.c (c0d67c00)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv6/ip6_input.c (c0e0551c)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (c0e465ac)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
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
In net/ipv4/route.c (c000000000d59918)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv6/ip6_input.c (c000000000e25d68)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (c000000000e78e60)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
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
In net/ipv4/route.c (ffffffe0007c227e)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv6/ip6_input.c (ffffffe00084802c)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (ffffffe00087ed10)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
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
In net/ipv4/route.c (ffffffff81948558)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv6/ip6_input.c (ffffffff819dbeec)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81a19618)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
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
In net/ipv4/route.c (ffffffff81902048)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv6/ip6_input.c (ffffffff81998cac)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff819d63d8)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
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
In net/ipv4/route.c (ffffffff819b2d28)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv6/ip6_input.c (ffffffff81a4696c)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81a84098)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
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
In net/ipv4/route.c (ffffffff819bc3ea)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv6/ip6_input.c (ffffffff81a5269c)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/ip6mr.c (ffffffff81a909c8)
Location: include/linux/skbuff.h:2586
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
</details>
</li>
</ul>

## Differences
