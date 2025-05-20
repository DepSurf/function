# Function: <code>ip6_route_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d3ca0)
Location: net/ipv6/route.c:2054
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff817d3ca0-ffffffff817d3dbb: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff818416a0)
Location: net/ipv6/route.c:2125
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff818416a0-ffffffff818417bb: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81873500)
Location: net/ipv6/route.c:2146
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff81873500-ffffffff81873633: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189aa90)
Location: net/ipv6/route.c:2214
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff8189aa90-ffffffff8189ae02: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191ba90)
Location: net/ipv6/route.c:2911
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff8191ba90-ffffffff8191bdf9: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81974280)
Location: net/ipv6/route.c:3266
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff81974280-ffffffff8197467c: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a9b80)
Location: net/ipv6/route.c:3246
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff819a9b80-ffffffff819a9f4d: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a18420)
Location: net/ipv6/route.c:3849
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff81a18420-ffffffff81a1889b: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4f080)
Location: net/ipv6/route.c:3862
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff81a4f080-ffffffff81a4f4fb: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b469c0)
Location: net/ipv6/route.c:3915
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff81b469c0-ffffffff81b46c37: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b55500)
Location: net/ipv6/route.c:3899
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff81b55500-ffffffff81b55833: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b43120)
Location: net/ipv6/route.c:3913
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff81b43120-ffffffff81b43449: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c09c40)
Location: net/ipv6/route.c:4043
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff81c09c40-ffffffff81c09f69: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da40c0)
Location: net/ipv6/route.c:4019
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff81da40c0-ffffffff81da4461: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f73520)
Location: net/ipv6/route.c:4019
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff81f73520-ffffffff81f738c1: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd3610)
Location: net/ipv6/route.c:4017
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff81fd3610-ffffffff81fd39a1: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a0f20)
Location: net/ipv6/route.c:4019
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff820a0f20-ffffffff820a12b1: ip6_route_del (STB_LOCAL)
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
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d10898)
Location: net/ipv6/route.c:3862
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffff800010d10898-ffff800010d10d38: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e18b30)
Location: net/ipv6/route.c:3862
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
c0e18b30-c0e18fbc: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3f5f0)
Location: net/ipv6/route.c:3862
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
c000000000e3f5f0-c000000000e3fb74: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000857f94)
Location: net/ipv6/route.c:3862
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffe000857f94-ffffffe0008582f2: ip6_route_del (STB_LOCAL)
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
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ee710)
Location: net/ipv6/route.c:3862
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff819ee710-ffffffff819eeb8b: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ab4d0)
Location: net/ipv6/route.c:3862
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff819ab4d0-ffffffff819ab94b: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a59190)
Location: net/ipv6/route.c:3862
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff81a59190-ffffffff81a5960b: ip6_route_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6_route_del(struct fib6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a65390)
Location: net/ipv6/route.c:3862
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff81a65390-ffffffff81a65849: ip6_route_del (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
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
