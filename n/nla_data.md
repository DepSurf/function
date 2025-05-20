# Function: <code>nla_data</code>

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
In kernel/taskstats.c (ffffffff8113e325)
Location: include/net/netlink.h:669
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffff814158fb)
Location: include/net/netlink.h:669
Inline: True
Inline callers:
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:nla_strcmp
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In net/core/neighbour.c (ffffffff817294a7)
Location: include/net/netlink.h:669
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81729b8e)
Location: include/net/netlink.h:669
Inline: True
Inline callers:
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_fdb_del
```
```
In net/core/filter.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In net/sched/ematch.c (ffffffff81749a6a)
Location: include/net/netlink.h:669
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/netlink/genetlink.c (ffffffff817500ed)
Location: include/net/netlink.h:669
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8178f8a9)
Location: include/net/netlink.h:669
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff817ca270)
Location: include/net/netlink.h:669
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:extract_addr
  - net/ipv6/addrconf.c:extract_addr
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_set_link_af
```
```
In net/ipv6/addrlabel.c (ffffffff817d2c8f)
Location: include/net/netlink.h:669
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff81809dab)
Location: include/net/netlink.h:669
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:669
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818103e9)
Location: include/net/netlink.h:669
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/dcb/dcbnl.c (ffffffff81814edf)
Location: include/net/netlink.h:669
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In kernel/taskstats.c (ffffffff81146975)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffff8145d87f)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff814d85c2)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/core/neighbour.c (ffffffff817918a6)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81794762)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff8179c4db)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/core/filter.c:__skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff8179eacf)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817afbe6)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff817b4202)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/sched/ematch.c (ffffffff817b698b)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/netlink/genetlink.c (ffffffff817bc0ce)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff817fcf50)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81807b36)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818122a6)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81817939)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff8183fb22)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:extract_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81840928)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81842d19)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/wireless/wext-core.c (ffffffff8187b8ab)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8187fa2f)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81882219)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81882fd5)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81886d29)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/switchdev/switchdev.c (ffffffff8188b7be)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
  - net/switchdev/switchdev.c:switchdev_port_br_afspec
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
In kernel/taskstats.c (ffffffff81150855)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffff8147c33f)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff814facaa)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/core/neighbour.c (ffffffff817bf3f6)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff817c1fe2)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff817c9789)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/core/filter.c:__skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff817cd49f)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff817d9c68)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/sch_api.c (ffffffff817df2d6)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff817e3ab2)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:nla_memdup_cookie
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/sched/ematch.c (ffffffff817e641b)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/netlink/genetlink.c (ffffffff817ebacc)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8182deb0)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81838be7)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818437b6)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818491a6)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff81871752)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:extract_addr
```
```
In net/ipv6/addrlabel.c (ffffffff818725a8)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81874a79)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff818996e6)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a3f16)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:nla_put_srh
```
```
In net/wireless/wext-core.c (ffffffff818b016b)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b42df)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b6ac9)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b787a)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff818bb599)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/switchdev/switchdev.c (ffffffff818bfaa4)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
  - net/switchdev/switchdev.c:switchdev_port_br_afspec
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
In kernel/taskstats.c (ffffffff81152e64)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffff81485601)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff8150a1c8)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:689
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/core/neighbour.c (ffffffff817ddcd4)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff817e0763)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff817e86d6)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/core/filter.c:__skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff817ec7ff)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff817f92a5)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/sch_api.c (ffffffff817fe766)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/cls_api.c (ffffffff81802a6a)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
```
```
In net/sched/act_api.c (ffffffff818033f2)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/sched/ematch.c (ffffffff81805f6a)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8180ba31)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8184fb30)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81859e9f)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8186500e)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8186c7af)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff818964c7)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:extract_addr
  - net/ipv6/addrconf.c:extract_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81897334)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff818983c6)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff818bf8e6)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ip6mr.c (ffffffff818c1895)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca619)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/wireless/wext-core.c (ffffffff818d6b19)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818dac8f)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dd392)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818dde4a)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff818e1f6e)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/switchdev/switchdev.c (ffffffff818e62cb)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
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
In kernel/taskstats.c (ffffffff8115f684)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffff814c1791)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff8154c6c8)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/core/neighbour.c (ffffffff81856ac4)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8185afe7)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff81863a36)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/core/filter.c:__skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff818689df)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81876bb5)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/sch_api.c (ffffffff8187c3f6)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/cls_api.c (ffffffff81880d4d)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
```
```
In net/sched/act_api.c (ffffffff81881872)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/sched/ematch.c (ffffffff81884c9a)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8188a9c1)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff818cf760)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff818d9da5)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e516e)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818ed095)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81917897)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:extract_addr
  - net/ipv6/addrconf.c:extract_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81917fe1)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81919776)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff819429b6)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ip6mr.c (ffffffff81944c16)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194dde9)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff8194f085)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:put_nla_srh
