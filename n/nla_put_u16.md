# Function: <code>nla_put_u16</code>

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
In net/core/rtnetlink.c (ffffffff8172f659)
Location: include/net/netlink.h:757
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/lwtunnel.c (ffffffff8173e306)
Location: include/net/netlink.h:757
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8174fc6a)
Location: include/net/netlink.h:757
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:genl_ctrl_event
```
```
In net/ipv4/tcp_metrics.c (ffffffff81781456)
Location: include/net/netlink.h:757
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a4372)
Location: include/net/netlink.h:757
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/dcb/dcbnl.c (ffffffff8181444c)
Location: include/net/netlink.h:757
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
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
In net/core/rtnetlink.c (ffffffff817991dc)
Location: include/net/netlink.h:768
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/lwtunnel.c (ffffffff817aac74)
Location: include/net/netlink.h:768
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff817bc39b)
Location: include/net/netlink.h:768
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ee91b)
Location: include/net/netlink.h:768
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8187faba)
Location: include/net/netlink.h:768
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81887308)
Location: include/net/netlink.h:768
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/switchdev/switchdev.c (ffffffff8188ae4c)
Location: include/net/netlink.h:768
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb
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
In net/core/rtnetlink.c (ffffffff817c6f8c)
Location: include/net/netlink.h:768
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/lwtunnel.c (ffffffff817d9a14)
Location: include/net/netlink.h:768
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff817ebcab)
Location: include/net/netlink.h:768
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f32b)
Location: include/net/netlink.h:768
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b436a)
Location: include/net/netlink.h:768
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff818bbb58)
Location: include/net/netlink.h:768
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/switchdev/switchdev.c (ffffffff818bf21c)
Location: include/net/netlink.h:768
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb
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
In net/core/rtnetlink.c (ffffffff817e5880)
Location: include/net/netlink.h:780
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/lwtunnel.c (ffffffff817f8ca8)
Location: include/net/netlink.h:780
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8180bc08)
Location: include/net/netlink.h:780
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183fee4)
Location: include/net/netlink.h:780
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffffffff8186acfe)
Location: include/net/netlink.h:780
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818dad1a)
Location: include/net/netlink.h:780
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff818e254d)
Location: include/net/netlink.h:780
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/switchdev/switchdev.c (ffffffff818e5b8b)
Location: include/net/netlink.h:780
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb
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
In net/core/rtnetlink.c (ffffffff81860920)
Location: include/net/netlink.h:789
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/lwtunnel.c (ffffffff8187658b)
Location: include/net/netlink.h:789
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8188ab98)
Location: include/net/netlink.h:789
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf28b)
Location: include/net/netlink.h:789
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffffffff818eb493)
Location: include/net/netlink.h:789
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819608f5)
Location: include/net/netlink.h:789
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff8196830d)
Location: include/net/netlink.h:789
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
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
In net/core/rtnetlink.c (ffffffff818aa7f3)
Location: include/net/netlink.h:789
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/lwtunnel.c (ffffffff818c7cc0)
Location: include/net/netlink.h:789
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff818de1c5)
Location: include/net/netlink.h:789
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914f17)
Location: include/net/netlink.h:789
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffffffff81941b4a)
Location: include/net/netlink.h:789
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819ba0b5)
Location: include/net/netlink.h:789
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff819c1a5d)
Location: include/net/netlink.h:789
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819cada2)
Location: include/net/netlink.h:789
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/rtnetlink.c (ffffffff818d0690)
Location: include/net/netlink.h:932
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/lwtunnel.c (ffffffff818f0e20)
Location: include/net/netlink.h:932
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8190ab85)
Location: include/net/netlink.h:932
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819436c7)
Location: include/net/netlink.h:932
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffffffff819713aa)
Location: include/net/netlink.h:932
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f1a05)
Location: include/net/netlink.h:932
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff819f8fbd)
Location: include/net/netlink.h:932
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a03861)
Location: include/net/netlink.h:932
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/rtnetlink.c (ffffffff8191d523)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/lwtunnel.c (ffffffff819427c4)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/core/devlink.c (ffffffff819500bc)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/netlink/genetlink.c (ffffffff8196bf78)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7c88)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/nexthop.c (ffffffff819d384d)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff819dab31)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a610cf)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81a68512)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a72ac8)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/rtnetlink.c (ffffffff8194fb71)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffff81975d35)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/lwtunnel.c (ffffffff819776ed)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/core/devlink.c (ffffffff8198672c)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/netlink/genetlink.c (ffffffff819a2928)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819ded18)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/nexthop.c (ffffffff81a0a3bd)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81a119dd)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a97cff)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81a9ee72)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa9288)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/rtnetlink.c (ffffffff81a2138f)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffff81a4a8d4)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81a4c4c4)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/core/devlink.c (ffffffff81a5ca34)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
```
```
In net/netlink/genetlink.c (ffffffff81a7c67f)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/cabletest.c (ffffffff81a8d0c8)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
```
```
In net/ipv4/tcp.c (ffffffff81aaf438)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acbd3a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/nexthop.c (ffffffff81afae8c)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81b03000)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b93265)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/dcb/dcbnl.c (ffffffff81b9b0f1)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba49af)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/mptcp/diag.c (ffffffff81bb2bf2)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb2fc6)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/core/rtnetlink.c (ffffffff81a1f91b)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffff81a50514)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81a52106)
Location: include/net/netlink.h:1255
Inline: True
```
```
In net/core/devlink.c (ffffffff81a63e24)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
```
```
In net/netlink/genetlink.c (ffffffff81a85776)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/cabletest.c (ffffffff81a96808)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
```
```
In net/ipv4/tcp.c (ffffffff81aba4ed)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7cfa)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/nexthop.c (ffffffff81b0855c)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81b10150)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba2eb5)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/dcb/dcbnl.c (ffffffff81baae15)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb3e64)
Location: include/net/netlink.h:1255
Inline: True
```
```
In net/mptcp/diag.c (ffffffff81bc7027)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7456)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/core/rtnetlink.c (ffffffff81a069e3)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffff81a35434)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81a37a3c)
Location: include/net/netlink.h:1255
Inline: True
```
```
In net/core/devlink.c (ffffffff81a47e54)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
```
```
In net/netlink/genetlink.c (ffffffff81a6e836)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/cabletest.c (ffffffff81a802e8)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
```
```
In net/ipv4/tcp.c (ffffffff81aa5772)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2e76)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/nexthop.c (ffffffff81af6e7e)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81afdd5e)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b91fd5)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/dcb/dcbnl.c (ffffffff81b99fa8)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba2e4b)
Location: include/net/netlink.h:1255
Inline: True
```
```
In net/mptcp/diag.c (ffffffff81bb7d56)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb812e)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/core/rtnetlink.c (ffffffff81ab8e31)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffff81aeb004)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81aed867)
Location: include/net/netlink.h:1255
Inline: True
```
```
In net/core/devlink.c (ffffffff81afed50)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
```
```
In net/netlink/genetlink.c (ffffffff81b27eb6)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/cabletest.c (ffffffff81b3a0b8)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
```
```
In net/ipv4/tcp.c (ffffffff81b61ac2)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b80a33)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/nexthop.c (ffffffff81bb67e6)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81bbefc2)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv6/ioam6.c (ffffffff81c393dd)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5e775)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/dcb/dcbnl.c (ffffffff81c67618)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c7099b)
Location: include/net/netlink.h:1255
Inline: True
```
```
In net/mptcp/diag.c (ffffffff81c872a6)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81c877ae)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/core/rtnetlink.c (ffffffff81c3208e)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffff81c6d854)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81c701d5)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/core/devlink.c (ffffffff81c82675)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
```
```
In net/netlink/genetlink.c (ffffffff81cafc92)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/cabletest.c (ffffffff81cc5fa0)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
```
```
In net/ipv4/tcp.c (ffffffff81cf051b)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d10e34)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/nexthop.c (ffffffff81d4a43d)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81d53d36)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv6/ioam6.c (ffffffff81dd6c90)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00995)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/dcb/dcbnl.c (ffffffff81e0ac07)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e145ab)
Location: include/net/netlink.h:1255
Inline: True
```
```
In net/mptcp/diag.c (ffffffff81e2dae8)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2dfbe)
Location: include/net/netlink.h:1255
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/core/rtnetlink.c (ffffffff81de545e)
Location: include/net/netlink.h:1304
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffff81e254b4)
Location: include/net/netlink.h:1304
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81e28145)
Location: include/net/netlink.h:1304
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/core/devlink.c (ffffffff81e3ac45)
Location: include/net/netlink.h:1304
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
```
```
In net/netlink/genetlink.c (ffffffff81e6d9c2)
Location: include/net/netlink.h:1304
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/cabletest.c (ffffffff81e85580)
Location: include/net/netlink.h:1304
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
```
```
In net/ipv4/tcp.c (ffffffff81eb384b)
Location: include/net/netlink.h:1304
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed6bb4)
Location: include/net/netlink.h:1304
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/nexthop.c (ffffffff81f13add)
Location: include/net/netlink.h:1304
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81f1df0b)
Location: include/net/netlink.h:1304
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv6/ioam6.c (ffffffff81fa8630)
Location: include/net/netlink.h:1304
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd57e5)
Location: include/net/netlink.h:1304
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/dcb/dcbnl.c (ffffffff81fe04a7)
Location: include/net/netlink.h:1304
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81feb3b4)
Location: include/net/netlink.h:1304
Inline: True
```
```
In net/mptcp/diag.c (ffffffff82006078)
Location: include/net/netlink.h:1304
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff8200af25)
Location: include/net/netlink.h:1304
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/core/rtnetlink.c (ffffffff81e56e7a)
Location: include/net/netlink.h:1305
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffff81e9a9f4)
Location: include/net/netlink.h:1305
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81e9d759)
Location: include/net/netlink.h:1305
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/netlink/genetlink.c (ffffffff81ec9ad2)
Location: include/net/netlink.h:1305
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/cabletest.c (ffffffff81ee1eb0)
Location: include/net/netlink.h:1305
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
```
```
In net/ethtool/plca.c (ffffffff81ee630a)
Location: include/net/netlink.h:1305
Inline: True
Inline callers:
  - net/ethtool/plca.c:plca_get_cfg_fill_reply
