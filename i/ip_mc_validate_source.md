# Function: <code>ip_mc_validate_source</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81890ac0)
Location: net/ipv4/route.c:1530
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81890ac0-ffffffff81890b6a: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e46d0)
Location: net/ipv4/route.c:1603
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff818e46d0-ffffffff818e477a: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81911600)
Location: net/ipv4/route.c:1600
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81911600-ffffffff819116aa: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81973c40)
Location: net/ipv4/route.c:1684
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81973c40-ffffffff81973d06: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819aa660)
Location: net/ipv4/route.c:1688
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff819aa660-ffffffff819aa726: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a949a0)
Location: net/ipv4/route.c:1690
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81a949a0-ffffffff81a94a66: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9e9a0)
Location: net/ipv4/route.c:1696
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81a9e9a0-ffffffff81a9ea66: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a89900)
Location: net/ipv4/route.c:1684
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81a89900-ffffffff81a899c3: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b44490)
Location: net/ipv4/route.c:1680
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81b44490-ffffffff81b44553: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81cd10b0)
Location: net/ipv4/route.c:1693
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81cd10b0-ffffffff81cd11d7: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e91330)
Location: net/ipv4/route.c:1691
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81e91330-ffffffff81e91457: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81eefab0)
Location: net/ipv4/route.c:1689
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81eefab0-ffffffff81eefbd7: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb3c00)
Location: net/ipv4/route.c:1691
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81fb3c00-ffffffff81fb3d27: ip_mc_validate_source (STB_GLOBAL)
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
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c5a9f0)
Location: net/ipv4/route.c:1688
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffff800010c5a9f0-ffff800010c5ab08: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d69ee8)
Location: net/ipv4/route.c:1688
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
c0d69ee8-c0d69fcc: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5c610)
Location: net/ipv4/route.c:1688
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
c000000000d5c610-c000000000d5c710: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c3df4)
Location: net/ipv4/route.c:1688
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffe0007c3df4-ffffffe0007c3ec6: ip_mc_validate_source (STB_GLOBAL)
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
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8194a4d0)
Location: net/ipv4/route.c:1688
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff8194a4d0-ffffffff8194a596: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81903fc0)
Location: net/ipv4/route.c:1688
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81903fc0-ffffffff81904086: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b4ca0)
Location: net/ipv4/route.c:1688
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff819b4ca0-ffffffff819b4d66: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip_mc_validate_source(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct in_device *in_dev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819be3e0)
Location: net/ipv4/route.c:1688
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff819be3e0-ffffffff819be4a6: ip_mc_validate_source (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