```
```
In net/wireless/wext-core.c (ffffffff8195c6e9)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8196086f)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81962f82)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81963a3a)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81967d0e)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In kernel/taskstats.c (ffffffff8116e695)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffff814f24c1)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff81582e08)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff817e6c45)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/core/neighbour.c (ffffffff818a1afc)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818a689c)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff818b1239)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff818b887b)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818c8372)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/sched/sch_api.c (ffffffff818cec52)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/cls_api.c (ffffffff818d451c)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff818d5338)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/sched/ematch.c (ffffffff818d87f6)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff818ddff1)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8192545d)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff819307b6)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193ba7d)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8194305c)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8196efd0)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:extract_addr
  - net/ipv6/addrconf.c:extract_addr
```
```
In net/ipv6/addrlabel.c (ffffffff8196f800)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81971263)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff8199b8e6)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ip6mr.c (ffffffff8199d92f)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7061)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff819a8361)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/wireless/wext-core.c (ffffffff819b5ec9)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819ba02a)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bc7a5)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bd516)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:695
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff819c153f)
Location: include/net/netlink.h:695
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:695
Inline: True
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
In kernel/taskstats.c (ffffffff8117c165)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffff81506201)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff8159af38)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:838
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81812ff5)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:838
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:838
Inline: True
```
```
In net/core/neighbour.c (ffffffff818c4c6c)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818ca0fc)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff818d5da3)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff818df4cb)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:838
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:838
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818f14e2)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/sched/sch_api.c (ffffffff818f9f52)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/cls_api.c (ffffffff819000e3)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81901f78)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:838
Inline: True
```
```
In net/sched/ematch.c (ffffffff81904fe6)
Location: include/net/netlink.h:838
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8190a9b1)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:838
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:838
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8195426d)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff8195fcb9)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:838
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196b76d)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:838
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:838
Inline: True
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:838
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819731f2)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff819a4b80)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:extract_addr
  - net/ipv6/addrconf.c:extract_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819a5410)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff819a7e67)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff819d22c6)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ip6mr.c (ffffffff819d4489)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819ddbc1)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff819deeb1)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/wireless/wext-core.c (ffffffff819ed189)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f12fa)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f39f5)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f4488)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:838
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff819f8a92)
Location: include/net/netlink.h:838
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:838
Inline: True
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
In kernel/taskstats.c (ffffffff81188ff5)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffff81534bc1)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff815cc5a7)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81855095)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/neighbour.c (ffffffff81910c8d)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff819170cf)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff81923591)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff8192db2b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81942e02)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffff81951c5b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/sched/sch_api.c (ffffffff819596ad)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/cls_api.c (ffffffff81960bdb)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff819630f8)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/ematch.c (ffffffff81966248)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8196bdb4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819b9aed)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff819c6561)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2314)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff819d4144)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819dccf2)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a07cdb)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:extract_addr
  - net/ipv6/addrconf.c:extract_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a118f4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a14c4b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81a410e6)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a43310)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4c741)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81a4da21)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/wireless/wext-core.c (ffffffff81a5c37d)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a605ae)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a62e28)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a63b71)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81a67fea)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1072
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
In kernel/taskstats.c (ffffffff81194f35)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffff815559f1)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff815ed827)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81886af5)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/neighbour.c (ffffffff81943a5d)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8194970f)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff819557c1)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff8195fdab)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81975e78)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81977db2)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffff8198869b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/sched/sch_api.c (ffffffff8198fb4d)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/act_api.c (ffffffff81999c78)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/ematch.c (ffffffff8199ccd8)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff819a2764)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819f1ded)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff819fd111)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a08e84)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a0acb4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a13d5b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a3e84b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:extract_addr
  - net/ipv6/addrconf.c:extract_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a48514)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a4b83b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81a77d66)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a79e70)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83311)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81a845f1)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/wireless/wext-core.c (ffffffff81a92faa)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a971de)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a99a08)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a9a721)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81a9e94a)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1072
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
In kernel/taskstats.c (ffffffff811aa6c9)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffff815de781)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff816993a7)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/core/neighbour.c (ffffffff81a147c5)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81a19a9f)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff81a283b4)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff81a3330b)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81a4aa71)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a4d0f7)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (ffffffff81a5169d)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_compat_running_version
  - net/core/devlink.c:__devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/core/bpf_sk_storage.c (ffffffff81a612f1)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81a6812d)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/sched/act_api.c (ffffffff81a730e8)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:nla_memdup_cookie
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/sched/ematch.c (ffffffff81a75f35)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81a7c790)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81a85e6e)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81a879b5)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a87c83)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/ethtool/wol.c (ffffffff81a89ba2)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/ethtool/cabletest.c (ffffffff81a8cc77)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81adfacd)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81aebbcb)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af93e2)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81afb217)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_check_attr_group
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b0212e)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81b3e929)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f3a2)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81b4188e)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81b71fe6)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ip6mr.c (ffffffff81b74640)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7df81)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f654)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/wireless/wext-core.c (ffffffff81b8e2ba)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b92f7c)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b95245)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b95f8c)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81b99738)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1124
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb3165)
Location: include/net/netlink.h:1124
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
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
In kernel/taskstats.c (ffffffff811a7c79)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffff815fbe21)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strscpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff816b6467)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/neighbour.c (ffffffff81a14ad5)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81a19c8f)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff81a28cd4)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff81a3567b)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81a506b1)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a52db7)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (ffffffff81a577ad)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_compat_running_version
  - net/core/devlink.c:__devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
  - net/core/devlink.c:devlink_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/core/bpf_sk_storage.c (ffffffff81a69be1)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81a7083d)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/sched/act_api.c (ffffffff81a7bca8)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
  - net/sched/act_api.c:nla_memdup_cookie
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/sched/ematch.c (ffffffff81a7ece5)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81a86b56)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81a8f7e8)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81a9133c)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a915f3)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/wol.c (ffffffff81a933e2)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/cabletest.c (ffffffff81a96387)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81aec94d)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81af8ac3)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06052)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81b088d7)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_check_attr_group
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b104bc)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81b4d4b9)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81b4de32)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81b5034e)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81b80d46)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ip6mr.c (ffffffff81b833b0)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8cf91)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f8c4)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/wireless/wext-core.c (ffffffff81b9df5a)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba2bcc)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba4ea5)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba5bfc)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81ba93fc)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7605)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
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
In kernel/taskstats.c (ffffffff811a85ad)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffff815dea61)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strscpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff81698517)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/neighbour.c (ffffffff819fb5d5)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81a00c8f)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff81a0ffc4)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff81a1c7cb)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81a355da)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a385b9)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (ffffffff81a4bf55)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_port_function_set
  - net/core/devlink.c:devlink_port_function_set
  - net/core/devlink.c:devlink_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/core/bpf_sk_storage.c (ffffffff81a52651)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81a5913d)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/sched/act_api.c (ffffffff81a648e8)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/sched/ematch.c (ffffffff81a67b35)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81a6f0c7)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81a78ec2)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81a7ab46)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a7b61b)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/wol.c (ffffffff81a7cdf1)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/cabletest.c (ffffffff81a7fe0f)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ethtool/fec.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/eeprom.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81ad687d)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae4223)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af18af)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81af59a1)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81afe0cb)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81b3b363)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81b3b8d2)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81b3e822)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81b6f896)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ip6mr.c (ffffffff81b7201a)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7be41)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81b7e494)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/wireless/wext-core.c (ffffffff81b8d05a)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b91cf1)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93fe0)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b94d6c)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81b9858c)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb8aa4)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
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
In kernel/taskstats.c (ffffffff811d220d)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffff8164a5e1)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strscpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff8170e297)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8191aaa4)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/neighbour.c (ffffffff81aad90c)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81ab304f)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff81ac2294)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff81acff8b)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81aeb1aa)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81aee429)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (ffffffff81b043a4)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_rate_parent_node_set
  - net/core/devlink.c:devlink_port_function_set
  - net/core/devlink.c:devlink_port_function_set
  - net/core/devlink.c:devlink_rate_node_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0b0c1)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81b1242d)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/sched/act_api.c (ffffffff81b1dbb8)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/sched/ematch.c (ffffffff81b210a5)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81b28b07)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81b33192)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81b34f64)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81b359b0)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/wol.c (ffffffff81b36fec)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/cabletest.c (ffffffff81b39bdf)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ethtool/fec.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/eeprom.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81b96503)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba3b73)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1dbf)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81bb62a1)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bbf35b)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81c01b63)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81c02162)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81c05172)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81c37946)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ioam6.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c4ca)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c46b81)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81c49ed4)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4bc16)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/wireless/wext-core.c (ffffffff81c59411)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5e611)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c60780)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c61585)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81c650e9)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff81c88074)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
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
In kernel/taskstats.c (ffffffff81206deb)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffff81760c6d)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strscpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff8183cc67)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6fef0)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/neighbour.c (ffffffff81c26571)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81c2cfed)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff81c3cbcc)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff81c4d797)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81c6da0d)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81c71314)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (ffffffff81c89cb2)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_linecard_set_doit
  - net/core/devlink.c:devlink_nl_rate_parent_node_set
  - net/core/devlink.c:devlink_port_function_set
  - net/core/devlink.c:devlink_port_function_set
  - net/core/devlink.c:devlink_rate_node_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/core/bpf_sk_storage.c (ffffffff81c91793)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81c99798)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_rtab
  - net/sched/sch_api.c:qdisc_get_rtab
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/sched/act_api.c (ffffffff81ca51b4)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/sched/ematch.c (ffffffff81ca9010)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/netlink/genetlink.c (ffffffff81cb1415)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81cbe382)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81cc0774)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81cc0bfc)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/wol.c (ffffffff81cc2992)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/cabletest.c (ffffffff81cc5a89)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ethtool/fec.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/eeprom.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ethtool/module.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81d26993)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81d36408)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d454e5)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81d49eab)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d540ed)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81d9b896)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81d9c0fc)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81d9f1f8)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81dd54e6)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ioam6.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81dda8a0)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de5e81)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81de9776)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:parse_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81deb796)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/wireless/wext-core.c (ffffffff81dfaba8)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00808)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e02c53)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e03b60)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81e07cfb)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2e988)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
```
```
In net/mptcp/pm_userspace.c (0)
Location: include/net/netlink.h:1137
Inline: True
```
```
In net/mctp/device.c (ffffffff81e37e60)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_set_link_af
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff81e39c56)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_newroute
```
```
In net/mctp/neigh.c (ffffffff81e3b7fa)
Location: include/net/netlink.h:1137
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_newneigh
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
In kernel/taskstats.c (ffffffff8124f14b)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffff8188f821)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strscpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff819726b7)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c02d80)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/core/neighbour.c (ffffffff81dd8f65)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81de014d)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff81df0fbc)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff81e026d7)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81e2566d)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81e293c4)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (ffffffff81e44892)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_linecard_set_doit
  - net/core/devlink.c:devlink_nl_rate_parent_node_set
  - net/core/devlink.c:devlink_port_function_set
  - net/core/devlink.c:devlink_port_function_set
  - net/core/devlink.c:devlink_rate_node_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4cd92)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81e55ab8)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_rtab
  - net/sched/sch_api.c:qdisc_get_rtab
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/sched/act_api.c (ffffffff81e61c74)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/sched/ematch.c (ffffffff81e65f20)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/netlink/genetlink.c (ffffffff81e6fd06)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81e7ce42)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81e7f3c6)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81e7f8dc)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ethtool/rss.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ethtool/wol.c (ffffffff81e81ae4)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ethtool/cabletest.c (ffffffff81e85039)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ethtool/fec.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ethtool/eeprom.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ethtool/module.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ethtool/pse-pd.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81eee323)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81efea4b)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0e885)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f1351b)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f1e2bd)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81f6a4e6)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81f6adcc)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81f6e208)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81fa6c36)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ioam6.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81fac5c0)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb8a3e)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81fbcb56)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_flavors
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:parse_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbf3f6)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/wireless/wext-core.c (ffffffff81fcf3c3)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd5638)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd7b63)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd8af0)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81fdd24b)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff82006b18)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
```
```
In net/mptcp/pm_userspace.c (0)
Location: include/net/netlink.h:1186
Inline: True
```
```
In net/mctp/device.c (ffffffff82011080)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_set_link_af
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff82012d36)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_newroute
```
```
In net/mctp/neigh.c (ffffffff820150a1)
Location: include/net/netlink.h:1186
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_newneigh
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
In kernel/taskstats.c (ffffffff812664fb)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffff818d1c61)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strscpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff819b8d87)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c68430)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/core/neighbour.c (ffffffff81e49cce)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81e5181d)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff81e62cdc)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff81e74c47)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/netdev-genl.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81e9abad)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81e9e9f4)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea84b2)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81eb1358)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_rtab
  - net/sched/sch_api.c:qdisc_get_rtab
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/sched/act_api.c (ffffffff81ebe334)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/sched/ematch.c (ffffffff81ec1e60)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/netlink/genetlink.c (ffffffff81ecb5d6)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81ed922b)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81edb9b6)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81edbf89)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ethtool/rss.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ethtool/wol.c (ffffffff81ede1f4)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ethtool/cabletest.c (ffffffff81ee1969)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ethtool/fec.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ethtool/eeprom.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ethtool/stats.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ethtool/mm.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ethtool/module.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ethtool/pse-pd.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ethtool/plca.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81f4dce3)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5e529)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6e545)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f731eb)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f7ddad)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81fca526)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81fcadfc)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81fce2c8)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff820074a6)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ioam6.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8200cd60)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201919e)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff8201dc36)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_flavors
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:parse_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020386)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/devlink/leftover.c (ffffffff82030e6c)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_trap_group_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_group_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
  - net/devlink/leftover.c:devlink_nl_cmd_region_del
  - net/devlink/leftover.c:devlink_nl_cmd_region_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_param_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/devlink/leftover.c:devlink_nl_cmd_dpipe_entries_get
  - net/devlink/leftover.c:devlink_nl_cmd_dpipe_table_get
  - net/devlink/leftover.c:devlink_nl_cmd_linecard_set_doit
  - net/devlink/leftover.c:devlink_nl_rate_parent_node_set
  - net/devlink/leftover.c:devlink_port_function_set
  - net/devlink/leftover.c:devlink_port_function_set
  - net/devlink/leftover.c:devlink_rate_node_get_from_attrs
