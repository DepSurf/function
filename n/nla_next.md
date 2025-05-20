# Function: <code>nla_next</code>

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
In lib/nlattr.c (ffffffff814155b3)
Location: include/net/netlink.h:703
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:nla_validate
  - lib/nlattr.c:nla_parse
```
```
In net/core/rtnetlink.c (ffffffff81729bee)
Location: include/net/netlink.h:703
Inline: True
Inline callers:
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/sched/ematch.c (ffffffff81749b53)
Location: include/net/netlink.h:703
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ipv4/devinet.c (ffffffff8178f8c8)
Location: include/net/netlink.h:703
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81799dd0)
Location: include/net/netlink.h:703
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8179cecf)
Location: include/net/netlink.h:703
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff817d4b85)
Location: include/net/netlink.h:703
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818103fb)
Location: include/net/netlink.h:703
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
In net/dcb/dcbnl.c (ffffffff81814ef4)
Location: include/net/netlink.h:703
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
In lib/nlattr.c (ffffffff8145d2be)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:nla_parse
  - lib/nlattr.c:nla_validate
```
```
In net/core/rtnetlink.c (ffffffff81794840)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/sched/ematch.c (ffffffff817b6ac3)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ipv4/devinet.c (ffffffff817fcfb8)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81807ab9)
Location: include/net/netlink.h:714
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8180a8ab)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/ipmr.c (ffffffff8181787f)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff81842a91)
Location: include/net/netlink.h:714
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81882c43)
Location: include/net/netlink.h:714
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
In net/dcb/dcbnl.c (ffffffff81887dc4)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
```
```
In net/switchdev/switchdev.c (ffffffff8188b856)
Location: include/net/netlink.h:714
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
In lib/nlattr.c (ffffffff8147bdae)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:nla_parse
  - lib/nlattr.c:nla_validate
```
```
In net/core/rtnetlink.c (ffffffff817c20c0)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/sched/ematch.c (ffffffff817e6553)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ipv4/devinet.c (ffffffff8182df18)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81838b5b)
Location: include/net/netlink.h:714
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8183b9bb)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/ipmr.c (ffffffff818490ef)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff81874801)
Location: include/net/netlink.h:714
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b74f3)
Location: include/net/netlink.h:714
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
In net/dcb/dcbnl.c (ffffffff818bc5e4)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
```
```
In net/switchdev/switchdev.c (ffffffff818bfb35)
Location: include/net/netlink.h:714
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
In lib/nlattr.c (ffffffff814850ea)
Location: include/net/netlink.h:723
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:nla_parse
  - lib/nlattr.c:nla_validate
```
```
In net/core/rtnetlink.c (ffffffff817e07a7)
Location: include/net/netlink.h:723
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/sched/ematch.c (ffffffff81806081)
Location: include/net/netlink.h:723
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8184fbaa)
Location: include/net/netlink.h:723
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81859e3d)
Location: include/net/netlink.h:723
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff8185d2be)
Location: include/net/netlink.h:723
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/ipmr.c (ffffffff8186c841)
Location: include/net/netlink.h:723
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff818995a6)
Location: include/net/netlink.h:723
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818ddf06)
Location: include/net/netlink.h:723
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/dcb/dcbnl.c (ffffffff818e2fe9)
Location: include/net/netlink.h:723
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
```
```
In net/switchdev/switchdev.c (ffffffff818e635a)
Location: include/net/netlink.h:723
Inline: True
Inline callers:
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
In lib/nlattr.c (ffffffff814c115a)
Location: include/net/netlink.h:729
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:nla_parse
  - lib/nlattr.c:nla_validate
