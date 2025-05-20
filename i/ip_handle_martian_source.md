# Function: <code>ip_handle_martian_source</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81753950)
Location: net/ipv4/route.c:1535
Inline: True
```
**Symbols:**

```
ffffffff81753950-ffffffff81753a13: ip_handle_martian_source.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff817bfa20)
Location: net/ipv4/route.c:1542
Inline: True
```
**Symbols:**

```
ffffffff817bfa20-ffffffff817bfae3: ip_handle_martian_source.isra.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff817ef370)
Location: net/ipv4/route.c:1552
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff817ef370-ffffffff817ef433: ip_handle_martian_source.isra.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff8180f690)
Location: net/ipv4/route.c:1585
Inline: True
```
**Symbols:**

```
ffffffff8180f690-ffffffff8180f74e: ip_handle_martian_source.isra.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff8188ebc0)
Location: net/ipv4/route.c:1598
Inline: True
```
**Symbols:**

```
ffffffff8188ebc0-ffffffff8188ec7e: ip_handle_martian_source.isra.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1671
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff818e2830-ffffffff818e288b: ip_handle_martian_source.isra.44 (STB_LOCAL)
ffffffff818e763c-ffffffff818e76ae: ip_handle_martian_source.isra.44.cold.61 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1668
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff8190f6d0-ffffffff8190f72b: ip_handle_martian_source.isra.47 (STB_LOCAL)
ffffffff819144ec-ffffffff8191455e: ip_handle_martian_source.isra.47.cold.64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1753
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff819718e0-ffffffff81971939: ip_handle_martian_source.isra.0 (STB_LOCAL)
ffffffff819769a6-ffffffff81976a17: ip_handle_martian_source.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1757
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff819a82e0-ffffffff819a8339: ip_handle_martian_source.isra.0 (STB_LOCAL)
ffffffff819ad37d-ffffffff819ad3ee: ip_handle_martian_source.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ip_handle_martian_source(struct net_device *dev, struct in_device *in_dev, struct sk_buff *skb, __be32 daddr, __be32 saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1759
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81a90a00-ffffffff81a90a5c: ip_handle_martian_source (STB_LOCAL)
ffffffff81a97120-ffffffff81a97191: ip_handle_martian_source.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ip_handle_martian_source(struct net_device *dev, struct in_device *in_dev, struct sk_buff *skb, __be32 daddr, __be32 saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1765
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81a9a850-ffffffff81a9a8ac: ip_handle_martian_source (STB_LOCAL)
ffffffff81c323f8-ffffffff81c32469: ip_handle_martian_source.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ip_handle_martian_source(struct net_device *dev, struct in_device *in_dev, struct sk_buff *skb, __be32 daddr, __be32 saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1753
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81a85be0-ffffffff81a85c3c: ip_handle_martian_source (STB_LOCAL)
ffffffff81c246e1-ffffffff81c24752: ip_handle_martian_source.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ip_handle_martian_source(struct net_device *dev, struct in_device *in_dev, struct sk_buff *skb, __be32 daddr, __be32 saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1749
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81b403e0-ffffffff81b4043c: ip_handle_martian_source (STB_LOCAL)
ffffffff81d39c32-ffffffff81d39ca3: ip_handle_martian_source.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ip_handle_martian_source(struct net_device *dev, struct in_device *in_dev, struct sk_buff *skb, __be32 daddr, __be32 saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1768
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81cccdf0-ffffffff81ccce60: ip_handle_martian_source (STB_LOCAL)
ffffffff81f06375-ffffffff81f063e6: ip_handle_martian_source.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip_handle_martian_source(struct net_device *dev, struct in_device *in_dev, struct sk_buff *skb, __be32 daddr, __be32 saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e8ce10)
Location: net/ipv4/route.c:1764
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81e8ce10-ffffffff81e8cee4: ip_handle_martian_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip_handle_martian_source(struct net_device *dev, struct in_device *in_dev, struct sk_buff *skb, __be32 daddr, __be32 saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81eeb540)
Location: net/ipv4/route.c:1762
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81eeb540-ffffffff81eeb614: ip_handle_martian_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip_handle_martian_source(struct net_device *dev, struct in_device *in_dev, struct sk_buff *skb, __be32 daddr, __be32 saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81faf540)
Location: net/ipv4/route.c:1764
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81faf540-ffffffff81faf618: ip_handle_martian_source (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffff800010c59190)
Location: net/ipv4/route.c:1757
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffff800010c59190-ffff800010c59270: ip_handle_martian_source.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip_handle_martian_source(struct net_device *dev, struct in_device *in_dev, struct sk_buff *skb, __be32 daddr, __be32 saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d66dec)
Location: net/ipv4/route.c:1757
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
c0d66dec-c0d66edc: ip_handle_martian_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip_handle_martian_source(struct net_device *dev, struct in_device *in_dev, struct sk_buff *skb, __be32 daddr, __be32 saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d58690)
Location: net/ipv4/route.c:1757
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
c000000000d58690-c000000000d587a0: ip_handle_martian_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip_handle_martian_source(struct net_device *dev, struct in_device *in_dev, struct sk_buff *skb, __be32 daddr, __be32 saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c150c)
Location: net/ipv4/route.c:1757
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffe0007c150c-ffffffe0007c15d8: ip_handle_martian_source (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1757
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81948150-ffffffff819481a9: ip_handle_martian_source.isra.0 (STB_LOCAL)
ffffffff8194d1ed-ffffffff8194d25e: ip_handle_martian_source.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1757
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81901c40-ffffffff81901c99: ip_handle_martian_source.isra.0 (STB_LOCAL)
ffffffff81906cdd-ffffffff81906d4e: ip_handle_martian_source.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1757
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff819b2920-ffffffff819b2979: ip_handle_martian_source.isra.0 (STB_LOCAL)
ffffffff819b79bd-ffffffff819b7a2e: ip_handle_martian_source.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1757
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff819bbfe0-ffffffff819bc039: ip_handle_martian_source.isra.0 (STB_LOCAL)
ffffffff819c122d-ffffffff819c129e: ip_handle_martian_source.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
