# Function: <code>nlmsg_total_size</code>

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
In kernel/audit.c (ffffffff81121c45)
Location: include/net/netlink.h:274
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In drivers/connector/connector.c (ffffffff81541daf)
Location: include/net/netlink.h:274
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:274
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:274
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
In kernel/audit.c (ffffffff81129b7e)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81146865)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In drivers/connector/connector.c (ffffffff815936f2)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8179670a)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff817bb281)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff817ff796)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81839f08)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/ipv6/route.c (ffffffff81847189)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
```
```
In net/ipv6/ndisc.c (ffffffff8184f0fe)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8188253c)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/net/netlink.h:285
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
In kernel/audit.c (ffffffff8113389e)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81150745)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In drivers/connector/connector.c (ffffffff815c0fb2)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff817c4d67)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/core/fib_rules.c (ffffffff818c4853)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff817eadf1)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff818306f6)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8186b928)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/ipv6/route.c (ffffffff81878fc9)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
```
```
In net/ipv6/ndisc.c (ffffffff81881054)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b6dec)
Location: include/net/netlink.h:285
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:285
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/net/netlink.h:285
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
Location: include/net/netlink.h:289
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81152d35)
Location: include/net/netlink.h:289
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In drivers/connector/connector.c (ffffffff815d6b01)
Location: include/net/netlink.h:289
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff817e37c0)
Location: include/net/netlink.h:289
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8180ad51)
Location: include/net/netlink.h:289
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81851bcb)
Location: include/net/netlink.h:289
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8186b082)
Location: include/net/netlink.h:289
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8189036b)
Location: include/net/netlink.h:289
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/ipv6/route.c (ffffffff8189e201)
Location: include/net/netlink.h:289
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff818a708a)
Location: include/net/netlink.h:289
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff818c15d5)
Location: include/net/netlink.h:289
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818dd6a9)
Location: include/net/netlink.h:289
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:289
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/net/netlink.h:289
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
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8115f555)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In drivers/connector/connector.c (ffffffff8163d8e1)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8185e6f9)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81889ca1)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff818d19bb)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818eb822)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81911abb)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/ipv6/route.c (ffffffff819207e1)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff81929ae9)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81944925)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81963299)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:295
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
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8116e565)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In drivers/connector/connector.c (ffffffff81678ef4)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff818aa2b7)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff818dd761)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81927eae)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81941789)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81968ee0)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/ipv6/route.c (ffffffff81978b27)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff81981c8a)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8199d643)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bcad6)
Location: include/net/netlink.h:295
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:295
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:295
Inline: True
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
Location: include/net/netlink.h:422
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8117c035)
Location: include/net/netlink.h:422
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In drivers/connector/connector.c (ffffffff81697fd4)
Location: include/net/netlink.h:422
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff818ce9a7)
Location: include/net/netlink.h:422
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8190a11e)
Location: include/net/netlink.h:422
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81957101)
Location: include/net/netlink.h:422
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81971e10)
Location: include/net/netlink.h:422
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8199e7c0)
Location: include/net/netlink.h:422
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/ipv6/route.c (ffffffff819ae7a7)
Location: include/net/netlink.h:422
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff819b8336)
Location: include/net/netlink.h:422
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d4189)
Location: include/net/netlink.h:422
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f3d28)
Location: include/net/netlink.h:422
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:422
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:422
Inline: True
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
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81188ec5)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In drivers/connector/connector.c (ffffffff816d0b54)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8191b7b7)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8196b525)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819bbb3b)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819ca19d)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffffffff819d3beb)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff819db6a5)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a0a8ef)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a1d033)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff81a26d8b)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a43032)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a63188)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
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
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81194e05)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In drivers/connector/connector.c (ffffffff816f4974)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8194ddf4)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81975cd7)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff819a1ed5)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819f283b)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a00d6d)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffffffff81a0a75b)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81a125be)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a4159f)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a53d03)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff81a5d7f1)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a79b92)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a99d38)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
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
In kernel/audit.c (ffffffff81187e02)
Location: include/net/netlink.h:535
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff811a9f95)
Location: include/net/netlink.h:535
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In drivers/connector/connector.c (ffffffff817acfa4)
Location: include/net/netlink.h:535
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81a1f97a)
Location: include/net/netlink.h:535
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81a4088a)
Location: include/net/netlink.h:535
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81a4ab2e)
Location: include/net/netlink.h:535
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a7aec7)
Location: include/net/netlink.h:535
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81a7b6f5)
Location: include/net/netlink.h:535
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ethtool/netlink.c (ffffffff81a86746)
Location: include/net/netlink.h:535
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81ae0a2b)
Location: include/net/netlink.h:535
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81aefdd0)
Location: include/net/netlink.h:535
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffffffff81afba0f)
Location: include/net/netlink.h:535
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81b048ef)
Location: include/net/netlink.h:535
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81b3703f)
Location: include/net/netlink.h:535
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b4b393)
Location: include/net/netlink.h:535
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81b53b06)
Location: include/net/netlink.h:535
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b744b4)
Location: include/net/netlink.h:535
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b957b8)
Location: include/net/netlink.h:535
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:535
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/net/netlink.h:535
Inline: True
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
In kernel/audit.c (ffffffff81185182)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff811a75b8)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In drivers/connector/connector.c (ffffffff817c1b34)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81a1f3da)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81a435aa)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81a5076e)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a83c87)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81a8573a)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
```
```
In net/ethtool/netlink.c (ffffffff81a90056)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81aed8ab)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81afcd10)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffffffff81b090df)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81b12a60)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81b45d6f)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b5a039)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81b620f6)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b83224)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba540b)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
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
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff811a7f98)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In drivers/connector/connector.c (ffffffff817a5052)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81a0647d)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81a2830a)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81a35703)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a6ce46)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81a6e7fa)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
```
```
In net/ethtool/netlink.c (ffffffff81a79767)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81ad908b)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae864e)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81aea935)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
```
In net/ipv4/nexthop.c (ffffffff81af727d)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81b00180)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81b33bdf)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b419c5)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81b50356)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b71ea5)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b94566)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
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
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff811d1d58)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In drivers/connector/connector.c (ffffffff818309d2)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81ab8afd)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81add0aa)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81aeb2d3)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81b264c6)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81b27e7a)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
```
```
In net/ethtool/netlink.c (ffffffff81b33ae8)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81b980eb)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba85dd)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81ba9cc6)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
```
In net/ipv4/nexthop.c (ffffffff81bb6c38)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81bc12b0)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81bfa24f)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c096f2)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81c17606)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c355)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60d46)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
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
In kernel/audit.c (ffffffff811e02f6)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81206578)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In drivers/connector/connector.c (ffffffff81971d68)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81c33b40)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81c5e8ea)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81c6db32)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81caf02e)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81cafbc5)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ethtool/netlink.c (ffffffff81cbf215)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81d29ecf)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3afe7)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81d3c8bd)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
```
In net/ipv4/nexthop.c (ffffffff81d4a89a)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81d55c7a)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81d9361b)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv6/route.c (ffffffff81da4880)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81db33f6)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81dda70f)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e032b6)
Location: include/net/netlink.h:550
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/net/netlink.h:550
Inline: True
```
```
In net/mctp/neigh.c (0)
Location: include/net/netlink.h:550
Inline: True
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
In kernel/audit.c (ffffffff81226086)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8124e888)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In drivers/connector/connector.c (ffffffff81adcfe8)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81de6f90)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81e1515a)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81e257a2)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e6c72a)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81e6d8e5)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ethtool/netlink.c (ffffffff81e7ddb5)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81ef198f)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81f03967)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81f0535d)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
```
In net/ipv4/nexthop.c (ffffffff81f13f5a)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81f1fffa)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81f61dab)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f73d20)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81f82d56)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81fad345)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd8236)
Location: include/net/netlink.h:565
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/net/netlink.h:565
Inline: True
```
```
In net/mctp/neigh.c (0)
Location: include/net/netlink.h:565
Inline: True
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
In kernel/audit.c (ffffffff8123c666)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81265c38)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In drivers/connector/connector.c (ffffffff81b2b258)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81e57f80)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/core/netdev-genl.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81e88a6a)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81e9ace2)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec878a)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81ec99f5)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ethtool/netlink.c (ffffffff81eda375)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81f51376)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81f63347)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81f64d5f)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
```
In net/ipv4/nexthop.c (ffffffff81f73c2a)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81f7fafa)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81fc1b86)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fd3e00)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81fe3056)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8200db05)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/devlink/leftover.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/devlink/dev.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/devlink/health.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053f06)
Location: include/net/netlink.h:566
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/mctp/neigh.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/handshake/netlink.c (0)
Location: include/net/netlink.h:566
Inline: True
```
```
In net/handshake/tlshd.c (0)
Location: include/net/netlink.h:566
Inline: True
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
In kernel/audit.c (ffffffff81256546)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8127faf8)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In drivers/regulator/event.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In drivers/connector/connector.c (ffffffff81b825ec)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In drivers/dpll/dpll_netlink.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81f172d0)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/core/netdev-genl.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/core/page_pool_user.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81f4aa7a)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81f5d438)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f8baa4)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81f8cac8)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ethtool/netlink.c (ffffffff81f9e146)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff820175f6)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff82029917)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff8202b32f)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
```
In net/ipv4/nexthop.c (ffffffff8203a41a)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff8204617a)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff8208f0f6)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/ipv6/route.c (ffffffff820a1710)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff820b0f76)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820dd585)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
```
In net/devlink/netlink.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/devlink/dev.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/devlink/port.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/devlink/sb.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/devlink/dpipe.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/devlink/resource.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/devlink/param.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/devlink/region.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/devlink/health.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/devlink/trap.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/devlink/rate.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/devlink/linecard.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff821266e6)
Location: include/net/netlink.h:573
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/mctp/neigh.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/handshake/netlink.c (0)
Location: include/net/netlink.h:573
Inline: True
```
```
In net/handshake/tlshd.c (0)
Location: include/net/netlink.h:573
Inline: True
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
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffff80001020d2e8)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In drivers/connector/connector.c (ffff8000108ddd58)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/rtnetlink.c (ffff800010befd3c)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/drop_monitor.c (ffff800010c1c194)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/genetlink.c (ffff800010c50b18)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/devinet.c (ffff800010ca8b00)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9360)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffff800010cc3d00)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffff800010ccb290)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffff800010d02fd0)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/route.c (ffff800010d17e18)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffff800010d22a8c)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/ip6mr.c (ffff800010d43ea8)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d697e8)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
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
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (c044bc64)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In drivers/connector/connector.c (c09ccdc0)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/rtnetlink.c (c0d0837c)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/drop_monitor.c (c0d33fb0)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/genetlink.c (c0d607cc)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/devinet.c (c0db5290)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/fib_semantics.c (c0dc4b00)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (c0dcf1ec)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (c0dd6bd4)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (c0e0a484)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/route.c (c0e1d9ec)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (c0e27030)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/ip6mr.c (c0e45c4c)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e67dd0)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
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
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (c00000000028b09c)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In drivers/connector/connector.c (c00000000097155c)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/rtnetlink.c (c000000000cd40b0)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/drop_monitor.c (c000000000d0ceb4)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/genetlink.c (c000000000d4f784)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/fib_semantics.c (c000000000dd20e0)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (c000000000ddfab4)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (c000000000dec42c)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/route.c (c000000000e45a78)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (c000000000e52754)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/ip6mr.c (c000000000e789fc)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea6678)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
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
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffe00016e402)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In drivers/connector/connector.c (ffffffe0005742ec)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/rtnetlink.c (ffffffe000771fbc)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/drop_monitor.c (ffffffe000796248)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/genetlink.c (ffffffe0007bbfde)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffe000810068)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffffffe000818eb6)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffe000821448)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/route.c (ffffffe00085cdba)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffe000864572)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffe00087ea08)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089c6f2)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
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
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8118d425)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In drivers/connector/connector.c (ffffffff816ba164)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff818eddc4)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81915ca7)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81941d45)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819925db)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819a0b0d)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffffffff819aa4fb)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff819b1e95)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff819e0c2f)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/route.c (ffffffff819f3393)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff819fce81)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a19222)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a390c8)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
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
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81180545)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In drivers/connector/connector.c (ffffffff81697da4)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_transport_fc.c (ffffffff8170f794)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_fc.c:fc_host_post_fc_event
```
```
In drivers/net/vxlan.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff818a7c04)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff818cfa57)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff818fb835)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8194c09b)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8195a5cd)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffffffff81963fbb)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff8196e4c5)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8199d9ef)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/route.c (ffffffff819b0153)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff819b9c41)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d5fe2)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f5ce8)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
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
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8118b1f5)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In drivers/connector/connector.c (ffffffff816e8634)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8193edf4)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81966cd7)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81992ed5)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/netfilter/nfnetlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netfilter/nfnetlink_queue.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netfilter/nfnetlink_log.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819af3cb)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819fce7b)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0b3ad)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffffffff81a14d9b)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81a1c735)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a4b6af)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a5de13)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff81a67901)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a83ca2)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa4f78)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
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
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81198b65)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In drivers/connector/connector.c (ffffffff81702d34)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81960651)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81988f67)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff819b59c5)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81a0720b)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a15b8d)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/nexthop.c (ffffffff81a1f7ab)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81a276e7)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a5761f)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a6a223)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff81a73ef0)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a905c7)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab12f8)
Location: include/net/netlink.h:483
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:483
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:483
Inline: True
```
</details>
</li>
</ul>

## Differences
