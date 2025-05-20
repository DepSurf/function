# Function: <code>nla_get_u32</code>

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
In kernel/taskstats.c (ffffffff8113e959)
Location: include/net/netlink.h:992
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:992
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:992
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8172a3af)
Location: include/net/netlink.h:992
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/fib_rules.c (ffffffff8173a47f)
Location: include/net/netlink.h:992
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/act_api.c (ffffffff8174897a)
Location: include/net/netlink.h:992
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
```
In net/ipv4/route.c (ffffffff8175730a)
Location: include/net/netlink.h:992
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81791b22)
Location: include/net/netlink.h:992
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_frontend.c (ffffffff81799e09)
Location: include/net/netlink.h:992
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8179ceb5)
Location: include/net/netlink.h:992
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_rules.c (ffffffff817a6c70)
Location: include/net/netlink.h:992
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/addrconf.c (ffffffff817cf69d)
Location: include/net/netlink.h:992
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
```
In net/ipv6/addrlabel.c (ffffffff817d2c98)
Location: include/net/netlink.h:992
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff817d40fe)
Location: include/net/netlink.h:992
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180dd91)
Location: include/net/netlink.h:992
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8180feb2)
Location: include/net/netlink.h:992
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:992
Inline: True
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
In kernel/taskstats.c (ffffffff81146f89)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1016
Inline: True
```
```
In net/core/neighbour.c (ffffffff817918d8)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff81794a81)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817a6c39)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/act_api.c (ffffffff817b5b55)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
```
In net/ipv4/route.c (ffffffff817c35aa)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff817fec16)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_frontend.c (ffffffff81807b04)
Location: include/net/netlink.h:1016
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8180a866)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_rules.c (ffffffff81814976)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:1016
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8183db57)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff8184068f)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff818426e5)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818802c2)
Location: include/net/netlink.h:1016
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818829c2)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
In net/netlabel/netlabel_calipso.c (ffffffff818836d2)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:1016
Inline: True
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
In kernel/taskstats.c (ffffffff81150e33)
Location: include/net/netlink.h:1016
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1016
Inline: True
```
```
In net/core/neighbour.c (ffffffff817bf428)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff817c2301)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817d5740)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/lwt_bpf.c (ffffffff817d9d27)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/act_api.c (ffffffff817e555b)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
```
In net/ipv4/route.c (ffffffff817f2b9b)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff8182fb76)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_frontend.c (ffffffff81838baf)
Location: include/net/netlink.h:1016
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8183b976)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_rules.c (ffffffff81846115)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:1016
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8186f767)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff8187230f)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81874431)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81899a15)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b4b72)
Location: include/net/netlink.h:1016
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b7272)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
In net/netlabel/netlabel_calipso.c (ffffffff818b7f72)
Location: include/net/netlink.h:1016
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:1016
Inline: True
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
In kernel/taskstats.c (ffffffff81153373)
Location: include/net/netlink.h:1028
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1028
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1028
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff817e0a77)
Location: include/net/netlink.h:1028
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817f4bc5)
Location: include/net/netlink.h:1028
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/lwt_bpf.c (ffffffff817f9367)
Location: include/net/netlink.h:1028
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/cls_api.c (ffffffff81802954)
Location: include/net/netlink.h:1028
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
```
```
In net/sched/act_api.c (ffffffff818050ad)
Location: include/net/netlink.h:1028
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
```
In net/ipv4/route.c (ffffffff81813474)
Location: include/net/netlink.h:1028
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81851175)
Location: include/net/netlink.h:1028
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_frontend.c (ffffffff81859e89)
Location: include/net/netlink.h:1028
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff8185d289)
Location: include/net/netlink.h:1028
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_rules.c (ffffffff81867cdf)
Location: include/net/netlink.h:1028
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:1028
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8189450d)
Location: include/net/netlink.h:1028
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81897077)
Location: include/net/netlink.h:1028
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81899270)
Location: include/net/netlink.h:1028
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff818bfc0c)
Location: include/net/netlink.h:1028
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818db323)
Location: include/net/netlink.h:1028
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818ddb42)
Location: include/net/netlink.h:1028
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
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
In net/netlabel/netlabel_calipso.c (ffffffff818de852)
Location: include/net/netlink.h:1028
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:1028
Inline: True
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
In kernel/taskstats.c (ffffffff8115fb73)
Location: include/net/netlink.h:1071
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1071
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1071
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8185b30d)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818703bf)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/lwt_bpf.c (ffffffff81876c77)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/cls_api.c (ffffffff81880c26)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
```
```
In net/sched/act_api.c (ffffffff81882495)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/ipv4/route.c (ffffffff81892ac4)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff818d0db3)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_frontend.c (ffffffff818d9d8f)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff818dd2b2)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/fib_rules.c (ffffffff818e7dd0)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:1071
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81915985)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff819185b6)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff8191d84b)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_convert_metrics
```
```
In net/ipv6/seg6.c (ffffffff81942cdc)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (ffffffff8194f0cd)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81960f03)
Location: include/net/netlink.h:1071
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81963732)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
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
In net/netlabel/netlabel_calipso.c (ffffffff81964462)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:1071
Inline: True
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
In kernel/taskstats.c (ffffffff8116e648)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In net/core/net_namespace.c (ffffffff818871ad)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff818a2f50)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff818a6bed)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818c0690)
Location: include/net/netlink.h:1071
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818c844b)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/sched/sch_api.c (ffffffff818d1686)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffff818d3665)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff818d5fa5)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/ipv4/route.c (ffffffff818e6a54)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff819254c8)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_frontend.c (ffffffff81930834)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81934588)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv4/metrics.c (ffffffff8193c9b9)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/fib_rules.c (ffffffff8193e9e0)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81943196)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff8196cfd1)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff8196fddb)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff8197260a)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff8199bbec)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (ffffffff819a83b9)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819ba6f1)
Location: include/net/netlink.h:1071
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bcf7e)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
In net/netlabel/netlabel_calipso.c (ffffffff819bdcfe)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819c0c7d)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819ca884)
Location: include/net/netlink.h:1071
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff8117c118)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffff81506863)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/net_namespace.c (ffffffff818a83fc)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff818c40b1)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff818cac4f)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818e95e0)
Location: include/net/netlink.h:1214
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818f15bb)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/sched/sch_api.c (ffffffff818fca06)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffff818ffad3)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff819027a6)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/ipv4/route.c (ffffffff81913921)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff819542d8)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_frontend.c (ffffffff81960411)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81963e5e)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv4/metrics.c (ffffffff8196c6c2)
Location: include/net/netlink.h:1214
Inline: True
```
```
In net/ipv4/fib_rules.c (ffffffff8196e890)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81973273)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff819a2b04)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff819a59fb)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff819a8175)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff819d240c)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (ffffffff819def09)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f1373)
Location: include/net/netlink.h:1214
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f41be)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
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
In net/netlabel/netlabel_calipso.c (ffffffff819f4e9e)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819f802d)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a033c6)
Location: include/net/netlink.h:1214
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff81188fa8)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffff815347ef)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/net_namespace.c (ffffffff818f39e0)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81910228)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff81918389)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81938fea)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81942ee1)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffff8194c8fb)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_port_unsplit_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
```
In net/sched/sch_api.c (ffffffff8195c3a1)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffff81960337)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81963a0a)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/ipv4/route.c (ffffffff81975fc5)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff819b9b4e)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_frontend.c (ffffffff819c4fb7)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff819c8bee)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/metrics.c (ffffffff819d33d9)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff819d46fc)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (ffffffff819d8090)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff819dcd6a)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff81a0f167)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81a11f69)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a1537d)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81a4122d)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (ffffffff81a4da6f)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a60a33)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a63632)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
In net/netlabel/netlabel_calipso.c (ffffffff81a64362)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81a6755f)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a72642)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff81194ee8)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffff8155564b)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/net_namespace.c (ffffffff81925990)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81942898)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff8194a9a9)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8196beaa)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81974644)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config
  - net/core/drop_monitor.c:net_dm_cmd_config
