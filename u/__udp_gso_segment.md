# Function: <code>__udp_gso_segment</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81920ce0)
Location: net/ipv4/udp_offload.c:190
Inline: False
```
**Symbols:**

```
ffffffff81920ce0-ffffffff81921063: __udp_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8194f850)
Location: net/ipv4/udp_offload.c:191
Inline: False
```
**Symbols:**

```
ffffffff8194f850-ffffffff8194fbcd: __udp_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff819b4090)
Location: net/ipv4/udp_offload.c:187
Inline: False
```
**Symbols:**

```
ffffffff819b4090-ffffffff819b4449: __udp_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff819eadc0)
Location: net/ipv4/udp_offload.c:187
Inline: False
```
**Symbols:**

```
ffffffff819eadc0-ffffffff819eb179: __udp_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ad8a20)
Location: net/ipv4/udp_offload.c:201
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff81ad8a20-ffffffff81ad8e8e: __udp_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features, bool is_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ae4f40)
Location: net/ipv4/udp_offload.c:263
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff81ae4f40-ffffffff81ae53c1: __udp_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features, bool is_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ad0160)
Location: net/ipv4/udp_offload.c:263
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff81ad0160-ffffffff81ad06af: __udp_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features, bool is_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81b8eb80)
Location: net/ipv4/udp_offload.c:263
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff81b8eb80-ffffffff81b8f0cd: __udp_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features, bool is_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81d1f820)
Location: net/ipv4/udp_offload.c:264
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff81d1f820-ffffffff81d1fd79: __udp_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features, bool is_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ee6a10)
Location: net/ipv4/udp_offload.c:264
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff81ee6a10-ffffffff81ee6f69: __udp_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features, bool is_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81f46250)
Location: net/ipv4/udp_offload.c:265
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff81f46250-ffffffff81f4680c: __udp_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features, bool is_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8200c390)
Location: net/ipv4/udp_offload.c:265
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff8200c390-ffffffff8200c94c: __udp_gso_segment (STB_GLOBAL)
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
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffff800010ca0978)
Location: net/ipv4/udp_offload.c:187
Inline: False
```
**Symbols:**

```
ffff800010ca0978-ffff800010ca0cf4: __udp_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (c0dadb4c)
Location: net/ipv4/udp_offload.c:187
Inline: False
```
**Symbols:**

```
c0dadb4c-c0dadeb4: __udp_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (c000000000db3280)
Location: net/ipv4/udp_offload.c:187
Inline: False
```
**Symbols:**

```
c000000000db3280-c000000000db36f8: __udp_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffe0007fd034)
Location: net/ipv4/udp_offload.c:187
Inline: False
```
**Symbols:**

```
ffffffe0007fd034-ffffffe0007fd35a: __udp_gso_segment (STB_GLOBAL)
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
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8198ac30)
Location: net/ipv4/udp_offload.c:187
Inline: False
```
**Symbols:**

```
ffffffff8198ac30-ffffffff8198afe9: __udp_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff819446f0)
Location: net/ipv4/udp_offload.c:187
Inline: False
```
**Symbols:**

```
ffffffff819446f0-ffffffff81944aa9: __udp_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff819f5400)
Location: net/ipv4/udp_offload.c:187
Inline: False
```
**Symbols:**

```
ffffffff819f5400-ffffffff819f57b9: __udp_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *__udp_gso_segment(struct sk_buff *gso_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff819ff600)
Location: net/ipv4/udp_offload.c:187
Inline: False
```
**Symbols:**

```
ffffffff819ff600-ffffffff819ff9b9: __udp_gso_segment (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool is_ipv6</code>
</li>
</ul>
</details>
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
