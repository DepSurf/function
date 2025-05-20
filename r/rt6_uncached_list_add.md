# Function: <code>rt6_uncached_list_add</code>

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
In net/ipv6/route.c (ffffffff817d5ddb)
Location: net/ipv6/route.c:118
Inline: True
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
In net/ipv6/route.c (ffffffff81844332)
Location: net/ipv6/route.c:119
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (ffffffff818760a2)
Location: net/ipv6/route.c:121
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff818974e0)
Location: net/ipv6/route.c:127
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff818974e0-ffffffff81897541: rt6_uncached_list_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81918800)
Location: net/ipv6/route.c:131
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81918800-ffffffff81918861: rt6_uncached_list_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819754c0)
Location: net/ipv6/route.c:135
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff819754c0-ffffffff81975521: rt6_uncached_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ab100)
Location: net/ipv6/route.c:135
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff819ab100-ffffffff819ab161: rt6_uncached_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a18a90)
Location: net/ipv6/route.c:132
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81a18a90-ffffffff81a18af1: rt6_uncached_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4f6f0)
Location: net/ipv6/route.c:133
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81a4f6f0-ffffffff81a4f751: rt6_uncached_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b48c59)
Location: net/ipv6/route.c:133
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
Direct callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81b46e30-ffffffff81b46e91: rt6_uncached_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b5786e)
Location: net/ipv6/route.c:134
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
Direct callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81b55a30-ffffffff81b55a91: rt6_uncached_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4544a)
Location: net/ipv6/route.c:137
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
Direct callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81b43650-ffffffff81b436b1: rt6_uncached_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0c58a)
Location: net/ipv6/route.c:137
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
Direct callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81c0a1b0-ffffffff81c0a211: rt6_uncached_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da749e)
Location: net/ipv6/route.c:138
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
Direct callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81da4e30-ffffffff81da4e9d: rt6_uncached_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f76ace)
Location: net/ipv6/route.c:138
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
Direct callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81f742f0-ffffffff81f7435d: rt6_uncached_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd6b01)
Location: net/ipv6/route.c:138
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
Direct callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81fd43e0-ffffffff81fd4441: rt6_uncached_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a447b)
Location: net/ipv6/route.c:138
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
Direct callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff820a1cf0-ffffffff820a1d51: rt6_uncached_list_add (STB_GLOBAL)
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
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d13560)
Location: net/ipv6/route.c:133
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffff800010d13560-ffff800010d13624: rt6_uncached_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e191b0)
Location: net/ipv6/route.c:133
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
c0e191b0-c0e1920c: rt6_uncached_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3fe40)
Location: net/ipv6/route.c:133
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
c000000000e3fe40-c000000000e3fec8: rt6_uncached_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000859132)
Location: net/ipv6/route.c:133
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffe000859132-ffffffe0008591a2: rt6_uncached_list_add (STB_GLOBAL)
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
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819eed80)
Location: net/ipv6/route.c:133
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff819eed80-ffffffff819eede1: rt6_uncached_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819abb40)
Location: net/ipv6/route.c:133
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff819abb40-ffffffff819abba1: rt6_uncached_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a59800)
Location: net/ipv6/route.c:133
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81a59800-ffffffff81a59861: rt6_uncached_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rt6_uncached_list_add(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a65a40)
Location: net/ipv6/route.c:133
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81a65a40-ffffffff81a65aa1: rt6_uncached_list_add (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
