# Function: <code>netlink_unicast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174e4b0)
Location: net/netlink/af_netlink.c:1843
Inline: False
Direct callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:kauditd_send_skb
  - kernel/audit.c:audit_send_list
  - kernel/taskstats.c:send_reply
  - kernel/taskstats.c:taskstats_exit
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
**Symbols:**

```
ffffffff8174e4b0-ffffffff8174e654: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817ba650)
Location: net/netlink/af_netlink.c:1223
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_send_skb
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
**Symbols:**

```
ffffffff817ba650-ffffffff817ba86b: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e9ff0)
Location: net/netlink/af_netlink.c:1240
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_send_unicast_skb
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/sched/cls_api.c:tfilter_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
**Symbols:**

```
ffffffff817e9ff0-ffffffff817ea20b: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81809cc0)
Location: net/netlink/af_netlink.c:1274
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/sched/cls_api.c:tfilter_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
**Symbols:**

```
ffffffff81809cc0-ffffffff81809edd: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81888c20)
Location: net/netlink/af_netlink.c:1287
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/sched/cls_api.c:tfilter_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
**Symbols:**

```
ffffffff81888c20-ffffffff81888e5f: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818dc670)
Location: net/netlink/af_netlink.c:1326
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/sched/cls_api.c:tfilter_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff818dc670-ffffffff818dc8c9: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81909050)
Location: net/netlink/af_netlink.c:1319
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff81909050-ffffffff819092a3: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8196a3a0)
Location: net/netlink/af_netlink.c:1311
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
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
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff8196a3a0-ffffffff8196a5b8: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819a0e10)
Location: net/netlink/af_netlink.c:1312
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
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
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff819a0e10-ffffffff819a1028: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a7a620)
Location: net/netlink/af_netlink.c:1312
Inline: False
Direct callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:send_cpu_listeners
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
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
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/features.c:features_send_reply
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
**Symbols:**

```
ffffffff81a7a620-ffffffff81a7a943: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a83490)
Location: net/netlink/af_netlink.c:1313
Inline: False
Direct callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:send_cpu_listeners
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
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
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/features.c:features_send_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
**Symbols:**

```
ffffffff81a83490-ffffffff81a837bc: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a6c560)
Location: net/netlink/af_netlink.c:1323
Inline: False
Direct callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
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
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/features.c:features_send_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
**Symbols:**

```
ffffffff81a6c560-ffffffff81a6c88c: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b25bb0)
Location: net/netlink/af_netlink.c:1328
Inline: False
Direct callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
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
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/features.c:features_send_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
**Symbols:**

```
ffffffff81b25bb0-ffffffff81b25edc: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81cae760)
Location: net/netlink/af_netlink.c:1328
Inline: False
Direct callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
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
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/features.c:features_send_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
**Symbols:**

```
ffffffff81cae760-ffffffff81caeae4: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e6bda0)
Location: net/netlink/af_netlink.c:1348
Inline: False
Direct callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
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
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/features.c:features_send_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
**Symbols:**

```
ffffffff81e6bda0-ffffffff81e6c124: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec7e00)
Location: net/netlink/af_netlink.c:1348
Inline: False
Direct callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/features.c:features_send_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
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
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_cmd_selftests_get_doit
  - net/devlink/dev.c:devlink_nl_cmd_info_get_doit
  - net/devlink/dev.c:devlink_nl_cmd_eswitch_get_doit
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_cmd_get_doit
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_get_doit
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/handshake/tlshd.c:tls_handshake_accept
```
**Symbols:**

```
ffffffff81ec7e00-ffffffff81ec8184: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f8b210)
Location: net/netlink/af_netlink.c:1350
Inline: False
Direct callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_id_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_id_get_doit
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/netdev-genl.c:netdev_nl_queue_get_doit
  - net/core/netdev-genl.c:netdev_nl_napi_get_doit
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
  - net/core/page_pool_user.c:netdev_nl_page_pool_get_do
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/features.c:features_send_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/devlink/netlink.c:devlink_nl_msg_reply_and_new
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_get_doit
  - net/devlink/dev.c:devlink_nl_info_get_doit
  - net/devlink/dev.c:devlink_nl_eswitch_get_doit
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_get_doit
  - net/devlink/port.c:devlink_nl_port_new_doit
  - net/devlink/port.c:devlink_nl_port_get_doit
  - net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_get_doit
  - net/devlink/sb.c:devlink_nl_sb_port_pool_get_doit
  - net/devlink/sb.c:devlink_nl_sb_pool_get_doit
  - net/devlink/sb.c:devlink_nl_sb_get_doit
  - net/devlink/dpipe.c:devlink_nl_dpipe_entries_get_doit
  - net/devlink/dpipe.c:devlink_dpipe_send_and_alloc_skb
  - net/devlink/param.c:devlink_nl_param_get_doit
  - net/devlink/region.c:devlink_nl_region_new_doit
  - net/devlink/region.c:devlink_nl_region_get_doit
  - net/devlink/health.c:devlink_nl_health_reporter_get_doit
  - net/devlink/trap.c:devlink_nl_trap_policer_get_doit
  - net/devlink/trap.c:devlink_nl_trap_group_get_doit
  - net/devlink/trap.c:devlink_nl_trap_get_doit
  - net/devlink/rate.c:devlink_nl_rate_get_doit
  - net/devlink/linecard.c:devlink_nl_linecard_get_doit
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_limits_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_doit
  - net/handshake/tlshd.c:tls_handshake_accept
```
**Symbols:**

```
ffffffff81f8b210-ffffffff81f8b59a: netlink_unicast (STB_GLOBAL)
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
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4f518)
Location: net/netlink/af_netlink.c:1312
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
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
  - net/sched/cls_api.c:tc_chain_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffff800010c4f518-ffff800010c4f720: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5f67c)
Location: net/netlink/af_netlink.c:1312
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
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
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
c0d5f67c-c0d5f890: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d4dd70)
Location: net/netlink/af_netlink.c:1312
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
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
  - net/sched/cls_api.c:tc_chain_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
c000000000d4dd70-c000000000d4e034: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007bb184)
Location: net/netlink/af_netlink.c:1312
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
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
  - net/sched/cls_api.c:tc_chain_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffe0007bb184-ffffffe0007bb356: netlink_unicast (STB_GLOBAL)
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
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81940c80)
Location: net/netlink/af_netlink.c:1312
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
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
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff81940c80-ffffffff81940e98: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818fa770)
Location: net/netlink/af_netlink.c:1312
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
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
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff818fa770-ffffffff818fa988: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81991e10)
Location: net/netlink/af_netlink.c:1312
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
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
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netfilter/nfnetlink.c:nfnetlink_unicast
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_stat_ct
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_conntrack
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff81991e10-ffffffff81992028: netlink_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int netlink_unicast(struct sock *ssk, struct sk_buff *skb, u32 portid, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b4900)
Location: net/netlink/af_netlink.c:1312
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_send_queue
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
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
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff819b4900-ffffffff819b4b18: netlink_unicast (STB_GLOBAL)
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