```
```
In net/core/lwt_bpf.c (ffffffff81977e91)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffff819856fc)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_port_unsplit_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
```
In net/sched/sch_api.c (ffffffff819928f1)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffff81997417)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff8199a58a)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/ipv4/route.c (ffffffff819ac9d5)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff819f1e4e)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_frontend.c (ffffffff819fbb57)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff819ff7ae)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/metrics.c (ffffffff81a09f49)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a0b26c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (ffffffff81a0eb80)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81a13c07)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81a45ea7)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81a48b89)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a4bf4d)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81a77ead)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (ffffffff81a8463f)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a97663)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a9a1e2)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
In net/netlabel/netlabel_calipso.c (ffffffff81a9aee2)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81a9e07f)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa8e02)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff811aa91d)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffff815dec8a)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - lib/nlattr.c:nla_validate_int_range
```
```
In net/core/net_namespace.c (ffffffff819f9b2d)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81a1297e)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff81a1b1f3)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a3fdbe)
Location: include/net/netlink.h:1539
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81a497c4)
Location: include/net/netlink.h:1539
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a4d1c3)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (ffffffff81a532a0)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_netns_get
  - net/core/devlink.c:devlink_netns_get
  - net/core/devlink.c:devlink_netns_get
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_port_unsplit_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
```
In net/core/bpf_sk_storage.c (ffffffff81a6100e)
Location: include/net/netlink.h:1539
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81a69ef0)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffff81a6f757)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81a734e8)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ethtool/netlink.c (ffffffff81a85e42)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81a879aa)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
```
```
In net/ethtool/strset.c (ffffffff81a87cb5)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/linkmodes.c (ffffffff81a88e47)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rings.c (ffffffff81a8abed)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81a8b16d)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81a8bb7d)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/cabletest.c (ffffffff81a8cca7)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/route.c (ffffffff81a9657b)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81adfb2e)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae9e77)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81aeecfe)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af90f5)
Location: include/net/netlink.h:1539
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81afa69c)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/nexthop.c (ffffffff81afbffc)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (ffffffff81aff414)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_compare
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81b04881)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81b3cd47)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f824)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81b45a9d)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81b72310)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f68d)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b92944)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b95612)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b966e2)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81b99c3f)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5592)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb37f0)
Location: include/net/netlink.h:1539
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
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
In kernel/taskstats.c (ffffffff811a7ecd)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffff815fc97d)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
```
```
In drivers/thermal/thermal_netlink.c (ffffffff8195f0c7)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
```
```
In net/core/net_namespace.c (ffffffff819f967d)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81a12cce)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff81a1b383)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
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
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a42abe)
Location: include/net/netlink.h:1552
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81a4ef94)
Location: include/net/netlink.h:1552
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a52e83)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (ffffffff81a597d0)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_netns_get
  - net/core/devlink.c:devlink_netns_get
  - net/core/devlink.c:devlink_netns_get
  - net/core/devlink.c:devlink_nl_cmd_sb_occ_max_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_occ_snapshot_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_unsplit_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
