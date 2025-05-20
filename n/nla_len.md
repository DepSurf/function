# Function: <code>nla_len</code>

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
In kernel/taskstats.c (ffffffff8113e3e5)
Location: include/net/netlink.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff8141560f)
Location: include/net/netlink.h:678
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_strcmp
```
```
In net/core/gen_estimator.c (0)
Location: include/net/netlink.h:678
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:678
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81729b5f)
Location: include/net/netlink.h:678
Inline: True
Inline callers:
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/filter.c (0)
Location: include/net/netlink.h:678
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:678
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:678
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:678
Inline: True
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/netlink.h:678
Inline: True
```
```
In net/sched/ematch.c (ffffffff81749a76)
Location: include/net/netlink.h:678
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:678
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8178f889)
Location: include/net/netlink.h:678
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:678
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:678
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff817cada5)
Location: include/net/netlink.h:678
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:678
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:678
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:678
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818103d0)
Location: include/net/netlink.h:678
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/dcb/dcbnl.c (ffffffff81814ec1)
Location: include/net/netlink.h:678
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In kernel/taskstats.c (ffffffff81146a35)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff8145d705)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In net/core/gen_estimator.c (ffffffff81777089)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff8179189c)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8179475f)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
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
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff8179c4cd)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/core/filter.c:__skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff817a5e0b)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817afc06)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff817b41f8)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (ffffffff817b5ef2)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff817b697d)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff817fcf4d)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81807b3f)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818122c2)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/ipmr.c (ffffffff81817934)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff8183fb1f)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81842685)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818802d5)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81881a1a)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81882fd9)
Location: include/net/netlink.h:689
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/dcb/dcbnl.c (ffffffff818865d5)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/switchdev/switchdev.c (ffffffff8188b7c9)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
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
In kernel/taskstats.c (ffffffff81150695)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff8147c1c5)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In net/core/gen_estimator.c (ffffffff817a41bd)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff817bf3ec)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff817c1fdf)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
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
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff817c977e)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/core/filter.c:__skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff817d48db)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff817d9c65)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/sch_api.c (ffffffff817df2f6)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff817e3aa8)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:nla_memdup_cookie
  - net/sched/act_api.c:nla_memdup_cookie
