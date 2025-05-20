# Function: <code>fib_validate_source</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8179aca0)
Location: net/ipv4/fib_frontend.c:409
Inline: False
```
**Symbols:**

```
ffffffff8179aca0-ffffffff8179b1f7: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff818088b0)
Location: net/ipv4/fib_frontend.c:408
Inline: False
```
**Symbols:**

```
ffffffff818088b0-ffffffff81808df2: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81839970)
Location: net/ipv4/fib_frontend.c:400
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff81839970-ffffffff81839ee1: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8185aee0)
Location: net/ipv4/fib_frontend.c:400
Inline: False
```
**Symbols:**

```
ffffffff8185aee0-ffffffff8185b463: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff818dae10)
Location: net/ipv4/fib_frontend.c:407
Inline: False
```
**Symbols:**

```
ffffffff818dae10-ffffffff818db35b: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81931dc0)
Location: net/ipv4/fib_frontend.c:412
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81931dc0-ffffffff81931ebd: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81961620)
Location: net/ipv4/fib_frontend.c:422
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81961620-ffffffff8196171a: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819c5dc0)
Location: net/ipv4/fib_frontend.c:426
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
**Symbols:**

```
ffffffff819c5dc0-ffffffff819c5ebb: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819fc970)
Location: net/ipv4/fib_frontend.c:427
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
**Symbols:**

```
ffffffff819fc970-ffffffff819fca6b: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81aeb6e0)
Location: net/ipv4/fib_frontend.c:419
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mc_validate_source
```
**Symbols:**

```
ffffffff81aeb6e0-ffffffff81aeb7db: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81af85f0)
Location: net/ipv4/fib_frontend.c:419
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mc_validate_source
```
**Symbols:**

```
ffffffff81af85f0-ffffffff81af86eb: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ae3d10)
Location: net/ipv4/fib_frontend.c:421
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mc_validate_source
```
**Symbols:**

```
ffffffff81ae3d10-ffffffff81ae3e0c: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:421
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mc_validate_source
```
**Symbols:**

```
ffffffff81d3c79a-ffffffff81d3c808: fib_validate_source.cold (STB_LOCAL)
ffffffff81ba3630-ffffffff81ba3753: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:421
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mc_validate_source
```
**Symbols:**

```
ffffffff81f08ff9-ffffffff81f09067: fib_validate_source.cold (STB_LOCAL)
ffffffff81d35ea0-ffffffff81d35fd8: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:421
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mc_validate_source
```
**Symbols:**

```
ffffffff820b0952-ffffffff820b09c0: fib_validate_source.cold (STB_LOCAL)
ffffffff81efe4a0-ffffffff81efe5d8: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:421
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mc_validate_source
```
**Symbols:**

```
ffffffff82131bd9-ffffffff82131c47: fib_validate_source.cold (STB_LOCAL)
ffffffff81f5df30-ffffffff81f5e068: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:421
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mc_validate_source
```
**Symbols:**

```
ffffffff82213597-ffffffff82213605: fib_validate_source.cold (STB_LOCAL)
ffffffff820244f0-ffffffff82024628: fib_validate_source (STB_GLOBAL)
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
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffff800010cb4d90)
Location: net/ipv4/fib_frontend.c:427
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
**Symbols:**

```
ffff800010cb4d90-ffff800010cb4ec8: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c0dc0740)
Location: net/ipv4/fib_frontend.c:427
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
**Symbols:**

```
c0dc0740-c0dc0864: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c000000000dcc0b0)
Location: net/ipv4/fib_frontend.c:427
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
**Symbols:**

```
c000000000dcc0b0-c000000000dcc240: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffe00080c8e4)
Location: net/ipv4/fib_frontend.c:427
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
**Symbols:**

```
ffffffe00080c8e4-ffffffe00080c9dc: fib_validate_source (STB_GLOBAL)
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
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8199c710)
Location: net/ipv4/fib_frontend.c:427
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
**Symbols:**

```
ffffffff8199c710-ffffffff8199c80b: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819561d0)
Location: net/ipv4/fib_frontend.c:427
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
**Symbols:**

```
ffffffff819561d0-ffffffff819562cb: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a06fb0)
Location: net/ipv4/fib_frontend.c:427
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
**Symbols:**

```
ffffffff81a06fb0-ffffffff81a070ab: fib_validate_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a11680)
Location: net/ipv4/fib_frontend.c:427
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
**Symbols:**

```
ffffffff81a11680-ffffffff81a1177b: fib_validate_source (STB_GLOBAL)
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