```
In net/core/bpf_sk_storage.c (ffffffff81a698de)
Location: include/net/netlink.h:1552
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81a7261d)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffff81a73e7e)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_validate_change
  - net/sched/cls_api.c:tcf_qevent_init
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81a7c0e8)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/netlink/genetlink.c (ffffffff81a86a8b)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
```
```
In net/ethtool/netlink.c (ffffffff81a8f7bc)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81a9132a)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
```
```
In net/ethtool/strset.c (ffffffff81a91629)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/linkmodes.c (ffffffff81a9272f)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rings.c (ffffffff81a943aa)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81a9488c)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81a9521a)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/cabletest.c (ffffffff81a963b7)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/route.c (ffffffff81aa061b)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81aec9ae)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/fib_frontend.c (ffffffff81af6cd7)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81afbc5e)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05d55)
Location: include/net/netlink.h:1552
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81b07e4c)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/nexthop.c (ffffffff81b09896)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (ffffffff81b0d484)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_compare
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81b129f1)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81b4ba57)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81b4e2c6)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81b5443d)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81b81080)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f911)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_vrftable
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba2594)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba5262)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba6352)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81ba993f)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb4a62)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7c45)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
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
In kernel/taskstats.c (ffffffff811a8960)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffff815df64c)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81942627)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
```
```
In net/core/net_namespace.c (ffffffff819df7e9)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff819fa161)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff81a08c1b)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
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
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a2768e)
Location: include/net/netlink.h:1552
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81a33fd5)
Location: include/net/netlink.h:1552
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a38691)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (ffffffff81a3bf42)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_sb_occ_max_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_occ_snapshot_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_del_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_unsplit_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
```
In net/core/bpf_sk_storage.c (ffffffff81a5207e)
Location: include/net/netlink.h:1552
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81a5ae46)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffff81a63b01)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_init
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81a64d19)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/genetlink.c (ffffffff81a6effc)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
```
```
In net/ethtool/netlink.c (ffffffff81a78ea8)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81a7ab2c)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
```
```
In net/ethtool/strset.c (ffffffff81a7ae49)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/linkmodes.c (ffffffff81a7c2e1)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rings.c (ffffffff81a7ddba)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81a7e29c)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81a7eccb)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/eee.c (ffffffff81a7f94d)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81a7fe3f)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ethtool/eeprom.c (ffffffff81a81c77)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_parse_request
  - net/ethtool/eeprom.c:eeprom_parse_request
```
```
In net/ipv4/route.c (ffffffff81a8b54b)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81ad68de)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae2427)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae73be)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af15b3)
Location: include/net/netlink.h:1552
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81af365c)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/nexthop.c (ffffffff81af5036)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:__nh_valid_dump_req
  - net/ipv4/nexthop.c:__nh_valid_dump_req
  - net/ipv4/nexthop.c:__nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (ffffffff81afb254)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_compare
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81b00111)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81b39607)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81b3bff9)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81b41b9d)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81b6fc90)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (ffffffff81b7e4e4)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_vrftable
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b91684)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b943bf)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b954df)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81b98ad1)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba3a42)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb93b5)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
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
In kernel/taskstats.c (ffffffff811d24c0)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffff8164b1fb)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8191a833)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_newlink
```
```
In drivers/thermal/thermal_netlink.c (ffffffff819e6f67)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
```
```
In net/core/net_namespace.c (ffffffff81a8fbc9)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81aabeed)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff81abaa3b)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
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
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81adc42e)
Location: include/net/netlink.h:1552
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81ae9adf)
Location: include/net/netlink.h:1552
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81aee501)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (ffffffff81af2562)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_sb_occ_max_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_occ_snapshot_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_del_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_unsplit_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0ad0e)
Location: include/net/netlink.h:1552
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81b13ff6)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffff81b1ce81)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_init
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81b1dfe9)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/genetlink.c (ffffffff81b28a3c)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
```
```
In net/ethtool/netlink.c (ffffffff81b33178)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81b34f4a)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
```
```
In net/ethtool/strset.c (ffffffff81b353a9)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/linkmodes.c (ffffffff81b36621)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rings.c (ffffffff81b37f1e)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81b383af)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81b38c25)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/eee.c (ffffffff81b397b2)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81b39c0f)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ethtool/eeprom.c (ffffffff81b3b8f7)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_parse_request
  - net/ethtool/eeprom.c:eeprom_parse_request