```
```
In net/sched/sch_fifo.c (ffffffff817e58f2)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff817e640d)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8182dead)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81838be4)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818437d2)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/ipmr.c (ffffffff818491a1)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff8187174f)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff818743d1)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a3f38)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b4b85)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b62ca)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b787e)
Location: include/net/netlink.h:689
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/dcb/dcbnl.c (ffffffff818bae45)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/switchdev/switchdev.c (ffffffff818bfaa0)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
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
In kernel/taskstats.c (ffffffff81152c8a)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff814854e5)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In net/core/gen_estimator.c (ffffffff817c230d)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff817ddcc3)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff817e0760)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
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
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff817e86cb)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - net/core/filter.c:__skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff817f3beb)
Location: include/net/netlink.h:698
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff817f92a2)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/sch_api.c (ffffffff817fe789)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff818033e8)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (ffffffff81805422)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff81805f5d)
Location: include/net/netlink.h:698
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:698
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8184fb2d)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81859ea4)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81865035)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/ipmr.c (ffffffff8186c7ac)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff818964c4)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff818991ea)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca4ac)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818db336)
Location: include/net/netlink.h:698
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dcba3)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818dde44)
Location: include/net/netlink.h:698
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/dcb/dcbnl.c (ffffffff818e1853)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/switchdev/switchdev.c (ffffffff818e62c8)
Location: include/net/netlink.h:698
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
  - net/switchdev/switchdev.c:switchdev_port_br_afspec
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
In kernel/taskstats.c (ffffffff8115f4aa)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff814c1675)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In net/core/gen_estimator.c (ffffffff8183bd2d)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81856ab3)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8185afe4)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
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
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff81863a2b)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/core/filter.c:__skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff8186f2db)
Location: include/net/netlink.h:704
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81876bb2)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/sch_api.c (ffffffff8187c419)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81881868)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (ffffffff81884132)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff81884c8d)
Location: include/net/netlink.h:704
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:704
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff818cf75d)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff818d9daa)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e5195)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/ipmr.c (ffffffff818ed092)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff81917894)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff8191d7c5)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194dc46)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff8194f082)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81960f16)
Location: include/net/netlink.h:704
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81962793)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81963a34)
Location: include/net/netlink.h:704
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/dcb/dcbnl.c (ffffffff819675d3)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In kernel/taskstats.c (ffffffff8116e415)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff814f23a5)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strlcpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
```
In net/core/gen_estimator.c (ffffffff818864b1)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff818a1afc)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818a68a3)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
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
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff818b1239)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff818c0612)
Location: include/net/netlink.h:704
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818c8372)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/sched/sch_api.c (ffffffff818cec52)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff818d536c)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (ffffffff818d7d32)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff818d87f6)
Location: include/net/netlink.h:704
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:704
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8192545d)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff819307b6)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:704
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193ba7d)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:704
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8194305c)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff8196efd0)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff819725a5)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a6ec6)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff819a8361)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819ba704)
Location: include/net/netlink.h:704
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bbff2)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bd516)
Location: include/net/netlink.h:704
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/dcb/dcbnl.c (ffffffff819c0af0)
Location: include/net/netlink.h:704
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8117bee5)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff815060e5)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
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
In net/core/gen_estimator.c (ffffffff818a6c31)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff818c4c6c)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818ca103)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff818d5da3)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff818e9562)
Location: include/net/netlink.h:847
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818f14e2)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/sched/sch_api.c (ffffffff818f9f52)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81901fac)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (ffffffff81904522)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff81904fe6)
Location: include/net/netlink.h:847
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:847
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8195426d)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff8195fcc2)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:847
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196b76d)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:847
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819731f2)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff819a4b80)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff819a8110)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dda26)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff819deeb1)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f1386)
Location: include/net/netlink.h:847
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f3262)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f4488)
Location: include/net/netlink.h:847
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/dcb/dcbnl.c (ffffffff819f7ea0)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (ffffffff81a043a6)
Location: include/net/netlink.h:847
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
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
In kernel/taskstats.c (ffffffff81188d0c)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff81534aab)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
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
In net/core/gen_estimator.c (ffffffff818f20c1)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81910c8d)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff819170d3)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff81923591)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff81938f72)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81942e02)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffff81951c5b)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/sched/sch_api.c (ffffffff819596ad)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff8196312f)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (ffffffff81965722)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff81966248)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819b9aed)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff819c6569)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2314)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff819d4134)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff819dccf2)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff81a07cdb)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81a15311)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4c596)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81a4da21)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a60a48)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a625e4)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a63b71)
Location: include/net/netlink.h:1081
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/dcb/dcbnl.c (ffffffff81a673d2)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (ffffffff81a73658)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
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
In kernel/taskstats.c (ffffffff81194c4c)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff815558db)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
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
In net/core/gen_estimator.c (ffffffff81924011)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81943a5d)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81949713)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff819557c1)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff8196be32)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81977db2)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffff8198869b)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/sched/sch_api.c (ffffffff8198fb4d)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81999caf)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (ffffffff8199c1b2)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff8199ccd8)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819f1ded)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff819fd119)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a08e84)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a0aca4)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81a13d5b)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff81a3e84b)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81a4bee1)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83166)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81a845f1)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a97678)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a991c4)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a9a721)
Location: include/net/netlink.h:1081
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/dcb/dcbnl.c (ffffffff81a9def2)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (ffffffff81aa9e48)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
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
In kernel/taskstats.c (ffffffff811a9d9c)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff815de65b)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
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
In net/core/gen_estimator.c (ffffffff819f7bc1)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81a147c5)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81a19aa3)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
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
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff81a283b4)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff81a3fd34)
Location: include/net/netlink.h:1133
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a4d0f7)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (ffffffff81a5169d)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81a60f41)
Location: include/net/netlink.h:1133
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81a6812d)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81a730e8)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:nla_memdup_cookie
  - net/sched/act_api.c:nla_memdup_cookie
```
```
In net/sched/sch_fifo.c (ffffffff81a756e2)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff81a75d65)
Location: include/net/netlink.h:1133
Inline: True
```
```
In net/ethtool/netlink.c (ffffffff81a85ddd)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81a87840)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
```
```
In net/ethtool/strset.c (ffffffff81a87c83)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/wol.c (ffffffff81a89b7f)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/cabletest.c (ffffffff81a8cc77)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acb7b7)
Location: include/net/netlink.h:1133
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81adfacd)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81aebbd3)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:fib_gw_from_via
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1133
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af93e2)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1133
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81afb7d4)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_check_attr_group
```
```
In net/ipv4/ipmr.c (ffffffff81b00ab5)
Location: include/net/netlink.h:1133
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b3e929)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81b45a38)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e00c)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f654)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b92959)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b94e11)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b95f8c)
Location: include/net/netlink.h:1133
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81b999b0)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (ffffffff81ba6095)
Location: include/net/netlink.h:1133
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb3165)
Location: include/net/netlink.h:1133
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
In kernel/taskstats.c (ffffffff811a739c)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff815fbcfb)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strscpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
```
```
In net/core/gen_estimator.c (ffffffff819f7621)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81a14ad5)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81a19c93)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
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
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff81a28cd4)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff81a42a34)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a52db7)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (ffffffff81a577ad)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
```
In net/core/bpf_sk_storage.c (ffffffff81a69811)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81a7083d)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81a7bca8)
Location: include/net/netlink.h:1146
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
  - net/sched/act_api.c:nla_memdup_cookie
