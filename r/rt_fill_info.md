# Function: <code>rt_fill_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81753b40)
Location: net/ipv4/route.c:2399
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff81753b40-ffffffff81754066: rt_fill_info.constprop.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff817bfc10)
Location: net/ipv4/route.c:2422
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff817bfc10-ffffffff817c011f: rt_fill_info.constprop.41 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff817f2d2f)
Location: net/ipv4/route.c:2457
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
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
In net/ipv4/route.c (ffffffff8181372c)
Location: net/ipv4/route.c:2552
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
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
In net/ipv4/route.c (ffffffff81892d86)
Location: net/ipv4/route.c:2573
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e6e5f)
Location: net/ipv4/route.c:2597
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81913d3b)
Location: net/ipv4/route.c:2599
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int rt_fill_info(struct net *net, __be32 dst, __be32 src, struct rtable *rt, u32 table_id, struct flowi4 *fl4, struct sk_buff *skb, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2729
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
```
**Symbols:**

```
ffffffff81970fc0-ffffffff81971585: rt_fill_info (STB_LOCAL)
ffffffff81976967-ffffffff81976981: rt_fill_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rt_fill_info(struct net *net, __be32 dst, __be32 src, struct rtable *rt, u32 table_id, struct flowi4 *fl4, struct sk_buff *skb, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819a79c0)
Location: net/ipv4/route.c:2738
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
```
**Symbols:**

```
ffffffff819a79c0-ffffffff819a7f97: rt_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rt_fill_info(struct net *net, __be32 dst, __be32 src, struct rtable *rt, u32 table_id, struct flowi4 *fl4, struct sk_buff *skb, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a91130)
Location: net/ipv4/route.c:2825
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fnhe_dump_bucket
```
**Symbols:**

```
ffffffff81a91130-ffffffff81a916f9: rt_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rt_fill_info(struct net *net, __be32 dst, __be32 src, struct rtable *rt, u32 table_id, struct flowi4 *fl4, struct sk_buff *skb, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9af90)
Location: net/ipv4/route.c:2804
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fnhe_dump_bucket
```
**Symbols:**

```
ffffffff81a9af90-ffffffff81a9b57c: rt_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rt_fill_info(struct net *net, __be32 dst, __be32 src, struct rtable *rt, u32 table_id, struct flowi4 *fl4, struct sk_buff *skb, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a863b0)
Location: net/ipv4/route.c:2805
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
```
**Symbols:**

```
ffffffff81a863b0-ffffffff81a8699a: rt_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rt_fill_info(struct net *net, __be32 dst, __be32 src, struct rtable *rt, u32 table_id, struct flowi4 *fl4, struct sk_buff *skb, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b40af0)
Location: net/ipv4/route.c:2923
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
```
**Symbols:**

```
ffffffff81b40af0-ffffffff81b410da: rt_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rt_fill_info(struct net *net, __be32 dst, __be32 src, struct rtable *rt, u32 table_id, struct flowi4 *fl4, struct sk_buff *skb, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81ccd570)
Location: net/ipv4/route.c:2947
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
```
**Symbols:**

```
ffffffff81ccd570-ffffffff81ccdb35: rt_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rt_fill_info(struct net *net, __be32 dst, __be32 src, struct rtable *rt, u32 table_id, struct flowi4 *fl4, struct sk_buff *skb, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e8d6c0)
Location: net/ipv4/route.c:2938
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
```
**Symbols:**

```
ffffffff81e8d6c0-ffffffff81e8dcc0: rt_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rt_fill_info(struct net *net, __be32 dst, __be32 src, struct rtable *rt, u32 table_id, struct flowi4 *fl4, struct sk_buff *skb, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81eebde0)
Location: net/ipv4/route.c:2934
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
```
**Symbols:**

```
ffffffff81eebde0-ffffffff81eec3f8: rt_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rt_fill_info(struct net *net, __be32 dst, __be32 src, struct rtable *rt, u32 table_id, struct flowi4 *fl4, struct sk_buff *skb, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fafe30)
Location: net/ipv4/route.c:2889
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
```
**Symbols:**

```
ffffffff81fafe30-ffffffff81fb0448: rt_fill_info (STB_LOCAL)
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
int rt_fill_info(struct net *net, __be32 dst, __be32 src, struct rtable *rt, u32 table_id, struct flowi4 *fl4, struct sk_buff *skb, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c57280)
Location: net/ipv4/route.c:2738
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
```
**Symbols:**

```
ffff800010c57280-ffff800010c57728: rt_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rt_fill_info(struct net *net, __be32 dst, __be32 src, struct rtable *rt, u32 table_id, struct flowi4 *fl4, struct sk_buff *skb, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d66f00)
Location: net/ipv4/route.c:2738
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
```
**Symbols:**

```
c0d66f00-c0d6745c: rt_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rt_fill_info(struct net *net, __be32 dst, __be32 src, struct rtable *rt, u32 table_id, struct flowi4 *fl4, struct sk_buff *skb, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d587e0)
Location: net/ipv4/route.c:2738
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
```
**Symbols:**

```
c000000000d587e0-c000000000d58e44: rt_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rt_fill_info(struct net *net, __be32 dst, __be32 src, struct rtable *rt, u32 table_id, struct flowi4 *fl4, struct sk_buff *skb, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c15fc)
Location: net/ipv4/route.c:2738
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
```
**Symbols:**

```
ffffffe0007c15fc-ffffffe0007c19dc: rt_fill_info (STB_LOCAL)
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
int rt_fill_info(struct net *net, __be32 dst, __be32 src, struct rtable *rt, u32 table_id, struct flowi4 *fl4, struct sk_buff *skb, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81947830)
Location: net/ipv4/route.c:2738
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
```
**Symbols:**

```
ffffffff81947830-ffffffff81947e07: rt_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rt_fill_info(struct net *net, __be32 dst, __be32 src, struct rtable *rt, u32 table_id, struct flowi4 *fl4, struct sk_buff *skb, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81901320)
Location: net/ipv4/route.c:2738
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
```
**Symbols:**

```
ffffffff81901320-ffffffff819018f7: rt_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rt_fill_info(struct net *net, __be32 dst, __be32 src, struct rtable *rt, u32 table_id, struct flowi4 *fl4, struct sk_buff *skb, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b2000)
Location: net/ipv4/route.c:2738
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
```
**Symbols:**

```
ffffffff819b2000-ffffffff819b25d7: rt_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rt_fill_info(struct net *net, __be32 dst, __be32 src, struct rtable *rt, u32 table_id, struct flowi4 *fl4, struct sk_buff *skb, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819bb6c0)
Location: net/ipv4/route.c:2738
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
```
**Symbols:**

```
ffffffff819bb6c0-ffffffff819bbc97: rt_fill_info (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
