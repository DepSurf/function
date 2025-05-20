# Function: <code>netdev_start_xmit</code>

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
Location: include/linux/netdevice.h:3725
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81738be0)
Location: include/linux/netdevice.h:3725
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/packet/af_packet.c (ffffffff81803842)
Location: include/linux/netdevice.h:3725
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
Location: include/linux/netdevice.h:4005
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff817a4eb5)
Location: include/linux/netdevice.h:4005
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/packet/af_packet.c (ffffffff81874a82)
Location: include/linux/netdevice.h:4005
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
Location: include/linux/netdevice.h:3959
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff817d3925)
Location: include/linux/netdevice.h:3959
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/packet/af_packet.c (ffffffff818a9007)
Location: include/linux/netdevice.h:3959
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
In net/core/dev.c (ffffffff817d0b17)
Location: include/linux/netdevice.h:4011
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff817f2b70)
Location: include/linux/netdevice.h:4011
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/packet/af_packet.c (ffffffff818cf952)
Location: include/linux/netdevice.h:4011
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
In net/core/dev.c (ffffffff8184a48e)
Location: include/linux/netdevice.h:4045
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff8186e134)
Location: include/linux/netdevice.h:4045
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/packet/af_packet.c (ffffffff819548c5)
Location: include/linux/netdevice.h:4045
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
In net/core/dev.c (ffffffff818947aa)
Location: include/linux/netdevice.h:4151
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff818bf1c5)
Location: include/linux/netdevice.h:4151
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
In net/core/dev.c (ffffffff818b51ba)
Location: include/linux/netdevice.h:4388
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff818e7fee)
Location: include/linux/netdevice.h:4388
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
In net/core/dev.c (ffffffff81901bab)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff8193795f)
Location: include/linux/netdevice.h:4414
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
In net/core/dev.c (ffffffff81933deb)
Location: include/linux/netdevice.h:4427
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff8196a81f)
Location: include/linux/netdevice.h:4427
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
In net/core/dev.c (ffffffff81a08807)
Location: include/linux/netdevice.h:4619
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81a3df1f)
Location: include/linux/netdevice.h:4619
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
In net/core/dev.c (ffffffff81a09dc7)
Location: include/linux/netdevice.h:4825
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/core/netpoll.c (ffffffff81a40c41)
Location: include/linux/netdevice.h:4825
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
In net/core/dev.c (ffffffff819f0757)
Location: include/linux/netdevice.h:4956
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/core/netpoll.c (ffffffff81a258ff)
Location: include/linux/netdevice.h:4956
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
In net/core/dev.c (ffffffff81aa1f47)
Location: include/linux/netdevice.h:5004
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/core/netpoll.c (ffffffff81ada63f)
Location: include/linux/netdevice.h:5004
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
In net/core/dev.c (ffffffff81c1a323)
Location: include/linux/netdevice.h:4827
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81c5bdb5)
Location: include/linux/netdevice.h:4827
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
In net/core/dev.c (ffffffff81dcb3c3)
Location: include/linux/netdevice.h:4871
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81e12219)
Location: include/linux/netdevice.h:4871
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
In net/core/dev.c (ffffffff81e3bf53)
Location: include/linux/netdevice.h:4918
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81e85a59)
Location: include/linux/netdevice.h:4918
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
In net/core/dev.c (ffffffff81efa48b)
Location: include/linux/netdevice.h:4994
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81f47989)
Location: include/linux/netdevice.h:4994
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
In net/core/dev.c (ffff800010bd20ac)
Location: include/linux/netdevice.h:4427
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffff800010c10bb4)
Location: include/linux/netdevice.h:4427
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
In net/core/dev.c (c0cecc8c)
Location: include/linux/netdevice.h:4427
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (c0d28aec)
Location: include/linux/netdevice.h:4427
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
In net/core/dev.c (c000000000cb0648)
Location: include/linux/netdevice.h:4427
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (c000000000cfd7e8)
Location: include/linux/netdevice.h:4427
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
Location: include/linux/netdevice.h:4427
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffe00078d2e6)
Location: include/linux/netdevice.h:4427
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
In net/core/dev.c (ffffffff818d3deb)
Location: include/linux/netdevice.h:4427
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff8190a7ef)
Location: include/linux/netdevice.h:4427
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
In net/core/dev.c (ffffffff8188dc7b)
Location: include/linux/netdevice.h:4427
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff818c483f)
Location: include/linux/netdevice.h:4427
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
In net/core/dev.c (ffffffff81924deb)
Location: include/linux/netdevice.h:4427
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff8195b81f)
Location: include/linux/netdevice.h:4427
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
In net/core/dev.c (ffffffff8194629b)
Location: include/linux/netdevice.h:4427
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff8197da3f)
Location: include/linux/netdevice.h:4427
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
</details>
</li>
</ul>

## Differences
