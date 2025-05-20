# Function: <code>_raw_write_lock_bh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81824180)
Location: kernel/locking/spinlock.c:317
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/neighbour.c:neigh_parms_release
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:pneigh_delete
  - net/core/rtnetlink.c:set_operstate
  - net/core/rtnetlink.c:do_setlink
  - net/core/link_watch.c:rfc2863_policy
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk_done
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81824180-ffffffff818241ab: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8189ee30)
Location: kernel/locking/spinlock.c:317
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_parms_release
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk_done
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff8189ee30-ffffffff8189ee5b: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff818d42f0)
Location: kernel/locking/spinlock.c:317
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_parms_release
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff818d42f0-ffffffff818d431b: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8190b490)
Location: kernel/locking/spinlock.c:317
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff8190b490-ffffffff8190b4bc: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81995810)
Location: kernel/locking/spinlock.c:310
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:sock_map_delete_elem
  - kernel/bpf/sockmap.c:sock_map_free
  - kernel/bpf/sockmap.c:smap_data_ready
  - kernel/bpf/sockmap.c:smap_state_change
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81995810-ffffffff8199583c: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff819f1d50)
Location: kernel/locking/spinlock.c:310
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:sock_map_delete_elem
  - kernel/bpf/sockmap.c:smap_data_ready
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/core/link_watch.c:rfc2863_policy
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff819f1d50-ffffffff819f1d7c: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a2d300)
Location: kernel/locking/spinlock.c:310
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/core/link_watch.c:rfc2863_policy
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/sock_map.c:sock_map_unref
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81a2d300-ffffffff81a2d32a: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a9d450)
Location: kernel/locking/spinlock.c:317
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/core/link_watch.c:rfc2863_policy
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/sock_map.c:sock_map_unref
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81a9d450-ffffffff81a9d479: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81ad4c30)
Location: kernel/locking/spinlock.c:317
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/core/link_watch.c:rfc2863_policy
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/sock_map.c:sock_map_unref
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81ad4c30-ffffffff81ad4c59: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81bccbc0)
Location: kernel/locking/spinlock.c:317
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/neighbour.c:neigh_forced_gc
  - net/core/neighbour.c:neigh_update_gc_list
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_del_link
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
**Symbols:**

```
ffffffff81bccbc0-ffffffff81bccbe9: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81c45780)
Location: kernel/locking/spinlock.c:317
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_bridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_bridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_bridge_channels
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/neighbour.c:neigh_forced_gc
  - net/core/neighbour.c:neigh_update_gc_list
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_init
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_del_link
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
**Symbols:**

```
ffffffff81c45780-ffffffff81c457a9: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81c389f0)
Location: kernel/locking/spinlock.c:317
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_init
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
**Symbols:**

```
ffffffff81c389f0-ffffffff81c38a19: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81d572d0)
Location: kernel/locking/spinlock.c:322
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_init
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
**Symbols:**

```
ffffffff81d572d0-ffffffff81d572f9: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81f29f10)
Location: kernel/locking/spinlock.c:332
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - net/core/sock.c:sk_common_release
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_managed_work
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_init
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/subflow.c:mptcp_sock_destruct
  - net/mctp/af_mctp.c:mctp_pf_create
```
**Symbols:**

```
ffffffff81f29f10-ffffffff81f29f4d: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff820d5ed0)
Location: kernel/locking/spinlock.c:332
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - net/core/sock.c:sk_common_release
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_managed_work
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_init
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/af_inet.c:inet_accept
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mctp/af_mctp.c:mctp_pf_create
```
**Symbols:**

```
ffffffff820d5ed0-ffffffff820d5f0d: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff82159350)
Location: kernel/locking/spinlock.c:332
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - net/core/sock.c:sk_common_release
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_managed_work
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_init
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/af_inet.c:__inet_accept
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close
  - net/mctp/af_mctp.c:mctp_pf_create
```
**Symbols:**

```
ffffffff82159350-ffffffff8215938d: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8223cbd0)
Location: kernel/locking/spinlock.c:332
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - net/core/sock.c:sk_common_release
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_managed_work
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_init
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/af_inet.c:__inet_accept
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close
  - net/mctp/af_mctp.c:mctp_pf_create
```
**Symbols:**

```
ffffffff8223cbd0-ffffffff8223cc0d: _raw_write_lock_bh (STB_GLOBAL)
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
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (c0e9f234)
Location: kernel/locking/spinlock.c:317
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/core/link_watch.c:rfc2863_policy
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
c0e9f234-c0e9f288: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (c000000000eea3b0)
Location: kernel/locking/spinlock.c:317
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/sock_map.c:sock_map_unref
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
c000000000eea3b0-c000000000eea494: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffe0008c968a)
Location: kernel/locking/spinlock.c:317
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/sock_map.c:sock_map_unref
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffe0008c968a-ffffffe0008c96c8: _raw_write_lock_bh (STB_GLOBAL)
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
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a73aa0)
Location: kernel/locking/spinlock.c:317
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/core/link_watch.c:rfc2863_policy
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/sock_map.c:sock_map_unref
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81a73aa0-ffffffff81a73ac9: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a2feb0)
Location: kernel/locking/spinlock.c:317
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/core/link_watch.c:rfc2863_policy
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/sock_map.c:sock_map_unref
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81a2feb0-ffffffff81a2fed9: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81adfeb0)
Location: kernel/locking/spinlock.c:317
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/core/link_watch.c:rfc2863_policy
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/sock_map.c:sock_map_unref
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81adfeb0-ffffffff81adfed9: _raw_write_lock_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _raw_write_lock_bh(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81aec800)
Location: kernel/locking/spinlock.c:317
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/core/link_watch.c:rfc2863_policy
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/sock_map.c:sock_map_unref
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/ip6_fib.c:ipv6_route_seq_setup_walk
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81aec800-ffffffff81aec829: _raw_write_lock_bh (STB_GLOBAL)
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