```
```
In net/sched/sch_fifo.c (ffffffff81a7e4b2)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff81a7eb15)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/ethtool/netlink.c (ffffffff81a8f76d)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81a911c0)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
```
```
In net/ethtool/strset.c (ffffffff81a915f3)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/wol.c (ffffffff81a933bf)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/cabletest.c (ffffffff81a96387)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7777)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81aec94d)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81af8acb)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:fib_gw_from_via
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06052)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81b08ea4)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_check_attr_group
```
```
In net/ipv4/ipmr.c (ffffffff81b0eb95)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b4d4b9)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81b543d8)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d01c)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f8c4)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba25a9)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba4a71)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba5bfc)
Location: include/net/netlink.h:1146
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81ba96b0)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (ffffffff81bb557b)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7605)
Location: include/net/netlink.h:1146
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
In kernel/taskstats.c (ffffffff811a7edc)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff815de93b)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strscpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81882a30)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
```
```
In net/core/gen_estimator.c (ffffffff819dd7a1)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff819fb5d5)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81a00c93)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
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
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff81a0ffc4)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff81a2760a)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a385b9)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (ffffffff81a4bf55)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_port_function_set
  - net/core/devlink.c:devlink_port_function_set
```
```
In net/core/bpf_sk_storage.c (ffffffff81a51fb1)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81a5913d)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81a648e8)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/sch_fifo.c (ffffffff81a67305)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff81a67975)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/ethtool/netlink.c (ffffffff81a78e5e)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81a7a9d0)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
```
```
In net/ethtool/strset.c (ffffffff81a7ae13)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/wol.c (ffffffff81a7cdcf)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/cabletest.c (ffffffff81a7fe0f)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2849)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81ad687d)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae422b)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:fib_gw_from_via
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af18af)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81af59a1)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/ipmr.c (ffffffff81afc885)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b3b363)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81b41b38)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7becc)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81b7e494)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b91699)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93770)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b94d6c)
Location: include/net/netlink.h:1146
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81b98840)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (ffffffff81ba4567)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb8aa4)
Location: include/net/netlink.h:1146
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
In kernel/taskstats.c (ffffffff811d1a0c)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff8164a4bb)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - lib/nlattr.c:nla_strcmp
  - lib/nlattr.c:nla_memcpy
  - lib/nlattr.c:nla_strdup
  - lib/nlattr.c:nla_strscpy
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff819143d0)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8191aaa4)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/gen_estimator.c (ffffffff81a8da81)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81aad90c)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81ab3053)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
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
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff81ac2294)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff81adc3aa)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff81aed334)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/lwt_bpf.c (ffffffff81aee429)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (ffffffff81b043a4)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_port_function_set
  - net/core/devlink.c:devlink_port_function_set
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0ac41)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81b1242d)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81b1dbb8)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/sch_fifo.c (ffffffff81b207e5)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff81b20ee5)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/ethtool/netlink.c (ffffffff81b3312e)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81b34de0)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
```
```
In net/ethtool/strset.c (ffffffff81b35373)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/wol.c (ffffffff81b36fca)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/cabletest.c (ffffffff81b39bdf)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b806e9)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81b96503)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba3b7b)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:fib_gw_from_via
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba706a)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1dbf)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81bb62a1)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/ipmr.c (ffffffff81bbdf78)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81c01b63)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81c09868)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ioam6.c (ffffffff81c3a0a9)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c46d8c)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81c49ed4)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4bc16)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5de39)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5ff10)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c61585)
Location: include/net/netlink.h:1146
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81c65434)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (ffffffff81c720f7)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81c88074)
Location: include/net/netlink.h:1146
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
In kernel/taskstats.c (ffffffff8120617b)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff81760c6d)
Location: include/net/netlink.h:1146
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
  - lib/nlattr.c:nla_validate_int_range
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6998a)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6fef0)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/gen_estimator.c (ffffffff81c0359f)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81c26571)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81c2cfed)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
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
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff81c3cbcc)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff81c5d83a)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff81c6ffbb)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/lwt_bpf.c (ffffffff81c71314)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (ffffffff81c89cb2)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_port_function_set
  - net/core/devlink.c:devlink_port_function_set
