# Function: <code>genlmsg_end</code>

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
In kernel/taskstats.c (ffffffff8113e1a6)
Location: include/net/genetlink.h:267
Inline: True
Inline callers:
  - kernel/taskstats.c:send_reply
  - kernel/taskstats.c:taskstats_exit
```
```
In fs/quota/netlink.c (ffffffff8127685a)
Location: include/net/genetlink.h:267
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81489801)
Location: include/net/genetlink.h:267
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8168591e)
Location: include/net/genetlink.h:267
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/netlink/genetlink.c (ffffffff8174fd0e)
Location: include/net/genetlink.h:267
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:genl_ctrl_event
```
```
In net/ipv4/tcp_metrics.c (ffffffff8178174c)
Location: include/net/genetlink.h:267
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180d47f)
Location: include/net/genetlink.h:267
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180e5e6)
Location: include/net/genetlink.h:267
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8180fdce)
Location: include/net/genetlink.h:267
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
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
In kernel/taskstats.c (ffffffff811473bf)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff812a30a6)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff814d85f7)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff816e6e02)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/netlink/genetlink.c (ffffffff817bc47b)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff817eec09)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8187f870)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81880c67)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8188249d)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8188349d)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
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
In kernel/taskstats.c (ffffffff8115125f)
Location: include/net/genetlink.h:215
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff812b8a86)
Location: include/net/genetlink.h:215
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff814facdf)
Location: include/net/genetlink.h:215
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff81716252)
Location: include/net/genetlink.h:215
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/netlink/genetlink.c (ffffffff817ebd8b)
Location: include/net/genetlink.h:215
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f619)
Location: include/net/genetlink.h:215
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81899913)
Location: include/net/genetlink.h:215
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b4120)
Location: include/net/genetlink.h:215
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b5517)
Location: include/net/genetlink.h:215
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b6d4d)
Location: include/net/genetlink.h:215
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b7d3d)
Location: include/net/genetlink.h:215
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
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
In kernel/taskstats.c (ffffffff811538dc)
Location: include/net/genetlink.h:228
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff812c5e52)
Location: include/net/genetlink.h:228
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8150a219)
Location: include/net/genetlink.h:228
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8172e052)
Location: include/net/genetlink.h:228
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/netlink/genetlink.c (ffffffff8180bced)
Location: include/net/genetlink.h:228
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81840323)
Location: include/net/genetlink.h:228
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff818bfb23)
Location: include/net/genetlink.h:228
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818daad0)
Location: include/net/genetlink.h:228
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dbe6b)
Location: include/net/genetlink.h:228
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818dd62c)
Location: include/net/genetlink.h:228
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818de62c)
Location: include/net/genetlink.h:228
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
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
In kernel/taskstats.c (ffffffff811600dc)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff812e9d02)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8154c719)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8179f682)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/netlink/genetlink.c (ffffffff8188ac7d)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf6c3)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81942bf3)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819606b0)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81961a4b)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8196321c)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8196422c)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
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
In kernel/taskstats.c (ffffffff8116f01c)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff81316c06)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81582e5d)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff817e6c62)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/netlink/genetlink.c (ffffffff818de2cb)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819152ae)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff8199bb2a)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819b9e70)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bb1bb)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bca6c)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bdacc)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819cb101)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (ffffffff8117cb1c)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff8132dbb6)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8159af8d)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff81813012)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/netlink/genetlink.c (ffffffff8190ac8b)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819438ce)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff819d26fa)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f1140)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f242b)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f3cbc)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4c6c)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a04159)
Location: include/net/genetlink.h:224
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (ffffffff811899cd)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff813558f2)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815cc608)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff818550b0)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/devlink.c (ffffffff81951ac7)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff8196c076)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7ea1)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81a414f3)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a603fc)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a6177a)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a6311b)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a6412b)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a733f9)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (ffffffff81195910)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff8136dc32)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815ed888)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff81886b10)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/drop_monitor.c (ffffffff81976566)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81983b0e)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff819a2a26)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819def34)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81a78173)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a9702c)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a9834a)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a99ccd)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9acad)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa9be9)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (ffffffff811aa96f)
Location: include/net/genetlink.h:256
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:send_cpu_listeners
```
```
In fs/quota/netlink.c (ffffffff813b5762)
Location: include/net/genetlink.h:256
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81699408)
Location: include/net/genetlink.h:256
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In net/core/drop_monitor.c (ffffffff81a4b2ff)
Location: include/net/genetlink.h:256
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81a5f705)
Location: include/net/genetlink.h:256
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
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81a7c76a)
Location: include/net/genetlink.h:256
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81a867f7)
Location: include/net/genetlink.h:256
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81a89f86)
Location: include/net/genetlink.h:256
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a8cbb1)
Location: include/net/genetlink.h:256
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acc520)
Location: include/net/genetlink.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81b72152)
Location: include/net/genetlink.h:256
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b928ac)
Location: include/net/genetlink.h:256
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93e37)
Location: include/net/genetlink.h:256
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b9551d)
Location: include/net/genetlink.h:256
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b9647d)
Location: include/net/genetlink.h:256
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5de9)
Location: include/net/genetlink.h:256
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb368b)
Location: include/net/genetlink.h:256
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
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
In kernel/taskstats.c (ffffffff811a7f1f)
Location: include/net/genetlink.h:278
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:send_cpu_listeners
```
```
In fs/quota/netlink.c (ffffffff813c6f92)
Location: include/net/genetlink.h:278
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff816b6525)
Location: include/net/genetlink.h:278
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff8195f73a)
Location: include/net/genetlink.h:278
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/drop_monitor.c (ffffffff81a50f2f)
Location: include/net/genetlink.h:278
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81a67ef5)
Location: include/net/genetlink.h:278
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
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81a85a66)
Location: include/net/genetlink.h:278
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81a90107)
Location: include/net/genetlink.h:278
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81a93856)
Location: include/net/genetlink.h:278
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a962c8)
Location: include/net/genetlink.h:278
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81a97790)
Location: include/net/genetlink.h:278
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad84ed)
Location: include/net/genetlink.h:278
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81b80eb2)
Location: include/net/genetlink.h:278
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba24fc)
Location: include/net/genetlink.h:278
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba3a9f)
Location: include/net/genetlink.h:278
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba518d)
Location: include/net/genetlink.h:278
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba60ed)
Location: include/net/genetlink.h:278
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb52c9)
Location: include/net/genetlink.h:278
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7d70)
Location: include/net/genetlink.h:278
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
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
In kernel/taskstats.c (ffffffff811a8ca2)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In fs/quota/netlink.c (ffffffff813ce022)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff816985d5)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81942c9a)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/drop_monitor.c (ffffffff81a35e8b)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81a42fec)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81a6f40a)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81a7981e)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81a7d276)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a7fd48)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81a811f0)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac3288)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81b6faa3)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b915dc)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b92bbe)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b942d3)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b95263)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba42c9)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bbb9d2)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
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
In kernel/taskstats.c (ffffffff811d27ee)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In fs/quota/netlink.c (ffffffff8141f352)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8170e355)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff819e7769)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/drop_monitor.c (ffffffff81aeba7d)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81af945c)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81b281aa)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81b33ba7)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81b37456)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81b39b18)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81b3af40)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b811e3)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81c37bf3)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ioam6.c (ffffffff81c393ef)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5dd7c)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f35e)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60a73)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61a93)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c71e59)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8b612)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
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
In kernel/taskstats.c (ffffffff8120708c)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In fs/quota/netlink.c (ffffffff81497196)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8183cd26)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81b4d01d)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/drop_monitor.c (ffffffff81c6e3af)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81c7c365)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81cb119a)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81cbf2c8)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81cc2e4e)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81cc5978)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81cc6ee0)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d1156c)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81dd57ac)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ioam6.c (ffffffff81dd6ca2)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00057)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e0172c)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e02f75)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e04095)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e159dd)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81e32bc2)
Location: include/net/genetlink.h:279
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
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
In kernel/taskstats.c (ffffffff8124f3fc)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In fs/quota/netlink.c (ffffffff8152b1f1)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81972776)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81ce4d1d)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/drop_monitor.c (ffffffff81e26038)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81e40c35)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_selftests_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81e6f174)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81e7de68)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81e8213e)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81e84f08)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81e86530)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed731c)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81fa6f3c)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ioam6.c (ffffffff81fa8642)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd4e77)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd658c)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd7eb5)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd9055)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81fec97d)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff8200b622)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
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
In kernel/taskstats.c (ffffffff812667ac)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In fs/quota/netlink.c (ffffffff81563581)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff819b8e46)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81d4d2ed)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/netdev-genl.c (ffffffff81e7ce93)
Location: include/net/genetlink.h:360
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81e9b5d8)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/netlink/genetlink.c (ffffffff81ecb284)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81eda428)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81ede79e)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81ee1838)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81ee2f12)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f363b2)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff8200779c)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ioam6.c (ffffffff82008fd2)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/devlink/leftover.c (ffffffff820377f9)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_region_notify_build
  - net/devlink/leftover.c:devlink_dpipe_entry_ctx_close
  - net/devlink/leftover.c:devlink_nl_port_fill
