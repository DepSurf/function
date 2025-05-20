# Function: <code>rtnetlink_put_metrics</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172cfb0)
Location: net/core/rtnetlink.c:663
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
**Symbols:**

```
ffffffff8172cfb0-ffffffff8172d198: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817960f0)
Location: net/core/rtnetlink.c:685
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
**Symbols:**

```
ffffffff817960f0-ffffffff817962db: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c39f0)
Location: net/core/rtnetlink.c:686
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/fib_semantics.c:fib_dump_info
```
**Symbols:**

```
ffffffff817c39f0-ffffffff817c3be3: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e22d0)
Location: net/core/rtnetlink.c:688
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff817e22d0-ffffffff817e24a5: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185d190)
Location: net/core/rtnetlink.c:661
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff8185d190-ffffffff8185d365: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a8d40)
Location: net/core/rtnetlink.c:744
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff818a8d40-ffffffff818a8ef4: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818cbdb0)
Location: net/core/rtnetlink.c:754
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff818cbdb0-ffffffff818cbf61: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81918bbe)
Location: net/core/rtnetlink.c:749
Inline: True
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff8191e74d-ffffffff8191e781: rtnetlink_put_metrics.cold (STB_LOCAL)
ffffffff81918b80-ffffffff81918d55: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8194b0e0)
Location: net/core/rtnetlink.c:749
Inline: True
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff8194b0e0-ffffffff8194b2bc: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1d980)
Location: net/core/rtnetlink.c:749
Inline: True
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81a1d980-ffffffff81a1db29: rtnetlink_put_metrics.part.0 (STB_LOCAL)
ffffffff81a1db30-ffffffff81a1db4c: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1c4e0)
Location: net/core/rtnetlink.c:751
Inline: True
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81a1c4e0-ffffffff81a1c689: rtnetlink_put_metrics.part.0 (STB_LOCAL)
ffffffff81a1c690-ffffffff81a1c6ac: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a04c80)
Location: net/core/rtnetlink.c:753
Inline: True
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81a04c80-ffffffff81a04e46: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab5870)
Location: net/core/rtnetlink.c:742
Inline: True
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81ab5870-ffffffff81ab5a36: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2f350)
Location: net/core/rtnetlink.c:779
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81c2f350-ffffffff81c2f551: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de2630)
Location: net/core/rtnetlink.c:780
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81de2630-ffffffff81de2831: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e55590)
Location: net/core/rtnetlink.c:783
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81e55590-ffffffff81e55791: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f14940)
Location: net/core/rtnetlink.c:778
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81f14940-ffffffff81f14b41: rtnetlink_put_metrics (STB_GLOBAL)
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
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bee080)
Location: net/core/rtnetlink.c:749
Inline: True
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffff800010bee080-ffff800010bee280: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d06598)
Location: net/core/rtnetlink.c:749
Inline: True
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
c0d06598-c0d06794: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cd1a10)
Location: net/core/rtnetlink.c:749
Inline: True
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
c000000000cd1a10-c000000000cd1d14: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe000770a4e)
Location: net/core/rtnetlink.c:749
Inline: True
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffe000770a4e-ffffffe000770bc6: rtnetlink_put_metrics (STB_GLOBAL)
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
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818eb0b0)
Location: net/core/rtnetlink.c:749
Inline: True
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff818eb0b0-ffffffff818eb28c: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a4ef0)
Location: net/core/rtnetlink.c:749
Inline: True
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff818a4ef0-ffffffff818a50cc: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8193c0e0)
Location: net/core/rtnetlink.c:749
Inline: True
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff8193c0e0-ffffffff8193c2bc: rtnetlink_put_metrics (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int rtnetlink_put_metrics(struct sk_buff *skb, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195d950)
Location: net/core/rtnetlink.c:749
Inline: True
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff8195d950-ffffffff8195db2c: rtnetlink_put_metrics (STB_GLOBAL)
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
