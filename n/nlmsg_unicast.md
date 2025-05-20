# Function: <code>nlmsg_unicast</code>

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
In kernel/taskstats.c (ffffffff8113e1bd)
Location: include/net/netlink.h:578
Inline: True
Inline callers:
  - kernel/taskstats.c:send_reply
  - kernel/taskstats.c:taskstats_exit
```
```
In net/core/rtnetlink.c (ffffffff8172a079)
Location: include/net/netlink.h:578
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/netlink/af_netlink.c (ffffffff8174eebe)
Location: include/net/netlink.h:578
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff8175012c)
Location: include/net/netlink.h:578
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/tcp_metrics.c (ffffffff81781757)
Location: include/net/netlink.h:578
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180d489)
Location: include/net/netlink.h:578
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180e5f0)
Location: include/net/netlink.h:578
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818101ce)
Location: include/net/netlink.h:578
Inline: True
Inline callers:
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
In kernel/taskstats.c (ffffffff8114741c)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In net/core/rtnetlink.c (ffffffff8179675c)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/netlink/af_netlink.c (ffffffff817bae8e)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff817bc109)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/tcp_metrics.c (ffffffff817eec14)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8187f87a)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81880c71)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8188289e)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818835c6)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
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
In kernel/taskstats.c (ffffffff811512bc)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In net/core/rtnetlink.c (ffffffff817c4db9)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/netlink/af_netlink.c (ffffffff817ea82e)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff817ebb0b)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f624)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/seg6.c (ffffffff81899cd4)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b412a)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b5521)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b714e)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b7e66)
Location: include/net/netlink.h:589
Inline: True
Inline callers:
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
In kernel/taskstats.c (ffffffff8115392b)
Location: include/net/netlink.h:598
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In net/core/rtnetlink.c (ffffffff817e3846)
Location: include/net/netlink.h:598
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/netlink/af_netlink.c (ffffffff8180a78e)
Location: include/net/netlink.h:598
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff8180ba70)
Location: include/net/netlink.h:598
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/tcp_metrics.c (ffffffff8184032e)
Location: include/net/netlink.h:598
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/seg6.c (ffffffff818bfec4)
Location: include/net/netlink.h:598
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818daada)
Location: include/net/netlink.h:598
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dbe75)
Location: include/net/netlink.h:598
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818dda04)
Location: include/net/netlink.h:598
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818de73e)
Location: include/net/netlink.h:598
Inline: True
Inline callers:
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
In kernel/taskstats.c (ffffffff8116012b)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In net/core/rtnetlink.c (ffffffff8185e77f)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/netlink/af_netlink.c (ffffffff818896c8)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff8188aa04)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf6ce)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/seg6.c (ffffffff81942f94)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819606ba)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81961a55)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819635f4)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8196434a)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
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
In kernel/taskstats.c (ffffffff8116f063)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In net/core/rtnetlink.c (ffffffff818aa33a)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/netlink/af_netlink.c (ffffffff818dd14d)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff818de035)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/tcp_metrics.c (ffffffff819152cf)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/seg6.c (ffffffff8199b886)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819b9e90)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bb1db)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bcebf)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bdc06)
Location: include/net/netlink.h:604
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819cb321)
Location: include/net/netlink.h:604
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
In kernel/taskstats.c (ffffffff8117cb63)
Location: include/net/netlink.h:747
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In net/core/rtnetlink.c (ffffffff818cea2a)
Location: include/net/netlink.h:747
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/netlink/af_netlink.c (ffffffff81909af3)
Location: include/net/netlink.h:747
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff8190a9f5)
Location: include/net/netlink.h:747
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/tcp_metrics.c (ffffffff819438ef)
Location: include/net/netlink.h:747
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/seg6.c (ffffffff819d2256)
Location: include/net/netlink.h:747
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f1160)
Location: include/net/netlink.h:747
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f244b)
Location: include/net/netlink.h:747
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f410e)
Location: include/net/netlink.h:747
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4da6)
Location: include/net/netlink.h:747
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a042bb)
Location: include/net/netlink.h:747
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
In kernel/taskstats.c (ffffffff81189a14)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In net/core/rtnetlink.c (ffffffff8191b83a)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/devlink.c (ffffffff8194f003)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
```
```
In net/netlink/af_netlink.c (ffffffff8196ae02)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff8196bdf6)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7ec2)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/seg6.c (ffffffff81a41085)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a6041f)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a6179c)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a63580)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a64265)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a73563)
Location: include/net/netlink.h:981
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
In kernel/taskstats.c (ffffffff81195957)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In net/core/rtnetlink.c (ffffffff8194de71)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/drop_monitor.c (ffffffff8197657e)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff819837bc)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
```
```
In net/netlink/af_netlink.c (ffffffff819a18a2)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff819a27a6)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/tcp_metrics.c (ffffffff819def55)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/seg6.c (ffffffff81a77d05)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a9704f)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a9836c)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a9a130)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9ade5)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa9d53)
Location: include/net/netlink.h:981
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
In kernel/taskstats.c (ffffffff811aa981)
Location: include/net/netlink.h:1033
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:send_cpu_listeners
```
```
In net/core/rtnetlink.c (ffffffff81a1f9f7)
Location: include/net/netlink.h:1033
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/drop_monitor.c (ffffffff81a4b31e)
Location: include/net/netlink.h:1033
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff81a5f9a0)
Location: include/net/netlink.h:1033
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
```
```
In net/netlink/af_netlink.c (ffffffff81a7b234)
Location: include/net/netlink.h:1033
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff81a7d650)
Location: include/net/netlink.h:1033
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81a864be)
Location: include/net/netlink.h:1033
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81a89fa5)
Location: include/net/netlink.h:1033
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acc541)
Location: include/net/netlink.h:1033
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/seg6.c (ffffffff81b72285)
Location: include/net/netlink.h:1033
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b928cf)
Location: include/net/netlink.h:1033
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93bdc)
Location: include/net/netlink.h:1033
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b95ba6)
Location: include/net/netlink.h:1033
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b965b3)
Location: include/net/netlink.h:1033
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5f53)
Location: include/net/netlink.h:1033
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb36ae)
Location: include/net/netlink.h:1033
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
In kernel/taskstats.c (ffffffff811a7f31)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:send_cpu_listeners
```
```
In drivers/thermal/thermal_netlink.c (ffffffff8195f759)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
```
```
In net/core/rtnetlink.c (ffffffff81a1f457)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/drop_monitor.c (ffffffff81a50f4e)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff81a68190)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
```
```
In net/netlink/af_netlink.c (ffffffff81a840b4)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff81a86210)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81a8fd9e)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81a93875)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/tunnels.c (ffffffff81a975c5)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad8514)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/seg6.c (ffffffff81b80fea)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba251f)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba381c)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba5813)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba6223)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb5433)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7d93)
Location: include/net/netlink.h:1046
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
In kernel/taskstats.c (ffffffff811a8cf4)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81942cb9)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
```
```
In net/core/rtnetlink.c (ffffffff81a064fc)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/drop_monitor.c (ffffffff81a35ea2)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff81a43294)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
```
```
In net/netlink/af_netlink.c (ffffffff81a6d201)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff81a6ef20)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81a794d8)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81a7d295)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/tunnels.c (ffffffff81a80fc7)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac32a9)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/seg6.c (ffffffff81b6fbf7)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b915ff)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b9293b)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b9498b)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b9539d)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba4433)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb9510)
Location: include/net/netlink.h:1046
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
In kernel/taskstats.c (ffffffff811d2840)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In drivers/thermal/thermal_netlink.c (ffffffff819e7788)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
```
```
In net/core/rtnetlink.c (ffffffff81ab8b7c)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/drop_monitor.c (ffffffff81aeba94)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff81af9774)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
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
```
```
In net/netlink/af_netlink.c (ffffffff81b26873)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81b28960)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81b337d3)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81b37475)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/tunnels.c (ffffffff81b3ad0c)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b81209)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba273b)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv6/seg6.c (ffffffff81c37d47)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5dd9f)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f0db)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c61185)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61bcd)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c71fc3)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81c88be0)
Location: include/net/netlink.h:1046
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
In kernel/taskstats.c (ffffffff812070d6)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81b4d039)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
```
```
In net/core/rtnetlink.c (ffffffff81c33f72)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/drop_monitor.c (ffffffff81c6e3c3)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff81c7c4a8)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_linecard_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_doit
```
```
In net/netlink/af_netlink.c (ffffffff81caf55b)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81cb1c08)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81cbee94)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81cc2e6d)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/tunnels.c (ffffffff81cc6c83)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d1158e)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/fib_frontend.c (ffffffff81d34e3b)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv6/seg6.c (ffffffff81dd5911)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00077)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e0148c)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e03718)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e041cd)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e15b41)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2f0aa)
Location: include/net/netlink.h:1046
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
In kernel/taskstats.c (ffffffff8124f446)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81ce4d39)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
```
```
In net/core/rtnetlink.c (ffffffff81de73e2)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/drop_monitor.c (ffffffff81e2604c)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff81e40d88)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_cmd_selftests_get_doit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_linecard_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_doit
```
```
In net/netlink/af_netlink.c (ffffffff81e6cb6b)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81e6fa58)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81e7d9e3)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81e8215d)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/tunnels.c (ffffffff81e862b3)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed733e)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/fib_frontend.c (ffffffff81efd35b)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv6/seg6.c (ffffffff81fa70b1)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd4e97)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd62dc)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd8698)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd919d)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81fecaf1)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff8200779a)
Location: include/net/netlink.h:1095
Inline: True
Inline callers:
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
In kernel/taskstats.c (ffffffff812667f6)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81d4d309)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
```
```
In net/core/rtnetlink.c (ffffffff81e583d2)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/netdev-genl.c (ffffffff81e7d15d)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
```
```
In net/core/drop_monitor.c (ffffffff81e9b5ec)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/netlink/af_netlink.c (ffffffff81ec8be8)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81ecbed8)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81ed9fa3)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81ede7bd)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/tunnels.c (ffffffff81ee2c62)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f363d3)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5cd9b)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv6/seg6.c (ffffffff82007911)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/devlink/leftover.c (ffffffff82037a38)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_trap_policer_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_group_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
  - net/devlink/leftover.c:devlink_nl_cmd_region_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_param_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_dpipe_entries_get
  - net/devlink/leftover.c:devlink_dpipe_send_and_alloc_skb
  - net/devlink/leftover.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_pool_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_linecard_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_port_new_doit
  - net/devlink/leftover.c:devlink_nl_cmd_port_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_rate_get_doit