```
```
In net/devlink/netlink.c (ffffffff82042762)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_get_from_attrs_lock
  - net/devlink/netlink.c:devlink_get_from_attrs_lock
```
```
In net/devlink/dev.c (ffffffff820458a2)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:__devlink_compat_running_version
  - net/devlink/dev.c:__devlink_compat_running_version
  - net/devlink/dev.c:devlink_nl_cmd_flash_update
  - net/devlink/dev.c:devlink_nl_cmd_flash_update
```
```
In net/devlink/health.c (ffffffff820463e1)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_health_reporter_get_from_attrs
```
```
In net/wireless/wext-core.c (ffffffff8204b03f)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff820512d8)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82053853)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff820547cc)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff8205931b)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_app_table_setdel
  - net/dcb/dcbnl.c:dcbnl_app_table_setdel
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff82082eb8)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
```
```
In net/mptcp/pm_userspace.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/mctp/device.c (ffffffff8208de40)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_set_link_af
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff8208fb5a)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_newroute
```
```
In net/mctp/neigh.c (ffffffff82091ec1)
Location: include/net/netlink.h:1187
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_newneigh
```
```
In net/handshake/netlink.c (0)
Location: include/net/netlink.h:1187
Inline: True
```
```
In net/handshake/tlshd.c (0)
Location: include/net/netlink.h:1187
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
In kernel/taskstats.c (ffffffff812803eb)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffff81923c61)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strscpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff81a033b7)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/regulator/event.c (ffffffff81ae25a2)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - drivers/regulator/event.c:reg_generate_netlink_event
```
```
In drivers/net/netkit.c (ffffffff81ce5a48)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_new_link
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81ebabaf)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_pin_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/core/neighbour.c (ffffffff81f089ee)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81f1098d)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff81f220bb)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff81f344e7)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/netdev-genl.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/core/page_pool_user.c (ffffffff81f45e25)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/core/page_pool_user.c:netdev_nl_page_pool_stats_get_doit
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81f5d2f4)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81f61164)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6af72)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81f73df5)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_rtab
  - net/sched/sch_api.c:qdisc_get_rtab
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/sched/act_api.c (ffffffff81f81544)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/sched/ematch.c (ffffffff81f851a0)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/netlink/genetlink.c (ffffffff81f8eac6)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81f9d0f2)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81f9f77d)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81f9fd4f)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ethtool/rss.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ethtool/wol.c (ffffffff81fa2032)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ethtool/cabletest.c (ffffffff81fa57f9)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ethtool/fec.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ethtool/eeprom.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ethtool/stats.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ethtool/mm.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ethtool/module.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ethtool/pse-pd.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ethtool/plca.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff82013e13)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff82024aef)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034c65)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff820392ab)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff820445ed)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff82097cc6)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff8209859c)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff8209bb1e)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff820d62b6)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ioam6.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820dbd30)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e816e)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff820ecc16)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_flavors
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:parse_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820ef4b6)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/devlink/netlink.c (ffffffff8210189d)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_get_from_attrs_lock
  - net/devlink/netlink.c:devlink_get_from_attrs_lock