```
```
In net/core/bpf_sk_storage.c (ffffffff81c9129f)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81c99798)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_rtab
```
```
In net/sched/act_api.c (ffffffff81ca51b4)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/sch_fifo.c (ffffffff81ca8b15)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff81ca9010)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ethtool/netlink.c (ffffffff81cbe31e)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81cc05c7)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
```
```
In net/ethtool/strset.c (ffffffff81cc0bfc)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/wol.c (ffffffff81cc2970)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/cabletest.c (ffffffff81cc5a89)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d10ab1)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81d26993)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81d36410)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:fib_gw_from_via
```
```
In net/ipv4/fib_semantics.c (ffffffff81d399b4)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d454e5)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81d49eab)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/ipmr.c (ffffffff81d52a4e)
Location: include/net/netlink.h:1146
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81d9b896)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81da4a30)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ioam6.c (ffffffff81dd7e03)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de609e)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81de9776)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81deb796)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00115)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e0231d)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e03b60)
Location: include/net/netlink.h:1146
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81e080de)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (ffffffff81e15c99)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2e988)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
```
```
In net/mctp/device.c (ffffffff81e37e60)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_set_link_af
```
```
In net/mctp/route.c (ffffffff81e39c56)
Location: include/net/netlink.h:1146
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_newroute
```
```
In net/mctp/neigh.c (ffffffff81e3b814)
Location: include/net/netlink.h:1146
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
In kernel/taskstats.c (ffffffff8124e45b)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff8188f64d)
Location: include/net/netlink.h:1195
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
  - lib/nlattr.c:nla_validate_range_unsigned
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfc4ea)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c02d80)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/gen_estimator.c (ffffffff81db2b8f)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81dd8f65)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81de014d)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
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
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff81df0fbc)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff81e1401a)
Location: include/net/netlink.h:1195
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff81e27f0b)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/lwt_bpf.c (ffffffff81e293c4)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (ffffffff81e44892)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_port_function_set
  - net/core/devlink.c:devlink_port_function_set
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4c7ef)
Location: include/net/netlink.h:1195
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81e55ab8)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_rtab
```
```
In net/sched/act_api.c (ffffffff81e61c74)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/sch_fifo.c (ffffffff81e659a5)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff81e65f20)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ethtool/netlink.c (ffffffff81e7cdde)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81e7f217)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
```
```
In net/ethtool/strset.c (ffffffff81e7f8dc)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/wol.c (ffffffff81e81ac3)
Location: include/net/netlink.h:1195
Inline: True
```
```
In net/ethtool/cabletest.c (ffffffff81e85039)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed6821)
Location: include/net/netlink.h:1195
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81eee323)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81efea53)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:fib_gw_from_via
```
```
In net/ipv4/fib_semantics.c (ffffffff81f022af)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0e885)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1195
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f1351b)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/ipmr.c (ffffffff81f1cd89)
Location: include/net/netlink.h:1195
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81f6a4e6)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81f73ee0)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81fa71c3)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ioam6.c (ffffffff81fa97f8)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb8a3e)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81fbcb56)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_flavors
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbf3f6)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd4f48)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd71ed)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd8af0)
Location: include/net/netlink.h:1195
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81fdd64e)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (ffffffff81fecc5a)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff82006b18)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
```
```
In net/mctp/device.c (ffffffff82011080)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_set_link_af
```
```
In net/mctp/route.c (ffffffff82012d36)
Location: include/net/netlink.h:1195
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_newroute
```
```
In net/mctp/neigh.c (ffffffff820150b7)
Location: include/net/netlink.h:1195
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
In kernel/taskstats.c (ffffffff8126580b)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff818d1a8d)
Location: include/net/netlink.h:1196
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
  - lib/nlattr.c:nla_validate_range_unsigned
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c61b6d)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c68430)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/gen_estimator.c (ffffffff81e2315f)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81e49cce)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81e4e765)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_validate_mdb_entry
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
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
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff81e62cdc)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff81e8792a)
Location: include/net/netlink.h:1196
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff81e9d51b)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/lwt_bpf.c (ffffffff81e9e9f4)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea7eff)
Location: include/net/netlink.h:1196
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81eb1358)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_rtab
```
```
In net/sched/act_api.c (ffffffff81ebe334)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/sch_fifo.c (ffffffff81ec18e5)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff81ec1e60)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ethtool/netlink.c (ffffffff81ed919d)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81edb807)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
```
```
In net/ethtool/strset.c (ffffffff81edbf89)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/wol.c (ffffffff81ede1d3)
Location: include/net/netlink.h:1196
Inline: True
```
```
In net/ethtool/cabletest.c (ffffffff81ee1969)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f35791)
Location: include/net/netlink.h:1196
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81f4dce3)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5e531)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:fib_gw_from_via
```
```
In net/ipv4/fib_semantics.c (ffffffff81f61d0f)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6e545)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1196
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f731eb)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/ipmr.c (ffffffff81f7c845)
Location: include/net/netlink.h:1196
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fca526)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81fd3fc0)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff82007a23)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ioam6.c (ffffffff8200a178)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201919e)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff8201dc36)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_flavors
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020386)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/devlink/leftover.c (ffffffff8203d485)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_port_function_set
  - net/devlink/leftover.c:devlink_port_function_set
