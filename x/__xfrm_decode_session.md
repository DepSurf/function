# Function: <code>__xfrm_decode_session</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff817b11a0)
Location: net/xfrm/xfrm_policy.c:2434
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff817b11a0-ffffffff817b11e6: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8181e0f0)
Location: net/xfrm/xfrm_policy.c:2438
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff8181e0f0-ffffffff8181e136: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8184f970)
Location: net/xfrm/xfrm_policy.c:2466
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff8184f970-ffffffff8184f9b6: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81873580)
Location: net/xfrm/xfrm_policy.c:2412
Inline: False
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81873580-ffffffff818735c7: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff818f3f00)
Location: net/xfrm/xfrm_policy.c:2354
Inline: False
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff818f3f00-ffffffff818f3f4c: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8194a6e0)
Location: net/xfrm/xfrm_policy.c:2364
Inline: False
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff8194a6e0-ffffffff8194a72b: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197c730)
Location: net/xfrm/xfrm_policy.c:3266
Inline: False
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff8197c730-ffffffff8197c77b: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819e84d0)
Location: net/xfrm/xfrm_policy.c:3473
Inline: False
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff819e84d0-ffffffff819e8ce2: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a1f4e0)
Location: net/xfrm/xfrm_policy.c:3475
Inline: False
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81a1f4e0-ffffffff81a1fcf2: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b15c3d)
Location: net/xfrm/xfrm_policy.c:3465
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81b126a0-ffffffff81b126ec: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b240ad)
Location: net/xfrm/xfrm_policy.c:3486
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81b20af0-ffffffff81b20b3c: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b11cdd)
Location: net/xfrm/xfrm_policy.c:3446
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81b0e590-ffffffff81b0e5dc: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bd582d)
Location: net/xfrm/xfrm_policy.c:3471
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81bd1a80-ffffffff81bd1acc: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d6c06e)
Location: net/xfrm/xfrm_policy.c:3473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81d67c00-ffffffff81d67c58: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f373ce)
Location: net/xfrm/xfrm_policy.c:3547
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81f32c70-ffffffff81f32cc8: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f96d8e)
Location: net/xfrm/xfrm_policy.c:3557
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81f93df0-ffffffff81f93e48: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __xfrm_decode_session(struct net *net, struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8205b4a0)
Location: net/xfrm/xfrm_policy.c:3458
Inline: False
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff8205b4a0-ffffffff8205b736: __xfrm_decode_session (STB_GLOBAL)
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
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010cdb470)
Location: net/xfrm/xfrm_policy.c:3475
Inline: False
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffff800010cdb470-ffff800010cdbba4: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de5de0)
Location: net/xfrm/xfrm_policy.c:3475
Inline: False
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
c0de5de0-c0de669c: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000e00480)
Location: net/xfrm/xfrm_policy.c:3475
Inline: False
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
c000000000e00480-c000000000e00ed8: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe00082cda0)
Location: net/xfrm/xfrm_policy.c:3475
Inline: False
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffe00082cda0-ffffffe00082d3b2: __xfrm_decode_session (STB_GLOBAL)
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
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819beb70)
Location: net/xfrm/xfrm_policy.c:3475
Inline: False
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff819beb70-ffffffff819bf382: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197b960)
Location: net/xfrm/xfrm_policy.c:3475
Inline: False
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff8197b960-ffffffff8197c172: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a295f0)
Location: net/xfrm/xfrm_policy.c:3475
Inline: False
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81a295f0-ffffffff81a29e02: __xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff *skb, struct flowi *fl, unsigned int family, int reverse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a34b80)
Location: net/xfrm/xfrm_policy.c:3475
Inline: False
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81a34b80-ffffffff81a35392: __xfrm_decode_session (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, fl, family, reverse</code> ➡️ <code>net, skb, fl, family, reverse</code>
</li>
</ul>
</details>
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
