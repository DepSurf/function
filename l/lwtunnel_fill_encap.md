# Function: <code>lwtunnel_fill_encap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff8173e250)
Location: net/core/lwtunnel.c:96
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
**Symbols:**

```
ffffffff8173e250-ffffffff8173e3c7: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff817aabc0)
Location: net/core/lwtunnel.c:133
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
**Symbols:**

```
ffffffff817aabc0-ffffffff817aad3c: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff817d9960)
Location: net/core/lwtunnel.c:204
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
**Symbols:**

```
ffffffff817d9960-ffffffff817d9adc: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff817f8bc0)
Location: net/core/lwtunnel.c:224
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_nexthop_info
```
**Symbols:**

```
ffffffff817f8bc0-ffffffff817f8d1d: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818764a0)
Location: net/core/lwtunnel.c:226
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_nexthop_info
```
**Symbols:**

```
ffffffff818764a0-ffffffff81876600: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818c7bb0)
Location: net/core/lwtunnel.c:226
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_nexthop_info
```
**Symbols:**

```
ffffffff818c7bb0-ffffffff818c7d15: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818f0d10)
Location: net/core/lwtunnel.c:226
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_nexthop_info
```
**Symbols:**

```
ffffffff818f0d10-ffffffff818f0e75: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate, int encap_attr, int encap_type_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/lwtunnel.c (ffffffff8194271d)
Location: net/core/lwtunnel.c:221
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
```
**Symbols:**

```
ffffffff8194284f-ffffffff81942870: lwtunnel_fill_encap.cold (STB_LOCAL)
ffffffff819426b0-ffffffff81942817: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate, int encap_attr, int encap_type_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff819775e0)
Location: net/core/lwtunnel.c:221
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
```
**Symbols:**

```
ffffffff819775e0-ffffffff81977742: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate, int encap_attr, int encap_type_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81a4c3d0)
Location: net/core/lwtunnel.c:223
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
```
**Symbols:**

```
ffffffff81a4c3d0-ffffffff81a4c51e: lwtunnel_fill_encap.part.0 (STB_LOCAL)
ffffffff81a4c520-ffffffff81a4c54f: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate, int encap_attr, int encap_type_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81a52050)
Location: net/core/lwtunnel.c:223
Inline: True
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81a52050-ffffffff81a5219a: lwtunnel_fill_encap.part.0 (STB_LOCAL)
ffffffff81a521a0-ffffffff81a521cf: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate, int encap_attr, int encap_type_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81a37950)
Location: net/core/lwtunnel.c:223
Inline: True
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81a37950-ffffffff81a37aba: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate, int encap_attr, int encap_type_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81aed770)
Location: net/core/lwtunnel.c:232
Inline: True
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81aed770-ffffffff81aed902: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate, int encap_attr, int encap_type_attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81c700a0)
Location: net/core/lwtunnel.c:232
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81c700a0-ffffffff81c7024e: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate, int encap_attr, int encap_type_attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81e28010)
Location: net/core/lwtunnel.c:235
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81e28010-ffffffff81e281be: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate, int encap_attr, int encap_type_attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81e9d620)
Location: net/core/lwtunnel.c:235
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81e9d620-ffffffff81e9d7d5: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate, int encap_attr, int encap_type_attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81f5fda0)
Location: net/core/lwtunnel.c:235
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81f5fda0-ffffffff81f5ff55: lwtunnel_fill_encap (STB_GLOBAL)
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
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate, int encap_attr, int encap_type_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffff800010c1e0f8)
Location: net/core/lwtunnel.c:221
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
```
**Symbols:**

```
ffff800010c1e0f8-ffff800010c1e28c: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate, int encap_attr, int encap_type_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (c0d35c6c)
Location: net/core/lwtunnel.c:221
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
```
**Symbols:**

```
c0d35c6c-c0d35de4: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate, int encap_attr, int encap_type_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (c000000000d0f830)
Location: net/core/lwtunnel.c:221
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
```
**Symbols:**

```
c000000000d0f830-c000000000d0fa3c: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate, int encap_attr, int encap_type_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffe000797b20)
Location: net/core/lwtunnel.c:221
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
```
**Symbols:**

```
ffffffe000797b20-ffffffe000797c2a: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate, int encap_attr, int encap_type_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81917450)
Location: net/core/lwtunnel.c:221
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
```
**Symbols:**

```
ffffffff81917450-ffffffff819175b2: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate, int encap_attr, int encap_type_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818d1200)
Location: net/core/lwtunnel.c:221
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
```
**Symbols:**

```
ffffffff818d1200-ffffffff818d1362: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate, int encap_attr, int encap_type_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff819685e0)
Location: net/core/lwtunnel.c:221
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
```
**Symbols:**

```
ffffffff819685e0-ffffffff81968742: lwtunnel_fill_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_fill_encap(struct sk_buff *skb, struct lwtunnel_state *lwtstate, int encap_attr, int encap_type_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff8198a980)
Location: net/core/lwtunnel.c:221
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
```
**Symbols:**

```
ffffffff8198a980-ffffffff8198aaff: lwtunnel_fill_encap (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int encap_attr</code>
</li>
<li>
<b>Param added. </b>
<code>int encap_type_attr</code>
</li>
</ul>
</details>
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
