# Function: <code>nla_get_u8</code>

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
In net/core/rtnetlink.c (ffffffff8172a49f)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a459d)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff817d22b4)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
```
```
In net/ipv6/route.c (ffffffff817d4159)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180e65c)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81810443)
Location: include/net/netlink.h:1046
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff818140e1)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
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
In net/core/rtnetlink.c (ffffffff81793ed6)
Location: include/net/netlink.h:1070
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff817a66f8)
Location: include/net/netlink.h:1070
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8181238f)
Location: include/net/netlink.h:1070
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff8183fc74)
Location: include/net/netlink.h:1070
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
```
```
In net/ipv6/route.c (ffffffff81842d64)
Location: include/net/netlink.h:1070
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81880cec)
Location: include/net/netlink.h:1070
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81882b13)
Location: include/net/netlink.h:1070
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff8188812a)
Location: include/net/netlink.h:1070
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/switchdev/switchdev.c (ffffffff8188b711)
Location: include/net/netlink.h:1070
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_br_setflag
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
In net/core/rtnetlink.c (ffffffff817c1756)
Location: include/net/netlink.h:1070
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff817d5136)
Location: include/net/netlink.h:1070
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8184389f)
Location: include/net/netlink.h:1070
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff818718a4)
Location: include/net/netlink.h:1070
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
```
```
In net/ipv6/route.c (ffffffff81874ad4)
Location: include/net/netlink.h:1070
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81899a0c)
Location: include/net/netlink.h:1070
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b559c)
Location: include/net/netlink.h:1070
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b73c0)
Location: include/net/netlink.h:1070
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff818bc94a)
Location: include/net/netlink.h:1070
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/switchdev/switchdev.c (ffffffff818bf9e1)
Location: include/net/netlink.h:1070
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_br_setflag
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
In net/core/rtnetlink.c (ffffffff817dff27)
Location: include/net/netlink.h:1082
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff817f4606)
Location: include/net/netlink.h:1082
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818650f5)
Location: include/net/netlink.h:1082
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff81896617)
Location: include/net/netlink.h:1082
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
```
```
In net/ipv6/route.c (ffffffff81898421)
Location: include/net/netlink.h:1082
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff818bfc10)
Location: include/net/netlink.h:1082
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dbedc)
Location: include/net/netlink.h:1082
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818ddc75)
Location: include/net/netlink.h:1082
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff818e335d)
Location: include/net/netlink.h:1082
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/switchdev/switchdev.c (ffffffff818e6221)
Location: include/net/netlink.h:1082
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_br_setflag
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
In net/core/rtnetlink.c (ffffffff8185a7f7)
Location: include/net/netlink.h:1125
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff8186fd89)
Location: include/net/netlink.h:1125
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e5255)
Location: include/net/netlink.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff819179e7)
Location: include/net/netlink.h:1125
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
```
```
In net/ipv6/route.c (ffffffff819197d1)
Location: include/net/netlink.h:1125
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81942ce0)
Location: include/net/netlink.h:1125
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81961abc)
Location: include/net/netlink.h:1125
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81963865)
Location: include/net/netlink.h:1125
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff8196915d)
Location: include/net/netlink.h:1125
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
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
In net/core/rtnetlink.c (ffffffff818a606e)
Location: include/net/netlink.h:1125
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff818c06a8)
Location: include/net/netlink.h:1125
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193bb32)
Location: include/net/netlink.h:1125
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/netlink.c (ffffffff8193ca95)
Location: include/net/netlink.h:1125
Inline: True
Inline callers:
  - net/ipv4/netlink.c:rtm_getroute_parse_ip_proto
```
```
In net/ipv6/addrconf.c (ffffffff8196f122)
Location: include/net/netlink.h:1125
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
```
```
In net/ipv6/route.c (ffffffff819712be)
Location: include/net/netlink.h:1125
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff8199bbf9)
Location: include/net/netlink.h:1125
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bb26c)
Location: include/net/netlink.h:1125
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bd0dc)
Location: include/net/netlink.h:1125
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff819c0b20)
Location: include/net/netlink.h:1125
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
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
In lib/nlattr.c (ffffffff815067f2)
Location: include/net/netlink.h:1268
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/neighbour.c (ffffffff818c8614)
Location: include/net/netlink.h:1268
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff818c9687)
Location: include/net/netlink.h:1268
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff818e95f8)
Location: include/net/netlink.h:1268
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196b822)
Location: include/net/netlink.h:1268
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/netlink.c (ffffffff8196c815)
Location: include/net/netlink.h:1268
Inline: True
Inline callers:
  - net/ipv4/netlink.c:rtm_getroute_parse_ip_proto
