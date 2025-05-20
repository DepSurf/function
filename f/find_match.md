# Function: <code>find_match</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct rt6_info *find_match(struct rt6_info *rt, int oif, int strict, int *mpri, struct rt6_info *match, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d55a0)
Location: net/ipv6/route.c:647
Inline: True
```
**Symbols:**

```
ffffffff817d55a0-ffffffff817d58a0: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct rt6_info *find_match(struct rt6_info *rt, int oif, int strict, int *mpri, struct rt6_info *match, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff818439e0)
Location: net/ipv6/route.c:649
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff818439e0-ffffffff81843cf3: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct rt6_info *find_match(struct rt6_info *rt, int oif, int strict, int *mpri, struct rt6_info *match, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81875750)
Location: net/ipv6/route.c:651
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81875750-ffffffff81875a6a: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct rt6_info *find_match(struct rt6_info *rt, int oif, int strict, int *mpri, struct rt6_info *match, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81899df0)
Location: net/ipv6/route.c:670
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81899df0-ffffffff8189a0e5: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct rt6_info *find_match(struct rt6_info *rt, int oif, int strict, int *mpri, struct rt6_info *match, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191b320)
Location: net/ipv6/route.c:675
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff8191b320-ffffffff8191b615: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct fib6_info *find_match(struct fib6_info *rt, int oif, int strict, int *mpri, struct fib6_info *match, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81973060)
Location: net/ipv6/route.c:655
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
ffffffff81973060-ffffffff819733ba: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct fib6_info *find_match(struct fib6_info *rt, int oif, int strict, int *mpri, struct fib6_info *match, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a8c80)
Location: net/ipv6/route.c:657
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
ffffffff819a8c80-ffffffff819a9010: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool find_match(struct fib6_nh *nh, u32 fib6_flags, int oif, int strict, int *mpri, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a157e0)
Location: net/ipv6/route.c:733
Inline: True
Direct callers:
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_nh_find_match
```
**Symbols:**

```
ffffffff81a157e0-ffffffff81a15aec: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool find_match(struct fib6_nh *nh, u32 fib6_flags, int oif, int strict, int *mpri, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4c3f0)
Location: net/ipv6/route.c:739
Inline: True
Direct callers:
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_nh_find_match
```
**Symbols:**

```
ffffffff81a4c3f0-ffffffff81a4c72f: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool find_match(struct fib6_nh *nh, u32 fib6_flags, int oif, int strict, int *mpri, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b427b9)
Location: net/ipv6/route.c:742
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:rt6_nh_find_match
Direct callers:
  - net/ipv6/route.c:__find_rr_leaf
```
**Symbols:**

```
ffffffff81b426f0-ffffffff81b427ac: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool find_match(struct fib6_nh *nh, u32 fib6_flags, int oif, int strict, int *mpri, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b51179)
Location: net/ipv6/route.c:725
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:rt6_nh_find_match
Direct callers:
  - net/ipv6/route.c:__find_rr_leaf
```
**Symbols:**

```
ffffffff81b510b0-ffffffff81b5116c: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool find_match(struct fib6_nh *nh, u32 fib6_flags, int oif, int strict, int *mpri, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3f0bf)
Location: net/ipv6/route.c:728
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:rt6_nh_find_match
Direct callers:
  - net/ipv6/route.c:__find_rr_leaf
```
**Symbols:**

```
ffffffff81b3efd0-ffffffff81b3f08c: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool find_match(struct fib6_nh *nh, u32 fib6_flags, int oif, int strict, int *mpri, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c06b8f)
Location: net/ipv6/route.c:728
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:rt6_nh_find_match
Direct callers:
  - net/ipv6/route.c:__find_rr_leaf
```
**Symbols:**

```
ffffffff81c06aa0-ffffffff81c06b5c: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool find_match(struct fib6_nh *nh, u32 fib6_flags, int oif, int strict, int *mpri, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da13d2)
Location: net/ipv6/route.c:731
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_find_match
Direct callers:
  - net/ipv6/route.c:__find_rr_leaf
```
**Symbols:**

```
ffffffff81da12a0-ffffffff81da13a0: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool find_match(struct fib6_nh *nh, u32 fib6_flags, int oif, int strict, int *mpri, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f70702)
Location: net/ipv6/route.c:731
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_find_match
Direct callers:
  - net/ipv6/route.c:__find_rr_leaf