```
```
In net/devlink/dev.c (ffffffff821051e2)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:__devlink_compat_running_version
  - net/devlink/dev.c:__devlink_compat_running_version
  - net/devlink/dev.c:devlink_nl_flash_update_doit
  - net/devlink/dev.c:devlink_nl_flash_update_doit
```
```
In net/devlink/port.c (ffffffff82106ed5)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_port_function_set
  - net/devlink/port.c:devlink_port_function_set
```
```
In net/devlink/sb.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/devlink/dpipe.c (ffffffff8210c12a)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devlink_nl_dpipe_table_counters_set_doit
  - net/devlink/dpipe.c:devlink_nl_dpipe_entries_get_doit
  - net/devlink/dpipe.c:devlink_nl_dpipe_table_get_doit
```
```
In net/devlink/param.c (ffffffff8210f044)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/devlink/param.c:devlink_nl_param_get_doit
```
```
In net/devlink/region.c (ffffffff82111080)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_new_doit
  - net/devlink/region.c:devlink_nl_region_del_doit
  - net/devlink/region.c:devlink_nl_region_get_doit
```
```
In net/devlink/health.c (ffffffff82111e31)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_health_reporter_get_from_attrs
```
```
In net/devlink/trap.c (ffffffff8211722c)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_group_set_doit
  - net/devlink/trap.c:devlink_nl_trap_group_get_doit
  - net/devlink/trap.c:devlink_nl_trap_set_doit
  - net/devlink/trap.c:devlink_nl_trap_get_doit
