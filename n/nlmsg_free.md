# Function: <code>nlmsg_free</code>

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
In kernel/taskstats.c (ffffffff8113e28f)
Location: include/net/netlink.h:545
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
```
```
In drivers/acpi/event.c (ffffffff8148978e)
Location: include/net/netlink.h:545
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff816859c7)
Location: include/net/netlink.h:545
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff8170ff78)
Location: include/net/netlink.h:545
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/netlink/genetlink.c (ffffffff81750064)
Location: include/net/netlink.h:545
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:genl_ctrl_event
```
```
In net/ipv4/tcp_metrics.c (ffffffff817817af)
Location: include/net/netlink.h:545
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff817dfac9)
Location: include/net/netlink.h:545
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/dcb/dcbnl.c (ffffffff81813ef4)
Location: include/net/netlink.h:545
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/taskstats.c (ffffffff81147457)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff814d8584)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff816e6e98)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff817778b8)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/netlink/genetlink.c (ffffffff817bc58b)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff817eec6b)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff8184f1f4)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/dcb/dcbnl.c (ffffffff81886dd4)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/taskstats.c (ffffffff811512f7)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff814fac6c)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff817162e8)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff817a4938)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/netlink/genetlink.c (ffffffff817ebe9b)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f67b)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff8188114a)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81899d2c)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffffffff818bb644)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/taskstats.c (ffffffff81153a1b)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff8150a27b)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8172e0e1)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff817c2a63)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/netlink/genetlink.c (ffffffff8180bdf5)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff8184038b)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff818a7186)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff818bff18)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffffffff818e2053)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/taskstats.c (ffffffff8116021b)
Location: include/net/netlink.h:571
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff8154c77b)
Location: include/net/netlink.h:571
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8179f711)
Location: include/net/netlink.h:571
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff8183c3a3)
Location: include/net/netlink.h:571
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/netlink/genetlink.c (ffffffff8188ad85)
Location: include/net/netlink.h:571
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf72b)
Location: include/net/netlink.h:571
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff81929be5)
Location: include/net/netlink.h:571
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81942fe8)
Location: include/net/netlink.h:571
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffffffff81967df5)
Location: include/net/netlink.h:571
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/taskstats.c (ffffffff8116f156)
Location: include/net/netlink.h:571
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff81582ebb)
Location: include/net/netlink.h:571
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff817e6cf1)
Location: include/net/netlink.h:571
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff81886e22)
Location: include/net/netlink.h:571
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/netlink/genetlink.c (ffffffff818de3af)
Location: include/net/netlink.h:571
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff81915318)
Location: include/net/netlink.h:571
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff81981f51)
Location: include/net/netlink.h:571
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff8199b8a8)
Location: include/net/netlink.h:571
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffffffff819c1632)
Location: include/net/netlink.h:571
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/taskstats.c (ffffffff8117cc56)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff8159afeb)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff818130a1)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff818a7594)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/netlink/genetlink.c (ffffffff8190ad6f)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff81943938)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff819b85fb)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff819d227b)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffffffff819f8b77)
Location: include/net/netlink.h:714
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/taskstats.c (ffffffff81189aee)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff815cc666)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff81855138)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff818f2636)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/devlink.c (ffffffff81951c1a)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/genetlink.c (ffffffff8196c16c)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7f0b)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff81a27066)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81a410a7)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffffffff81a680d4)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/taskstats.c (ffffffff81195a2a)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff815ed8e6)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff81886b98)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff8192459a)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/drop_monitor.c (ffffffff819765f5)
Location: include/net/netlink.h:948
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
In net/core/devlink.c (ffffffff8198865a)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/genetlink.c (ffffffff819a2b18)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff819def9e)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff81a5db24)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81a77d27)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffffffff81a9ea34)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/taskstats.c (ffffffff811aac93)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:send_cpu_listeners
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff81699466)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff819f824a)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/drop_monitor.c (ffffffff81a4b362)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81a5163b)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/genetlink.c (ffffffff81a7d6ae)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81a86847)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/features.c (ffffffff81a8a001)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a8cbf5)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_free
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acc4ed)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff81b53c53)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff81b722a7)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffffffff81b99822)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb36f3)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
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
In kernel/taskstats.c (ffffffff811a8243)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:send_cpu_listeners
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff816b6584)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff8195f7ae)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff819f7c4a)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/drop_monitor.c (ffffffff81a50f92)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81a5774b)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/genetlink.c (ffffffff81a8626e)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81a90157)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/features.c (ffffffff81a938d1)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a96305)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_free
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81a97616)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad84b0)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff81b62243)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff81b81011)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffffffff81ba94e6)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7dd8)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
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
In kernel/taskstats.c (ffffffff811a8d3d)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff81698634)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81942d11)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff819dddcd)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/drop_monitor.c (ffffffff81a35f1b)
Location: include/net/netlink.h:1013
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
In net/core/devlink.c (ffffffff81a4bf14)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/genetlink.c (ffffffff81a6ef7b)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81a7986b)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/features.c (ffffffff81a7d2f7)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a7fd85)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_free
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81a8105e)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac324a)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff81b504a3)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff81b6fc1f)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffffffff81b9866f)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb9562)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
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
In kernel/taskstats.c (ffffffff811d2889)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff8170e3b4)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8191ab5c)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff819e77e2)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81a8e05d)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/drop_monitor.c (ffffffff81aebb15)
Location: include/net/netlink.h:1013
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
In net/core/devlink.c (ffffffff81b042dc)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_doit
  - net/core/devlink.c:devlink_rate_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/genetlink.c (ffffffff81b289bb)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81b33c23)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/features.c (ffffffff81b374d7)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81b39b55)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_free
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81b3ada8)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b810f3)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff81c17753)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff81c37d6f)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffffffff81c651cc)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/mptcp/pm_netlink.c (ffffffff81c88c32)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
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
In kernel/taskstats.c (ffffffff812071b1)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff8183cd8b)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6ffa8)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81b4d0ab)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81c03ce6)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/drop_monitor.c (ffffffff81c6e455)
Location: include/net/netlink.h:1013
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
In net/core/devlink.c (ffffffff81c89c67)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_linecard_get_doit
  - net/core/devlink.c:devlink_linecard_notify
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_doit
  - net/core/devlink.c:devlink_rate_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/genetlink.c (ffffffff81cb1aa1)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ethtool/netlink.c (ffffffff81cbf35b)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/features.c (ffffffff81cc2ee1)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81cc59c5)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_free
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81cc6d39)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d11676)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff81db352c)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff81dd594e)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffffffff81e07e09)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2f113)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
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
In kernel/taskstats.c (ffffffff8124f521)
Location: include/net/netlink.h:1062
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff819727db)
Location: include/net/netlink.h:1062
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c02e3c)
Location: include/net/netlink.h:1062
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81ce4dab)
Location: include/net/netlink.h:1062
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81db33a6)
Location: include/net/netlink.h:1062
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/drop_monitor.c (ffffffff81e260de)
Location: include/net/netlink.h:1062
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
In net/core/devlink.c (ffffffff81e44847)
Location: include/net/netlink.h:1062
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_cmd_selftests_get_doit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_linecard_get_doit
  - net/core/devlink.c:devlink_linecard_notify
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_doit
  - net/core/devlink.c:devlink_rate_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/af_netlink.c (ffffffff81e6c85d)
