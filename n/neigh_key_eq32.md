# Function: <code>neigh_key_eq32</code>

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
In net/ipv4/route.c (0)
Location: include/net/neighbour.h:256
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/net/neighbour.h:256
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/net/neighbour.h:256
Inline: True
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
In net/ipv4/route.c (0)
Location: include/net/neighbour.h:256
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/net/neighbour.h:256
Inline: True
```
```
In net/ipv4/arp.c (ffffffff817f9015)
Location: include/net/neighbour.h:256
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/neighbour.h:256
Inline: True
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
In net/ipv4/route.c (0)
Location: include/net/neighbour.h:256
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/net/neighbour.h:256
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81829ee5)
Location: include/net/neighbour.h:256
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/neighbour.h:256
Inline: True
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
In net/ipv4/route.c (0)
Location: include/net/neighbour.h:257
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/net/neighbour.h:257
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8184b125)
Location: include/net/neighbour.h:257
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/neighbour.h:257
Inline: True
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
In net/ipv4/route.c (0)
Location: include/net/neighbour.h:258
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/net/neighbour.h:258
Inline: True
```
```
In net/ipv4/arp.c (ffffffff818cad85)
Location: include/net/neighbour.h:258
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/neighbour.h:258
Inline: True
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
In net/core/filter.c (ffffffff818b42b8)
Location: include/net/neighbour.h:259
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff818e3756)
Location: include/net/neighbour.h:259
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff818ebeda)
Location: include/net/neighbour.h:259
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81921215)
Location: include/net/neighbour.h:259
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (ffffffff819353dc)
Location: include/net/neighbour.h:259
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
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
In net/core/filter.c (ffffffff818d9a68)
Location: include/net/neighbour.h:265
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81910606)
Location: include/net/neighbour.h:265
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81919c7a)
Location: include/net/neighbour.h:265
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81950025)
Location: include/net/neighbour.h:265
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (ffffffff81964ddc)
Location: include/net/neighbour.h:265
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
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
In net/core/neighbour.c (ffffffff81914ede)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff8192a539)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff8197306a)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8197bd6e)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff819b48f5)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (ffffffff819cab44)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff819d4deb)
Location: include/net/neighbour.h:267
Inline: True
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
In net/core/neighbour.c (ffffffff8194754e)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff8195c8c9)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819a99dd)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819b2711)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff819eb625)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (ffffffff81a01734)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a0b94b)
Location: include/net/neighbour.h:266
Inline: True
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
In net/core/neighbour.c (ffffffff81a176a5)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81a2e0b7)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a92e10)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a9be07)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81ad9345)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (ffffffff81af073b)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81afc3bf)
Location: include/net/neighbour.h:266
Inline: True
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
In net/core/neighbour.c (ffffffff81a17975)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81a30028)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a9ccbe)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81aa5c67)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81ae5d85)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (ffffffff81afd72b)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81b09bff)
Location: include/net/neighbour.h:267
Inline: True
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
In net/core/neighbour.c (ffffffff819fe885)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81a17165)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a87d80)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a90c34)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81ad1065)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae8f66)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81af4a37)
Location: include/net/neighbour.h:267
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
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
In net/core/neighbour.c (ffffffff81ab0a05)
Location: include/net/neighbour.h:268
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81ac93e6)
Location: include/net/neighbour.h:268
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81b422bf)
Location: include/net/neighbour.h:268
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81b4c0a1)
Location: include/net/neighbour.h:268
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81b8fa85)
Location: include/net/neighbour.h:268
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba8f9a)
Location: include/net/neighbour.h:268
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81bb52dc)
Location: include/net/neighbour.h:268
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
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
In net/core/neighbour.c (ffffffff81c29aa0)
Location: include/net/neighbour.h:282
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81c4622d)
Location: include/net/neighbour.h:282
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81ccecc7)
Location: include/net/neighbour.h:282
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81cd97de)
Location: include/net/neighbour.h:282
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81d20d75)
Location: include/net/neighbour.h:282
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3ba03)
Location: include/net/neighbour.h:282
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81d48df4)
Location: include/net/neighbour.h:282
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
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
In net/core/neighbour.c (ffffffff81ddc7e0)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81dfa6fd)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81e8ef32)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81e99f5e)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81ee8005)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (ffffffff81f043e3)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81f123e4)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
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
In net/core/neighbour.c (ffffffff81e4d53a)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81e6e58d)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81eed64a)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81ef88ce)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81f478d5)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (ffffffff81f63dd3)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81f720e0)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
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
In net/core/neighbour.c (ffffffff81f0c29a)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81f2de6a)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81fb16ba)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81fbc801)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff8200da15)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (ffffffff8202a3a3)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff820397b8)
Location: include/net/neighbour.h:279
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
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
In net/core/neighbour.c (ffff800010be8968)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffff800010bfe694)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffff800010c595b0)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffff800010c6361c)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffff800010ca1164)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9d88)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffff800010cc4f44)
Location: include/net/neighbour.h:266
Inline: True
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
In net/core/neighbour.c (c0d01b38)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (c0d18e30)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c0d69168)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (c0d7299c)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (c0dae054)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (c0dc56fc)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (c0dd0a10)
Location: include/net/neighbour.h:266
Inline: True
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
In net/core/neighbour.c (c000000000ccaf98)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (c000000000ce6358)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c000000000d5b378)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (c000000000d66958)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (c000000000db4108)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (c000000000dd2ee8)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (c000000000de12d8)
Location: include/net/neighbour.h:266
Inline: True
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
In net/core/neighbour.c (ffffffe00076cdce)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffe0007806c0)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffe0007c325e)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffe0007cac4e)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffe0007fd764)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (ffffffe000810864)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffe00081a2a6)
Location: include/net/neighbour.h:266
Inline: True
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
In net/core/neighbour.c (ffffffff818e751e)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff818fc899)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff8194984d)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81952581)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff8198b495)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (ffffffff819a14d4)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff819ab6eb)
Location: include/net/neighbour.h:266
Inline: True
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
In net/core/neighbour.c (ffffffff818a135e)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff818b66c9)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff8190333d)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8190c071)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81944f55)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (ffffffff8195af94)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff819651ab)
Location: include/net/neighbour.h:266
Inline: True
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
In net/core/neighbour.c (ffffffff8193854e)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff8194d8c9)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819b401d)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819bcd51)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff819f5c65)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0bd74)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a15f8b)
Location: include/net/neighbour.h:266
Inline: True
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
In net/core/neighbour.c (ffffffff81959d5e)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff8196f283)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819bd70d)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819c6661)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff819ffe65)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_key_eq
```
```
In net/ipv4/fib_semantics.c (ffffffff81a16564)
Location: include/net/neighbour.h:266
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a209cb)
Location: include/net/neighbour.h:266
Inline: True
```
</details>
</li>
</ul>

## Differences
