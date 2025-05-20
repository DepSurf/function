# Function: <code>nla_get_u16</code>

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
In net/core/rtnetlink.c (ffffffff8172a674)
Location: include/net/netlink.h:1019
Inline: True
Inline callers:
  - net/core/rtnetlink.c:fdb_vid_parse
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
```
```
In net/netlink/genetlink.c (ffffffff817500a0)
Location: include/net/netlink.h:1019
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff81799dff)
Location: include/net/netlink.h:1019
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1019
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a45bd)
Location: include/net/netlink.h:1019
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv6/route.c (ffffffff817d4196)
Location: include/net/netlink.h:1019
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_route_multipath_add
```
```
In net/dcb/dcbnl.c (ffffffff8181526f)
Location: include/net/netlink.h:1019
Inline: True
Inline callers:
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
In net/core/rtnetlink.c (ffffffff8179487f)
Location: include/net/netlink.h:1043
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:fdb_vid_parse
```
```
In net/netlink/genetlink.c (ffffffff817bc070)
Location: include/net/netlink.h:1043
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff81807aee)
Location: include/net/netlink.h:1043
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1043
Inline: True
```
```
In net/ipv6/route.c (ffffffff81844e65)
Location: include/net/netlink.h:1043
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8187fef4)
Location: include/net/netlink.h:1043
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/dcb/dcbnl.c (ffffffff8188813f)
Location: include/net/netlink.h:1043
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
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
In net/core/rtnetlink.c (ffffffff817c20fd)
Location: include/net/netlink.h:1043
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:fdb_vid_parse
```
```
In net/core/lwtunnel.c (0)
Location: include/net/netlink.h:1043
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff817eba90)
Location: include/net/netlink.h:1043
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff81838b90)
Location: include/net/netlink.h:1043
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1043
Inline: True
```
```
In net/ipv6/route.c (ffffffff81876bd5)
Location: include/net/netlink.h:1043
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b47a4)
Location: include/net/netlink.h:1043
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/dcb/dcbnl.c (ffffffff818bc95f)
Location: include/net/netlink.h:1043
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
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
In net/core/rtnetlink.c (ffffffff817e0887)
Location: include/net/netlink.h:1055
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:fdb_vid_parse
```
```
In net/core/lwtunnel.c (ffffffff817f8b72)
Location: include/net/netlink.h:1055
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/netlink/genetlink.c (0)
Location: include/net/netlink.h:1055
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81859e70)
Location: include/net/netlink.h:1055
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1055
Inline: True
```
```
In net/ipv6/route.c (ffffffff8189e8bb)
Location: include/net/netlink.h:1055
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818db136)
Location: include/net/netlink.h:1055
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/dcb/dcbnl.c (ffffffff818e3372)
Location: include/net/netlink.h:1055
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
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
In net/core/rtnetlink.c (ffffffff8185b105)
Location: include/net/netlink.h:1098
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffffffff81876452)
Location: include/net/netlink.h:1098
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/netlink/genetlink.c (0)
Location: include/net/netlink.h:1098
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff818d9d76)
Location: include/net/netlink.h:1098
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:1098
Inline: True
```
```
In net/ipv6/route.c (ffffffff81920e71)
Location: include/net/netlink.h:1098
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81960d16)
Location: include/net/netlink.h:1098
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/dcb/dcbnl.c (ffffffff81969172)
Location: include/net/netlink.h:1098
Inline: True
Inline callers:
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
In net/core/rtnetlink.c (ffffffff818a69a8)
Location: include/net/netlink.h:1098
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffffffff818c7b95)
Location: include/net/netlink.h:1098
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff818ddfd0)
Location: include/net/netlink.h:1098
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff81930817)
Location: include/net/netlink.h:1098
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff819345d6)
Location: include/net/netlink.h:1098
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff8197927d)
Location: include/net/netlink.h:1098
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819ba506)
Location: include/net/netlink.h:1098
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/dcb/dcbnl.c (ffffffff819c299b)
Location: include/net/netlink.h:1098
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
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
In lib/nlattr.c (ffffffff815068e1)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff818ca208)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffffffff818f0cf5)
Location: include/net/netlink.h:1241
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8190a990)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff8195fc8a)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81963eba)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff819aee5d)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f1f16)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/dcb/dcbnl.c (ffffffff819f9efb)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
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
In lib/nlattr.c (ffffffff81534650)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff8191721f)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffffffff819423f4)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/devlink.c (ffffffff81950655)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
```
In net/netlink/genetlink.c (ffffffff8196bd90)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff819c6753)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff819c852a)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/nexthop.c (ffffffff819d4121)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81a1cdf7)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a61216)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/dcb/dcbnl.c (ffffffff81a69440)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
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
In lib/nlattr.c (ffffffff8155543b)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff8194985f)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffffffff81977324)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/devlink.c (ffffffff81986dd9)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
```
In net/netlink/genetlink.c (ffffffff819a2740)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff819fd303)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff819ff0da)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/nexthop.c (ffffffff81a0ac91)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81a53ab1)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a97e36)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/dcb/dcbnl.c (ffffffff81a9fda0)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
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
In lib/nlattr.c (ffffffff815dec3e)
Location: include/net/netlink.h:1566
Inline: True
Inline callers:
  - lib/nlattr.c:nla_validate_int_range