```
```
In net/devlink/dev.c (ffffffff820458a2)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:__devlink_compat_running_version
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82050be8)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82052ede)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff820547cc)
Location: include/net/netlink.h:1196
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff8205987e)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (ffffffff82068efa)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff82082eb8)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
```
```
In net/mctp/device.c (ffffffff8208de40)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_set_link_af
```
```
In net/mctp/route.c (ffffffff8208fb5a)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_newroute
```
```
In net/mctp/neigh.c (ffffffff82091ed7)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_newneigh
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
In kernel/taskstats.c (ffffffff8127f68b)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff81923a85)
Location: include/net/netlink.h:1240
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
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_range_unsigned
  - lib/nlattr.c:nla_validate_range_unsigned
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1855d)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81ebabaf)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_pin_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set
```
```
In net/core/gen_estimator.c (ffffffff81ee109a)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81f089ee)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81f0e168)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_validate_mdb_entry_del_bulk
  - net/core/rtnetlink.c:rtnl_validate_mdb_entry
  - net/core/rtnetlink.c:rtnl_validate_mdb_entry_get
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
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
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff81f220bb)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/page_pool_user.c (ffffffff81f45fdb)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/core/page_pool_user.c:netdev_nl_page_pool_get_doit
  - net/core/page_pool_user.c:netdev_nl_page_pool_stats_get_doit
  - net/core/page_pool_user.c:netdev_nl_page_pool_stats_get_doit
```
```
In net/core/fib_rules.c (ffffffff81f4993a)
Location: include/net/netlink.h:1240
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff81f5fc9f)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/lwt_bpf.c (ffffffff81f61164)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6a9af)
Location: include/net/netlink.h:1240
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81f73df5)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_rtab
```
```
In net/sched/act_api.c (ffffffff81f81544)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/sch_fifo.c (ffffffff81f84c25)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff81f851a0)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ethtool/netlink.c (ffffffff81f9d05d)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81f9f5c7)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
```
```
In net/ethtool/strset.c (ffffffff81f9fd4f)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/wol.c (ffffffff81fa2013)
Location: include/net/netlink.h:1240
Inline: True
```
```
In net/ethtool/cabletest.c (ffffffff81fa57f9)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffb841)
Location: include/net/netlink.h:1240
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff82013e13)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff82024af7)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:fib_gw_from_via
```
```
In net/ipv4/fib_semantics.c (ffffffff820282e0)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034c65)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1240
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff820392ab)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/ipmr.c (ffffffff82042f38)
Location: include/net/netlink.h:1240
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff82097cc6)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff820a18d0)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff820d68b3)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ioam6.c (ffffffff820d9118)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e816e)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff820ecc16)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_flavors
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820ef4b6)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/devlink/netlink.c (ffffffff821013f5)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_notify_filter_set_doit
  - net/devlink/netlink.c:devlink_nl_notify_filter_set_doit
