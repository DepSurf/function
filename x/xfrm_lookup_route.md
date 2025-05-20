# Function: <code>xfrm_lookup_route</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff817b6160)
Location: net/xfrm/xfrm_policy.c:2354
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
```
**Symbols:**

```
ffffffff817b6160-ffffffff817b61c4: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81823150)
Location: net/xfrm/xfrm_policy.c:2358
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff81823150-ffffffff818231b4: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81854aa0)
Location: net/xfrm/xfrm_policy.c:2386
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff81854aa0-ffffffff81854b04: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff818785e0)
Location: net/xfrm/xfrm_policy.c:2332
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff818785e0-ffffffff81878644: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff818f8ef0)
Location: net/xfrm/xfrm_policy.c:2274
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff818f8ef0-ffffffff818f8f5a: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8194f950)
Location: net/xfrm/xfrm_policy.c:2281
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff8194f950-ffffffff8194f9d2: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81982f70)
Location: net/xfrm/xfrm_policy.c:3182
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff81982f70-ffffffff81982ff5: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819ecb80)
Location: net/xfrm/xfrm_policy.c:3181
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff819ecb80-ffffffff819ecc0a: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a23b90)
Location: net/xfrm/xfrm_policy.c:3183
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff81a23b90-ffffffff81a23c1a: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b15b80)
Location: net/xfrm/xfrm_policy.c:3173
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff81b15b80-ffffffff81b15c0c: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b23fe0)
Location: net/xfrm/xfrm_policy.c:3194
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff81b23fe0-ffffffff81b2407e: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b11c10)
Location: net/xfrm/xfrm_policy.c:3193
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff81b11c10-ffffffff81b11cae: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bd5740)
Location: net/xfrm/xfrm_policy.c:3198
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff81bd5740-ffffffff81bd57f8: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d6bf50)
Location: net/xfrm/xfrm_policy.c:3201
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff81d6bf50-ffffffff81d6c028: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f372a0)
Location: net/xfrm/xfrm_policy.c:3275
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff81f372a0-ffffffff81f37378: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f96c60)
Location: net/xfrm/xfrm_policy.c:3277
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff81f96c60-ffffffff81f96d39: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff82064010)
Location: net/xfrm/xfrm_policy.c:3299
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff82064010-ffffffff820640e9: xfrm_lookup_route (STB_GLOBAL)
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
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010ce0da0)
Location: net/xfrm/xfrm_policy.c:3183
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffff800010ce0da0-ffff800010ce0e70: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0dea0fc)
Location: net/xfrm/xfrm_policy.c:3183
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
c0dea0fc-c0dea1a8: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000e03200)
Location: net/xfrm/xfrm_policy.c:3183
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
c000000000e03200-c000000000e032e8: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe00082f9f0)
Location: net/xfrm/xfrm_policy.c:3183
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffe00082f9f0-ffffffe00082fa94: xfrm_lookup_route (STB_GLOBAL)
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
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819c3220)
Location: net/xfrm/xfrm_policy.c:3183
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff819c3220-ffffffff819c32aa: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81980010)
Location: net/xfrm/xfrm_policy.c:3183
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff81980010-ffffffff8198009a: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a2dca0)
Location: net/xfrm/xfrm_policy.c:3183
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff81a2dca0-ffffffff81a2dd2a: xfrm_lookup_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup_route(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a39460)
Location: net/xfrm/xfrm_policy.c:3183
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
**Symbols:**

```
ffffffff81a39460-ffffffff81a39503: xfrm_lookup_route (STB_GLOBAL)
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