```
```
In net/devlink/rate.c (ffffffff82118274)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/devlink/rate.c:devlink_nl_rate_parent_node_set
  - net/devlink/rate.c:devlink_rate_node_get_from_attrs
```
```
In net/devlink/linecard.c (ffffffff8211a7bd)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/devlink/linecard.c:devlink_nl_linecard_set_doit
```
```
In net/wireless/wext-core.c (ffffffff8211d4bf)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82123aa2)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82126043)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8212702b)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff8212be9b)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_app_table_setdel
  - net/dcb/dcbnl.c:dcbnl_app_table_setdel
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff82158532)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
```
```
In net/mptcp/pm_userspace.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/mctp/device.c (ffffffff82164300)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_set_link_af
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff8216606a)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_newroute
```
```
In net/mctp/neigh.c (ffffffff82168498)
Location: include/net/netlink.h:1231
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_newneigh
```
```
In net/handshake/netlink.c (0)
Location: include/net/netlink.h:1231
Inline: True
```
```
In net/handshake/tlshd.c (0)
Location: include/net/netlink.h:1231
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
In kernel/taskstats.c (ffff80001020d424)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffff800010661ea8)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffff800010778cf4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffff800010ad3904)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/neighbour.c (ffff800010be6934)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffff800010beb240)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffff800010bf744c)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffff800010c0355c)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/drop_monitor.c (ffff800010c1c2f4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/lwt_bpf.c (ffff800010c1e618)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffff800010c305fc)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/sched/sch_api.c (ffff800010c3bad4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/act_api.c (ffff800010c46998)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/ematch.c (ffff800010c4a204)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/netlink/genetlink.c (ffff800010c51a1c)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/devinet.c (ffff800010ca7fb0)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffff800010cb5290)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc21c8)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/nexthop.c (ffff800010cc4238)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010cce378)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffff800010cff81c)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:extract_addr
  - net/ipv6/addrconf.c:extract_addr