```
```
In net/core/rtnetlink.c (ffffffff81a19bef)
Location: include/net/netlink.h:1566
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffffffff81a4c114)
Location: include/net/netlink.h:1566
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/devlink.c (ffffffff81a503dd)
Location: include/net/netlink.h:1566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
```
In net/netlink/genetlink.c (ffffffff81a7c5ec)
Location: include/net/netlink.h:1566
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff81aebcf9)
Location: include/net/netlink.h:1566
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81aee668)
Location: include/net/netlink.h:1566
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/nexthop.c (ffffffff81afb628)
Location: include/net/netlink.h:1566
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81b4b1b8)
Location: include/net/netlink.h:1566
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b93756)
Location: include/net/netlink.h:1566
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81b9bac0)
Location: include/net/netlink.h:1566
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb31b4)
Location: include/net/netlink.h:1566
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
In lib/nlattr.c (ffffffff815fc62c)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
```
```
In net/core/rtnetlink.c (ffffffff81a19ddf)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffffffff81a51d44)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/devlink.c (ffffffff81a5647d)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
```
In net/netlink/genetlink.c (ffffffff81a86a5b)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff81af8bbd)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81afb5c8)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/nexthop.c (ffffffff81b08cf8)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81b59e57)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba33a6)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81bab7d0)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7654)
Location: include/net/netlink.h:1579
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
In lib/nlattr.c (ffffffff815df2d3)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
```
```
In net/core/rtnetlink.c (ffffffff81a00deb)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffffffff81a37644)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/devlink.c (ffffffff81a3944d)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
```
In net/netlink/genetlink.c (ffffffff81a6efcb)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae432f)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae6cbd)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/nexthop.c (ffffffff81af59db)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81b47ed7)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b924c6)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81b9a970)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb8af8)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
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
In lib/nlattr.c (ffffffff8164ae69)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
```
```
In net/core/rtnetlink.c (ffffffff81ab31ab)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffffffff81aed33f)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/devlink.c (ffffffff81af0967)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
```
In net/netlink/genetlink.c (ffffffff81b28a0b)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba3c7f)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba692c)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/nexthop.c (ffffffff81bb62db)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81c0ee77)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ioam6.c (ffffffff81c39702)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5ec66)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81c68020)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/mptcp/pm_netlink.c (ffffffff81c880c8)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
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
In lib/nlattr.c (ffffffff817617f7)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
```
```
In net/core/rtnetlink.c (ffffffff81c2c2fb)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffffffff81c6ffc6)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/devlink.c (ffffffff81c7406f)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
```
In net/netlink/genetlink.c (ffffffff81cb130d)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff81d36505)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81d39313)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/nexthop.c (ffffffff81d49eea)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81daa208)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ioam6.c (ffffffff81dd732b)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00eb6)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81e0b6dd)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/mptcp/pm_netlink.c (ffffffff81e316f9)
Location: include/net/netlink.h:1579
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_entry
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
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
In lib/nlattr.c (ffffffff818904e4)
Location: include/net/netlink.h:1628
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_range_unsigned
```
```
In net/core/rtnetlink.c (ffffffff81ddf3bb)
Location: include/net/netlink.h:1628
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffffffff81e27f16)
Location: include/net/netlink.h:1628
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/devlink.c (ffffffff81e2ccdf)
Location: include/net/netlink.h:1628
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
```
In net/netlink/genetlink.c (ffffffff81e6fb22)
Location: include/net/netlink.h:1628
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff81efeb26)
Location: include/net/netlink.h:1628
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81f01be3)
Location: include/net/netlink.h:1628
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0dc70)
Location: include/net/netlink.h:1628
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_encap_parms
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_encap_parms
```
```
In net/ipv4/nexthop.c (ffffffff81f1355a)
Location: include/net/netlink.h:1628
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81f799d8)
Location: include/net/netlink.h:1628
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ioam6.c (ffffffff81fa8cfb)
Location: include/net/netlink.h:1628
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd5d26)
Location: include/net/netlink.h:1628
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/dcb/dcbnl.c (ffffffff81fe0b5d)
Location: include/net/netlink.h:1628
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/mptcp/pm_netlink.c (ffffffff82009d29)
Location: include/net/netlink.h:1628
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_entry
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
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
In lib/nlattr.c (ffffffff818d2985)
Location: include/net/netlink.h:1629
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_range_unsigned
```
```
In net/core/rtnetlink.c (ffffffff81e506db)
Location: include/net/netlink.h:1629
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffffffff81e9d526)
Location: include/net/netlink.h:1629
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/netlink/genetlink.c (ffffffff81ecb3f2)
Location: include/net/netlink.h:1629
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5e625)
Location: include/net/netlink.h:1629
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81f61643)
Location: include/net/netlink.h:1629
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6d920)
Location: include/net/netlink.h:1629
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_encap_parms
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_encap_parms
```
```
In net/ipv4/nexthop.c (ffffffff81f7322a)
Location: include/net/netlink.h:1629
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81fd9be8)
Location: include/net/netlink.h:1629
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ioam6.c (ffffffff8200968b)
Location: include/net/netlink.h:1629
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/devlink/leftover.c (ffffffff820346ca)
Location: include/net/netlink.h:1629
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_pool_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_pool_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_port_new_doit
  - net/devlink/leftover.c:devlink_nl_cmd_port_new_doit
  - net/devlink/leftover.c:devlink_nl_cmd_port_new_doit
  - net/devlink/leftover.c:devlink_nl_cmd_port_set_doit
