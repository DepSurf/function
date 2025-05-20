# Function: <code>ndo_dflt_bridge_getlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172f3d0)
Location: net/core/rtnetlink.c:2992
Inline: False
```
**Symbols:**

```
ffffffff8172f3d0-ffffffff8172f9df: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81798f70)
Location: net/core/rtnetlink.c:3195
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_bridge_getlink
```
**Symbols:**

```
ffffffff81798f70-ffffffff81799567: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c6d20)
Location: net/core/rtnetlink.c:3296
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_bridge_getlink
```
**Symbols:**

```
ffffffff817c6d20-ffffffff817c730a: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e5630)
Location: net/core/rtnetlink.c:3397
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_bridge_getlink
```
**Symbols:**

```
ffffffff817e5630-ffffffff817e5b61: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818606d0)
Location: net/core/rtnetlink.c:3634
Inline: False
```
**Symbols:**

```
ffffffff818606d0-ffffffff81860c04: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818aa580)
Location: net/core/rtnetlink.c:3792
Inline: False
```
**Symbols:**

```
ffffffff818aa580-ffffffff818aaaf6: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818d0420)
Location: net/core/rtnetlink.c:4191
Inline: False
```
**Symbols:**

```
ffffffff818d0420-ffffffff818d0993: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:4259
Inline: False
```
**Symbols:**

```
ffffffff8191e9ef-ffffffff8191ea95: ndo_dflt_bridge_getlink.cold (STB_LOCAL)
ffffffff8191d2d0-ffffffff8191d80f: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8194f900)
Location: net/core/rtnetlink.c:4290
Inline: False
```
**Symbols:**

```
ffffffff8194f900-ffffffff8194fe31: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a21120)
Location: net/core/rtnetlink.c:4493
Inline: False
```
**Symbols:**

```
ffffffff81a21120-ffffffff81a21735: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:4585
Inline: False
```
**Symbols:**

```
ffffffff81c316c7-ffffffff81c316df: ndo_dflt_bridge_getlink.cold (STB_LOCAL)
ffffffff81a1f6a0-ffffffff81a1fcbe: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:4583
Inline: False
```
**Symbols:**

```
ffffffff81c239d0-ffffffff81c239e8: ndo_dflt_bridge_getlink.cold (STB_LOCAL)
ffffffff81a06770-ffffffff81a06d82: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:4604
Inline: False
```
**Symbols:**

```
ffffffff81d36e7e-ffffffff81d36e96: ndo_dflt_bridge_getlink.cold (STB_LOCAL)
ffffffff81ab8bd0-ffffffff81ab91e3: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:4725
Inline: False
```
**Symbols:**

```
ffffffff81f0375c-ffffffff81f03774: ndo_dflt_bridge_getlink.cold (STB_LOCAL)
ffffffff81c31e10-ffffffff81c3246c: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de51e0)
Location: net/core/rtnetlink.c:4776
Inline: False
```
**Symbols:**

```
ffffffff81de51e0-ffffffff81de5854: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e56c00)
Location: net/core/rtnetlink.c:4865
Inline: False
```
**Symbols:**

```
ffffffff81e56c00-ffffffff81e57268: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f15f50)
Location: net/core/rtnetlink.c:4898
Inline: False
```
**Symbols:**

```
ffffffff81f15f50-ffffffff81f165ca: ndo_dflt_bridge_getlink (STB_GLOBAL)
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
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bf1600)
Location: net/core/rtnetlink.c:4290
Inline: False
```
**Symbols:**

```
ffff800010bf1600-ffff800010bf1ac4: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d09db4)
Location: net/core/rtnetlink.c:4290
Inline: False
```
**Symbols:**

```
c0d09db4-c0d0a36c: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cd60a0)
Location: net/core/rtnetlink.c:4290
Inline: False
```
**Symbols:**

```
c000000000cd60a0-c000000000cd66b0: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe0007733a8)
Location: net/core/rtnetlink.c:4290
Inline: False
```
**Symbols:**

```
ffffffe0007733a8-ffffffe000773774: ndo_dflt_bridge_getlink (STB_GLOBAL)
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
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ef8d0)
Location: net/core/rtnetlink.c:4290
Inline: False
```
**Symbols:**

```
ffffffff818ef8d0-ffffffff818efe01: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a9710)
Location: net/core/rtnetlink.c:4290
Inline: False
```
**Symbols:**

```
ffffffff818a9710-ffffffff818a9c41: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81940900)
Location: net/core/rtnetlink.c:4290
Inline: False
```
**Symbols:**

```
ffffffff81940900-ffffffff81940e31: ndo_dflt_bridge_getlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ndo_dflt_bridge_getlink(struct sk_buff *skb, u32 pid, u32 seq, struct net_device *dev, u16 mode, u32 flags, u32 mask, int nlflags, u32 filter_mask, int (*vlan_fill)(struct sk_buff *, struct net_device *, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81962210)
Location: net/core/rtnetlink.c:4290
Inline: False
```
**Symbols:**

```
ffffffff81962210-ffffffff81962741: ndo_dflt_bridge_getlink (STB_GLOBAL)
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
