# Function: <code>___neigh_lookup_noref</code>

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
In net/core/neighbour.c (ffffffff81725ed2)
Location: include/net/neighbour.h:270
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_xmit
```
```
In net/ipv4/route.c (ffffffff817542c5)
Location: include/net/neighbour.h:270
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8175d076)
Location: include/net/neighbour.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff817c51aa)
Location: include/net/neighbour.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff817d4e03)
Location: include/net/neighbour.h:270
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff817931e8)
Location: include/net/neighbour.h:270
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (ffffffff817c038f)
Location: include/net/neighbour.h:270
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff817c9e36)
Location: include/net/neighbour.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff8180bfe4)
Location: include/net/neighbour.h:270
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv6/ip6_output.c (ffffffff81831d9a)
Location: include/net/neighbour.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81843065)
Location: include/net/neighbour.h:270
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff817c0ab8)
Location: include/net/neighbour.h:270
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (ffffffff817f022f)
Location: include/net/neighbour.h:270
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff817f911c)
Location: include/net/neighbour.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff8183d104)
Location: include/net/neighbour.h:270
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv6/ip6_output.c (ffffffff81863d3e)
Location: include/net/neighbour.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81874dd5)
Location: include/net/neighbour.h:270
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff817df188)
Location: include/net/neighbour.h:271
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (ffffffff818102c5)
Location: include/net/neighbour.h:271
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81819533)
Location: include/net/neighbour.h:271
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff8185e775)
Location: include/net/neighbour.h:271
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv6/ip6_output.c (ffffffff818892f6)
Location: include/net/neighbour.h:271
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81899be5)
Location: include/net/neighbour.h:271
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff81859a38)
Location: include/net/neighbour.h:272
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (ffffffff8188f328)
Location: include/net/neighbour.h:272
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81897b43)
Location: include/net/neighbour.h:272
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff818de827)
Location: include/net/neighbour.h:272
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv6/ip6_output.c (ffffffff81909744)
Location: include/net/neighbour.h:272
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff8191f26b)
Location: include/net/neighbour.h:272
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff818a500d)
Location: include/net/neighbour.h:273
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff818b4d0b)
Location: include/net/neighbour.h:273
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff818e3718)
Location: include/net/neighbour.h:273
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff818ebe9c)
Location: include/net/neighbour.h:273
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff819353ad)
Location: include/net/neighbour.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv6/ip6_output.c (ffffffff81960a5a)
Location: include/net/neighbour.h:273
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff819758ff)
Location: include/net/neighbour.h:273
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff818c83bd)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff818da8cb)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819105c8)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81919c3c)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81964dad)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv6/ip6_output.c (ffffffff81996d5a)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff819ab54f)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff81914e9c)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff8192a19b)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff8197302c)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8197bd2e)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff819cab11)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff819d4c9d)
Location: include/net/neighbour.h:281
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a00b56)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a14e6f)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff8194750c)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff8195c52b)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819a999f)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819b26d1)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81a01701)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a0b7fd)
Location: include/net/neighbour.h:280
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a37726)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a4ba5f)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff81a17668)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81a302d2)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a92dd2)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a9bdc9)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81af0708)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81afc282)
Location: include/net/neighbour.h:280
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d263)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81b430d2)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_examine_exception
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff81a17938)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81a31fdc)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a9cc80)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81aa5c29)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81afd6f8)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81b09ac2)
Location: include/net/neighbour.h:281
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b3bc73)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81b517c2)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_examine_exception
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff819fe848)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81a18e64)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a87d42)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a90bf6)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae8f27)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81af48e7)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81b295db)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81b3dc4f)
Location: include/net/neighbour.h:281
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff81ab09b7)
Location: include/net/neighbour.h:282
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81aca660)
Location: include/net/neighbour.h:282
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81b42275)
Location: include/net/neighbour.h:282
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81b4c055)
Location: include/net/neighbour.h:282
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba8f57)
Location: include/net/neighbour.h:282
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81bb5187)
Location: include/net/neighbour.h:282
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81beeff1)
Location: include/net/neighbour.h:282
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81c0476c)
Location: include/net/neighbour.h:282
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff81c29a5b)
Location: include/net/neighbour.h:296
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81c47a69)
Location: include/net/neighbour.h:296
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81ccec7f)
Location: include/net/neighbour.h:296
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81cd9796)
Location: include/net/neighbour.h:296
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3b9c1)
Location: include/net/neighbour.h:296
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81d48c87)
Location: include/net/neighbour.h:296
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81d876be)
Location: include/net/neighbour.h:296
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81d9e896)
Location: include/net/neighbour.h:296
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff81ddc79b)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81dfc139)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81e8eeea)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81e99f16)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81f043a1)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81f12277)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81f5543e)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81f6d846)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff81e4d4f5)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81e6fc7d)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81eed602)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81ef8886)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81f63d90)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81f720a3)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81fb4ec1)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81fcd961)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff81f0c255)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81f2f44f)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81fb1672)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81fbc7ba)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff8202a360)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff8203964b)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff8208259a)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff8209b1b1)
Location: include/net/neighbour.h:293
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffff800010be8930)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffff800010bfe368)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffff800010c59578)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffff800010c635e4)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9d50)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffff800010cc4f0c)
Location: include/net/neighbour.h:280
Inline: True
```
```
In net/ipv6/ip6_output.c (ffff800010cfa31c)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffff800010d11c98)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (c0d01af8)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (c0d18ac8)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c0d69128)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (c0d72964)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (c0dc5500)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (c0dd09d4)
Location: include/net/neighbour.h:280
Inline: True
```
```
In net/ipv6/ip6_output.c (c0dff464)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (c0e1505c)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (c000000000ccaf58)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (c000000000ce5f18)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c000000000d5b330)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (c000000000d66910)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (c000000000dd2ea4)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (c000000000de12a0)
Location: include/net/neighbour.h:280
Inline: True
```
```
In net/ipv6/ip6_output.c (c000000000e1f2ec)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (c000000000e3b2f8)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffe00076cd84)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffe0007803aa)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffe0007c3210)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffe0007cabf8)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffe0008107b0)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffe00081a104)
Location: include/net/neighbour.h:280
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffe000843cde)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffe0008568ce)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff818e74dc)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff818fc4fb)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff8194980f)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81952541)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff819a14a1)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff819ab59d)
Location: include/net/neighbour.h:280
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819d6db6)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff819eb0ef)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff818a131c)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff818b632b)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819032ff)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8190c031)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff8195af61)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff8196505d)
Location: include/net/neighbour.h:280
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81993b76)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff819a7eaf)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff8193850c)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff8194d52b)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819b3fdf)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819bcd11)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0bd41)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a15e3d)
Location: include/net/neighbour.h:280
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a41836)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a55b6f)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
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
In net/core/neighbour.c (ffffffff81959d1c)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff8196eeeb)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819bd6cf)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819c6621)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81a16531)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a2087d)
Location: include/net/neighbour.h:280
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d496)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a61b6f)
Location: include/net/neighbour.h:280
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
</details>
</li>
</ul>

## Differences
