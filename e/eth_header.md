# Function: <code>eth_header</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8173fe10)
Location: net/ethernet/eth.c:81
Inline: False
```
**Symbols:**

```
ffffffff8173fe10-ffffffff8173fecd: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff817acb50)
Location: net/ethernet/eth.c:81
Inline: False
```
**Symbols:**

```
ffffffff817acb50-ffffffff817acc0d: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff817dc140)
Location: net/ethernet/eth.c:82
Inline: False
```
**Symbols:**

```
ffffffff817dc140-ffffffff817dc1fd: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff817fb810)
Location: net/ethernet/eth.c:82
Inline: False
```
**Symbols:**

```
ffffffff817fb810-ffffffff817fb8ce: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff818791c0)
Location: net/ethernet/eth.c:82
Inline: False
```
**Symbols:**

```
ffffffff818791c0-ffffffff8187927e: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff818caba0)
Location: net/ethernet/eth.c:82
Inline: False
```
**Symbols:**

```
ffffffff818caba0-ffffffff818cac60: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff818f5c70)
Location: net/ethernet/eth.c:83
Inline: False
```
**Symbols:**

```
ffffffff818f5c70-ffffffff818f5d30: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81955330)
Location: net/ethernet/eth.c:79
Inline: False
```
**Symbols:**

```
ffffffff81955330-ffffffff819553f0: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8198b7d0)
Location: net/ethernet/eth.c:79
Inline: False
```
**Symbols:**

```
ffffffff8198b7d0-ffffffff8198b890: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81a63490)
Location: net/ethernet/eth.c:79
Inline: False
```
**Symbols:**

```
ffffffff81a63490-ffffffff81a63550: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81a6b5e0)
Location: net/ethernet/eth.c:79
Inline: False
Direct callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
**Symbols:**

```
ffffffff81a6b5e0-ffffffff81a6b6a0: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81a53d10)
Location: net/ethernet/eth.c:80
Inline: False
Direct callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
**Symbols:**

```
ffffffff81a53d10-ffffffff81a53dd0: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81b0ca20)
Location: net/ethernet/eth.c:78
Inline: False
Direct callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
**Symbols:**

```
ffffffff81b0ca20-ffffffff81b0cae0: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81c93310)
Location: net/ethernet/eth.c:79
Inline: False
Direct callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
**Symbols:**

```
ffffffff81c93310-ffffffff81c933d4: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81e4ebd0)
Location: net/ethernet/eth.c:79
Inline: False
Direct callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
**Symbols:**

```
ffffffff81e4ebd0-ffffffff81e4ec94: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81eaa270)
Location: net/ethernet/eth.c:79
Inline: False
Direct callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
**Symbols:**

```
ffffffff81eaa270-ffffffff81eaa334: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81f6cd20)
Location: net/ethernet/eth.c:79
Inline: False
Direct callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
**Symbols:**

```
ffffffff81f6cd20-ffffffff81f6cde4: eth_header (STB_GLOBAL)
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
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffff800010c36718)
Location: net/ethernet/eth.c:79
Inline: False
```
**Symbols:**

```
ffff800010c36718-ffff800010c367fc: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (c0d49124)
Location: net/ethernet/eth.c:79
Inline: False
```
**Symbols:**

```
c0d49124-c0d491d0: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (c000000000d2e7c0)
Location: net/ethernet/eth.c:79
Inline: False
```
**Symbols:**

```
c000000000d2e7c0-c000000000d2e928: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffe0007a80b0)
Location: net/ethernet/eth.c:79
Inline: False
```
**Symbols:**

```
ffffffe0007a80b0-ffffffe0007a81be: eth_header (STB_GLOBAL)
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
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8192b640)
Location: net/ethernet/eth.c:79
Inline: False
```
**Symbols:**

```
ffffffff8192b640-ffffffff8192b700: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff818e53f0)
Location: net/ethernet/eth.c:79
Inline: False
```
**Symbols:**

```
ffffffff818e53f0-ffffffff818e54b0: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8197c7d0)
Location: net/ethernet/eth.c:79
Inline: False
```
**Symbols:**

```
ffffffff8197c7d0-ffffffff8197c890: eth_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int eth_header(struct sk_buff *skb, struct net_device *dev, short unsigned int type, const void *daddr, const void *saddr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8199ed20)
Location: net/ethernet/eth.c:79
Inline: False
```
**Symbols:**

```
ffffffff8199ed20-ffffffff8199ede0: eth_header (STB_GLOBAL)
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
