# Function: <code>rt_del_uncached_list</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e29dc)
Location: net/ipv4/route.c:1471
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
ffffffff818e4590-ffffffff818e4602: rt_del_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8190f87c)
Location: net/ipv4/route.c:1474
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
ffffffff819114c0-ffffffff81911532: rt_del_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81971a9c)
Location: net/ipv4/route.c:1514
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
ffffffff81973b20-ffffffff81973b90: rt_del_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819a849c)
Location: net/ipv4/route.c:1516
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
ffffffff819aa540-ffffffff819aa5b0: rt_del_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a91847)
Location: net/ipv4/route.c:1520
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
ffffffff81a94880-ffffffff81a948f0: rt_del_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9b6c7)
Location: net/ipv4/route.c:1526
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
ffffffff81a9e880-ffffffff81a9e8f0: rt_del_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a869d7)
Location: net/ipv4/route.c:1514
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
ffffffff81a897e0-ffffffff81a89850: rt_del_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b41117)
Location: net/ipv4/route.c:1510
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
ffffffff81b44330-ffffffff81b443a0: rt_del_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81cce409)
Location: net/ipv4/route.c:1518
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
ffffffff81cd0ee0-ffffffff81cd0f4f: rt_del_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e8e619)
Location: net/ipv4/route.c:1518
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
ffffffff81e91140-ffffffff81e911af: rt_del_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81eecd39)
Location: net/ipv4/route.c:1518
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
ffffffff81eef8f0-ffffffff81eef94a: rt_del_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb0dc9)
Location: net/ipv4/route.c:1520
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
ffffffff81fb3a40-ffffffff81fb3a9a: rt_del_uncached_list (STB_GLOBAL)
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
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffff800010c58728)
Location: net/ipv4/route.c:1516
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
ffff800010c58628-ffff800010c586e4: rt_del_uncached_list.part.0 (STB_LOCAL)
ffff800010c5a810-ffff800010c5a84c: rt_del_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d6794c)
Location: net/ipv4/route.c:1516
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
c0d69d80-c0d69ddc: rt_del_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d595bc)
Location: net/ipv4/route.c:1516
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
c000000000d5c3a0-c000000000d5c444: rt_del_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c1f32)
Location: net/ipv4/route.c:1516
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
ffffffe0007c3c7c-ffffffe0007c3cd6: rt_del_uncached_list (STB_GLOBAL)
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
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8194830c)
Location: net/ipv4/route.c:1516
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
ffffffff8194a3b0-ffffffff8194a420: rt_del_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81901dfc)
Location: net/ipv4/route.c:1516
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
ffffffff81903ea0-ffffffff81903f10: rt_del_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b2adc)
Location: net/ipv4/route.c:1516
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
ffffffff819b4b80-ffffffff819b4bf0: rt_del_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rt_del_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819bc19c)
Location: net/ipv4/route.c:1516
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:ipv4_dst_destroy
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
**Symbols:**

```
ffffffff819be2c0-ffffffff819be330: rt_del_uncached_list (STB_GLOBAL)
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
