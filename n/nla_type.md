# Function: <code>nla_type</code>

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
In lib/nlattr.c (ffffffff814155e0)
Location: include/net/netlink.h:660
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81729b92)
Location: include/net/netlink.h:660
Inline: True
Inline callers:
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:do_setlink
```
```
In net/ipv4/devinet.c (ffffffff8178f99b)
Location: include/net/netlink.h:660
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:660
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8179ce9c)
Location: include/net/netlink.h:660
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff817d4b53)
Location: include/net/netlink.h:660
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:660
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:660
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
In lib/nlattr.c (ffffffff8145d2a8)
Location: include/net/netlink.h:671
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff8179482f)
Location: include/net/netlink.h:671
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
In net/ipv4/devinet.c (ffffffff817fcf9d)
Location: include/net/netlink.h:671
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81807a9f)
Location: include/net/netlink.h:671
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8180a848)
Location: include/net/netlink.h:671
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/ipmr.c (ffffffff81817848)
Location: include/net/netlink.h:671
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff81842a53)
Location: include/net/netlink.h:671
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81882c32)
Location: include/net/netlink.h:671
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
In net/dcb/dcbnl.c (ffffffff81887db3)
Location: include/net/netlink.h:671
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
```
```
In net/switchdev/switchdev.c (ffffffff8188b80f)
Location: include/net/netlink.h:671
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
In lib/nlattr.c (ffffffff8147bd98)
Location: include/net/netlink.h:671
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff817c20af)
Location: include/net/netlink.h:671
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
In net/ipv4/devinet.c (ffffffff8182defd)
Location: include/net/netlink.h:671
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81838b41)
Location: include/net/netlink.h:671
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8183b958)
Location: include/net/netlink.h:671
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/ipmr.c (ffffffff818490b8)
Location: include/net/netlink.h:671
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff818747c3)
Location: include/net/netlink.h:671
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b74e2)
Location: include/net/netlink.h:671
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
In net/dcb/dcbnl.c (ffffffff818bc5d3)
Location: include/net/netlink.h:671
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
```
```
In net/switchdev/switchdev.c (ffffffff818bfaed)
Location: include/net/netlink.h:671
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
In lib/nlattr.c (ffffffff814850df)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:nla_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff817e18d1)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/ipv4/devinet.c (ffffffff8184fb8f)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81859dfd)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff8185d2ef)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/ipmr.c (ffffffff8186c790)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff818995d1)
Location: include/net/netlink.h:680
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818ddf34)
Location: include/net/netlink.h:680
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
In net/dcb/dcbnl.c (ffffffff818e2fc1)
Location: include/net/netlink.h:680
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
```
```
In net/switchdev/switchdev.c (ffffffff818e6313)
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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814c114f)
Location: include/net/netlink.h:686
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:nla_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff8185c87f)
Location: include/net/netlink.h:686
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
```
```
In net/ipv4/devinet.c (ffffffff818cf7bf)
Location: include/net/netlink.h:686
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff818d9cfd)
Location: include/net/netlink.h:686
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff818dd31c)
Location: include/net/netlink.h:686
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ipmr.c (ffffffff818ed070)
Location: include/net/netlink.h:686
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff8191a91d)
Location: include/net/netlink.h:686
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_convert_metrics
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81963b24)
Location: include/net/netlink.h:686
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
In net/dcb/dcbnl.c (ffffffff81968db1)
Location: include/net/netlink.h:686
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
In lib/nlattr.c (ffffffff814f2050)
Location: include/net/netlink.h:686
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff818a6961)
Location: include/net/netlink.h:686
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
In net/ipv4/devinet.c (ffffffff819254cf)
Location: include/net/netlink.h:686
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff8193079a)
Location: include/net/netlink.h:686
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff8193387b)
Location: include/net/netlink.h:686
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff8193c98d)
Location: include/net/netlink.h:686
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff8194303b)
Location: include/net/netlink.h:686
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bd2a2)
Location: include/net/netlink.h:686
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
In net/dcb/dcbnl.c (ffffffff819c25f4)
Location: include/net/netlink.h:686
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
In lib/nlattr.c (ffffffff81506430)
Location: include/net/netlink.h:829
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff818ca1c1)
Location: include/net/netlink.h:829
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
In net/ipv4/devinet.c (ffffffff819542df)
Location: include/net/netlink.h:829
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff8195fbad)
Location: include/net/netlink.h:829
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81962d6b)
Location: include/net/netlink.h:829
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff8196c698)
Location: include/net/netlink.h:829
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8197310f)
Location: include/net/netlink.h:829
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f4541)
Location: include/net/netlink.h:829
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
In net/dcb/dcbnl.c (ffffffff819f9b54)
Location: include/net/netlink.h:829
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
In lib/nlattr.c (ffffffff81534152)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81917179)
Location: include/net/netlink.h:1063
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
In net/core/devlink.c (ffffffff81951bfc)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/ipv4/devinet.c (ffffffff819b9b55)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff819c652d)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff819c8bca)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff819d33b0)
Location: include/net/netlink.h:1063
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819dcc10)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a63962)
Location: include/net/netlink.h:1063
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
In net/dcb/dcbnl.c (ffffffff81a690a9)
Location: include/net/netlink.h:1063
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
In lib/nlattr.c (ffffffff81554f92)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff819497b9)
Location: include/net/netlink.h:1063
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
In net/core/devlink.c (ffffffff8198863c)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/ipv4/devinet.c (ffffffff819f1e55)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff819fd0dd)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff819ff78a)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff81a09f20)
Location: include/net/netlink.h:1063
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a13bcd)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a9a512)
Location: include/net/netlink.h:1063
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
In net/dcb/dcbnl.c (ffffffff81a9fa09)
Location: include/net/netlink.h:1063
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
In lib/nlattr.c (ffffffff815de4d2)
Location: include/net/netlink.h:1115
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81a19b49)
Location: include/net/netlink.h:1115
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
In net/core/devlink.c (ffffffff81a5167c)
Location: include/net/netlink.h:1115
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_compat_running_version
  - net/core/devlink.c:__devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81a60f9e)
