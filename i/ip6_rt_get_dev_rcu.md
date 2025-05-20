# Function: <code>ip6_rt_get_dev_rcu</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81918e50)
Location: net/ipv6/route.c:1026
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81918e50-ffffffff81918ed3: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(struct fib6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81970b90)
Location: net/ipv6/route.c:869
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81970b90-ffffffff81970c11: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(struct fib6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a67c0)
Location: net/ipv6/route.c:871
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff819a67c0-ffffffff819a6841: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a12e80)
Location: net/ipv6/route.c:1009
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81a12e80-ffffffff81a12f0e: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a49a70)
Location: net/ipv6/route.c:1015
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81a49a70-ffffffff81a49afe: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b40440)
Location: net/ipv6/route.c:1018
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81b40440-ffffffff81b404d0: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4ef00)
Location: net/ipv6/route.c:1001
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81b4ef00-ffffffff81b4ef90: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3cd40)
Location: net/ipv6/route.c:1004
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81b3cd40-ffffffff81b3cdd0: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c036e0)
Location: net/ipv6/route.c:1004
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81c036e0-ffffffff81c03770: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9d700)
Location: net/ipv6/route.c:1007
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81d9d700-ffffffff81d9d790: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6c6c0)
Location: net/ipv6/route.c:1007
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81f6c6c0-ffffffff81f6c750: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcc800)
Location: net/ipv6/route.c:1006
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81fcc800-ffffffff81fcc890: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff82099fe0)
Location: net/ipv6/route.c:1008
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff82099fe0-ffffffff8209a064: ip6_rt_get_dev_rcu (STB_LOCAL)
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
struct net_device *ip6_rt_get_dev_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0cbc8)
Location: net/ipv6/route.c:1015
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffff800010d0cbc8-ffff800010d0cc64: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e133c4)
Location: net/ipv6/route.c:1015
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
c0e133c4-c0e1346c: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e38220)
Location: net/ipv6/route.c:1015
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
c000000000e38220-c000000000e38310: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe0008541e4)
Location: net/ipv6/route.c:1015
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffe0008541e4-ffffffe00085427e: ip6_rt_get_dev_rcu (STB_LOCAL)
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
struct net_device *ip6_rt_get_dev_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819e9100)
Location: net/ipv6/route.c:1015
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff819e9100-ffffffff819e918e: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a5ec0)
Location: net/ipv6/route.c:1015
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff819a5ec0-ffffffff819a5f4e: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a53b80)
Location: net/ipv6/route.c:1015
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81a53b80-ffffffff81a53c0e: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct net_device *ip6_rt_get_dev_rcu(const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5fb70)
Location: net/ipv6/route.c:1015
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81a5fb70-ffffffff81a5fbfe: ip6_rt_get_dev_rcu (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