```
```
In net/ipv6/addrconf.c (ffffffff819a4cd2)
Location: include/net/netlink.h:1268
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
```
```
In net/ipv6/route.c (ffffffff819a7ec2)
Location: include/net/netlink.h:1268
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff819d2419)
Location: include/net/netlink.h:1268
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f24dc)
Location: include/net/netlink.h:1268
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f431c)
Location: include/net/netlink.h:1268
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff819f7ed0)
Location: include/net/netlink.h:1268
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
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
In lib/nlattr.c (ffffffff81534363)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/neighbour.c (ffffffff81915163)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81916668)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff81939004)
Location: include/net/netlink.h:1526
Inline: True
```
```
In net/core/devlink.c (ffffffff8194775e)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d23c8)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/netlink.c (ffffffff819d3525)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/netlink.c:rtm_getroute_parse_ip_proto
```
```
In net/ipv6/addrconf.c (ffffffff81a07d14)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/route.c (ffffffff81a14ca9)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81a4123a)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a6182c)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a63781)
Location: include/net/netlink.h:1526
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81a67405)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
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
In lib/nlattr.c (ffffffff81555532)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/neighbour.c (ffffffff819477d3)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81948cb5)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff8196bec4)
Location: include/net/netlink.h:1526
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff8197462c)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config
```
```
In net/core/devlink.c (ffffffff8197d637)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a08f38)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/netlink.c (ffffffff81a0a095)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/netlink.c:rtm_getroute_parse_ip_proto
```
```
In net/ipv6/addrconf.c (ffffffff81a3e884)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/route.c (ffffffff81a4b899)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81a77eba)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a983fc)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a9a331)
Location: include/net/netlink.h:1526
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81a9df25)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
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
In lib/nlattr.c (ffffffff815dec93)
Location: include/net/netlink.h:1593
Inline: True
Inline callers:
  - lib/nlattr.c:nla_validate_int_range
```
```
In net/core/neighbour.c (ffffffff81a17932)
Location: include/net/netlink.h:1593
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81a18a90)
Location: include/net/netlink.h:1593
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff81a3fdd7)
Location: include/net/netlink.h:1593
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81a497ac)
Location: include/net/netlink.h:1593
Inline: True
```
```
In net/core/devlink.c (ffffffff81a52f83)
Location: include/net/netlink.h:1593
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
```
```
In net/ethtool/linkinfo.c (ffffffff81a8897b)
Location: include/net/netlink.h:1593
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81a88da8)
Location: include/net/netlink.h:1593
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/coalesce.c (ffffffff81a8bcb1)
Location: include/net/netlink.h:1593
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/pause.c (ffffffff81a8c1da)
Location: include/net/netlink.h:1593
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81a8c72c)
Location: include/net/netlink.h:1593
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81a8ccd3)
Location: include/net/netlink.h:1593
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af94df)
Location: include/net/netlink.h:1593
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/netlink.c (ffffffff81afa865)
Location: include/net/netlink.h:1593
Inline: True
Inline callers:
  - net/ipv4/netlink.c:rtm_getroute_parse_ip_proto
