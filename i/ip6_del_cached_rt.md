# Function: <code>ip6_del_cached_rt</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819743db)
Location: net/ipv6/route.c:3250
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_del
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
In net/ipv6/route.c (ffffffff819a9cdc)
Location: net/ipv6/route.c:3230
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_del
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6_del_cached_rt(struct fib6_config *cfg, struct fib6_info *rt, struct fib6_nh *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a16900)
Location: net/ipv6/route.c:3809
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:fib6_nh_del_cached_rt
```
**Symbols:**

```
ffffffff81a16900-ffffffff81a169b3: ip6_del_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6_del_cached_rt(struct fib6_config *cfg, struct fib6_info *rt, struct fib6_nh *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4d540)
Location: net/ipv6/route.c:3822
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:fib6_nh_del_cached_rt
```
**Symbols:**

```
ffffffff81a4d540-ffffffff81a4d5f3: ip6_del_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ip6_del_cached_rt(struct fib6_config *cfg, struct fib6_info *rt, struct fib6_nh *nh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b43aa1)
Location: net/ipv6/route.c:3875
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
Direct callers:
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81b438f0-ffffffff81b4399e: ip6_del_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ip6_del_cached_rt(struct fib6_config *cfg, struct fib6_info *rt, struct fib6_nh *nh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b52192)
Location: net/ipv6/route.c:3859
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
Direct callers:
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81b51fe0-ffffffff81b5208e: ip6_del_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ip6_del_cached_rt(struct fib6_config *cfg, struct fib6_info *rt, struct fib6_nh *nh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3fb42)
Location: net/ipv6/route.c:3873
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
Direct callers:
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81b3f9a0-ffffffff81b3fa4e: ip6_del_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ip6_del_cached_rt(struct fib6_config *cfg, struct fib6_info *rt, struct fib6_nh *nh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c063b2)
Location: net/ipv6/route.c:4003
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
Direct callers:
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81c06210-ffffffff81c062be: ip6_del_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ip6_del_cached_rt(struct fib6_config *cfg, struct fib6_info *rt, struct fib6_nh *nh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da0b02)
Location: net/ipv6/route.c:3979
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
Direct callers:
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81da0900-ffffffff81da09b8: ip6_del_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ip6_del_cached_rt(struct fib6_config *cfg, struct fib6_info *rt, struct fib6_nh *nh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6fdd2)
Location: net/ipv6/route.c:3979
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
Direct callers:
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81f6fba0-ffffffff81f6fc58: ip6_del_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ip6_del_cached_rt(struct fib6_config *cfg, struct fib6_info *rt, struct fib6_nh *nh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcfee2)
Location: net/ipv6/route.c:3977
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
Direct callers:
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81fcfca0-ffffffff81fcfd58: ip6_del_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ip6_del_cached_rt(struct fib6_config *cfg, struct fib6_info *rt, struct fib6_nh *nh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209d772)
Location: net/ipv6/route.c:3979
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_del_cached_rt
Direct callers:
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff8209d530-ffffffff8209d5e8: ip6_del_cached_rt (STB_LOCAL)
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
int ip6_del_cached_rt(struct fib6_config *cfg, struct fib6_info *rt, struct fib6_nh *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d10238)
Location: net/ipv6/route.c:3822
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:fib6_nh_del_cached_rt
```
**Symbols:**

```
ffff800010d10238-ffff800010d1030c: ip6_del_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_del_cached_rt(struct fib6_config *cfg, struct fib6_info *rt, struct fib6_nh *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e17bc0)
Location: net/ipv6/route.c:3822
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:fib6_nh_del_cached_rt
```
**Symbols:**

```
c0e17bc0-c0e17cc4: ip6_del_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6_del_cached_rt(struct fib6_config *cfg, struct fib6_info *rt, struct fib6_nh *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3df80)
Location: net/ipv6/route.c:3822
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:fib6_nh_del_cached_rt
```
**Symbols:**

```
c000000000e3df80-c000000000e3e090: ip6_del_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_del_cached_rt(struct fib6_config *cfg, struct fib6_info *rt, struct fib6_nh *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000857ea2)
Location: net/ipv6/route.c:3822
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:fib6_nh_del_cached_rt
```
**Symbols:**

```
ffffffe000857ea2-ffffffe000857f58: ip6_del_cached_rt (STB_LOCAL)
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
int ip6_del_cached_rt(struct fib6_config *cfg, struct fib6_info *rt, struct fib6_nh *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ecbd0)
Location: net/ipv6/route.c:3822
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:fib6_nh_del_cached_rt
```
**Symbols:**

```
ffffffff819ecbd0-ffffffff819ecc83: ip6_del_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6_del_cached_rt(struct fib6_config *cfg, struct fib6_info *rt, struct fib6_nh *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a9990)
Location: net/ipv6/route.c:3822
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:fib6_nh_del_cached_rt
```
**Symbols:**

```
ffffffff819a9990-ffffffff819a9a43: ip6_del_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6_del_cached_rt(struct fib6_config *cfg, struct fib6_info *rt, struct fib6_nh *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a57650)
Location: net/ipv6/route.c:3822
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:fib6_nh_del_cached_rt
```
**Symbols:**

```
ffffffff81a57650-ffffffff81a57703: ip6_del_cached_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6_del_cached_rt(struct fib6_config *cfg, struct fib6_info *rt, struct fib6_nh *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a63700)
Location: net/ipv6/route.c:3822
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:fib6_nh_del_cached_rt
```
**Symbols:**

```
ffffffff81a63700-ffffffff81a637b3: ip6_del_cached_rt (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
