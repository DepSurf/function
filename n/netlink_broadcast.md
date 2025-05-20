# Function: <code>netlink_broadcast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174bca0)
Location: net/netlink/af_netlink.c:2127
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:nlmsg_notify
Direct callers:
  - kernel/audit.c:audit_log_end
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
```
**Symbols:**

```
ffffffff8174bca0-ffffffff8174bcbf: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817bae4a)
Location: net/netlink/af_netlink.c:1434
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:audit_log_end
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
```
**Symbols:**

```
ffffffff817b8c80-ffffffff817b8c9f: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817ea7ea)
Location: net/netlink/af_netlink.c:1451
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_thread
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
```
**Symbols:**

```
ffffffff817e8730-ffffffff817e874f: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8180a74a)
Location: net/netlink/af_netlink.c:1486
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
```
**Symbols:**

```
ffffffff818086f0-ffffffff81808705: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81889682)
Location: net/netlink/af_netlink.c:1499
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
```
**Symbols:**

```
ffffffff81887570-ffffffff81887585: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818dd121)
Location: net/netlink/af_netlink.c:1538
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff818dac40-ffffffff818dac55: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81909acb)
Location: net/netlink/af_netlink.c:1531
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81907520-ffffffff81907535: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8196adc9)
Location: net/netlink/af_netlink.c:1531
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff819687d0-ffffffff819687e5: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819a1869)
Location: net/netlink/af_netlink.c:1532
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8199f270-ffffffff8199f285: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a7b20c)
Location: net/netlink/af_netlink.c:1532
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - lib/kobject_uevent.c:uevent_net_broadcast
  - lib/kobject_uevent.c:uevent_net_broadcast_tagged
  - lib/kobject_uevent.c:uevent_net_broadcast_untagged
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/netlink/genetlink.c:genlmsg_mcast
  - net/netlink/genetlink.c:genlmsg_mcast
  - net/ethtool/netlink.c:ethnl_multicast
```
**Symbols:**

```
ffffffff81a79150-ffffffff81a79165: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a8408c)
Location: net/netlink/af_netlink.c:1533
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - lib/kobject_uevent.c:uevent_net_broadcast
  - lib/kobject_uevent.c:uevent_net_broadcast_tagged
  - lib/kobject_uevent.c:uevent_net_broadcast_untagged
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/netlink/genetlink.c:genlmsg_mcast
  - net/netlink/genetlink.c:genlmsg_mcast
  - net/ethtool/netlink.c:ethnl_multicast
```
**Symbols:**

```
ffffffff81a81980-ffffffff81a81995: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a6d1d0)
Location: net/netlink/af_netlink.c:1543
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ethtool/netlink.c:ethnl_multicast
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
```
**Symbols:**

```
ffffffff81a6aa80-ffffffff81a6aa95: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b26841)
Location: net/netlink/af_netlink.c:1548
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_rate_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ethtool/netlink.c:ethnl_multicast
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
```
**Symbols:**

```
ffffffff81b24080-ffffffff81b24095: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81cad6d0)
Location: net/netlink/af_netlink.c:1490
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:devlink_linecard_notify
  - net/core/devlink.c:devlink_rate_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ethtool/netlink.c:ethnl_multicast
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
```
**Symbols:**

```
ffffffff81cad6d0-ffffffff81cad86c: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e6ac90)
Location: net/netlink/af_netlink.c:1510
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_linecard_notify
  - net/core/devlink.c:devlink_rate_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ethtool/netlink.c:ethnl_multicast
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff81e6ac90-ffffffff81e6ae2c: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec7100)
Location: net/netlink/af_netlink.c:1510
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ethtool/netlink.c:ethnl_multicast
  - net/devlink/leftover.c:devlink_nl_region_notify
  - net/devlink/leftover.c:devlink_linecard_notify
  - net/devlink/leftover.c:devlink_rate_notify
  - net/devlink/leftover.c:devlink_port_notify
  - net/devlink/dev.c:devlink_notify
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/handshake/netlink.c:handshake_genl_notify
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff81ec7100-ffffffff81ec729c: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f8b8f1)
Location: net/netlink/af_netlink.c:1571
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - security/selinux/netlink.c:selnl_notify
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff81f8a5a0-ffffffff81f8a5c7: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4fea0)
Location: net/netlink/af_netlink.c:1532
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffff800010c4c590-ffff800010c4c5f4: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d600cc)
Location: net/netlink/af_netlink.c:1532
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c0d5d2dc-c0d5d314: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d4eaec)
Location: net/netlink/af_netlink.c:1532
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c000000000d4afe0-c000000000d4affc: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007bb9b6)
Location: net/netlink/af_netlink.c:1532
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffe0007b98f6-ffffffe0007b9944: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819416d9)
Location: net/netlink/af_netlink.c:1532
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8193f0e0-ffffffff8193f0f5: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818fb1c9)
Location: net/netlink/af_netlink.c:1532
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/scsi/scsi_transport_fc.c:fc_host_post_fc_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff818f8be0-ffffffff818f8bf5: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81992869)
Location: net/netlink/af_netlink.c:1532
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81990270-ffffffff81990285: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int netlink_broadcast(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b5359)
Location: net/netlink/af_netlink.c:1532
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff819b2b40-ffffffff819b2b55: netlink_broadcast (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
