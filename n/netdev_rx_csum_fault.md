# Function: <code>netdev_rx_csum_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81717000)
Location: net/core/dev.c:2576
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/datagram.c:__skb_checksum_complete_head
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
**Symbols:**

```
ffffffff81717000-ffffffff8171703a: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81780403)
Location: net/core/dev.c:2746
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
```
**Symbols:**

```
ffffffff8177ef20-ffffffff8177ef5a: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817add53)
Location: net/core/dev.c:2743
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
```
**Symbols:**

```
ffffffff817ac700-ffffffff817ac73a: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cc8b3)
Location: net/core/dev.c:2807
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
```
**Symbols:**

```
ffffffff817cae40-ffffffff817cae7a: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81845f83)
Location: net/core/dev.c:2834
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
```
**Symbols:**

```
ffffffff81844680-ffffffff818446ba: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8188e4d1)
Location: net/core/dev.c:2876
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
```
**Symbols:**

```
ffffffff81898f16-ffffffff81898f3a: netdev_rx_csum_fault.cold.150 (STB_LOCAL)
ffffffff8188f840-ffffffff8188f85d: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818af47e)
Location: net/core/dev.c:3113
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__skb_gro_checksum_complete
```
**Symbols:**

```
ffffffff818bb2c7-ffffffff818bb392: netdev_rx_csum_fault.part.120 (STB_LOCAL)
ffffffff818bb392-ffffffff818bb3a2: netdev_rx_csum_fault.cold.156 (STB_LOCAL)
ffffffff818af3d0-ffffffff818af3f4: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818fb2be)
Location: net/core/dev.c:3121
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__skb_gro_checksum_complete
```
**Symbols:**

```
ffffffff81906c54-ffffffff81906c99: netdev_rx_csum_fault.part.0 (STB_LOCAL)
ffffffff81906c99-ffffffff81906ca9: netdev_rx_csum_fault.cold (STB_LOCAL)
ffffffff818fb210-ffffffff818fb236: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8192d40e)
Location: net/core/dev.c:3039
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__skb_gro_checksum_complete
```
**Symbols:**

```
ffffffff81939339-ffffffff8193937e: netdev_rx_csum_fault.part.0 (STB_LOCAL)
ffffffff8193937e-ffffffff8193938e: netdev_rx_csum_fault.cold (STB_LOCAL)
ffffffff8192d360-ffffffff8192d386: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81a0249e)
Location: net/core/dev.c:3397
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__skb_gro_checksum_complete
```
**Symbols:**

```
ffffffff81a0edcb-ffffffff81a0ee10: netdev_rx_csum_fault.part.0 (STB_LOCAL)
ffffffff81a0ee10-ffffffff81a0ee20: netdev_rx_csum_fault.cold (STB_LOCAL)
ffffffff81a00530-ffffffff81a00556: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81a02c9e)
Location: net/core/dev.c:3422
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__skb_gro_checksum_complete
```
**Symbols:**

```
ffffffff81c310bf-ffffffff81c31104: netdev_rx_csum_fault.part.0 (STB_LOCAL)
ffffffff81c31104-ffffffff81c31114: netdev_rx_csum_fault.cold (STB_LOCAL)
ffffffff81a00b00-ffffffff81a00b26: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff819e9516)
Location: net/core/dev.c:3490
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__skb_gro_checksum_complete
```
**Symbols:**

```
ffffffff81c233c5-ffffffff81c2340d: netdev_rx_csum_fault.part.0 (STB_LOCAL)
ffffffff81c2340d-ffffffff81c2341d: netdev_rx_csum_fault.cold (STB_LOCAL)
ffffffff819e7020-ffffffff819e7046: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3424
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__skb_gro_checksum_complete
```
**Symbols:**

```
ffffffff81d358b3-ffffffff81d3590a: netdev_rx_csum_fault.cold (STB_LOCAL)
ffffffff81a97520-ffffffff81a97557: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3431
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/gro.c:__skb_gro_checksum_complete
```
**Symbols:**

