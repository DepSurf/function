# Function: <code>nlmsg_len</code>

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
In kernel/audit.c (ffffffff81122da9)
Location: include/net/netlink.h:301
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:301
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:301
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:301
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8172b91c)
Location: include/net/netlink.h:301
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:301
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:301
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:301
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:301
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:301
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:301
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: include/net/netlink.h:301
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:301
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:301
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:301
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:301
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:301
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:301
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:301
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
In kernel/audit.c (ffffffff8112b1b2)
Location: include/net/netlink.h:312
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/core/neighbour.c (ffffffff81790a0b)
Location: include/net/netlink.h:312
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff817946f5)
Location: include/net/netlink.h:312
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff8179efa2)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817b0539)
Location: include/net/netlink.h:312
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff817b316c)
Location: include/net/netlink.h:312
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817bac58)
Location: include/net/netlink.h:312
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff817bb5e7)
Location: include/net/netlink.h:312
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81807f1c)
Location: include/net/netlink.h:312
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/ipv6/route.c (ffffffff818470c8)
Location: include/net/netlink.h:312
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_dump_route
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/net/netlink.h:312
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
In kernel/audit.c (ffffffff8113506a)
Location: include/net/netlink.h:312
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/core/neighbour.c (ffffffff817be2b7)
Location: include/net/netlink.h:312
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff817c4eb7)
Location: include/net/netlink.h:312
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff817cd972)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817dfc79)
Location: include/net/netlink.h:312
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff817e29ec)
Location: include/net/netlink.h:312
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817ea5f8)
Location: include/net/netlink.h:312
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff817eafe9)
Location: include/net/netlink.h:312
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81838fec)
Location: include/net/netlink.h:312
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/ipv6/route.c (ffffffff81878f08)
Location: include/net/netlink.h:312
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_dump_route
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:312
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/net/netlink.h:312
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
In kernel/audit.c (ffffffff811362d0)
Location: include/net/netlink.h:316
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:316
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:316
Inline: True
```
```
In net/core/neighbour.c (ffffffff817dd57a)
Location: include/net/netlink.h:316
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff817e3924)
Location: include/net/netlink.h:316
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff817eccc2)
Location: include/net/netlink.h:316
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:316
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817ff139)
Location: include/net/netlink.h:316
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff81802301)
Location: include/net/netlink.h:316
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:316
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8180a469)
Location: include/net/netlink.h:316
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff8180af4f)
Location: include/net/netlink.h:316
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:316
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:316
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff8185a50c)
Location: include/net/netlink.h:316
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:316
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:316
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:316
Inline: True
```
```
In net/ipv6/route.c (ffffffff8189e14f)
Location: include/net/netlink.h:316
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_dump_route
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:316
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/net/netlink.h:316
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
In kernel/audit.c (ffffffff81143020)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/core/neighbour.c (ffffffff818578fa)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8185e864)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff81868eb2)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/sched/sch_api.c (ffffffff8187cdc9)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff81880723)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818892d5)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81889e9f)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff818da42c)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/ipv6/route.c (ffffffff8192072f)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_dump_route
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:322
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
In kernel/audit.c (ffffffff811519c1)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/core/neighbour.c (ffffffff818a2a76)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818aa404)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff818b8d4c)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818cf659)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff818d34d2)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818dcf0b)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff818ded34)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81930ed4)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/ipv6/route.c (ffffffff81978a7d)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_dump_route
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:322
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
In kernel/audit.c (ffffffff8115e676)
Location: include/net/netlink.h:449
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:449
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:449
Inline: True
```
```
In net/core/neighbour.c (ffffffff818c5c89)
Location: include/net/netlink.h:449
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818ceafa)
Location: include/net/netlink.h:449
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff818df99c)
Location: include/net/netlink.h:449
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:449
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818fa549)
Location: include/net/netlink.h:449
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff818ff912)
Location: include/net/netlink.h:449
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:449
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819098e1)
Location: include/net/netlink.h:449
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff8190b6f4)
Location: include/net/netlink.h:449
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:449
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:449
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff819607d1)
Location: include/net/netlink.h:449
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:449
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:449
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:449
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:449
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff819afed7)
Location: include/net/netlink.h:449
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:449
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:449
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
In kernel/audit.c (ffffffff8116ac8f)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/neighbour.c (ffffffff81911cd5)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8191706d)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff8192dfe6)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81959df9)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff81960182)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8196a9fd)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff8196c5dd)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff819c535e)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1e05e)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:510
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
In kernel/audit.c (ffffffff81176421)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/neighbour.c (ffffffff81944345)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff819496ad)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff81960276)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81990299)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff81997262)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819a148d)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff819a2f8d)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff819fbefe)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81a54cbe)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:510
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
In kernel/audit.c (ffffffff81188dea)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In drivers/connector/connector.c (ffffffff817ad27d)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/core/neighbour.c (ffffffff81a145a1)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81a1a8b1)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff81a33666)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81a67dd9)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff81a6f59f)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a7ae38)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81a7c081)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ethtool/debug.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ethtool/wol.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ethtool/features.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ethtool/privflags.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ethtool/cabletest.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeaaea)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b00596)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4c6fc)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/ipv6/ip6mr.c (ffffffff81b73438)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:562
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
In kernel/audit.c (ffffffff8118614a)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In drivers/connector/connector.c (ffffffff817c1e0d)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/core/neighbour.c (ffffffff81a148b1)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81a1aad2)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff81a359d6)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81a704d9)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff81a77f9f)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a83dc5)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81a850f3)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81af798a)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b0e616)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5b33c)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/ipv6/ip6mr.c (ffffffff81b82168)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:577
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
In kernel/audit.c (ffffffff81186fcf)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In drivers/connector/connector.c (ffffffff817a5213)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/core/neighbour.c (ffffffff819fb056)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81a01a12)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff81a1cb26)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81a58de4)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff81a60dbf)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a6cda9)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81a6e0d3)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae30ab)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81afc2f6)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b497ec)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/ipv6/ip6mr.c (ffffffff81b70d88)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:577
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
In kernel/audit.c (ffffffff811af42f)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In drivers/connector/connector.c (ffffffff81830b93)
Location: include/net/netlink.h:577
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8191aa79)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/core/neighbour.c (ffffffff81aace98)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81ab3e12)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff81ad0348)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81b11e24)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff81b19fcf)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81b26429)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81b27753)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba26db)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bbdb67)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81c10daa)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/ipv6/ip6mr.c (ffffffff81c3b79f)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:577
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
In kernel/audit.c (ffffffff811e1749)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In drivers/connector/connector.c (ffffffff81971f92)
Location: include/net/netlink.h:577
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6fecb)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/core/neighbour.c (ffffffff81c26088)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81c2d4df)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff81c4dbd7)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81c990fb)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff81ca11c0)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81caf197)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81cb06f9)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81d34ddb)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d5244d)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81dac17f)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/ipv6/ip6mr.c (ffffffff81dd98f5)
Location: include/net/netlink.h:577
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/net/netlink.h:577
Inline: True
```
```
In net/mctp/neigh.c (0)
Location: include/net/netlink.h:577
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
In kernel/audit.c (ffffffff812275e9)
Location: include/net/netlink.h:592
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In drivers/connector/connector.c (ffffffff81add232)
Location: include/net/netlink.h:592
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c02d5b)
Location: include/net/netlink.h:592
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:592
Inline: True
```
```
In net/core/neighbour.c (ffffffff81dd8498)
Location: include/net/netlink.h:592
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81de066f)
Location: include/net/netlink.h:592
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff81e02bb7)
Location: include/net/netlink.h:592
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:592
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81e54feb)
Location: include/net/netlink.h:592
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff81e5d230)
Location: include/net/netlink.h:592
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:592
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e6c98d)
Location: include/net/netlink.h:592
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81e6e4d9)
Location: include/net/netlink.h:592
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:592
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:592
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81efd2fb)
Location: include/net/netlink.h:592
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:592
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f1c70d)
Location: include/net/netlink.h:592
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:592
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:592
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:592
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7bb6f)
Location: include/net/netlink.h:592
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/ipv6/ip6mr.c (ffffffff81fab545)
Location: include/net/netlink.h:592
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:592
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:592
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:592
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/net/netlink.h:592
Inline: True
```
```
In net/mctp/neigh.c (0)
Location: include/net/netlink.h:592
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
In kernel/audit.c (ffffffff8123dc08)
Location: include/net/netlink.h:593
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In drivers/connector/connector.c (ffffffff81b2b4a2)
Location: include/net/netlink.h:593
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c6840b)
Location: include/net/netlink.h:593
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:593
Inline: True
```
```
In net/core/neighbour.c (ffffffff81e490b8)
Location: include/net/netlink.h:593
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81e51dff)
Location: include/net/netlink.h:593
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff81e75127)
Location: include/net/netlink.h:593
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:593
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81eb089b)
Location: include/net/netlink.h:593
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff81eb9de0)
Location: include/net/netlink.h:593
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:593
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec89ed)
Location: include/net/netlink.h:593
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81eca5f9)
Location: include/net/netlink.h:593
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:593
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:593
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5cd3b)
Location: include/net/netlink.h:593
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:593
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f7c1ed)
Location: include/net/netlink.h:593
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:593
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:593
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:593
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdbd8d)
Location: include/net/netlink.h:593
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/ipv6/ip6mr.c (ffffffff8200bce5)
Location: include/net/netlink.h:593
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:593
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:593
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:593
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/net/netlink.h:593
Inline: True
```
```
In net/mctp/neigh.c (0)
Location: include/net/netlink.h:593
Inline: True
```
```
In net/handshake/tlshd.c (ffffffff82093cf6)
Location: include/net/netlink.h:593
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_done
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
In kernel/audit.c (ffffffff81257b33)
Location: include/net/netlink.h:600
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In drivers/connector/connector.c (ffffffff81b82842)
Location: include/net/netlink.h:600
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:600
Inline: True
```
```
In net/core/neighbour.c (ffffffff81f07da8)
Location: include/net/netlink.h:600
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81f10edf)
Location: include/net/netlink.h:600
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff81f349c7)
Location: include/net/netlink.h:600
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:600
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81f7330b)
Location: include/net/netlink.h:600
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff81f7d050)
Location: include/net/netlink.h:600
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:600
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f8bc7c)
Location: include/net/netlink.h:600
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81f8cfb9)
Location: include/net/netlink.h:600
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:600
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:600
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff820232cb)
Location: include/net/netlink.h:600
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:600
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff820428dd)
Location: include/net/netlink.h:600
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:600
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:600
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:600
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff820a98bd)
Location: include/net/netlink.h:600
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/ipv6/ip6mr.c (ffffffff820dacb5)
Location: include/net/netlink.h:600
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:600
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:600
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:600
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/net/netlink.h:600
Inline: True
```
```
In net/mctp/neigh.c (0)
Location: include/net/netlink.h:600
Inline: True
```
```
In net/handshake/tlshd.c (ffffffff8216a618)
Location: include/net/netlink.h:600
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_done
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
In kernel/audit.c (ffff8000101eb4e4)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/neighbour.c (ffff800010be5820)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffff800010beb200)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffff800010c03af0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/sched/sch_api.c (ffff800010c3c8e4)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffff800010c443dc)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4fc70)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffff800010c511d8)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffff800010cb39f4)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffff800010d1a6a8)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:510
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
In kernel/audit.c (c042b150)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In drivers/connector/connector.c (c09ccb64)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/neighbour.c (c0cffb0c)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (c0d04c10)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (c0d1ce5c)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/sched/sch_api.c (c0d4e0dc)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (c0d54f40)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/netlink/af_netlink.c (c0d5fe34)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (c0d619e8)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/fib_frontend.c (c0dbf298)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/ipmr.c (c0dd92f0)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/ip6_fib.c (c0e1e7b4)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:510
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
In kernel/audit.c (c00000000025cb90)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/neighbour.c (c000000000cc91cc)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (c000000000cce5f0)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (c000000000ced3f8)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/sched/sch_api.c (c000000000d36698)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (c000000000d3f89c)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/netlink/af_netlink.c (c000000000d4e7ac)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (c000000000d51a3c)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/fib_frontend.c (c000000000dcb278)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/ip6_fib.c (c000000000e488ac)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:510
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
In kernel/audit.c (ffffffe00015fcf2)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/neighbour.c (ffffffe00076bd6e)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffe00076eba4)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffe000782b00)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/sched/sch_api.c (ffffffe0007ad2b8)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffe0007b279e)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffe0007bb7fa)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffe0007bc4f2)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b814)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffe00085de9a)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:510
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
In kernel/audit.c (ffffffff8116ea41)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/neighbour.c (ffffffff818e4315)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818e967d)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff81900246)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81930109)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff819370d2)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819412fd)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81942dfd)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff8199bc9e)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff819f434e)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:510
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
In kernel/audit.c (ffffffff81161be1)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/neighbour.c (ffffffff8189e155)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818a34bd)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff818ba076)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818e9c09)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff818f0bd2)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818faded)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff818fc8ed)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff8195575e)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff819b110e)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:510
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
In kernel/audit.c (ffffffff8116c811)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/neighbour.c (ffffffff81935345)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8193a6ad)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff81951276)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81981299)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff81988262)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8199248d)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81993f8d)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/netfilter/nfnetlink.c (ffffffff819983ab)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81a0653e)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5edce)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:510
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
In kernel/audit.c (ffffffff81179fe1)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/neighbour.c (ffffffff81956a55)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8195bedd)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/sock_diag.c (ffffffff81972c66)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/sched/sch_api.c (ffffffff819a3819)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/sched/cls_api.c (ffffffff819aa4d2)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819b4f7d)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff819b6a8d)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81a10bbe)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6b24e)
Location: include/net/netlink.h:510
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:510
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:510
Inline: True
```
</details>
</li>
</ul>

## Differences
