# Function: <code>dst_release_immediate</code>

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
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff817d9a30)
Location: net/core/dst.c:193
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_flo_delete
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_dst_alloc
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff817d9a30-ffffffff817d9a99: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff818543d0)
Location: net/core/dst.c:193
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_dst_alloc
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff818543d0-ffffffff81854439: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:196
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff8189fb5f-ffffffff8189fb7c: dst_release_immediate.cold.7 (STB_LOCAL)
ffffffff8189faf0-ffffffff8189fb41: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:196
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff818c252e-ffffffff818c254b: dst_release_immediate.cold.7 (STB_LOCAL)
ffffffff818c2280-ffffffff818c22d1: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:184
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff8190ecc0-ffffffff8190ecde: dst_release_immediate.cold (STB_LOCAL)
ffffffff8190e9e0-ffffffff8190ea35: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:184
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff81941330-ffffffff8194134e: dst_release_immediate.cold (STB_LOCAL)
ffffffff81941040-ffffffff819410ac: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:184
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81a10fad-ffffffff81a10fc8: dst_release_immediate.cold (STB_LOCAL)
ffffffff81a10c10-ffffffff81a10c87: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:184
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81c31587-ffffffff81c315a2: dst_release_immediate.cold (STB_LOCAL)
ffffffff81a10fc0-ffffffff81a11037: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:184
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81c23890-ffffffff81c238ab: dst_release_immediate.cold (STB_LOCAL)
ffffffff819f7e30-ffffffff819f7ea7: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:182
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81d3699b-ffffffff81d369d0: dst_release_immediate.cold (STB_LOCAL)
ffffffff81aa9a40-ffffffff81aa9aca: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:182
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81f0327e-ffffffff81f032b4: dst_release_immediate.cold (STB_LOCAL)
ffffffff81c21e90-ffffffff81c21f44: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:182
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff820abaee-ffffffff820abb09: dst_release_immediate.cold (STB_LOCAL)
ffffffff81dd4410-ffffffff81dd44da: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81e45130)
Location: net/core/dst.c:171
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_destroy
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81e45250-ffffffff81e452ca: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81f03db0)
Location: net/core/dst.c:171
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_destroy
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81f03ed0-ffffffff81f03f4a: dst_release_immediate (STB_GLOBAL)
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
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffff800010be0d28)
Location: net/core/dst.c:184
Inline: True
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffff800010be0d28-ffff800010be0e00: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (c0cfadb4)
Location: net/core/dst.c:184
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:rt_fibinfo_free
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
c0cfadb4-c0cfae70: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (c000000000cc18d0)
Location: net/core/dst.c:184
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
c000000000cc18d0-c000000000cc19dc: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffe000767120)
Location: net/core/dst.c:184
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffe000767120-ffffffe0007671c2: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:184
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff818e1300-ffffffff818e131e: dst_release_immediate.cold (STB_LOCAL)
ffffffff818e1010-ffffffff818e107c: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:184
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff8189b140-ffffffff8189b15e: dst_release_immediate.cold (STB_LOCAL)
ffffffff8189ae50-ffffffff8189aebc: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:184
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff81932330-ffffffff8193234e: dst_release_immediate.cold (STB_LOCAL)
ffffffff81932040-ffffffff819320ac: dst_release_immediate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dst_release_immediate(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:184
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/ipv4/fib_semantics.c:fib_nh_common_release
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff81953a00-ffffffff81953a1e: dst_release_immediate.cold (STB_LOCAL)
ffffffff81953710-ffffffff8195377c: dst_release_immediate (STB_GLOBAL)
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