```
```
In net/ipv4/route.c (ffffffff81b4648b)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81b96573)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba1c06)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba71be)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1ac3)
Location: include/net/netlink.h:1552
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81bb3b6c)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/nexthop.c (ffffffff81bb5936)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:__nh_valid_dump_req
  - net/ipv4/nexthop.c:__nh_valid_dump_req
  - net/ipv4/nexthop.c:__nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (ffffffff81bbc694)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_compare
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81bc1241)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81bffdb7)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81c028e9)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81c098cd)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81c37de0)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ioam6.c (ffffffff81c39891)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/seg6_local.c (ffffffff81c49f24)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_vrftable
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5de24)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60b5f)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61cdf)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81c65741)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c71042)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81c88a85)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
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
In kernel/taskstats.c (ffffffff81206b96)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffff81761c28)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6fc25)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_newlink
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81b4c597)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
```
```
In net/core/net_namespace.c (ffffffff81c0597a)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81c24351)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81c2d054)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
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
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81c5d8b2)
Location: include/net/netlink.h:1552
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81c6c33f)
Location: include/net/netlink.h:1552
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81c713e8)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (ffffffff81c76512)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_sb_occ_max_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_occ_snapshot_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_del_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
```
In net/core/bpf_sk_storage.c (ffffffff81c91367)
Location: include/net/netlink.h:1552
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81c9b4bc)
Location: include/net/netlink.h:1552
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81ca10e1)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_init
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81ca59cb)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/genetlink.c (ffffffff81cb133f)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
```
```
In net/ethtool/netlink.c (ffffffff81cbe368)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81cc0756)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
```
```
In net/ethtool/strset.c (ffffffff81cc0c36)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/linkmodes.c (ffffffff81cc1f70)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rings.c (ffffffff81cc3b44)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81cc411f)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81cc49d3)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/eee.c (ffffffff81cc55e6)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81cc5ab9)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ethtool/eeprom.c (ffffffff81cc7917)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_parse_request
  - net/ethtool/eeprom.c:eeprom_parse_request
```
```
In net/ipv4/route.c (ffffffff81cd3307)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81d26a19)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81d342da)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81d39b0a)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d4519a)
Location: include/net/netlink.h:1552
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81d473bb)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/nexthop.c (ffffffff81d49cf0)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:__nh_valid_dump_req
  - net/ipv4/nexthop.c:__nh_valid_dump_req
  - net/ipv4/nexthop.c:__nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (ffffffff81d50c23)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_compare
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81d55bf8)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81d9989a)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81d9c501)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81da4a95)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81dd59c4)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ioam6.c (ffffffff81dd7499)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/seg6_local.c (ffffffff81de97be)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_vrftable
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81deb7d8)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00102)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e03092)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e04312)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81e0845a)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e14c32)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2ef39)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_entry
```
```
In net/mptcp/pm_userspace.c (ffffffff81e36065)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
```
In net/mctp/device.c (ffffffff81e37e98)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_set_link_af
```
```
In net/mctp/route.c (ffffffff81e39c8f)
Location: include/net/netlink.h:1552
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_newroute
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
In kernel/taskstats.c (ffffffff8124eed6)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffff81890859)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_range_unsigned
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c02aa5)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_newlink
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81ce41f7)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
```
```
In net/core/net_namespace.c (ffffffff81db524a)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81dd6981)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81de01b4)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
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
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81e14092)
Location: include/net/netlink.h:1601
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81e23d2f)
Location: include/net/netlink.h:1601
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81e29498)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (ffffffff81e2ed12)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_sb_occ_max_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_occ_snapshot_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_rate_set
  - net/core/devlink.c:devlink_nl_rate_set
  - net/core/devlink.c:devlink_nl_cmd_port_del_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4c8b7)
Location: include/net/netlink.h:1601
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81e579f2)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffff81e5d141)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_init
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81e63a6b)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/genetlink.c (ffffffff81e6fba0)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
```
```
In net/ethtool/netlink.c (ffffffff81e7ce28)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81e7f3af)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
```
```
In net/ethtool/strset.c (ffffffff81e7f91a)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/linkmodes.c (ffffffff81e80d60)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rss.c (ffffffff81e80f22)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ethtool/rss.c:rss_parse_request
```
```
In net/ethtool/rings.c (ffffffff81e82ee4)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81e83508)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81e83ea9)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/eee.c (ffffffff81e84b36)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81e85069)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ethtool/eeprom.c (ffffffff81e86fc7)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_parse_request
  - net/ethtool/eeprom.c:eeprom_parse_request
