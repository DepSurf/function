# Function: <code>nlmsg_data</code>

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
In kernel/audit.c (ffffffff81122d7b)
Location: include/net/netlink.h:292
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In drivers/connector/connector.c (ffffffff81541bdf)
Location: include/net/netlink.h:292
Inline: True
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8172c66b)
Location: include/net/netlink.h:292
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_fdb_del
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81739d84)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817436f1)
Location: include/net/netlink.h:292
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:292
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:292
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
In kernel/audit.c (ffffffff8112ad36)
Location: include/net/netlink.h:303
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_printk_skb
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In drivers/connector/connector.c (ffffffff81593760)
Location: include/net/netlink.h:303
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81796f20)
Location: include/net/netlink.h:303
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/core/fib_rules.c (ffffffff817a6c02)
Location: include/net/netlink.h:303
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff817b0591)
Location: include/net/netlink.h:303
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff817bb623)
Location: include/net/netlink.h:303
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/ipv6/route.c (ffffffff81842545)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/net/netlink.h:303
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
In kernel/audit.c (ffffffff81134a48)
Location: include/net/netlink.h:303
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In drivers/connector/connector.c (ffffffff815c1020)
Location: include/net/netlink.h:303
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff817c4100)
Location: include/net/netlink.h:303
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/core/fib_rules.c (ffffffff817d570b)
Location: include/net/netlink.h:303
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff817dfcd1)
Location: include/net/netlink.h:303
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff817eb025)
Location: include/net/netlink.h:303
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/ipv6/route.c (ffffffff8187429d)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:303
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/net/netlink.h:303
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
In kernel/audit.c (ffffffff81135e41)
Location: include/net/netlink.h:307
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:307
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:307
Inline: True
```
```
In drivers/connector/connector.c (ffffffff815d6b6d)
Location: include/net/netlink.h:307
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:307
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:307
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:307
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff817e2e5c)
Location: include/net/netlink.h:307
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:307
Inline: True
```
```
In net/core/fib_rules.c (ffffffff817f4cc5)
Location: include/net/netlink.h:307
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff817ff18c)
Location: include/net/netlink.h:307
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:307
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:307
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:307
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8180af92)
Location: include/net/netlink.h:307
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:307
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:307
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:307
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:307
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8186a226)
Location: include/net/netlink.h:307
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:307
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:307
Inline: True
```
```
In net/ipv6/route.c (ffffffff818990db)
Location: include/net/netlink.h:307
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:307
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff818c1ce6)
Location: include/net/netlink.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:307
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:307
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/net/netlink.h:307
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
In kernel/audit.c (ffffffff81142b91)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In drivers/connector/connector.c (ffffffff8163d94d)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8185ddbf)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/core/fib_rules.c (ffffffff818704bf)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff8187ce1c)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81889ee2)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818ea9a6)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/ipv6/route.c (ffffffff8191a3e1)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81945626)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:313
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
In kernel/audit.c (ffffffff8115156c)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In drivers/connector/connector.c (ffffffff81678f50)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff818a98a6)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/core/fib_rules.c (ffffffff818c190f)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff818cf659)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffffffff818d315a)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff818ded7d)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff818e6e9e)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819418ed)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/ipv6/route.c (ffffffff81971fdf)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8199d11a)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:313
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff819d1a50)
Location: include/net/netlink.h:313
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In kernel/audit.c (ffffffff8115e21c)
Location: include/net/netlink.h:440
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:440
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:440
Inline: True
```
```
In drivers/connector/connector.c (ffffffff8169802d)
Location: include/net/netlink.h:440
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:440
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:440
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:440
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff818cd416)
Location: include/net/netlink.h:440
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:440
Inline: True
```
```
In net/core/fib_rules.c (ffffffff818ea72f)
Location: include/net/netlink.h:440
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff818fa549)
Location: include/net/netlink.h:440
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffffffff818fe5a7)
Location: include/net/netlink.h:440
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:440
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:440
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8190b73d)
Location: include/net/netlink.h:440
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff81913d7a)
Location: include/net/netlink.h:440
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:440
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:440
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:440
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8197119e)
Location: include/net/netlink.h:440
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:440
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:440
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a772c)
Location: include/net/netlink.h:440
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:440
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:440
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d3c77)
Location: include/net/netlink.h:440
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:440
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:440
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:440
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81a0b950)
Location: include/net/netlink.h:440
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In kernel/audit.c (ffffffff8116a579)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In drivers/connector/connector.c (ffffffff816d0ba5)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8191a0f9)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/fib_rules.c (ffffffff8193a1af)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81959df9)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffffffff8195f2aa)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8196c4ef)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff81971051)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff819c53b2)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819da91e)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a13d81)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a41ef7)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81a7b330)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In kernel/audit.c (ffffffff8117641d)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In drivers/connector/connector.c (ffffffff816f49c5)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8194c719)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/fib_rules.c (ffffffff8196d06f)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81990299)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffffffff8199568a)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff819a2e9f)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff819a7a51)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff819fbf52)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a11805)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a4a971)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a78b57)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81ab2690)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In kernel/audit.c (ffffffff81188de6)
Location: include/net/netlink.h:553
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff815ecd90)
Location: include/net/netlink.h:553
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
```
In drivers/connector/connector.c (ffffffff817ad158)
Location: include/net/netlink.h:553
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_call_callback
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81a1e367)
Location: include/net/netlink.h:553
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81a4037f)
Location: include/net/netlink.h:553
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81a67dd9)
Location: include/net/netlink.h:553
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a6d606)
Location: include/net/netlink.h:553
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81a7c1fc)
Location: include/net/netlink.h:553
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ethtool/debug.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ethtool/wol.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ethtool/features.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ethtool/privflags.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ethtool/cabletest.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a911c0)
Location: include/net/netlink.h:553
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeab25)
Location: include/net/netlink.h:553
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b04a69)
Location: include/net/netlink.h:553
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b44ed1)
Location: include/net/netlink.h:553
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b740f7)
Location: include/net/netlink.h:553
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:553
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:553
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
In kernel/audit.c (ffffffff81186146)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81611570)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
```
In drivers/connector/connector.c (ffffffff817c1ce8)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_call_callback
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81a1e69a)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81a4307f)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81a704d9)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a75fb0)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81a851d9)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg_doit
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a9b021)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81af79c5)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b12bd9)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b53851)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b82e67)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:568
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
In kernel/audit.c (ffffffff81186fcb)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff815f4b00)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
```
In drivers/connector/connector.c (ffffffff817a50a5)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81a0542a)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81a27ddf)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81a58ddc)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a5e010)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81a6e1c9)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg_doit
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a86441)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae30e1)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b00937)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b40e15)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b71af7)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:568
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
In kernel/audit.c (ffffffff811af42b)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:kauditd_hold_skb
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81661ed0)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
```
In drivers/connector/connector.c (ffffffff81830a25)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81ab786a)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81adcb7f)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81b11e1c)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffffffff81b171d0)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81b27849)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg_doit
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv4/route.c (ffffffff81b40b81)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba2711)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bc1e16)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c08ae5)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81c3bfa7)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:568
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
In kernel/audit.c (ffffffff811e1744)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:kauditd_hold_skb
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff8177bbf0)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
```
In drivers/connector/connector.c (ffffffff81971db6)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81c3136e)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81c5e0fe)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81c990ec)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffffffff81c9ed90)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81cb0835)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg_doit
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv4/route.c (ffffffff81ccd656)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81d34e11)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d5615b)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv6/route.c (ffffffff81da35ce)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81dda314)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/mctp/route.c (ffffffff81e396db)
Location: include/net/netlink.h:568
Inline: True
```
```
In net/mctp/neigh.c (0)
Location: include/net/netlink.h:568
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
In kernel/audit.c (ffffffff812275e4)
Location: include/net/netlink.h:583
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:kauditd_hold_skb
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In drivers/connector/connector.c (ffffffff81add036)
Location: include/net/netlink.h:583
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81de46ee)
Location: include/net/netlink.h:583
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81e1491e)
Location: include/net/netlink.h:583
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81e54fdc)
Location: include/net/netlink.h:583
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffffffff81e5d830)
Location: include/net/netlink.h:583
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e6c98d)
Location: include/net/netlink.h:583
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81e6e79a)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/ipv4/route.c (ffffffff81e8d7a6)
Location: include/net/netlink.h:583
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81efd331)
Location: include/net/netlink.h:583
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f201bb)
Location: include/net/netlink.h:583
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f72a0e)
Location: include/net/netlink.h:583
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81fabfe4)
Location: include/net/netlink.h:583
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/mctp/route.c (ffffffff8201278b)
Location: include/net/netlink.h:583
Inline: True
```
```
In net/mctp/neigh.c (0)
Location: include/net/netlink.h:583
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff82024e60)
Location: include/net/netlink.h:583
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In kernel/audit.c (ffffffff8123dc04)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:kauditd_hold_skb
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In drivers/connector/connector.c (ffffffff81b2b2a6)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81e560fe)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81e88233)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81eb088c)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec89ed)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81eca72a)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5cd71)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f7fcbb)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fd2b01)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8200c784)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/mctp/route.c (ffffffff8208f57b)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/mctp/neigh.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In net/handshake/tlshd.c (0)
Location: include/net/netlink.h:584
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff820a4f70)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In kernel/audit.c (ffffffff81257b2f)
Location: include/net/netlink.h:591
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:kauditd_hold_skb
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In drivers/connector/connector.c (ffffffff81b8263a)
Location: include/net/netlink.h:591
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81f15488)
Location: include/net/netlink.h:591
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81f4a243)
Location: include/net/netlink.h:591
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81f732fc)
Location: include/net/netlink.h:591
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f8bc7c)
Location: include/net/netlink.h:591
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81f8d103)
Location: include/net/netlink.h:591
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg_doit
  - net/netlink/genetlink.c:genl_start
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff82023301)
Location: include/net/netlink.h:591
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8204633b)
Location: include/net/netlink.h:591
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/ipv6/route.c (ffffffff820a0411)
Location: include/net/netlink.h:591
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820db754)
Location: include/net/netlink.h:591
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/mctp/route.c (ffffffff82165a5b)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/mctp/neigh.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In net/handshake/tlshd.c (0)
Location: include/net/netlink.h:591
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff8217d0d0)
Location: include/net/netlink.h:591
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In drivers/connector/connector.c (ffff8000108ddd90)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/rtnetlink.c (ffff800010bee860)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/fib_rules.c (ffff800010c1381c)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/sched/sch_api.c (ffff800010c3c8e4)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffff800010c42318)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/genetlink.c (ffff800010c5108c)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffff800010c57310)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffff800010cb3a44)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010cc9efc)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/route.c (ffff800010d0da64)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ip6mr.c (ffff800010d422f4)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In lib/kobject_uevent.c (ffff800010d8c9e4)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In kernel/audit.c (c042b14c)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In drivers/connector/connector.c (c09cce0c)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/rtnetlink.c (c0d06d1c)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/fib_rules.c (c0d2a6a4)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/sched/sch_api.c (c0d4e0dc)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (c0d552c8)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/genetlink.c (c0d618dc)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (c0d66f90)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/ipmr.c (c0dd5e8c)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/route.c (c0e142f0)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ip6mr.c (c0e44c14)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In lib/kobject_uevent.c (c0e86dc0)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In drivers/connector/connector.c (c0000000009715b8)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/rtnetlink.c (c000000000cd2484)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/fib_rules.c (c000000000d00b70)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/sched/sch_api.c (c000000000d36698)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (c000000000d3fdc4)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/genetlink.c (c000000000d518e8)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (c000000000d588ac)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/fib_frontend.c (c000000000dcb2e4)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000de9358)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/route.c (c000000000e39860)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ip6mr.c (c000000000e770c4)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In lib/kobject_uevent.c (c000000000ecdb10)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In drivers/connector/connector.c (ffffffe000574338)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/rtnetlink.c (ffffffe000770ffe)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/fib_rules.c (ffffffe00078f012)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/sched/sch_api.c (ffffffe0007ad2b8)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffffffe0007b2a28)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffe0007b8ff4)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffe0007bc434)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffe0007c1666)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b84c)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe00081f3de)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/route.c (ffffffe000855714)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffe00087d9a2)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In lib/kobject_uevent.c (ffffffe0008b5096)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In kernel/audit.c (ffffffff8116ea3d)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In drivers/connector/connector.c (ffffffff816ba1b5)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff818ec6e9)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/fib_rules.c (ffffffff8190d03f)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81930109)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffffffff819354fa)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81942d0f)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff819478c1)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff8199bcf2)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819b112e)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/route.c (ffffffff819ea001)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a181e7)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81a514e0)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In kernel/audit.c (ffffffff81161bdd)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In drivers/connector/connector.c (ffffffff81697df5)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In drivers/scsi/scsi_transport_fc.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In drivers/net/vxlan.c (ffffffff8176cd69)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fdb_info
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff818a6529)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/fib_rules.c (ffffffff818c6dff)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818e9c09)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffffffff818eeffa)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff818fc7ff)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff819013b1)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff819557b2)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196d75e)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a6dc1)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d4fa7)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81a0e5e0)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In kernel/audit.c (ffffffff8116c80d)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In drivers/connector/connector.c (ffffffff816e8685)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8193d719)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/fib_rules.c (ffffffff8195e06f)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81981299)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffffffff8198668a)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81993e9f)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/netfilter/nfnetlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netfilter/nfnetlink_queue.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netfilter/nfnetlink_log.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netfilter/nf_conntrack_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/route.c (ffffffff819b2091)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81a06592)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1b9ce)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a54a81)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a82c67)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81abd8d0)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In kernel/audit.c (ffffffff81179fdd)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In drivers/connector/connector.c (ffffffff81702d85)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8195efa9)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/fib_rules.c (ffffffff819802bf)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/drop_monitor.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/sched/sch_api.c (ffffffff819a3819)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffffffff819aa8ea)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff819b699f)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff819bb751)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81a10c12)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a26915)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a60a71)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a8f537)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:501
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81ac9d50)
Location: include/net/netlink.h:501
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
</details>
</li>
</ul>

## Differences
