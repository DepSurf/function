# Function: <code>arp_hashfn</code>

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
In net/ipv4/route.c (ffffffff817542cc)
Location: include/net/arp.h:12
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8175d084)
Location: include/net/arp.h:12
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff8178b9c5)
Location: include/net/arp.h:12
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
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
In net/ipv4/route.c (ffffffff817c0396)
Location: include/net/arp.h:12
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff817c9e44)
Location: include/net/arp.h:12
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff817f8ff5)
Location: include/net/arp.h:12
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff8180bff3)
Location: include/net/arp.h:12
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
In net/ipv4/route.c (ffffffff817f0236)
Location: include/net/arp.h:12
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff817f912a)
Location: include/net/arp.h:12
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81829ec5)
Location: include/net/arp.h:12
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff8183d113)
Location: include/net/arp.h:12
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
In net/ipv4/route.c (ffffffff818102cc)
Location: include/net/arp.h:12
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81819541)
Location: include/net/arp.h:12
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff8184b105)
Location: include/net/arp.h:12
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff8185e7c6)
Location: include/net/arp.h:12
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
In net/ipv4/route.c (ffffffff8188f337)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81897b6a)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff818cad65)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff818de83d)
Location: include/net/arp.h:13
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
In net/core/filter.c (ffffffff818b4278)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff818e3718)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff818ebe9c)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff819211f5)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff819353ad)
Location: include/net/arp.h:13
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
In net/core/filter.c (ffffffff818d9a28)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819105c8)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81919c3c)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81950005)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81964dad)
Location: include/net/arp.h:13
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
In net/core/neighbour.c (ffffffff81914ea8)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff8192a500)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff8197302c)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8197bd2e)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff819b48d5)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff819cab11)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff819d4dbe)
Location: include/net/arp.h:13
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
In net/core/neighbour.c (ffffffff81947518)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff8195c890)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819a999f)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819b26d1)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff819eb605)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81a01701)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a0b91e)
Location: include/net/arp.h:13
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
In net/core/neighbour.c (ffffffff81a17668)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81a2e080)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a92dd2)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a9bdc9)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81ad9325)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81af0708)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81afc392)
Location: include/net/arp.h:13
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
In net/core/neighbour.c (ffffffff81a17938)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81a2ffef)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a9cc80)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81aa5c29)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81ae5d65)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81afd6f8)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81b09bd2)
Location: include/net/arp.h:13
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
In net/core/neighbour.c (ffffffff819fe848)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81a1712c)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a87d42)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a90bf6)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81ad1045)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae8f31)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81af4a0a)
Location: include/net/arp.h:13
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
In net/core/neighbour.c (ffffffff81ab09c6)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81ac93ab)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81b42280)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81b4c05e)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81b8fa65)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba8f5e)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81bb52ad)
Location: include/net/arp.h:13
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
In net/core/neighbour.c (ffffffff81c29a65)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81c461f0)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81ccec87)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81cd979e)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81d20d45)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3b9c8)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81d48dc5)
Location: include/net/arp.h:13
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
In net/core/neighbour.c (ffffffff81ddc7a5)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81dfa6c0)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81e8eef2)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81e99f1e)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81ee7fc5)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81f043a8)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81f123b5)
Location: include/net/arp.h:13
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
In net/core/neighbour.c (ffffffff81e4d4ff)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81e6e55e)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81eed60a)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81ef888e)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81f47895)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81f63d97)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81f720aa)
Location: include/net/arp.h:13
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
In net/core/neighbour.c (ffffffff81f0c25f)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff81f2de3b)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81fb167a)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81fbc7c2)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff8200d9d5)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff8202a367)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff82039786)
Location: include/net/arp.h:13
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
In net/core/neighbour.c (ffff800010be8930)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffff800010bfe65c)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffff800010c59578)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffff800010c635e4)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffff800010ca1124)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9d50)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffff800010cc4f0c)
Location: include/net/arp.h:13
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
In net/core/neighbour.c (c0d01af8)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (c0d18df8)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c0d69128)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (c0d72964)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (c0dae02c)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (c0dc56c4)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (c0dd09d4)
Location: include/net/arp.h:13
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
In net/core/neighbour.c (c000000000ccaf58)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (c000000000ce6318)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c000000000d5b330)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (c000000000d66910)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (c000000000db40d8)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (c000000000dd2ea4)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (c000000000de12a0)
Location: include/net/arp.h:13
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
In net/core/neighbour.c (ffffffe00076cd96)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffe000780688)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffe0007c3218)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffe0007cac00)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffe0007fd728)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffe000810824)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffe00081a266)
Location: include/net/arp.h:13
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
In net/core/neighbour.c (ffffffff818e74e8)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff818fc860)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff8194980f)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81952541)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff8198b475)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff819a14a1)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff819ab6be)
Location: include/net/arp.h:13
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
In net/core/neighbour.c (ffffffff818a1328)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff818b6690)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819032ff)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8190c031)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff81944f35)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff8195af61)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff8196517e)
Location: include/net/arp.h:13
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
In net/core/neighbour.c (ffffffff81938518)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff8194d890)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819b3fdf)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819bcd11)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff819f5c45)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0bd41)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a15f5e)
Location: include/net/arp.h:13
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
In net/core/neighbour.c (ffffffff81959d28)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
```
```
In net/core/filter.c (ffffffff8196f24a)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819bd6cf)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819c6621)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/arp.c (ffffffff819ffe45)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_hash
```
```
In net/ipv4/fib_semantics.c (ffffffff81a16531)
Location: include/net/arp.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a2099e)
Location: include/net/arp.h:13
Inline: True
```
</details>
</li>
</ul>

## Differences
