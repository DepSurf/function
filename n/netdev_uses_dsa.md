# Function: <code>netdev_uses_dsa</code>

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
In net/ethernet/eth.c (0)
Location: include/linux/netdevice.h:1949
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
In net/ethernet/eth.c (ffffffff817acfa8)
Location: include/linux/netdevice.h:2026
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/ethernet/eth.c (ffffffff817dc5f8)
Location: include/linux/netdevice.h:2008
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/ethernet/eth.c (ffffffff817fbcbc)
Location: include/net/dsa.h:460
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffffffff8183e901)
Location: include/net/dsa.h:483
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ethernet/eth.c (ffffffff8187967c)
Location: include/net/dsa.h:483
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffffffff818892ad)
Location: include/net/dsa.h:543
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ethernet/eth.c (ffffffff818cb059)
Location: include/net/dsa.h:543
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffffffff818aa932)
Location: include/net/dsa.h:548
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ethernet/eth.c (ffffffff818f61fa)
Location: include/net/dsa.h:548
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffffffff818f5a53)
Location: include/net/dsa.h:555
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ethernet/eth.c (ffffffff8195583b)
Location: include/net/dsa.h:555
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffffffff81927953)
Location: include/net/dsa.h:556
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ethernet/eth.c (ffffffff8198bcdb)
Location: include/net/dsa.h:556
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffffffff819fbbef)
Location: include/net/dsa.h:663
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ethernet/eth.c (ffffffff81a63984)
Location: include/net/dsa.h:663
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffffffff819fb301)
Location: include/net/dsa.h:735
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a0aa31)
Location: include/net/dsa.h:735
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/core/netpoll.c (ffffffff81a410e0)
Location: include/net/dsa.h:735
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ethernet/eth.c (ffffffff81a6bae4)
Location: include/net/dsa.h:735
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffffffff819e1559)
Location: include/net/dsa.h:893
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff819f13c5)
Location: include/net/dsa.h:893
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81a54274)
Location: include/net/dsa.h:893
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffffffff81a91999)
Location: include/net/dsa.h:985
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81aa2ced)
Location: include/net/dsa.h:985
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81b0cf86)
Location: include/net/dsa.h:985
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffffffff81c07bd6)
Location: include/net/dsa.h:1267
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81c1afae)
Location: include/net/dsa.h:1267
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81c938bc)
Location: include/net/dsa.h:1267
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffffffff81db768c)
Location: include/net/dsa.h:1297
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81dcbe38)
Location: include/net/dsa.h:1297
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81e4efec)
Location: include/net/dsa.h:1297
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffffffff81e27fc8)
Location: include/net/dsa.h:1315
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81e3cbe0)
Location: include/net/dsa.h:1315
Inline: True
```
```
In net/core/dev_ioctl.c (ffffffff81e758bd)
Location: include/net/dsa.h:1315
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_set_hwtstamp
```
```
In net/ethernet/eth.c (ffffffff81eaa68c)
Location: include/net/dsa.h:1315
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffffffff81ee604b)
Location: include/net/dsa.h:1323
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81efb47e)
Location: include/net/dsa.h:1323
Inline: True
```
```
In net/core/dev_ioctl.c (ffffffff81f356f7)
Location: include/net/dsa.h:1323
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_set_hwtstamp
```
```
In net/ethernet/eth.c (ffffffff81f6d13c)
Location: include/net/dsa.h:1323
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffff800010bc3da8)
Location: include/net/dsa.h:556
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ethernet/eth.c (ffff800010c36d5c)
Location: include/net/dsa.h:556
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (c0cdf22c)
Location: include/net/dsa.h:556
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ethernet/eth.c (c0d496b4)
Location: include/net/dsa.h:556
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (c000000000c9e400)
Location: include/net/dsa.h:556
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ethernet/eth.c (c000000000d2ed5c)
Location: include/net/dsa.h:556
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffffffe000750802)
Location: include/net/dsa.h:556
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ethernet/eth.c (ffffffe0007a8706)
Location: include/net/dsa.h:556
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffffffff818c7953)
Location: include/net/dsa.h:556
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ethernet/eth.c (ffffffff8192bb4b)
Location: include/net/dsa.h:556
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffffffff81881893)
Location: include/net/dsa.h:556
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ethernet/eth.c (ffffffff818e58fb)
Location: include/net/dsa.h:556
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffffffff81918953)
Location: include/net/dsa.h:556
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ethernet/eth.c (ffffffff8197ccdb)
Location: include/net/dsa.h:556
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/flow_dissector.c (ffffffff81939598)
Location: include/net/dsa.h:556
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ethernet/eth.c (ffffffff8199f24b)
Location: include/net/dsa.h:556
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
</details>
</li>
</ul>

## Differences
