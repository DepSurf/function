# Function: <code>__in_dev_get_rcu</code>

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
In net/core/neighbour.c (ffffffff8172442b)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/ipv4/route.c (ffffffff817533e1)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff8175893c)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/udp.c (ffffffff8178a72f)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff8178c36a)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff8178f4c6)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv4/igmp.c (ffffffff81795087)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff8179aa9a)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_trie.c (ffffffff8179ee17)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/ipmr.c (ffffffff817a7dbd)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
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
In net/core/neighbour.c (ffffffff8178e311)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/ipv4/route.c (ffffffff817c259b)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff817c4cee)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/udp.c (ffffffff817f7f8c)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff817fa08c)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff818003dc)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff818035ae)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff818086ca)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_trie.c (ffffffff8180c7fe)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/neighbour.c (ffffffff817bb7aa)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/ipv4/route.c (ffffffff817f0c4b)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff817f480e)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/udp.c (ffffffff81828e2c)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff8182af5c)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff8183133c)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff81834548)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff8183977a)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_trie.c (ffffffff8183da7e)
Location: include/linux/inetdevice.h:203
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/neighbour.c (ffffffff817d9ef4)
Location: include/linux/inetdevice.h:211
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/ipv4/route.c (ffffffff818123ed)
Location: include/linux/inetdevice.h:211
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81814c55)
Location: include/linux/inetdevice.h:211
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/udp.c (ffffffff8184a108)
Location: include/linux/inetdevice.h:211
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff8184c1ac)
Location: include/linux/inetdevice.h:211
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff81852883)
Location: include/linux/inetdevice.h:211
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff81856014)
Location: include/linux/inetdevice.h:211
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff8185acea)
Location: include/linux/inetdevice.h:211
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_trie.c (ffffffff8185f301)
Location: include/linux/inetdevice.h:211
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/neighbour.c (ffffffff81854694)
Location: include/linux/inetdevice.h:214
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/ipv4/route.c (ffffffff81891a0d)
Location: include/linux/inetdevice.h:214
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81893e0f)
Location: include/linux/inetdevice.h:214
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/udp.c (ffffffff818c9ccb)
Location: include/linux/inetdevice.h:214
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff818cbe5c)
Location: include/linux/inetdevice.h:214
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff818d2693)
Location: include/linux/inetdevice.h:214
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff818d5ea4)
Location: include/linux/inetdevice.h:214
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff818dac1a)
Location: include/linux/inetdevice.h:214
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff818ddfd8)
Location: include/linux/inetdevice.h:214
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffffffff818df366)
Location: include/linux/inetdevice.h:214
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/neighbour.c (ffffffff8189fce3)
Location: include/linux/inetdevice.h:215
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/filter.c (ffffffff818b4137)
Location: include/linux/inetdevice.h:215
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff818e5966)
Location: include/linux/inetdevice.h:215
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff818e8088)
Location: include/linux/inetdevice.h:215
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/udp.c (ffffffff8191fefc)
Location: include/linux/inetdevice.h:215
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff8192233c)
Location: include/linux/inetdevice.h:215
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff81928c56)
Location: include/linux/inetdevice.h:215
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff8192dc80)
Location: include/linux/inetdevice.h:215
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81931ba5)
Location: include/linux/inetdevice.h:215
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81934acf)
Location: include/linux/inetdevice.h:215
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffffffff819375db)
Location: include/linux/inetdevice.h:215
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/neighbour.c (ffffffff818c26b3)
Location: include/linux/inetdevice.h:218
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/filter.c (ffffffff818d98e7)
Location: include/linux/inetdevice.h:218
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81912876)
Location: include/linux/inetdevice.h:218
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81914eec)
Location: include/linux/inetdevice.h:218
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194eb5a)
Location: include/linux/inetdevice.h:218
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff8195116c)
Location: include/linux/inetdevice.h:218
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff81957f3c)
Location: include/linux/inetdevice.h:218
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff8195b710)
Location: include/linux/inetdevice.h:218
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81961405)
Location: include/linux/inetdevice.h:218
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff8196441c)
Location: include/linux/inetdevice.h:218
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_trie.c (ffffffff81966fcb)
Location: include/linux/inetdevice.h:218
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/core/neighbour.c (ffffffff8191080c)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/filter.c (ffffffff8192a2a5)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81974f8c)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819773cd)
Location: include/linux/inetdevice.h:217
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b3321)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff819b5a2c)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff819bc996)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff819c03e7)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff819c5be5)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
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
In net/core/neighbour.c (ffffffff81942e7c)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/filter.c (ffffffff8195c635)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819ab9ac)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819add5d)
Location: include/linux/inetdevice.h:217
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819ea0a4)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff819ec74c)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff819f3686)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff819f6f87)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff819fc795)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
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
In net/core/neighbour.c (ffffffff81a133e8)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/filter.c (ffffffff81a2de15)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a95c6d)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81a979d7)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/udp.c (ffffffff81ad7bce)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff81ada6dc)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff81ae1069)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff81ae69e7)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeb505)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
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
In net/core/neighbour.c (ffffffff81a137c8)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/filter.c (ffffffff81a2fd57)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a9fcf1)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81aa1937)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/udp.c (ffffffff81ae421e)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff81ae717c)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff81aedee9)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff81af38b7)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81af8405)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
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
In net/core/neighbour.c (ffffffff819f98cb)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/filter.c (ffffffff81a16ea7)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a8ac31)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81a8c908)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/udp.c (ffffffff81acf4eb)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff81ad243c)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff81ad50df)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_echo
```
```
In net/ipv4/devinet.c (ffffffff81ad967e)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff81adef17)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae3b25)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
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
In net/core/neighbour.c (ffffffff81aab2f6)
Location: include/linux/inetdevice.h:226
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/filter.c (ffffffff81ac9117)
Location: include/linux/inetdevice.h:226
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81b45b23)
Location: include/linux/inetdevice.h:226
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81b47a38)
Location: include/linux/inetdevice.h:226
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/udp.c (ffffffff81b8df14)
Location: include/linux/inetdevice.h:226
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff81b9108c)
Location: include/linux/inetdevice.h:226
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff81b9313e)
Location: include/linux/inetdevice.h:226
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81b986f1)
Location: include/linux/inetdevice.h:226
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff81b9e3f7)
Location: include/linux/inetdevice.h:226
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba3435)
Location: include/linux/inetdevice.h:226
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
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
In net/core/neighbour.c (ffffffff81c22a84)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/filter.c (ffffffff81c46080)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81cd290f)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81cd4ca0)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/udp.c (ffffffff81d1eec8)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff81d223fc)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff81d257de)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81d2a4de)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff81d3070d)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81d35c8c)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
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
In net/core/neighbour.c (ffffffff81dd5c64)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/filter.c (ffffffff81dfa550)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81e92bdf)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81e94fd0)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/udp.c (ffffffff81ee5fd8)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff81ee988c)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff81eed06e)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81ef1fde)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff81ef886d)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81efe27c)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
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
In net/core/neighbour.c (ffffffff81e46a36)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/filter.c (ffffffff81e6e100)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81ef137f)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81ef37a0)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/udp.c (ffffffff81f457d8)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff81f491bc)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff81f4ca0e)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81f51a75)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff81f582dd)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5dd0f)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
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
In net/core/neighbour.c (ffffffff81f056d9)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/filter.c (ffffffff81f2d9d0)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81fb54cf)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81fb7730)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/udp.c (ffffffff8200b928)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff8200f34c)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff82012b1e)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff82017d38)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff8201e7a0)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff820242cf)
Location: include/linux/inetdevice.h:231
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
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
In net/core/neighbour.c (ffff800010be38bc)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/filter.c (ffff800010bfe474)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffff800010c5bb64)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffff800010c5e5c0)
Location: include/linux/inetdevice.h:217
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9f878)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffff800010ca22c4)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffff800010ca9988)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffff800010cb0378)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffff800010cb4bdc)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
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
In net/core/neighbour.c (c0cfc03c)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/filter.c (c0d18be8)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c0d6b194)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (c0d6d554)
Location: include/linux/inetdevice.h:217
Inline: True
```
```
In net/ipv4/udp.c (c0dacbc8)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (c0daf08c)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (c0db6124)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (c0db95e4)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mcf_get_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (c0dc0580)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
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
In net/core/neighbour.c (c000000000cc2790)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/filter.c (c000000000ce609c)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c000000000d5dc24)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (c000000000d60a40)
Location: include/linux/inetdevice.h:217
Inline: True
```
```
In net/ipv4/udp.c (c000000000db2458)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (c000000000db5810)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (c000000000dbee10)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (c000000000dc4308)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (c000000000dcbe04)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
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
In net/core/neighbour.c (ffffffe0007677ee)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/filter.c (ffffffe0007804f6)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffe0007c4d34)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffe0007c6998)
Location: include/linux/inetdevice.h:217
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007fc3be)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffe0007fe318)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffe0008044f2)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffe000807f5a)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffe00080c784)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
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
In net/core/neighbour.c (ffffffff818e2e4c)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/filter.c (ffffffff818fc605)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff8194b81c)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff8194dbcd)
Location: include/linux/inetdevice.h:217
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81989f14)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff8198c57c)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff81993426)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff81996d27)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff8199c535)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
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
In net/core/neighbour.c (ffffffff8189cc8c)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/filter.c (ffffffff818b6435)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff8190530c)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819076bd)
Location: include/linux/inetdevice.h:217
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819439d4)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff8194603c)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff8194cee6)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff819507e7)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81955ff5)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
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
In net/core/neighbour.c (ffffffff81933e7c)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/filter.c (ffffffff8194d635)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819b5fec)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819b839d)
Location: include/linux/inetdevice.h:217
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f46e4)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff819f6d8c)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff819fdcc6)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff81a015c7)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81a06dd5)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
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
In net/core/neighbour.c (ffffffff81955584)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/filter.c (ffffffff8196eff7)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819bf7ec)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819c1bfd)
Location: include/linux/inetdevice.h:217
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fe8a4)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff81a00fac)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff81a08042)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
```
```
In net/ipv4/igmp.c (ffffffff81a0bab7)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81a11485)
Location: include/linux/inetdevice.h:217
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
</details>
</li>
</ul>

## Differences
