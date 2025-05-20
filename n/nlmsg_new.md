# Function: <code>nlmsg_new</code>

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
In kernel/audit.c (ffffffff811217c3)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8113e200)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff812766c6)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff8134cb22)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff81489729)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff81541daa)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (ffffffff81685889)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff8170ff06)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81726db6)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
```
```
In net/core/rtnetlink.c (ffffffff8172a56b)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
```
```
In net/core/sock_diag.c (ffffffff817331f6)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff8173a28c)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/netlink/genetlink.c (ffffffff8175000e)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:genl_ctrl_event
```
```
In net/ipv4/tcp_metrics.c (ffffffff81781658)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff81790509)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_semantics.c (ffffffff8179dd41)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ipmr.c (ffffffff817a8896)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff817cc3fe)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
```
```
In net/ipv6/addrlabel.c (ffffffff817d2f7f)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff817d9233)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
```
```
In net/ipv6/ndisc.c (ffffffff817df99e)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff817f9606)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/wireless/wext-core.c (ffffffff81809d45)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180d3c6)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180e526)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8180fe59)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81813cdb)
Location: include/net/netlink.h:483
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
In kernel/audit.c (ffffffff81129756)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8114685e)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff812a2f06)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff81382ac2)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff814d851f)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff815936ea)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (ffffffff816e6d5f)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff81777846)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff817908d6)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
```
```
In net/core/rtnetlink.c (ffffffff8179670a)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff8179ec16)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff817a63fc)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/netlink/af_netlink.c (ffffffff817bac6f)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff817bc326)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff817eeb18)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff817fd989)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff8180b881)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ipmr.c (ffffffff81815fc6)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81838e4e)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff8184097f)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81847186)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
```
```
In net/ipv6/ndisc.c (ffffffff8184f0c9)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff81868e46)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/wireless/wext-core.c (ffffffff8187b845)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8187f7b6)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81880ba6)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81882530)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8188353b)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81886bbb)
Location: include/net/netlink.h:494
Inline: True
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
In kernel/audit.c (ffffffff81133880)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8115073e)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff812b88e6)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff81399542)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff814fac07)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff815c0faa)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (ffffffff817161af)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff817a48c6)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff817be186)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
```
```
In net/core/rtnetlink.c (ffffffff817c4d67)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff817cd5e6)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff818c4853)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/netlink/af_netlink.c (ffffffff817ea60f)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff817ebc36)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f528)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff8182e8e9)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff8183c9a1)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ipmr.c (ffffffff81847776)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff8186a86e)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff818725ff)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81878fc6)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
```
```
In net/ipv6/ndisc.c (ffffffff8188101f)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81899c46)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff8189bc96)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/wireless/wext-core.c (ffffffff818b0105)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b4066)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b5456)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b6de0)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b7ddb)
Location: include/net/netlink.h:494
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff818bb42b)
Location: include/net/netlink.h:494
Inline: True
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
In kernel/audit.c (ffffffff81134d6d)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81152d2e)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff812c5cb6)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff813af9b6)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff8150a145)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff815d6af9)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (ffffffff8172dfaf)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff817c29f6)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff817dcc0b)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
```
```
In net/core/rtnetlink.c (ffffffff817e37c0)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff817ec95f)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff817f4337)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/netlink/af_netlink.c (ffffffff8180a337)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff8180bb83)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff8184024f)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff8184fa15)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff8185e140)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ipmr.c (ffffffff8186b06f)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8188edae)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81897385)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff8189e201)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff818a7053)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff818bfe36)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff818c2088)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff818d6ab4)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818daa16)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dbda6)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818dd69d)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818de6ab)
Location: include/net/netlink.h:503
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff818e1e1b)
Location: include/net/netlink.h:503
Inline: True
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
In kernel/audit.c (ffffffff81141abd)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8115f54e)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff812e9b66)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff813d5a66)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff8154c645)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff8163d8d9)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (ffffffff8179f5df)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff8183c336)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff818577db)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
```
```
In net/core/rtnetlink.c (ffffffff8185e6f9)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81868b3f)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff8186fa9a)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/netlink/af_netlink.c (ffffffff818892f3)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff8188ab13)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf5ef)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff818cf645)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff818de180)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ipmr.c (ffffffff818eb80f)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff819103fe)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81917fd0)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff819207e1)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff81929ab2)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81942f06)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff819459c8)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff8195c684)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819605f6)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81961986)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8196328d)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819642b1)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81967bbb)
Location: include/net/netlink.h:509
Inline: True
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
In kernel/audit.c (ffffffff81150479)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8116e565)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff81316a9f)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff81406085)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff81582d75)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff81678ef4)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (ffffffff817e6bda)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff81886d95)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff818a2981)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
```
```
In net/core/rtnetlink.c (ffffffff818aa2b7)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff818b89c7)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff818c128a)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/netlink/af_netlink.c (ffffffff818dcd75)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff818de145)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff819151ec)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff81926085)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff81934cf0)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ipmr.c (ffffffff81941789)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8196784e)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff8196f810)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81978b27)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff81981c8a)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff8199b803)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff8199d298)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819b5e7f)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819b9de7)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bb157)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bcad6)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bdb51)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819c13c5)
Location: include/net/netlink.h:509
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819cb24f)
Location: include/net/netlink.h:509
Inline: True
Inline callers:
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
In kernel/audit.c (ffffffff8115d139)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8117c035)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff8132da4f)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff81421bd5)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff8159aea5)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff81697fd4)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (ffffffff81812f8a)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff818a7519)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff818c5b91)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff818ce9a7)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff818df617)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff818ea09a)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/netlink/af_netlink.c (ffffffff8190974b)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff8190ab05)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff8194380c)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff819550a5)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff81964640)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ipmr.c (ffffffff81971e10)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8199cf36)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819a5420)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff819ae7a7)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff819b8336)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff819d21d3)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff819d3df8)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819ed13f)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f10b7)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f23c7)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f3d28)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4cf1)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819f8925)
Location: include/net/netlink.h:652
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a04205)
Location: include/net/netlink.h:652
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
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
In kernel/audit.c (ffffffff81169867)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81188ec5)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff8135578e)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff8144f7be)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff815cc515)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff816d0b54)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (ffffffff81855020)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff818f25ba)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81911be0)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff8191b7b7)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff8192dc95)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff81939afa)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/devlink.c (ffffffff81951b96)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
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
In net/netlink/af_netlink.c (ffffffff8196aa57)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff8196befd)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7ddb)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff819b994a)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff819ca19d)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffffffff819d3beb)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff819db6a5)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a09116)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a118ff)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81a1d033)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff81a26d8b)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81a41003)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a42508)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a5c330)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a60377)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a61717)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a63188)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a641b1)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81a67be5)
Location: include/net/netlink.h:886
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a734a5)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
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
In kernel/audit.c (ffffffff81175707)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81194e05)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff8136dace)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff8146962e)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff815ed795)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff816f4974)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (ffffffff81886a80)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff81924527)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81944250)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff8194ddf4)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff8195fee9)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff8196c9ca)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff819763b9)
Location: include/net/netlink.h:886
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
In net/core/devlink.c (ffffffff819885d6)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
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
In net/netlink/af_netlink.c (ffffffff819a14e9)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff819a28ad)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff819dee6b)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff819f063e)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff81a00d6d)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffffffff81a0a75b)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81a125be)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a3fdc6)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a4851f)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81a53d03)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff81a5d7f1)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81a77c83)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a79168)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a92f60)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a96fa7)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a982e7)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a99d38)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9ad31)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81a9e545)
Location: include/net/netlink.h:886
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa9c95)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
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
In kernel/audit.c (ffffffff8118656c)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_alloc
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff811a9f95)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff813b55fe)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff814bd7d5)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff81699315)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff817acfa4)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (ffffffff819f81d7)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81a142c0)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff81a1f97a)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81a337b9)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff81a4088a)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81a4b285)
Location: include/net/netlink.h:938
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
In net/core/devlink.c (ffffffff81a515ff)
Location: include/net/netlink.h:938
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
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
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
In net/netlink/af_netlink.c (ffffffff81a7aec7)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81a7d619)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81a86746)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (ffffffff81a8cf68)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acc405)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff81ade5ac)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff81aefdd0)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffffffff81afba0f)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81b048ef)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81b3dd20)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f3ad)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81b4b393)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81b53b06)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff81b72203)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81b744b4)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/wireless/wext-core.c (ffffffff81b8e270)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b92827)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93b57)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b957b8)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b964ff)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81b995c5)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5e95)
Location: include/net/netlink.h:938
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb35fb)
Location: include/net/netlink.h:938
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
In kernel/audit.c (ffffffff8118365c)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_alloc
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff811a75b8)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff813c6e2e)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff814db251)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff816b63d5)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff817c1b34)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_netlink.c (ffffffff8195f6e3)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff819f7bd7)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81a145d0)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff81a1f3da)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81a35b29)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff81a435aa)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81a50eb5)
Location: include/net/netlink.h:951
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
In net/core/devlink.c (ffffffff81a5770f)
Location: include/net/netlink.h:951
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
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
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
In net/netlink/af_netlink.c (ffffffff81a83c87)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81a861d9)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81a90056)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (ffffffff81a966a8)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad83c7)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff81aeb38c)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff81afcd10)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffffffff81b090df)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81b12a60)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81b4c8b0)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b4de3d)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81b5a039)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81b620f6)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff81b80f63)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81b83224)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/wireless/wext-core.c (ffffffff81b9df10)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba2477)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba3797)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba540b)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba616f)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81ba9275)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb5375)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7ce0)
Location: include/net/netlink.h:951
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
In kernel/audit.c (ffffffff81186012)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff811a7f98)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff813cdebe)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff814e1bb5)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff81698485)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff817a5052)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81942c43)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff819ddd5a)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff819faf60)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff81a0647d)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81a1cc79)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff81a2830a)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81a35cd9)
Location: include/net/netlink.h:951
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
In net/core/devlink.c (ffffffff81a4be95)
Location: include/net/netlink.h:951
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
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
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
In net/netlink/af_netlink.c (ffffffff81a6ce46)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81a6eee9)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81a79767)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (ffffffff81a80188)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac315f)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff81ad80b8)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae864e)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81aea935)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
```
In net/ipv4/nexthop.c (ffffffff81af727d)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81b00180)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81b31f33)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3b8dd)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81b419c5)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81b50356)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff81b6fb73)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81b71ea5)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/wireless/wext-core.c (ffffffff81b8d010)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b91557)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b928b7)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b94566)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b952ef)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81b98405)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba4375)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bbb96a)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
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
In kernel/audit.c (ffffffff811ae402)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff811d1d58)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff8141f1ee)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff8153abb5)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff8170e205)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff818309d2)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8191a8ff)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff819e7705)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81a8dfea)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81aacba0)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff81ab8afd)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81ad04d9)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff81add0aa)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81aeb8a9)
Location: include/net/netlink.h:951
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
In net/core/devlink.c (ffffffff81b0428c)
Location: include/net/netlink.h:951
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
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
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
In net/netlink/af_netlink.c (ffffffff81b264c6)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81b28929)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81b33ae8)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (ffffffff81b39f58)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b80fd0)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff81b96f18)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba85dd)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81ba9cc6)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
```
In net/ipv4/nexthop.c (ffffffff81bb6c38)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81bc12b0)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81bf8003)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81c0216d)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81c096f2)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81c17606)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff81c37cc3)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c355)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/wireless/wext-core.c (ffffffff81c593c7)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5dcf7)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f057)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60d46)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61b1f)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81c64f55)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c71f05)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8b5aa)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
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
In kernel/audit.c (ffffffff811df62e)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81206578)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff8149702f)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff815d22f5)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff8183cbd5)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff81971d68)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6fd42)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81b4cfb5)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81c03c5a)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81c25b91)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff81c33b40)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81c4dd8a)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff81c5e8ea)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81c6e1e9)
Location: include/net/netlink.h:951
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
In net/core/devlink.c (ffffffff81c89bf9)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
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
In net/netlink/af_netlink.c (ffffffff81caf02e)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81cb1a15)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ethtool/netlink.c (ffffffff81cbf215)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (ffffffff81cc5e18)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d1144a)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff81d28ab3)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3afe7)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81d3c8bd)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
```
In net/ipv4/nexthop.c (ffffffff81d4a89a)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81d55c7a)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81d913a3)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81d9c10c)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81da4880)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81db33f6)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff81dd5883)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81dda70f)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/wireless/wext-core.c (ffffffff81dfab5e)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81dfffb7)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e01407)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e032b6)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e0411f)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81e07b45)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e15a95)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81e32b5f)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
```
In net/mctp/device.c (ffffffff81e38050)
Location: include/net/netlink.h:951
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_addr_notify
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
In kernel/audit.c (ffffffff8122530e)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8124e888)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff8152b03f)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff816801b5)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff81972625)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff81adcfe8)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c02bd2)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81ce4cb5)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81db331a)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81dd7de1)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff81de6f90)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81e02e8a)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff81e1515a)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81e25e69)
Location: include/net/netlink.h:1000
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
In net/core/devlink.c (ffffffff81e447d9)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_cmd_selftests_get_doit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
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
In net/netlink/af_netlink.c (ffffffff81e6c72a)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81e6f855)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ethtool/netlink.c (ffffffff81e7ddb5)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (ffffffff81e853e8)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed71fa)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff81ef0503)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff81f03967)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81f0535d)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
```
In net/ipv4/nexthop.c (ffffffff81f13f5a)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81f1fffa)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81f5fb03)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81f6addc)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81f73d20)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81f82d56)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff81fa7023)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81fad345)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/wireless/wext-core.c (ffffffff81fcf377)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd4dd7)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd6257)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd8236)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd90ef)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81fdd085)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81feca45)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff8200b5bf)
Location: include/net/netlink.h:1000
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
In net/mctp/device.c (ffffffff82011290)
Location: include/net/netlink.h:1000
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_addr_notify
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
In kernel/audit.c (ffffffff8123b8de)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81265c38)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff815633cf)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff816b8295)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff819b8cf5)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff81b2b258)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c68282)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81d4d285)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81e239da)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81e48b51)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff81e57f80)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81e753e7)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netdev-genl.c (ffffffff81e7d0e2)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
```
```
In net/core/fib_rules.c (ffffffff81e88a6a)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81e9b409)
Location: include/net/netlink.h:1001
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
In net/netlink/af_netlink.c (ffffffff81ec878a)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81ecbcd5)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ethtool/netlink.c (ffffffff81eda375)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (ffffffff81ee1d18)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f361db)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff81f4ff53)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff81f63347)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81f64d5f)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
```
In net/ipv4/nexthop.c (ffffffff81f73c2a)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81f7fafa)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81fbf833)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81fcae0c)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81fd3e00)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81fe3056)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff82007883)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff8200db05)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/devlink/leftover.c (ffffffff820379f3)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_trap_policer_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_group_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_region_get_doit
  - net/devlink/leftover.c:devlink_nl_region_notify_build
  - net/devlink/leftover.c:devlink_nl_cmd_param_get_doit
  - net/devlink/leftover.c:devlink_dpipe_send_and_alloc_skb
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
In net/devlink/dev.c (ffffffff820458d2)
Location: include/net/netlink.h:1001
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
In net/devlink/health.c (ffffffff82047eea)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_get_doit
```
```
In net/wireless/wext-core.c (ffffffff8204aff3)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82050a77)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82051f17)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053f06)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82054dbf)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff82059155)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82068ce5)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff82087a4f)
Location: include/net/netlink.h:1001
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
In net/mctp/device.c (ffffffff8208e050)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_addr_notify
```
```
In net/handshake/netlink.c (ffffffff820924c6)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
```
In net/handshake/tlshd.c (ffffffff82093e7e)
Location: include/net/netlink.h:1001
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
In kernel/audit.c (ffffffff8125579e)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8127faf8)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff81599abf)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff816f4cc5)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff81a03325)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/regulator/event.c (ffffffff81ae2515)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - drivers/regulator/event.c:reg_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff81b825ec)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81e03d75)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81ebb6bd)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_id_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_id_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_pin_event_send
  - drivers/dpll/dpll_netlink.c:dpll_device_event_send
```
```
In net/core/net_namespace.c (ffffffff81ee193a)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81f07711)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff81f172d0)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
```
```
In net/core/sock_diag.c (ffffffff81f34c87)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netdev-genl.c (ffffffff81f3dfcd)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_queue_get_doit
  - net/core/netdev-genl.c:netdev_nl_napi_get_doit
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
  - net/core/netdev-genl.c:netdev_genl_dev_notify
```
```
In net/core/page_pool_user.c (ffffffff81f4557a)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/core/page_pool_user.c:netdev_nl_page_pool_event
  - net/core/page_pool_user.c:netdev_nl_page_pool_get_do
```
```
In net/core/fib_rules.c (ffffffff81f4aa7a)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81f5db79)
Location: include/net/netlink.h:1008
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
In net/netlink/af_netlink.c (ffffffff81f8baa4)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81f8f1f5)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ethtool/netlink.c (ffffffff81f9e146)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (ffffffff81fa5ba8)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffc47b)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff82016103)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff82029917)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff8202b32f)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
```
In net/ipv4/nexthop.c (ffffffff8203a41a)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff8204617a)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff8208ccd3)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff820985ac)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff820a1710)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff820b0f76)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff820d6713)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff820dd585)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/devlink/netlink.c (ffffffff82101804)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_msg_reply_and_new
```
```
In net/devlink/dev.c (ffffffff82105215)
Location: include/net/netlink.h:1008
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
In net/devlink/port.c (ffffffff8210807a)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_new_doit
  - net/devlink/port.c:devlink_nl_port_get_doit
  - net/devlink/port.c:devlink_port_notify
