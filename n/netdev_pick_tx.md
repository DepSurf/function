# Function: <code>netdev_pick_tx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct netdev_queue *netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, void *accel_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171cc60)
Location: net/core/dev.c:3022
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
**Symbols:**

```
ffffffff8171cc60-ffffffff8171cd35: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct netdev_queue *netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, void *accel_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817853f0)
Location: net/core/dev.c:3265
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
**Symbols:**

```
ffffffff817853f0-ffffffff817854ca: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct netdev_queue *netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, void *accel_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b2a00)
Location: net/core/dev.c:3269
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
**Symbols:**

```
ffffffff817b2a00-ffffffff817b2ada: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct netdev_queue *netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, void *accel_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d0200)
Location: net/core/dev.c:3349
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
**Symbols:**

```
ffffffff817d0200-ffffffff817d02da: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct netdev_queue *netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, void *accel_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81849b60)
Location: net/core/dev.c:3395
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
**Symbols:**

```
ffffffff81849b60-ffffffff81849c3d: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct netdev_queue *netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, void *accel_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3438
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff81899076-ffffffff81899097: netdev_pick_tx.cold.162 (STB_LOCAL)
ffffffff81893d80-ffffffff81893e33: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct netdev_queue *netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3733
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff818bb518-ffffffff818bb539: netdev_pick_tx.cold.169 (STB_LOCAL)
ffffffff818b4780-ffffffff818b4830: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u16 netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f9d90)
Location: net/core/dev.c:3717
Inline: False
Direct callers:
  - net/core/dev.c:netdev_core_pick_tx
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff818f9d90-ffffffff818f9faa: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u16 netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192bef0)
Location: net/core/dev.c:3617
Inline: False
Direct callers:
  - net/core/dev.c:netdev_core_pick_tx
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff8192bef0-ffffffff8192c10a: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u16 netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ff4c0)
Location: net/core/dev.c:3975
Inline: False
Direct callers:
  - net/core/dev.c:netdev_core_pick_tx
  - net/packet/af_packet.c:packet_pick_tx_queue
```
**Symbols:**

```
ffffffff819ff4c0-ffffffff819ff6f3: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u16 netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ff210)
Location: net/core/dev.c:4006
Inline: False
Direct callers:
  - net/core/dev.c:netdev_core_pick_tx
  - net/packet/af_packet.c:packet_pick_tx_queue
```
**Symbols:**

```
ffffffff819ff210-ffffffff819ff45e: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u16 netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e59e0)
Location: net/core/dev.c:4089
Inline: False
Direct callers:
  - net/core/dev.c:netdev_core_pick_tx
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff819e59e0-ffffffff819e5c55: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u16 netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4054
Inline: False
Direct callers:
  - net/core/dev.c:netdev_core_pick_tx
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff81d35748-ffffffff81d3578d: netdev_pick_tx.cold (STB_LOCAL)
ffffffff81a95e90-ffffffff81a961a2: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u16 netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4086
Inline: False
Direct callers:
  - net/core/dev.c:netdev_core_pick_tx
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff81f01d2b-ffffffff81f01d79: netdev_pick_tx.cold (STB_LOCAL)
ffffffff81c0c8a0-ffffffff81c0cc47: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u16 netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4073
Inline: False
Direct callers:
  - net/core/dev.c:netdev_core_pick_tx
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff820ab0de-ffffffff820ab104: netdev_pick_tx.cold (STB_LOCAL)
ffffffff81dbc700-ffffffff81dbcac4: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u16 netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4033
Inline: False
Direct callers:
  - drivers/net/net_failover.c:net_failover_select_queue
  - net/core/dev.c:netdev_core_pick_tx
  - net/packet/af_packet.c:packet_xmit
```
**Symbols:**

```
ffffffff8212c78e-ffffffff8212c7ad: netdev_pick_tx.cold (STB_LOCAL)
ffffffff81e2cf10-ffffffff81e2d2d8: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u16 netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4183
Inline: False
Direct callers:
  - drivers/net/net_failover.c:net_failover_select_queue
  - net/core/dev.c:netdev_core_pick_tx
  - net/packet/af_packet.c:packet_xmit
```
**Symbols:**

```
ffffffff8220e4b8-ffffffff8220e4d7: netdev_pick_tx.cold (STB_LOCAL)
ffffffff81eeb250-ffffffff81eeb5b7: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
u16 netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc85e0)
Location: net/core/dev.c:3617
Inline: False
Direct callers:
  - net/core/dev.c:netdev_core_pick_tx
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffff800010bc85e0-ffff800010bc87f0: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u16 netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce3e84)
Location: net/core/dev.c:3617
Inline: False
Direct callers:
  - net/core/dev.c:netdev_core_pick_tx
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
c0ce3e84-c0ce40c4: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u16 netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca4630)
Location: net/core/dev.c:3617
Inline: False
Direct callers:
  - net/core/dev.c:netdev_core_pick_tx
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
c000000000ca4630-c000000000ca4960: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u16 netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000754ac4)
Location: net/core/dev.c:3617
Inline: False
Direct callers:
  - net/core/dev.c:netdev_core_pick_tx
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffe000754ac4-ffffffe000754c76: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
u16 netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cbef0)
Location: net/core/dev.c:3617
Inline: False
Direct callers:
  - net/core/dev.c:netdev_core_pick_tx
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff818cbef0-ffffffff818cc10a: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u16 netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81885e30)
Location: net/core/dev.c:3617
Inline: False
Direct callers:
  - net/core/dev.c:netdev_core_pick_tx
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff81885e30-ffffffff8188604a: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u16 netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191cef0)
Location: net/core/dev.c:3617
Inline: False
Direct callers:
  - net/core/dev.c:netdev_core_pick_tx
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff8191cef0-ffffffff8191d10a: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u16 netdev_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193e3c0)
Location: net/core/dev.c:3617
Inline: False
Direct callers:
  - net/core/dev.c:netdev_core_pick_tx
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff8193e3c0-ffffffff8193e62b: netdev_pick_tx (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net_device *sb_dev</code>
</li>
<li>
<b>Param removed. </b>
<code>void *accel_priv</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct netdev_queue *</code> ➡️ <code>u16</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