Location: include/net/netlink.h:1115
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a86ec7)
Location: include/net/netlink.h:1115
Inline: True
```
```
In net/ethtool/strset.c (ffffffff81a87c65)
Location: include/net/netlink.h:1115
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81adfb35)
Location: include/net/netlink.h:1115
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81aebae2)
Location: include/net/netlink.h:1115
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81aeecda)
Location: include/net/netlink.h:1115
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af9048)
Location: include/net/netlink.h:1115
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81afa670)
Location: include/net/netlink.h:1115
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81b0097b)
Location: include/net/netlink.h:1115
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b95cdb)
Location: include/net/netlink.h:1115
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
In net/dcb/dcbnl.c (ffffffff81b9b719)
Location: include/net/netlink.h:1115
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
In lib/nlattr.c (ffffffff815fbb52)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81a19d39)
Location: include/net/netlink.h:1128
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
In net/core/devlink.c (ffffffff81a5778c)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_compat_running_version
  - net/core/devlink.c:__devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81a6986e)
Location: include/net/netlink.h:1128
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a90838)
Location: include/net/netlink.h:1128
Inline: True
```
```
In net/ethtool/strset.c (ffffffff81a915d5)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81aec9b5)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81af89ef)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81afbc3a)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05ca8)
Location: include/net/netlink.h:1128
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81b07e20)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81b0ea5b)
Location: include/net/netlink.h:1128
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba594b)
Location: include/net/netlink.h:1128
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
In net/dcb/dcbnl.c (ffffffff81bab429)
Location: include/net/netlink.h:1128
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
In lib/nlattr.c (ffffffff815de7a2)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81a00d39)
Location: include/net/netlink.h:1128
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
In net/core/devlink.c (ffffffff81a4bef7)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81a5200e)
Location: include/net/netlink.h:1128
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a79fe7)
Location: include/net/netlink.h:1128
Inline: True
```
```
In net/ethtool/strset.c (ffffffff81a7adf5)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81ad68e5)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae414f)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae739a)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af1517)
Location: include/net/netlink.h:1128
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81af3630)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81afc74b)
Location: include/net/netlink.h:1128
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b94abb)
Location: include/net/netlink.h:1128
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
In net/dcb/dcbnl.c (ffffffff81b9a5b9)
Location: include/net/netlink.h:1128
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
In lib/nlattr.c (ffffffff8164a322)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81ab30f9)
Location: include/net/netlink.h:1128
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
In net/core/devlink.c (ffffffff81b04381)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0ac9e)
Location: include/net/netlink.h:1128
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81b343f7)
Location: include/net/netlink.h:1128
Inline: True
```
```
In net/ethtool/strset.c (ffffffff81b35417)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81b9657c)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba3a9f)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba7196)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1a27)
Location: include/net/netlink.h:1128
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81bb3b40)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81bbded0)
Location: include/net/netlink.h:1128
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c61318)
Location: include/net/netlink.h:1128
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
In net/dcb/dcbnl.c (ffffffff81c67c29)
Location: include/net/netlink.h:1128
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
In lib/nlattr.c (ffffffff81760a72)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81c2c27b)
Location: include/net/netlink.h:1128
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
In net/core/devlink.c (ffffffff81c89c49)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81c912fb)
Location: include/net/netlink.h:1128
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81cbfb90)
Location: include/net/netlink.h:1128
Inline: True
```
```
In net/ethtool/strset.c (ffffffff81cc0ca8)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81d26a22)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81d36322)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81d39ae2)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d450d7)
Location: include/net/netlink.h:1128
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81d4738f)
Location: include/net/netlink.h:1128
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81d5299d)
Location: include/net/netlink.h:1128
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e0391d)
Location: include/net/netlink.h:1128
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
In net/dcb/dcbnl.c (ffffffff81e0b2b9)
Location: include/net/netlink.h:1128
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
In lib/nlattr.c (ffffffff8188f5a2)
Location: include/net/netlink.h:1177
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81ddf33b)
Location: include/net/netlink.h:1177
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
In net/core/devlink.c (ffffffff81e44829)
Location: include/net/netlink.h:1177
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4c84b)
Location: include/net/netlink.h:1177
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81e7e770)
Location: include/net/netlink.h:1177
Inline: True
```
```
In net/ethtool/strset.c (ffffffff81e7f98c)
Location: include/net/netlink.h:1177
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81eee3b2)
Location: include/net/netlink.h:1177
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81efe953)
Location: include/net/netlink.h:1177
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81f023f2)
Location: include/net/netlink.h:1177
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0e577)
Location: include/net/netlink.h:1177
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81f107cf)
Location: include/net/netlink.h:1177
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81f1cc08)
Location: include/net/netlink.h:1177
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd88ad)
Location: include/net/netlink.h:1177
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
In net/dcb/dcbnl.c (ffffffff81fe12f9)
Location: include/net/netlink.h:1177
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
In lib/nlattr.c (ffffffff818d19e2)
Location: include/net/netlink.h:1178
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff81e5065b)
Location: include/net/netlink.h:1178
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
In net/core/bpf_sk_storage.c (ffffffff81ea7f2a)
Location: include/net/netlink.h:1178
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81edad30)
Location: include/net/netlink.h:1178
Inline: True
```
```
In net/ethtool/strset.c (ffffffff81edc08b)
Location: include/net/netlink.h:1178
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff81f4dd72)
Location: include/net/netlink.h:1178
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5e3e3)
Location: include/net/netlink.h:1178
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81f61e52)
Location: include/net/netlink.h:1178
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6e227)
Location: include/net/netlink.h:1178
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff81f704bf)
Location: include/net/netlink.h:1178
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81f7c6e4)
Location: include/net/netlink.h:1178
Inline: True
```
```
In net/devlink/dev.c (ffffffff82042c32)
Location: include/net/netlink.h:1178
Inline: True
Inline callers:
  - net/devlink/dev.c:__devlink_compat_running_version
  - net/devlink/dev.c:__devlink_compat_running_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8205458b)
