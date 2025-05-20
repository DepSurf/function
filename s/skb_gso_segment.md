# Function: <code>skb_gso_segment</code>

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
In net/core/dev.c (ffffffff8171c67d)
Location: include/linux/netdevice.h:3682
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8175e0ab)
Location: include/linux/netdevice.h:3682
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc607)
Location: include/linux/netdevice.h:3682
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/dev.c (ffffffff8178502f)
Location: include/linux/netdevice.h:3938
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff817ca2e8)
Location: include/linux/netdevice.h:3938
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81829527)
Location: include/linux/netdevice.h:3938
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/dev.c (ffffffff817b263f)
Location: include/linux/netdevice.h:3905
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff817f9f07)
Location: include/linux/netdevice.h:3905
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/xfrm/xfrm_output.c (ffffffff8185aef7)
Location: include/linux/netdevice.h:3905
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/dev.c (ffffffff817cfe44)
Location: include/linux/netdevice.h:3957
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff8181a2e9)
Location: include/linux/netdevice.h:3957
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/xfrm/xfrm_output.c (ffffffff8187eec1)
Location: include/linux/netdevice.h:3957
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/dev.c (ffffffff81849794)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff81898931)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/xfrm/xfrm_output.c (ffffffff818fffe0)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/dev.c (ffffffff8189378a)
Location: include/linux/netdevice.h:4097
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff818ed693)
Location: include/linux/netdevice.h:4097
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81956b9e)
Location: include/linux/netdevice.h:4097
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81957e49)
Location: include/linux/netdevice.h:4097
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/core/dev.c (ffffffff818b41a9)
Location: include/linux/netdevice.h:4333
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff8191a190)
Location: include/linux/netdevice.h:4333
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b7e1)
Location: include/linux/netdevice.h:4333
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff8198cffc)
Location: include/linux/netdevice.h:4333
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/core/dev.c (ffffffff81900a9d)
Location: include/linux/netdevice.h:4354
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff8197c319)
Location: include/linux/netdevice.h:4354
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6d0e)
Location: include/linux/netdevice.h:4354
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff819f8832)
Location: include/linux/netdevice.h:4354
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/core/dev.c (ffffffff81932dcd)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff819b2ce5)
Location: include/linux/netdevice.h:4367
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d97e)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f492)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/core/dev.c (ffffffff81a07cce)
Location: include/linux/netdevice.h:4559
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a9cb97)
Location: include/linux/netdevice.h:4559
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output_gso
```
```
In net/xfrm/xfrm_output.c (ffffffff81b201b5)
Location: include/linux/netdevice.h:4559
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81b21f17)
Location: include/linux/netdevice.h:4559
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/core/dev.c (ffffffff81a0939e)
Location: include/linux/netdevice.h:4765
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff81aa6a27)
Location: include/linux/netdevice.h:4765
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output_gso
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2eb05)
Location: include/linux/netdevice.h:4765
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30a41)
Location: include/linux/netdevice.h:4765
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ef05)
Location: include/linux/netdevice.h:4765
Inline: True
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
In net/core/dev.c (ffffffff819efd1e)
Location: include/linux/netdevice.h:4896
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a91bc8)
Location: include/linux/netdevice.h:4896
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c8a5)
Location: include/linux/netdevice.h:4896
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e779)
Location: include/linux/netdevice.h:4896
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81b2beb1)
Location: include/linux/netdevice.h:4896
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
In net/core/dev.c (ffffffff81aa1153)
Location: include/linux/netdevice.h:4944
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff81b4cfb8)
Location: include/linux/netdevice.h:4944
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81be1215)
Location: include/linux/netdevice.h:4944
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81be327d)
Location: include/linux/netdevice.h:4944
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81bf201d)
Location: include/linux/netdevice.h:4944
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
In net/core/dev.c (ffffffff81c18ff9)
Location: include/linux/netdevice.h:4761
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff81cda739)
Location: include/linux/netdevice.h:4761
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81d78133)
Location: include/linux/netdevice.h:4761
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a516)
Location: include/linux/netdevice.h:4761
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81d8ab27)
Location: include/linux/netdevice.h:4761
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
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
In net/core/dev.c (ffffffff81dc9fcf)
Location: include/linux/netdevice.h:4805
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff81e9af19)
Location: include/linux/netdevice.h:4805
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81f449d3)
Location: include/linux/netdevice.h:4805
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81f47269)
Location: include/linux/netdevice.h:4805
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81f58adb)
Location: include/linux/netdevice.h:4805
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
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
In net/core/dev.c (ffffffff81e3ab4b)
Location: include/net/gso.h:80
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff81ef9919)
Location: include/net/gso.h:80
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa41b3)
Location: include/net/gso.h:80
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6ca5)
Location: include/net/gso.h:80
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81fb878d)
Location: include/net/gso.h:80
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
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
In net/core/dev.c (ffffffff81ef8eef)
Location: include/net/gso.h:80
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff81fbd839)
Location: include/net/gso.h:80
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff820714e3)
Location: include/net/gso.h:80
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff82073f8a)
Location: include/net/gso.h:80
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff82085d33)
Location: include/net/gso.h:80
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
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
In net/core/dev.c (ffff800010bd0da4)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffff800010c641f0)
Location: include/linux/netdevice.h:4367
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffff800010cec710)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffff800010cee55c)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/core/dev.c (c0ceb9f0)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (c0d73050)
Location: include/linux/netdevice.h:4367
Inline: True
```
```
In net/xfrm/xfrm_output.c (c0df4640)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (c0df647c)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/core/dev.c (c000000000caee54)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (c000000000d67150)
Location: include/linux/netdevice.h:4367
Inline: True
```
```
In net/xfrm/xfrm_output.c (c000000000e10940)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (c000000000e131b8)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/core/dev.c (ffffffe00075b3fe)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffe0007cb166)
Location: include/linux/netdevice.h:4367
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffe000839df4)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b80a)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/core/dev.c (ffffffff818d2dcd)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff81952b55)
Location: include/linux/netdevice.h:4367
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819cd00e)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff819ceb22)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/core/dev.c (ffffffff8188cc5d)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff8190c645)
Location: include/linux/netdevice.h:4367
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81989dfe)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b8e9)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/core/dev.c (ffffffff81923dcd)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199a9c1)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_enqueue_packet
```
```
In net/ipv4/ip_output.c (ffffffff819bd325)
Location: include/linux/netdevice.h:4367
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a37a8e)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81a395a2)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/core/dev.c (ffffffff8194523d)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/ipv4/ip_output.c (ffffffff819c6c35)
Location: include/linux/netdevice.h:4367
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a4344e)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44fd2)
Location: include/linux/netdevice.h:4367
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
</details>
</li>
</ul>

## Differences
