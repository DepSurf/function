# Function: <code>rtnl_is_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81729aa0)
Location: net/core/rtnetlink.c:92
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
Direct callers:
  - net/core/gen_estimator.c:gen_estimator_active
  - net/core/dev.c:__dev_getfirstbyhwtype
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:netdev_rx_handler_register
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_set_alias
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:register_netdevice
  - net/core/ethtool.c:__ethtool_get_settings
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/fib_rules.c:fib_rules_event
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/cls_api.c:tcf_exts_change
  - net/sched/cls_api.c:tcf_exts_change
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/igmp.c:ip_mc_join_group
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_dec_group
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff81729aa0-ffffffff81729aba: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8179796b)
Location: net/core/rtnetlink.c:114
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
Direct callers:
  - net/core/gen_estimator.c:gen_estimator_active
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_rx_handler_register
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_set_alias
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:__dev_getfirstbyhwtype
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/fib_rules.c:fib_rules_event
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tcf_exts_change
  - net/sched/cls_api.c:tcf_exts_change
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:ip_mc_dec_group
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/switchdev/switchdev.c:switchdev_port_fwd_mark_set
  - net/switchdev/switchdev.c:switchdev_get_dev_by_nhs
  - net/switchdev/switchdev.c:call_switchdev_notifiers
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
**Symbols:**

```
ffffffff817935e0-ffffffff817935fa: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c56eb)
Location: net/core/rtnetlink.c:114
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
Direct callers:
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_rx_handler_register
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_set_alias
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:__dev_getfirstbyhwtype
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/fib_rules.c:fib_rules_event
  - net/sched/sch_generic.c:pfifo_fast_reset
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tcf_exts_change
  - net/sched/cls_api.c:tcf_exts_change
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:ip_mc_dec_group
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/switchdev/switchdev.c:call_switchdev_notifiers
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
**Symbols:**

```
ffffffff817c0eb0-ffffffff817c0ece: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e409b)
Location: net/core/rtnetlink.c:116
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
Direct callers:
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_set_alias
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:__dev_getfirstbyhwtype
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:__ethtool_get_link_ksettings
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/fib_rules.c:fib_rules_event
  - net/sched/sch_generic.c:pfifo_fast_reset
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tcf_exts_change
  - net/sched/cls_api.c:tcf_exts_change
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:ip_mc_dec_group
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
**Symbols:**

```
ffffffff817df680-ffffffff817df69e: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185f13a)
Location: net/core/rtnetlink.c:116
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_notification
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:__dev_getfirstbyhwtype
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:__ethtool_get_link_ksettings
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/sched/sch_generic.c:pfifo_fast_reset
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:ip_mc_dec_group
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:call_ipmr_mfc_entry_notifiers
  - net/ipv4/ipmr.c:call_ipmr_vif_entry_notifiers
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
**Symbols:**

```
ffffffff81859f50-ffffffff81859f6e: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ab293)
Location: net/core/rtnetlink.c:127
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_notification
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:__dev_getfirstbyhwtype
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:__ethtool_get_link_ksettings
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:__tcf_idr_release
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:ip_mc_dec_group
  - net/ipv4/igmp.c:__ip_mc_inc_group
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:mif6_delete
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
**Symbols:**

```
ffffffff818a57d0-ffffffff818a57ee: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ced1d)
Location: net/core/rtnetlink.c:127
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:__dev_getfirstbyhwtype
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:__ethtool_get_link_ksettings
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:ip_mc_dec_group
  - net/ipv4/igmp.c:__ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:mif6_delete
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
**Symbols:**

```
ffffffff818c8d60-ffffffff818c8d7e: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8191bad1)
Location: net/core/rtnetlink.c:122
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:dev_get_nest_level
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:__dev_getfirstbyhwtype
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_set_link_ksettings
  - net/core/ethtool.c:ethtool_get_link_ksettings
  - net/core/ethtool.c:__ethtool_get_link_ksettings
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/devlink.c:devlink_compat_switch_id_get
  - net/core/devlink.c:devlink_compat_phys_port_name_get
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:mif6_delete
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
**Symbols:**

```
ffffffff819159a0-ffffffff819159be: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8194e0f7)
Location: net/core/rtnetlink.c:122
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:__dev_getfirstbyhwtype
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_set_link_ksettings
  - net/core/ethtool.c:ethtool_get_link_ksettings
  - net/core/ethtool.c:__ethtool_get_link_ksettings
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/devlink.c:devlink_compat_phys_port_name_get
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:mif6_delete
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_attr_set
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
**Symbols:**

```
ffffffff81948540-ffffffff8194855a: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1fc83)
Location: net/core/rtnetlink.c:122
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_rx_handler_register
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:__dev_getfirstbyhwtype
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/devlink.c:devlink_compat_phys_port_name_get
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:qdisc_change
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/ioctl.c:ethtool_get_link_ksettings
  - net/ethtool/ioctl.c:__ethtool_get_link_ksettings
  - net/ethtool/netlink.c:ethtool_notify
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:ip_mc_rejoin_groups
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_gre_config
  - net/ipv6/addrconf.c:addrconf_sit_config
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:init_loopback
  - net/ipv6/addrconf.c:sit_add_v4_addrs
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_rejoin_groups
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
**Symbols:**

