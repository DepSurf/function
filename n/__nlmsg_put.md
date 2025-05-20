# Function: <code>__nlmsg_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174a430)
Location: net/netlink/af_netlink.c:2759
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tc_dump_action
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
**Symbols:**

```
ffffffff8174a430-ffffffff8174a4b0: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817b74b0)
Location: net/netlink/af_netlink.c:2034
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb
```
**Symbols:**

```
ffffffff817b74b0-ffffffff817b7530: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e6f50)
Location: net/netlink/af_netlink.c:2051
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb
```
**Symbols:**

```
ffffffff817e6f50-ffffffff817e6fd0: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81806cb0)
Location: net/netlink/af_netlink.c:2102
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb
```
**Symbols:**

```
ffffffff81806cb0-ffffffff81806d30: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81885990)
Location: net/netlink/af_netlink.c:2115
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
**Symbols:**

```
ffffffff81885990-ffffffff81885a10: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818d9330)
Location: net/netlink/af_netlink.c:2156
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
**Symbols:**

```
ffffffff818d9330-ffffffff818d93b0: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81905b20)
Location: net/netlink/af_netlink.c:2165
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
**Symbols:**

```
ffffffff81905b20-ffffffff81905ba0: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81966d70)
Location: net/netlink/af_netlink.c:2165
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
**Symbols:**

```
ffffffff81966d70-ffffffff81966df2: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199d7f0)
Location: net/netlink/af_netlink.c:2166
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
**Symbols:**

```
ffffffff8199d7f0-ffffffff8199d872: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a7804a)
Location: net/netlink/af_netlink.c:2166
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
Direct callers:
  - kernel/audit.c:audit_buffer_alloc
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/dcb/dcbnl.c:dcbnl_newmsg
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
**Symbols:**

```
ffffffff81a767d0-ffffffff81a76854: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a804a8)
Location: net/netlink/af_netlink.c:2167
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump_done
Direct callers:
  - kernel/audit.c:audit_buffer_alloc
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/dcb/dcbnl.c:dcbnl_newmsg
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
**Symbols:**

```
ffffffff81a7f520-ffffffff81a7f5a4: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a69401)
Location: net/netlink/af_netlink.c:2177
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump_done
Direct callers:
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/dcb/dcbnl.c:dcbnl_newmsg
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
**Symbols:**

```
ffffffff81a68500-ffffffff81a6857f: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b229b1)
Location: net/netlink/af_netlink.c:2188
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump_done
Direct callers:
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/dcb/dcbnl.c:dcbnl_newmsg
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
**Symbols:**

```
ffffffff81b21a70-ffffffff81b21aef: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81cab566)
Location: net/netlink/af_netlink.c:2167
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump_done
Direct callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/dcb/dcbnl.c:dcbnl_newmsg
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/mctp/device.c:mctp_fill_addrinfo
  - net/mctp/neigh.c:mctp_rtm_getneigh
```
**Symbols:**

```
ffffffff81caa230-ffffffff81caa2c4: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e6c77d)
Location: net/netlink/af_netlink.c:2188
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
Direct callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/dcb/dcbnl.c:dcbnl_newmsg
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/mctp/device.c:mctp_fill_addrinfo
  - net/mctp/neigh.c:mctp_rtm_getneigh
```
**Symbols:**

```
ffffffff81e67310-ffffffff81e673a4: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec87dd)
Location: net/netlink/af_netlink.c:2159
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
Direct callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/devlink/leftover.c:devlink_nl_cmd_dpipe_entries_get
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/dcb/dcbnl.c:dcbnl_newmsg
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/mctp/device.c:mctp_fill_addrinfo
  - net/mctp/neigh.c:mctp_rtm_getneigh
```
**Symbols:**

```
ffffffff81ec3100-ffffffff81ec318e: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f8bae9)
Location: net/netlink/af_netlink.c:2154
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
Direct callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/devlink/dpipe.c:devlink_nl_dpipe_entries_get_doit
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/dcb/dcbnl.c:dcbnl_newmsg
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/mctp/device.c:mctp_fill_addrinfo
  - net/mctp/neigh.c:mctp_rtm_getneigh
```
**Symbols:**

```
ffffffff81f86450-ffffffff81f864de: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4acc8)
Location: net/netlink/af_netlink.c:2166
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
**Symbols:**

```
ffff800010c4acc8-ffff800010c4ad60: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5b870)
Location: net/netlink/af_netlink.c:2166
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
**Symbols:**

```
c0d5b870-c0d5b8d8: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d48df0)
Location: net/netlink/af_netlink.c:2166
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/dcb/dcbnl.c:dcbnl_newmsg
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
**Symbols:**

```
c000000000d48df0-c000000000d48eb8: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007b7fe6)
Location: net/netlink/af_netlink.c:2166
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
**Symbols:**

```
ffffffe0007b7fe6-ffffffe0007b8072: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8193d660)
Location: net/netlink/af_netlink.c:2166
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
**Symbols:**

```
ffffffff8193d660-ffffffff8193d6e2: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f7160)
Location: net/netlink/af_netlink.c:2166
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/scsi/scsi_transport_fc.c:fc_host_post_fc_event
  - drivers/net/vxlan.c:vxlan_fdb_info
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
**Symbols:**

```
ffffffff818f7160-ffffffff818f71e2: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8198e7f0)
Location: net/netlink/af_netlink.c:2166
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/genetlink.c:genlmsg_put
  - net/netfilter/nfnetlink_log.c:__build_packet_message
  - net/netfilter/nfnetlink_log.c:__nfulnl_send
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_stat_cpu_dump
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_expect_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_stat_ct
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_ct_stat_cpu_dump
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
**Symbols:**

```
ffffffff8198e7f0-ffffffff8198e872: __nlmsg_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct nlmsghdr *__nlmsg_put(struct sk_buff *skb, u32 portid, u32 seq, int type, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b10a0)
Location: net/netlink/af_netlink.c:2166
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/genetlink.c:genlmsg_put
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
**Symbols:**

```
ffffffff819b10a0-ffffffff819b1122: __nlmsg_put (STB_GLOBAL)
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
