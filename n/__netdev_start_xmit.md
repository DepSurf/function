# Function: <code>__netdev_start_xmit</code>

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
In net/core/dev.c (ffffffff8171ca4b)
Location: include/linux/netdevice.h:3717
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81738be7)
Location: include/linux/netdevice.h:3717
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/packet/af_packet.c (ffffffff81803849)
Location: include/linux/netdevice.h:3717
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/dev.c (ffffffff8178520a)
Location: include/linux/netdevice.h:3997
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff817a4ebc)
Location: include/linux/netdevice.h:3997
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/packet/af_packet.c (ffffffff81874a89)
Location: include/linux/netdevice.h:3997
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/dev.c (ffffffff817b288a)
Location: include/linux/netdevice.h:3951
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff817d392c)
Location: include/linux/netdevice.h:3951
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/packet/af_packet.c (ffffffff818a900e)
Location: include/linux/netdevice.h:3951
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/dev.c (ffffffff817d0b1f)
Location: include/linux/netdevice.h:4003
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff817f2b78)
Location: include/linux/netdevice.h:4003
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/packet/af_packet.c (ffffffff818cf959)
Location: include/linux/netdevice.h:4003
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/dev.c (ffffffff8184a495)
Location: include/linux/netdevice.h:4037
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff8186e13c)
Location: include/linux/netdevice.h:4037
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/packet/af_packet.c (ffffffff819548cc)
Location: include/linux/netdevice.h:4037
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/dev.c (ffffffff818947b1)
Location: include/linux/netdevice.h:4143
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff818bf1cc)
Location: include/linux/netdevice.h:4143
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff818b51c1)
Location: include/linux/netdevice.h:4380
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff818e7ff6)
Location: include/linux/netdevice.h:4380
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81901bb2)
Location: include/linux/netdevice.h:4401
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81937966)
Location: include/linux/netdevice.h:4401
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81933df2)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff8196a826)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81a0880e)
Location: include/linux/netdevice.h:4606
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81a3df26)
Location: include/linux/netdevice.h:4606
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81a09dce)
Location: include/linux/netdevice.h:4812
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/core/netpoll.c (ffffffff81a40c48)
Location: include/linux/netdevice.h:4812
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff819f075e)
Location: include/linux/netdevice.h:4943
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/core/netpoll.c (ffffffff81a25906)
Location: include/linux/netdevice.h:4943
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81aa1f4e)
Location: include/linux/netdevice.h:4991
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/core/netpoll.c (ffffffff81ada646)
Location: include/linux/netdevice.h:4991
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81c1a32a)
Location: include/linux/netdevice.h:4814
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81c5bdbd)
Location: include/linux/netdevice.h:4814
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81dcb3ca)
Location: include/linux/netdevice.h:4858
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81e12221)
Location: include/linux/netdevice.h:4858
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81e3bf5a)
Location: include/linux/netdevice.h:4905
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81e85a61)
Location: include/linux/netdevice.h:4905
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81efa48f)
Location: include/linux/netdevice.h:4981
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81f4798e)
Location: include/linux/netdevice.h:4981
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffff800010bd20b0)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffff800010c10bbc)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (c0cecc90)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (c0d28af0)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (c000000000cb0658)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (c000000000cfd7e8)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffe00075c630)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffe00078d2e6)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff818d3df2)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff8190a7f6)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff8188dc82)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff818c4846)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff81924df2)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff8195b826)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
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
In net/core/dev.c (ffffffff819462a2)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff8197da46)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
</details>
</li>
</ul>

## Differences
