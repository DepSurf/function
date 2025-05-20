# Function: <code>dst_dev_put</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff817d9520)
Location: net/core/dst.c:163
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
**Symbols:**

```
ffffffff817d9520-ffffffff817d9595: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81853c30)
Location: net/core/dst.c:163
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81853c30-ffffffff81853ca8: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff8189f3b0)
Location: net/core/dst.c:166
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
```
**Symbols:**

```
ffffffff8189f3b0-ffffffff8189f426: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff818c1d70)
Location: net/core/dst.c:166
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
```
**Symbols:**

```
ffffffff818c1d70-ffffffff818c1de6: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff8190e4c0)
Location: net/core/dst.c:154
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv6/route.c:fib6_nh_release
```
**Symbols:**

```
ffffffff8190e4c0-ffffffff8190e529: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81940b00)
Location: net/core/dst.c:154
Inline: False
Direct callers:
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv6/route.c:fib6_nh_release
```
**Symbols:**

```
ffffffff81940b00-ffffffff81940b69: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81a106a0)
Location: net/core/dst.c:154
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81a106a0-ffffffff81a10709: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81a10a70)
Location: net/core/dst.c:154
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81a10a70-ffffffff81a10ad9: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff819f78e0)
Location: net/core/dst.c:154
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff819f78e0-ffffffff819f7949: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81aa94c0)
Location: net/core/dst.c:152
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv6/route.c:fib6_nh_release_dsts
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81aa94c0-ffffffff81aa9533: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81c21830)
Location: net/core/dst.c:152
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81c21830-ffffffff81c218af: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81dd39f0)
Location: net/core/dst.c:152
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81dd39f0-ffffffff81dd3a6f: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81e447b0)
Location: net/core/dst.c:149
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81e447b0-ffffffff81e4482f: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81f03410)
Location: net/core/dst.c:149
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81f03410-ffffffff81f03488: dst_dev_put (STB_GLOBAL)
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
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffff800010be0910)
Location: net/core/dst.c:154
Inline: False
Direct callers:
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv6/route.c:fib6_nh_release
```
**Symbols:**

```
ffff800010be0910-ffff800010be09bc: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (c0cfa8c8)
Location: net/core/dst.c:154
Inline: False
Direct callers:
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/fib_semantics.c:rt_fibinfo_free
  - net/ipv6/route.c:fib6_nh_release
```
**Symbols:**

```
c0cfa8c8-c0cfa974: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (c000000000cc1f60)
Location: net/core/dst.c:154
Inline: False
Direct callers:
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv6/route.c:fib6_nh_release
```
**Symbols:**

```
c000000000cc1f60-c000000000cc2050: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffe000766ab8)
Location: net/core/dst.c:154
Inline: False
Direct callers:
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv6/route.c:fib6_nh_release
```
**Symbols:**

```
ffffffe000766ab8-ffffffe000766b5e: dst_dev_put (STB_GLOBAL)
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
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff818e0ad0)
Location: net/core/dst.c:154
Inline: False
Direct callers:
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv6/route.c:fib6_nh_release
```
**Symbols:**

```
ffffffff818e0ad0-ffffffff818e0b39: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff8189a910)
Location: net/core/dst.c:154
Inline: False
Direct callers:
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv6/route.c:fib6_nh_release
```
**Symbols:**

```
ffffffff8189a910-ffffffff8189a979: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81931b00)
Location: net/core/dst.c:154
Inline: False
Direct callers:
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv6/route.c:fib6_nh_release
```
**Symbols:**

```
ffffffff81931b00-ffffffff81931b69: dst_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff819531d0)
Location: net/core/dst.c:154
Inline: False
Direct callers:
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv6/route.c:fib6_nh_release
```
**Symbols:**

```
ffffffff819531d0-ffffffff81953239: dst_dev_put (STB_GLOBAL)
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