```
```
In net/ipv4/tcp.c (ffffffff81f11f6b)
Location: include/net/netlink.h:1305
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f35b55)
Location: include/net/netlink.h:1305
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/nexthop.c (ffffffff81f737ad)
Location: include/net/netlink.h:1305
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81f7d9fb)
Location: include/net/netlink.h:1305
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv6/ioam6.c (ffffffff82008fc0)
Location: include/net/netlink.h:1305
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/devlink/leftover.c (ffffffff8203aae5)
Location: include/net/netlink.h:1305
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_param_value_fill_one
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_attrs_put
  - net/devlink/leftover.c:devlink_nl_port_attrs_put
  - net/devlink/leftover.c:devlink_nl_port_attrs_put
  - net/devlink/leftover.c:devlink_nl_port_attrs_put
  - net/devlink/leftover.c:devlink_nl_port_attrs_put
```
```
In net/devlink/dev.c (ffffffff82043ba9)
Location: include/net/netlink.h:1305
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82051485)
Location: include/net/netlink.h:1305
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/dcb/dcbnl.c (ffffffff8205c857)
Location: include/net/netlink.h:1305
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82067660)
Location: include/net/netlink.h:1305
Inline: True
```
```
In net/mptcp/diag.c (ffffffff820823f1)
Location: include/net/netlink.h:1305
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff82087355)
Location: include/net/netlink.h:1305
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/core/rtnetlink.c (ffffffff81f161d7)
Location: include/net/netlink.h:1349
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffff81f5d134)
Location: include/net/netlink.h:1349
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81f5fed9)
Location: include/net/netlink.h:1349
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/netlink/genetlink.c (ffffffff81f8cba2)
Location: include/net/netlink.h:1349
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/cabletest.c (ffffffff81fa5d40)
Location: include/net/netlink.h:1349
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
```
```
In net/ethtool/plca.c (ffffffff81faa0ba)
Location: include/net/netlink.h:1349
Inline: True
Inline callers:
  - net/ethtool/plca.c:plca_get_cfg_fill_reply