```
```
In net/ipv6/addrconf.c (ffffffff81b3e970)
Location: include/net/netlink.h:1593
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/route.c (ffffffff81b418ec)
Location: include/net/netlink.h:1593
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81b7231c)
Location: include/net/netlink.h:1593
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b94372)
Location: include/net/netlink.h:1593
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b95755)
Location: include/net/netlink.h:1593
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81b999e3)
Location: include/net/netlink.h:1593
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb3200)
Location: include/net/netlink.h:1593
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
In lib/nlattr.c (ffffffff815fc967)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
```
```
In net/core/neighbour.c (ffffffff81a17c05)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81a18b40)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff81a42ad7)
Location: include/net/netlink.h:1606
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81a4ef7c)
Location: include/net/netlink.h:1606
Inline: True
```
```
In net/core/devlink.c (ffffffff81a5958f)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
```
```
In net/ethtool/linkinfo.c (ffffffff81a92264)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81a92688)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/coalesce.c (ffffffff81a95309)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/pause.c (ffffffff81a9597c)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81a95e69)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81a963e3)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b0614f)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/netlink.c (ffffffff81b08025)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ipv4/netlink.c:rtm_getroute_parse_ip_proto
```
```
In net/ipv6/addrconf.c (ffffffff81b4d500)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/route.c (ffffffff81b503ac)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81b8108c)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba3fb2)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba53a5)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81ba96e3)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc76a0)
Location: include/net/netlink.h:1606
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
In lib/nlattr.c (ffffffff815df636)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
```
```
In net/core/neighbour.c (ffffffff819feb15)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff819ffa22)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff81a276a7)
Location: include/net/netlink.h:1606
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81a33fbd)
Location: include/net/netlink.h:1606
Inline: True
```
```
In net/core/devlink.c (ffffffff81a3c506)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_port_function_set
```
```
In net/ethtool/linkinfo.c (ffffffff81a7ba74)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81a7c26b)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/coalesce.c (ffffffff81a7edba)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/pause.c (ffffffff81a7f40c)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81a7f8f9)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81a7fe6b)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ethtool/fec.c (ffffffff81a819d1)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/ethtool/eeprom.c (ffffffff81a81c6c)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_parse_request
  - net/ethtool/eeprom.c:eeprom_parse_request
  - net/ethtool/eeprom.c:eeprom_parse_request
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af19b2)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/netlink.c (ffffffff81af3885)
Location: include/net/netlink.h:1606
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b3b3a8)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/route.c (ffffffff81b3e880)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81b6fc9c)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b930d7)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b94505)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81b98875)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb8b44)
Location: include/net/netlink.h:1606
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
In lib/nlattr.c (ffffffff8164b1f1)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
```
```
In net/core/neighbour.c (ffffffff81ab0cc5)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81ab1d06)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff81adc447)
Location: include/net/netlink.h:1606
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81ae9ac7)
Location: include/net/netlink.h:1606
Inline: True
```
```
In net/core/devlink.c (ffffffff81af27e6)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_port_function_set
```
```
In net/ethtool/linkinfo.c (ffffffff81b35db8)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81b365ab)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/coalesce.c (ffffffff81b38d14)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/pause.c (ffffffff81b39302)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81b39766)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81b39c3b)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ethtool/fec.c (ffffffff81b3b6a2)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/ethtool/eeprom.c (ffffffff81b3b8ec)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_parse_request
  - net/ethtool/eeprom.c:eeprom_parse_request
  - net/ethtool/eeprom.c:eeprom_parse_request
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1ec2)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/netlink.c (ffffffff81bb3da5)
Location: include/net/netlink.h:1606
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81c01ba8)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/route.c (ffffffff81c051d0)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81c37dec)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f877)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60cb0)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81c65484)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
```
```
In net/mptcp/pm_netlink.c (ffffffff81c88114)
Location: include/net/netlink.h:1606
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
In lib/nlattr.c (ffffffff81761bdc)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
```
```
In net/core/neighbour.c (ffffffff81c29d9f)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81c33d2a)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff81c5d8cd)
Location: include/net/netlink.h:1606
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81c6c327)
Location: include/net/netlink.h:1606
Inline: True
```
```
In net/core/devlink.c (ffffffff81c76799)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_port_function_set
```
```
In net/ethtool/linkinfo.c (ffffffff81cc1694)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81cc1efb)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rings.c (ffffffff81cc3bdf)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/coalesce.c (ffffffff81cc4ac2)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/pause.c (ffffffff81cc5100)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81cc5594)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81cc5ae5)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ethtool/fec.c (ffffffff81cc76a4)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/ethtool/eeprom.c (ffffffff81cc790c)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_parse_request
  - net/ethtool/eeprom.c:eeprom_parse_request
  - net/ethtool/eeprom.c:eeprom_parse_request
