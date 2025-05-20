# Function: <code>__jhash_nwords</code>

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
In kernel/workqueue.c (ffffffff8109b707)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff817546e4)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/route.c:find_exception
```
```
In net/ipv4/ip_fragment.c (ffffffff8175929d)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipqhashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff81761f4a)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff81788b19)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/icmp.c (ffffffff8178e1eb)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b21ea)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff817e3384)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_portaddr_hash
```
```
In net/ipv6/reassembly.c (ffffffff817eda3d)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
```
```
In net/ipv6/output_core.c (ffffffff81800706)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81801cb4)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/workqueue.c (ffffffff8109ed17)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff817c105f)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_fragment.c (ffffffff817c564b)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipqhashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ce267)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff817f8162)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv4/icmp.c (ffffffff817fb7e8)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81820067)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff81851bef)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/reassembly.c (ffffffff8185c292)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
```
```
In net/ipv6/output_core.c (ffffffff81871e26)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81873037)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/workqueue.c (ffffffff810a3be6)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff817f2117)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_fragment.c (ffffffff817f514b)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipqhashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fe007)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff81829002)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv4/icmp.c (ffffffff8182c6b5)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff818518c6)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff818839af)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/reassembly.c (ffffffff8188e1a2)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
```
```
In net/ipv6/output_core.c (ffffffff818a6406)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7657)
Location: include/linux/jhash.h:149
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/workqueue.c (ffffffff810a0d65)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff81810aa7)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_fragment.c (ffffffff818155eb)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipqhashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181e42b)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff8184a226)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff81874748)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff818a9c28)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/reassembly.c (ffffffff818b4846)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
```
```
In net/ipv6/output_core.c (ffffffff818cce56)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818cdf57)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/workqueue.c (ffffffff810a75b4)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff8188ff0b)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_fragment.c (ffffffff818947a1)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipqhashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189d309)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff818c9d97)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f4caf)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff8192c628)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/reassembly.c (ffffffff8193759e)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
```
```
In net/ipv6/output_core.c (ffffffff81951c46)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81952d47)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/workqueue.c (ffffffff810ae11b)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff818e2e57)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f203b)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff8191fd69)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194b623)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff819853a8)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/output_core.c (ffffffff819ab1e0)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819ac839)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/workqueue.c (ffffffff810b724e)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff8190fcf7)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191f9ee)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff8194e9d3)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197bf51)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff819bbb22)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/output_core.c (ffffffff819e1d00)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e337c)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/workqueue.c (ffffffff810bc5de)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff81973da1)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffff81982300)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff819b31bc)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e542b)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff81a2a95e)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a521ea)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/workqueue.c (ffffffff810c332e)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/sched/cls_api.c (ffffffff81999438)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/ipv4/route.c (ffffffff819aa7c1)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b8b67)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff819e9f3f)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1c45b)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff81a614b1)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a88ded)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/workqueue.c (ffffffff810cadb5)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In security/selinux/ss/ebitmap.c (ffffffff814bf4fc)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In security/selinux/ss/context.c (ffffffff814d0235)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/sched/cls_api.c (ffffffff81a6c315)
Location: include/linux/jhash.h:148
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a94add)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa3587)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff81ad7b1d)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b103fe)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff81b59337)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b83e86)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/workqueue.c (ffffffff810c5ee5)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In security/selinux/ss/ebitmap.c (ffffffff814dcf1c)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In security/selinux/ss/context.c (ffffffff814ed765)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/sched/cls_api.c (ffffffff81a74cb5)
Location: include/linux/jhash.h:150
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a9eadd)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aadad2)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff81ae416d)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1e6ee)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff81b67967)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b936e6)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/workqueue.c (ffffffff810c7825)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In security/selinux/ss/ebitmap.c (ffffffff814e387c)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In security/selinux/ss/context.c (ffffffff814f44e5)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/sched/cls_api.c (ffffffff81a5d865)
Location: include/linux/jhash.h:150
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a89a3e)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a98b90)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff81acf367)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c3e5)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff81b55b48)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b827fd)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff81bbccc2)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In kernel/workqueue.c (ffffffff810da585)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In security/selinux/ss/ebitmap.c (ffffffff8153cc6c)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In security/selinux/ss/context.c (ffffffff8154ee95)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/sched/cls_api.c (ffffffff81b16775)
Location: include/linux/jhash.h:150
Inline: True
```
```
In net/ipv4/route.c (ffffffff81b446f3)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b54070)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff81b8dd87)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcf427)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/route.c (ffffffff81c0a9ee)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/udp.c (ffffffff81c1b608)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4e8cd)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff81c8cb22)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In kernel/workqueue.c (ffffffff810f3cc6)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In security/selinux/ss/ebitmap.c (ffffffff815d466c)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In security/selinux/ss/context.c (ffffffff815e8011)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/sched/cls_api.c (ffffffff81c9de65)
Location: include/linux/jhash.h:150
Inline: True
```
```
In net/ipv4/route.c (ffffffff81cd13ac)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce1f79)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff81d1efaf)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6543f)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/route.c (ffffffff81da57a1)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/udp.c (ffffffff81db7d28)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def1fd)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff81e361d2)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In kernel/workqueue.c (ffffffff81115f16)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In security/selinux/ss/ebitmap.c (ffffffff8168277c)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In security/selinux/ss/context.c (ffffffff81697751)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/sched/cls_api.c (ffffffff81e5a555)
Location: include/linux/jhash.h:150
Inline: True
```
```
In net/ipv4/route.c (ffffffff81e918dc)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea53d1)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_bhash2_addr_any_hashbucket
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5ba1)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81eaa16f)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/udp.c (ffffffff81ee60c7)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f303a0)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/route.c (ffffffff81f74ce1)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/udp.c (ffffffff81f87d58)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc32ad)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff8200f1a2)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In kernel/workqueue.c (ffffffff81122cb6)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In security/selinux/ss/ebitmap.c (ffffffff816ba8fc)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In security/selinux/ss/context.c (ffffffff816cfc51)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/sched/cls_api.c (ffffffff81eb5e05)
Location: include/linux/jhash.h:150
Inline: True
```
```
In net/ipv4/route.c (ffffffff81ef0091)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f03b59)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_bhash2_addr_any_hashbucket
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04322)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f08989)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/udp.c (ffffffff81f458c7)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8ec82)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/route.c (ffffffff81fd4d81)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/udp.c (ffffffff81feb489)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820249fd)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff8208bd92)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In kernel/workqueue.c (ffffffff8112cc85)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:get_unbound_pool
```
```
In security/selinux/ss/ebitmap.c (ffffffff816f738c)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In security/selinux/ss/policydb.c (ffffffff816fc388)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_trans_hash
```
```
In security/selinux/ss/context.c (ffffffff8170c271)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/sched/cls_api.c (ffffffff81f78b15)
Location: include/linux/jhash.h:150
Inline: True
```
```
In net/ipv4/route.c (ffffffff81fb41e1)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc7e0c)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_bhash2_addr_any_hashbucket
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8672)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fccbea)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/udp.c (ffffffff8200ba17)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205c992)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/route.c (ffffffff820a2691)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/udp.c (ffffffff820b9149)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3cee)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff82162252)
Location: include/linux/jhash.h:150
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In kernel/workqueue.c (ffff8000101210a4)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/sched/cls_api.c (ffff800010c46138)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/ipv4/route.c (ffff800010c5ab78)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffff800010c69f78)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffff800010c9f74c)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffff800010cda66c)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffff800010d24508)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d559ec)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/workqueue.c (c0374fe4)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/sched/cls_api.c (c0d55fcc)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_signal_destroying
```
```
In net/ipv4/route.c (c0d6a03c)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (c0d794c8)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (c0daca78)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (c0de2288)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (c0e2b37c)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (c0e55fd8)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/workqueue.c (c00000000016a624)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/sched/cls_api.c (c000000000d40b50)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_signal_destroying
```
```
In net/ipv4/route.c (c000000000d5c7c0)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (c000000000d6f4f0)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (c000000000db220c)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (c000000000df8e0c)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (c000000000e56d94)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8eb14)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/workqueue.c (ffffffe0000d9ff0)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/sched/cls_api.c (ffffffe0007b3018)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_signal_destroying
```
```
In net/ipv4/route.c (ffffffe0007c3f16)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007cfde2)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffe0007fc258)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082b2e2)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffe000868054)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d196)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/workqueue.c (ffffffff810bd69e)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/sched/cls_api.c (ffffffff819392a8)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/ipv4/route.c (ffffffff8194a631)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffff819589d7)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff81989daf)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bbaeb)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff81a00b41)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a2847d)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/workqueue.c (ffffffff810abece)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In drivers/net/vxlan.c (ffffffff8176caa4)
Location: include/linux/jhash.h:148
Inline: True
```
```
In net/sched/cls_api.c (ffffffff818f2da8)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/ipv4/route.c (ffffffff81904121)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffff819124c7)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff8194386f)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff819788db)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff819bd901)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e523d)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/workqueue.c (ffffffff810bcbfe)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/sched/cls_api.c (ffffffff8198a438)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/ipv4/route.c (ffffffff819b4e01)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c31a7)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff819f457f)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2656b)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff81a6b5c1)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a9402d)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In kernel/workqueue.c (ffffffff810c4f7e)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/sched/cls_api.c (ffffffff819ab7a7)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/ipv4/route.c (ffffffff819be541)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cce77)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff819fe73f)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a31a1b)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff81a77bd1)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa017d)
Location: include/linux/jhash.h:148
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
</ul>

## Differences
