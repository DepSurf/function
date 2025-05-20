# Function: <code>fib_select_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, int mp_hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8179e2d0)
Location: net/ipv4/fib_semantics.c:1580
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
**Symbols:**

```
ffffffff8179e2d0-ffffffff8179e434: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, int mp_hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8180c0d0)
Location: net/ipv4/fib_semantics.c:1616
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
**Symbols:**

```
ffffffff8180c0d0-ffffffff8180c1f5: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, int mp_hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8183d1f0)
Location: net/ipv4/fib_semantics.c:1621
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
**Symbols:**

```
ffffffff8183d1f0-ffffffff8183d315: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8185e8a0)
Location: net/ipv4/fib_semantics.c:1724
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff8185e8a0-ffffffff8185eba3: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff818de900)
Location: net/ipv4/fib_semantics.c:1767
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff818de900-ffffffff818dec03: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81935470)
Location: net/ipv4/fib_semantics.c:1730
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff81935470-ffffffff81935772: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81964e70)
Location: net/ipv4/fib_semantics.c:1767
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff81964e70-ffffffff81965172: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:2190
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff819cb0f5-ffffffff819cb126: fib_select_path.cold (STB_LOCAL)
ffffffff819cad00-ffffffff819cb05e: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a018f0)
Location: net/ipv4/fib_semantics.c:2190
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff81a018f0-ffffffff81a01c65: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81af0910)
Location: net/ipv4/fib_semantics.c:2208
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff81af0910-ffffffff81af09ce: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81afd900)
Location: net/ipv4/fib_semantics.c:2207
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff81afd900-ffffffff81afd9be: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae9130)
Location: net/ipv4/fib_semantics.c:2210
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff81ae9130-ffffffff81ae91ee: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:2251
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff81d3d1af-ffffffff81d3d1e9: fib_select_path.cold (STB_LOCAL)
ffffffff81ba9170-ffffffff81ba9277: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:2239
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff81f099f6-ffffffff81f09a30: fib_select_path.cold (STB_LOCAL)
ffffffff81d3bc00-ffffffff81d3bd20: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:2245
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff820b12d1-ffffffff820b130b: fib_select_path.cold (STB_LOCAL)
ffffffff81f045f0-ffffffff81f04710: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:2245
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff8213255f-ffffffff82132599: fib_select_path.cold (STB_LOCAL)
ffffffff81f63fb0-ffffffff81f640d0: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:2253
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff82213f1d-ffffffff82213f57: fib_select_path.cold (STB_LOCAL)
ffffffff8202a580-ffffffff8202a6a0: fib_select_path (STB_GLOBAL)
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
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffff800010cb9ee8)
Location: net/ipv4/fib_semantics.c:2190
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffff800010cb9ee8-ffff800010cba27c: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c0dc576c)
Location: net/ipv4/fib_semantics.c:2190
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
c0dc576c-c0dc5b78: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c000000000dd3110)
Location: net/ipv4/fib_semantics.c:2190
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
c000000000dd3110-c000000000dd35fc: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffe0008109b2)
Location: net/ipv4/fib_semantics.c:2190
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffe0008109b2-ffffffe000810c4c: fib_select_path (STB_GLOBAL)
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
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819a1690)
Location: net/ipv4/fib_semantics.c:2190
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff819a1690-ffffffff819a1a05: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8195b150)
Location: net/ipv4/fib_semantics.c:2190
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff8195b150-ffffffff8195b4c5: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a0bf30)
Location: net/ipv4/fib_semantics.c:2190
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff81a0bf30-ffffffff81a0c2a5: fib_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fib_select_path(struct net *net, struct fib_result *res, struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a16720)
Location: net/ipv4/fib_semantics.c:2190
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff81a16720-ffffffff81a16a95: fib_select_path (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sk_buff *skb</code>
</li>
<li>
<b>Param removed. </b>
<code>int mp_hash</code>
</li>
</ul>
</details>
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
