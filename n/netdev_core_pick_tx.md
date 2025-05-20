# Function: <code>netdev_core_pick_tx</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct netdev_queue *netdev_core_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3744
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff81907407-ffffffff81907428: netdev_core_pick_tx.cold (STB_LOCAL)
ffffffff819010b0-ffffffff81901153: netdev_core_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct netdev_queue *netdev_core_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3644
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff81939a01-ffffffff81939a22: netdev_core_pick_tx.cold (STB_LOCAL)
ffffffff819333e0-ffffffff81933483: netdev_core_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct netdev_queue *netdev_core_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4002
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:__netpoll_send_skb
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff81a0efc9-ffffffff81a0efea: netdev_core_pick_tx.cold (STB_LOCAL)
ffffffff81a08250-ffffffff81a082f9: netdev_core_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct netdev_queue *netdev_core_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
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
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:__netpoll_send_skb
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff81c312f1-ffffffff81c31312: netdev_core_pick_tx.cold (STB_LOCAL)
ffffffff81a097e0-ffffffff81a09889: netdev_core_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct netdev_queue *netdev_core_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4116
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:__netpoll_send_skb
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff81c235b7-ffffffff81c235d8: netdev_core_pick_tx.cold (STB_LOCAL)
ffffffff819f0150-ffffffff819f01f9: netdev_core_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct netdev_queue *netdev_core_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4081
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:__netpoll_send_skb
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff81d36375-ffffffff81d36396: netdev_core_pick_tx.cold (STB_LOCAL)
ffffffff81aa1580-ffffffff81aa1629: netdev_core_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct netdev_queue *netdev_core_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4113
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:__netpoll_send_skb
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff81f02b4b-ffffffff81f02b68: netdev_core_pick_tx.cold (STB_LOCAL)
ffffffff81c195b0-ffffffff81c19665: netdev_core_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct netdev_queue *netdev_core_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dca5d0)
Location: net/core/dev.c:4100
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:__netpoll_send_skb
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff81dca5d0-ffffffff81dca69b: netdev_core_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct netdev_queue *netdev_core_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3b150)
Location: net/core/dev.c:4060
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:__netpoll_send_skb
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff81e3b150-ffffffff81e3b21b: netdev_core_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct netdev_queue *netdev_core_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef9520)
Location: net/core/dev.c:4210
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:__netpoll_send_skb
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff81ef9520-ffffffff81ef95e0: netdev_core_pick_tx (STB_GLOBAL)
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
struct netdev_queue *netdev_core_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd1498)
Location: net/core/dev.c:3644
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffff800010bd1498-ffff800010bd159c: netdev_core_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct netdev_queue *netdev_core_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cec0e8)
Location: net/core/dev.c:3644
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
c0cec0e8-c0cec1c8: netdev_core_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct netdev_queue *netdev_core_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000caf7a0)
Location: net/core/dev.c:3644
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
c000000000caf7a0-c000000000caf908: netdev_core_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct netdev_queue *netdev_core_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075b9c8)
Location: net/core/dev.c:3644
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffe00075b9c8-ffffffe00075ba88: netdev_core_pick_tx (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct netdev_queue *netdev_core_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3644
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff818d99d1-ffffffff818d99f2: netdev_core_pick_tx.cold (STB_LOCAL)
ffffffff818d33e0-ffffffff818d3483: netdev_core_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct netdev_queue *netdev_core_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3644
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff81893811-ffffffff81893832: netdev_core_pick_tx.cold (STB_LOCAL)
ffffffff8188d270-ffffffff8188d313: netdev_core_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct netdev_queue *netdev_core_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3644
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff8192aa01-ffffffff8192aa22: netdev_core_pick_tx.cold (STB_LOCAL)
ffffffff819243e0-ffffffff81924483: netdev_core_pick_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct netdev_queue *netdev_core_pick_tx(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3644
Inline: False
Direct callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff8194c0d1-ffffffff8194c0f2: netdev_core_pick_tx.cold (STB_LOCAL)
ffffffff81945870-ffffffff81945913: netdev_core_pick_tx (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