```
```
In net/ethtool/pse-pd.c (ffffffff81e886c5)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ethtool/pse-pd.c:ethnl_set_pse
```
```
In net/ipv4/route.c (ffffffff81e934f7)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81eee3a9)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81efc7aa)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81f02422)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0da88)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
```
```
In net/ipv4/metrics.c (ffffffff81f10807)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/nexthop.c (ffffffff81f13350)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:__nh_valid_dump_req
  - net/ipv4/nexthop.c:__nh_valid_dump_req
  - net/ipv4/nexthop.c:__nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (ffffffff81f1a9f3)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_compare
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81f1ff78)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81f685da)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81f6b1f1)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81f73f45)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81fa7170)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ioam6.c (ffffffff81fa8e69)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fad2aa)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
```
```
In net/ipv6/seg6_local.c (ffffffff81fbcba1)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_flavors
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_vrftable
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbf438)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd4f35)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd7ff2)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd92f2)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81fdd9ea)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81febb42)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff82007619)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_entry
```
```
In net/mptcp/pm_userspace.c (ffffffff8200ed85)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
```
In net/mctp/device.c (ffffffff820110b8)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_set_link_af
```
```
In net/mctp/route.c (ffffffff82012d6f)
Location: include/net/netlink.h:1601
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_newroute
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
In kernel/taskstats.c (ffffffff81266286)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffff818d2d5d)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_range_unsigned
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c68155)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_newlink
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81d4c827)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
```
```
In net/core/net_namespace.c (ffffffff81e2581a)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81e477b1)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81e51884)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
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
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/netdev-genl.c (ffffffff81e7d0d2)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
```
```
In net/core/fib_rules.c (ffffffff81e879a2)
Location: include/net/netlink.h:1602
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81e9909e)
Location: include/net/netlink.h:1602
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81e9eac8)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea7fd5)
Location: include/net/netlink.h:1602
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81eb1d38)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffff81eb9cf1)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_init
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81ebfb01)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/genetlink.c (ffffffff81ecb470)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
```
```
In net/ethtool/netlink.c (ffffffff81ed91fd)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81edb99f)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
```
```
In net/ethtool/strset.c (ffffffff81edbfc7)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/linkmodes.c (ffffffff81edcce9)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes_validate
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rss.c (ffffffff81edd632)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ethtool/rss.c:rss_parse_request
```
```
In net/ethtool/rings.c (ffffffff81edf6ba)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81edfc67)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81ee01ca)
Location: include/net/netlink.h:1602
Inline: True
```
```
In net/ethtool/pause.c (ffffffff81ee0e64)
Location: include/net/netlink.h:1602
Inline: True
```
```
In net/ethtool/eee.c (ffffffff81ee1498)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81ee1999)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ethtool/eeprom.c (ffffffff81ee3a27)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_parse_request
  - net/ethtool/eeprom.c:eeprom_parse_request
```
```
In net/ethtool/stats.c (ffffffff81ee40e5)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_parse_request
```
```
In net/ethtool/mm.c (ffffffff81ee54ca)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ethtool/mm.c:ethnl_set_mm
  - net/ethtool/mm.c:ethnl_set_mm
```
```
In net/ethtool/pse-pd.c (ffffffff81ee5f95)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ethtool/pse-pd.c:ethnl_set_pse
```
```
In net/ethtool/plca.c (ffffffff81ee65db)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ethtool/plca.c:ethnl_set_plca
  - net/ethtool/plca.c:ethnl_set_plca
  - net/ethtool/plca.c:ethnl_set_plca
  - net/ethtool/plca.c:ethnl_set_plca
  - net/ethtool/plca.c:ethnl_set_plca
  - net/ethtool/plca.c:ethnl_set_plca
```
```
In net/ipv4/route.c (ffffffff81ef1c97)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81f4dd69)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5c1da)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81f61e82)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6d728)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
```
```
In net/ipv4/metrics.c (ffffffff81f704f7)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/nexthop.c (ffffffff81f73020)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:__nh_valid_dump_req
  - net/ipv4/nexthop.c:__nh_valid_dump_req
  - net/ipv4/nexthop.c:__nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (ffffffff81f7a673)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_compare
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81f7fa78)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81fc86ca)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81fcb2f2)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81fd4025)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff820079d0)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ioam6.c (ffffffff820097f1)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200da6a)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
```
```
In net/ipv6/seg6_local.c (ffffffff8201dc81)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_flavors
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_vrftable
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820203c8)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/devlink/leftover.c (ffffffff82030c32)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_trap_policer_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_policer_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_group_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
  - net/devlink/leftover.c:devlink_nl_cmd_region_del
  - net/devlink/leftover.c:devlink_nl_cmd_region_del
  - net/devlink/leftover.c:devlink_nl_cmd_region_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_occ_max_clear_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_occ_snapshot_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_pool_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_pool_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_pool_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_get_doit
  - net/devlink/leftover.c:devlink_nl_rate_set
  - net/devlink/leftover.c:devlink_nl_rate_set
  - net/devlink/leftover.c:devlink_nl_cmd_port_new_doit
  - net/devlink/leftover.c:devlink_nl_cmd_port_new_doit
  - net/devlink/leftover.c:devlink_nl_cmd_port_split_doit
  - net/devlink/leftover.c:devlink_linecard_get_from_info
  - net/devlink/leftover.c:devlink_rate_get_from_info
  - net/devlink/leftover.c:devlink_port_get_from_info
```
```
In net/devlink/dev.c (ffffffff82044989)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_cmd_reload
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82050bd5)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053ce2)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82054fc2)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff82059c1a)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82067de2)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff820839b9)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_entry
```
```
In net/mptcp/pm_userspace.c (ffffffff8208b975)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
```
In net/mctp/device.c (ffffffff8208de78)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_set_link_af
```
```
In net/mctp/route.c (ffffffff8208fb98)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_newroute
```
```
In net/handshake/netlink.c (ffffffff8209285a)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_nl_done_doit
  - net/handshake/netlink.c:handshake_nl_done_doit
  - net/handshake/netlink.c:handshake_nl_accept_doit
```
```
In net/handshake/tlshd.c (ffffffff82093ddb)
Location: include/net/netlink.h:1602
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_done
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
In kernel/taskstats.c (ffffffff81280176)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffff81924e1c)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_range_unsigned
```
```
In drivers/net/netkit.c (ffffffff81ce5527)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_change_link
  - drivers/net/netkit.c:netkit_change_link
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/netkit.c:netkit_new_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81e03507)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81ebbb78)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_pin_pre_doit
  - drivers/dpll/dpll_netlink.c:dpll_pre_doit
  - drivers/dpll/dpll_netlink.c:dpll_device_find_from_nlattr
  - drivers/dpll/dpll_netlink.c:dpll_pin_find_from_nlattr
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_pin_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_pin_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set
```
```
In net/core/net_namespace.c (ffffffff81ee377a)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81f06461)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81f109f7)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
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
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/netdev-genl.c (ffffffff81f3e1a1)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_queue_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_queue_get_doit
  - net/core/netdev-genl.c:netdev_nl_queue_get_doit
  - net/core/netdev-genl.c:netdev_nl_queue_get_doit
  - net/core/netdev-genl.c:netdev_nl_napi_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_napi_get_doit
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
```
```
In net/core/page_pool_user.c (ffffffff81f46028)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/core/page_pool_user.c:netdev_nl_page_pool_get_doit
  - net/core/page_pool_user.c:netdev_nl_page_pool_stats_get_doit