```
```
In net/devlink/dev.c (ffffffff821051e2)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:__devlink_compat_running_version
```
```
In net/devlink/port.c (ffffffff82106ed5)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_port_function_set
  - net/devlink/port.c:devlink_port_function_set
```
```
In net/devlink/param.c (ffffffff8210d9ca)
Location: include/net/netlink.h:1240
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff821232c7)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff821256f6)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8212702b)
Location: include/net/netlink.h:1240
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff8212c3fe)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (ffffffff8213c17a)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff82158532)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
```
```
In net/mctp/device.c (ffffffff82164300)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_set_link_af
```
```
In net/mctp/route.c (ffffffff8216606a)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_newroute
```
```
In net/mctp/neigh.c (ffffffff821684ae)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_newneigh
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
In kernel/taskstats.c (ffff80001020ce5c)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffff800010661d44)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
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
In net/core/gen_estimator.c (ffff800010bbf87c)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffff800010be6934)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffff800010beb240)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffff800010bf744c)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffff800010c12524)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/core/lwt_bpf.c (ffff800010c1e618)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffff800010c305fc)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/sched/sch_api.c (ffff800010c3bad4)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffff800010c469c8)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (ffff800010c493f4)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffff800010c4a204)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/devinet.c (ffff800010ca7fb0)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffff800010cb5298)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:fib_gw_from_via
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc21c8)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/nexthop.c (ffff800010cc5934)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffff800010cce378)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffff800010cff81c)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffff800010d11450)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4ef80)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffff800010d505cc)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d66cac)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d68a90)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d6a2e0)
Location: include/net/netlink.h:1081
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/dcb/dcbnl.c (ffff800010d6e858)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (ffff800010d7dae8)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
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
In kernel/taskstats.c (c044b84c)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (c080ae08)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
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
In net/core/gen_estimator.c (c0cdb320)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (c0d004d0)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (c0d03f34)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
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
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:linkinfo_to_kind_ops
```
```
In net/core/filter.c (c0d10770)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (c0d2a050)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl2rule
  - net/core/fib_rules.c:fib_nl2rule