```
```
In net/ethtool/module.c (ffffffff81cc8b43)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ethtool/module.c:ethnl_set_module
```
```
In net/ipv4/devinet.c (ffffffff81d29032)
Location: include/net/netlink.h:1606
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45628)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/netlink.c (ffffffff81d47625)
Location: include/net/netlink.h:1606
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81d9b8da)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
```
In net/ipv6/route.c (ffffffff81d9f256)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81dd59d0)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81deb801)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e01cb1)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e03218)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81e0812e)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2e9c2)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
```
```
In net/mptcp/pm_userspace.c (ffffffff81e35800)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
```
```
In net/mctp/route.c (ffffffff81e396c1)
Location: include/net/netlink.h:1606
Inline: True
```
```
In net/mctp/neigh.c (ffffffff81e3b57f)
Location: include/net/netlink.h:1606
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_delneigh
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
In lib/nlattr.c (ffffffff81890840)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_range_unsigned
```
```
In net/core/neighbour.c (ffffffff81ddcaab)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81de718a)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff81e140ad)
Location: include/net/netlink.h:1655
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81e23d17)
Location: include/net/netlink.h:1655
Inline: True
```
```
In net/core/devlink.c (ffffffff81e2efa9)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_port_function_set
```
```
In net/ethtool/linkinfo.c (ffffffff81e80414)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81e80ceb)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rings.c (ffffffff81e82f7f)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/coalesce.c (ffffffff81e83f98)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/pause.c (ffffffff81e84610)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81e84ae4)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81e85095)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ethtool/fec.c (ffffffff81e86d14)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/ethtool/eeprom.c (ffffffff81e86fbc)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_parse_request
  - net/ethtool/eeprom.c:eeprom_parse_request
  - net/ethtool/eeprom.c:eeprom_parse_request
```
```
In net/ethtool/module.c (ffffffff81e88353)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/ethtool/module.c:ethnl_set_module
```
```
In net/ipv4/devinet.c (ffffffff81ef0972)
Location: include/net/netlink.h:1655
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0dab5)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
```
```
In net/ipv4/netlink.c (ffffffff81f10ab5)
Location: include/net/netlink.h:1655
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81f6a52a)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
```
In net/ipv6/route.c (ffffffff81f6e266)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81fa717d)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (ffffffff81fbbe34)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_flavors
  - net/ipv6/seg6_local.c:parse_nla_flavors
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbf461)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd6b61)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd8188)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81fdd69e)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
```
```
In net/mptcp/pm_netlink.c (ffffffff82006b52)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
```
```
In net/mptcp/pm_userspace.c (ffffffff8200e4c0)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
```
```
In net/mctp/route.c (ffffffff82012771)
Location: include/net/netlink.h:1655
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82014c4f)
Location: include/net/netlink.h:1655
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_delneigh
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
In lib/nlattr.c (ffffffff818d2d65)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_range_unsigned
```
```
In net/core/neighbour.c (ffffffff81e4d830)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81e5817a)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff81e879bd)
Location: include/net/netlink.h:1656
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81e99087)
Location: include/net/netlink.h:1656
Inline: True
```
```
In net/ethtool/linkinfo.c (ffffffff81edcb42)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81edcc93)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes_validate
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rings.c (ffffffff81edf752)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/coalesce.c (ffffffff81ee045c)
Location: include/net/netlink.h:1656
Inline: True
```
```
In net/ethtool/pause.c (ffffffff81ee0d4e)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81ee144c)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81ee19c5)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ethtool/fec.c (ffffffff81ee350b)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/ethtool/eeprom.c (ffffffff81ee3a1c)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_parse_request
  - net/ethtool/eeprom.c:eeprom_parse_request
  - net/ethtool/eeprom.c:eeprom_parse_request
```
```
In net/ethtool/mm.c (ffffffff81ee5492)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/ethtool/mm.c:ethnl_set_mm
  - net/ethtool/mm.c:ethnl_set_mm
  - net/ethtool/mm.c:ethnl_set_mm
