# Function: <code>nla_ok</code>

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
In lib/nlattr.c (ffffffff81415591)
Location: include/net/netlink.h:688
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:nla_validate
  - lib/nlattr.c:nla_parse
```
```
In net/core/rtnetlink.c (ffffffff81729b68)
Location: include/net/netlink.h:688
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
In net/sched/ematch.c (ffffffff81749a94)
Location: include/net/netlink.h:688
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ipv4/devinet.c (ffffffff8178f88f)
Location: include/net/netlink.h:688
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81799d9f)
Location: include/net/netlink.h:688
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8179cc90)
Location: include/net/netlink.h:688
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff817d4b02)
Location: include/net/netlink.h:688
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818103d6)
Location: include/net/netlink.h:688
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
In net/dcb/dcbnl.c (ffffffff81814ec9)
Location: include/net/netlink.h:688
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
In lib/nlattr.c (ffffffff8145d291)
Location: include/net/netlink.h:699
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:nla_parse
  - lib/nlattr.c:nla_validate
```
```
In net/core/rtnetlink.c (ffffffff81794769)
Location: include/net/netlink.h:699
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
In net/sched/ematch.c (ffffffff817b6a04)
Location: include/net/netlink.h:699
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ipv4/devinet.c (ffffffff817fcf7f)
Location: include/net/netlink.h:699
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81807a8b)
Location: include/net/netlink.h:699
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8180a820)
Location: include/net/netlink.h:699
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/ipmr.c (ffffffff81817823)
Location: include/net/netlink.h:699
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff81842a02)
Location: include/net/netlink.h:699
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81882c18)
Location: include/net/netlink.h:699
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
In net/dcb/dcbnl.c (ffffffff81887d99)
Location: include/net/netlink.h:699
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
```
```
In net/switchdev/switchdev.c (ffffffff8188b7f1)
Location: include/net/netlink.h:699
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
In lib/nlattr.c (ffffffff8147bd81)
Location: include/net/netlink.h:699
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:nla_parse
  - lib/nlattr.c:nla_validate
```
```
In net/core/rtnetlink.c (ffffffff817c1fe9)
Location: include/net/netlink.h:699
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
In net/sched/ematch.c (ffffffff817e6494)
Location: include/net/netlink.h:699
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ipv4/devinet.c (ffffffff8182dedf)
Location: include/net/netlink.h:699
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81838b2b)
Location: include/net/netlink.h:699
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8183b930)
Location: include/net/netlink.h:699
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/ipmr.c (ffffffff81849093)
Location: include/net/netlink.h:699
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff81874772)
Location: include/net/netlink.h:699
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b74c8)
Location: include/net/netlink.h:699
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
In net/dcb/dcbnl.c (ffffffff818bc5b9)
Location: include/net/netlink.h:699
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
```
```
In net/switchdev/switchdev.c (ffffffff818bfacf)
Location: include/net/netlink.h:699
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
In lib/nlattr.c (ffffffff814850d1)
Location: include/net/netlink.h:708
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:nla_parse
  - lib/nlattr.c:nla_validate
```
```
In net/core/rtnetlink.c (ffffffff817e076a)
Location: include/net/netlink.h:708
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
In net/sched/ematch.c (ffffffff81805fe4)
Location: include/net/netlink.h:708
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8184fb66)
Location: include/net/netlink.h:708
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81859de7)
Location: include/net/netlink.h:708
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff8185d25a)
Location: include/net/netlink.h:708
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/ipmr.c (ffffffff8186c76a)
Location: include/net/netlink.h:708
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff8189956a)
Location: include/net/netlink.h:708
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818ddedf)
Location: include/net/netlink.h:708
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
In net/dcb/dcbnl.c (ffffffff818e2faf)
Location: include/net/netlink.h:708
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
```
```
In net/switchdev/switchdev.c (ffffffff818e62fd)
Location: include/net/netlink.h:708
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
In lib/nlattr.c (ffffffff814c1141)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:nla_parse
  - lib/nlattr.c:nla_validate