```
```
In net/core/fib_rules.c (ffffffff81f499b8)
Location: include/net/netlink.h:1678
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81f5b75e)
Location: include/net/netlink.h:1678
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81f6123b)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6aa8b)
Location: include/net/netlink.h:1678
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81f747e7)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffff81f7cf61)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_init
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81f82cb1)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/genetlink.c (ffffffff81f8e960)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
```
```
In net/ethtool/netlink.c (ffffffff81f9d0c0)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81f9f766)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_compact_sanity_checks
  - net/ethtool/bitset.c:ethnl_parse_bit
```
```
In net/ethtool/strset.c (ffffffff81f9fd90)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/linkmodes.c (ffffffff81fa0ab9)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes_validate
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rss.c (ffffffff81fa1402)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ethtool/rss.c:rss_parse_request
```
```
In net/ethtool/rings.c (ffffffff81fa353a)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81fa3b07)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81fa405a)
Location: include/net/netlink.h:1678
Inline: True
```
```
In net/ethtool/pause.c (ffffffff81fa4cf4)
Location: include/net/netlink.h:1678
Inline: True
```
```
In net/ethtool/eee.c (ffffffff81fa5328)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81fa582c)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ethtool/eeprom.c (ffffffff81fa7807)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_parse_request
  - net/ethtool/eeprom.c:eeprom_parse_request
```
```
In net/ethtool/stats.c (ffffffff81fa7ec5)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_parse_request
```
```
In net/ethtool/mm.c (ffffffff81fa92aa)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ethtool/mm.c:ethnl_set_mm
  - net/ethtool/mm.c:ethnl_set_mm
```
```
In net/ethtool/pse-pd.c (ffffffff81fa9d65)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ethtool/pse-pd.c:ethnl_set_pse
```
```
In net/ethtool/plca.c (ffffffff81faa430)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ethtool/plca.c:ethnl_set_plca
  - net/ethtool/plca.c:ethnl_set_plca
  - net/ethtool/plca.c:ethnl_set_plca
  - net/ethtool/plca.c:ethnl_set_plca
  - net/ethtool/plca.c:ethnl_set_plca
```
```
In net/ipv4/route.c (ffffffff81fb5de7)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff82013e9b)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff8202273a)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff82028452)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82033e78)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
```
```
In net/ipv4/metrics.c (ffffffff82036c27)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/nexthop.c (ffffffff82039023)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:__nh_valid_dump_req
  - net/ipv4/nexthop.c:__nh_valid_dump_req
  - net/ipv4/nexthop.c:__nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (ffffffff82040d73)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_compare
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff820460f8)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff82095dfa)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff82098ad2)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff820a1937)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff820d6860)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ioam6.c (ffffffff820d8791)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820dd4ea)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
```
```
In net/ipv6/seg6_local.c (ffffffff820ecc64)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_flavors
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_vrftable
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820ef4fb)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/devlink/netlink.c (ffffffff8210147d)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_notify_filter_set_doit
```
```
In net/devlink/dev.c (ffffffff82104249)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_reload_doit
```
```
In net/devlink/port.c (ffffffff82108000)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_new_doit
  - net/devlink/port.c:devlink_nl_port_new_doit
  - net/devlink/port.c:devlink_nl_port_split_doit
  - net/devlink/port.c:devlink_port_get_from_info
```
```
In net/devlink/sb.c (ffffffff8210a3e2)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/devlink/sb.c:devlink_nl_sb_occ_max_clear_doit
  - net/devlink/sb.c:devlink_nl_sb_occ_snapshot_doit
  - net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_set_doit
  - net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_set_doit
  - net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_get_doit
  - net/devlink/sb.c:devlink_nl_sb_port_pool_set_doit
  - net/devlink/sb.c:devlink_nl_sb_port_pool_set_doit
  - net/devlink/sb.c:devlink_nl_sb_port_pool_get_doit
  - net/devlink/sb.c:devlink_nl_sb_pool_set_doit
  - net/devlink/sb.c:devlink_nl_sb_pool_set_doit
  - net/devlink/sb.c:devlink_nl_sb_pool_get_doit
  - net/devlink/sb.c:devlink_nl_sb_get_doit
```
```
In net/devlink/param.c (ffffffff8210da59)
Location: include/net/netlink.h:1678
Inline: True
```
```
In net/devlink/region.c (ffffffff82111104)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_new_doit
  - net/devlink/region.c:devlink_nl_region_new_doit
  - net/devlink/region.c:devlink_nl_region_del_doit
  - net/devlink/region.c:devlink_nl_region_del_doit
  - net/devlink/region.c:devlink_nl_region_get_doit
```
```
In net/devlink/health.c (ffffffff8211381e)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_get_dump_one
```
```
In net/devlink/trap.c (ffffffff821177a2)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_set_doit
  - net/devlink/trap.c:devlink_nl_trap_policer_get_doit
  - net/devlink/trap.c:devlink_nl_trap_group_set_doit