```
```
In net/ipv4/tcp.c (ffffffff81fd620b)
Location: include/net/netlink.h:1349
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffbc05)
Location: include/net/netlink.h:1349
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/nexthop.c (ffffffff82039f9d)
Location: include/net/netlink.h:1349
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff8204423b)
Location: include/net/netlink.h:1349
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv6/ioam6.c (ffffffff820d7f30)
Location: include/net/netlink.h:1349
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/devlink/dev.c (ffffffff82102d89)
Location: include/net/netlink.h:1349
Inline: True
```
```
In net/devlink/port.c (ffffffff82106898)
Location: include/net/netlink.h:1349
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_fill
  - net/devlink/port.c:devlink_nl_port_fill
  - net/devlink/port.c:devlink_nl_port_attrs_put
  - net/devlink/port.c:devlink_nl_port_attrs_put
  - net/devlink/port.c:devlink_nl_port_attrs_put
  - net/devlink/port.c:devlink_nl_port_attrs_put
  - net/devlink/port.c:devlink_nl_port_attrs_put
```
```
In net/devlink/sb.c (ffffffff82108841)
Location: include/net/netlink.h:1349
Inline: True
```
```
In net/devlink/param.c (ffffffff8210dbb5)
Location: include/net/netlink.h:1349
Inline: True
Inline callers:
  - net/devlink/param.c:devlink_nl_param_value_fill_one