```
ffffffff81f023d3-ffffffff81f0241c: netdev_rx_csum_fault.cold (STB_LOCAL)
ffffffff81c0eaa0-ffffffff81c0eae1: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3418
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/gro.c:__skb_gro_checksum_complete
```
**Symbols:**

```
ffffffff820ab460-ffffffff820ab475: netdev_rx_csum_fault.cold (STB_LOCAL)
ffffffff81dc3d70-ffffffff81dc3ded: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81e3324d)
Location: net/core/dev.c:3378
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/gro.c:__skb_gro_checksum_complete
```
**Symbols:**

```
ffffffff8212ca95-ffffffff8212caaa: netdev_rx_csum_fault.cold (STB_LOCAL)
ffffffff81e33210-ffffffff81e3328d: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81ef137d)
Location: net/core/dev.c:3385
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/gro.c:__skb_gro_checksum_complete
```
**Symbols:**

```
ffffffff8220e7bf-ffffffff8220e7d4: netdev_rx_csum_fault.cold (STB_LOCAL)
ffffffff81ef1340-ffffffff81ef13bd: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffff800010bc94a8)
Location: net/core/dev.c:3039
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__skb_gro_checksum_complete
```
**Symbols:**

```
ffff800010bd89d0-ffff800010bd8a2c: netdev_rx_csum_fault.part.0 (STB_LOCAL)
ffff800010bc93c8-ffff800010bc9408: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (c0ce672c)
Location: net/core/dev.c:3039
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__skb_gro_checksum_complete
```
**Symbols:**

```
c0cf3264-c0cf32b8: netdev_rx_csum_fault.part.0 (STB_LOCAL)
c0ce6664-c0ce669c: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (c000000000ca70c8)
Location: net/core/dev.c:3039
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__skb_gro_checksum_complete
```
**Symbols:**

```
c000000000cb8474-c000000000cb84f4: netdev_rx_csum_fault.part.0 (STB_LOCAL)
c000000000ca6f80-c000000000ca6ff4: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffe000756158)
Location: net/core/dev.c:3039
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__skb_gro_checksum_complete
```
**Symbols:**

```
ffffffe0007615d4-ffffffe000761632: netdev_rx_csum_fault.part.0 (STB_LOCAL)
ffffffe000756078-ffffffe0007560b6: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818cd40e)
Location: net/core/dev.c:3039
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__skb_gro_checksum_complete
```
**Symbols:**

```
ffffffff818d9309-ffffffff818d934e: netdev_rx_csum_fault.part.0 (STB_LOCAL)
ffffffff818d934e-ffffffff818d935e: netdev_rx_csum_fault.cold (STB_LOCAL)
ffffffff818cd360-ffffffff818cd386: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8188752e)
Location: net/core/dev.c:3039
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__skb_gro_checksum_complete
```
**Symbols:**

```
ffffffff81893149-ffffffff8189318e: netdev_rx_csum_fault.part.0 (STB_LOCAL)
ffffffff8189318e-ffffffff8189319e: netdev_rx_csum_fault.cold (STB_LOCAL)
ffffffff81887480-ffffffff818874a6: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8191e40e)
Location: net/core/dev.c:3039
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__skb_gro_checksum_complete
```
**Symbols:**

```
ffffffff8192a339-ffffffff8192a37e: netdev_rx_csum_fault.part.0 (STB_LOCAL)
ffffffff8192a37e-ffffffff8192a38e: netdev_rx_csum_fault.cold (STB_LOCAL)
ffffffff8191e360-ffffffff8191e386: netdev_rx_csum_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netdev_rx_csum_fault(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8193fa9e)
Location: net/core/dev.c:3039
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
Direct callers:
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/dev.c:__skb_gro_checksum_complete
```
**Symbols:**

```
ffffffff8194ba31-ffffffff8194ba76: netdev_rx_csum_fault.part.0 (STB_LOCAL)
ffffffff8194ba76-ffffffff8194ba86: netdev_rx_csum_fault.cold (STB_LOCAL)
ffffffff8193f9f0-ffffffff8193fa16: netdev_rx_csum_fault (STB_GLOBAL)
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
<code>struct sk_buff *skb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
