# Function: <code>ndisc_hashfn</code>

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
In net/ipv6/ip6_output.c (ffffffff817c51b1)
Location: include/net/ndisc.h:147
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff817d4e0a)
Location: include/net/ndisc.h:147
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff817de18d)
Location: include/net/ndisc.h:147
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
In net/ipv6/ip6_output.c (ffffffff81831da1)
Location: include/net/ndisc.h:364
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff8184306c)
Location: include/net/ndisc.h:364
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff8184c225)
Location: include/net/ndisc.h:364
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
In net/ipv6/ip6_output.c (ffffffff81863d45)
Location: include/net/ndisc.h:366
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81874ddc)
Location: include/net/ndisc.h:366
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff8187e0f5)
Location: include/net/ndisc.h:366
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
In net/ipv6/ip6_output.c (ffffffff818892fd)
Location: include/net/ndisc.h:366
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81899bec)
Location: include/net/ndisc.h:366
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff818a4125)
Location: include/net/ndisc.h:366
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
In net/ipv6/ip6_output.c (ffffffff8190974b)
Location: include/net/ndisc.h:367
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff8191f275)
Location: include/net/ndisc.h:367
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81926ac5)
Location: include/net/ndisc.h:367
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
In net/core/filter.c (ffffffff818b4d12)
Location: include/net/ndisc.h:367
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff81960a61)
Location: include/net/ndisc.h:367
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff819758ff)
Location: include/net/ndisc.h:367
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff8197ee95)
Location: include/net/ndisc.h:367
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
In net/core/filter.c (ffffffff818da8d2)
Location: include/net/ndisc.h:367
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff81996d61)
Location: include/net/ndisc.h:367
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff819ab54f)
Location: include/net/ndisc.h:367
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff819b5465)
Location: include/net/ndisc.h:367
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
In net/core/filter.c (ffffffff8192a1a2)
Location: include/net/ndisc.h:369
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819721f9)
Location: include/net/ndisc.h:369
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8197c0ad)
Location: include/net/ndisc.h:369
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff819cac56)
Location: include/net/ndisc.h:369
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff819d4cac)
Location: include/net/ndisc.h:369
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a00b5d)
Location: include/net/ndisc.h:369
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a14e6f)
Location: include/net/ndisc.h:369
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a23ef5)
Location: include/net/ndisc.h:369
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
In net/core/filter.c (ffffffff8195c532)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819a8b73)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819b2a53)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81a01846)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a0b80c)
Location: include/net/ndisc.h:370
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a3772d)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a4ba5f)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a5a975)
Location: include/net/ndisc.h:370
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
In net/core/filter.c (ffffffff81a302d2)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a9222a)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a9c0ab)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81af084f)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81afc282)
Location: include/net/ndisc.h:371
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d26a)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81b430d2)
Location: include/net/ndisc.h:371
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
Location: include/net/ndisc.h:371
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
In net/core/filter.c (ffffffff81a31fdc)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a9c0ca)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81aa5f0b)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81afd83f)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81b09ac2)
Location: include/net/ndisc.h:371
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b3bc7a)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81b517c2)
Location: include/net/ndisc.h:371
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
Location: include/net/ndisc.h:371
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
In net/core/filter.c (ffffffff81a18e64)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a873f8)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a90ed5)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae907a)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81af4904)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81b295e2)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81b3dc4f)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81b4fc35)
Location: include/net/ndisc.h:371
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
In net/core/filter.c (ffffffff81aca683)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81b41bef)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81b4c3c4)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba90f3)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81bb51a9)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81bef00a)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81c04787)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81c16f95)
Location: include/net/ndisc.h:371
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
In net/core/filter.c (ffffffff81c47a8d)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81cce5cd)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81cd9a80)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3bb6f)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81d48ca9)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81d876d8)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81d9e8af)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81db2d05)
Location: include/net/ndisc.h:371
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
In net/core/filter.c (ffffffff81dfc15d)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81e8e7ed)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81e9a200)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81f0454f)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81f12299)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81f55458)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81f6d85f)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81f82515)
Location: include/net/ndisc.h:371
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
In net/core/filter.c (ffffffff81e6fca1)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81eecee9)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81ef8b5a)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81f63f18)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81f71f8d)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81fb4edb)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81fcd97c)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81fe2825)
Location: include/net/ndisc.h:371
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
In net/core/filter.c (ffffffff81f2f475)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81fb0f79)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81fbca85)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff8202a4e8)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff8203966d)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff820825b3)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff8209b1cc)
Location: include/net/ndisc.h:371
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff820b0745)
Location: include/net/ndisc.h:371
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
In net/core/filter.c (ffff800010bfe378)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffff800010c58410)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffff800010c63954)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9e50)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffff800010cc4e0c)
Location: include/net/ndisc.h:370
Inline: True
```
```
In net/ipv6/ip6_output.c (ffff800010cfa31c)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffff800010d11c98)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffff800010d1fc7c)
Location: include/net/ndisc.h:370
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
In net/core/filter.c (c0d18ad4)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c0d684d4)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (c0d72d90)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (c0dc5528)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (c0dd08b0)
Location: include/net/ndisc.h:370
Inline: True
```
```
In net/ipv6/ip6_output.c (c0dff464)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (c0e1505c)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (c0e2484c)
Location: include/net/ndisc.h:370
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
In net/core/filter.c (c000000000ce5f1c)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c000000000d5a040)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (c000000000d66dd0)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (c000000000dd3050)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (c000000000de1120)
Location: include/net/ndisc.h:370
Inline: True
```
```
In net/ipv6/ip6_output.c (c000000000e1f304)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (c000000000e3b314)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (c000000000e4e378)
Location: include/net/ndisc.h:370
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
In net/core/filter.c (ffffffe0007803aa)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffe0007c2822)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffe0007caf2e)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffe000810914)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffe00081a14c)
Location: include/net/ndisc.h:370
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffe000843cea)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffe0008568da)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffe000861e64)
Location: include/net/ndisc.h:370
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
In net/core/filter.c (ffffffff818fc502)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819489e3)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819528c3)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff819a15e6)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff819ab5ac)
Location: include/net/ndisc.h:370
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819d6dbd)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff819eb0ef)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff819fa005)
Location: include/net/ndisc.h:370
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
In net/core/filter.c (ffffffff818b6332)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819024d3)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8190c3b3)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff8195b0a6)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff8196506c)
Location: include/net/ndisc.h:370
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81993b7d)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff819a7eaf)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff819b6dc5)
Location: include/net/ndisc.h:370
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
In net/core/filter.c (ffffffff8194d532)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819b31b3)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819bd093)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0be86)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a15e4c)
Location: include/net/ndisc.h:370
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a4183d)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a55b6f)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a64a85)
Location: include/net/ndisc.h:370
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
In net/core/filter.c (ffffffff8196eef2)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819bc883)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819c69a3)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81a16676)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a2088c)
Location: include/net/ndisc.h:370
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d49d)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a61b6f)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a70fb5)
Location: include/net/ndisc.h:370
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_hash
```
</details>
</li>
</ul>

## Differences