```
```
In net/devlink/rate.c (ffffffff82118638)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/devlink/rate.c:devlink_nl_rate_set
  - net/devlink/rate.c:devlink_nl_rate_set
```
```
In net/devlink/linecard.c (ffffffff8211a76f)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/devlink/linecard.c:devlink_nl_linecard_set_doit
  - net/devlink/linecard.c:devlink_nl_linecard_get_doit
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff821232b4)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff821264c1)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
```
```
In net/netlabel/netlabel_calipso.c (ffffffff821278a1)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
```
```
In net/dcb/dcbnl.c (ffffffff8212c79d)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213b062)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff8215c129)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_limits_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_limits_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_entry
```
```
In net/mptcp/pm_userspace.c (ffffffff82161775)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit
```
```
In net/mctp/device.c (ffffffff8216433b)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_set_link_af
```
```
In net/mctp/route.c (ffffffff821660ab)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_newroute
```
```
In net/handshake/netlink.c (ffffffff82169170)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_nl_done_doit
  - net/handshake/netlink.c:handshake_nl_accept_doit
```
```
In net/handshake/tlshd.c (ffffffff8216a706)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_done
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
In kernel/taskstats.c (ffff80001020d65c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffff800010661a08)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/net_namespace.c (ffff800010bc1d3c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffff800010be696c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffff800010bed8cc)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffff800010c12588)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/core/drop_monitor.c (ffff800010c1a514)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config
  - net/core/drop_monitor.c:net_dm_cmd_config
```
```
In net/core/lwt_bpf.c (ffff800010c1e704)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffff800010c2dd30)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_port_unsplit_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
```
In net/sched/sch_api.c (ffff800010c3ed10)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffff800010c4458c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffff800010c477a4)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/ipv4/route.c (ffff800010c5cb5c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffff800010ca8038)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_frontend.c (ffff800010cb3ba0)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffff800010cb7c80)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/metrics.c (ffff800010cc3308)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/ipv4/nexthop.c (ffff800010cc4854)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (ffff800010cc89a0)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffff800010cce2f0)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffff800010d0892c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffff800010d0bfb4)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffff800010d114a0)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffff800010d414e0)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (ffff800010d50638)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d66c98)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d69e30)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
In net/netlabel/netlabel_calipso.c (ffff800010d6ab40)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffff800010d6e9f0)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d3dc)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (c044c058)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (c080aa5c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/net_namespace.c (c0cdd21c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (c0cffbe8)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (c0d05f18)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (c0d2a0c0)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl2rule
  - net/core/fib_rules.c:fib_nl2rule
  - net/core/fib_rules.c:fib_nl2rule
  - net/core/fib_rules.c:fib_nl2rule
  - net/core/fib_rules.c:fib_nl2rule
  - net/core/fib_rules.c:fib_nl2rule
  - net/core/fib_rules.c:fib_nl2rule
```
```
In net/core/drop_monitor.c (c0d325d8)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config
  - net/core/drop_monitor.c:net_dm_cmd_config
```
```
In net/core/lwt_bpf.c (c0d36758)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/core/devlink.c (c0d44ce8)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_port_unsplit_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
```
In net/sched/sch_api.c (c0d5075c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (c0d5507c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (c0d585a0)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/ipv4/route.c (c0d6c290)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (c0db29dc)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_frontend.c (c0dbee88)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (c0dc3ad0)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv4/metrics.c (c0dceb14)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/ipv4/nexthop.c (c0dd0288)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (c0dd3d78)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (c0dd94c8)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (c0e0f02c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (c0e11d64)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (c0e158a0)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (c0e43ecc)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (c0e511b0)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (c0e65350)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e67e24)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
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
```
```
In net/netlabel/netlabel_calipso.c (c0e690bc)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (c0e6c950)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (c0e77288)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (c00000000028b658)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (c00000000081571c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/net_namespace.c (c000000000c9b538)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (c000000000cc6154)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (c000000000cd0478)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (c000000000cff59c)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/core/drop_monitor.c (c000000000d0a94c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config
  - net/core/drop_monitor.c:net_dm_cmd_config
```
```
In net/core/lwt_bpf.c (c000000000d10744)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (c000000000d253b8)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_port_unsplit_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
```
In net/sched/sch_api.c (c000000000d390dc)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (c000000000d3fa8c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (c000000000d4466c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/ipv4/route.c (c000000000d5f0f8)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (c000000000db9f20)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_frontend.c (c000000000dcad20)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (c000000000dd0440)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/metrics.c (c000000000ddeec8)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/ipv4/nexthop.c (c000000000de08f4)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (c000000000de5d8c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (c000000000deae9c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (c000000000e32e4c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (c000000000e368d8)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (c000000000e3a910)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (c000000000e760cc)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (c000000000e881cc)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea35f0)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea6c54)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
In net/netlabel/netlabel_calipso.c (c000000000ea7f58)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (c000000000ead39c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebbacc)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffe00016e6c4)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffe00048e166)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/net_namespace.c (ffffffe00074ed8e)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffe000769e84)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffe0007705cc)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffe00078e43c)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/core/drop_monitor.c (ffffffe000794aba)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config
  - net/core/drop_monitor.c:net_dm_cmd_config
```
```
In net/core/lwt_bpf.c (ffffffe0007983de)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffe0007a4da0)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_port_unsplit_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
```
In net/sched/sch_api.c (ffffffe0007aeb78)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffe0007b2888)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffe0007b54da)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/ipv4/route.c (ffffffe0007c5998)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffe0008015a2)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_frontend.c (ffffffe00080bb06)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffe00080ed64)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/metrics.c (ffffffe00081868a)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffe000819caa)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (ffffffe00081cc14)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffe00082067e)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffe00085086a)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffe000852ee0)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffe000856174)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffe00087cc14)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (ffffffe000888bea)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a602)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089ca94)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
In net/netlabel/netlabel_calipso.c (ffffffe00089d5a8)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
```
```
In net/dcb/dcbnl.c (ffffffe0008a07f6)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008aa2cc)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff8118d508)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffff8154dc2b)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/net_namespace.c (ffffffff818c5990)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff818e2868)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff818ea979)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8190be7a)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81914614)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config
  - net/core/drop_monitor.c:net_dm_cmd_config
