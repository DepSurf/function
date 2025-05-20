# Function: <code>skb_zerocopy_iter_dgram</code>

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
int skb_zerocopy_iter_dgram(struct sk_buff *skb, struct msghdr *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189b2a0)
Location: net/core/skbuff.c:1111
Inline: False
```
**Symbols:**

```
ffffffff8189b2a0-ffffffff8189b2c1: skb_zerocopy_iter_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int skb_zerocopy_iter_dgram(struct sk_buff *skb, struct msghdr *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e5b20)
Location: net/core/skbuff.c:1270
Inline: False
```
**Symbols:**

```
ffffffff818e5b20-ffffffff818e5b41: skb_zerocopy_iter_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int skb_zerocopy_iter_dgram(struct sk_buff *skb, struct msghdr *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81917c70)
Location: net/core/skbuff.c:1270
Inline: False
```
**Symbols:**

```
ffffffff81917c70-ffffffff81917c91: skb_zerocopy_iter_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skb_zerocopy_iter_dgram(struct sk_buff *skb, struct msghdr *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ea0b0)
Location: net/core/skbuff.c:1269
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
**Symbols:**

```
ffffffff819ea0b0-ffffffff819ea0d1: skb_zerocopy_iter_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skb_zerocopy_iter_dgram(struct sk_buff *skb, struct msghdr *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819e9de0)
Location: net/core/skbuff.c:1280
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
**Symbols:**

```
ffffffff819e9de0-ffffffff819e9e01: skb_zerocopy_iter_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skb_zerocopy_iter_dgram(struct sk_buff *skb, struct msghdr *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d0320)
Location: net/core/skbuff.c:1322
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
**Symbols:**

```
ffffffff819d0320-ffffffff819d0341: skb_zerocopy_iter_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skb_zerocopy_iter_dgram(struct sk_buff *skb, struct msghdr *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a7ffa0)
Location: net/core/skbuff.c:1343
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
**Symbols:**

```
ffffffff81a7ffa0-ffffffff81a7ffc1: skb_zerocopy_iter_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81cdae76)
Location: include/linux/skbuff.h:1779
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv6/ip6_output.c (ffffffff81d8909e)
Location: include/linux/skbuff.h:1779
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81e9b68f)
Location: include/linux/skbuff.h:1624
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv6/ip6_output.c (ffffffff81f56ec5)
Location: include/linux/skbuff.h:1624
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81efa227)
Location: include/linux/skbuff.h:1653
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv6/ip6_output.c (ffffffff81fb6a83)
Location: include/linux/skbuff.h:1653
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81fbe155)
Location: include/linux/skbuff.h:1660
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv6/ip6_output.c (ffffffff8208420b)
Location: include/linux/skbuff.h:1660
Inline: True
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
int skb_zerocopy_iter_dgram(struct sk_buff *skb, struct msghdr *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb1328)
Location: net/core/skbuff.c:1270
Inline: False
```
**Symbols:**

```
ffff800010bb1328-ffff800010bb1370: skb_zerocopy_iter_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int skb_zerocopy_iter_dgram(struct sk_buff *skb, struct msghdr *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cce9b4)
Location: net/core/skbuff.c:1270
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
```
**Symbols:**

```
c0cce9b4-c0cce9e4: skb_zerocopy_iter_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int skb_zerocopy_iter_dgram(struct sk_buff *skb, struct msghdr *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c87db0)
Location: net/core/skbuff.c:1270
Inline: False
```
**Symbols:**

```
c000000000c87db0-c000000000c87df8: skb_zerocopy_iter_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int skb_zerocopy_iter_dgram(struct sk_buff *skb, struct msghdr *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000742a22)
Location: net/core/skbuff.c:1270
Inline: False
```
**Symbols:**

```
ffffffe000742a22-ffffffe000742a60: skb_zerocopy_iter_dgram (STB_GLOBAL)
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
int skb_zerocopy_iter_dgram(struct sk_buff *skb, struct msghdr *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b7c70)
Location: net/core/skbuff.c:1270
Inline: False
```
**Symbols:**

```
ffffffff818b7c70-ffffffff818b7c91: skb_zerocopy_iter_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int skb_zerocopy_iter_dgram(struct sk_buff *skb, struct msghdr *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81871bc0)
Location: net/core/skbuff.c:1270
Inline: False
```
**Symbols:**

```
ffffffff81871bc0-ffffffff81871be1: skb_zerocopy_iter_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int skb_zerocopy_iter_dgram(struct sk_buff *skb, struct msghdr *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81908c70)
Location: net/core/skbuff.c:1270
Inline: False
```
**Symbols:**

```
ffffffff81908c70-ffffffff81908c91: skb_zerocopy_iter_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int skb_zerocopy_iter_dgram(struct sk_buff *skb, struct msghdr *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81929d20)
Location: net/core/skbuff.c:1270
Inline: False
```
**Symbols:**

```
ffffffff81929d20-ffffffff81929d41: skb_zerocopy_iter_dgram (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