```
```
In net/core/rtnetlink.c (ffffffff8185b027)
Location: include/net/netlink.h:729
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/sched/ematch.c (ffffffff81884db1)
Location: include/net/netlink.h:729
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff818cf7da)
Location: include/net/netlink.h:729
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff818d9d43)
Location: include/net/netlink.h:729
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff818dd2eb)
Location: include/net/netlink.h:729
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ipmr.c (ffffffff818ed127)
Location: include/net/netlink.h:729
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff8191a8ea)
Location: include/net/netlink.h:729
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_convert_metrics
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81963af6)
Location: include/net/netlink.h:729
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/dcb/dcbnl.c (ffffffff81968ddc)
Location: include/net/netlink.h:729
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In lib/nlattr.c (ffffffff814f269f)
Location: include/net/netlink.h:729
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff818a6969)
Location: include/net/netlink.h:729
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/sched/ematch.c (ffffffff818d8991)
Location: include/net/netlink.h:729
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819254e4)
Location: include/net/netlink.h:729
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff819307df)
Location: include/net/netlink.h:729
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff819338c1)
Location: include/net/netlink.h:729
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff8193c9d6)
Location: include/net/netlink.h:729
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff819430d4)
Location: include/net/netlink.h:729
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bd2b3)
Location: include/net/netlink.h:729
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
In net/dcb/dcbnl.c (ffffffff819c262b)
Location: include/net/netlink.h:729
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In lib/nlattr.c (ffffffff815066bc)
Location: include/net/netlink.h:872
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff818ca1c9)
Location: include/net/netlink.h:872
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/sched/ematch.c (ffffffff81905181)
Location: include/net/netlink.h:872
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819542f4)
Location: include/net/netlink.h:872
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff8195fbe2)
Location: include/net/netlink.h:872
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81962db1)
Location: include/net/netlink.h:872
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff8196c6df)
Location: include/net/netlink.h:872
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8197313e)
Location: include/net/netlink.h:872
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f4552)
Location: include/net/netlink.h:872
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/dcb/dcbnl.c (ffffffff819f9b8b)
Location: include/net/netlink.h:872
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In lib/nlattr.c (ffffffff8153415d)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81917186)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/core/devlink.c (ffffffff81951cc6)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (ffffffff819663cf)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819b9b6e)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff819c6577)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff819c8c13)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff819d33fb)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819dcc44)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a63973)
Location: include/net/netlink.h:1106
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
In net/dcb/dcbnl.c (ffffffff81a690e6)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In lib/nlattr.c (ffffffff81554f9d)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff819497c6)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/core/devlink.c (ffffffff81988706)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (ffffffff8199ce5f)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819f1e6e)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff819fd127)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff819ff7d3)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff81a09f6b)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a13c28)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a9a523)
Location: include/net/netlink.h:1106
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
In net/dcb/dcbnl.c (ffffffff81a9fa46)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In lib/nlattr.c (ffffffff815de4dd)
Location: include/net/netlink.h:1158
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81a19b56)
Location: include/net/netlink.h:1158
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/core/devlink.c (ffffffff81a516f7)
Location: include/net/netlink.h:1158
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_compat_running_version
  - net/core/devlink.c:__devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81a60fab)
Location: include/net/netlink.h:1158
Inline: True
```
```
In net/sched/ematch.c (ffffffff81a76029)
Location: include/net/netlink.h:1158
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a8795b)
Location: include/net/netlink.h:1158
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/strset.c (ffffffff81a87cbf)
Location: include/net/netlink.h:1158
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81adfb4e)
Location: include/net/netlink.h:1158
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81aebb33)
Location: include/net/netlink.h:1158
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81aeed22)
Location: include/net/netlink.h:1158
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af910e)
Location: include/net/netlink.h:1158
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81afa6bf)
Location: include/net/netlink.h:1158
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81b009d4)
Location: include/net/netlink.h:1158
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b95cec)
Location: include/net/netlink.h:1158
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81b9b756)
Location: include/net/netlink.h:1158
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In lib/nlattr.c (ffffffff815fbb5d)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81a19d46)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/core/devlink.c (ffffffff81a57807)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_compat_running_version
  - net/core/devlink.c:__devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81a6987b)
