# Function: <code>ip_select_ident</code>

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
In net/ipv4/ip_output.c (ffffffff8175f2bc)
Location: include/net/ip.h:358
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff81785753)
Location: include/net/ip.h:358
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/igmp.c (ffffffff817962a7)
Location: include/net/ip.h:358
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ipmr.c (ffffffff817a9786)
Location: include/net/ip.h:358
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
In net/ipv4/ip_output.c (ffffffff817cb518)
Location: include/net/ip.h:354
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff817f2d2b)
Location: include/net/ip.h:354
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/igmp.c (ffffffff818048a5)
Location: include/net/ip.h:354
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81816fc6)
Location: include/net/ip.h:354
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
In net/ipv4/ip_output.c (ffffffff817fb178)
Location: include/net/ip.h:383
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff81823aec)
Location: include/net/ip.h:383
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/igmp.c (ffffffff8183587a)
Location: include/net/ip.h:383
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff818487e2)
Location: include/net/ip.h:383
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
In net/ipv4/ip_output.c (ffffffff8181b510)
Location: include/net/ip.h:395
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff81844696)
Location: include/net/ip.h:395
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/igmp.c (ffffffff81856daf)
Location: include/net/ip.h:395
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81869e76)
Location: include/net/ip.h:395
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
In net/ipv4/ip_output.c (ffffffff8189a446)
Location: include/net/ip.h:406
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff818c3fc4)
Location: include/net/ip.h:406
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/igmp.c (ffffffff818d6c5f)
Location: include/net/ip.h:406
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff818ea531)
Location: include/net/ip.h:406
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
In net/ipv4/ip_output.c (ffffffff818ee92a)
Location: include/net/ip.h:428
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff81919ca2)
Location: include/net/ip.h:428
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/igmp.c (ffffffff8192d5a1)
Location: include/net/ip.h:428
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81940c0e)
Location: include/net/ip.h:428
Inline: True
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
In net/ipv4/ip_output.c (ffffffff8191c0c2)
Location: include/net/ip.h:480
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff8194851b)
Location: include/net/ip.h:480
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/igmp.c (ffffffff8195ca41)
Location: include/net/ip.h:480
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81970b9c)
Location: include/net/ip.h:480
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/ipv4/ip_output.c (ffffffff8197e3e4)
Location: include/net/ip.h:518
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff819ac5c3)
Location: include/net/ip.h:518
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819c1743)
Location: include/net/ip.h:518
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff819da3d3)
Location: include/net/ip.h:518
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6551)
Location: include/net/ip.h:518
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
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
In net/ipv4/ip_output.c (ffffffff819b4d94)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff819e3076)
Location: include/net/ip.h:519
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819f82e3)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81a1126c)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d1d1)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
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
In net/ipv4/ip_output.c (ffffffff81a9ef87)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff81ad095a)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/igmp.c (ffffffff81ae5360)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81b015c3)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1f3e5)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
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
In net/ipv4/ip_output.c (ffffffff81aa8ec7)
Location: include/net/ip.h:522
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff81adc978)
Location: include/net/ip.h:522
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/igmp.c (ffffffff81af222c)
Location: include/net/ip.h:522
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81b0f6a3)
Location: include/net/ip.h:522
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2dcb5)
Location: include/net/ip.h:522
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
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
In net/ipv4/ip_output.c (ffffffff81a93fb8)
Location: include/net/ip.h:526
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff81ac79bb)
Location: include/net/ip.h:526
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/igmp.c (ffffffff81adda21)
Location: include/net/ip.h:526
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81afea1d)
Location: include/net/ip.h:526
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1b5dc)
Location: include/net/ip.h:526
Inline: True
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
In net/ipv4/ip_output.c (ffffffff81b4f3ec)
Location: include/net/ip.h:539
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff81b86218)
Location: include/net/ip.h:539
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/igmp.c (ffffffff81b9cebc)
Location: include/net/ip.h:539
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81bc0262)
Location: include/net/ip.h:539
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81bdfe4c)
Location: include/net/ip.h:539
Inline: True
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
In net/ipv4/ip_output.c (ffffffff81cdcd6b)
Location: include/net/ip.h:544
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff81d16b73)
Location: include/net/ip.h:544
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/igmp.c (ffffffff81d2ef91)
Location: include/net/ip.h:544
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81d52ffe)
Location: include/net/ip.h:544
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81d76e8c)
Location: include/net/ip.h:544
Inline: True
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
In net/ipv4/ip_output.c (ffffffff81e9d7db)
Location: include/net/ip.h:544
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff81edd330)
Location: include/net/ip.h:544
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/igmp.c (ffffffff81ef6ff1)
Location: include/net/ip.h:544
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81f1d99e)
Location: include/net/ip.h:544
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81f436ec)
Location: include/net/ip.h:544
Inline: True
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
In net/ipv4/ip_output.c (ffffffff81efbf30)
Location: include/net/ip.h:564
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff81f3c57e)
Location: include/net/ip.h:564
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/igmp.c (ffffffff81f56a6e)
Location: include/net/ip.h:564
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81f7d48e)
Location: include/net/ip.h:564
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa2ecc)
Location: include/net/ip.h:564
Inline: True
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
In net/ipv4/ip_output.c (ffffffff81fbfe70)
Location: include/net/ip.h:574
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff820026ad)
Location: include/net/ip.h:574
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/igmp.c (ffffffff8201cf0f)
Location: include/net/ip.h:574
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff82043b8e)
Location: include/net/ip.h:574
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff820701cc)
Location: include/net/ip.h:574
Inline: True
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
In net/ipv4/ip_output.c (ffff800010c654fc)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffff800010c97e5c)
Location: include/net/ip.h:519
Inline: True
```
```
In net/ipv4/igmp.c (ffff800010cafee4)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffff800010ccceec)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_output.c (ffff800010cebdf8)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
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
In net/ipv4/ip_output.c (c0d75164)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (c0da5cb8)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/igmp.c (c0dbb8a4)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (c0dd7710)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_output.c (c0df3d50)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
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
In net/ipv4/ip_output.c (c000000000d69ae4)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (c000000000da8e80)
Location: include/net/ip.h:519
Inline: True
```
```
In net/ipv4/igmp.c (c000000000dc5e18)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (c000000000de8c3c)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_output.c (c000000000e0fe60)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
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
In net/ipv4/ip_output.c (ffffffe0007ccd28)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffe0007f6216)
Location: include/net/ip.h:519
Inline: True
```
```
In net/ipv4/igmp.c (ffffffe000808fe2)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffe00081ef4c)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffe0008396a0)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
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
In net/ipv4/ip_output.c (ffffffff81954c04)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff81982ee6)
Location: include/net/ip.h:519
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81998083)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff819b0bfc)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc861)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
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
In net/ipv4/ip_output.c (ffffffff8190e6f4)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff8193c9a6)
Location: include/net/ip.h:519
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81951b43)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff8196d22c)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81989651)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
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
In net/ipv4/ip_output.c (ffffffff819bf3d4)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff819ed6b6)
Location: include/net/ip.h:519
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81a02923)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81a1b49c)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81a372e1)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
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
In net/ipv4/ip_output.c (ffffffff819c8d54)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/raw.c (ffffffff819f75a9)
Location: include/net/ip.h:519
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81a0ce53)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81a2637c)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42c71)
Location: include/net/ip.h:519
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
</details>
</li>
</ul>

## Differences