```
**Symbols:**

```
ffffffff81f705c0-ffffffff81f706c0: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool find_match(struct fib6_nh *nh, u32 fib6_flags, int oif, int strict, int *mpri, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd0972)
Location: net/ipv6/route.c:730
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_find_match
Direct callers:
  - net/ipv6/route.c:__find_rr_leaf
```
**Symbols:**

```
ffffffff81fd0830-ffffffff81fd0930: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool find_match(struct fib6_nh *nh, u32 fib6_flags, int oif, int strict, int *mpri, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209e262)
Location: net/ipv6/route.c:732
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nh_find_match
Direct callers:
  - net/ipv6/route.c:__find_rr_leaf
```
**Symbols:**

```
ffffffff8209e120-ffffffff8209e220: find_match (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int find_match(const struct tcs_group *tcs, const struct tcs_cmd *cmd, int len);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081c80c)
Location: drivers/soc/qcom/rpmh-rsc.c:422
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_write_ctrl_data
```
```
In net/ipv6/route.c (ffff800010d12d28)
Location: net/ipv6/route.c:739
Inline: True
Direct callers:
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_nh_find_match
```
**Symbols:**

```
ffff800010d12d28-ffff800010d1308c: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool find_match(struct fib6_nh *nh, u32 fib6_flags, int oif, int strict, int *mpri, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1690c)
Location: net/ipv6/route.c:739
Inline: True
Direct callers:
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_nh_find_match
```
**Symbols:**

```
c0e1690c-c0e16c68: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool find_match(struct fib6_nh *nh, u32 fib6_flags, int oif, int strict, int *mpri, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3c890)
Location: net/ipv6/route.c:739
Inline: True
Direct callers:
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_nh_find_match
```
**Symbols:**

```
c000000000e3c890-c000000000e3ccfc: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool find_match(struct fib6_nh *nh, u32 fib6_flags, int oif, int strict, int *mpri, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000856f86)
Location: net/ipv6/route.c:739
Inline: True
Direct callers:
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_nh_find_match
```
**Symbols:**

```
ffffffe000856f86-ffffffe00085726c: find_match (STB_LOCAL)
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
bool find_match(struct fib6_nh *nh, u32 fib6_flags, int oif, int strict, int *mpri, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819eba80)
Location: net/ipv6/route.c:739
Inline: True
Direct callers:
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_nh_find_match
```
**Symbols:**

```
ffffffff819eba80-ffffffff819ebdbf: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool find_match(struct fib6_nh *nh, u32 fib6_flags, int oif, int strict, int *mpri, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a8840)
Location: net/ipv6/route.c:739
Inline: True
Direct callers:
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_nh_find_match
```
**Symbols:**

```
ffffffff819a8840-ffffffff819a8b7f: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool find_match(struct fib6_nh *nh, u32 fib6_flags, int oif, int strict, int *mpri, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a56500)
Location: net/ipv6/route.c:739
Inline: True
Direct callers:
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_nh_find_match
```
**Symbols:**

```
ffffffff81a56500-ffffffff81a5683f: find_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool find_match(struct fib6_nh *nh, u32 fib6_flags, int oif, int strict, int *mpri, bool *do_rr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a62550)
Location: net/ipv6/route.c:739
Inline: True
Direct callers:
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_nh_find_match
```
**Symbols:**

```
ffffffff81a62550-ffffffff81a628ec: find_match (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rt6_info *rt</code> ➡️ <code>struct fib6_info *rt</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct rt6_info *match</code> ➡️ <code>struct fib6_info *match</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct rt6_info *</code> ➡️ <code>struct fib6_info *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fib6_nh *nh</code>
</li>
<li>
<b>Param added. </b>
<code>u32 fib6_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fib6_info *rt</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fib6_info *match</code>
</li>
<li>
<b>Param reordered. </b>
<code>rt, oif, strict, mpri, match, do_rr</code> ➡️ <code>nh, fib6_flags, oif, strict, mpri, do_rr</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct fib6_info *</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct tcs_group *tcs</code>
</li>
<li>
<b>Param added. </b>
<code>const struct tcs_cmd *cmd</code>
</li>
<li>
<b>Param added. </b>
<code>int len</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fib6_nh *nh</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 fib6_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int oif</code>
</li>
<li>
<b>Param removed. </b>
<code>int strict</code>
</li>
<li>
<b>Param removed. </b>
<code>int *mpri</code>
</li>
<li>
<b>Param removed. </b>
<code>bool *do_rr</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