```
```
In net/devlink/dev.c (ffffffff820459e5)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_fill
```
```
In net/devlink/health.c (ffffffff8204845a)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82050b17)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8205224c)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053ba5)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82054d25)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82068c1d)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff82087ab2)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
```
In net/handshake/netlink.c (ffffffff82092531)
Location: include/net/genetlink.h:360
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
```
In net/handshake/tlshd.c (ffffffff82094010)
Location: include/net/genetlink.h:360
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
In kernel/taskstats.c (ffffffff8128069c)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In fs/quota/netlink.c (ffffffff81599c71)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81a03476)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/regulator/event.c (ffffffff81ae2613)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - drivers/regulator/event.c:reg_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81e03ddd)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81ebb8eb)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_dumpit
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_id_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_dumpit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_id_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_pin_event_send
  - drivers/dpll/dpll_netlink.c:dpll_device_event_send
```
```
In net/core/netdev-genl.c (ffffffff81f3d214)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_queue_fill_one
  - net/core/netdev-genl.c:netdev_nl_napi_fill_one
  - net/core/netdev-genl.c:netdev_nl_dev_fill
```
```
In net/core/page_pool_user.c (ffffffff81f45330)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_nl_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
```
```
In net/core/drop_monitor.c (ffffffff81f5dd48)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/netlink/genetlink.c (ffffffff81f8e774)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81f9e205)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81fa25ce)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81fa56c8)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81fa6d76)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffc652)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff820d662c)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ioam6.c (ffffffff820d7f42)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/devlink/dev.c (ffffffff82105328)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_fill
```
```
In net/devlink/port.c (ffffffff82106994)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_fill
```
```
In net/devlink/sb.c (ffffffff8210892b)
Location: include/net/genetlink.h:438
Inline: True
```
```
In net/devlink/dpipe.c (ffffffff8210a4ac)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devlink_dpipe_entry_ctx_close
```
```
In net/devlink/resource.c (ffffffff8210c8ca)
Location: include/net/genetlink.h:438
Inline: True
```
```
In net/devlink/param.c (ffffffff8210e0e6)
Location: include/net/genetlink.h:438
Inline: True
```
```
In net/devlink/region.c (ffffffff821114f7)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_notify_build
```
```
In net/devlink/health.c (ffffffff8211455f)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/devlink/trap.c (ffffffff82114c29)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
```
```
In net/devlink/rate.c (ffffffff8211898f)
Location: include/net/genetlink.h:438
Inline: True
```
```
In net/devlink/linecard.c (ffffffff82119ace)
Location: include/net/genetlink.h:438
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff821231c7)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82124a39)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82126385)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82127605)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213be9d)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff8215d30a)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_limits_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_dumpit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_doit
```
```
In net/handshake/netlink.c (ffffffff82168e11)
Location: include/net/genetlink.h:438
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
```
In net/handshake/tlshd.c (ffffffff8216a930)
Location: include/net/genetlink.h:438
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
In kernel/taskstats.c (ffff80001020db8c)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffff800010437688)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffff800010778d2c)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffff800010ad391c)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/drop_monitor.c (ffff800010c1ca2c)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffff800010c2c13c)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffff800010c51cdc)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffff800010c92128)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffff800010d416f8)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d66600)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d67a14)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d6975c)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6a8a4)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d8a8)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (c044c578)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (c05ff2ec)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/thermal/thermal_core.c (c0bb44dc)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/drop_monitor.c (c0d34974)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (c0d42730)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (c0d613b8)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (c0da0e3c)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (c0e440fc)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (c0e64e30)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_protocols_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (c0e66588)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e67d44)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (c0e68e24)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (c0e78410)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (c00000000028bc34)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (c000000000549ac8)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/thermal/thermal_core.c (c000000000bb8c20)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/drop_monitor.c (c000000000d0da30)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (c000000000d22c64)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (c000000000d507dc)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (c000000000da290c)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (c000000000e75f84)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea27a0)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea4314)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea65bc)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea7c3c)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebd390)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (ffffffe00016ea98)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffe0002d18bc)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/thermal/thermal_core.c (ffffffe0006cff18)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/drop_monitor.c (ffffffe00079691c)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffe0007a3740)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffe0007bcda0)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f20d0)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffe00087cdcc)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a0de)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089b020)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089c690)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d440)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008ab0f2)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (ffffffff8118df30)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff81366212)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815dc9d8)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8182c990)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/drop_monitor.c (ffffffff81916536)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff8192397e)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81942896)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197eda4)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81a17803)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a363bc)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a376da)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a3905d)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a3a03d)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a48f79)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (ffffffff81181040)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff81356eb2)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815c8018)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff817f4020)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/drop_monitor.c (ffffffff818d02e6)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff818dd72e)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff818fc386)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938864)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff819d45c3)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f2fdc)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f42fa)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f5c7d)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6c5d)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a05b69)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (ffffffff8118bd00)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff81363ce2)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815e1b68)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8187bfc0)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/drop_monitor.c (ffffffff81967566)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81974b0e)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81993a26)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9574)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81a82283)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa226c)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa358a)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa4f0d)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa5eed)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4e29)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (ffffffff8119967d)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff81377392)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815fba28)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff818979f0)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/drop_monitor.c (ffffffff819897f6)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81996ffe)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff819b6516)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f32e4)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv6/seg6.c (ffffffff81a8eb93)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aae5dc)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aaf9aa)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab128d)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab228d)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac11c9)
Location: include/net/genetlink.h:250
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
</details>
</li>
</ul>

## Differences