Location: include/net/netlink.h:1171
Inline: True
```
```
In net/sched/ematch.c (ffffffff81a7edb3)
Location: include/net/netlink.h:1171
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a912db)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/strset.c (ffffffff81a9163c)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81aec9ce)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81af8a3c)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81afbc82)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05d73)
Location: include/net/netlink.h:1171
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81b07e6f)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81b0eab4)
Location: include/net/netlink.h:1171
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba595c)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81bab466)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In lib/nlattr.c (ffffffff815de7ad)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81a00d46)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/core/devlink.c (ffffffff81a4bfbe)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81a5201b)
Location: include/net/netlink.h:1171
Inline: True
```
```
In net/sched/ematch.c (ffffffff81a67c07)
Location: include/net/netlink.h:1171
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a7aade)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/strset.c (ffffffff81a7ae58)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81ad68fe)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae419c)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae73e3)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af15d2)
Location: include/net/netlink.h:1171
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81af367f)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81afc7a4)
Location: include/net/netlink.h:1171
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b94acc)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81b9a5f6)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In lib/nlattr.c (ffffffff8164a32d)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81ab3106)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/core/devlink.c (ffffffff81b0440b)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0acab)
Location: include/net/netlink.h:1171
Inline: True
```
```
In net/sched/ematch.c (ffffffff81b21177)
Location: include/net/netlink.h:1171
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81b34efc)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/strset.c (ffffffff81b353b8)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81b965a1)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba3aec)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba71f0)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1ae2)
Location: include/net/netlink.h:1171
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81bb3b8f)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81bbdef9)
Location: include/net/netlink.h:1171
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c61329)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81c67c66)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In lib/nlattr.c (ffffffff81760a7d)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81c2c284)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/core/devlink.c (ffffffff81c89d19)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81c91308)
Location: include/net/netlink.h:1171
Inline: True
```
```
In net/sched/ematch.c (ffffffff81ca90f4)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ethtool/bitset.c (ffffffff81cc06ed)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/strset.c (ffffffff81cc0c45)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81d26a47)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81d36373)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81d39b3c)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d451bd)
Location: include/net/netlink.h:1171
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81d473de)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81d529c6)
Location: include/net/netlink.h:1171
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e0392e)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81e0b2f1)
Location: include/net/netlink.h:1171
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In lib/nlattr.c (ffffffff8188f5ad)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81ddf344)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/core/devlink.c (ffffffff81e448f9)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4c858)
Location: include/net/netlink.h:1220
Inline: True
```
```
In net/sched/ematch.c (ffffffff81e66004)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ethtool/bitset.c (ffffffff81e7f341)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/strset.c (ffffffff81e7f929)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81eee3d7)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81efe9a4)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81f02453)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0e657)
Location: include/net/netlink.h:1220
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81f10830)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81f1cc63)
Location: include/net/netlink.h:1220
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd88be)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81fe1308)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In lib/nlattr.c (ffffffff818d19ed)
Location: include/net/netlink.h:1221
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81e50664)
Location: include/net/netlink.h:1221
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea7f40)
Location: include/net/netlink.h:1221
Inline: True
```
```
In net/sched/ematch.c (ffffffff81ec1f44)
Location: include/net/netlink.h:1221
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ethtool/bitset.c (ffffffff81edb931)
Location: include/net/netlink.h:1221
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/strset.c (ffffffff81edbfd6)
Location: include/net/netlink.h:1221
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81f4dd97)
Location: include/net/netlink.h:1221
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5e42b)
Location: include/net/netlink.h:1221
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81f61eb3)
Location: include/net/netlink.h:1221
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6e381)
Location: include/net/netlink.h:1221
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81f70520)
Location: include/net/netlink.h:1221
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81f7c71e)
Location: include/net/netlink.h:1221
Inline: True
```
```
In net/devlink/dev.c (ffffffff82042d13)
Location: include/net/netlink.h:1221
Inline: True
Inline callers:
  - net/devlink/dev.c:__devlink_compat_running_version
  - net/devlink/dev.c:__devlink_compat_running_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8205459c)
Location: include/net/netlink.h:1221
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff8205d325)
Location: include/net/netlink.h:1221
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_app_table_setdel
```
```
In net/handshake/tlshd.c (ffffffff82093d54)
Location: include/net/netlink.h:1221
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_done
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
In lib/nlattr.c (ffffffff819239dd)
Location: include/net/netlink.h:1265
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81eb8ace)
Location: include/net/netlink.h:1265
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_device_find_from_nlattr
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_set_doit
  - drivers/dpll/dpll_netlink.c:dpll_pin_find_from_nlattr
