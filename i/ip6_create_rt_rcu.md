# Function: <code>ip6_create_rt_rcu</code>

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
struct rt6_info *ip6_create_rt_rcu(struct fib6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81973f60)
Location: net/ipv6/route.c:1035
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81973f60-ffffffff81974014: ip6_create_rt_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rt6_info *ip6_create_rt_rcu(struct fib6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819aa130)
Location: net/ipv6/route.c:1036
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff819aa130-ffffffff819aa21d: ip6_create_rt_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct rt6_info *ip6_create_rt_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:1180
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81a17220-ffffffff81a1731f: ip6_create_rt_rcu (STB_LOCAL)
ffffffff81a1d2be-ffffffff81a1d2c8: ip6_create_rt_rcu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rt6_info *ip6_create_rt_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4de70)
Location: net/ipv6/route.c:1186
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81a4de70-ffffffff81a4df6f: ip6_create_rt_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rt6_info *ip6_create_rt_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b44730)
Location: net/ipv6/route.c:1187
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81b44730-ffffffff81b44852: ip6_create_rt_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rt6_info *ip6_create_rt_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b533e0)
Location: net/ipv6/route.c:1170
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81b533e0-ffffffff81b53502: ip6_create_rt_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rt6_info *ip6_create_rt_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b41ef0)
Location: net/ipv6/route.c:1173
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81b41ef0-ffffffff81b4200a: ip6_create_rt_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rt6_info *ip6_create_rt_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c07390)
Location: net/ipv6/route.c:1173
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81c07390-ffffffff81c074aa: ip6_create_rt_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rt6_info *ip6_create_rt_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da1e70)
Location: net/ipv6/route.c:1176
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81da1e70-ffffffff81da1fae: ip6_create_rt_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rt6_info *ip6_create_rt_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f71200)
Location: net/ipv6/route.c:1176
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81f71200-ffffffff81f7133e: ip6_create_rt_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rt6_info *ip6_create_rt_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd12f0)
Location: net/ipv6/route.c:1175
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81fd12f0-ffffffff81fd140c: ip6_create_rt_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rt6_info *ip6_create_rt_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209e980)
Location: net/ipv6/route.c:1177
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff8209e980-ffffffff8209eacc: ip6_create_rt_rcu (STB_LOCAL)
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
struct rt6_info *ip6_create_rt_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0f1d8)
Location: net/ipv6/route.c:1186
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffff800010d0f1d8-ffff800010d0f2e8: ip6_create_rt_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rt6_info *ip6_create_rt_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e166a8)
Location: net/ipv6/route.c:1186
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
c0e166a8-c0e167ac: ip6_create_rt_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rt6_info *ip6_create_rt_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3d070)
Location: net/ipv6/route.c:1186
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
c000000000e3d070-c000000000e3d224: ip6_create_rt_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rt6_info *ip6_create_rt_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000856d4e)
Location: net/ipv6/route.c:1186
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffe000856d4e-ffffffe000856e3e: ip6_create_rt_rcu (STB_LOCAL)
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
struct rt6_info *ip6_create_rt_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ed500)
Location: net/ipv6/route.c:1186
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff819ed500-ffffffff819ed5ff: ip6_create_rt_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rt6_info *ip6_create_rt_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819aa2c0)
Location: net/ipv6/route.c:1186
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff819aa2c0-ffffffff819aa3bf: ip6_create_rt_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rt6_info *ip6_create_rt_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a57f80)
Location: net/ipv6/route.c:1186
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81a57f80-ffffffff81a5807f: ip6_create_rt_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rt6_info *ip6_create_rt_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a640f0)
Location: net/ipv6/route.c:1186
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
```
**Symbols:**

```
ffffffff81a640f0-ffffffff81a641ef: ip6_create_rt_rcu (STB_LOCAL)
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
<code>const struct fib6_result *res</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fib6_info *rt</code>
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
