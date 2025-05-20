# Function: <code>rt6_uncached_list_del</code>

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
In net/ipv6/route.c (ffffffff817d52bf)
Location: net/ipv6/route.c:130
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
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
In net/ipv6/route.c (ffffffff8184342f)
Location: net/ipv6/route.c:131
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
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
In net/ipv6/route.c (ffffffff8187519f)
Location: net/ipv6/route.c:133
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
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
In net/ipv6/route.c (ffffffff8189993f)
Location: net/ipv6/route.c:138
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
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
In net/ipv6/route.c (ffffffff8191cda1)
Location: net/ipv6/route.c:142
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81973cc7)
Location: net/ipv6/route.c:146
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81971b00-ffffffff81971b77: rt6_uncached_list_del.part.80 (STB_LOCAL)
ffffffff81975530-ffffffff81975554: rt6_uncached_list_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff819a98da)
Location: net/ipv6/route.c:146
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff819a7250-ffffffff819a72c7: rt6_uncached_list_del.part.80 (STB_LOCAL)
ffffffff819ab170-ffffffff819ab194: rt6_uncached_list_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81a15e3a)
Location: net/ipv6/route.c:143
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81a13880-ffffffff81a138f5: rt6_uncached_list_del.part.0 (STB_LOCAL)
ffffffff81a18b00-ffffffff81a18b24: rt6_uncached_list_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4ca7a)
Location: net/ipv6/route.c:144
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81a4a470-ffffffff81a4a4e5: rt6_uncached_list_del.part.0 (STB_LOCAL)
ffffffff81a4f760-ffffffff81a4f784: rt6_uncached_list_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b42f89)
Location: net/ipv6/route.c:144
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81b40e50-ffffffff81b40ec5: rt6_uncached_list_del.part.0 (STB_LOCAL)
ffffffff81b46ea0-ffffffff81b46ec4: rt6_uncached_list_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b52529)
Location: net/ipv6/route.c:145
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81b4f910-ffffffff81b4f985: rt6_uncached_list_del.part.0 (STB_LOCAL)
ffffffff81b55aa0-ffffffff81b55ac4: rt6_uncached_list_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3fec9)
Location: net/ipv6/route.c:148
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81b3d640-ffffffff81b3d6b5: rt6_uncached_list_del.part.0 (STB_LOCAL)
ffffffff81b436c0-ffffffff81b436e4: rt6_uncached_list_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81c064b9)
Location: net/ipv6/route.c:148
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81c03e80-ffffffff81c03ef5: rt6_uncached_list_del.part.0 (STB_LOCAL)
ffffffff81c0a220-ffffffff81c0a244: rt6_uncached_list_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da0ef1)
Location: net/ipv6/route.c:149
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81da4ea0-ffffffff81da4f0f: rt6_uncached_list_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f701f1)
Location: net/ipv6/route.c:149
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81f74370-ffffffff81f743df: rt6_uncached_list_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd0311)
Location: net/ipv6/route.c:149
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81fd4460-ffffffff81fd44ba: rt6_uncached_list_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209d8a1)
Location: net/ipv6/route.c:149
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff820a1d70-ffffffff820a1dca: rt6_uncached_list_del (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffff800010d0f660)
Location: net/ipv6/route.c:144
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffff800010d0f530-ffff800010d0f620: rt6_uncached_list_del.part.0 (STB_LOCAL)
ffff800010d13628-ffff800010d13664: rt6_uncached_list_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (c0e15e74)
Location: net/ipv6/route.c:144
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
c0e13d68-c0e13ddc: rt6_uncached_list_del.part.0 (STB_LOCAL)
c0e1920c-c0e19238: rt6_uncached_list_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (c000000000e3bb54)
Location: net/ipv6/route.c:144
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
c000000000e39170-c000000000e3922c: rt6_uncached_list_del.part.0 (STB_LOCAL)
c000000000e3fed0-c000000000e3fef4: rt6_uncached_list_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffe000855316)
Location: net/ipv6/route.c:144
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffe000855278-ffffffe0008552de: rt6_uncached_list_del.part.0 (STB_LOCAL)
ffffffe0008591a2-ffffffe0008591d6: rt6_uncached_list_del (STB_GLOBAL)
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
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff819ec10a)
Location: net/ipv6/route.c:144
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff819e9b00-ffffffff819e9b75: rt6_uncached_list_del.part.0 (STB_LOCAL)
ffffffff819eedf0-ffffffff819eee14: rt6_uncached_list_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff819a8eca)
Location: net/ipv6/route.c:144
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff819a68c0-ffffffff819a6935: rt6_uncached_list_del.part.0 (STB_LOCAL)
ffffffff819abbb0-ffffffff819abbd4: rt6_uncached_list_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81a56b8a)
Location: net/ipv6/route.c:144
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81a54580-ffffffff81a545f5: rt6_uncached_list_del.part.0 (STB_LOCAL)
ffffffff81a59870-ffffffff81a59894: rt6_uncached_list_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_uncached_list_del(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81a62c3a)
Location: net/ipv6/route.c:144
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
Direct callers:
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81a60570-ffffffff81a605e5: rt6_uncached_list_del.part.0 (STB_LOCAL)
ffffffff81a65ab0-ffffffff81a65ad4: rt6_uncached_list_del (STB_GLOBAL)
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
