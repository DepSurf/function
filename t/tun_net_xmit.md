# Function: <code>tun_net_xmit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff815ee810)
Location: drivers/net/tun.c:806
Inline: False
```
**Symbols:**

```
ffffffff815ee810-ffffffff815eeb78: tun_net_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8164d3e0)
Location: drivers/net/tun.c:840
Inline: False
```
**Symbols:**

```
ffffffff8164d3e0-ffffffff8164d752: tun_net_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8167f120)
Location: drivers/net/tun.c:845
Inline: False
```
**Symbols:**

```
ffffffff8167f120-ffffffff8167f45f: tun_net_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81694360)
Location: drivers/net/tun.c:848
Inline: False
```
**Symbols:**

```
ffffffff81694360-ffffffff816946a3: tun_net_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816fe430)
Location: drivers/net/tun.c:949
Inline: False
```
**Symbols:**

```
ffffffff816fe430-ffffffff816fe77c: tun_net_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8173d4d0)
Location: drivers/net/tun.c:1072
Inline: False
```
**Symbols:**

```
ffffffff8173d4d0-ffffffff8173d8f8: tun_net_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81760f90)
Location: drivers/net/tun.c:1074
Inline: False
```
**Symbols:**

```
ffffffff81760f90-ffffffff8176139e: tun_net_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8179ec20)
Location: drivers/net/tun.c:1062
Inline: False
```
**Symbols:**

```
ffffffff8179ec20-ffffffff8179f07e: tun_net_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c3370)
Location: drivers/net/tun.c:1062
Inline: False
```
**Symbols:**

```
ffffffff817c3370-ffffffff817c37a9: tun_net_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:1030
Inline: False
```
**Symbols:**

```
ffffffff8188e6b0-ffffffff8188eace: tun_net_xmit (STB_LOCAL)
ffffffff818909df-ffffffff81890a03: tun_net_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:1001
Inline: False
```
**Symbols:**

```
ffffffff8189d010-ffffffff8189d43d: tun_net_xmit (STB_LOCAL)
ffffffff81c19652-ffffffff81c19676: tun_net_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:1009
Inline: False
```
**Symbols:**

```
ffffffff8187f840-ffffffff8187fc84: tun_net_xmit (STB_LOCAL)
ffffffff81c0b4ad-ffffffff81c0b4d1: tun_net_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:1058
Inline: False
```
**Symbols:**

```
ffffffff819109b0-ffffffff81910e83: tun_net_xmit (STB_LOCAL)
ffffffff81d10ac3-ffffffff81d10ae7: tun_net_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:1068
Inline: False
```
**Symbols:**

```
ffffffff81a60780-ffffffff81a60cef: tun_net_xmit (STB_LOCAL)
ffffffff81edb7ba-ffffffff81edb7dd: tun_net_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81becd40)
Location: drivers/net/tun.c:1070
Inline: False
```
**Symbols:**

```
ffffffff81becd40-ffffffff81bed2d9: tun_net_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c45240)
Location: drivers/net/tun.c:1070
Inline: False
```
**Symbols:**

```
ffffffff81c45240-ffffffff81c45802: tun_net_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfab70)
Location: drivers/net/tun.c:1071
Inline: False
```
**Symbols:**

```
ffffffff81cfab70-ffffffff81cfb11b: tun_net_xmit (STB_LOCAL)
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
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109dedf8)
Location: drivers/net/tun.c:1062
Inline: False
```
**Symbols:**

```
ffff8000109dedf8-ffff8000109df208: tun_net_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac29cc)
Location: drivers/net/tun.c:1062
Inline: False
```
**Symbols:**

```
c0ac29cc-c0ac2e30: tun_net_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000aa06f0)
Location: drivers/net/tun.c:1062
Inline: False
```
**Symbols:**

```
c000000000aa06f0-c000000000aa0cb8: tun_net_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe00062804a)
Location: drivers/net/tun.c:1062
Inline: False
```
**Symbols:**

```
ffffffe00062804a-ffffffe000628444: tun_net_xmit (STB_LOCAL)
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
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81787e40)
Location: drivers/net/tun.c:1062
Inline: False
```
**Symbols:**

```
ffffffff81787e40-ffffffff81788281: tun_net_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81767790)
Location: drivers/net/tun.c:1062
Inline: False
```
**Symbols:**

```
ffffffff81767790-ffffffff81767bd1: tun_net_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817b81f0)
Location: drivers/net/tun.c:1062
Inline: False
```
**Symbols:**

```
ffffffff817b81f0-ffffffff817b8629: tun_net_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
netdev_tx_t tun_net_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817d04d0)
Location: drivers/net/tun.c:1062
Inline: False
```
**Symbols:**

```
ffffffff817d04d0-ffffffff817d093e: tun_net_xmit (STB_LOCAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