```
```
In net/ipv6/addrlabel.c (ffff800010d0b87c)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffff800010d0e688)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffff800010d41388)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ip6mr.c (ffff800010d440ec)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f144)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffff800010d505cc)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/wireless/wext-core.c (ffff800010d60dc8)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d667c0)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d69308)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d6a2d8)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/dcb/dcbnl.c (ffff800010d6f334)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1072
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
In kernel/taskstats.c (c044bdb8)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (c080af34)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In drivers/thermal/thermal_core.c (c0bb44c0)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/neighbour.c (c0d004e4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (c0d03f34)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:linkinfo_to_kind_ops
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (c0d10770)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (c0d1c944)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/drop_monitor.c (c0d34150)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/lwt_bpf.c (c0d36668)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (c0d475d4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/sched/sch_api.c (c0d4dacc)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/act_api.c (c0d57a78)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/ematch.c (c0d5add0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/netlink/genetlink.c (c0d61110)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/devinet.c (c0db2954)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (c0dc0d7c)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (c0dcd8a0)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/nexthop.c (c0dcf0b0)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ipmr.c (c0dd9448)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (c0e07d90)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:extract_addr
  - net/ipv6/addrconf.c:extract_addr
```
```
In net/ipv6/addrlabel.c (c0e1176c)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (c0e15384)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (c0e43d8c)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ip6mr.c (c0e45ec0)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_iptunnel.c (c0e4fea8)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (c0e51158)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:parse_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/wireless/wext-core.c (c0e6056c)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (c0e65db4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (c0e67a34)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e68858)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/dcb/dcbnl.c (c0e6cfa4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1072
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
In kernel/taskstats.c (c00000000028b244)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (c000000000816108)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In drivers/thermal/thermal_core.c (c000000000bb8c00)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/neighbour.c (c000000000cc6110)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (c000000000cce664)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (c000000000cdd1f0)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (c000000000cecbc8)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/drop_monitor.c (c000000000d0d0ac)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/lwt_bpf.c (c000000000d10610)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (c000000000d29410)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/sched/sch_api.c (c000000000d353a0)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/act_api.c (c000000000d433ac)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/ematch.c (c000000000d47d20)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/netlink/genetlink.c (c000000000d5043c)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/devinet.c (c000000000db9e70)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (c000000000dcce60)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (c000000000ddd7e4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/nexthop.c (c000000000de018c)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000deafc0)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (c000000000e29200)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:extract_addr
  - net/ipv6/addrconf.c:extract_addr
```
```
In net/ipv6/addrlabel.c (c000000000e36058)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (c000000000e3af50)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (c000000000e75cb0)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ip6mr.c (c000000000e78d18)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86534)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (c000000000e88130)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:parse_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/wireless/wext-core.c (c000000000e9c1d0)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea29d4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea6198)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea7458)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/dcb/dcbnl.c (c000000000eae1ac)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1072
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
In kernel/taskstats.c (ffffffe00016e520)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffe00048e7f0)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffe0006cfeea)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/neighbour.c (ffffffe000769e56)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffe00076ebe4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffe000778800)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffe000782624)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/drop_monitor.c (ffffffe000796388)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffe000798308)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffe0007a67c6)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/sched/sch_api.c (ffffffe0007ac770)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/act_api.c (ffffffe0007b55be)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/ematch.c (ffffffe0007b75ec)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/netlink/genetlink.c (ffffffe0007bcb48)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/devinet.c (ffffffe000801552)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffe00080cdf0)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817682)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffe00081982e)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe0008206b2)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffe00084a09c)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:extract_addr
  - net/ipv6/addrconf.c:extract_addr
