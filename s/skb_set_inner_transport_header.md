# Function: <code>skb_set_inner_transport_header</code>

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
In net/core/dev.c (ffffffff8171c729)
Location: include/linux/skbuff.h:1951
Inline: True
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
In net/core/dev.c (ffffffff817850db)
Location: include/linux/skbuff.h:2081
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/dev.c (ffffffff817b26eb)
Location: include/linux/skbuff.h:2098
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/dev.c (ffffffff817cff4a)
Location: include/linux/skbuff.h:2137
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/dev.c (ffffffff8184989a)
Location: include/linux/skbuff.h:2224
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e55b)
Location: include/linux/skbuff.h:2224
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (ffffffff818938ba)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7798)
Location: include/linux/skbuff.h:2235
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (ffffffff818b42d6)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de305)
Location: include/linux/skbuff.h:2313
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (ffffffff81900bd4)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6245)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4ce6c)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (ffffffff81932f04)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2cec5)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83a3c)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (ffffffff81a07d81)
Location: include/linux/skbuff.h:2438
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1edcd)
Location: include/linux/skbuff.h:2438
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e802)
Location: include/linux/skbuff.h:2438
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (ffffffff81a09465)
Location: include/linux/skbuff.h:2459
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2d67d)
Location: include/linux/skbuff.h:2459
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d82c)
Location: include/linux/skbuff.h:2459
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (ffffffff819efdd1)
Location: include/linux/skbuff.h:2475
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c101)
Location: include/linux/skbuff.h:2475
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c6dc)
Location: include/linux/skbuff.h:2475
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (ffffffff81aa120a)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0a8d)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c476b0)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (ffffffff81c190b2)
Location: include/linux/skbuff.h:2872
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81d777af)
Location: include/linux/skbuff.h:2872
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6a77)
Location: include/linux/skbuff.h:2872
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (ffffffff81dca088)
Location: include/linux/skbuff.h:2764
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81f4403f)
Location: include/linux/skbuff.h:2764
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb989f)
Location: include/linux/skbuff.h:2764
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (ffffffff81e3abff)
Location: include/linux/skbuff.h:2818
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3901)
Location: include/linux/skbuff.h:2818
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019f2f)
Location: include/linux/skbuff.h:2818
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (ffffffff81ef8fa3)
Location: include/linux/skbuff.h:2825
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff82070c31)
Location: include/linux/skbuff.h:2825
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8eff)
Location: include/linux/skbuff.h:2825
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (ffff800010bd0ebc)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_output.c (ffff800010cebb20)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f738)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (c0cebb58)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_output.c (c0df3878)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (c0e50508)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (c000000000caf0dc)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_output.c (c000000000e0f574)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86e34)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (ffffffe00075b558)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_output.c (ffffffe000839416)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000888012)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (ffffffff818d2f04)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc555)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a230cc)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (ffffffff8188cd94)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81989345)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dfe8c)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (ffffffff81923f04)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81a36fd5)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8db4c)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/dev.c (ffffffff81945374)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42965)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a84c)
Location: include/linux/skbuff.h:2415
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
</details>
</li>
</ul>

## Differences
