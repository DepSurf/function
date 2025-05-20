# Function: <code>genlmsg_cancel</code>

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
In net/netlink/genetlink.c (ffffffff8174fc10)
Location: include/net/genetlink.h:277
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:genl_ctrl_event
```
```
In net/ipv4/tcp_metrics.c (ffffffff817818f9)
Location: include/net/genetlink.h:277
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180db6e)
Location: include/net/genetlink.h:277
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180e876)
Location: include/net/genetlink.h:277
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8180fd62)
Location: include/net/genetlink.h:277
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
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
In net/netlink/genetlink.c (ffffffff817bc55d)
Location: include/net/genetlink.h:275
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff817eedb9)
Location: include/net/genetlink.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8188004f)
Location: include/net/genetlink.h:275
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81880f00)
Location: include/net/genetlink.h:275
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81882430)
Location: include/net/genetlink.h:275
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81883430)
Location: include/net/genetlink.h:275
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
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
In net/netlink/genetlink.c (ffffffff817ebe6d)
Location: include/net/genetlink.h:225
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f7c9)
Location: include/net/genetlink.h:225
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81899951)
Location: include/net/genetlink.h:225
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b48ff)
Location: include/net/genetlink.h:225
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b57b0)
Location: include/net/genetlink.h:225
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b6ce0)
Location: include/net/genetlink.h:225
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b7cd0)
Location: include/net/genetlink.h:225
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
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
In net/netlink/genetlink.c (ffffffff8180bdd1)
Location: include/net/genetlink.h:238
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff8184019b)
Location: include/net/genetlink.h:238
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff818bfb5e)
Location: include/net/genetlink.h:238
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818db282)
Location: include/net/genetlink.h:238
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dc09f)
Location: include/net/genetlink.h:238
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818dd5c4)
Location: include/net/genetlink.h:238
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818de5c4)
Location: include/net/genetlink.h:238
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
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
In net/netlink/genetlink.c (ffffffff8188ad61)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf53b)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81942c2e)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81960e62)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81961c82)
Location: include/net/genetlink.h:234
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819631b4)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819641c4)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
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
In net/netlink/genetlink.c (ffffffff818de38b)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81915131)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff8199bb44)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819ba67a)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bb45f)
Location: include/net/genetlink.h:234
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bca04)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bda64)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819cb17a)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In net/netlink/genetlink.c (ffffffff8190ad4b)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81943aee)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff819d2714)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f1eba)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f26df)
Location: include/net/genetlink.h:234
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f3c54)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4c04)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a03c4c)
Location: include/net/genetlink.h:234
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In net/core/devlink.c (ffffffff81951a72)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff8196c144)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a848f)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81a41553)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a611b5)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a61a60)
Location: include/net/genetlink.h:260
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a630aa)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a640ba)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a72ef2)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In net/core/drop_monitor.c (ffffffff819765d0)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff81983b60)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff819a2af4)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819df15f)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81a781d3)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a97dda)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a985ed)
Location: include/net/genetlink.h:260
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a99c65)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9ac45)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa96d2)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In net/core/drop_monitor.c (ffffffff81a4b342)
Location: include/net/genetlink.h:266
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff81a5f73d)
Location: include/net/genetlink.h:266
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81a7c6f0)
Location: include/net/genetlink.h:266
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81a85b87)
Location: include/net/genetlink.h:266
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acbf6f)
Location: include/net/genetlink.h:266
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81b721a3)
Location: include/net/genetlink.h:266
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b936fa)
Location: include/net/genetlink.h:266
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93d19)
Location: include/net/genetlink.h:266
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b954b5)
Location: include/net/genetlink.h:266
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b96415)
Location: include/net/genetlink.h:266
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5ac2)
Location: include/net/genetlink.h:266
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb393c)
Location: include/net/genetlink.h:266
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
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
In drivers/thermal/thermal_netlink.c (ffffffff8195f791)
Location: include/net/genetlink.h:288
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/drop_monitor.c (ffffffff81a50f72)
Location: include/net/genetlink.h:288
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff81a67f2d)
Location: include/net/genetlink.h:288
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81a85acb)
Location: include/net/genetlink.h:288
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81a8f517)
Location: include/net/genetlink.h:288
Inline: True
```
```
In net/ethtool/tunnels.c (ffffffff81a978af)
Location: include/net/genetlink.h:288
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7f39)
Location: include/net/genetlink.h:288
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81b80f03)
Location: include/net/genetlink.h:288
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba334a)
Location: include/net/genetlink.h:288
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba395f)
Location: include/net/genetlink.h:288
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba5125)
Location: include/net/genetlink.h:288
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba6085)
Location: include/net/genetlink.h:288
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb4f98)
Location: include/net/genetlink.h:288
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7bd1)
Location: include/net/genetlink.h:288
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
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
In drivers/thermal/thermal_netlink.c (ffffffff81942cf5)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/drop_monitor.c (ffffffff81a35efc)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/devlink.c (ffffffff81a42f55)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81a6f46e)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81a78d3d)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81a8130e)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac30a9)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81b6fb03)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b9246a)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b92a7f)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b9426a)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b951fa)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba3f74)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb9327)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
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
In drivers/thermal/thermal_netlink.c (ffffffff819e77c6)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/drop_monitor.c (ffffffff81aebaf2)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/devlink.c (ffffffff81af93c5)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81b2820e)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81b32f0d)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81b3b05e)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b80c92)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81c37c53)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff81c3945c)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5ec0a)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f21f)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60a0a)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61a2a)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c718d4)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81c88797)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
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
In drivers/thermal/thermal_netlink.c (ffffffff81b4d090)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/drop_monitor.c (ffffffff81c6e433)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/devlink.c (ffffffff81c7c2d5)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81cb11fe)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81cbeac7)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81cc6fc5)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d110a4)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81dd581c)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff81dd6d19)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00e4c)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e016bd)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e02f8f)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e040af)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e15467)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2f2d0)
Location: include/net/genetlink.h:289
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
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
In drivers/thermal/thermal_netlink.c (ffffffff81ce4d90)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/drop_monitor.c (ffffffff81e260bc)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/devlink.c (ffffffff81e40ba5)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_selftests_fill
  - net/core/devlink.c:devlink_nl_selftests_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81e6f1d0)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81e7d5e7)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81e86615)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed6e34)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81fa6fac)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff81fa86b9)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd5cac)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd651d)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd7ecf)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd906f)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81fec3c7)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff820079ca)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
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
In drivers/thermal/thermal_netlink.c (ffffffff81d4d360)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/netdev-genl.c (ffffffff81e7ced6)
Location: include/net/genetlink.h:370
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81e9b65c)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/netlink/genetlink.c (ffffffff81ecb2e0)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81ed9ba7)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81ee2ff7)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f35ddf)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff8200780c)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff82009049)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/devlink/leftover.c (ffffffff82037769)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_region_notify_build
  - net/devlink/leftover.c:devlink_nl_region_notify_build
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_fill
```
```
In net/devlink/dev.c (ffffffff82045ac8)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_nl_fill
```
```
In net/devlink/health.c (ffffffff8204842b)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8205196c)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff820521dd)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053bbf)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82054d3f)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82068667)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff82083d0b)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
```
```
In net/handshake/netlink.c (ffffffff8209259d)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
```
In net/handshake/tlshd.c (ffffffff82094071)
Location: include/net/genetlink.h:370
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_accept
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
In drivers/thermal/thermal_netlink.c (ffffffff81e03e50)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81ebb9b6)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_dumpit
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_dumpit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_dumpit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_dumpit
  - drivers/dpll/dpll_netlink.c:dpll_pin_event_send
  - drivers/dpll/dpll_netlink.c:dpll_pin_event_send
  - drivers/dpll/dpll_netlink.c:dpll_device_event_send
  - drivers/dpll/dpll_netlink.c:dpll_device_event_send
```
```
In net/core/netdev-genl.c (ffffffff81f3d2aa)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_queue_fill_one
  - net/core/netdev-genl.c:netdev_nl_queue_fill_one
  - net/core/netdev-genl.c:netdev_nl_napi_fill_one
  - net/core/netdev-genl.c:netdev_nl_napi_fill_one
  - net/core/netdev-genl.c:netdev_nl_dev_fill
  - net/core/netdev-genl.c:netdev_nl_dev_fill
  - net/core/netdev-genl.c:netdev_nl_dev_fill
  - net/core/netdev-genl.c:netdev_nl_dev_fill
```
```
In net/core/page_pool_user.c (ffffffff81f453a0)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_nl_fill
  - net/core/page_pool_user.c:page_pool_nl_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
```
```
In net/core/drop_monitor.c (ffffffff81f5ddcc)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/netlink/genetlink.c (ffffffff81f8e7d0)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81f9d9e3)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81fa6e24)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffbe8f)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff820d669c)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff820d7fb9)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/devlink/dev.c (ffffffff8210540b)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_nl_fill
```
```
In net/devlink/port.c (ffffffff82106a83)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_fill
```
```
In net/devlink/sb.c (ffffffff82108993)
Location: include/net/genetlink.h:448
Inline: True
```
```
In net/devlink/param.c (ffffffff8210e162)
Location: include/net/genetlink.h:448
Inline: True
```
```
In net/devlink/region.c (ffffffff82111690)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_notify_build
  - net/devlink/region.c:devlink_nl_region_notify_build
```
```
In net/devlink/health.c (ffffffff82114597)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/devlink/trap.c (ffffffff82114b99)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
```
```
In net/devlink/rate.c (ffffffff82118a07)
Location: include/net/genetlink.h:448
Inline: True
```
```
In net/devlink/linecard.c (ffffffff82119a6d)
Location: include/net/genetlink.h:448
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8212413c)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8212495d)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8212639f)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8212761f)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213b8e7)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff8215c06b)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_dumpit
```
```
In net/handshake/netlink.c (ffffffff82168e83)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
```
In net/handshake/tlshd.c (ffffffff8216a991)
Location: include/net/genetlink.h:448
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_accept
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
In net/core/drop_monitor.c (ffff800010c1caa0)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffff800010c2c198)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffff800010c51dcc)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffff800010c924cc)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffff800010d41760)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d673b4)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d67da0)
Location: include/net/genetlink.h:260
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d696ec)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6a834)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d148)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In net/core/drop_monitor.c (c0d34a30)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (c0d42760)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (c0d61484)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (c0e44154)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/netlabel/netlabel_mgmt.c (c0e65bc4)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_protocols_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (c0e66610)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e67cd8)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (c0e68db8)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (c0e77f24)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In net/core/drop_monitor.c (c000000000d0dae0)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (c000000000d22ce0)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (c000000000d508fc)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (c000000000da2b90)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (c000000000e76010)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea3140)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea46d0)
Location: include/net/genetlink.h:260
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea6528)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea7ba8)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebcd38)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In net/core/drop_monitor.c (ffffffe000796978)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffe0007a377a)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffe0007bce42)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f2290)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffe00087ce24)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089ac24)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089b256)
Location: include/net/genetlink.h:260
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089c644)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d3f4)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008aad3a)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In net/core/drop_monitor.c (ffffffff819165a0)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff819239d0)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81942964)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197efcf)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81a17863)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a3716a)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a3797d)
Location: include/net/genetlink.h:260
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a38ff5)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a39fd5)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a48a62)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In net/core/drop_monitor.c (ffffffff818d0350)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff818dd780)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff818fc454)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938a8f)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff819d4623)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f3d8a)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f459d)
Location: include/net/genetlink.h:260
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f5c15)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6bf5)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a05652)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In net/core/drop_monitor.c (ffffffff819675d0)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff81974b60)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81993af4)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e979f)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81a822e3)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa301a)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa382d)
Location: include/net/genetlink.h:260
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa4ea5)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa5e85)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4912)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In net/core/drop_monitor.c (ffffffff81989860)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff81997050)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff819b65ee)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f352f)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81a8ebf3)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aaf38a)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aafc4d)
Location: include/net/genetlink.h:260
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab1225)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab2225)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac0cb2)
Location: include/net/genetlink.h:260
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
</details>
</li>
</ul>

## Differences
