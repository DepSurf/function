# Function: <code>__rt6_find_exception_rcu</code>

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
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191b950)
Location: net/ipv6/route.c:1240
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff8191b950-ffffffff8191ba0f: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81973670)
Location: net/ipv6/route.c:1362
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff81973670-ffffffff8197372c: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a92c0)
Location: net/ipv6/route.c:1376
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff819a92c0-ffffffff819a937c: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a160f0)
Location: net/ipv6/route.c:1526
Inline: False
```
**Symbols:**

```
ffffffff81a160f0-ffffffff81a161a8: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4cd30)
Location: net/ipv6/route.c:1532
Inline: False
```
**Symbols:**

```
ffffffff81a4cd30-ffffffff81a4cdec: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:1554
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_update_exception_stamp_rt
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff81b43260-ffffffff81b434d2: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:1537
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_update_exception_stamp_rt
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff81b51950-ffffffff81b51bc2: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3d970)
Location: net/ipv6/route.c:1547
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff81b3d970-ffffffff81b3da27: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c041d0)
Location: net/ipv6/route.c:1547
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff81c041d0-ffffffff81c04287: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9e4b0)
Location: net/ipv6/route.c:1547
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff81d9e4b0-ffffffff81d9e59d: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6d380)
Location: net/ipv6/route.c:1547
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff81f6d380-ffffffff81f6d46d: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcd4a0)
Location: net/ipv6/route.c:1546
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff81fcd4a0-ffffffff81fcd590: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209acf0)
Location: net/ipv6/route.c:1548
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
ffffffff8209acf0-ffffffff8209ade0: __rt6_find_exception_rcu (STB_LOCAL)
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
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0fca0)
Location: net/ipv6/route.c:1532
Inline: False
```
**Symbols:**

```
ffff800010d0fca0-ffff800010d0fd70: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e172d8)
Location: net/ipv6/route.c:1532
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_find_cached_rt
```
**Symbols:**

```
c0e172d8-c0e173ec: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3d540)
Location: net/ipv6/route.c:1532
Inline: False
```
**Symbols:**

```
c000000000e3d540-c000000000e3d658: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe0008577f0)
Location: net/ipv6/route.c:1532
Inline: False
```
**Symbols:**

```
ffffffe0008577f0-ffffffe0008578cc: __rt6_find_exception_rcu (STB_LOCAL)
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
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ec3c0)
Location: net/ipv6/route.c:1532
Inline: False
```
**Symbols:**

```
ffffffff819ec3c0-ffffffff819ec47c: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a9180)
Location: net/ipv6/route.c:1532
Inline: False
```
**Symbols:**

```
ffffffff819a9180-ffffffff819a923c: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a56e40)
Location: net/ipv6/route.c:1532
Inline: False
```
**Symbols:**

```
ffffffff81a56e40-ffffffff81a56efc: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_rcu(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a62ef0)
Location: net/ipv6/route.c:1532
Inline: False
```
**Symbols:**

```
ffffffff81a62ef0-ffffffff81a62fac: __rt6_find_exception_rcu (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
