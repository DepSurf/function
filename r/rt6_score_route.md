# Function: <code>rt6_score_route</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rt6_score_route(struct rt6_info *rt, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d4d70)
Location: net/ipv6/route.c:628
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_multipath_select
```
**Symbols:**

```
ffffffff817d4d70-ffffffff817d4f34: rt6_score_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rt6_score_route(struct rt6_info *rt, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81842fe0)
Location: net/ipv6/route.c:630
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_multipath_select
```
**Symbols:**

```
ffffffff81842fe0-ffffffff818431a8: rt6_score_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rt6_score_route(struct rt6_info *rt, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81874d50)
Location: net/ipv6/route.c:632
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_multipath_select
```
**Symbols:**

```
ffffffff81874d50-ffffffff81874f18: rt6_score_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rt6_score_route(struct rt6_info *rt, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81899b60)
Location: net/ipv6/route.c:651
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_multipath_select
```
**Symbols:**

```
ffffffff81899b60-ffffffff81899d1c: rt6_score_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rt6_score_route(struct rt6_info *rt, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191b160)
Location: net/ipv6/route.c:656
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_multipath_select
```
**Symbols:**

```
ffffffff8191b160-ffffffff8191b31c: rt6_score_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rt6_score_route(struct fib6_info *rt, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81972eb0)
Location: net/ipv6/route.c:622
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_multipath_select
```
**Symbols:**

```
ffffffff81972eb0-ffffffff81973058: rt6_score_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rt6_score_route(struct fib6_info *rt, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a8ad0)
Location: net/ipv6/route.c:624
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_multipath_select
```
**Symbols:**

```
ffffffff819a8ad0-ffffffff819a8c78: rt6_score_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rt6_score_route(const struct fib6_nh *nh, u32 fib6_flags, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a14e00)
Location: net/ipv6/route.c:711
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81a14e00-ffffffff81a14f87: rt6_score_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rt6_score_route(const struct fib6_nh *nh, u32 fib6_flags, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4b9f0)
Location: net/ipv6/route.c:717
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81a4b9f0-ffffffff81a4bb77: rt6_score_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rt6_score_route(const struct fib6_nh *nh, u32 fib6_flags, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b41a40)
Location: net/ipv6/route.c:720
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81b41a40-ffffffff81b41bc4: rt6_score_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rt6_score_route(const struct fib6_nh *nh, u32 fib6_flags, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b50500)
Location: net/ipv6/route.c:703
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81b50500-ffffffff81b50684: rt6_score_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rt6_score_route(const struct fib6_nh *nh, u32 fib6_flags, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3dbe0)
Location: net/ipv6/route.c:706
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81b3dbe0-ffffffff81b3dd5e: rt6_score_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rt6_score_route(const struct fib6_nh *nh, u32 fib6_flags, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:706
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81c046f0-ffffffff81c0488e: rt6_score_route (STB_LOCAL)
ffffffff81d3fbd4-ffffffff81d3fbf5: rt6_score_route.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rt6_score_route(const struct fib6_nh *nh, u32 fib6_flags, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:709
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81d9e800-ffffffff81d9e9a4: rt6_score_route (STB_LOCAL)
ffffffff81f0c547-ffffffff81f0c56e: rt6_score_route.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rt6_score_route(const struct fib6_nh *nh, u32 fib6_flags, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:709
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81f6d7b0-ffffffff81f6d954: rt6_score_route (STB_LOCAL)
ffffffff820b3bfb-ffffffff820b3c22: rt6_score_route.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rt6_score_route(const struct fib6_nh *nh, u32 fib6_flags, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:708
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81fcd8d0-ffffffff81fcda25: rt6_score_route (STB_LOCAL)
ffffffff82134d17-ffffffff82134d3e: rt6_score_route.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rt6_score_route(const struct fib6_nh *nh, u32 fib6_flags, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:710
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff8209b120-ffffffff8209b275: rt6_score_route (STB_LOCAL)
ffffffff822167db-ffffffff82216802: rt6_score_route.cold (STB_LOCAL)
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
int rt6_score_route(const struct fib6_nh *nh, u32 fib6_flags, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d11bd8)
Location: net/ipv6/route.c:717
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffff800010d11bd8-ffff800010d11dd8: rt6_score_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rt6_score_route(const struct fib6_nh *nh, u32 fib6_flags, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e14f94)
Location: net/ipv6/route.c:717
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
c0e14f94-c0e15154: rt6_score_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rt6_score_route(const struct fib6_nh *nh, u32 fib6_flags, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3b220)
Location: net/ipv6/route.c:717
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
c000000000e3b220-c000000000e3b474: rt6_score_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rt6_score_route(const struct fib6_nh *nh, u32 fib6_flags, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000856850)
Location: net/ipv6/route.c:717
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffe000856850-ffffffe000856a0c: rt6_score_route (STB_LOCAL)
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
int rt6_score_route(const struct fib6_nh *nh, u32 fib6_flags, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819eb080)
Location: net/ipv6/route.c:717
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff819eb080-ffffffff819eb207: rt6_score_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rt6_score_route(const struct fib6_nh *nh, u32 fib6_flags, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a7e40)
Location: net/ipv6/route.c:717
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff819a7e40-ffffffff819a7fc7: rt6_score_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rt6_score_route(const struct fib6_nh *nh, u32 fib6_flags, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a55b00)
Location: net/ipv6/route.c:717
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81a55b00-ffffffff81a55c87: rt6_score_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rt6_score_route(const struct fib6_nh *nh, u32 fib6_flags, int oif, int strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a61b00)
Location: net/ipv6/route.c:717
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81a61b00-ffffffff81a61c8d: rt6_score_route (STB_LOCAL)
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
<code>const struct fib6_nh *nh</code>
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
<b>Param reordered. </b>
<code>rt, oif, strict</code> ➡️ <code>nh, fib6_flags, oif, strict</code>
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