Location: include/net/netlink.h:1178
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
In net/dcb/dcbnl.c (ffffffff8205d21d)
Location: include/net/netlink.h:1178
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_app_table_setdel
```
```
In net/handshake/tlshd.c (ffffffff82093d3f)
Location: include/net/netlink.h:1178
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
In lib/nlattr.c (ffffffff819239d2)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81eb8aa4)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_device_find_from_nlattr
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_set_doit
  - drivers/dpll/dpll_netlink.c:dpll_pin_find_from_nlattr
```
```
In net/core/rtnetlink.c (ffffffff81f0f6fb)
Location: include/net/netlink.h:1222
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
In net/core/bpf_sk_storage.c (ffffffff81f6a9dd)
Location: include/net/netlink.h:1222
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81f9eaf3)
Location: include/net/netlink.h:1222
Inline: True
```
```
In net/ethtool/strset.c (ffffffff81f9fe54)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ipv4/devinet.c (ffffffff82013ea4)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff820249a6)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff82028422)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034940)
Location: include/net/netlink.h:1222
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff82036bef)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff82042dd7)
Location: include/net/netlink.h:1222
Inline: True
```
```
In net/devlink/dev.c (ffffffff82101fb5)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/devlink/dev.c:__devlink_compat_running_version
  - net/devlink/dev.c:__devlink_compat_running_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82126dd5)