```
```
In net/devlink/dev.c (ffffffff82044fed)
Location: include/net/netlink.h:1629
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_eswitch_set_doit
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff820519e6)
Location: include/net/netlink.h:1629
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/dcb/dcbnl.c (ffffffff8205d55d)
Location: include/net/netlink.h:1629
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/mptcp/pm_netlink.c (ffffffff82086039)
Location: include/net/netlink.h:1629
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_entry
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
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
In lib/nlattr.c (ffffffff81924e62)
Location: include/net/netlink.h:1705
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_range_unsigned
```
```
In net/core/rtnetlink.c (ffffffff81f0f77c)
Location: include/net/netlink.h:1705
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffffffff81f5fcab)
Location: include/net/netlink.h:1705
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/netlink/genetlink.c (ffffffff81f8e8e2)
Location: include/net/netlink.h:1705
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff82024bf4)
Location: include/net/netlink.h:1705
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff82027c15)
Location: include/net/netlink.h:1705
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034070)
Location: include/net/netlink.h:1705
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_encap_parms
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_encap_parms
```
```
In net/ipv4/nexthop.c (ffffffff820392ed)
Location: include/net/netlink.h:1705
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff820a74e4)
Location: include/net/netlink.h:1705
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ioam6.c (ffffffff820d862b)
Location: include/net/netlink.h:1705
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/devlink/dev.c (ffffffff821048ad)
Location: include/net/netlink.h:1705
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_eswitch_set_doit
```
```
In net/devlink/port.c (ffffffff82107fe8)
Location: include/net/netlink.h:1705
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_new_doit
  - net/devlink/port.c:devlink_nl_port_new_doit
  - net/devlink/port.c:devlink_nl_port_new_doit
  - net/devlink/port.c:devlink_nl_port_set_doit
