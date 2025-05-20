# Function: <code>inet_gso_segment</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81794980)
Location: net/ipv4/af_inet.c:1197
Inline: False
```
**Symbols:**

```
ffffffff81794980-ffffffff81794ce6: inet_gso_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81802320)
Location: net/ipv4/af_inet.c:1195
Inline: False
```
**Symbols:**

```
ffffffff81802320-ffffffff818026c1: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818332b0)
Location: net/ipv4/af_inet.c:1201
Inline: False
```
**Symbols:**

```
ffffffff818332b0-ffffffff81833660: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81854610)
Location: net/ipv4/af_inet.c:1219
Inline: False
```
**Symbols:**

```
ffffffff81854610-ffffffff818549c7: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818d44b0)
Location: net/ipv4/af_inet.c:1223
Inline: False
```
**Symbols:**

```
ffffffff818d44b0-ffffffff818d486b: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8192ab90)
Location: net/ipv4/af_inet.c:1291
Inline: False
```
**Symbols:**

```
ffffffff8192ab90-ffffffff8192af44: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8195a320)
Location: net/ipv4/af_inet.c:1291
Inline: False
```
**Symbols:**

```
ffffffff8195a320-ffffffff8195a6b6: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819beea0)
Location: net/ipv4/af_inet.c:1297
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
```
**Symbols:**

```
ffffffff819beea0-ffffffff819bf247: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819f5ae0)
Location: net/ipv4/af_inet.c:1297
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
```
**Symbols:**

```
ffffffff819f5ae0-ffffffff819f5e87: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ae3fd0)
Location: net/ipv4/af_inet.c:1329
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
```
**Symbols:**

```
ffffffff81ae3fd0-ffffffff81ae4377: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81af0f00)
Location: net/ipv4/af_inet.c:1327
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
```
**Symbols:**

```
ffffffff81af0f00-ffffffff81af12a7: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81adc6c0)
Location: net/ipv4/af_inet.c:1331
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
```
**Symbols:**

```
ffffffff81adc6c0-ffffffff81adca67: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81b9baa0)
Location: net/ipv4/af_inet.c:1333
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
```
**Symbols:**

```
ffffffff81b9baa0-ffffffff81b9be59: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81d2d860)
Location: net/ipv4/af_inet.c:1328
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
```
**Symbols:**

```
ffffffff81d2d860-ffffffff81d2dc1e: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ef5760)
Location: net/ipv4/af_inet.c:1348
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
```
**Symbols:**

```
ffffffff81ef5760-ffffffff81ef5b1e: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81f55110)
Location: net/ipv4/af_inet.c:1347
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
```
**Symbols:**

```
ffffffff81f55110-ffffffff81f554c7: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8201b380)
Location: net/ipv4/af_inet.c:1367
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
```
**Symbols:**

```
ffffffff8201b380-ffffffff8201b737: inet_gso_segment (STB_GLOBAL)
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
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffff800010cab778)
Location: net/ipv4/af_inet.c:1297
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
```
**Symbols:**

```
ffff800010cab778-ffff800010cabab8: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c0db8648)
Location: net/ipv4/af_inet.c:1297
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
```
**Symbols:**

```
c0db8648-c0db89a0: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c000000000dc2090)
Location: net/ipv4/af_inet.c:1297
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
```
**Symbols:**

```
c000000000dc2090-c000000000dc25cc: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffe0008063f8)
Location: net/ipv4/af_inet.c:1297
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
```
**Symbols:**

```
ffffffe0008063f8-ffffffe0008066d6: inet_gso_segment (STB_GLOBAL)
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
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81995880)
Location: net/ipv4/af_inet.c:1297
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
```
**Symbols:**

```
ffffffff81995880-ffffffff81995c27: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8194f340)
Location: net/ipv4/af_inet.c:1297
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
```
**Symbols:**

```
ffffffff8194f340-ffffffff8194f6e7: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81a00120)
Location: net/ipv4/af_inet.c:1297
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
```
**Symbols:**

```
ffffffff81a00120-ffffffff81a004c7: inet_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *inet_gso_segment(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81a0a170)
Location: net/ipv4/af_inet.c:1297
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
```
**Symbols:**

```
ffffffff81a0a170-ffffffff81a0a517: inet_gso_segment (STB_GLOBAL)
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
