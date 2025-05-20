# Function: <code>skb_reset_inner_transport_header</code>

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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:1946
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2076
Inline: True
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2093
Inline: True
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2132
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2219
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/skbuff.h:2219
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2230
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7798)
Location: include/linux/skbuff.h:2230
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2308
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de305)
Location: include/linux/skbuff.h:2308
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2396
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6026)
Location: include/linux/skbuff.h:2396
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4ce6c)
Location: include/linux/skbuff.h:2396
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2410
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2cca6)
Location: include/linux/skbuff.h:2410
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83a3c)
Location: include/linux/skbuff.h:2410
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2433
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1f1cc)
Location: include/linux/skbuff.h:2433
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e802)
Location: include/linux/skbuff.h:2433
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2454
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2da9c)
Location: include/linux/skbuff.h:2454
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d82c)
Location: include/linux/skbuff.h:2454
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2470
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c101)
Location: include/linux/skbuff.h:2470
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c6dc)
Location: include/linux/skbuff.h:2470
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2499
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0a8d)
Location: include/linux/skbuff.h:2499
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c476b0)
Location: include/linux/skbuff.h:2499
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2867
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81d777af)
Location: include/linux/skbuff.h:2867
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6a77)
Location: include/linux/skbuff.h:2867
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2759
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81f4403f)
Location: include/linux/skbuff.h:2759
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb989f)
Location: include/linux/skbuff.h:2759
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2813
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3901)
Location: include/linux/skbuff.h:2813
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019f2f)
Location: include/linux/skbuff.h:2813
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2820
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff82070c31)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8eff)
Location: include/linux/skbuff.h:2820
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2410
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffff800010ceb910)
Location: include/linux/skbuff.h:2410
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f738)
Location: include/linux/skbuff.h:2410
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2410
Inline: True
```
```
In net/xfrm/xfrm_output.c (c0df3700)
Location: include/linux/skbuff.h:2410
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (c0e50508)
Location: include/linux/skbuff.h:2410
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2410
Inline: True
```
```
In net/xfrm/xfrm_output.c (c000000000e0f574)
Location: include/linux/skbuff.h:2410
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86e34)
Location: include/linux/skbuff.h:2410
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2410
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffe000839268)
Location: include/linux/skbuff.h:2410
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000888026)
Location: include/linux/skbuff.h:2410
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2410
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc336)
Location: include/linux/skbuff.h:2410
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a230cc)
Location: include/linux/skbuff.h:2410
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2410
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81989126)
Location: include/linux/skbuff.h:2410
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dfe8c)
Location: include/linux/skbuff.h:2410
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2410
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a36db6)
Location: include/linux/skbuff.h:2410
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8db4c)
Location: include/linux/skbuff.h:2410
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2410
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42746)
Location: include/linux/skbuff.h:2410
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a84c)
Location: include/linux/skbuff.h:2410
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
</details>
</li>
</ul>

## Differences