```
```
In net/core/rtnetlink.c (ffffffff8185afee)
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
In net/sched/ematch.c (ffffffff81884d14)
Location: include/net/netlink.h:714
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff818cf796)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff818d9ce7)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff818dd27b)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ipmr.c (ffffffff818ed04a)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff8191a8b0)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_convert_metrics
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81963acf)
Location: include/net/netlink.h:714
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
In net/dcb/dcbnl.c (ffffffff81968d9f)
Location: include/net/netlink.h:714
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
In lib/nlattr.c (ffffffff814f2680)
Location: include/net/netlink.h:714
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff818a68a6)
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
In net/sched/ematch.c (ffffffff818d8866)
Location: include/net/netlink.h:714
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81925492)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81930774)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff8193383e)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff8193c94f)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81942fd4)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bd1d3)
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
In net/dcb/dcbnl.c (ffffffff819c2576)
Location: include/net/netlink.h:714
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
In lib/nlattr.c (ffffffff81506662)
Location: include/net/netlink.h:857
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff818ca106)
Location: include/net/netlink.h:857
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
In net/sched/ematch.c (ffffffff81905056)
Location: include/net/netlink.h:857
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819542a2)
Location: include/net/netlink.h:857
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff8195fb84)
Location: include/net/netlink.h:857
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81962d2e)
Location: include/net/netlink.h:857
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff8196c677)
Location: include/net/netlink.h:857
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819730a4)
Location: include/net/netlink.h:857
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f4521)
Location: include/net/netlink.h:857
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
In net/dcb/dcbnl.c (ffffffff819f9ad6)
Location: include/net/netlink.h:857
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
In lib/nlattr.c (ffffffff81534140)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff819170d9)
Location: include/net/netlink.h:1091
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
In net/core/devlink.c (ffffffff81951be1)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (ffffffff819662b7)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819b9b21)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff819c650e)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff819c8b9e)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff819d3397)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819dcbb5)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a638ab)
Location: include/net/netlink.h:1091
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
In net/dcb/dcbnl.c (ffffffff81a6902e)
Location: include/net/netlink.h:1091
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
In lib/nlattr.c (ffffffff81554f80)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81949719)
Location: include/net/netlink.h:1091
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
In net/core/devlink.c (ffffffff81988621)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (ffffffff8199cd47)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819f1e21)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff819fd0be)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff819ff75e)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff81a09f07)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a13bad)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a9a45b)
Location: include/net/netlink.h:1091
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
In net/dcb/dcbnl.c (ffffffff81a9f98e)
Location: include/net/netlink.h:1091
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
In lib/nlattr.c (ffffffff815de4c0)
Location: include/net/netlink.h:1143
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81a19aa9)
Location: include/net/netlink.h:1143
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
In net/core/devlink.c (ffffffff81a516a0)
Location: include/net/netlink.h:1143
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_compat_running_version
  - net/core/devlink.c:__devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81a60f52)
Location: include/net/netlink.h:1143
Inline: True
```
```
In net/sched/ematch.c (ffffffff81a75f92)
Location: include/net/netlink.h:1143
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a878e2)
Location: include/net/netlink.h:1143
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/strset.c (ffffffff81a87c34)
Location: include/net/netlink.h:1143
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81adfb01)
Location: include/net/netlink.h:1143
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81aebac3)
Location: include/net/netlink.h:1143
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81aeecae)
Location: include/net/netlink.h:1143
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af9032)
Location: include/net/netlink.h:1143
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81afa645)
Location: include/net/netlink.h:1143
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81b00962)
Location: include/net/netlink.h:1143
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b95cc6)
Location: include/net/netlink.h:1143
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
In net/dcb/dcbnl.c (ffffffff81b9b69e)
Location: include/net/netlink.h:1143
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
In lib/nlattr.c (ffffffff815fbb40)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81a19c99)
Location: include/net/netlink.h:1156
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
In net/core/devlink.c (ffffffff81a577b0)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_compat_running_version
  - net/core/devlink.c:__devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81a69822)
