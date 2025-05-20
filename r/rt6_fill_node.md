# Function: <code>rt6_fill_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff817d85a0)
Location: net/ipv6/route.c:3045
Inline: True
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:inet6_rt_notify
```
**Symbols:**

```
ffffffff817d85a0-ffffffff817d8b83: rt6_fill_node.constprop.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81841f70)
Location: net/ipv6/route.c:3109
Inline: True
Direct callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
```
**Symbols:**

```
ffffffff81841f70-ffffffff818425b1: rt6_fill_node.constprop.52 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81873cc0)
Location: net/ipv6/route.c:3178
Inline: True
Direct callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
```
**Symbols:**

```
ffffffff81873cc0-ffffffff81874309: rt6_fill_node.constprop.54 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct rt6_info *rt, struct in6_addr *dst, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81898b10)
Location: net/ipv6/route.c:3382
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81898b10-ffffffff8189913c: rt6_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct rt6_info *rt, struct in6_addr *dst, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81919e10)
Location: net/ipv6/route.c:4072
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81919e10-ffffffff8191a442: rt6_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81971f30)
Location: net/ipv6/route.c:4665
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81971f30-ffffffff819724fa: rt6_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a7680)
Location: net/ipv6/route.c:4638
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff819a7680-ffffffff819a7c52: rt6_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:5355
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81a13cd0-ffffffff81a14504: rt6_fill_node (STB_LOCAL)
ffffffff81a1d280-ffffffff81a1d29a: rt6_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4a8c0)
Location: net/ipv6/route.c:5369
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81a4a8c0-ffffffff81a4b0fb: rt6_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b44e20)
Location: net/ipv6/route.c:5449
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81b44e20-ffffffff81b45654: rt6_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b537a0)
Location: net/ipv6/route.c:5434
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81b537a0-ffffffff81b53ff7: rt6_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b40d60)
Location: net/ipv6/route.c:5451
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81b40d60-ffffffff81b415cb: rt6_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:5609
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81c08a30-ffffffff81c0932b: rt6_fill_node (STB_LOCAL)
ffffffff81d3fef9-ffffffff81d3ffd4: rt6_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:5602
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81da34e0-ffffffff81da3e27: rt6_fill_node (STB_LOCAL)
ffffffff81f0c876-ffffffff81f0c94e: rt6_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:5603
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81f72920-ffffffff81f73267: rt6_fill_node (STB_LOCAL)
ffffffff820b3ec7-ffffffff820b3f9f: rt6_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:5601
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81fd2a10-ffffffff81fd335d: rt6_fill_node (STB_LOCAL)
ffffffff82134f8e-ffffffff82135066: rt6_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:5594
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff820a0320-ffffffff820a0c6d: rt6_fill_node (STB_LOCAL)
ffffffff82216a52-ffffffff82216b2a: rt6_fill_node.cold (STB_LOCAL)
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
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0d9c0)
Location: net/ipv6/route.c:5369
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffff800010d0d9c0-ffff800010d0e108: rt6_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e14230)
Location: net/ipv6/route.c:5369
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
c0e14230-c0e14a40: rt6_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e39770)
Location: net/ipv6/route.c:5369
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
c000000000e39770-c000000000e3a174: rt6_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085568e)
Location: net/ipv6/route.c:5369
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffe00085568e-ffffffe000855c9e: rt6_fill_node (STB_LOCAL)
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
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819e9f50)
Location: net/ipv6/route.c:5369
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff819e9f50-ffffffff819ea78b: rt6_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a6d10)
Location: net/ipv6/route.c:5369
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff819a6d10-ffffffff819a754b: rt6_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a549d0)
Location: net/ipv6/route.c:5369
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81a549d0-ffffffff81a5520b: rt6_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rt6_fill_node(struct net *net, struct sk_buff *skb, struct fib6_info *rt, struct dst_entry *dst, struct in6_addr *dest, struct in6_addr *src, int iif, int type, u32 portid, u32 seq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a609c0)
Location: net/ipv6/route.c:5369
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_dump_route
  - net/ipv6/route.c:rt6_nh_dump_exceptions
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81a609c0-ffffffff81a611fb: rt6_fill_node (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct in6_addr *dest</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, skb, rt, dst, src, iif, type, portid, seq, flags</code> ➡️ <code>net, skb, rt, dst, dest, src, iif, type, portid, seq, flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct rt6_info *rt</code> ➡️ <code>struct fib6_info *rt</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct in6_addr *dst</code> ➡️ <code>struct dst_entry *dst</code>
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
