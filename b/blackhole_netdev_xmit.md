# Function: <code>blackhole_netdev_xmit</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
netdev_tx_t blackhole_netdev_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/loopback.c (ffffffff8179409d)
Location: drivers/net/loopback.c:236
Inline: True
```
**Symbols:**

```
ffffffff81794070-ffffffff8179408f: blackhole_netdev_xmit (STB_LOCAL)
ffffffff8179409d-ffffffff817940b5: blackhole_netdev_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
netdev_tx_t blackhole_netdev_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/loopback.c (ffffffff817b7bcd)
Location: drivers/net/loopback.c:236
Inline: True
```
**Symbols:**

```
ffffffff817b7ba0-ffffffff817b7bbf: blackhole_netdev_xmit (STB_LOCAL)
ffffffff817b7bcd-ffffffff817b7be5: blackhole_netdev_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
netdev_tx_t blackhole_netdev_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/loopback.c (ffffffff8187ebd3)
Location: drivers/net/loopback.c:238
Inline: True
```
**Symbols:**

```
ffffffff8187eab0-ffffffff8187eacf: blackhole_netdev_xmit (STB_LOCAL)
ffffffff8187ebd3-ffffffff8187ebeb: blackhole_netdev_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
netdev_tx_t blackhole_netdev_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/loopback.c (ffffffff81c18fab)
Location: drivers/net/loopback.c:238
Inline: True
```
**Symbols:**

```
ffffffff8188d030-ffffffff8188d04f: blackhole_netdev_xmit (STB_LOCAL)
ffffffff81c18fab-ffffffff81c18fc3: blackhole_netdev_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
netdev_tx_t blackhole_netdev_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/loopback.c (ffffffff81c0add9)
Location: drivers/net/loopback.c:238
Inline: True
```
**Symbols:**

```
ffffffff8186f970-ffffffff8186f98f: blackhole_netdev_xmit (STB_LOCAL)
ffffffff81c0add9-ffffffff81c0adf1: blackhole_netdev_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
netdev_tx_t blackhole_netdev_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/loopback.c (ffffffff81d10163)
Location: drivers/net/loopback.c:238
Inline: True
```
**Symbols:**

```
ffffffff818fff10-ffffffff818fff2f: blackhole_netdev_xmit (STB_LOCAL)
ffffffff81d10163-ffffffff81d1017b: blackhole_netdev_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
netdev_tx_t blackhole_netdev_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/loopback.c (ffffffff81edaea0)
Location: drivers/net/loopback.c:241
Inline: True
```
**Symbols:**

```
ffffffff81a51970-ffffffff81a5199c: blackhole_netdev_xmit (STB_LOCAL)
ffffffff81edaea0-ffffffff81edaeb8: blackhole_netdev_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
netdev_tx_t blackhole_netdev_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffff81bdaa20)
Location: drivers/net/loopback.c:241
Inline: True
```
**Symbols:**

```
ffffffff81bdaa20-ffffffff81bdaa67: blackhole_netdev_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
netdev_tx_t blackhole_netdev_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffff81c314c0)
Location: drivers/net/loopback.c:241
Inline: True
```
**Symbols:**

```
ffffffff81c314c0-ffffffff81c31507: blackhole_netdev_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
netdev_tx_t blackhole_netdev_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffff81ce4340)
Location: drivers/net/loopback.c:241
Inline: True
```
**Symbols:**

```
ffffffff81ce4340-ffffffff81ce4387: blackhole_netdev_xmit (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
netdev_tx_t blackhole_netdev_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffff8000109d0148)
Location: drivers/net/loopback.c:236
Inline: True
```
**Symbols:**

```
ffff8000109d0148-ffff8000109d019c: blackhole_netdev_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
netdev_tx_t blackhole_netdev_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (c0ab83cc)
Location: drivers/net/loopback.c:236
Inline: True
```
**Symbols:**

```
c0ab83cc-c0ab8410: blackhole_netdev_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
netdev_tx_t blackhole_netdev_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (c000000000a8f320)
Location: drivers/net/loopback.c:236
Inline: True
```
**Symbols:**

```
c000000000a8f320-c000000000a8f384: blackhole_netdev_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
netdev_tx_t blackhole_netdev_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffe00061ce4e)
Location: drivers/net/loopback.c:236
Inline: True
```
**Symbols:**

```
ffffffe00061ce4e-ffffffe00061ce9e: blackhole_netdev_xmit (STB_LOCAL)
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
netdev_tx_t blackhole_netdev_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/loopback.c (ffffffff8177c69d)
Location: drivers/net/loopback.c:236
Inline: True
```
**Symbols:**

```
ffffffff8177c670-ffffffff8177c68f: blackhole_netdev_xmit (STB_LOCAL)
ffffffff8177c69d-ffffffff8177c6b5: blackhole_netdev_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
netdev_tx_t blackhole_netdev_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/loopback.c (ffffffff8175c44d)
Location: drivers/net/loopback.c:236
Inline: True
```
**Symbols:**

```
ffffffff8175c420-ffffffff8175c43f: blackhole_netdev_xmit (STB_LOCAL)
ffffffff8175c44d-ffffffff8175c465: blackhole_netdev_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
netdev_tx_t blackhole_netdev_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/loopback.c (ffffffff817aca4d)
Location: drivers/net/loopback.c:236
Inline: True
```
**Symbols:**

```
ffffffff817aca20-ffffffff817aca3f: blackhole_netdev_xmit (STB_LOCAL)
ffffffff817aca4d-ffffffff817aca65: blackhole_netdev_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
netdev_tx_t blackhole_netdev_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/loopback.c (ffffffff817c69dd)
Location: drivers/net/loopback.c:236
Inline: True
```
**Symbols:**

```
ffffffff817c69b0-ffffffff817c69cf: blackhole_netdev_xmit (STB_LOCAL)
ffffffff817c69dd-ffffffff817c69f5: blackhole_netdev_xmit.cold (STB_LOCAL)
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
