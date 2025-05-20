# Function: <code>skb_copy_to_linear_data</code>

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
In net/core/netpoll.c (ffffffff81739373)
Location: include/linux/skbuff.h:2916
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff817a7363)
Location: include/linux/skbuff.h:2916
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff817f8539)
Location: include/linux/skbuff.h:2916
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (ffffffff817a562b)
Location: include/linux/skbuff.h:3123
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff81815053)
Location: include/linux/skbuff.h:3123
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff81867d2a)
Location: include/linux/skbuff.h:3123
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (ffffffff817d409b)
Location: include/linux/skbuff.h:3175
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff81846813)
Location: include/linux/skbuff.h:3175
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff8189ab8a)
Location: include/linux/skbuff.h:3175
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (ffffffff817f33de)
Location: include/linux/skbuff.h:3249
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff8186953f)
Location: include/linux/skbuff.h:3249
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff818c14c1)
Location: include/linux/skbuff.h:3249
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (ffffffff8186e7ce)
Location: include/linux/skbuff.h:3370
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff818e9b8f)
Location: include/linux/skbuff.h:3370
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff81944811)
Location: include/linux/skbuff.h:3370
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (ffffffff818bf992)
Location: include/linux/skbuff.h:3380
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff81940244)
Location: include/linux/skbuff.h:3380
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff8199d51f)
Location: include/linux/skbuff.h:3380
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (ffffffff818e87b2)
Location: include/linux/skbuff.h:3459
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff819700c4)
Location: include/linux/skbuff.h:3459
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff819d407f)
Location: include/linux/skbuff.h:3459
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (ffffffff81937fc4)
Location: include/linux/skbuff.h:3550
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff819d997f)
Location: include/linux/skbuff.h:3550
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff81a42f2f)
Location: include/linux/skbuff.h:3550
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (ffffffff8196ae84)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff81a107df)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff81a79a8f)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (ffffffff81a3ebea)
Location: include/linux/skbuff.h:3640
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff81b02213)
Location: include/linux/skbuff.h:3640
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff81b7472f)
Location: include/linux/skbuff.h:3640
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (ffffffff81a4198a)
Location: include/linux/skbuff.h:3669
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff81b105b3)
Location: include/linux/skbuff.h:3669
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff81b8349f)
Location: include/linux/skbuff.h:3669
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (ffffffff81a2644a)
Location: include/linux/skbuff.h:3733
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff81afe1c3)
Location: include/linux/skbuff.h:3733
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff81b7210f)
Location: include/linux/skbuff.h:3733
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (ffffffff81adb1c1)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff81bbf453)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c5bf)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (ffffffff81c5c6d1)
Location: include/linux/skbuff.h:4143
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff81d541e3)
Location: include/linux/skbuff.h:4143
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff81dda994)
Location: include/linux/skbuff.h:4143
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/netpoll.c (ffffffff81e12dc1)
Location: include/linux/skbuff.h:4039
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff81f1e3c3)
Location: include/linux/skbuff.h:4039
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff81faba00)
Location: include/linux/skbuff.h:4039
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
**Symbols:**

```
ffffffff81faba00-ffffffff81faba3a: skb_copy_to_linear_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/netpoll.c (ffffffff81e866ea)
Location: include/linux/skbuff.h:4071
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff81f7deb3)
Location: include/linux/skbuff.h:4071
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff8200c1a0)
Location: include/linux/skbuff.h:4071
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
**Symbols:**

```
ffffffff8200c1a0-ffffffff8200c1da: skb_copy_to_linear_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/netpoll.c (ffffffff81f486f7)
Location: include/linux/skbuff.h:4108
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff82044707)
Location: include/linux/skbuff.h:4108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff820db170)
Location: include/linux/skbuff.h:4108
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
**Symbols:**

```
ffffffff820db170-ffffffff820db1aa: skb_copy_to_linear_data.constprop.0 (STB_LOCAL)
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
In net/core/netpoll.c (ffff800010c114dc)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffff800010ccb458)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffff800010d43dac)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (c0d293ac)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (c0dd5948)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (c0e45b18)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (c000000000cfe1cc)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (c000000000de80d8)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (c000000000e788d8)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (ffffffe00078d6aa)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffe00081e786)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffe00087e932)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (ffffffff8190ae54)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff819b01ef)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff81a1911f)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (ffffffff818c4bef)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff8196c81f)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff819d5edf)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (ffffffff8195be84)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff81999960)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
```
```
In net/ipv4/ipmr.c (ffffffff81a1aa8f)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff81a83b9f)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
In net/core/netpoll.c (ffffffff8197e264)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ipmr.c (ffffffff81a258ef)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff81a904bf)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
</details>
</li>
</ul>

## Differences
