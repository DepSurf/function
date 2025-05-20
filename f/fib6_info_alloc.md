# Function: <code>fib6_info_alloc</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8197b210)
Location: net/ipv6/ip6_fib.c:148
Inline: False
Direct callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff8197b210-ffffffff8197b29e: fib6_info_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b0ee0)
Location: net/ipv6/ip6_fib.c:150
Inline: False
Direct callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff819b0ee0-ffffffff819b0f75: fib6_info_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags, bool with_fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a1f1a0)
Location: net/ipv6/ip6_fib.c:146
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81a1f1a0-ffffffff81a1f21a: fib6_info_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags, bool with_fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a55e20)
Location: net/ipv6/ip6_fib.c:146
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81a55e20-ffffffff81a55e9a: fib6_info_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags, bool with_fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4e680)
Location: net/ipv6/ip6_fib.c:146
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81b4e680-ffffffff81b4e6fa: fib6_info_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags, bool with_fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b5d2f0)
Location: net/ipv6/ip6_fib.c:146
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81b5d2f0-ffffffff81b5d36a: fib6_info_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags, bool with_fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4b530)
Location: net/ipv6/ip6_fib.c:146
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81b4b530-ffffffff81b4b576: fib6_info_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags, bool with_fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81c12870)
Location: net/ipv6/ip6_fib.c:147
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81c12870-ffffffff81c128b6: fib6_info_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags, bool with_fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81dadd80)
Location: net/ipv6/ip6_fib.c:148
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81dadd80-ffffffff81daddcb: fib6_info_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags, bool with_fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81f7d840)
Location: net/ipv6/ip6_fib.c:147
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81f7d840-ffffffff81f7d88b: fib6_info_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags, bool with_fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81fdda50)
Location: net/ipv6/ip6_fib.c:147
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81fdda50-ffffffff81fdda9b: fib6_info_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags, bool with_fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff820aab00)
Location: net/ipv6/ip6_fib.c:147
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff820aab00-ffffffff820aab4b: fib6_info_alloc (STB_GLOBAL)
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
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags, bool with_fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffff800010d1a8f0)
Location: net/ipv6/ip6_fib.c:146
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffff800010d1a8f0-ffff800010d1a964: fib6_info_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags, bool with_fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c0e1fd4c)
Location: net/ipv6/ip6_fib.c:146
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
c0e1fd4c-c0e1fdb0: fib6_info_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags, bool with_fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c000000000e48c30)
Location: net/ipv6/ip6_fib.c:146
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
c000000000e48c30-c000000000e48ccc: fib6_info_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags, bool with_fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffe00085eca2)
Location: net/ipv6/ip6_fib.c:146
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffe00085eca2-ffffffe00085ed14: fib6_info_alloc (STB_GLOBAL)
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
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags, bool with_fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819f54b0)
Location: net/ipv6/ip6_fib.c:146
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff819f54b0-ffffffff819f552a: fib6_info_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags, bool with_fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b2270)
Location: net/ipv6/ip6_fib.c:146
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff819b2270-ffffffff819b22ea: fib6_info_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags, bool with_fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a5ff30)
Location: net/ipv6/ip6_fib.c:146
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81a5ff30-ffffffff81a5ffaa: fib6_info_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fib6_info *fib6_info_alloc(gfp_t gfp_flags, bool with_fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a6c3e0)
Location: net/ipv6/ip6_fib.c:146
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81a6c3e0-ffffffff81a6c45a: fib6_info_alloc (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool with_fib6_nh</code>
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