Location: include/net/netlink.h:1062
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81e6f8e1)
Location: include/net/netlink.h:1062
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ethtool/netlink.c (ffffffff81e7defb)
Location: include/net/netlink.h:1062
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/features.c (ffffffff81e821d1)
Location: include/net/netlink.h:1062
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81e84f65)
Location: include/net/netlink.h:1062
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_free
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81e86369)
Location: include/net/netlink.h:1062
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed7426)
Location: include/net/netlink.h:1062
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff81f82e8c)
Location: include/net/netlink.h:1062
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff81fa70ee)
Location: include/net/netlink.h:1062
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffffffff81fdd359)
Location: include/net/netlink.h:1062
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/mptcp/pm_netlink.c (ffffffff8200b693)
Location: include/net/netlink.h:1062
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
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
In kernel/taskstats.c (ffffffff812668d1)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff819b8eab)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c684ec)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81d4d37b)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81e23a66)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/netdev-genl.c (ffffffff81e7d137)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
```
```
In net/core/drop_monitor.c (ffffffff81e9b67e)
Location: include/net/netlink.h:1063
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
In net/netlink/af_netlink.c (ffffffff81ec88bd)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81ecbd61)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ethtool/netlink.c (ffffffff81eda4a3)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/features.c (ffffffff81ede831)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81ee1895)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_free
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81ee2d10)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f36328)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff81fe318c)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff8200794e)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/devlink/leftover.c (ffffffff82037a87)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_trap_policer_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_group_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_region_get_doit
  - net/devlink/leftover.c:devlink_nl_region_notify_build
  - net/devlink/leftover.c:devlink_nl_cmd_param_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_pool_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_linecard_get_doit
  - net/devlink/leftover.c:devlink_linecard_notify
  - net/devlink/leftover.c:devlink_nl_cmd_port_new_doit
  - net/devlink/leftover.c:devlink_nl_cmd_port_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_rate_get_doit
  - net/devlink/leftover.c:devlink_rate_notify
  - net/devlink/leftover.c:devlink_port_notify