```
ffffffff81a18380-ffffffff81a1839a: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a205e3)
Location: net/core/rtnetlink.c:122
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:dev_xdp_uninstall
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_rx_handler_register
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/devlink.c:devlink_compat_phys_port_name_get
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:qdisc_change
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/ioctl.c:ethtool_get_link_ksettings
  - net/ethtool/ioctl.c:__ethtool_get_link_ksettings
  - net/ethtool/netlink.c:ethtool_notify
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:ip_mc_rejoin_groups
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/nexthop.c:call_nexthop_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_gre_config
  - net/ipv6/addrconf.c:addrconf_sit_config
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:init_loopback
  - net/ipv6/addrconf.c:sit_add_v4_addrs
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_rejoin_groups
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/xdp/xsk_buff_pool.c:__xp_assign_dev
  - net/xdp/xsk_buff_pool.c:xp_disable_drv_zc
```
**Symbols:**

```
ffffffff81a18450-ffffffff81a1846a: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a076b3)
Location: net/core/rtnetlink.c:122
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
  - net/core/rtnetlink.c:rtnl_af_lookup
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_rx_handler_register
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/devlink.c:devlink_compat_phys_port_name_get
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/ioctl.c:ethtool_get_link_ksettings
  - net/ethtool/ioctl.c:__ethtool_get_link_ksettings
  - net/ethtool/netlink.c:ethtool_notify
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:call_nexthop_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:sit_add_v4_addrs
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
  - net/xdp/xsk_buff_pool.c:xp_disable_drv_zc
```
**Symbols:**

```
ffffffff819ff320-ffffffff819ff33a: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab9b17)
Location: net/core/rtnetlink.c:122
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
  - net/core/rtnetlink.c:rtnl_af_lookup
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_rx_handler_register
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/devlink.c:devlink_compat_phys_port_name_get
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/ioctl.c:ethtool_get_link_ksettings
  - net/ethtool/ioctl.c:__ethtool_get_link_ksettings
  - net/ethtool/netlink.c:ethtool_notify
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:call_nexthop_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:add_v4_addrs
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_bridge_port_unoffload
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
  - net/xdp/xsk_buff_pool.c:xp_disable_drv_zc
```
**Symbols:**

```
ffffffff81ab1510-ffffffff81ab152a: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c33b18)
Location: net/core/rtnetlink.c:157
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
  - net/core/rtnetlink.c:rtnl_af_lookup
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_offload_xstats_push_delta
  - net/core/dev.c:netdev_offload_xstats_get
  - net/core/dev.c:netdev_offload_xstats_enabled
  - net/core/dev.c:netdev_offload_xstats_disable
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_rx_handler_register
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:dev_remove_pack
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/devlink.c:devlink_compat_phys_port_name_get
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/ioctl.c:ethtool_get_link_ksettings
  - net/ethtool/ioctl.c:__ethtool_get_link_ksettings
  - net/ethtool/netlink.c:ethtool_notify
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:call_nexthop_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:add_v4_addrs
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_bridge_port_unoffload
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
  - net/xdp/xsk_buff_pool.c:xp_disable_drv_zc
  - net/mctp/device.c:mctp_add_dev
  - net/mctp/route.c:mctp_route_remove_dev
  - net/mctp/route.c:mctp_route_remove
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_route_add
```
**Symbols:**

```
ffffffff81c2a6c0-ffffffff81c2a6e0: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de6f68)
Location: net/core/rtnetlink.c:158
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
  - net/core/rtnetlink.c:rtnl_af_lookup
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_offload_xstats_push_delta
  - net/core/dev.c:netdev_offload_xstats_get
  - net/core/dev.c:netdev_offload_xstats_enabled
  - net/core/dev.c:netdev_offload_xstats_disable
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_rx_handler_register
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:dev_remove_pack
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/devlink.c:devlink_compat_phys_port_name_get
  - net/core/devlink.c:__devlink_port_type_set
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/ioctl.c:ethtool_get_link_ksettings
  - net/ethtool/ioctl.c:__ethtool_get_link_ksettings
  - net/ethtool/netlink.c:ethtool_notify
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:call_nexthop_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:add_v4_addrs
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_bridge_port_unoffload
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
  - net/xdp/xsk_buff_pool.c:xp_disable_drv_zc
  - net/mctp/device.c:mctp_add_dev
  - net/mctp/route.c:mctp_route_remove_dev
  - net/mctp/route.c:mctp_route_remove
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_route_add
```
**Symbols:**

