# Function: <code>rt_add_uncached_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81752f80)
Location: net/ipv4/route.c:1344
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_set_nexthop
```
**Symbols:**

```
ffffffff81752f80-ffffffff81752fe1: rt_add_uncached_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817bf100)
Location: net/ipv4/route.c:1350
Inline: False
```
**Symbols:**

```
ffffffff817bf100-ffffffff817bf161: rt_add_uncached_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817ee9f0)
Location: net/ipv4/route.c:1360
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff817ee9f0-ffffffff817eea51: rt_add_uncached_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8180eb30)
Location: net/ipv4/route.c:1385
Inline: False
```
**Symbols:**

```
ffffffff8180eb30-ffffffff8180eb91: rt_add_uncached_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8188e0f0)
Location: net/ipv4/route.c:1392
Inline: False
```
**Symbols:**

```
ffffffff8188e0f0-ffffffff8188e151: rt_add_uncached_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e4200)
Location: net/ipv4/route.c:1460
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
ffffffff818e4200-ffffffff818e4261: rt_add_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81911110)
Location: net/ipv4/route.c:1463
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
ffffffff81911110-ffffffff81911171: rt_add_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819737a0)
Location: net/ipv4/route.c:1503
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
ffffffff819737a0-ffffffff81973801: rt_add_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819aa120)
Location: net/ipv4/route.c:1505
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
ffffffff819aa120-ffffffff819aa181: rt_add_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9568c)
Location: net/ipv4/route.c:1509
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
ffffffff81a94810-ffffffff81a94871: rt_add_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9f71c)
Location: net/ipv4/route.c:1515
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
ffffffff81a9e810-ffffffff81a9e871: rt_add_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a8a653)
Location: net/ipv4/route.c:1503
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
ffffffff81a89770-ffffffff81a897d1: rt_add_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b454ff)
Location: net/ipv4/route.c:1499
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
ffffffff81b442c0-ffffffff81b44321: rt_add_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81cd2221)
Location: net/ipv4/route.c:1507
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
ffffffff81cd0e70-ffffffff81cd0edd: rt_add_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e9274b)
Location: net/ipv4/route.c:1507
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
ffffffff81e910c0-ffffffff81e9112d: rt_add_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81ef0eec)
Location: net/ipv4/route.c:1507
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
ffffffff81eef870-ffffffff81eef8d1: rt_add_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb503f)
Location: net/ipv4/route.c:1509
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
ffffffff81fb39c0-ffffffff81fb3a21: rt_add_uncached_list (STB_GLOBAL)
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
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c5a260)
Location: net/ipv4/route.c:1505
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
ffff800010c5a260-ffff800010c5a324: rt_add_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d698dc)
Location: net/ipv4/route.c:1505
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
c0d698dc-c0d69938: rt_add_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5bd80)
Location: net/ipv4/route.c:1505
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
c000000000d5bd80-c000000000d5be08: rt_add_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c386a)
Location: net/ipv4/route.c:1505
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
ffffffe0007c386a-ffffffe0007c38da: rt_add_uncached_list (STB_GLOBAL)
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
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81949f90)
Location: net/ipv4/route.c:1505
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
ffffffff81949f90-ffffffff81949ff1: rt_add_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81903a80)
Location: net/ipv4/route.c:1505
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
ffffffff81903a80-ffffffff81903ae1: rt_add_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b4760)
Location: net/ipv4/route.c:1505
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
ffffffff819b4760-ffffffff819b47c1: rt_add_uncached_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rt_add_uncached_list(struct rtable *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819bdea0)
Location: net/ipv4/route.c:1505
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
**Symbols:**

```
ffffffff819bdea0-ffffffff819bdf01: rt_add_uncached_list (STB_GLOBAL)
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
