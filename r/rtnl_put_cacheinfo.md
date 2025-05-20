# Function: <code>rtnl_put_cacheinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172a150)
Location: net/core/rtnetlink.c:709
Inline: False
```
**Symbols:**

```
ffffffff8172a150-ffffffff8172a24c: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81793b90)
Location: net/core/rtnetlink.c:731
Inline: False
```
**Symbols:**

```
ffffffff81793b90-ffffffff81793c8c: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c1410)
Location: net/core/rtnetlink.c:734
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff817c1410-ffffffff817c150c: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817dfbe0)
Location: net/core/rtnetlink.c:736
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff817dfbe0-ffffffff817dfcdb: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185a4b0)
Location: net/core/rtnetlink.c:709
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff8185a4b0-ffffffff8185a5ab: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a5d30)
Location: net/core/rtnetlink.c:792
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff818a5d30-ffffffff818a5e16: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818c92e0)
Location: net/core/rtnetlink.c:802
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff818c92e0-ffffffff818c93c6: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819162b0)
Location: net/core/rtnetlink.c:801
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff819162b0-ffffffff81916396: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819488e0)
Location: net/core/rtnetlink.c:801
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff819488e0-ffffffff819489c6: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a186d0)
Location: net/core/rtnetlink.c:801
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81a186d0-ffffffff81a187b6: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a18780)
Location: net/core/rtnetlink.c:803
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81a18780-ffffffff81a18866: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819ff650)
Location: net/core/rtnetlink.c:805
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff819ff650-ffffffff819ff72d: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab1920)
Location: net/core/rtnetlink.c:794
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81ab1920-ffffffff81ab19fd: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2ab50)
Location: net/core/rtnetlink.c:831
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81c2ab50-ffffffff81c2ac3c: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ddd900)
Location: net/core/rtnetlink.c:832
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81ddd900-ffffffff81ddd9ec: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e4e650)
Location: net/core/rtnetlink.c:835
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81e4e650-ffffffff81e4e74d: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f0d3b0)
Location: net/core/rtnetlink.c:830
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81f0d3b0-ffffffff81f0d4ad: rtnl_put_cacheinfo (STB_GLOBAL)
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
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bea5e0)
Location: net/core/rtnetlink.c:801
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffff800010bea5e0-ffff800010bea6c8: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d02f08)
Location: net/core/rtnetlink.c:801
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
c0d02f08-c0d03000: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000ccce60)
Location: net/core/rtnetlink.c:801
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
c000000000ccce60-c000000000cccfc0: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076dd8a)
Location: net/core/rtnetlink.c:801
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffe00076dd8a-ffffffe00076de62: rtnl_put_cacheinfo (STB_GLOBAL)
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
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818e88b0)
Location: net/core/rtnetlink.c:801
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff818e88b0-ffffffff818e8996: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a26f0)
Location: net/core/rtnetlink.c:801
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff818a26f0-ffffffff818a27d6: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819398e0)
Location: net/core/rtnetlink.c:801
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff819398e0-ffffffff819399c6: rtnl_put_cacheinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rtnl_put_cacheinfo(struct sk_buff *skb, struct dst_entry *dst, u32 id, long int expires, u32 error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195afc0)
Location: net/core/rtnetlink.c:801
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff8195afc0-ffffffff8195b0a6: rtnl_put_cacheinfo (STB_GLOBAL)
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
