# Function: <code>rt_cache_route</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh *nh, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81753290)
Location: net/ipv4/route.c:1315
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_set_nexthop
```
**Symbols:**

```
ffffffff81753290-ffffffff817532e5: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh *nh, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817bf420)
Location: net/ipv4/route.c:1321
Inline: False
```
**Symbols:**

```
ffffffff817bf420-ffffffff817bf475: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh *nh, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817eed70)
Location: net/ipv4/route.c:1331
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff817eed70-ffffffff817eedc5: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh *nh, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818106a0)
Location: net/ipv4/route.c:1348
Inline: False
```
**Symbols:**

```
ffffffff818106a0-ffffffff8181074e: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh *nh, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8188fb20)
Location: net/ipv4/route.c:1355
Inline: False
```
**Symbols:**

```
ffffffff8188fb20-ffffffff8188fbce: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh *nh, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e2d70)
Location: net/ipv4/route.c:1423
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff818e2d70-ffffffff818e2e07: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh *nh, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8190fc10)
Location: net/ipv4/route.c:1426
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff8190fc10-ffffffff8190fca7: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool rt_cache_route(struct fib_nh_common *nhc, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1466
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81972070-ffffffff819720f8: rt_cache_route (STB_LOCAL)
ffffffff81976a17-ffffffff81976a29: rt_cache_route.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh_common *nhc, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819aa190)
Location: net/ipv4/route.c:1468
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff819aa190-ffffffff819aa215: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh_common *nhc, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a92720)
Location: net/ipv4/route.c:1472
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81a92720-ffffffff81a927fa: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh_common *nhc, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9c5c0)
Location: net/ipv4/route.c:1478
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81a9c5c0-ffffffff81a9c69a: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh_common *nhc, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a87750)
Location: net/ipv4/route.c:1466
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81a87750-ffffffff81a8782d: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh_common *nhc, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b42b10)
Location: net/ipv4/route.c:1462
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81b42b10-ffffffff81b42bed: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh_common *nhc, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81ccf300)
Location: net/ipv4/route.c:1469
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81ccf300-ffffffff81ccf3de: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh_common *nhc, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e8f660)
Location: net/ipv4/route.c:1469
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81e8f660-ffffffff81e8f73e: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh_common *nhc, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81eedc80)
Location: net/ipv4/route.c:1469
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81eedc80-ffffffff81eedd68: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh_common *nhc, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb1de0)
Location: net/ipv4/route.c:1471
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81fb1de0-ffffffff81fb1ec8: rt_cache_route (STB_LOCAL)
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
bool rt_cache_route(struct fib_nh_common *nhc, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c5a328)
Location: net/ipv4/route.c:1468
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffff800010c5a328-ffff800010c5a42c: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh_common *nhc, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d69938)
Location: net/ipv4/route.c:1468
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
c0d69938-c0d69a28: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh_common *nhc, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5be10)
Location: net/ipv4/route.c:1468
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
c000000000d5be10-c000000000d5bf24: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh_common *nhc, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c38da)
Location: net/ipv4/route.c:1468
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffe0007c38da-ffffffe0007c3996: rt_cache_route (STB_LOCAL)
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
bool rt_cache_route(struct fib_nh_common *nhc, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8194a000)
Location: net/ipv4/route.c:1468
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff8194a000-ffffffff8194a085: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh_common *nhc, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81903af0)
Location: net/ipv4/route.c:1468
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81903af0-ffffffff81903b75: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh_common *nhc, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b47d0)
Location: net/ipv4/route.c:1468
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff819b47d0-ffffffff819b4855: rt_cache_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool rt_cache_route(struct fib_nh_common *nhc, struct rtable *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819bdf10)
Location: net/ipv4/route.c:1468
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff819bdf10-ffffffff819bdf95: rt_cache_route (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fib_nh_common *nhc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fib_nh *nh</code>
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