```
```
In net/devlink/dev.c (ffffffff820459fc)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_cmd_selftests_get_doit
  - net/devlink/dev.c:devlink_nl_cmd_info_get_doit
  - net/devlink/dev.c:devlink_nl_cmd_eswitch_get_doit
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_cmd_get_doit
```
```
In net/devlink/health.c (ffffffff82047f1d)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_get_doit
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82050b37)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82051f9c)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8205436d)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82054e6d)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82068d91)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff82083b3a)
Location: include/net/netlink.h:1096
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
```
In net/handshake/tlshd.c (ffffffff82094033)
Location: include/net/netlink.h:1096
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
In kernel/taskstats.c (ffffffff812806e6)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81e03df9)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81ebb75a)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_id_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_id_get_doit
```
```
In net/core/rtnetlink.c (ffffffff81f17722)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/netdev-genl.c (ffffffff81f3e064)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_queue_get_doit
  - net/core/netdev-genl.c:netdev_nl_napi_get_doit
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
```
```
In net/core/page_pool_user.c (ffffffff81f4517f)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/core/page_pool_user.c:netdev_nl_page_pool_get_do
```
```
In net/core/drop_monitor.c (ffffffff81f5dd5c)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/netlink/af_netlink.c (ffffffff81f8be6f)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81f8f3f8)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81f9dd29)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81fa25ed)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/tunnels.c (ffffffff81fa6af2)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffc673)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/fib_frontend.c (ffffffff8202332b)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv6/seg6.c (ffffffff820d67a1)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/devlink/netlink.c (ffffffff821017e5)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_msg_reply_and_new
```
```
In net/devlink/dev.c (ffffffff8210533f)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_get_doit
  - net/devlink/dev.c:devlink_nl_info_get_doit
  - net/devlink/dev.c:devlink_nl_eswitch_get_doit
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_get_doit
```
```
In net/devlink/port.c (ffffffff821080c1)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_new_doit
  - net/devlink/port.c:devlink_nl_port_get_doit
```
```
In net/devlink/sb.c (ffffffff82109ff1)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_get_doit
  - net/devlink/sb.c:devlink_nl_sb_port_pool_get_doit
  - net/devlink/sb.c:devlink_nl_sb_pool_get_doit
  - net/devlink/sb.c:devlink_nl_sb_get_doit
```
```
In net/devlink/dpipe.c (ffffffff8210c013)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devlink_nl_dpipe_entries_get_doit
  - net/devlink/dpipe.c:devlink_dpipe_send_and_alloc_skb
```
```
In net/devlink/resource.c (ffffffff8210c997)
Location: include/net/netlink.h:1140
Inline: True
```
```
In net/devlink/param.c (ffffffff8210f09c)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/devlink/param.c:devlink_nl_param_get_doit
```
```
In net/devlink/region.c (ffffffff82110df2)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_new_doit
  - net/devlink/region.c:devlink_nl_region_get_doit
```
```
In net/devlink/health.c (ffffffff82113f6d)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_get_doit
```
```
In net/devlink/trap.c (ffffffff82117638)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_get_doit
  - net/devlink/trap.c:devlink_nl_trap_group_get_doit
  - net/devlink/trap.c:devlink_nl_trap_get_doit
```
```
In net/devlink/rate.c (ffffffff82119210)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/devlink/rate.c:devlink_nl_rate_get_doit
```
```
In net/devlink/linecard.c (ffffffff8211a67f)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/devlink/linecard.c:devlink_nl_linecard_get_doit
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff821231e7)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8212477c)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82126b4d)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8212774d)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213c011)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff8215c2aa)
Location: include/net/netlink.h:1140
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_limits_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_doit
```
```
In net/handshake/tlshd.c (ffffffff8216a953)
Location: include/net/netlink.h:1140
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
In kernel/taskstats.c (ffff80001020dbd0)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In net/core/rtnetlink.c (ffff800010befdcc)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/drop_monitor.c (ffff800010c1ca40)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffff800010c2bdf0)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
```
```
In net/netlink/af_netlink.c (ffff800010c4fee8)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffff800010c51a60)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/tcp_metrics.c (ffff800010c92148)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/seg6.c (ffff800010d41320)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d66620)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d67a34)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d69be8)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6a9c4)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7da14)
Location: include/net/netlink.h:981
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
In kernel/taskstats.c (c044c5b8)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In net/core/rtnetlink.c (c0d08404)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/drop_monitor.c (c0d34984)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (c0d4298c)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
```
```
In net/netlink/af_netlink.c (c0d600fc)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (c0d61160)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/tcp_metrics.c (c0da0e54)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/seg6.c (c0e43d30)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (c0e64e48)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (c0e663c8)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e6817c)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (c0e68f60)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (c0e78564)
Location: include/net/netlink.h:981
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
In kernel/taskstats.c (c00000000028bc88)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In net/core/rtnetlink.c (c000000000cd4160)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/drop_monitor.c (c000000000d0da44)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (c000000000d22764)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
```
```
In net/netlink/af_netlink.c (c000000000d4eafc)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (c000000000d50494)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/tcp_metrics.c (c000000000da292c)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/seg6.c (c000000000e75c10)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea27c0)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea4334)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea6b18)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea7dac)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebd564)
Location: include/net/netlink.h:981
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
In kernel/taskstats.c (ffffffe00016eade)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In net/core/rtnetlink.c (ffffffe00077202a)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/drop_monitor.c (ffffffe00079690c)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffe0007a348a)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
```
```
In net/netlink/af_netlink.c (ffffffe0007bb9d2)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffe0007bcb84)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f20dc)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/seg6.c (ffffffe00087ca64)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a0ea)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089b02a)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089ca1c)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d500)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008ab21e)
Location: include/net/netlink.h:981
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
In kernel/taskstats.c (ffffffff8118df77)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In net/core/rtnetlink.c (ffffffff818ede41)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/drop_monitor.c (ffffffff8191654e)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff8192362c)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
```
```
In net/netlink/af_netlink.c (ffffffff81941712)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff81942616)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197edc5)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/seg6.c (ffffffff81a17395)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a363df)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a376fc)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a394c0)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a3a175)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a490e3)
Location: include/net/netlink.h:981
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
In kernel/taskstats.c (ffffffff81181087)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In net/core/rtnetlink.c (ffffffff818a7c81)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/drop_monitor.c (ffffffff818d02fe)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff818dd3dc)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
```
```
In net/netlink/af_netlink.c (ffffffff818fb202)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff818fc106)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938885)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/seg6.c (ffffffff819d4155)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f2fff)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f431c)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f60e0)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6d95)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a05cd3)
Location: include/net/netlink.h:981
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
In kernel/taskstats.c (ffffffff8118bd47)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In net/core/rtnetlink.c (ffffffff8193ee71)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/drop_monitor.c (ffffffff8196757e)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff819747bc)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
```
```
In net/netlink/af_netlink.c (ffffffff819928a2)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff819937a6)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9595)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/seg6.c (ffffffff81a81e15)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa228f)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa35ac)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa5370)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa6025)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4f93)
Location: include/net/netlink.h:981
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
In kernel/taskstats.c (ffffffff811996c4)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In net/core/rtnetlink.c (ffffffff8196072f)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/drop_monitor.c (ffffffff8198980e)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff81996cac)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
```
```
In net/netlink/af_netlink.c (ffffffff819b5392)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff819b6296)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f330a)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv6/seg6.c (ffffffff81a8e71f)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aae5ff)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aaf9cc)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab170e)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab23c5)
Location: include/net/netlink.h:981
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac1333)
Location: include/net/netlink.h:981
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