Location: include/net/netlink.h:1156
Inline: True
```
```
In net/sched/ematch.c (ffffffff81a7ed42)
Location: include/net/netlink.h:1156
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a91262)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/strset.c (ffffffff81a915a4)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81aec981)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81af89d0)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81afbc0e)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05c92)
Location: include/net/netlink.h:1156
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81b07df5)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81b0ea42)
Location: include/net/netlink.h:1156
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba5936)
Location: include/net/netlink.h:1156
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
In net/dcb/dcbnl.c (ffffffff81bab3ae)
Location: include/net/netlink.h:1156
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
In lib/nlattr.c (ffffffff815de790)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81a00c99)
Location: include/net/netlink.h:1156
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
In net/core/devlink.c (ffffffff81a4bedc)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81a51fc2)
Location: include/net/netlink.h:1156
Inline: True
```
```
In net/sched/ematch.c (ffffffff81a67b92)
Location: include/net/netlink.h:1156
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a7aa6e)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/strset.c (ffffffff81a7adc4)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81ad68b1)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae4130)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae736e)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af1502)
Location: include/net/netlink.h:1156
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81af3605)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81afc732)
Location: include/net/netlink.h:1156
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b94aa6)
Location: include/net/netlink.h:1156
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
In net/dcb/dcbnl.c (ffffffff81b9a53e)
Location: include/net/netlink.h:1156
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
In lib/nlattr.c (ffffffff8164a310)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81ab3059)
Location: include/net/netlink.h:1156
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
In net/core/devlink.c (ffffffff81b042d3)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0ac52)
Location: include/net/netlink.h:1156
Inline: True
```
```
In net/sched/ematch.c (ffffffff81b21102)
Location: include/net/netlink.h:1156
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81b34e7e)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/strset.c (ffffffff81b35324)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81b9653d)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba3a80)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba7162)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1a12)
Location: include/net/netlink.h:1156
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81bb3b15)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81bbde22)
Location: include/net/netlink.h:1156
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c612c6)
Location: include/net/netlink.h:1156
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
In net/dcb/dcbnl.c (ffffffff81c67bae)
Location: include/net/netlink.h:1156
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
In lib/nlattr.c (ffffffff81760a60)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81c2c1d2)
Location: include/net/netlink.h:1156
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
In net/core/devlink.c (ffffffff81c89c2f)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81c912b0)
Location: include/net/netlink.h:1156
Inline: True
```
```
In net/sched/ematch.c (ffffffff81ca907f)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ethtool/bitset.c (ffffffff81cc0669)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/strset.c (ffffffff81cc0b84)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81d269cd)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81d36304)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81d39aa5)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d450c2)
Location: include/net/netlink.h:1156
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81d47355)
Location: include/net/netlink.h:1156
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81d528ed)
Location: include/net/netlink.h:1156
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e03858)
Location: include/net/netlink.h:1156
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
In net/dcb/dcbnl.c (ffffffff81e0b22d)
Location: include/net/netlink.h:1156
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
In lib/nlattr.c (ffffffff8188f590)
Location: include/net/netlink.h:1205
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81ddf292)
Location: include/net/netlink.h:1205
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
In net/core/devlink.c (ffffffff81e4480f)
Location: include/net/netlink.h:1205
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4c800)
Location: include/net/netlink.h:1205
Inline: True
```
```
In net/sched/ematch.c (ffffffff81e65f8f)
Location: include/net/netlink.h:1205
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ethtool/bitset.c (ffffffff81e7f2b9)
Location: include/net/netlink.h:1205
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/strset.c (ffffffff81e7f864)
Location: include/net/netlink.h:1205
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81eee35d)
Location: include/net/netlink.h:1205
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81efe935)
Location: include/net/netlink.h:1205
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81f023b5)
Location: include/net/netlink.h:1205
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0e562)
Location: include/net/netlink.h:1205
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81f107a9)
Location: include/net/netlink.h:1205
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81f1cbe9)
Location: include/net/netlink.h:1205
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd87e8)
Location: include/net/netlink.h:1205
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
In net/dcb/dcbnl.c (ffffffff81fe126d)
Location: include/net/netlink.h:1205
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
In lib/nlattr.c (ffffffff818d19d0)
Location: include/net/netlink.h:1206
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81e505b2)
Location: include/net/netlink.h:1206
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
In net/core/bpf_sk_storage.c (ffffffff81ea7f10)
Location: include/net/netlink.h:1206
Inline: True
```
```
In net/sched/ematch.c (ffffffff81ec1ecf)
Location: include/net/netlink.h:1206
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ethtool/bitset.c (ffffffff81edb8a9)
Location: include/net/netlink.h:1206
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/strset.c (ffffffff81edbf14)
Location: include/net/netlink.h:1206
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81f4dd1d)
Location: include/net/netlink.h:1206
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5e3c5)
Location: include/net/netlink.h:1206
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81f61e15)
Location: include/net/netlink.h:1206
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6e212)
Location: include/net/netlink.h:1206
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81f70499)
Location: include/net/netlink.h:1206
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81f7c6c9)
Location: include/net/netlink.h:1206
Inline: True
```
```
In net/devlink/dev.c (ffffffff82042c62)
Location: include/net/netlink.h:1206
Inline: True
Inline callers:
  - net/devlink/dev.c:__devlink_compat_running_version
  - net/devlink/dev.c:__devlink_compat_running_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff820544c8)
