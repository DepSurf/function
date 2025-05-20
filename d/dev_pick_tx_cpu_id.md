# Function: <code>dev_pick_tx_cpu_id</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev, select_queue_fallback_t fallback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ac4d0)
Location: net/core/dev.c:3699
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff818ac4d0-ffffffff818ac4ef: dev_pick_tx_cpu_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f7d50)
Location: net/core/dev.c:3710
Inline: False
```
**Symbols:**

```
ffffffff818f7d50-ffffffff818f7d6f: dev_pick_tx_cpu_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81929b00)
Location: net/core/dev.c:3610
Inline: False
```
**Symbols:**

```
ffffffff81929b00-ffffffff81929b1f: dev_pick_tx_cpu_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fdb40)
Location: net/core/dev.c:3968
Inline: False
```
**Symbols:**

```
ffffffff819fdb40-ffffffff819fdb5f: dev_pick_tx_cpu_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fd710)
Location: net/core/dev.c:3999
Inline: False
```
**Symbols:**

```
ffffffff819fd710-ffffffff819fd72f: dev_pick_tx_cpu_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e3f80)
Location: net/core/dev.c:4082
Inline: False
```
**Symbols:**

```
ffffffff819e3f80-ffffffff819e3f9f: dev_pick_tx_cpu_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a94890)
Location: net/core/dev.c:4047
Inline: False
```
**Symbols:**

```
ffffffff81a94890-ffffffff81a948af: dev_pick_tx_cpu_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0ade0)
Location: net/core/dev.c:4079
Inline: False
```
**Symbols:**

```
ffffffff81c0ade0-ffffffff81c0ae07: dev_pick_tx_cpu_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbad40)
Location: net/core/dev.c:4066
Inline: False
```
**Symbols:**

```
ffffffff81dbad40-ffffffff81dbad67: dev_pick_tx_cpu_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2b4d0)
Location: net/core/dev.c:4026
Inline: False
```
**Symbols:**

```
ffffffff81e2b4d0-ffffffff81e2b4f7: dev_pick_tx_cpu_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ee9530)
Location: net/core/dev.c:4176
Inline: False
```
**Symbols:**

```
ffffffff81ee9530-ffffffff81ee9554: dev_pick_tx_cpu_id (STB_GLOBAL)
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
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcb130)
Location: net/core/dev.c:3610
Inline: False
```
**Symbols:**

```
ffff800010bcb130-ffff800010bcb170: dev_pick_tx_cpu_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce1830)
Location: net/core/dev.c:3610
Inline: False
```
**Symbols:**

```
c0ce1830-c0ce1864: dev_pick_tx_cpu_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca0d60)
Location: net/core/dev.c:3610
Inline: False
```
**Symbols:**

```
c000000000ca0d60-c000000000ca0d84: dev_pick_tx_cpu_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000752968)
Location: net/core/dev.c:3610
Inline: False
```
**Symbols:**

```
ffffffe000752968-ffffffe000752998: dev_pick_tx_cpu_id (STB_GLOBAL)
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
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818c9b00)
Location: net/core/dev.c:3610
Inline: False
```
**Symbols:**

```
ffffffff818c9b00-ffffffff818c9b1f: dev_pick_tx_cpu_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81883a40)
Location: net/core/dev.c:3610
Inline: False
```
**Symbols:**

```
ffffffff81883a40-ffffffff81883a5f: dev_pick_tx_cpu_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191ab00)
Location: net/core/dev.c:3610
Inline: False
```
**Symbols:**

```
ffffffff8191ab00-ffffffff8191ab1f: dev_pick_tx_cpu_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u16 dev_pick_tx_cpu_id(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193bd10)
Location: net/core/dev.c:3610
Inline: False
```
**Symbols:**

```
ffffffff8193bd10-ffffffff8193bd2f: dev_pick_tx_cpu_id (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>select_queue_fallback_t fallback</code>
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