```
```
In net/devlink/rate.c (ffffffff8211887c)
Location: include/net/netlink.h:1349
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82123c55)
Location: include/net/netlink.h:1349
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/dcb/dcbnl.c (ffffffff8212e69e)
Location: include/net/netlink.h:1349
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213a8e2)
Location: include/net/netlink.h:1349
Inline: True
```
```
In net/mptcp/diag.c (ffffffff82157a3a)
Location: include/net/netlink.h:1349
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff8215cba5)
Location: include/net/netlink.h:1349
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/core/rtnetlink.c (ffff800010bf183c)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffff800010c1c1d8)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/lwtunnel.c (ffff800010c1e228)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/core/devlink.c (ffff800010c2eb9c)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/netlink/genetlink.c (ffff800010c51bec)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffff800010c91ecc)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/nexthop.c (ffff800010cc38b8)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffff800010cca0b0)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d672c0)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/dcb/dcbnl.c (ffff800010d6f874)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7ccf8)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/rtnetlink.c (c0d0a020)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (c0d34010)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/lwtunnel.c (c0d35d84)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/core/devlink.c (c0d45c10)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/netlink/genetlink.c (c0d612dc)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (c0da0b94)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/nexthop.c (c0dcf08c)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (c0dd606c)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/netlabel/netlabel_mgmt.c (c0e658cc)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/dcb/dcbnl.c (c0e6d9b4)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (c0e77b58)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/rtnetlink.c (c000000000cd63d4)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (c000000000d0cf3c)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/lwtunnel.c (c000000000d0f9c4)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/core/devlink.c (c000000000d26990)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/netlink/genetlink.c (c000000000d506b4)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (c000000000da25b0)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/nexthop.c (c000000000ddf5e0)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (c000000000de9590)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea300c)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/dcb/dcbnl.c (c000000000eae894)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebc6e8)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/rtnetlink.c (ffffffe00077357a)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffe000796284)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/lwtunnel.c (ffffffe000797bda)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/core/devlink.c (ffffffe0007a535a)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/netlink/genetlink.c (ffffffe0007bcce8)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1ef0)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/nexthop.c (ffffffe000818afa)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffe00081f568)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089aa98)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffe0008a1296)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008aaa3c)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/rtnetlink.c (ffffffff818efb41)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffff81915d05)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/lwtunnel.c (ffffffff8191755d)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/core/devlink.c (ffffffff8192659c)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/netlink/genetlink.c (ffffffff81942798)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197eb88)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/nexthop.c (ffffffff819aa15d)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff819b1339)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a3708f)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81a3e202)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a48618)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/rtnetlink.c (ffffffff818a9981)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffff818cfab5)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/lwtunnel.c (ffffffff818d130d)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/core/devlink.c (ffffffff818e034c)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/netlink/genetlink.c (ffffffff818fc288)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938648)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/nexthop.c (ffffffff81963c1d)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff8196d969)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f3caf)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff819fadf2)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a05208)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/rtnetlink.c (ffffffff81940b71)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffff81966d35)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/lwtunnel.c (ffffffff819686ed)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/core/devlink.c (ffffffff8197772c)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/netlink/genetlink.c (ffffffff81993928)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9358)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/nexthop.c (ffffffff81a149fd)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81a1bbd9)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa2f3f)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81aaa0b2)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab44c8)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/rtnetlink.c (ffffffff81962481)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffff81988fc5)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/lwtunnel.c (ffffffff8198aaa2)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/core/devlink.c (ffffffff81999c1c)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/netlink/genetlink.c (ffffffff819b6418)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f30b8)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/nexthop.c (ffffffff81a1f40d)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81a26aed)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aaf2af)
Location: include/net/netlink.h:1190
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81ab6422)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac0868)
Location: include/net/netlink.h:1190
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
</details>
</li>
</ul>

## Differences
