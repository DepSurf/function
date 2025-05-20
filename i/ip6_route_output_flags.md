# Function: <code>ip6_route_output_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d48b0)
Location: net/ipv6/route.c:1177
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff817d48b0-ffffffff817d49c0: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81841ea0)
Location: net/ipv6/route.c:1188
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffffffff81841ea0-ffffffff81841f6d: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff818731d0)
Location: net/ipv6/route.c:1193
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
ffffffff818731d0-ffffffff818732c9: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81897ba0)
Location: net/ipv6/route.c:1218
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
ffffffff81897ba0-ffffffff81897c99: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81918f20)
Location: net/ipv6/route.c:1896
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
ffffffff81918f20-ffffffff81919019: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81970c20)
Location: net/ipv6/route.c:2094
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
ffffffff81970c20-ffffffff81970d1b: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a6850)
Location: net/ipv6/route.c:2085
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
ffffffff819a6850-ffffffff819a694b: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2488
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
ffffffff81a1d2b4-ffffffff81a1d2be: ip6_route_output_flags.cold (STB_LOCAL)
ffffffff81a150d0-ffffffff81a15142: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4bcb0)
Location: net/ipv6/route.c:2494
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
ffffffff81a4bcb0-ffffffff81a4bd17: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b40de0)
Location: net/ipv6/route.c:2513
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
ffffffff81b40de0-ffffffff81b40e4c: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4f890)
Location: net/ipv6/route.c:2496
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
ffffffff81b4f890-ffffffff81b4f90a: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3d5c0)
Location: net/ipv6/route.c:2503
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
ffffffff81b3d5c0-ffffffff81b3d63a: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c05650)
Location: net/ipv6/route.c:2633
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
```
**Symbols:**

```
ffffffff81c05650-ffffffff81c056ca: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9fc20)
Location: net/ipv6/route.c:2629
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
**Symbols:**

```
ffffffff81d9fc20-ffffffff81d9fcb6: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6ecc0)
Location: net/ipv6/route.c:2629
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
**Symbols:**

```
ffffffff81f6ecc0-ffffffff81f6ed56: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2628
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
**Symbols:**

```
ffffffff82134d3e-ffffffff82134d57: ip6_route_output_flags.cold (STB_LOCAL)
ffffffff81fcea50-ffffffff81fcebf7: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2630
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
**Symbols:**

```
ffffffff82216802-ffffffff8221681b: ip6_route_output_flags.cold (STB_LOCAL)
ffffffff8209c2b0-ffffffff8209c457: ip6_route_output_flags (STB_GLOBAL)
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
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d11198)
Location: net/ipv6/route.c:2494
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
ffff800010d11198-ffff800010d11294: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e15544)
Location: net/ipv6/route.c:2494
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
c0e15544-c0e1560c: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e384e0)
Location: net/ipv6/route.c:2494
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
c000000000e384e0-c000000000e38594: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000854eac)
Location: net/ipv6/route.c:2494
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
ffffffe000854eac-ffffffe000854f42: ip6_route_output_flags (STB_GLOBAL)
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
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819eb340)
Location: net/ipv6/route.c:2494
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
ffffffff819eb340-ffffffff819eb3a7: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a8100)
Location: net/ipv6/route.c:2494
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
ffffffff819a8100-ffffffff819a8167: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a55dc0)
Location: net/ipv6/route.c:2494
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
ffffffff81a55dc0-ffffffff81a55e27: ip6_route_output_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a61dc0)
Location: net/ipv6/route.c:2494
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:__nf_ip6_route
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
**Symbols:**

```
ffffffff81a61dc0-ffffffff81a61e53: ip6_route_output_flags (STB_GLOBAL)
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