Location: include/net/netlink.h:1206
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
In net/dcb/dcbnl.c (ffffffff8205d1f0)
Location: include/net/netlink.h:1206
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_app_table_setdel
```
```
In net/handshake/tlshd.c (ffffffff82093cfc)
Location: include/net/netlink.h:1206
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
In lib/nlattr.c (ffffffff819239c0)
Location: include/net/netlink.h:1250
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81eb8a51)
Location: include/net/netlink.h:1250
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_device_find_from_nlattr
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_set_doit
  - drivers/dpll/dpll_netlink.c:dpll_pin_find_from_nlattr
```
```
In net/core/rtnetlink.c (ffffffff81f0f655)
Location: include/net/netlink.h:1250
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
In net/core/filter.c (ffffffff81f220a3)
Location: include/net/netlink.h:1250
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_nlattr_nest
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6a9c3)
Location: include/net/netlink.h:1250
Inline: True
```
```
In net/sched/ematch.c (ffffffff81f85216)
Location: include/net/netlink.h:1250
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ethtool/bitset.c (ffffffff81f9f670)
Location: include/net/netlink.h:1250
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/strset.c (ffffffff81f9fcda)
Location: include/net/netlink.h:1250
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff82013e51)
Location: include/net/netlink.h:1250
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff82024985)
Location: include/net/netlink.h:1250
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff820283e5)
Location: include/net/netlink.h:1250
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034928)
Location: include/net/netlink.h:1250
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff82036bc9)
Location: include/net/netlink.h:1250
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff82042db9)
Location: include/net/netlink.h:1250
Inline: True
```
```
In net/devlink/dev.c (ffffffff82101fe5)
Location: include/net/netlink.h:1250
Inline: True
Inline callers:
  - net/devlink/dev.c:__devlink_compat_running_version
  - net/devlink/dev.c:__devlink_compat_running_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82126d0c)
