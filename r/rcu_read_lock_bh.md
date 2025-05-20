# Function: <code>rcu_read_lock_bh</code>

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
In kernel/padata.c (ffffffff811898e6)
Location: include/linux/rcupdate.h:937
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/socket.c (ffffffff816fdfc8)
Location: include/linux/rcupdate.h:937
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff8170cc65)
Location: include/linux/rcupdate.h:937
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/core/dev.c (ffffffff8171cd9f)
Location: include/linux/rcupdate.h:937
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81724460)
Location: include/linux/rcupdate.h:937
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_dump_info
```
```
In net/ipv4/route.c (ffffffff817542ba)
Location: include/linux/rcupdate.h:937
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8175d053)
Location: include/linux/rcupdate.h:937
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp.c (ffffffff81767626)
Location: include/linux/rcupdate.h:937
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv6/ip6_output.c (ffffffff817c517a)
Location: include/linux/rcupdate.h:937
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff817c9381)
Location: include/linux/rcupdate.h:937
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
```
```
In net/ipv6/route.c (ffffffff817d4df8)
Location: include/linux/rcupdate.h:937
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff817d9c8f)
Location: include/linux/rcupdate.h:937
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff817f5c76)
Location: include/linux/rcupdate.h:937
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:fl_lookup
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
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
In kernel/padata.c (ffffffff8119bfd2)
Location: include/linux/rcupdate.h:946
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff8178552f)
Location: include/linux/rcupdate.h:946
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff8178f039)
Location: include/linux/rcupdate.h:946
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (ffffffff817c0384)
Location: include/linux/rcupdate.h:946
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff817c9e13)
Location: include/linux/rcupdate.h:946
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff8180bfd6)
Location: include/linux/rcupdate.h:946
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv6/ip6_output.c (ffffffff81831d6a)
Location: include/linux/rcupdate.h:946
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff818390b6)
Location: include/linux/rcupdate.h:946
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
```
```
In net/ipv6/route.c (ffffffff8184305a)
Location: include/linux/rcupdate.h:946
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81847df9)
Location: include/linux/rcupdate.h:946
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81864d56)
Location: include/linux/rcupdate.h:946
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/padata.c (ffffffff811abd02)
Location: include/linux/rcupdate.h:951
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff817b2b3f)
Location: include/linux/rcupdate.h:951
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff817bc8f6)
Location: include/linux/rcupdate.h:951
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (ffffffff817f0224)
Location: include/linux/rcupdate.h:951
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff817f90fb)
Location: include/linux/rcupdate.h:951
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff8183d0f6)
Location: include/linux/rcupdate.h:951
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv6/ip6_output.c (ffffffff81863d0e)
Location: include/linux/rcupdate.h:951
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff8186aad6)
Location: include/linux/rcupdate.h:951
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
```
```
In net/ipv6/route.c (ffffffff81874dca)
Location: include/linux/rcupdate.h:951
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81879c36)
Location: include/linux/rcupdate.h:951
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81897436)
Location: include/linux/rcupdate.h:951
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/padata.c (ffffffff811b3162)
Location: include/linux/rcupdate.h:685
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff817d034e)
Location: include/linux/rcupdate.h:685
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff817dafc6)
Location: include/linux/rcupdate.h:685
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (ffffffff818102ba)
Location: include/linux/rcupdate.h:685
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81819513)
Location: include/linux/rcupdate.h:685
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff8185e7ab)
Location: include/linux/rcupdate.h:685
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv6/ip6_output.c (ffffffff818892c6)
Location: include/linux/rcupdate.h:685
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff8188f046)
Location: include/linux/rcupdate.h:685
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81899bda)
Location: include/linux/rcupdate.h:685
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff8189f696)
Location: include/linux/rcupdate.h:685
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818bd846)
Location: include/linux/rcupdate.h:685
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/padata.c (ffffffff811c6db2)
Location: include/linux/rcupdate.h:707
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff81849cae)
Location: include/linux/rcupdate.h:707
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81855776)
Location: include/linux/rcupdate.h:707
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (ffffffff8188f30e)
Location: include/linux/rcupdate.h:707
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81897b23)
Location: include/linux/rcupdate.h:707
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff818de80f)
Location: include/linux/rcupdate.h:707
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv6/ip6_output.c (ffffffff81909706)
Location: include/linux/rcupdate.h:707
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81910696)
Location: include/linux/rcupdate.h:707
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff8191f19d)
Location: include/linux/rcupdate.h:707
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81921c96)
Location: include/linux/rcupdate.h:707
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819408e6)
Location: include/linux/rcupdate.h:707
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/padata.c (ffffffff811e8195)
Location: include/linux/rcupdate.h:705
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff8189441b)
Location: include/linux/rcupdate.h:705
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff818a0d2f)
Location: include/linux/rcupdate.h:705
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (ffffffff818e36ef)
Location: include/linux/rcupdate.h:705
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff818ebe53)
Location: include/linux/rcupdate.h:705
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff8193537f)
Location: include/linux/rcupdate.h:705
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv6/ip6_output.c (ffffffff81960a19)
Location: include/linux/rcupdate.h:705
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81967ab5)
Location: include/linux/rcupdate.h:705
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81975828)
Location: include/linux/rcupdate.h:705
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff8197a086)
Location: include/linux/rcupdate.h:705
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819997df)
Location: include/linux/rcupdate.h:705
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/padata.c (ffffffff811f7d45)
Location: include/linux/rcupdate.h:676
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff818b4e3f)
Location: include/linux/rcupdate.h:676
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff818c36af)
Location: include/linux/rcupdate.h:676
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (ffffffff8191059f)
Location: include/linux/rcupdate.h:676
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81919bf3)
Location: include/linux/rcupdate.h:676
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81964d7f)
Location: include/linux/rcupdate.h:676
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv6/ip6_output.c (ffffffff81996d19)
Location: include/linux/rcupdate.h:676
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff8199d1a5)
Location: include/linux/rcupdate.h:676
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819ab478)
Location: include/linux/rcupdate.h:676
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff819afc76)
Location: include/linux/rcupdate.h:676
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d012f)
Location: include/linux/rcupdate.h:676
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/padata.c (ffffffff8120fbc5)
Location: include/linux/rcupdate.h:661
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff81901824)
Location: include/linux/rcupdate.h:661
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff8190f7a5)
Location: include/linux/rcupdate.h:661
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (ffffffff81973003)
Location: include/linux/rcupdate.h:661
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:661
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff819caad6)
Location: include/linux/rcupdate.h:661
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff819d4c79)
Location: include/linux/rcupdate.h:661
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a00b19)
Location: include/linux/rcupdate.h:661
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81a09375)
Location: include/linux/rcupdate.h:661
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a14e47)
Location: include/linux/rcupdate.h:661
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1ddea)
Location: include/linux/rcupdate.h:661
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3ee4f)
Location: include/linux/rcupdate.h:661
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/padata.c (ffffffff8121d5b9)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff81933b40)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81941e15)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (ffffffff819a9976)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81a016c6)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a0b7d9)
Location: include/linux/rcupdate.h:668
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a376e9)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81a40065)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a4ba37)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81a54a3a)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a75abf)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/padata.c (ffffffff8124a0c9)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff81a08699)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81a11fe2)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (ffffffff81a92da9)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81af06cd)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81afc24f)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d224)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81b3b3e0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81b41a87)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4cb7a)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b70145)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/bpf/cpumap.c (ffffffff8122ec83)
Location: include/linux/rcupdate.h:719
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/padata.c (ffffffff81254759)
Location: include/linux/rcupdate.h:719
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff81a09c5b)
Location: include/linux/rcupdate.h:719
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81a12342)
Location: include/linux/rcupdate.h:719
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81a2eb78)
Location: include/linux/rcupdate.h:719
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a9cc5a)
Location: include/linux/rcupdate.h:719
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:719
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81afd6bd)
Location: include/linux/rcupdate.h:719
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81b09a8f)
Location: include/linux/rcupdate.h:719
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b3bc34)
Location: include/linux/rcupdate.h:719
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81b4a0f0)
Location: include/linux/rcupdate.h:719
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81b50547)
Location: include/linux/rcupdate.h:719
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5b7d8)
Location: include/linux/rcupdate.h:719
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7ec75)
Location: include/linux/rcupdate.h:719
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_renew
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/bpf/cpumap.c (ffffffff81233b93)
Location: include/linux/rcupdate.h:726
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/padata.c (ffffffff81258cf9)
Location: include/linux/rcupdate.h:726
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff819f05ed)
Location: include/linux/rcupdate.h:726
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff819f8ec5)
Location: include/linux/rcupdate.h:726
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81a161ce)
Location: include/linux/rcupdate.h:726
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a87d1f)
Location: include/linux/rcupdate.h:726
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a90bb8)
Location: include/linux/rcupdate.h:726
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae8efc)
Location: include/linux/rcupdate.h:726
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81af48d1)
Location: include/linux/rcupdate.h:726
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81b29597)
Location: include/linux/rcupdate.h:726
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81b37305)
Location: include/linux/rcupdate.h:726
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81b3dc27)
Location: include/linux/rcupdate.h:726
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81b49c98)
Location: include/linux/rcupdate.h:726
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6d875)
Location: include/linux/rcupdate.h:726
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/bpf/cpumap.c (ffffffff8126defa)
Location: include/linux/rcupdate.h:737
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff81294949)
Location: include/linux/rcupdate.h:737
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff81aa1a48)
Location: include/linux/rcupdate.h:737
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81aaaaa5)
Location: include/linux/rcupdate.h:737
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81ac75ed)
Location: include/linux/rcupdate.h:737
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81b42250)
Location: include/linux/rcupdate.h:737
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81b4c00f)
Location: include/linux/rcupdate.h:737
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba8f1c)
Location: include/linux/rcupdate.h:737
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81bb515e)
Location: include/linux/rcupdate.h:737
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81beefc8)
Location: include/linux/rcupdate.h:737
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81bfdabc)
Location: include/linux/rcupdate.h:737
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81c04756)
Location: include/linux/rcupdate.h:737
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81c10af8)
Location: include/linux/rcupdate.h:737
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c356ff)
Location: include/linux/rcupdate.h:737
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/bpf/cpumap.c (ffffffff812bcd3d)
Location: include/linux/rcupdate.h:745
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff812ea379)
Location: include/linux/rcupdate.h:745
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff81c19c12)
Location: include/linux/rcupdate.h:745
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81c23955)
Location: include/linux/rcupdate.h:745
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81c43e78)
Location: include/linux/rcupdate.h:745
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81ccec58)
Location: include/linux/rcupdate.h:745
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81cd974e)
Location: include/linux/rcupdate.h:745
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3b986)
Location: include/linux/rcupdate.h:745
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81d48c5e)
Location: include/linux/rcupdate.h:745
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81d87695)
Location: include/linux/rcupdate.h:745
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81d9747d)
Location: include/linux/rcupdate.h:745
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81d9e880)
Location: include/linux/rcupdate.h:745
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81dabc97)
Location: include/linux/rcupdate.h:745
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd312f)
Location: include/linux/rcupdate.h:745
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/bpf/cpumap.c (ffffffff8132019d)
Location: include/linux/rcupdate.h:823
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff81354269)
Location: include/linux/rcupdate.h:823
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff81dcaba0)
Location: include/linux/rcupdate.h:823
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81dd598a)
Location: include/linux/rcupdate.h:823
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81df81c8)
Location: include/linux/rcupdate.h:823
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81e8eec3)
Location: include/linux/rcupdate.h:823
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81e99ece)
Location: include/linux/rcupdate.h:823
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81f04366)
Location: include/linux/rcupdate.h:823
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81f1224e)
Location: include/linux/rcupdate.h:823
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv6/ip6_output.c (ffffffff81f55415)
Location: include/linux/rcupdate.h:823
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81f66181)
Location: include/linux/rcupdate.h:823
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81f6d830)
Location: include/linux/rcupdate.h:823
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7b627)
Location: include/linux/rcupdate.h:823
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa46b4)
Location: include/linux/rcupdate.h:823
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/bpf/cpumap.c (ffffffff8135000f)
Location: include/linux/rcupdate.h:799
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff81385469)
Location: include/linux/rcupdate.h:799
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff81e3b81e)
Location: include/linux/rcupdate.h:799
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/ipv6/addrconf.c (ffffffff81fc6291)
Location: include/linux/rcupdate.h:799
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
```
In net/ipv6/route.c (ffffffff81fcf495)
Location: include/linux/rcupdate.h:799
Inline: True
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
In kernel/bpf/cpumap.c (ffffffff81377448)
Location: include/linux/rcupdate.h:800
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff813ae809)
Location: include/linux/rcupdate.h:800
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff81ef9654)
Location: include/linux/rcupdate.h:800
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c935)
Location: include/linux/rcupdate.h:800
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_start
```
```
In net/ipv6/addrconf.c (ffffffff82093874)
Location: include/linux/rcupdate.h:800
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
```
In net/ipv6/route.c (ffffffff8209ccf5)
Location: include/linux/rcupdate.h:800
Inline: True
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
In kernel/padata.c (ffff8000102aa064)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffff800010bd1c1c)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffff800010be2700)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (ffff800010c5954c)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffff800010c6359c)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9d14)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffff800010cc4edc)
Location: include/linux/rcupdate.h:668
Inline: True
```
```
In net/ipv6/ip6_output.c (ffff800010cfa2e0)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffff800010d012d4)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffff800010d11c7c)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffff800010d19f78)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3e454)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/padata.c (c04d8110)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (c0cec930)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (c0cfc64c)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (c0d69100)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (c0dc567c)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (c0dd09a4)
Location: include/linux/rcupdate.h:668
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (c0e08e58)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c0e15008)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (c0e1ee94)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (c0e4182c)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/padata.c (c00000000035c1d4)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (c000000000cb00e4)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (c000000000cc3a74)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (c000000000d5b2f0)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (c000000000dd2e48)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (c000000000de1250)
Location: include/linux/rcupdate.h:668
Inline: True
```
```
In net/ipv6/ip6_output.c (c000000000e1f2ac)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (c000000000e2b23c)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c000000000e3b2d0)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (c000000000e46ef8)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (c000000000e72cb4)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/padata.c (ffffffe0001d2f6c)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffe00075bad4)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffe000768326)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (ffffffe0007c31f8)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffe0007cabda)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffe000810800)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffe00081a246)
Location: include/linux/rcupdate.h:668
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffe000843cb2)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffe00084b1fe)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffe0008568c2)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffe00085dc36)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087aa94)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/padata.c (ffffffff81215c09)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff818d3b40)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff818e1de5)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (ffffffff819497e6)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff819a1466)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff819ab579)
Location: include/linux/rcupdate.h:668
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819d6d79)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff819df6f5)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819eb0c7)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff819f40ca)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a1514f)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/padata.c (ffffffff81208969)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff8188d9d0)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff8189bc25)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (ffffffff819032d6)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff8195af26)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81965039)
Location: include/linux/rcupdate.h:668
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81993b39)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff8199c4b5)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819a7e87)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff819b0e8a)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d1f0f)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/padata.c (ffffffff812139a9)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff81924b40)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81932e15)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b205)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:seq_start
  - net/netfilter/nfnetlink_log.c:instance_lookup_get
```
```
In net/ipv4/route.c (ffffffff819b3fb6)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0bd06)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a15e19)
Location: include/linux/rcupdate.h:668
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a417f9)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81a4a175)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a55b47)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5eb4a)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a7fbcf)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
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
In kernel/padata.c (ffffffff81222b29)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In net/core/dev.c (ffffffff81945fff)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81954745)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/ipv4/route.c (ffffffff819bd6a6)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/fib_semantics.c (ffffffff81a164f6)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81a20859)
Location: include/linux/rcupdate.h:668
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d459)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81a560b5)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a61b47)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6afca)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8c48f)
Location: include/linux/rcupdate.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
</details>
</li>
</ul>

## Differences