```
ffffffff81ddd450-ffffffff81ddd470: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e57f58)
Location: net/core/rtnetlink.c:161
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
  - net/core/rtnetlink.c:rtnl_af_lookup
Direct callers:
  - kernel/bpf/offload.c:bpf_dev_bound_netdev_unregister
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_offload_xstats_push_delta
  - net/core/dev.c:netdev_offload_xstats_get
  - net/core/dev.c:netdev_offload_xstats_enabled
  - net/core/dev.c:netdev_offload_xstats_disable
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_rx_handler_register
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:dev_remove_pack
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/dev_ioctl.c:dev_set_hwtstamp
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/failover.c:failover_event
  - net/core/failover.c:failover_event
  - net/core/failover.c:failover_slave_unregister
  - net/core/failover.c:failover_slave_register
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/ioctl.c:ethtool_get_link_ksettings
  - net/ethtool/ioctl.c:__ethtool_get_link_ksettings
  - net/ethtool/netlink.c:ethtool_notify
  - net/ethtool/mm.c:ethtool_dev_mm_supported
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:call_nexthop_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:add_v4_addrs
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/devlink/leftover.c:devlink_compat_phys_port_name_get
  - net/devlink/leftover.c:__devlink_port_type_set
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_bridge_port_unoffload
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
  - net/xdp/xsk_buff_pool.c:xp_disable_drv_zc
  - net/mctp/device.c:mctp_add_dev
  - net/mctp/route.c:mctp_route_remove_dev
  - net/mctp/route.c:mctp_route_remove
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_route_add
```
**Symbols:**

```
ffffffff81e4e1a0-ffffffff81e4e1c0: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f172a8)
Location: net/core/rtnetlink.c:162
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
  - net/core/rtnetlink.c:rtnl_af_lookup
Direct callers:
  - kernel/bpf/offload.c:bpf_dev_bound_netdev_unregister
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - kernel/bpf/tcx.c:tcx_link_update
  - kernel/bpf/tcx.c:tcx_link_release
  - kernel/bpf/tcx.c:tcx_link_release
  - kernel/bpf/tcx.c:tcx_link_release
  - kernel/bpf/tcx.c:tcx_link_prog_attach
  - kernel/bpf/tcx.c:tcx_link_prog_attach
  - kernel/bpf/tcx.c:tcx_link_prog_attach
  - kernel/bpf/tcx.c:tcx_prog_query
  - kernel/bpf/tcx.c:tcx_uninstall
  - kernel/bpf/tcx.c:tcx_uninstall
  - kernel/bpf/tcx.c:tcx_prog_detach
  - kernel/bpf/tcx.c:tcx_prog_detach
  - kernel/bpf/tcx.c:tcx_prog_detach
  - kernel/bpf/tcx.c:tcx_prog_attach
  - kernel/bpf/tcx.c:tcx_prog_attach
  - drivers/net/netkit.c:netkit_link_attach
  - drivers/net/netkit.c:netkit_dev_fetch
  - drivers/net/netkit.c:netkit_entry_update
  - drivers/net/netkit.c:netkit_entry_fetch
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_offload_xstats_push_delta
  - net/core/dev.c:netdev_offload_xstats_get
  - net/core/dev.c:netdev_offload_xstats_enabled
  - net/core/dev.c:netdev_offload_xstats_disable
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netif_queue_set_napi
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_rx_handler_register
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:dev_remove_pack
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/dev_ioctl.c:dev_set_hwtstamp
  - net/core/dev_ioctl.c:dev_set_hwtstamp_phylib
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/failover.c:failover_event
  - net/core/failover.c:failover_event
  - net/core/failover.c:failover_slave_unregister
  - net/core/failover.c:failover_slave_register
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/ioctl.c:ethtool_get_link_ksettings
  - net/ethtool/ioctl.c:__ethtool_get_link_ksettings
  - net/ethtool/common.c:ethtool_set_ethtool_phy_ops
  - net/ethtool/netlink.c:ethtool_notify
  - net/ethtool/mm.c:ethtool_dev_mm_supported
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:call_nexthop_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:add_v4_addrs
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/devlink/port.c:devlink_compat_phys_port_name_get
  - net/devlink/port.c:__devlink_port_type_set
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_bridge_port_replay
  - net/switchdev/switchdev.c:switchdev_bridge_port_unoffload
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_act_is_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
  - net/xdp/xsk_buff_pool.c:xp_disable_drv_zc
  - net/mctp/device.c:mctp_add_dev
  - net/mctp/route.c:mctp_route_remove_dev
  - net/mctp/route.c:mctp_route_remove
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_route_add
```
**Symbols:**

