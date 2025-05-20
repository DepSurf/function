# Function: <code>xennet_start_xmit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff815fab50)
Location: drivers/net/xen-netfront.c:562
Inline: False
```
**Symbols:**

```
ffffffff815fab50-ffffffff815fb027: xennet_start_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8165aa30)
Location: drivers/net/xen-netfront.c:553
Inline: False
```
**Symbols:**

```
ffffffff8165aa30-ffffffff8165af7f: xennet_start_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81688790)
Location: drivers/net/xen-netfront.c:561
Inline: False
```
**Symbols:**

```
ffffffff81688790-ffffffff81688d6f: xennet_start_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8169df40)
Location: drivers/net/xen-netfront.c:562
Inline: False
```
**Symbols:**

```
ffffffff8169df40-ffffffff8169e520: xennet_start_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817090e0)
Location: drivers/net/xen-netfront.c:564
Inline: False
```
**Symbols:**

```
ffffffff817090e0-ffffffff817096c0: xennet_start_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
netdev_tx_t xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:567
Inline: False
```
**Symbols:**

```
ffffffff81747c20-ffffffff8174819a: xennet_start_xmit (STB_LOCAL)
ffffffff8174a3e1-ffffffff8174a3fa: xennet_start_xmit.cold.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
netdev_tx_t xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:566
Inline: False
```
**Symbols:**

```
ffffffff8176bd10-ffffffff8176c25c: xennet_start_xmit (STB_LOCAL)
ffffffff8176e56b-ffffffff8176e580: xennet_start_xmit.cold.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
netdev_tx_t xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:565
Inline: False
```
**Symbols:**

```
ffffffff817a9b00-ffffffff817aa074: xennet_start_xmit (STB_LOCAL)
ffffffff817ac262-ffffffff817ac278: xennet_start_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
netdev_tx_t xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:565
Inline: False
```
**Symbols:**

```
ffffffff817cd570-ffffffff817cdadc: xennet_start_xmit (STB_LOCAL)
ffffffff817cfca2-ffffffff817cfcb8: xennet_start_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
netdev_tx_t xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:567
Inline: False
```
**Symbols:**

```
ffffffff81899050-ffffffff818996e2: xennet_start_xmit (STB_LOCAL)
ffffffff8189a77b-ffffffff8189a791: xennet_start_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
netdev_tx_t xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:639
Inline: False
```
**Symbols:**

```
ffffffff818a7550-ffffffff818a7c14: xennet_start_xmit (STB_LOCAL)
ffffffff81c19db8-ffffffff81c19dce: xennet_start_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
netdev_tx_t xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:637
Inline: False
```
**Symbols:**

```
ffffffff8188ae00-ffffffff8188b4a7: xennet_start_xmit (STB_LOCAL)
ffffffff81c0bbf8-ffffffff81c0bc0e: xennet_start_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
netdev_tx_t xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:673
Inline: False
```
**Symbols:**

```
ffffffff8191d940-ffffffff8191e027: xennet_start_xmit (STB_LOCAL)
ffffffff81d1134d-ffffffff81d11376: xennet_start_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
netdev_tx_t xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:706
Inline: False
```
**Symbols:**

```
ffffffff81a74fc0-ffffffff81a75800: xennet_start_xmit (STB_LOCAL)
ffffffff81edc31d-ffffffff81edc39e: xennet_start_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
netdev_tx_t xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:706
Inline: False
```
**Symbols:**

```
ffffffff81c06940-ffffffff81c072e0: xennet_start_xmit (STB_LOCAL)
ffffffff8209db8b-ffffffff8209dc0d: xennet_start_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
netdev_tx_t xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:706
Inline: False
```
**Symbols:**

```
ffffffff81c6c050-ffffffff81c6c9d4: xennet_start_xmit (STB_LOCAL)
ffffffff8211f113-ffffffff8211f185: xennet_start_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
netdev_tx_t xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:707
Inline: False
```
**Symbols:**

```
ffffffff81d20a00-ffffffff81d2132a: xennet_start_xmit (STB_LOCAL)
ffffffff822008e9-ffffffff8220095b: xennet_start_xmit.cold (STB_LOCAL)
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
netdev_tx_t xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffff800010a092f0)
Location: drivers/net/xen-netfront.c:565
Inline: False
```
**Symbols:**

```
ffff800010a092f0-ffff800010a09874: xennet_start_xmit (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
netdev_tx_t xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:582
Inline: False
```
**Symbols:**

```
ffffffff81792190-ffffffff817926fc: xennet_start_xmit (STB_LOCAL)
ffffffff81794916-ffffffff8179492c: xennet_start_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
netdev_tx_t xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:565
Inline: False
```
**Symbols:**

```
ffffffff817c23f0-ffffffff817c295c: xennet_start_xmit (STB_LOCAL)
ffffffff817c4b22-ffffffff817c4b38: xennet_start_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
netdev_tx_t xennet_start_xmit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:565
Inline: False
```
**Symbols:**

```
ffffffff817dc6b0-ffffffff817dcc1c: xennet_start_xmit (STB_LOCAL)
ffffffff817dedc9-ffffffff817deddf: xennet_start_xmit.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>netdev_tx_t</code>
</li>
</ul>
</details>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