```
```
In net/devlink/dev.c (ffffffff82045aec)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_cmd_selftests_get_doit
  - net/devlink/dev.c:__devlink_compat_running_version
  - net/devlink/dev.c:devlink_nl_cmd_info_get_doit
  - net/devlink/dev.c:devlink_nl_cmd_eswitch_get_doit
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_cmd_get_doit
  - net/devlink/dev.c:devlink_notify
```
```
In net/devlink/health.c (ffffffff82047f67)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_get_doit
```
```
In net/dcb/dcbnl.c (ffffffff82059429)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/mptcp/pm_netlink.c (ffffffff82087b2c)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
```
In net/handshake/netlink.c (ffffffff820925b9)
Location: include/net/netlink.h:1063
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
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
In kernel/taskstats.c (ffffffff812807cc)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff81a034e1)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/regulator/event.c (ffffffff81ae268d)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - drivers/regulator/event.c:reg_generate_netlink_event
  - drivers/regulator/event.c:reg_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81e03e6b)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81ebb7b3)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_id_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_id_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_id_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_pin_event_send
  - drivers/dpll/dpll_netlink.c:dpll_device_event_send
```
```
In net/core/net_namespace.c (ffffffff81ee19c6)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/netdev-genl.c (ffffffff81f3e035)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_queue_get_doit
  - net/core/netdev-genl.c:netdev_nl_napi_get_doit
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
  - net/core/netdev-genl.c:netdev_genl_dev_notify
```
```
In net/core/page_pool_user.c (ffffffff81f455d1)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/core/page_pool_user.c:netdev_nl_page_pool_event
  - net/core/page_pool_user.c:netdev_nl_page_pool_get_do
```
```
In net/core/drop_monitor.c (ffffffff81f5ddee)
Location: include/net/netlink.h:1084
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
In net/netlink/af_netlink.c (ffffffff81f8bb9c)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81f8f281)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ethtool/netlink.c (ffffffff81f9e293)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/features.c (ffffffff81fa2661)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81fa5725)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_free
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81fa6ba0)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffc5c8)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff820b10ac)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff820d67de)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/devlink/dev.c (ffffffff8210542f)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_get_doit
  - net/devlink/dev.c:__devlink_compat_running_version
  - net/devlink/dev.c:devlink_nl_info_get_doit
  - net/devlink/dev.c:devlink_nl_eswitch_get_doit
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_get_doit
```
```
In net/devlink/port.c (ffffffff8210812b)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_new_doit
  - net/devlink/port.c:devlink_nl_port_get_doit
  - net/devlink/port.c:devlink_port_notify
```
```
In net/devlink/sb.c (ffffffff8210a08d)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_get_doit
  - net/devlink/sb.c:devlink_nl_sb_port_pool_get_doit
  - net/devlink/sb.c:devlink_nl_sb_pool_get_doit
  - net/devlink/sb.c:devlink_nl_sb_get_doit
```
```
In net/devlink/dpipe.c (ffffffff8210af5a)
Location: include/net/netlink.h:1084
Inline: True
```
```
In net/devlink/resource.c (ffffffff8210c978)
Location: include/net/netlink.h:1084
Inline: True
```
```
In net/devlink/param.c (ffffffff8210f0e8)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/devlink/param.c:devlink_nl_param_get_doit
```
```
In net/devlink/region.c (ffffffff821108b2)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_get_doit
  - net/devlink/region.c:devlink_nl_region_notify_build
```
```
In net/devlink/health.c (ffffffff82113fb7)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_get_doit
```
```
In net/devlink/trap.c (ffffffff82117687)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_get_doit
  - net/devlink/trap.c:devlink_nl_trap_group_get_doit
  - net/devlink/trap.c:devlink_nl_trap_get_doit
```
```
In net/devlink/rate.c (ffffffff8211925d)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/devlink/rate.c:devlink_nl_rate_get_doit
  - net/devlink/rate.c:devlink_rate_notify
```
```
In net/devlink/linecard.c (ffffffff8211a6d0)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/devlink/linecard.c:devlink_nl_linecard_get_doit
  - net/devlink/linecard.c:devlink_linecard_notify
```
```
In net/dcb/dcbnl.c (ffffffff8212bfa9)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/mptcp/pm_netlink.c (ffffffff8215d364)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_limits_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_doit
```
```
In net/handshake/netlink.c (ffffffff82168e9f)
Location: include/net/netlink.h:1084
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
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
In kernel/taskstats.c (ffff80001020dc50)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffff800010778da0)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffff800010ad39ac)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffff800010bbff48)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/drop_monitor.c (ffff800010c1cac8)
Location: include/net/netlink.h:948
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
In net/core/devlink.c (ffff800010c30594)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/genetlink.c (ffff800010c51df0)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffff800010c92194)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffff800010d22c48)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffff800010d41348)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffff800010d6f40c)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/taskstats.c (c044c698)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/thermal/thermal_core.c (c0bb4594)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (c0cdba44)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/drop_monitor.c (c0d34a58)
Location: include/net/netlink.h:948
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
In net/core/devlink.c (c0d47580)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/genetlink.c (c0d614ac)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (c0da0e90)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (c0e2721c)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (c0e43d4c)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (c0e6d070)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/taskstats.c (c00000000028bcf4)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/thermal/thermal_core.c (c000000000bb8cf0)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (c000000000c99474)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/drop_monitor.c (c000000000d0db28)
Location: include/net/netlink.h:948
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
In net/core/devlink.c (c000000000d29378)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/genetlink.c (c000000000d50928)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (c000000000da2964)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (c000000000e529e0)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (c000000000e75c60)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (c000000000eae2e0)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/taskstats.c (ffffffe00016ebd0)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/thermal/thermal_core.c (ffffffe0006cff92)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffe00074d76e)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/drop_monitor.c (ffffffe000796990)
Location: include/net/netlink.h:948
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
In net/core/devlink.c (ffffffe0007a676a)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/genetlink.c (ffffffe0007bce5a)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f2126)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffe000864714)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffe00087caa0)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffffffe0008a0f88)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/taskstats.c (ffffffff8118e04a)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff815dca36)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8182ca18)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff818c459a)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/drop_monitor.c (ffffffff819165c5)
Location: include/net/netlink.h:948
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
In net/core/devlink.c (ffffffff819284ca)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/genetlink.c (ffffffff81942988)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197ee0e)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff819fd1b4)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81a173b7)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffffffff81a3ddc4)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/taskstats.c (ffffffff81181154)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff815c8076)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff817f40a8)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff8187e4da)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/drop_monitor.c (ffffffff818d0375)
Location: include/net/netlink.h:948
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
In net/core/devlink.c (ffffffff818e227a)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/genetlink.c (ffffffff818fc478)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff819388ce)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff819b9f74)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff819d4177)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffffffff819fa9b4)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/taskstats.c (ffffffff8118be1a)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff815e1bc6)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8187c048)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff8191559a)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/drop_monitor.c (ffffffff819675f5)
Location: include/net/netlink.h:948
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
In net/core/devlink.c (ffffffff8197965a)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/genetlink.c (ffffffff81993b18)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e95de)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff81a67c34)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81a81e37)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffffffff81aa9c74)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/taskstats.c (ffffffff811997a2)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/acpi/event.c (ffffffff815fba86)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff81897a78)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff8193677a)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/drop_monitor.c (ffffffff81989885)
Location: include/net/netlink.h:948
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
In net/core/devlink.c (ffffffff8199bb4a)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/genetlink.c (ffffffff819b6612)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f334c)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/ndisc.c (ffffffff81a74223)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81a8e746)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/dcb/dcbnl.c (ffffffff81ab5fe4)
Location: include/net/netlink.h:948
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
</details>
</li>
</ul>

## Differences
