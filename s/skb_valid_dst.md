# Function: <code>skb_valid_dst</code>

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
In net/ipv4/ip_input.c (ffffffff81758763)
Location: include/net/dst_metadata.h:40
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff817c8527)
Location: include/net/dst_metadata.h:40
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
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
In net/ipv4/ip_input.c (ffffffff817c4a83)
Location: include/net/dst_metadata.h:40
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81835d8f)
Location: include/net/dst_metadata.h:40
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
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
In net/ipv4/ip_input.c (ffffffff817f45a3)
Location: include/net/dst_metadata.h:40
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff818678af)
Location: include/net/dst_metadata.h:40
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
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
In net/ipv4/ip_input.c (ffffffff818149e2)
Location: include/net/dst_metadata.h:52
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff8188c03a)
Location: include/net/dst_metadata.h:52
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
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
In net/ipv4/ip_input.c (ffffffff81893b85)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff8190d32a)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
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
In net/ipv4/ip_input.c (ffffffff818e7e33)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81964730)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
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
In net/ipv4/ip_input.c (ffffffff81914dfd)
Location: include/net/dst_metadata.h:54
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81998f7f)
Location: include/net/dst_metadata.h:54
Inline: True
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
In net/ipv4/ip_input.c (ffffffff819772d2)
Location: include/net/dst_metadata.h:54
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a04e58)
Location: include/net/dst_metadata.h:54
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
In net/ipv4/ip_input.c (ffffffff819adc62)
Location: include/net/dst_metadata.h:54
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a3ba28)
Location: include/net/dst_metadata.h:54
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
In net/ipv4/ip_input.c (ffffffff81a97bde)
Location: include/net/dst_metadata.h:54
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81b31038)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In net/ipv4/ip_input.c (ffffffff81aa1b3e)
Location: include/net/dst_metadata.h:54
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81b3fc68)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In net/ipv4/ip_input.c (ffffffff81a8cb0d)
Location: include/net/dst_metadata.h:56
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81b2da98)
Location: include/net/dst_metadata.h:56
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In net/ipv4/ip_input.c (ffffffff81b47c3d)
Location: include/net/dst_metadata.h:56
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81bf3ced)
Location: include/net/dst_metadata.h:56
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/exthdrs.c (ffffffff81c31545)
Location: include/net/dst_metadata.h:56
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv4/ip_input.c (ffffffff81cd4f28)
Location: include/net/dst_metadata.h:56
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81d8ca0a)
Location: include/net/dst_metadata.h:56
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/exthdrs.c (ffffffff81dce946)
Location: include/net/dst_metadata.h:56
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv4/ip_input.c (ffffffff81e952c5)
Location: include/net/dst_metadata.h:92
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42a49)
Location: include/net/dst_metadata.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/ipv6/ip6_input.c (ffffffff81f5ac1a)
Location: include/net/dst_metadata.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/exthdrs.c (ffffffff81f9fb58)
Location: include/net/dst_metadata.h:92
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv4/ip_input.c (ffffffff81ef3a98)
Location: include/net/dst_metadata.h:92
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa224d)
Location: include/net/dst_metadata.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/ipv6/ip6_input.c (ffffffff81fba9ca)
Location: include/net/dst_metadata.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/exthdrs.c (ffffffff82000675)
Location: include/net/dst_metadata.h:92
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv4/ip_input.c (ffffffff81fb7a28)
Location: include/net/dst_metadata.h:92
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f631)
Location: include/net/dst_metadata.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/ipv6/ip6_input.c (ffffffff82087dfa)
Location: include/net/dst_metadata.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/exthdrs.c (ffffffff820cf406)
Location: include/net/dst_metadata.h:92
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv4/ip_input.c (ffff800010c5e3f0)
Location: include/net/dst_metadata.h:54
Inline: True
```
```
In net/ipv6/ip6_input.c (ffff800010cfcd80)
Location: include/net/dst_metadata.h:54
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
In net/ipv4/ip_input.c (c0d6d43c)
Location: include/net/dst_metadata.h:54
Inline: True
```
```
In net/ipv6/ip6_input.c (c0e042e0)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In net/ipv4/ip_input.c (c000000000d60720)
Location: include/net/dst_metadata.h:54
Inline: True
```
```
In net/ipv6/ip6_input.c (c000000000e24c18)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In net/ipv4/ip_input.c (ffffffe0007c6890)
Location: include/net/dst_metadata.h:54
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffe000847514)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
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
In net/ipv4/ip_input.c (ffffffff8194dad2)
Location: include/net/dst_metadata.h:54
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff819db0b8)
Location: include/net/dst_metadata.h:54
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
In net/ipv4/ip_input.c (ffffffff819075c2)
Location: include/net/dst_metadata.h:54
Inline: True
```
```
In net/ipv4/ip_tunnel.c (ffffffff81966c1f)
Location: include/net/dst_metadata.h:54
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
```
```
In net/ipv6/ip6_input.c (ffffffff81997e78)
Location: include/net/dst_metadata.h:54
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
In net/ipv4/ip_input.c (ffffffff819b82a2)
Location: include/net/dst_metadata.h:54
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a45b38)
Location: include/net/dst_metadata.h:54
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
In net/ipv4/ip_input.c (ffffffff819c1b02)
Location: include/net/dst_metadata.h:54
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a51808)
Location: include/net/dst_metadata.h:54
Inline: True
```
</details>
</li>
</ul>

## Differences
