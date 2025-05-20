# Function: <code>__ipv4_neigh_lookup_noref</code>

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
In net/ipv4/route.c (ffffffff817542c5)
Location: include/net/arp.h:20
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8175d076)
Location: include/net/arp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (ffffffff817c038f)
Location: include/net/arp.h:20
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff817c9e36)
Location: include/net/arp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff8180bfe4)
Location: include/net/arp.h:20
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
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
In net/ipv4/route.c (ffffffff817f022f)
Location: include/net/arp.h:20
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff817f911c)
Location: include/net/arp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff8183d104)
Location: include/net/arp.h:20
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
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
In net/ipv4/route.c (ffffffff818102c5)
Location: include/net/arp.h:20
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81819533)
Location: include/net/arp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff8185e775)
Location: include/net/arp.h:20
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
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
In net/ipv4/route.c (ffffffff8188f31c)
Location: include/net/arp.h:21
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81897b43)
Location: include/net/arp.h:21
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff818de822)
Location: include/net/arp.h:21
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
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
In net/core/filter.c (ffffffff818b4262)
Location: include/net/arp.h:21
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff818e36fd)
Location: include/net/arp.h:21
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff818ebe99)
Location: include/net/arp.h:21
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff8193538e)
Location: include/net/arp.h:21
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
In net/core/filter.c (ffffffff818d9a12)
Location: include/net/arp.h:21
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819105ad)
Location: include/net/arp.h:21
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81919c39)
Location: include/net/arp.h:21
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81964d8e)
Location: include/net/arp.h:21
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
In net/core/neighbour.c (ffffffff81914e8f)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff8192a4ea)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81973011)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8197bd24)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff819caaf2)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff819d4da0)
Location: include/net/arp.h:22
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
In net/core/neighbour.c (ffffffff819474ff)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff8195c87a)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819a9984)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819b26c7)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81a016e2)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a0b900)
Location: include/net/arp.h:22
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
In net/core/neighbour.c (ffffffff81a1764f)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81a2e064)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a92db7)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a9bdbf)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81af06e9)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81afc374)
Location: include/net/arp.h:22
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
In net/core/neighbour.c (ffffffff81a1791f)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81a2ffd9)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a9cc65)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81aa5c1f)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81afd6dd)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81b09bb7)
Location: include/net/arp.h:22
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
In net/core/neighbour.c (ffffffff819fe82f)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81a17119)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a87d2a)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a90bec)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae8f18)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81af49f2)
Location: include/net/arp.h:22
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
In net/core/neighbour.c (ffffffff81ab099e)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81ac938c)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81b4225b)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81b4c049)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba8f3d)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81bb5289)
Location: include/net/arp.h:22
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
In net/core/neighbour.c (ffffffff81c29a3e)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81c461d2)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81ccec63)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81cd978b)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3b9a8)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81d48da1)
Location: include/net/arp.h:22
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
In net/core/neighbour.c (ffffffff81ddc77e)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81dfa6a2)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81e8eece)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81e99f0b)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81f04388)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81f12391)
Location: include/net/arp.h:22
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
In net/core/neighbour.c (ffffffff81e4d4d8)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81e6e539)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81eed5d7)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81ef887b)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81f63d76)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81f72088)
Location: include/net/arp.h:22
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
In net/core/neighbour.c (ffffffff81f0c238)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81f2de16)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81fb1647)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81fbc7ad)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff8202a346)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff82039765)
Location: include/net/arp.h:22
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
In net/core/neighbour.c (ffff800010be8920)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffff800010bfe640)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffff800010c59558)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffff800010c635d0)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9d48)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffff800010cc4f04)
Location: include/net/arp.h:22
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
In net/core/neighbour.c (c0d01af0)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (c0d18ddc)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c0d6910c)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (c0d7294c)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (c0dc56a8)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (c0dd09c0)
Location: include/net/arp.h:22
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
In net/core/neighbour.c (c000000000ccaf28)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (c000000000ce62e8)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c000000000d5b2f8)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (c000000000d668e4)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (c000000000dd2e6c)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (c000000000de1264)
Location: include/net/arp.h:22
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
In net/core/neighbour.c (ffffffe00076cd7c)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffe00078067c)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffe0007c320c)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffe0007cabf8)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffe0008107b4)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffe00081a104)
Location: include/net/arp.h:22
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
In net/core/neighbour.c (ffffffff818e74cf)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff818fc84a)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819497f4)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81952537)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff819a1482)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff819ab6a0)
Location: include/net/arp.h:22
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
In net/core/neighbour.c (ffffffff818a130f)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff818b667a)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819032e4)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8190c027)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff8195af42)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81965160)
Location: include/net/arp.h:22
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
In net/core/neighbour.c (ffffffff819384ff)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff8194d87a)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819b3fc4)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819bcd07)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0bd22)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a15f40)
Location: include/net/arp.h:22
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
In net/core/neighbour.c (ffffffff81959d0f)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff8196f234)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819bd6b4)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819c6617)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81a16512)
Location: include/net/arp.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a20980)
Location: include/net/arp.h:22
Inline: True
```
</details>
</li>
</ul>

## Differences
