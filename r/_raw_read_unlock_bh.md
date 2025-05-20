# Function: <code>_raw_read_unlock_bh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81824030)
Location: kernel/locking/spinlock.c:277
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - net/core/sock.c:sock_i_uid
  - net/core/sock.c:sock_i_uid
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_ino
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
  - net/xfrm/xfrm_policy.c:xfrm_spd_getinfo
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/addrconf.c:ipv6_count_addresses
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_up
```
**Symbols:**

```
ffffffff81824030-ffffffff81824052: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8189ece0)
Location: kernel/locking/spinlock.c:277
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/sock.c:sock_i_uid
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
  - net/xfrm/xfrm_policy.c:xfrm_spd_getinfo
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_count_addresses
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
**Symbols:**

```
ffffffff8189ece0-ffffffff8189ed02: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff818d41a0)
Location: kernel/locking/spinlock.c:277
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/sock.c:sock_i_uid
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_count_addresses
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
**Symbols:**

```
ffffffff818d41a0-ffffffff818d41c2: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8190b330)
Location: kernel/locking/spinlock.c:277
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_count_addresses
  - net/ipv6/addrconf.c:ipv6_count_addresses
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
**Symbols:**

```
ffffffff8190b330-ffffffff8190b352: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff819956e0)
Location: kernel/locking/spinlock.c:270
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
**Symbols:**

```
ffffffff819956e0-ffffffff81995702: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff819f1c20)
Location: kernel/locking/spinlock.c:270
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
**Symbols:**

```
ffffffff819f1c20-ffffffff819f1c42: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a2d250)
Location: kernel/locking/spinlock.c:270
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
**Symbols:**

```
ffffffff81a2d250-ffffffff81a2d272: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a9d3e0)
Location: kernel/locking/spinlock.c:277
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
**Symbols:**

```
ffffffff81a9d3e0-ffffffff81a9d402: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81ad4bc0)
Location: kernel/locking/spinlock.c:277
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
**Symbols:**

```
ffffffff81ad4bc0-ffffffff81ad4be2: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81bccab0)
Location: kernel/locking/spinlock.c:277
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/neighbour.c:pneigh_dump_table
  - net/core/neighbour.c:pneigh_dump_table
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_get_idx
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_get_idx
  - net/ipv6/mcast.c:ipv6_mc_rejoin_groups
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
**Symbols:**

```
ffffffff81bccab0-ffffffff81bccad2: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81c45610)
Location: kernel/locking/spinlock.c:277
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/neighbour.c:pneigh_dump_table
  - net/core/neighbour.c:pneigh_dump_table
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_get_idx
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_get_idx
  - net/ipv6/mcast.c:ipv6_mc_rejoin_groups
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
**Symbols:**

```
ffffffff81c45610-ffffffff81c45632: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81c388a0)
Location: kernel/locking/spinlock.c:277
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
```
**Symbols:**

```
ffffffff81c388a0-ffffffff81c388c2: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81d57180)
Location: kernel/locking/spinlock.c:282
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
```
**Symbols:**

```
ffffffff81d57180-ffffffff81d571a2: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81f29d90)
Location: kernel/locking/spinlock.c:282
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_req_get
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
```
**Symbols:**

```
ffffffff81f29d90-ffffffff81f29dbc: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff820d5ce0)
Location: kernel/locking/spinlock.c:282
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_req_get
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
```
**Symbols:**

```
ffffffff820d5ce0-ffffffff820d5d0c: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff821590c0)
Location: kernel/locking/spinlock.c:282
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_uid
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_req_get
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_inherit_eui64
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
```
**Symbols:**

```
ffffffff821590c0-ffffffff821590ec: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8223c940)
Location: kernel/locking/spinlock.c:282
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_uid
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_req_get
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_inherit_eui64
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
```
**Symbols:**

```
ffffffff8223c940-ffffffff8223c96c: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (c0e9f378)
Location: kernel/locking/spinlock.c:277
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ac6_get_next
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mcf_get_next
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:igmp6_mc_get_next
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
**Symbols:**

```
c0e9f378-c0e9f3cc: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (c000000000eea210)
Location: kernel/locking/spinlock.c:277
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:igmp6_mc_get_next
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
**Symbols:**

```
c000000000eea210-c000000000eea264: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffe0008c96c8)
Location: kernel/locking/spinlock.c:277
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:igmp6_mc_get_next
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
**Symbols:**

```
ffffffe0008c96c8-ffffffe0008c9706: _raw_read_unlock_bh (STB_GLOBAL)
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
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a73a30)
Location: kernel/locking/spinlock.c:277
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
**Symbols:**

```
ffffffff81a73a30-ffffffff81a73a52: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a2fd90)
Location: kernel/locking/spinlock.c:277
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
**Symbols:**

```
ffffffff81a2fd90-ffffffff81a2fdb2: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81adfe40)
Location: kernel/locking/spinlock.c:277
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/netfilter/nfnetlink_log.c:__build_packet_message
  - net/netfilter/nfnetlink_log.c:__build_packet_message
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
**Symbols:**

```
ffffffff81adfe40-ffffffff81adfe62: _raw_read_unlock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81aec730)
Location: kernel/locking/spinlock.c:277
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
**Symbols:**

```
ffffffff81aec730-ffffffff81aec752: _raw_read_unlock_bh (STB_GLOBAL)
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
