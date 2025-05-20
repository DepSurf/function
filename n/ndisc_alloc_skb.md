# Function: <code>ndisc_alloc_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff817de800)
Location: net/ipv6/ndisc.c:380
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
**Symbols:**

```
ffffffff817de800-ffffffff817de8d0: ndisc_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff8184c720)
Location: net/ipv6/ndisc.c:394
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff8184c720-ffffffff8184c7f0: ndisc_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff8187e5f0)
Location: net/ipv6/ndisc.c:394
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff8187e5f0-ffffffff8187e6c0: ndisc_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff818a4630)
Location: net/ipv6/ndisc.c:394
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff818a4630-ffffffff818a4700: ndisc_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81926fe0)
Location: net/ipv6/ndisc.c:395
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff81926fe0-ffffffff819270b0: ndisc_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:395
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff8197f3b0-ffffffff8197f471: ndisc_alloc_skb (STB_LOCAL)
ffffffff81982947-ffffffff8198295f: ndisc_alloc_skb.cold.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff819b5a32)
Location: net/ipv6/ndisc.c:395
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff819b5980-ffffffff819b5a41: ndisc_alloc_skb (STB_LOCAL)
ffffffff819b8fe7-ffffffff819b8fff: ndisc_alloc_skb.cold.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81a24515)
Location: net/ipv6/ndisc.c:408
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff81a24460-ffffffff81a24524: ndisc_alloc_skb (STB_LOCAL)
ffffffff81a27a68-ffffffff81a27a80: ndisc_alloc_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81a5af95)
Location: net/ipv6/ndisc.c:409
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff81a5aee0-ffffffff81a5afa4: ndisc_alloc_skb (STB_LOCAL)
ffffffff81a5e4c8-ffffffff81a5e4e0: ndisc_alloc_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:410
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff81b53860-ffffffff81b53924: ndisc_alloc_skb (STB_LOCAL)
ffffffff81b572b4-ffffffff81b572cc: ndisc_alloc_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:412
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff81b61df0-ffffffff81b61eb4: ndisc_alloc_skb (STB_LOCAL)
ffffffff81c32df8-ffffffff81c32e10: ndisc_alloc_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:412
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff81b50060-ffffffff81b50124: ndisc_alloc_skb (STB_LOCAL)
ffffffff81c250f9-ffffffff81c25111: ndisc_alloc_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:412
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff81c173c0-ffffffff81c17484: ndisc_alloc_skb (STB_LOCAL)
ffffffff81d40490-ffffffff81d404a8: ndisc_alloc_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:412
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff81db3220-ffffffff81db32ed: ndisc_alloc_skb (STB_LOCAL)
ffffffff81f0ce13-ffffffff81f0ce2b: ndisc_alloc_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81f82820)
Location: net/ipv6/ndisc.c:413
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff81f82820-ffffffff81f828fc: ndisc_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81fe2b30)
Location: net/ipv6/ndisc.c:414
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff81fe2b30-ffffffff81fe2c0c: ndisc_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff820b0a50)
Location: net/ipv6/ndisc.c:414
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff820b0a50-ffffffff820b0b29: ndisc_alloc_skb (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffff800010d202b0)
Location: net/ipv6/ndisc.c:409
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffff800010d202b0-ffff800010d20384: ndisc_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (c0e24e8c)
Location: net/ipv6/ndisc.c:409
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
c0e24e8c-c0e24f60: ndisc_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (c000000000e4eab0)
Location: net/ipv6/ndisc.c:409
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
c000000000e4eab0-c000000000e4ebcc: ndisc_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffe0008625dc)
Location: net/ipv6/ndisc.c:409
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffe0008625dc-ffffffe0008626aa: ndisc_alloc_skb (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff819fa625)
Location: net/ipv6/ndisc.c:409
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff819fa570-ffffffff819fa634: ndisc_alloc_skb (STB_LOCAL)
ffffffff819fdb58-ffffffff819fdb70: ndisc_alloc_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff819b73e5)
Location: net/ipv6/ndisc.c:409
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff819b7330-ffffffff819b73f4: ndisc_alloc_skb (STB_LOCAL)
ffffffff819ba918-ffffffff819ba930: ndisc_alloc_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81a650a5)
Location: net/ipv6/ndisc.c:409
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff81a64ff0-ffffffff81a650b4: ndisc_alloc_skb (STB_LOCAL)
ffffffff81a685d8-ffffffff81a685f0: ndisc_alloc_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct sk_buff *ndisc_alloc_skb(struct net_device *dev, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81a715d5)
Location: net/ipv6/ndisc.c:409
Inline: True
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
```
**Symbols:**

```
ffffffff81a71520-ffffffff81a715e4: ndisc_alloc_skb (STB_LOCAL)
ffffffff81a74bc8-ffffffff81a74be0: ndisc_alloc_skb.cold (STB_LOCAL)
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