```
```
In net/ethtool/module.c (ffffffff81ee5c9b)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/ethtool/module.c:ethnl_set_module
```
```
In net/ipv4/devinet.c (ffffffff81f503d2)
Location: include/net/netlink.h:1656
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6d755)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
```
```
In net/ipv4/netlink.c (ffffffff81f707a5)
Location: include/net/netlink.h:1656
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fca56a)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
```
In net/ipv6/route.c (ffffffff81fce326)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff820079dd)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (ffffffff8201c734)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_flavors
  - net/ipv6/seg6_local.c:parse_nla_flavors
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820203f1)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/devlink/leftover.c (ffffffff82030ec9)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_trap_group_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/devlink/leftover.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_pool_set_doit
  - net/devlink/leftover.c:devlink_port_function_set
```
```
In net/devlink/dev.c (ffffffff8204503b)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_eswitch_set_doit
  - net/devlink/dev.c:devlink_nl_cmd_eswitch_set_doit
  - net/devlink/dev.c:devlink_nl_cmd_reload
```
```
In net/devlink/health.c (ffffffff82048044)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_set_doit
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_set_doit
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82052851)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053e63)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff820598ce)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
```
```
In net/mptcp/pm_netlink.c (ffffffff82082ef2)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
```
```
In net/mptcp/pm_userspace.c (ffffffff8208af50)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
```
```
In net/mctp/route.c (ffffffff8208f561)
Location: include/net/netlink.h:1656
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82091a6f)
Location: include/net/netlink.h:1656
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_delneigh
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
In lib/nlattr.c (ffffffff819249d7)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_range_unsigned
```
```
In net/core/neighbour.c (ffffffff81f0c583)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81f174ca)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff81f499d3)
Location: include/net/netlink.h:1732
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81f5b747)
Location: include/net/netlink.h:1732
Inline: True
```
```
In net/ethtool/linkinfo.c (ffffffff81fa0912)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81fa0a63)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes_validate
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rings.c (ffffffff81fa35b9)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/coalesce.c (ffffffff81fa42ec)
Location: include/net/netlink.h:1732
Inline: True
```
```
In net/ethtool/pause.c (ffffffff81fa4bde)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81fa52dc)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81fa5858)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ethtool/fec.c (ffffffff81fa72eb)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/ethtool/eeprom.c (ffffffff81fa77fc)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_parse_request
  - net/ethtool/eeprom.c:eeprom_parse_request
  - net/ethtool/eeprom.c:eeprom_parse_request
```
```
In net/ethtool/mm.c (ffffffff81fa9272)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ethtool/mm.c:ethnl_set_mm
  - net/ethtool/mm.c:ethnl_set_mm
  - net/ethtool/mm.c:ethnl_set_mm
```
```
In net/ethtool/module.c (ffffffff81fa9a7b)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ethtool/module.c:ethnl_set_module
```
```
In net/ethtool/plca.c (ffffffff81faa41b)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ethtool/plca.c:ethnl_set_plca
```
```
In net/ipv4/devinet.c (ffffffff82016590)
Location: include/net/netlink.h:1732
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82033ea5)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
```
```
In net/ipv4/netlink.c (ffffffff82036f05)
Location: include/net/netlink.h:1732
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff82097d0d)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
```
In net/ipv6/route.c (ffffffff8209bb82)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff820d686d)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_local.c (ffffffff820eb88c)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_flavors
  - net/ipv6/seg6_local.c:parse_nla_flavors
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820ef524)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/devlink/dev.c (ffffffff821048fb)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_eswitch_set_doit
  - net/devlink/dev.c:devlink_nl_eswitch_set_doit
  - net/devlink/dev.c:devlink_nl_reload_doit
```
```
In net/devlink/port.c (ffffffff8210701c)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_port_function_set
```
```
In net/devlink/sb.c (ffffffff8210a19a)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_set_doit
  - net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_get_doit
  - net/devlink/sb.c:devlink_nl_sb_pool_set_doit
```
```
In net/devlink/dpipe.c (ffffffff8210c12e)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devlink_nl_dpipe_table_counters_set_doit
```
```
In net/devlink/param.c (ffffffff8210da4b)
Location: include/net/netlink.h:1732
Inline: True
```
```
In net/devlink/health.c (ffffffff821140d4)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_set_doit
  - net/devlink/health.c:devlink_nl_health_reporter_set_doit
