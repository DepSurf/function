# Function: <code>hash32_ptr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f09e6)
Location: include/linux/hash.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
```
```
In net/ipv4/route.c (ffffffff817542cc)
Location: include/linux/hash.h:76
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8175d084)
Location: include/linux/hash.h:76
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff8178b9c5)
Location: include/linux/hash.h:76
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv6/ip6_output.c (ffffffff817c51cb)
Location: include/linux/hash.h:76
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff817d4e30)
Location: include/linux/hash.h:76
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff817de18d)
Location: include/linux/hash.h:76
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f7a06)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
```
```
In net/ipv4/route.c (ffffffff817c0396)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff817c9e44)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff817f8ff5)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff8180bff3)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv6/ip6_output.c (ffffffff81831dbb)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81843093)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff8184c22d)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811053a6)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
```
```
In net/ipv4/route.c (ffffffff817f0236)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff817f912a)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81829ec5)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff8183d113)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv6/ip6_output.c (ffffffff81863d5f)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81874e03)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff8187e0fd)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81107364)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In net/ipv4/route.c (ffffffff818102cc)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81819541)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff8184b105)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff8185e7c6)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv6/ip6_output.c (ffffffff81889316)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81899c12)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff818a412d)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81112494)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In net/ipv4/route.c (ffffffff8188f337)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81897b6a)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff818cad65)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff818de83d)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv6/ip6_output.c (ffffffff81909756)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff8191f297)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81926acd)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8111de88)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In net/core/filter.c (ffffffff818b4d12)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff818e3718)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff818ebe9c)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff819211f5)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff819353ad)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv6/ip6_output.c (ffffffff81960a61)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81975906)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff8197ee95)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81129628)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In net/core/filter.c (ffffffff818da8d2)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819105c8)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81919c3c)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81950005)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81964dad)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv6/ip6_output.c (ffffffff81996d61)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff819ab556)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff819b5465)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811340b5)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In net/core/neighbour.c (ffffffff81914ea8)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff8192a1a2)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv4/route.c (ffffffff8197302c)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
```
```
In net/ipv4/ip_output.c (ffffffff8197bd2e)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff819b48d5)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff819cab11)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff819d4cac)
Location: include/linux/hash.h:94
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a00b5d)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a14e7b)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a23ef5)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81140055)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In net/core/neighbour.c (ffffffff81947518)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff8195c532)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819a999f)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
```
```
In net/ipv4/ip_output.c (ffffffff819b26d1)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff819eb605)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81a01701)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a0b80c)
Location: include/linux/hash.h:94
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a3772d)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a4ba6b)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a5a975)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114fcc5)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
```
```
In net/core/neighbour.c (ffffffff81a17668)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81a302d2)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a92dd2)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a9bdc9)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81ad9325)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81af0708)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81afc282)
Location: include/linux/hash.h:94
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d26a)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81b430d9)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_examine_exception
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81b53415)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114bf49)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
```
```
In net/core/neighbour.c (ffffffff81a17938)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81a31fdc)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a9cc80)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81aa5c29)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81ae5d65)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81afd6f8)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81b09ac2)
Location: include/linux/hash.h:94
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b3bc7a)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81b517c9)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_examine_exception
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81b6198b)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114d3fb)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In net/core/neighbour.c (ffffffff819fe848)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81a18e64)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a87d42)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a90bf6)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81ad1045)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae8f31)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81af4904)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81b295e2)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81b3dc5b)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81b4fc35)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81170bbb)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In net/core/neighbour.c (ffffffff81ab09c6)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81aca683)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81b42280)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81b4c05e)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81b8fa65)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba8f5e)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81bb51a9)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81bef00a)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81c04787)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81c16f95)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a51ed)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In net/core/neighbour.c (ffffffff81c29a65)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81c47a8d)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81ccec87)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81cd979e)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81d20d45)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3b9c8)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81d48ca9)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81d876d8)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81d9e8af)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81db2d05)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e4b4d)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/events/core.c (ffffffff8133cd19)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
```
In net/core/neighbour.c (ffffffff81ddc7a5)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81dfc15d)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81e8eef2)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81e99f1e)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81ee7fc5)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81f043a8)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81f12299)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81f55458)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81f6d85f)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81f82515)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811f91ad)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/events/core.c (ffffffff8136de89)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
```
In net/core/neighbour.c (ffffffff81e4d4ff)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81e6fca1)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81eed60a)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81ef888e)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81f47895)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81f63d97)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81f720aa)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81fb4edb)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81fcd97c)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81fe2825)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8120f39d)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/events/core.c (ffffffff81396fb9)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
```
In net/core/neighbour.c (ffffffff81f0c25f)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81f2f475)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81fb167a)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81fbc7c2)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff8200d9d5)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff8202a367)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff8203966d)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff820825b3)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff8209b1cc)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff820b0745)
Location: include/linux/hash.h:91
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffff8000101ab928)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In net/core/neighbour.c (ffff800010be8930)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffff800010bfe378)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv4/route.c (ffff800010c59578)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
```
```
In net/ipv4/ip_output.c (ffff800010c635e4)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffff800010ca1124)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9d50)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffff800010cc4f0c)
Location: include/linux/hash.h:94
Inline: True
```
```
In net/ipv6/ip6_output.c (ffff800010cfa31c)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffff800010d11c98)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffff800010d1fc7c)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c03f5778)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
```
```
In net/core/neighbour.c (c0d01af8)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (c0d18ad4)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv4/route.c (c0d69128)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
```
```
In net/ipv4/ip_output.c (c0d72964)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (c0dae02c)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (c0dc5528)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (c0dd09d4)
Location: include/linux/hash.h:94
Inline: True
```
```
In net/ipv6/ip6_output.c (c0dff46c)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (c0e15064)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (c0e2484c)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c00000000020dafc)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In net/core/neighbour.c (c000000000ccaf58)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (c000000000ce5f1c)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv4/route.c (c000000000d5b330)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
```
```
In net/ipv4/ip_output.c (c000000000d66910)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (c000000000db40d8)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (c000000000dd2ea4)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (c000000000de12a0)
Location: include/linux/hash.h:94
Inline: True
```
```
In net/ipv6/ip6_output.c (c000000000e1f304)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (c000000000e3b314)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (c000000000e4e378)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffe000135804)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In net/core/neighbour.c (ffffffe00076cd98)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffe0007803c2)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv4/route.c (ffffffe0007c3218)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
```
```
In net/ipv4/ip_output.c (ffffffe0007cac00)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffe0007fd728)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffe000810926)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffe00081a266)
Location: include/linux/hash.h:94
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffe000843cfe)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffe0008568ee)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffe000861e64)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81138805)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In net/core/neighbour.c (ffffffff818e74e8)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff818fc502)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv4/route.c (ffffffff8194980f)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
```
```
In net/ipv4/ip_output.c (ffffffff81952541)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff8198b475)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff819a14a1)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff819ab5ac)
Location: include/linux/hash.h:94
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819d6dbd)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff819eb0fb)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff819fa005)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112b255)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In net/core/neighbour.c (ffffffff818a1328)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff818b6332)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819032ff)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
```
```
In net/ipv4/ip_output.c (ffffffff8190c031)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81944f35)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff8195af61)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff8196506c)
Location: include/linux/hash.h:94
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81993b7d)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff819a7ebb)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff819b6dc5)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81136525)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In net/core/neighbour.c (ffffffff81938518)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff8194d532)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819b3fdf)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
```
```
In net/ipv4/ip_output.c (ffffffff819bcd11)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff819f5c45)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0bd41)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a15e4c)
Location: include/linux/hash.h:94
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a4183d)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a55b7b)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a64a85)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81143024)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In net/core/neighbour.c (ffffffff81959d28)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff8196eef2)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819bd6cf)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
```
```
In net/ipv4/ip_output.c (ffffffff819c6621)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff819ffe45)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81a16531)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a2088c)
Location: include/linux/hash.h:94
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d49d)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a61b7b)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a70fb5)
Location: include/linux/hash.h:94
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
</ul>

## Differences