Location: include/net/netlink.h:1222
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
In net/dcb/dcbnl.c (ffffffff8212fe33)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_app_table_setdel
```
```
In net/handshake/tlshd.c (ffffffff8216a69d)
Location: include/net/netlink.h:1222
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
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffff800010beb2cc)
Location: include/net/netlink.h:1063
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
In net/core/devlink.c (ffff800010c30568)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/ipv4/devinet.c (ffff800010ca8038)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffff800010cb5260)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffff800010cb7c5c)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffff800010cc32e4)
Location: include/net/netlink.h:1063
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010cce2cc)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d6a070)
Location: include/net/netlink.h:1063
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
In net/dcb/dcbnl.c (ffff800010d70f90)
Location: include/net/netlink.h:1063
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
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (c0d03fd0)
Location: include/net/netlink.h:1063
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
In net/core/devlink.c (c0d47558)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/ipv4/devinet.c (c0db29dc)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (c0dc0bd0)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (c0dc2d8c)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (c0dceaf0)
Location: include/net/netlink.h:1063
Inline: True
```
```
In net/ipv4/ipmr.c (c0dd93c8)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e685e8)
Location: include/net/netlink.h:1063
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
In net/dcb/dcbnl.c (c0e6dfe4)
Location: include/net/netlink.h:1063
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
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (c000000000cce740)
Location: include/net/netlink.h:1063
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
In net/core/devlink.c (c000000000d29338)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/ipv4/devinet.c (c000000000db9f20)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (c000000000dccc20)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (c000000000dd0418)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (c000000000ddee9c)
Location: include/net/netlink.h:1063
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000deaef8)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea7158)
Location: include/net/netlink.h:1063
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
In net/dcb/dcbnl.c (c000000000eaf87c)
Location: include/net/netlink.h:1063
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
In lib/nlattr.c (ffffffe00048de14)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffe00076ec5e)
Location: include/net/netlink.h:1063
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
In net/core/devlink.c (ffffffe0007a6726)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/ipv4/devinet.c (ffffffe000801586)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffe00080ccae)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffe00080ed2a)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffe000818652)
Location: include/net/netlink.h:1063
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe000820598)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089cd6c)
Location: include/net/netlink.h:1063
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
In net/dcb/dcbnl.c (ffffffe0008a1b90)
Location: include/net/netlink.h:1063
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
In lib/nlattr.c (ffffffff8154d572)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff818e9789)
Location: include/net/netlink.h:1063
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
In net/core/devlink.c (ffffffff819284ac)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/ipv4/devinet.c (ffffffff81991bf5)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff8199ce7d)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff8199f52a)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff819a9cc0)
Location: include/net/netlink.h:1063
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819b3400)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a398a2)
Location: include/net/netlink.h:1063
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
In net/dcb/dcbnl.c (ffffffff81a3ed99)
Location: include/net/netlink.h:1063
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
In lib/nlattr.c (ffffffff8153d852)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff818a35c9)
Location: include/net/netlink.h:1063
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
In net/core/devlink.c (ffffffff818e225c)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/ipv4/devinet.c (ffffffff8194b6b5)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff8195693d)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81958fea)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff81963780)
Location: include/net/netlink.h:1063
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196fa30)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f64c2)
Location: include/net/netlink.h:1063
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
In net/dcb/dcbnl.c (ffffffff819fb989)
Location: include/net/netlink.h:1063
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
In lib/nlattr.c (ffffffff815492b2)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff8193a7b9)
Location: include/net/netlink.h:1063
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
In net/core/devlink.c (ffffffff8197963c)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/ipv4/devinet.c (ffffffff819fc495)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81a0771d)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81a09dca)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff81a14560)
Location: include/net/netlink.h:1063
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1dca0)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa5752)
Location: include/net/netlink.h:1063
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
In net/dcb/dcbnl.c (ffffffff81aaac49)
Location: include/net/netlink.h:1063
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
In lib/nlattr.c (ffffffff81563102)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - lib/nlattr.c:nla_find
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff8195bfe9)
Location: include/net/netlink.h:1063
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
In net/core/devlink.c (ffffffff8199bb2c)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/ipv4/devinet.c (ffffffff81a06805)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/fib_frontend.c (ffffffff81a11e5d)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81a1457a)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff81a1ef70)
Location: include/net/netlink.h:1063
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a28ebd)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab1af2)
Location: include/net/netlink.h:1063
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
In net/dcb/dcbnl.c (ffffffff81ab6fb9)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
```
</details>
</li>
</ul>

## Differences