```
```
In net/ipv6/addrlabel.c (ffffffe000852914)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffe0008566ca)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffe00087cadc)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ip6mr.c (ffffffe00087ec1e)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000887956)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffe000888b9a)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:parse_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:parse_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/wireless/wext-core.c (ffffffe000895f30)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a212)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089c40e)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089d016)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffe0008a0ef4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1072
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
In kernel/taskstats.c (ffffffff8118d555)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffff8154dfd1)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff815dc977)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff8182c975)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/neighbour.c (ffffffff818e3a2d)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818e96df)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff818f5791)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff818ffd7b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81915e48)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81917c22)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffff8192850b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/sched/sch_api.c (ffffffff8192f9bd)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/act_api.c (ffffffff81939ae8)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/ematch.c (ffffffff8193cb48)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff819425d4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81991b8d)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff8199ceb1)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8c24)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff819aaa54)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819b34e2)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff819ddedb)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:extract_addr
  - net/ipv6/addrconf.c:extract_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819e7ba4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff819eaecb)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81a173f6)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a19500)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a229a1)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81a23c81)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/wireless/wext-core.c (ffffffff81a3263a)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a3656e)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a38d98)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a39ab1)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81a3dcda)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1072
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
In kernel/taskstats.c (ffffffff81180675)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffff8153e2b1)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff815c7fb7)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/vxlan.c (ffffffff8176ea1e)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_nl2conf
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff817f4005)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/neighbour.c (ffffffff8189d86d)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818a351f)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff818af5c1)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff818b9bab)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff818cfbf8)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818d19d2)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffff818e22bb)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/sched/sch_api.c (ffffffff818e94bd)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/act_api.c (ffffffff818f35e8)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/ematch.c (ffffffff818f6648)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff818fc0c4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8194b64d)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81956971)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819626e4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81964514)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196fb12)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8199ac9b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:extract_addr
  - net/ipv6/addrconf.c:extract_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819a4964)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff819a7c8b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff819d41b6)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ip6mr.c (ffffffff819d62c0)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819df761)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff819e0a41)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/wireless/wext-core.c (ffffffff819ef82a)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f318e)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f59b8)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f66d1)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff819fa8ca)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1072
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
In kernel/taskstats.c (ffffffff8118b325)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffff81549d11)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff815e1b07)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff8187bfa5)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/neighbour.c (ffffffff81934a5d)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8193a70f)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff819467c1)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff81950dab)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_filterinfo
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81966e78)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81968db2)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffff8197969b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/sched/sch_api.c (ffffffff81980b4d)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/act_api.c (ffffffff8198ac78)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/ematch.c (ffffffff8198dcd8)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81993764)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/netfilter/nfnetlink.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199ad37)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_config
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict_batch
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b864)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
  - net/netfilter/nfnetlink_log.c:__build_packet_message