```
ffffffff81f0cf00-ffffffff81f0cf20: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bf006c)
Location: net/core/rtnetlink.c:122
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:__dev_getfirstbyhwtype
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_set_link_ksettings
  - net/core/ethtool.c:ethtool_get_link_ksettings
  - net/core/ethtool.c:__ethtool_get_link_ksettings
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/devlink.c:devlink_compat_phys_port_name_get
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_delete
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_attr_set
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
**Symbols:**

```
ffff800010bea100-ffff800010bea12c: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d0869c)
Location: net/core/rtnetlink.c:122
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:__dev_getfirstbyhwtype
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:__ethtool_get_link_ksettings
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/devlink.c:devlink_compat_phys_port_name_get
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_delete
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_attr_set
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
**Symbols:**

```
c0d02a6c-c0d02a90: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cd4520)
Location: net/core/rtnetlink.c:122
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:__dev_getfirstbyhwtype
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_set_link_ksettings
  - net/core/ethtool.c:ethtool_get_link_ksettings
  - net/core/ethtool.c:__ethtool_get_link_ksettings
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/devlink.c:devlink_compat_phys_port_name_get
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_delete
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_attr_set
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
**Symbols:**

```
c000000000ccc540-c000000000ccc580: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe000772228)
Location: net/core/rtnetlink.c:122
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:__dev_getfirstbyhwtype
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_set_link_ksettings
  - net/core/ethtool.c:ethtool_get_link_ksettings
  - net/core/ethtool.c:__ethtool_get_link_ksettings
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/devlink.c:devlink_compat_phys_port_name_get
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_delete
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_attr_set
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
**Symbols:**

```
ffffffe00076d9b4-ffffffe00076d9e0: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ee0c7)
Location: net/core/rtnetlink.c:122
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:__dev_getfirstbyhwtype
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_set_link_ksettings
  - net/core/ethtool.c:ethtool_get_link_ksettings
  - net/core/ethtool.c:__ethtool_get_link_ksettings
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/devlink.c:devlink_compat_phys_port_name_get
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:mif6_delete
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_attr_set
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
**Symbols:**

```
ffffffff818e8510-ffffffff818e852a: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a7f07)
Location: net/core/rtnetlink.c:122
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:__dev_getfirstbyhwtype
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_set_link_ksettings
  - net/core/ethtool.c:ethtool_get_link_ksettings
  - net/core/ethtool.c:__ethtool_get_link_ksettings
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/devlink.c:devlink_compat_phys_port_name_get
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ip_tunnel.c:__ip_tunnel_create
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:mif6_delete
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_attr_set
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
**Symbols:**

```
ffffffff818a2350-ffffffff818a236a: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8193f0f7)
Location: net/core/rtnetlink.c:122
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:__dev_getfirstbyhwtype
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_set_link_ksettings
  - net/core/ethtool.c:ethtool_get_link_ksettings
  - net/core/ethtool.c:__ethtool_get_link_ksettings
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/devlink.c:devlink_compat_phys_port_name_get
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:mif6_delete
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_attr_set
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
**Symbols:**

```
ffffffff81939540-ffffffff8193955a: rtnl_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int rtnl_is_locked();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819609c7)
Location: net/core/rtnetlink.c:122
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_ndo
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
  - net/core/dev.c:netdev_master_upper_dev_get
  - net/core/dev.c:netdev_has_any_upper_dev
  - net/core/dev.c:netdev_has_upper_dev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netdev_is_rx_handler_busy
  - net/core/dev.c:netif_set_real_num_rx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_get_by_flags
  - net/core/dev.c:__dev_getfirstbyhwtype
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_set_link_ksettings
  - net/core/ethtool.c:ethtool_get_link_ksettings
  - net/core/ethtool.c:__ethtool_get_link_ksettings
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/netpoll.c:__netpoll_free
  - net/core/fib_rules.c:fib_rules_event
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/devlink.c:devlink_compat_phys_port_name_get
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/sch_fifo.c:qdisc_reset_queue
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/devinet.c:inet_ifa_byprefix
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_hash_remove
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_notifier.c:fib4_seq_read
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:ipmr_seq_read
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_init_vif_indev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/addrconf.c:addrconf_add_dev
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_seq_read
  - net/ipv6/ip6mr.c:mif6_delete
  - net/8021q/vlan_core.c:vlan_uses_dev
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_for_each
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_attr_set
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
**Symbols:**

```
ffffffff8195ac20-ffffffff8195ac3a: rtnl_is_locked (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
