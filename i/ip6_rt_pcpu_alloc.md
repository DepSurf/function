# Function: <code>ip6_rt_pcpu_alloc</code>

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
In net/ipv6/route.c (ffffffff817d5c7f)
Location: net/ipv6/route.c:972
Inline: True
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
In net/ipv6/route.c (ffffffff818441df)
Location: net/ipv6/route.c:977
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (ffffffff81875f4f)
Location: net/ipv6/route.c:980
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189b52a)
Location: net/ipv6/route.c:1002
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191e0b8)
Location: net/ipv6/route.c:1091
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81976664)
Location: net/ipv6/route.c:1211
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ac244)
Location: net/ipv6/route.c:1214
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a19cdf)
Location: net/ipv6/route.c:1365
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5094f)
Location: net/ipv6/route.c:1371
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_pcpu_alloc(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b44ce0)
Location: net/ipv6/route.c:1371
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81b44ce0-ffffffff81b44e18: ip6_rt_pcpu_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rt6_info *ip6_rt_pcpu_alloc(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b54790)
Location: net/ipv6/route.c:1354
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81b54790-ffffffff81b548d1: ip6_rt_pcpu_alloc (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff81b42f75)
Location: net/ipv6/route.c:1357
Inline: True
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
In net/ipv6/route.c (ffffffff81c0b48f)
Location: net/ipv6/route.c:1357
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da62e9)
Location: net/ipv6/route.c:1357
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f75859)
Location: net/ipv6/route.c:1357
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd5902)
Location: net/ipv6/route.c:1356
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a3262)
Location: net/ipv6/route.c:1358
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d14890)
Location: net/ipv6/route.c:1371
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1a4f0)
Location: net/ipv6/route.c:1371
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e415d0)
Location: net/ipv6/route.c:1371
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (ffffffe00085a090)
Location: net/ipv6/route.c:1371
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819effdf)
Location: net/ipv6/route.c:1371
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819acd9f)
Location: net/ipv6/route.c:1371
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5aa5f)
Location: net/ipv6/route.c:1371
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a66cfe)
Location: net/ipv6/route.c:1371
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