```
```
In net/core/rtnetlink.c (ffffffff81f0f704)
Location: include/net/netlink.h:1265
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6a9f3)
Location: include/net/netlink.h:1265
Inline: True
```
```
In net/sched/ematch.c (ffffffff81f85293)
Location: include/net/netlink.h:1265
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ethtool/bitset.c (ffffffff81f9f6f8)
Location: include/net/netlink.h:1265
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/strset.c (ffffffff81f9fd9f)
Location: include/net/netlink.h:1265
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff82013eca)
Location: include/net/netlink.h:1265
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff820249f1)
Location: include/net/netlink.h:1265
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff82028483)
Location: include/net/netlink.h:1265
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034a9e)
Location: include/net/netlink.h:1265
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff82036c50)
Location: include/net/netlink.h:1265
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff82042e11)
Location: include/net/netlink.h:1265
Inline: True
```
```
In net/devlink/dev.c (ffffffff8210209a)
Location: include/net/netlink.h:1265
Inline: True
Inline callers:
  - net/devlink/dev.c:__devlink_compat_running_version
  - net/devlink/dev.c:__devlink_compat_running_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82126de6)
Location: include/net/netlink.h:1265
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff8212ff3b)
Location: include/net/netlink.h:1265
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_app_table_setdel
```
```
In net/handshake/tlshd.c (ffffffff8216a6b2)
Location: include/net/netlink.h:1265
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_done
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
In lib/nlattr.c (ffff80001066131c)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffff800010beb2cc)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/core/devlink.c (ffff800010c30658)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (ffff800010c4a38c)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/devinet.c (ffff800010ca8070)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffff800010cb52a8)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffff800010cb7ca8)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffff800010cc3328)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010cce308)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d6a088)
Location: include/net/netlink.h:1106
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
In net/dcb/dcbnl.c (ffff800010d70fbc)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In lib/nlattr.c (c080a354)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (c0d03fd0)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/core/devlink.c (c0d47650)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (c0d5af64)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/devinet.c (c0db29fc)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (c0dc0c7c)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (c0dc2dd4)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (c0dceb44)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/ipmr.c (c0dd94ac)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e68600)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (c0e6e018)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In lib/nlattr.c (c00000000081507c)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (c000000000cce740)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/core/devlink.c (c000000000d29478)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (c000000000d47f20)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/devinet.c (c000000000db9f74)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (c000000000dccce0)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (c000000000dd046c)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (c000000000ddef04)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000deaec0)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea716c)
Location: include/net/netlink.h:1106
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
In net/dcb/dcbnl.c (c000000000eaf8b8)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In lib/nlattr.c (ffffffe00048de2c)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffe00076ec6e)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/core/devlink.c (ffffffe0007a681a)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (ffffffe0007b7700)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/devinet.c (ffffffe0008015de)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffe00080cd02)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffe00080ed84)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffe0008186b0)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe000820698)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089cd94)
Location: include/net/netlink.h:1106
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
In net/dcb/dcbnl.c (ffffffe0008a1c14)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In lib/nlattr.c (ffffffff8154d57d)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff818e9796)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/core/devlink.c (ffffffff81928576)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (ffffffff8193cccf)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81991c0e)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff8199cec7)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff8199f573)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff819a9d0b)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819b3434)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a398b3)
Location: include/net/netlink.h:1106
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
In net/dcb/dcbnl.c (ffffffff81a3edd6)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In lib/nlattr.c (ffffffff8153d85d)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/vxlan.c (ffffffff8176f008)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_nl2conf
```
```
In net/core/rtnetlink.c (ffffffff818a35d6)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/core/devlink.c (ffffffff818e2326)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (ffffffff818f67cf)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8194b6ce)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81956987)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81959033)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff819637cb)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196fa64)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f64d3)
Location: include/net/netlink.h:1106
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
In net/dcb/dcbnl.c (ffffffff819fb9c6)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In lib/nlattr.c (ffffffff815492bd)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff8193a7c6)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/core/devlink.c (ffffffff81979706)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (ffffffff8198de5f)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819fc4ae)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81a07767)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81a09e13)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff81a145ab)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1dcd4)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa5763)
Location: include/net/netlink.h:1106
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
In net/dcb/dcbnl.c (ffffffff81aaac86)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
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
In lib/nlattr.c (ffffffff8156310d)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff8195bff6)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setvfinfo
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/core/devlink.c (ffffffff8199bbf6)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (ffffffff819b06ff)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81a0681e)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81a11ea7)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81a145c3)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff81a1efbb)
Location: include/net/netlink.h:1106
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a28f18)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab1b03)
Location: include/net/netlink.h:1106
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
In net/dcb/dcbnl.c (ffffffff81ab6ff6)
Location: include/net/netlink.h:1106
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
```
</details>
</li>
</ul>

## Differences