```
```
In net/core/lwt_bpf.c (c0d36668)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (c0d475d4)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/sched/sch_api.c (c0d4dacc)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (c0d57a78)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (c0d5a14c)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (c0d5add0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/tcp_metrics.c (c0da05a4)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:__parse_nl_addr
```
```
In net/ipv4/devinet.c (c0db2954)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (c0dc0d80)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (c0dcd8a0)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/nexthop.c (c0dcff30)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/ipmr.c (c0dd9448)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (c0e07d90)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (c0e15850)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6_iptunnel.c (c0e4fd0c)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (c0e51158)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/netlabel/netlabel_mgmt.c (c0e65368)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_unlabeled.c (c0e671b8)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_addrinfo_get
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e6885c)
Location: include/net/netlink.h:1081
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (c0e6c7a8)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (c0e78648)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
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
In kernel/taskstats.c (c00000000028aae0)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (c000000000815f38)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
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
In net/core/gen_estimator.c (c000000000c98bfc)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (c000000000cc6110)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (c000000000cce66c)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (c000000000cdd1f0)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (c000000000cff520)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/core/lwt_bpf.c (c000000000d10610)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (c000000000d29410)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/sched/sch_api.c (c000000000d353a0)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (c000000000d433f8)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (c000000000d46ba0)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (c000000000d47d20)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/devinet.c (c000000000db9e70)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (c000000000dcce6c)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (c000000000ddd7e4)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/nexthop.c (c000000000de216c)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (c000000000deafc0)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (c000000000e29200)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (c000000000e3a8b0)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e862a0)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (c000000000e88130)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea3608)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea5614)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea7464)
Location: include/net/netlink.h:1081
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/dcb/dcbnl.c (c000000000ead150)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (c000000000ebd684)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
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
In kernel/taskstats.c (ffffffe00016e052)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffe00048e660)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
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
In net/core/gen_estimator.c (ffffffe00074d230)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffe000769e56)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffe00076ebe4)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffe000778800)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffe00078e3e6)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffe000798308)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffe0007a67c6)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/sched/sch_api.c (ffffffe0007ac770)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffe0007b4d96)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (ffffffe0007b6aa0)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffe0007b75ec)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/devinet.c (ffffffe000801552)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffe00080cdf4)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817682)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffe00081a568)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffe0008206b2)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffe00084a09c)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffe00085611e)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe00088780c)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffe000888b9a)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a60c)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089bd62)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089d01a)
Location: include/net/netlink.h:1081
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/dcb/dcbnl.c (ffffffe0008a06e6)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (ffffffe0008ab2ce)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
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
In kernel/taskstats.c (ffffffff8118d26c)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff8154debb)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
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
In net/core/gen_estimator.c (ffffffff818c4011)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff818e3a2d)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818e96e3)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff818f5791)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff8190be02)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81917c22)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffff8192850b)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/sched/sch_api.c (ffffffff8192f9bd)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81939b1f)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (ffffffff8193c022)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff8193cb48)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81991b8d)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff8199ceb9)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8c24)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff819aaa44)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff819b34e2)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff819ddedb)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff819eb571)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a227f6)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81a23c81)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a36a08)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a38554)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a39ab1)
Location: include/net/netlink.h:1081
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/dcb/dcbnl.c (ffffffff81a3d282)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (ffffffff81a491d8)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
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
In kernel/taskstats.c (ffffffff8118038c)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff8153e19b)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
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
In drivers/net/vxlan.c (ffffffff8176ea1e)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_fdb_parse
```
```
In net/core/gen_estimator.c (ffffffff8187df51)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff8189d86d)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818a3523)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff818af5c1)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff818c5bc2)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818d19d2)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffff818e22bb)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/sched/sch_api.c (ffffffff818e94bd)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff818f361f)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (ffffffff818f5b22)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff818f6648)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8194b64d)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81956979)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819626e4)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81964504)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff8196fb12)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff8199ac9b)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff819a8331)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819df5b6)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff819e0a41)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f3628)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f5174)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f66d1)
Location: include/net/netlink.h:1081
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/dcb/dcbnl.c (ffffffff819f9e72)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (ffffffff81a05dc8)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
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
In kernel/taskstats.c (ffffffff8118b03c)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff81549bfb)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
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
In net/core/gen_estimator.c (ffffffff81915011)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81934a5d)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8193a713)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff819467c1)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff8195ce32)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81968db2)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffff8197969b)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/sched/sch_api.c (ffffffff81980b4d)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff8198acaf)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (ffffffff8198d1b2)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff8198dcd8)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199991a)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
```
```
In net/netfilter/nf_conntrack_proto_tcp.c (ffffffff819a53a8)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:nlattr_to_tcp
```
```
In net/netfilter/nf_conntrack_proto_dccp.c (ffffffff819a9974)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_dccp.c:nlattr_to_dccp
```
```
In net/netfilter/nf_conntrack_proto_sctp.c (ffffffff819aa7b4)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_sctp.c:nlattr_to_sctp
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ad8d8)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_attach_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_parse
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_attach_labels
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_synproxy
  - net/netfilter/nf_conntrack_netlink.c:change_seq_adj
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_protoinfo
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple_proto
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple_proto
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819fc42d)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81a07759)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a134c4)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a152e4)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81a1dd82)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff81a4895b)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81a55ff1)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d276)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81a8e701)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa28b8)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa4404)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa5961)
Location: include/net/netlink.h:1081
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/dcb/dcbnl.c (ffffffff81aa9132)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (ffffffff81ab5088)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
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
In kernel/taskstats.c (ffffffff811989ac)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In lib/nlattr.c (ffffffff81563a4b)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
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
In net/core/gen_estimator.c (ffffffff81936191)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81955dcd)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8195bf43)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
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
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/filter.c (ffffffff819680d1)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/fib_rules.c (ffffffff8197f082)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff8198b192)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffff8199bb8b)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/sched/sch_api.c (ffffffff819a30cd)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff819ad50f)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (ffffffff819afa42)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff819b0578)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81a0679d)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81a11e99)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1de94)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/metrics.c (0)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a1fd24)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81a2904b)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff81a54a8b)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81a62021)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a99f66)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81a9b471)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aaec28)
Location: include/net/netlink.h:1081
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ab07a4)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab1d01)
Location: include/net/netlink.h:1081
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
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/dcb/dcbnl.c (ffffffff81ab54a2)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_del
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
In net/ncsi/ncsi-netlink.c (ffffffff81ac1428)
Location: include/net/netlink.h:1081
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
</details>
</li>
</ul>

## Differences
