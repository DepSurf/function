# Function: <code>rt6_info_init</code>

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
In net/ipv6/route.c (ffffffff817d3848)
Location: net/ipv6/route.c:317
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
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
In net/ipv6/route.c (ffffffff81845884)
Location: net/ipv6/route.c:318
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:__ip6_dst_alloc
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
In net/ipv6/route.c (ffffffff818775e4)
Location: net/ipv6/route.c:320
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:__ip6_dst_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rt6_info_init(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff818976e0)
Location: net/ipv6/route.c:341
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:__ip6_dst_alloc
```
**Symbols:**

```
ffffffff818976e0-ffffffff81897748: rt6_info_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rt6_info_init(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819189b0)
Location: net/ipv6/route.c:347
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:__ip6_dst_alloc
```
**Symbols:**

```
ffffffff819189b0-ffffffff81918a18: rt6_info_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rt6_info_init(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819706a0)
Location: net/ipv6/route.c:341
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff819706a0-ffffffff819706ed: rt6_info_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rt6_info_init(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a62d0)
Location: net/ipv6/route.c:343
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff819a62d0-ffffffff819a631d: rt6_info_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rt6_info_init(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a128f0)
Location: net/ipv6/route.c:341
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff81a128f0-ffffffff81a1293d: rt6_info_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rt6_info_init(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a494e0)
Location: net/ipv6/route.c:343
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff81a494e0-ffffffff81a4952d: rt6_info_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b48701)
Location: net/ipv6/route.c:343
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b572e1)
Location: net/ipv6/route.c:326
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b44ed1)
Location: net/ipv6/route.c:329
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0c011)
Location: net/ipv6/route.c:329
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rt6_info_init(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9df60)
Location: net/ipv6/route.c:334
Inline: True
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81d9df60-ffffffff81d9dfb9: rt6_info_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rt6_info_init(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6bf40)
Location: net/ipv6/route.c:334
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81f6bf40-ffffffff81f6bf99: rt6_info_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rt6_info_init(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcc080)
Location: net/ipv6/route.c:334
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81fcc080-ffffffff81fcc0c3: rt6_info_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rt6_info_init(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820997c0)
Location: net/ipv6/route.c:334
Inline: False
Direct callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffff820997c0-ffffffff82099803: rt6_info_init (STB_LOCAL)
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
void rt6_info_init(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0c818)
Location: net/ipv6/route.c:343
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffff800010d0c818-ffff800010d0c860: rt6_info_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rt6_info_init(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e12704)
Location: net/ipv6/route.c:343
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
c0e12704-c0e1273c: rt6_info_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rt6_info_init(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e37590)
Location: net/ipv6/route.c:343
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
c000000000e37590-c000000000e375e8: rt6_info_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085a6f2)
Location: net/ipv6/route.c:343
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
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
void rt6_info_init(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819e8b70)
Location: net/ipv6/route.c:343
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff819e8b70-ffffffff819e8bbd: rt6_info_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rt6_info_init(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a5930)
Location: net/ipv6/route.c:343
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff819a5930-ffffffff819a597d: rt6_info_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rt6_info_init(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a535f0)
Location: net/ipv6/route.c:343
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff81a535f0-ffffffff81a5363d: rt6_info_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rt6_info_init(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5f540)
Location: net/ipv6/route.c:343
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff81a5f540-ffffffff81a5f58d: rt6_info_init (STB_LOCAL)
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