```
```
In net/netfilter/nf_conntrack_core.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/netfilter/nf_conntrack_proto_generic.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/netfilter/nf_conntrack_proto_tcp.c (ffffffff819a53a8)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:nlattr_to_tcp
```
```
In net/netfilter/nf_conntrack_proto_udp.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/netfilter/nf_conntrack_proto_icmp.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/netfilter/nf_conntrack_proto_icmpv6.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/netfilter/nf_conntrack_proto_dccp.c (ffffffff819a9974)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_dccp.c:nlattr_to_dccp
```
```
In net/netfilter/nf_conntrack_proto_sctp.c (ffffffff819aa7b4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_sctp.c:nlattr_to_sctp
```
```
In net/netfilter/nf_conntrack_proto_gre.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819b0e9a)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_attach_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_attach_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_parse
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_attach_labels
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_attach_labels
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_synproxy
  - net/netfilter/nf_conntrack_netlink.c:change_seq_adj
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_protoinfo
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple_proto
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819fc42d)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81a07751)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a134c4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a152f4)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1dd82)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a4895b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:extract_addr
  - net/ipv6/addrconf.c:extract_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a52624)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a5594b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81a81e76)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a83f80)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d421)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81a8e701)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/wireless/wext-core.c (ffffffff81a9e1ea)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa241e)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa4c48)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa5961)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81aa9b8a)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1072
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
In kernel/taskstats.c (ffffffff81198c95)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
```
```
In lib/nlattr.c (ffffffff81563b61)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In drivers/acpi/event.c (ffffffff815fb9c7)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff818979d5)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/neighbour.c (ffffffff81955dcd)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8195bf3f)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_stats
```
```
In net/core/filter.c (ffffffff819680d1)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/sock_diag.c (ffffffff81972b2a)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81989108)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff8198b192)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffff8199bb8b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_get_from_attrs
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/sched/sch_api.c (ffffffff819a30cd)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/act_api.c (ffffffff819ad4d8)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/sched/ematch.c (ffffffff819b0578)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff819b6254)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81a0679d)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81a11e91)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1de94)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/netlink.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a1fd34)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a2904b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a54a8b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:extract_addr
  - net/ipv6/addrconf.c:extract_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a5e626)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a6194b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81a8e786)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a908ab)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a111)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81a9b471)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/wireless/wext-core.c (ffffffff81aaa3ea)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aae78e)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ab0fb8)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab1d01)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81ab5efa)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1072
Inline: True
```
</details>
</li>
</ul>

## Differences
