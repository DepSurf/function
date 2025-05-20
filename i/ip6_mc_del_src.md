# Function: <code>ip6_mc_del_src</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip6_mc_del_src(struct inet6_dev *idev, const struct in6_addr *pmca, int sfmode, int sfcount, const struct in6_addr *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff817e9a30)
Location: net/ipv6/mcast.c:2114
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
```
**Symbols:**

```
ffffffff817e9a30-ffffffff817e9c55: ip6_mc_del_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip6_mc_del_src(struct inet6_dev *idev, const struct in6_addr *pmca, int sfmode, int sfcount, const struct in6_addr *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff818585b0)
Location: net/ipv6/mcast.c:2113
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff818585b0-ffffffff818587ce: ip6_mc_del_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip6_mc_del_src(struct inet6_dev *idev, const struct in6_addr *pmca, int sfmode, int sfcount, const struct in6_addr *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81889d30)
Location: net/ipv6/mcast.c:2137
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff81889d30-ffffffff81889f4e: ip6_mc_del_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip6_mc_del_src(struct inet6_dev *idev, const struct in6_addr *pmca, int sfmode, int sfcount, const struct in6_addr *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff818b07c0)
Location: net/ipv6/mcast.c:2136
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff818b07c0-ffffffff818b09cd: ip6_mc_del_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip6_mc_del_src(struct inet6_dev *idev, const struct in6_addr *pmca, int sfmode, int sfcount, const struct in6_addr *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff819345e0)
Location: net/ipv6/mcast.c:2141
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff819345e0-ffffffff819347ea: ip6_mc_del_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip6_mc_del_src(struct inet6_dev *idev, const struct in6_addr *pmca, int sfmode, int sfcount, const struct in6_addr *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff8198d550)
Location: net/ipv6/mcast.c:2166
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff8198d550-ffffffff8198d756: ip6_mc_del_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip6_mc_del_src(struct inet6_dev *idev, const struct in6_addr *pmca, int sfmode, int sfcount, const struct in6_addr *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff819c3df0)
Location: net/ipv6/mcast.c:2166
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff819c3df0-ffffffff819c3ff6: ip6_mc_del_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6_mc_del_src(struct inet6_dev *idev, const struct in6_addr *pmca, int sfmode, int sfcount, const struct in6_addr *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a32c70)
Location: net/ipv6/mcast.c:2165
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff81a32c70-ffffffff81a32e7d: ip6_mc_del_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6_mc_del_src(struct inet6_dev *idev, const struct in6_addr *pmca, int sfmode, int sfcount, const struct in6_addr *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a697c0)
Location: net/ipv6/mcast.c:2165
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff81a697c0-ffffffff81a699cd: ip6_mc_del_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b62a70)
Location: net/ipv6/mcast.c:2162
Inline: True
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff81b62a70-ffffffff81b62bf7: ip6_mc_del_src.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b70fa0)
Location: net/ipv6/mcast.c:2162
Inline: True
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff81b70fa0-ffffffff81b71127: ip6_mc_del_src.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b5fa90)
Location: net/ipv6/mcast.c:2317
Inline: True
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff81b5fa90-ffffffff81b5fbd5: ip6_mc_del_src.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81c27330)
Location: net/ipv6/mcast.c:2315
Inline: True
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff81c27330-ffffffff81c274ac: ip6_mc_del_src.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81dc3b80)
Location: net/ipv6/mcast.c:2317
Inline: True
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff81dc3b80-ffffffff81dc3d02: ip6_mc_del_src.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81f94d90)
Location: net/ipv6/mcast.c:2317
Inline: True
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff81f94d90-ffffffff81f94f12: ip6_mc_del_src.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81ff5730)
Location: net/ipv6/mcast.c:2317
Inline: True
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff81ff5730-ffffffff81ff58ba: ip6_mc_del_src.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (ffffffff820c3310)
Location: net/ipv6/mcast.c:2314
Inline: True
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff820c3310-ffffffff820c349a: ip6_mc_del_src.isra.0 (STB_LOCAL)
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
int ip6_mc_del_src(struct inet6_dev *idev, const struct in6_addr *pmca, int sfmode, int sfcount, const struct in6_addr *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffff800010d319a8)
Location: net/ipv6/mcast.c:2165
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffff800010d319a8-ffff800010d31cf0: ip6_mc_del_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_mc_del_src(struct inet6_dev *idev, const struct in6_addr *pmca, int sfmode, int sfcount, const struct in6_addr *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (c0e32360)
Location: net/ipv6/mcast.c:2165
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
c0e32360-c0e3254c: ip6_mc_del_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6_mc_del_src(struct inet6_dev *idev, const struct in6_addr *pmca, int sfmode, int sfcount, const struct in6_addr *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (c000000000e604a0)
Location: net/ipv6/mcast.c:2165
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
c000000000e604a0-c000000000e60724: ip6_mc_del_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_mc_del_src(struct inet6_dev *idev, const struct in6_addr *pmca, int sfmode, int sfcount, const struct in6_addr *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffe00086e5fa)
Location: net/ipv6/mcast.c:2165
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffe00086e5fa-ffffffe00086e7ae: ip6_mc_del_src (STB_LOCAL)
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
int ip6_mc_del_src(struct inet6_dev *idev, const struct in6_addr *pmca, int sfmode, int sfcount, const struct in6_addr *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a08e50)
Location: net/ipv6/mcast.c:2165
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff81a08e50-ffffffff81a0905d: ip6_mc_del_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6_mc_del_src(struct inet6_dev *idev, const struct in6_addr *pmca, int sfmode, int sfcount, const struct in6_addr *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff819c5c10)
Location: net/ipv6/mcast.c:2165
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff819c5c10-ffffffff819c5e1d: ip6_mc_del_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6_mc_del_src(struct inet6_dev *idev, const struct in6_addr *pmca, int sfmode, int sfcount, const struct in6_addr *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a738d0)
Location: net/ipv6/mcast.c:2165
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff81a738d0-ffffffff81a73add: ip6_mc_del_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6_mc_del_src(struct inet6_dev *idev, const struct in6_addr *pmca, int sfmode, int sfcount, const struct in6_addr *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a7ff50)
Location: net/ipv6/mcast.c:2165
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
**Symbols:**

```
ffffffff81a7ff50-ffffffff81a8015d: ip6_mc_del_src (STB_LOCAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