Location: include/net/netlink.h:1250
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
In net/dcb/dcbnl.c (ffffffff8212fe06)
Location: include/net/netlink.h:1250
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_app_table_setdel
```
```
In net/handshake/tlshd.c (ffffffff8216a61e)
Location: include/net/netlink.h:1250
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
In lib/nlattr.c (ffff800010661308)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffff800010beb248)
Location: include/net/netlink.h:1091
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
In net/core/devlink.c (ffff800010c30538)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (ffff800010c4a270)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/devinet.c (ffff800010ca7fe8)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffff800010cb5238)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffff800010cb7c2c)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffff800010cc3280)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010cce228)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d69f98)
Location: include/net/netlink.h:1091
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
In net/dcb/dcbnl.c (ffff800010d70f74)
Location: include/net/netlink.h:1091
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
In lib/nlattr.c (c080a340)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (c0d03f3c)
Location: include/net/netlink.h:1091
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
In net/core/devlink.c (c0d4752c)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (c0d5ae58)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/devinet.c (c0db2994)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (c0dc0ba8)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (c0dc2d5c)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (c0dceaac)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/ipmr.c (c0dd92f4)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e684fc)
Location: include/net/netlink.h:1091
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
In net/dcb/dcbnl.c (c0e6df60)
Location: include/net/netlink.h:1091
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
In lib/nlattr.c (c000000000815060)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (c000000000cce678)
Location: include/net/netlink.h:1091
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
In net/core/devlink.c (c000000000d29304)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (c000000000d47dd0)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/devinet.c (c000000000db9ec4)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (c000000000dccbf8)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (c000000000dd03e8)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (c000000000ddee20)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000deadc0)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea7054)
Location: include/net/netlink.h:1091
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
In net/dcb/dcbnl.c (c000000000eaf7bc)
Location: include/net/netlink.h:1091
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
In lib/nlattr.c (ffffffe00048de08)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffe00076ebe8)
Location: include/net/netlink.h:1091
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
In net/core/devlink.c (ffffffe0007a671c)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (ffffffe0007b7666)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/devinet.c (ffffffe00080157e)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffe00080cca6)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffe00080ed24)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffe000818642)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe000820572)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089cd5a)
Location: include/net/netlink.h:1091
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
In net/dcb/dcbnl.c (ffffffe0008a1b84)
Location: include/net/netlink.h:1091
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
In lib/nlattr.c (ffffffff8154d560)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff818e96e9)
Location: include/net/netlink.h:1091
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
In net/core/devlink.c (ffffffff81928491)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (ffffffff8193cbb7)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81991bc1)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff8199ce5e)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff8199f4fe)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff819a9ca7)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819b33a5)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a397eb)
Location: include/net/netlink.h:1091
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
In net/dcb/dcbnl.c (ffffffff81a3ed1e)
Location: include/net/netlink.h:1091
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
In lib/nlattr.c (ffffffff8153d840)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/vxlan.c (ffffffff8176ea25)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_nl2conf
```
```
In net/core/rtnetlink.c (ffffffff818a3529)
Location: include/net/netlink.h:1091
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
In net/core/devlink.c (ffffffff818e2241)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (ffffffff818f66b7)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8194b681)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff8195691e)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81958fbe)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff81963767)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196f9d5)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f640b)
Location: include/net/netlink.h:1091
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
In net/dcb/dcbnl.c (ffffffff819fb90e)
Location: include/net/netlink.h:1091
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
In lib/nlattr.c (ffffffff815492a0)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff8193a719)
Location: include/net/netlink.h:1091
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
In net/core/devlink.c (ffffffff81979621)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (ffffffff8198dd47)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819fc461)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81a076fe)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81a09d9e)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff81a14547)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1dc45)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa569b)
Location: include/net/netlink.h:1091
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
In net/dcb/dcbnl.c (ffffffff81aaabce)
Location: include/net/netlink.h:1091
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
In lib/nlattr.c (ffffffff815630f0)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff8195bf49)
Location: include/net/netlink.h:1091
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
In net/core/devlink.c (ffffffff8199bb11)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/ematch.c (ffffffff819b05e7)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81a067d1)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81a11e3e)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81a1454e)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff81a1ef57)
Location: include/net/netlink.h:1091
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a28e9d)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab1a3b)
Location: include/net/netlink.h:1091
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
In net/dcb/dcbnl.c (ffffffff81ab6f3e)
Location: include/net/netlink.h:1091
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
```
</details>
</li>
</ul>

## Differences