```
```
In net/core/lwt_bpf.c (ffffffff81917d01)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffff8192556c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_port_unsplit_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
```
In net/sched/sch_api.c (ffffffff81932761)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffff81937287)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff8193a3fa)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/ipv4/route.c (ffffffff8194c845)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81991bee)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_frontend.c (ffffffff8199b8f7)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff8199f54e)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/metrics.c (ffffffff819a9ce9)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff819ab00c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (ffffffff819ae920)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff819b355a)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff819e5537)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff819e8219)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff819eb5dd)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81a1753d)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (ffffffff81a23ccf)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a369f3)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a39572)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
In net/netlabel/netlabel_calipso.c (ffffffff81a3a272)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81a3d40f)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a48192)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff81180628)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffff8153df0b)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/vxlan.c (ffffffff8176e975)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_validate
  - drivers/net/vxlan.c:vxlan_validate
  - drivers/net/vxlan.c:vxlan_fdb_get
  - drivers/net/vxlan.c:vxlan_fdb_parse
  - drivers/net/vxlan.c:vxlan_fdb_parse
  - drivers/net/vxlan.c:vxlan_fdb_parse
```
```
In net/core/net_namespace.c (ffffffff8187f8d0)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff8189c6a8)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff818a47b9)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818c5c3a)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff818ce3d4)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config
  - net/core/drop_monitor.c:net_dm_cmd_config
```
```
In net/core/lwt_bpf.c (ffffffff818d1ab1)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffff818df31c)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_port_unsplit_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
```
In net/sched/sch_api.c (ffffffff818ec261)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffff818f0d87)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff818f3efa)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/ipv4/route.c (ffffffff81906335)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff8194b6ae)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_frontend.c (ffffffff819553b7)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff8195900e)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/metrics.c (ffffffff819637a9)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81964acc)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (ffffffff8196af50)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff8196fb8a)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff819a22f7)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff819a4fd9)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff819a839d)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff819d42fd)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (ffffffff819e0a8f)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f3613)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f6192)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
In net/netlabel/netlabel_calipso.c (ffffffff819f6e92)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819f9fff)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a04d82)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff8118b2d8)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffff8154996b)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/net_namespace.c (ffffffff81916990)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81933898)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff8193b9a9)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8195ceaa)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81965644)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config
  - net/core/drop_monitor.c:net_dm_cmd_config
```
```
In net/core/lwt_bpf.c (ffffffff81968e91)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffff819766fc)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_port_unsplit_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
```
In net/sched/sch_api.c (ffffffff819838f1)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffff81988417)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff8198b58a)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/ipv4/route.c (ffffffff819b7015)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff819fc48e)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_frontend.c (ffffffff81a06197)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81a09dee)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/metrics.c (ffffffff81a14589)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a158ac)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (ffffffff81a191c0)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81a1ddfa)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff81a4ffb7)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81a52c99)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a5605d)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81a81fbd)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (ffffffff81a8e74f)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa28a3)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa5422)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
In net/netlabel/netlabel_calipso.c (ffffffff81aa6122)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81aa92bf)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4042)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff81198c48)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In lib/nlattr.c (ffffffff815637bb)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/net_namespace.c (ffffffff81937ba0)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff819551c8)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff8195d229)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8197f0fa)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81987884)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config
  - net/core/drop_monitor.c:net_dm_cmd_config
```
```
In net/core/lwt_bpf.c (ffffffff8198b271)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/core/devlink.c (ffffffff81998bec)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_port_unsplit_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
```
In net/sched/sch_api.c (ffffffff819a5e41)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffff819aa687)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff819addfa)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/ipv4/route.c (ffffffff819c0895)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81a067fe)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_frontend.c (ffffffff81a10807)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81a1459e)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/metrics.c (ffffffff81a1ef99)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a202ec)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/fib_rules.c (ffffffff81a23c60)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81a28ef7)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81a5bfb7)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
```
In net/ipv6/addrlabel.c (ffffffff81a5ec17)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a6208d)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81a8e8cd)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (ffffffff81a9b4bf)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_oif
  - net/ipv6/seg6_local.c:parse_nla_iif
  - net/ipv6/seg6_local.c:parse_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aaec13)
Location: include/net/netlink.h:1472
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab17c2)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
In net/netlabel/netlabel_calipso.c (ffffffff81ab24c2)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81ab562f)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac03e2)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
</details>
</li>
</ul>

## Differences
