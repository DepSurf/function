# Function: <code>rt6_remove_exception_rt</code>

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
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191f080)
Location: net/ipv6/route.c:1419
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
**Symbols:**

```
ffffffff8191f080-ffffffff8191f164: rt6_remove_exception_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81973870)
Location: net/ipv6/route.c:1557
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
ffffffff81973870-ffffffff81973948: rt6_remove_exception_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a94c0)
Location: net/ipv6/route.c:1566
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
ffffffff819a94c0-ffffffff819a959a: rt6_remove_exception_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a16870)
Location: net/ipv6/route.c:1859
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
ffffffff81a16870-ffffffff81a168fd: rt6_remove_exception_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4d4b0)
Location: net/ipv6/route.c:1865
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
ffffffff81a4d4b0-ffffffff81a4d53d: rt6_remove_exception_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b43860)
Location: net/ipv6/route.c:1887
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
ffffffff81b43860-ffffffff81b438ed: rt6_remove_exception_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b51f50)
Location: net/ipv6/route.c:1870
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
ffffffff81b51f50-ffffffff81b51fdd: rt6_remove_exception_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3f910)
Location: net/ipv6/route.c:1880
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
ffffffff81b3f910-ffffffff81b3f99d: rt6_remove_exception_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c06180)
Location: net/ipv6/route.c:1883
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
ffffffff81c06180-ffffffff81c0620d: rt6_remove_exception_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da0860)
Location: net/ipv6/route.c:1883
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
ffffffff81da0860-ffffffff81da08fe: rt6_remove_exception_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6faf0)
Location: net/ipv6/route.c:1883
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
ffffffff81f6faf0-ffffffff81f6fb8e: rt6_remove_exception_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcfbe0)
Location: net/ipv6/route.c:1882
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
ffffffff81fcfbe0-ffffffff81fcfc81: rt6_remove_exception_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209d470)
Location: net/ipv6/route.c:1884
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
ffffffff8209d470-ffffffff8209d511: rt6_remove_exception_rt (STB_LOCAL)
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
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d10190)
Location: net/ipv6/route.c:1865
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
ffff800010d10190-ffff800010d10238: rt6_remove_exception_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e17b04)
Location: net/ipv6/route.c:1865
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
c0e17b04-c0e17bc0: rt6_remove_exception_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3de90)
Location: net/ipv6/route.c:1865
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
c000000000e3de90-c000000000e3df78: rt6_remove_exception_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000857e20)
Location: net/ipv6/route.c:1865
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
ffffffe000857e20-ffffffe000857ea2: rt6_remove_exception_rt (STB_LOCAL)
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
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ecb40)
Location: net/ipv6/route.c:1865
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
ffffffff819ecb40-ffffffff819ecbcd: rt6_remove_exception_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a9900)
Location: net/ipv6/route.c:1865
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
ffffffff819a9900-ffffffff819a998d: rt6_remove_exception_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a575c0)
Location: net/ipv6/route.c:1865
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
ffffffff81a575c0-ffffffff81a5764d: rt6_remove_exception_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a63670)
Location: net/ipv6/route.c:1865
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_link_failure
```
**Symbols:**

```
ffffffff81a63670-ffffffff81a636fd: rt6_remove_exception_rt (STB_LOCAL)
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
