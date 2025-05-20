# Function: <code>xfrm_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff817b5a30)
Location: net/xfrm/xfrm_policy.c:2205
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff817b5a30-ffffffff817b5e1d: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81822a50)
Location: net/xfrm/xfrm_policy.c:2209
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81822a50-ffffffff81822e34: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81854390)
Location: net/xfrm/xfrm_policy.c:2237
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81854390-ffffffff81854774: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81877e00)
Location: net/xfrm/xfrm_policy.c:2185
Inline: False
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81877e00-ffffffff81878211: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff818f8220)
Location: net/xfrm/xfrm_policy.c:2127
Inline: False
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff818f8220-ffffffff818f8b15: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:2134
Inline: False
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff8195063c-ffffffff81950648: xfrm_lookup.cold.58 (STB_LOCAL)
ffffffff8194ec20-ffffffff8194f524: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81983070)
Location: net/xfrm/xfrm_policy.c:3171
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81982b50-ffffffff81982b63: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819ecc66)
Location: net/xfrm/xfrm_policy.c:3170
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff819ec7e0-ffffffff819ec7f3: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a23c76)
Location: net/xfrm/xfrm_policy.c:3172
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81a237f0-ffffffff81a23803: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b15c82)
Location: net/xfrm/xfrm_policy.c:3162
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81b15670-ffffffff81b15683: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b240f2)
Location: net/xfrm/xfrm_policy.c:3183
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81b23a90-ffffffff81b23aa3: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b11d22)
Location: net/xfrm/xfrm_policy.c:3182
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81b11690-ffffffff81b116a3: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bd5876)
Location: net/xfrm/xfrm_policy.c:3187
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81bd5180-ffffffff81bd5193: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d6c0be)
Location: net/xfrm/xfrm_policy.c:3190
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81d6b980-ffffffff81d6b9a5: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f3741e)
Location: net/xfrm/xfrm_policy.c:3264
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81f36cb0-ffffffff81f36cd5: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f96e2f)
Location: net/xfrm/xfrm_policy.c:3266
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81f96660-ffffffff81f96685: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff820641ca)
Location: net/xfrm/xfrm_policy.c:3288
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff82063a50-ffffffff82063a75: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010ce0ed0)
Location: net/xfrm/xfrm_policy.c:3172
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffff800010ce08a8-ffff800010ce0908: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0dea260)
Location: net/xfrm/xfrm_policy.c:3172
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
c0de9ca0-c0de9cd0: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000e0335c)
Location: net/xfrm/xfrm_policy.c:3172
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
c000000000e02c90-c000000000e02ca8: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe00082fad6)
Location: net/xfrm/xfrm_policy.c:3172
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffe00082f61c-ffffffe00082f668: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819c3306)
Location: net/xfrm/xfrm_policy.c:3172
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff819c2e80-ffffffff819c2e93: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819800f6)
Location: net/xfrm/xfrm_policy.c:3172
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff8197fc70-ffffffff8197fc83: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a2dd86)
Location: net/xfrm/xfrm_policy.c:3172
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81a2d900-ffffffff81a2d913: xfrm_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *xfrm_lookup(struct net *net, struct dst_entry *dst_orig, const struct flowi *fl, const struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a39566)
Location: net/xfrm/xfrm_policy.c:3172
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
Direct callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81a390c0-ffffffff81a390d3: xfrm_lookup (STB_GLOBAL)
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
