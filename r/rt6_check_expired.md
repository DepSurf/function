# Function: <code>rt6_check_expired</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d46a0)
Location: net/ipv6/route.c:415
Inline: True
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_negative_advice
```
**Symbols:**

```
ffffffff817d46a0-ffffffff817d46d8: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81841da0)
Location: net/ipv6/route.c:417
Inline: True
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_negative_advice
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_dst_check
```
**Symbols:**

```
ffffffff81841da0-ffffffff81841dd8: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81873c20)
Location: net/ipv6/route.c:419
Inline: True
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_negative_advice
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_dst_check
```
**Symbols:**

```
ffffffff81873c20-ffffffff81873c58: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff818988b0)
Location: net/ipv6/route.c:437
Inline: True
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
```
**Symbols:**

```
ffffffff818988b0-ffffffff818988f8: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81919c50)
Location: net/ipv6/route.c:441
Inline: True
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff81919c50-ffffffff81919c98: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81971750)
Location: net/ipv6/route.c:412
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff81971750-ffffffff819717a9: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a7080)
Location: net/ipv6/route.c:414
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff819a7080-ffffffff819a70d9: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a13680)
Location: net/ipv6/route.c:409
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_dst_check
```
**Symbols:**

```
ffffffff81a13680-ffffffff81a136d9: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4a270)
Location: net/ipv6/route.c:411
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_dst_check
```
**Symbols:**

```
ffffffff81a4a270-ffffffff81a4a2c9: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b41ce0)
Location: net/ipv6/route.c:411
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff81b41ce0-ffffffff81b41d39: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b507c0)
Location: net/ipv6/route.c:394
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff81b507c0-ffffffff81b50819: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3e0b0)
Location: net/ipv6/route.c:397
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff81b3e0b0-ffffffff81b3e109: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c04990)
Location: net/ipv6/route.c:397
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff81c04990-ffffffff81c049e9: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9f400)
Location: net/ipv6/route.c:399
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff81d9f400-ffffffff81d9f481: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6e420)
Location: net/ipv6/route.c:399
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff81f6e420-ffffffff81f6e4a1: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fce4e0)
Location: net/ipv6/route.c:398
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff81fce4e0-ffffffff81fce564: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209bd40)
Location: net/ipv6/route.c:397
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff8209bd40-ffffffff8209bdc4: rt6_check_expired (STB_LOCAL)
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
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0d3f0)
Location: net/ipv6/route.c:411
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_dst_check
```
**Symbols:**

```
ffff800010d0d3f0-ffff800010d0d478: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e13bb8)
Location: net/ipv6/route.c:411
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
c0e13bb8-c0e13c44: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e38e90)
Location: net/ipv6/route.c:411
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_dst_check
```
**Symbols:**

```
c000000000e38e90-c000000000e38f18: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000854d44)
Location: net/ipv6/route.c:411
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_dst_check
```
**Symbols:**

```
ffffffe000854d44-ffffffe000854dae: rt6_check_expired (STB_LOCAL)
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
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819e9900)
Location: net/ipv6/route.c:411
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_dst_check
```
**Symbols:**

```
ffffffff819e9900-ffffffff819e9959: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a66c0)
Location: net/ipv6/route.c:411
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_dst_check
```
**Symbols:**

```
ffffffff819a66c0-ffffffff819a6719: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a54380)
Location: net/ipv6/route.c:411
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_dst_check
```
**Symbols:**

```
ffffffff81a54380-ffffffff81a543d9: rt6_check_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool rt6_check_expired(const struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a60370)
Location: net/ipv6/route.c:411
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_dst_check
```
**Symbols:**

```
ffffffff81a60370-ffffffff81a603c9: rt6_check_expired (STB_LOCAL)
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