```
```
In net/devlink/trap.c (ffffffff82117289)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_group_set_doit
  - net/devlink/trap.c:devlink_nl_trap_set_doit
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8212504a)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82126639)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (ffffffff8212c451)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
```
```
In net/mptcp/pm_netlink.c (ffffffff82158563)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
```
```
In net/mptcp/pm_userspace.c (ffffffff82160bc0)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit
```
```
In net/mctp/route.c (ffffffff82165a41)
Location: include/net/netlink.h:1732
Inline: True
```
```
In net/mctp/neigh.c (ffffffff8216800f)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_delneigh
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
In lib/nlattr.c (ffff80001066189c)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/neighbour.c (ffff800010be8c58)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffff800010bec01c)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffff800010c125a0)
Location: include/net/netlink.h:1526
Inline: True
```
```
In net/core/drop_monitor.c (ffff800010c1a4fc)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config
```
```
In net/core/devlink.c (ffff800010c251a8)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc2264)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/netlink.c (ffff800010cc3480)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/netlink.c:rtm_getroute_parse_ip_proto
```
```
In net/ipv6/addrconf.c (ffff800010cff858)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/route.c (ffff800010d0e6dc)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffff800010d414ec)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d67ae0)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d69d90)
Location: include/net/netlink.h:1526
Inline: True
```
```
In net/dcb/dcbnl.c (ffff800010d6e898)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
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
In lib/nlattr.c (c080aa74)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/neighbour.c (c0d01e00)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (c0d032f0)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (c0d2a0d8)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl2rule
  - net/core/fib_rules.c:fib_nl2rule
  - net/core/fib_rules.c:fib_nl2rule