```
```
In net/devlink/sb.c (ffffffff82109f95)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_get_doit
  - net/devlink/sb.c:devlink_nl_sb_port_pool_get_doit
  - net/devlink/sb.c:devlink_nl_sb_pool_get_doit
  - net/devlink/sb.c:devlink_nl_sb_get_doit
```
```
In net/devlink/dpipe.c (ffffffff8210a704)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devlink_dpipe_send_and_alloc_skb
```
```
In net/devlink/param.c (ffffffff8210f059)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/devlink/param.c:devlink_nl_param_get_doit
```
```
In net/devlink/region.c (ffffffff821107e4)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_get_doit
  - net/devlink/region.c:devlink_nl_region_notify_build
```
```
In net/devlink/health.c (ffffffff82113f3a)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_get_doit
```
```
In net/devlink/trap.c (ffffffff821175f3)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_get_doit
  - net/devlink/trap.c:devlink_nl_trap_group_get_doit
  - net/devlink/trap.c:devlink_nl_trap_get_doit
```
```
In net/devlink/rate.c (ffffffff821191ce)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/devlink/rate.c:devlink_nl_rate_get_doit
  - net/devlink/rate.c:devlink_rate_notify
```
```
In net/devlink/linecard.c (ffffffff8211a624)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/devlink/linecard.c:devlink_nl_linecard_get_doit
  - net/devlink/linecard.c:devlink_linecard_notify