```
```
In net/devlink/sb.c (ffffffff8210a1ba)
Location: include/net/netlink.h:1705
Inline: True
Inline callers:
  - net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_set_doit
  - net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_set_doit
  - net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_get_doit
  - net/devlink/sb.c:devlink_nl_sb_port_pool_set_doit
  - net/devlink/sb.c:devlink_nl_sb_port_pool_get_doit
  - net/devlink/sb.c:devlink_nl_sb_pool_set_doit
  - net/devlink/sb.c:devlink_nl_sb_pool_get_doit
```
```
In net/devlink/param.c (ffffffff8210d9d4)
Location: include/net/netlink.h:1705
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff821241b6)
Location: include/net/netlink.h:1705
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/dcb/dcbnl.c (ffffffff82130180)
Location: include/net/netlink.h:1705
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/mptcp/pm_netlink.c (ffffffff8215b1e9)
Location: include/net/netlink.h:1705
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_entry
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
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
In lib/nlattr.c (ffff8000106617d0)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffff800010beb394)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffff800010c1dca0)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/devlink.c (ffff800010c2f21c)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
```
In net/netlink/genetlink.c (ffff800010c519fc)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffff800010cb5478)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffff800010cb7624)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/nexthop.c (ffff800010cc4214)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffff800010d17c58)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d67434)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/dcb/dcbnl.c (ffff800010d71360)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
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
In lib/nlattr.c (c080aa68)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (c0d0406c)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (c0d35920)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/devlink.c (c0d46360)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
```
In net/netlink/genetlink.c (c0d610f4)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (c0dc0d1c)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (c0dc3af8)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/nexthop.c (c0dcfc04)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (c0e1d7e8)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (c0e65a38)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/dcb/dcbnl.c (c0e6e384)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
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
In lib/nlattr.c (c000000000815728)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (c000000000cce81c)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (c000000000d0f25c)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/devlink.c (c000000000d272e4)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
```
In net/netlink/genetlink.c (c000000000d50418)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (c000000000dccdf0)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (c000000000dcfb98)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/nexthop.c (c000000000de0168)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (c000000000e457d0)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea3200)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/dcb/dcbnl.c (c000000000eafd4c)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
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
In lib/nlattr.c (ffffffe00048e16e)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffe00076ecea)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffffffe00079781c)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/devlink.c (ffffffe0007a5848)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
```
In net/netlink/genetlink.c (ffffffe0007bcb2e)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffe00080cd90)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffe00080e91c)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/nexthop.c (ffffffe00081980c)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffe00085cbdc)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089aaf2)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/dcb/dcbnl.c (ffffffe0008a1e4c)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
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
In lib/nlattr.c (ffffffff8154da1b)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff818e982f)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffffffff81917194)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/devlink.c (ffffffff81926c49)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
```
In net/netlink/genetlink.c (ffffffff819425b0)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff8199d0a3)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff8199ee7a)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/nexthop.c (ffffffff819aaa31)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff819f3141)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a371c6)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/dcb/dcbnl.c (ffffffff81a3f130)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
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
In lib/nlattr.c (ffffffff8153dcfb)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff818a366f)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffffffff818d0f44)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/devlink.c (ffffffff818e09f9)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
```
In net/netlink/genetlink.c (ffffffff818fc0a0)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff81956b63)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff8195893a)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/nexthop.c (ffffffff819644f1)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff819aff01)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f3de6)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/dcb/dcbnl.c (ffffffff819fbd20)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
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
In lib/nlattr.c (ffffffff8154975b)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff8193a85f)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffffffff81968324)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/devlink.c (ffffffff81977dd9)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
```
In net/netlink/genetlink.c (ffffffff81993740)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff81a07943)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0971a)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/nexthop.c (ffffffff81a152d1)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81a5dbc1)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa3076)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/dcb/dcbnl.c (ffffffff81aaafe0)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
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
In lib/nlattr.c (ffffffff815635ab)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In net/core/rtnetlink.c (ffffffff8195c08f)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/lwtunnel.c (ffffffff8198a5e4)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/core/devlink.c (ffffffff8199a2c9)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_set_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
```
In net/netlink/genetlink.c (ffffffff819b6230)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/fib_frontend.c (ffffffff81a12083)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81a13eca)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/nexthop.c (ffffffff81a1fd11)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81a69fd1)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aaf3e6)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/dcb/dcbnl.c (ffffffff81ab7350)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
```
</details>
</li>
</ul>

## Differences