```
```
In net/core/drop_monitor.c (c0d325bc)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config
```
```
In net/core/devlink.c (c0d3a40c)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
```
```
In net/ipv4/ip_tunnel_core.c (c0dcd950)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/netlink.c (c0dcec94)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/netlink.c:rtm_getroute_parse_ip_proto
```
```
In net/ipv6/addrconf.c (c0e07dd4)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/route.c (c0e153e4)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (c0e43ed4)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (c0e66bcc)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e6829c)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
```
In net/dcb/dcbnl.c (c0e6c7f4)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
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
In lib/nlattr.c (c000000000815734)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/neighbour.c (c000000000ccb308)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (c000000000ccd3f0)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (c000000000cff5b8)
Location: include/net/netlink.h:1526
Inline: True
```
```
In net/core/drop_monitor.c (c000000000d0a92c)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config
```
```
In net/core/devlink.c (c000000000d18eb8)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
```
```
In net/ipv4/ip_tunnel_core.c (c000000000ddd8b4)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/netlink.c (c000000000ddf0a0)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/netlink.c:rtm_getroute_parse_ip_proto
```
```
In net/ipv6/addrconf.c (c000000000e29250)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/route.c (c000000000e3afbc)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (c000000000e760d0)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea4414)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea6ed0)
Location: include/net/netlink.h:1526
Inline: True
```
```
In net/dcb/dcbnl.c (c000000000ead1c0)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
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
In lib/nlattr.c (ffffffe00048e176)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/neighbour.c (ffffffe00076cff8)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffe00076e172)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffe00078e44c)
Location: include/net/netlink.h:1526
Inline: True
```
```
In net/core/drop_monitor.c (ffffffe000794aa2)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config
```
```
In net/core/devlink.c (ffffffe00079d696)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817738)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/netlink.c (ffffffe0008187cc)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/netlink.c:rtm_getroute_parse_ip_proto
```
```
In net/ipv6/addrconf.c (ffffffe00084a0ce)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/route.c (ffffffe00085670a)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffe00087cc18)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089b09c)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089cc84)
Location: include/net/netlink.h:1526
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffe0008a0716)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
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
In lib/nlattr.c (ffffffff8154db12)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/neighbour.c (ffffffff818e77a3)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff818e8c85)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff8190be94)
Location: include/net/netlink.h:1526
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff819145fc)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config
```
```
In net/core/devlink.c (ffffffff8191d4a7)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8cd8)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/netlink.c (ffffffff819a9e35)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/netlink.c:rtm_getroute_parse_ip_proto
```
```
In net/ipv6/addrconf.c (ffffffff819ddf14)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/route.c (ffffffff819eaf29)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81a1754a)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a3778c)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a396c1)
Location: include/net/netlink.h:1526
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81a3d2b5)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
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
In lib/nlattr.c (ffffffff8153ddf2)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/vxlan.c (ffffffff8176eab5)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_nl2flag
  - drivers/net/vxlan.c:vxlan_validate
```
```
In net/core/neighbour.c (ffffffff818a15e3)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff818a2ac5)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff818c5c54)
Location: include/net/netlink.h:1526
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff818ce3bc)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config
```
```
In net/core/devlink.c (ffffffff818d7257)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962798)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/netlink.c (ffffffff819638f5)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/netlink.c:rtm_getroute_parse_ip_proto
```
```
In net/ipv6/addrconf.c (ffffffff8199acd4)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/route.c (ffffffff819a7ce9)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff819d430a)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f43ac)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f62e1)
Location: include/net/netlink.h:1526
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff819f9ea5)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
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
In lib/nlattr.c (ffffffff81549852)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/neighbour.c (ffffffff819387d3)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81939cb5)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff8195cec4)
Location: include/net/netlink.h:1526
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff8196562c)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config
```
```
In net/core/devlink.c (ffffffff8196e637)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
```
```
In net/netfilter/nf_conntrack_proto_tcp.c (ffffffff819a53d5)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:nlattr_to_tcp
  - net/netfilter/nf_conntrack_proto_tcp.c:nlattr_to_tcp
  - net/netfilter/nf_conntrack_proto_tcp.c:nlattr_to_tcp
  - net/netfilter/nf_conntrack_proto_tcp.c:nlattr_to_tcp
```
```
In net/netfilter/nf_conntrack_proto_icmp.c (ffffffff819a7530)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmp.c:icmp_nlattr_to_tuple
  - net/netfilter/nf_conntrack_proto_icmp.c:icmp_nlattr_to_tuple
```
```
In net/netfilter/nf_conntrack_proto_icmpv6.c (ffffffff819a8570)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmpv6.c:icmpv6_nlattr_to_tuple
  - net/netfilter/nf_conntrack_proto_icmpv6.c:icmpv6_nlattr_to_tuple
```
```
In net/netfilter/nf_conntrack_proto_dccp.c (ffffffff819a99b6)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_dccp.c:nlattr_to_dccp
  - net/netfilter/nf_conntrack_proto_dccp.c:nlattr_to_dccp
  - net/netfilter/nf_conntrack_proto_dccp.c:nlattr_to_dccp
  - net/netfilter/nf_conntrack_proto_dccp.c:nlattr_to_dccp
```
```
In net/netfilter/nf_conntrack_proto_sctp.c (ffffffff819aa7f5)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_sctp.c:nlattr_to_sctp
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ac823)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple_proto
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13578)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/netlink.c (ffffffff81a146d5)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/netlink.c:rtm_getroute_parse_ip_proto
```
```
In net/ipv6/addrconf.c (ffffffff81a48994)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/route.c (ffffffff81a559a9)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81a81fca)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa363c)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa5571)
Location: include/net/netlink.h:1526
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81aa9165)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
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
In lib/nlattr.c (ffffffff815636a2)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/neighbour.c (ffffffff81959fe3)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff8195b395)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/fib_rules.c (ffffffff8197f114)
Location: include/net/netlink.h:1526
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff8198786c)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config
```
```
In net/core/devlink.c (ffffffff81990ae7)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1df48)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv4/netlink.c (ffffffff81a1f0e5)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv4/netlink.c:rtm_getroute_parse_ip_proto
```
```
In net/ipv6/addrconf.c (ffffffff81a54ac4)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/route.c (ffffffff81a619a9)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/seg6.c (ffffffff81a8e8da)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_sethmac
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aafa5c)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab1911)
Location: include/net/netlink.h:1526
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81ab54d5)
Location: include/net/netlink.h:1526
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
```
</details>
</li>
</ul>

## Differences
