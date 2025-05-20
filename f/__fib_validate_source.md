# Function: <code>__fib_validate_source</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8179ad0a)
Location: net/ipv4/fib_frontend.c:324
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81808917)
Location: net/ipv4/fib_frontend.c:323
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff818399df)
Location: net/ipv4/fib_frontend.c:315
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8185af49)
Location: net/ipv4/fib_frontend.c:315
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff818daed6)
Location: net/ipv4/fib_frontend.c:325
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81931170)
Location: net/ipv4/fib_frontend.c:326
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
ffffffff81931170-ffffffff81931633: __fib_validate_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81960a60)
Location: net/ipv4/fib_frontend.c:352
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
ffffffff81960a60-ffffffff81960e9d: __fib_validate_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819c5540)
Location: net/ipv4/fib_frontend.c:351
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
ffffffff819c5540-ffffffff819c5993: __fib_validate_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819fc0e0)
Location: net/ipv4/fib_frontend.c:352
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
ffffffff819fc0e0-ffffffff819fc533: __fib_validate_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81aea2d0)
Location: net/ipv4/fib_frontend.c:343
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
ffffffff81aea2d0-ffffffff81aea733: __fib_validate_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81af7130)
Location: net/ipv4/fib_frontend.c:343
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
ffffffff81af7130-ffffffff81af75c5: __fib_validate_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ae2870)
Location: net/ipv4/fib_frontend.c:343
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
ffffffff81ae2870-ffffffff81ae2cf7: __fib_validate_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:343
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
ffffffff81ba2100-ffffffff81ba25a1: __fib_validate_source (STB_LOCAL)
ffffffff81d3c70a-ffffffff81d3c733: __fib_validate_source.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:344
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
ffffffff81d347f0-ffffffff81d34c78: __fib_validate_source (STB_LOCAL)
ffffffff81f08f4f-ffffffff81f08f85: __fib_validate_source.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:344
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
ffffffff81efccf0-ffffffff81efd176: __fib_validate_source (STB_LOCAL)
ffffffff820b08a8-ffffffff820b08de: __fib_validate_source.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:344
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
ffffffff81f5c730-ffffffff81f5cbb6: __fib_validate_source (STB_LOCAL)
ffffffff82131b2f-ffffffff82131b65: __fib_validate_source.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:344
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
ffffffff82022cb0-ffffffff82023135: __fib_validate_source (STB_LOCAL)
ffffffff822134ed-ffffffff82213523: __fib_validate_source.cold (STB_LOCAL)
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
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffff800010cb4530)
Location: net/ipv4/fib_frontend.c:352
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
ffff800010cb4530-ffff800010cb48e8: __fib_validate_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c0dbfa0c)
Location: net/ipv4/fib_frontend.c:352
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
c0dbfa0c-c0dbfdcc: __fib_validate_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c000000000dcb500)
Location: net/ipv4/fib_frontend.c:352
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
c000000000dcb500-c000000000dcb9d8: __fib_validate_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffe00080c22e)
Location: net/ipv4/fib_frontend.c:352
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
ffffffe00080c22e-ffffffe00080c534: __fib_validate_source (STB_LOCAL)
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
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8199be80)
Location: net/ipv4/fib_frontend.c:352
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
ffffffff8199be80-ffffffff8199c2d3: __fib_validate_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81955940)
Location: net/ipv4/fib_frontend.c:352
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
ffffffff81955940-ffffffff81955d93: __fib_validate_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a06720)
Location: net/ipv4/fib_frontend.c:352
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
ffffffff81a06720-ffffffff81a06b73: __fib_validate_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __fib_validate_source(struct sk_buff *skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device *dev, int rpf, struct in_device *idev, u32 *itag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a10da0)
Location: net/ipv4/fib_frontend.c:352
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
**Symbols:**

```
ffffffff81a10da0-ffffffff81a1122f: __fib_validate_source (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