```
```
In net/wireless/wext-core.c (ffffffff8211d473)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82123127)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff821246f7)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff821266e6)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8212769f)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff8212bcd5)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213bf65)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff8215d2af)
Location: include/net/netlink.h:1008
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
In net/mctp/device.c (ffffffff82164510)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_addr_notify
```
```
In net/handshake/netlink.c (ffffffff82168da6)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
```
In net/handshake/tlshd.c (ffffffff8216a79e)
Location: include/net/netlink.h:1008
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
In kernel/audit.c (ffff8000101ea560)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffff80001020d2e8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffff80001043752c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffff800010557ab0)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffff800010778c88)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffff8000108ddd58)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (ffff800010ad3898)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffff800010bbfecc)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffff800010be411c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffff800010befd3c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffff800010c03718)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffff800010c131d8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffff800010c1c86c)
Location: include/net/netlink.h:886
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
In net/core/devlink.c (ffff800010c304f8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
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
In net/netlink/af_netlink.c (ffff800010c4fb3c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffff800010c51b7c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffff800010c9202c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffff800010ca6490)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9360)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffff800010cc3d00)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffff800010ccb290)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffff800010d01050)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffff800010d0b880)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffff800010d17e18)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffff800010d22a8c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffff800010d412b8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffff800010d4266c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffff800010d60d84)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d6656c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d679ac)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d697e8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6a92c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffff800010d6ef58)
Location: include/net/netlink.h:886
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d990)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
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
In kernel/audit.c (c042a2b4)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (c044bc64)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (c05ff180)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (c070c9d0)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (c09ccdc0)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (c0bb444c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (c0cdb9d4)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (c0cfe5c8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (c0d0837c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (c0d1caac)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (c0d2ab94)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (c0d34750)
Location: include/net/netlink.h:886
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
In net/core/devlink.c (c0d474e8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
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
In net/netlink/af_netlink.c (c0d5fd28)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (c0d61264)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (c0da0d44)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (c0db2f88)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (c0dc4b00)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (c0dcf1ec)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (c0dd6bd4)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (c0e08b84)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (c0e11780)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (c0e1d9ec)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (c0e27030)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (c0e43cc0)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (c0e4508c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (c0e60414)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (c0e64dac)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (c0e6634c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e67dd0)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (c0e68ec4)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (c0e6cc0c)
Location: include/net/netlink.h:886
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (c0e784b8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
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
In kernel/audit.c (c00000000025b750)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (c00000000028b09c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (c000000000549940)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (c0000000006b59e4)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (c00000000097155c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (c000000000bb8b74)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (c000000000c993d0)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (c000000000cc75cc)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (c000000000cd40b0)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (c000000000cece54)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (c000000000d00348)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (c000000000d0d814)
Location: include/net/netlink.h:886
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
In net/core/devlink.c (c000000000d292b4)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
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
In net/netlink/af_netlink.c (c000000000d4e5e8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (c000000000d50628)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (c000000000da27a8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (c000000000dbac90)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (c000000000dd20e0)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (c000000000ddfab4)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (c000000000dec42c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (c000000000e2aef0)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (c000000000e3606c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (c000000000e45a78)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (c000000000e52754)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (c000000000e75b90)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (c000000000e77610)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (c000000000e9c16c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea26e8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea42a8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea6678)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea7cf8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (c000000000eac278)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebd4b4)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
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
In kernel/audit.c (ffffffe00015ef88)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffe00016e402)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffe0002d1790)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffe0003af404)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffe0005742ec)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (ffffffe0006cfe90)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffe00074d700)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffe00076aa6c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffe000771fbc)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffe0007827a6)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffe00078eb52)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffe00079678a)
Location: include/net/netlink.h:886
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
In net/core/devlink.c (ffffffe0007a66e8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
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
In net/netlink/af_netlink.c (ffffffe0007bb6e2)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffe0007bcc80)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1ff0)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffe000801c8c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffe000810068)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffffffe000818eb6)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffe000821448)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffe00084afc0)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffe000852914)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffe00085cdba)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffe000864548)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffe00087c9fe)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffe00087dee2)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffe000895e2e)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a06c)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089afc4)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089c6e2)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d494)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffe0008a0bf8)
Location: include/net/netlink.h:886
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008ab1ba)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
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
In kernel/audit.c (ffffffff8116dd27)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8118d425)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff813660ae)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff81461c0e)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff815dc8e5)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff816ba164)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (ffffffff8182c900)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff818c4527)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff818e4220)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff818eddc4)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff818ffeb9)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff8190c99a)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81916389)
Location: include/net/netlink.h:886
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
In net/core/devlink.c (ffffffff81928446)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
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
In net/netlink/af_netlink.c (ffffffff81941359)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff8194271d)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197ecdb)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff819903de)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff819a0b0d)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffffffff819aa4fb)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff819b1e95)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff819df456)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819e7baf)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff819f3393)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff819fce81)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81a17313)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a187f8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a325f0)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a36337)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a37677)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a390c8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a3a0c1)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81a3d8d5)
Location: include/net/netlink.h:886
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a49025)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
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
In kernel/audit.c (ffffffff81160ec7)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81180545)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff81356d4e)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff8145263e)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff815c7f25)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff81697da4)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_transport_fc.c (ffffffff8170f794)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_fc.c:fc_host_post_fc_event
```
```
In drivers/net/vxlan.c (ffffffff8176d10e)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/net/vxlan.c:__vxlan_fdb_notify
```
```
In drivers/thermal/thermal_core.c (ffffffff817f3f90)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff8187e467)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff8189e060)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff818a7c04)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff818b9ce9)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff818c675a)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff818d0139)
Location: include/net/netlink.h:886
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
In net/core/devlink.c (ffffffff818e21f6)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
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
In net/netlink/af_netlink.c (ffffffff818fae49)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff818fc20d)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff8193879b)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff81949e9e)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff8195a5cd)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffffffff81963fbb)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff8196e4c5)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8199c216)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819a496f)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff819b0153)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff819b9c41)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff819d40d3)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff819d55b8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819ef7e0)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f2f57)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f4297)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f5ce8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6ce1)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819fa4c5)
Location: include/net/netlink.h:886
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a05c15)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
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
In kernel/audit.c (ffffffff8116baf7)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8118b1f5)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff81363b7e)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff8145dcae)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff815e1a75)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff816e8634)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (ffffffff8187bf30)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff81915527)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81935250)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff8193edf4)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81950ee9)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff8195d9ca)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff819673b9)
Location: include/net/netlink.h:886
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
In net/core/devlink.c (ffffffff819795d6)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
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
In net/netlink/af_netlink.c (ffffffff819924e9)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff819938ad)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819b06d2)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_expect_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_stat_ct
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e94ab)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff819fac7e)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0b3ad)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffffffff81a14d9b)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81a1c735)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a49ed6)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a5262f)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81a5de13)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff81a67901)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81a81d93)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a83278)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a9e1a0)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa21e7)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa3527)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa4f78)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa5f71)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81aa9785)
Location: include/net/netlink.h:886
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4ed5)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
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
In kernel/audit.c (ffffffff811792b7)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81198b65)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff8137722e)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In security/selinux/netlink.c (ffffffff8147544e)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff815fb935)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff81702d34)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (ffffffff81897960)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff81936707)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81956960)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff81960651)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81972829)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/fib_rules.c (ffffffff8197fc1a)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81989649)
Location: include/net/netlink.h:886
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
In net/core/devlink.c (ffffffff8199bac6)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
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
In net/netlink/af_netlink.c (ffffffff819b4fd9)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff819b639d)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f320f)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/devinet.c (ffffffff81a04fce)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/fib_semantics.c (ffffffff81a15b8d)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffffffff81a1f7ab)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81a276e7)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a55e16)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a5e636)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81a6a223)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff81a73ef0)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81a8e693)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a8fb98)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81aaa3a0)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aae557)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aaf947)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab12f8)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab2311)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81ab5af5)
Location: include/net/netlink.h:886
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac1275)
Location: include/net/netlink.h:886
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
</details>
</li>
</ul>

## Differences
