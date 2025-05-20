# Function: <code>rt6_get_route_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rt6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d3320)
Location: net/ipv6/route.c:2249
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff817d3320-ffffffff817d33fc: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rt6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81840e50)
Location: net/ipv6/route.c:2320
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81840e50-ffffffff81840f2c: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rt6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81872b20)
Location: net/ipv6/route.c:2343
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81872b20-ffffffff81872c19: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rt6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189a970)
Location: net/ipv6/route.c:2425
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff8189a970-ffffffff8189aa90: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rt6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191cf10)
Location: net/ipv6/route.c:3123
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff8191cf10-ffffffff8191d037: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81972c10)
Location: net/ipv6/route.c:3459
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81972c10-ffffffff81972d15: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a8670)
Location: net/ipv6/route.c:3439
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff819a8670-ffffffff819a8775: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a17110)
Location: net/ipv6/route.c:4079
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81a17110-ffffffff81a17217: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4dd60)
Location: net/ipv6/route.c:4092
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81a4dd60-ffffffff81a4de67: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b44600)
Location: net/ipv6/route.c:4145
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81b44600-ffffffff81b44725: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b52aa0)
Location: net/ipv6/route.c:4129
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81b52aa0-ffffffff81b52bcf: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b40430)
Location: net/ipv6/route.c:4143
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81b40430-ffffffff81b40558: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c06d90)
Location: net/ipv6/route.c:4273
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81c06d90-ffffffff81c06eb8: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da1600)
Location: net/ipv6/route.c:4249
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81da1600-ffffffff81da173b: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f70950)
Location: net/ipv6/route.c:4249
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81f70950-ffffffff81f70a8b: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd0a40)
Location: net/ipv6/route.c:4247
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81fd0a40-ffffffff81fd0b73: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209e330)
Location: net/ipv6/route.c:4249
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff8209e330-ffffffff8209e463: rt6_get_route_info (STB_LOCAL)
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
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0c860)
Location: net/ipv6/route.c:4092
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffff800010d0c860-ffff800010d0c960: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e127a8)
Location: net/ipv6/route.c:4092
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
c0e127a8-c0e128d4: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e37680)
Location: net/ipv6/route.c:4092
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
c000000000e37680-c000000000e37808: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000853856)
Location: net/ipv6/route.c:4092
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffe000853856-ffffffe000853952: rt6_get_route_info (STB_LOCAL)
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
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ed3f0)
Location: net/ipv6/route.c:4092
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff819ed3f0-ffffffff819ed4f7: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819aa1b0)
Location: net/ipv6/route.c:4092
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff819aa1b0-ffffffff819aa2b7: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a57e70)
Location: net/ipv6/route.c:4092
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81a57e70-ffffffff81a57f77: rt6_get_route_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fib6_info *rt6_get_route_info(struct net *net, const struct in6_addr *prefix, int prefixlen, const struct in6_addr *gwaddr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a63fa0)
Location: net/ipv6/route.c:4092
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_route_rcv
```
**Symbols:**

```
ffffffff81a63fa0-ffffffff81a640e3: rt6_get_route_info (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net_device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>int ifindex</code>
</li>
</ul>
</details>
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
