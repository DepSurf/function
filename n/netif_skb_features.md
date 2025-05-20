# Function: <code>netif_skb_features</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171c330)
Location: net/core/dev.c:2675
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/netpoll.c:netpoll_start_xmit
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff8171c330-ffffffff8171c572: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81784c50)
Location: net/core/dev.c:2877
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff81784c50-ffffffff81784ef0: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b2280)
Location: net/core/dev.c:2874
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_output.c:ip_finish_output
```
**Symbols:**

```
ffffffff817b2280-ffffffff817b24f5: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cfaa0)
Location: net/core/dev.c:2941
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_output.c:ip_finish_output
```
**Symbols:**

```
ffffffff817cfaa0-ffffffff817cfcfa: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818493f0)
Location: net/core/dev.c:2968
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_output.c:ip_finish_output
```
**Symbols:**

```
ffffffff818493f0-ffffffff8184964d: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818933b0)
Location: net/core/dev.c:2992
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_output.c:ip_finish_output
```
**Symbols:**

```
ffffffff818933b0-ffffffff81893645: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b3de0)
Location: net/core/dev.c:3236
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_output.c:ip_finish_output
```
**Symbols:**

```
ffffffff818b3de0-ffffffff818b406c: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81900680)
Location: net/core/dev.c:3238
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
```
**Symbols:**

```
ffffffff81900680-ffffffff81900939: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819329b0)
Location: net/core/dev.c:3156
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
```
**Symbols:**

```
ffffffff819329b0-ffffffff81932c69: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a07a20)
Location: net/core/dev.c:3514
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_output.c:ip_finish_output_gso
```
**Symbols:**

```
ffffffff81a07a20-ffffffff81a07c0d: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a09080)
Location: net/core/dev.c:3543
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_output.c:ip_finish_output_gso
```
**Symbols:**

```
ffffffff81a09080-ffffffff81a092d2: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ef990)
Location: net/core/dev.c:3611
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
```
**Symbols:**

```
ffffffff819ef990-ffffffff819efc5d: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa0db0)
Location: net/core/dev.c:3541
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
```
**Symbols:**

```
ffffffff81aa0db0-ffffffff81aa107d: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c18bb0)
Location: net/core/dev.c:3548
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81c18bb0-ffffffff81c18e96: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc9b80)
Location: net/core/dev.c:3535
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81dc9b80-ffffffff81dc9e5c: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3a6f0)
Location: net/core/dev.c:3495
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81e3a6f0-ffffffff81e3a9e4: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef8a80)
Location: net/core/dev.c:3505
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81ef8a80-ffffffff81ef8d92: netif_skb_features (STB_GLOBAL)
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
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd0a00)
Location: net/core/dev.c:3156
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
```
**Symbols:**

```
ffff800010bd0a00-ffff800010bd0c8c: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ceb590)
Location: net/core/dev.c:3156
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
```
**Symbols:**

```
c0ceb590-c0ceb8c8: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cae9b0)
Location: net/core/dev.c:3156
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
```
**Symbols:**

```
c000000000cae9b0-c000000000caece8: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075b0ea)
Location: net/core/dev.c:3156
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
```
**Symbols:**

```
ffffffe00075b0ea-ffffffe00075b304: netif_skb_features (STB_GLOBAL)
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
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d29b0)
Location: net/core/dev.c:3156
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
```
**Symbols:**

```
ffffffff818d29b0-ffffffff818d2c69: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188c840)
Location: net/core/dev.c:3156
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
```
**Symbols:**

```
ffffffff8188c840-ffffffff8188caf9: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819239b0)
Location: net/core/dev.c:3156
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
```
**Symbols:**

```
ffffffff819239b0-ffffffff81923c69: netif_skb_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
netdev_features_t netif_skb_features(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81944e20)
Location: net/core/dev.c:3156
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:netpoll_start_xmit
```
**Symbols:**

```
ffffffff81944e20-ffffffff819450d9: netif_skb_features (STB_GLOBAL)
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
