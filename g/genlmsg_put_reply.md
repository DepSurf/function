# Function: <code>genlmsg_put_reply</code>

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
In kernel/taskstats.c (ffffffff8113e22f)
Location: include/net/genetlink.h:253
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff81781681)
Location: include/net/genetlink.h:253
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180d405)
Location: include/net/genetlink.h:253
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180e568)
Location: include/net/genetlink.h:253
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8180fe80)
Location: include/net/genetlink.h:253
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
In kernel/taskstats.c (ffffffff8114687f)
Location: include/net/genetlink.h:251
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff817eeb41)
Location: include/net/genetlink.h:251
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8187f7f5)
Location: include/net/genetlink.h:251
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81880be8)
Location: include/net/genetlink.h:251
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81882550)
Location: include/net/genetlink.h:251
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8188355d)
Location: include/net/genetlink.h:251
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
In kernel/taskstats.c (ffffffff8115075f)
Location: include/net/genetlink.h:201
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f551)
Location: include/net/genetlink.h:201
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b40a5)
Location: include/net/genetlink.h:201
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b5498)
Location: include/net/genetlink.h:201
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b6e00)
Location: include/net/genetlink.h:201
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b7dfd)
Location: include/net/genetlink.h:201
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
In kernel/taskstats.c (ffffffff81152d53)
Location: include/net/genetlink.h:214
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff81840278)
Location: include/net/genetlink.h:214
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818daa55)
Location: include/net/genetlink.h:214
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dbde4)
Location: include/net/genetlink.h:214
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818dd6bd)
Location: include/net/genetlink.h:214
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818de6cd)
Location: include/net/genetlink.h:214
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
In kernel/taskstats.c (ffffffff8115f573)
Location: include/net/genetlink.h:210
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf618)
Location: include/net/genetlink.h:210
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81960635)
Location: include/net/genetlink.h:210
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819619c4)
Location: include/net/genetlink.h:210
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819632ad)
Location: include/net/genetlink.h:210
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819642d3)
Location: include/net/genetlink.h:210
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
In kernel/taskstats.c (ffffffff8116e5a3)
Location: include/net/genetlink.h:210
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff819151fd)
Location: include/net/genetlink.h:210
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819b9e14)
Location: include/net/genetlink.h:210
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bb168)
Location: include/net/genetlink.h:210
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bcafd)
Location: include/net/genetlink.h:210
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bdb73)
Location: include/net/genetlink.h:210
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
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
In kernel/taskstats.c (ffffffff8117c073)
Location: include/net/genetlink.h:210
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff8194381d)
Location: include/net/genetlink.h:210
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f10e4)
Location: include/net/genetlink.h:210
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f23d8)
Location: include/net/genetlink.h:210
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f3d4f)
Location: include/net/genetlink.h:210
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4d13)
Location: include/net/genetlink.h:210
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
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
In kernel/taskstats.c (ffffffff81188f03)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7dec)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a603a0)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a61728)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a631af)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a641d3)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
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
In kernel/taskstats.c (ffffffff81194e43)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff819dee7c)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a96fd0)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a982f8)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a99d5f)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9ad53)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
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
In kernel/taskstats.c (ffffffff811a9fd3)
Location: include/net/genetlink.h:242
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In net/ethtool/netlink.c (ffffffff81a862ad)
Location: include/net/genetlink.h:242
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acc416)
Location: include/net/genetlink.h:242
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b92850)
Location: include/net/genetlink.h:242
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93b68)
Location: include/net/genetlink.h:242
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b957df)
Location: include/net/genetlink.h:242
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b96521)
Location: include/net/genetlink.h:242
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb3635)
Location: include/net/genetlink.h:242
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
In kernel/taskstats.c (ffffffff811a75d3)
Location: include/net/genetlink.h:264
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff8195f70d)
Location: include/net/genetlink.h:264
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
```
```
In net/ethtool/netlink.c (ffffffff81a8fb8d)
Location: include/net/genetlink.h:264
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad83d8)
Location: include/net/genetlink.h:264
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba24a0)
Location: include/net/genetlink.h:264
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba37a8)
Location: include/net/genetlink.h:264
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba5432)
Location: include/net/genetlink.h:264
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba6191)
Location: include/net/genetlink.h:264
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7d1a)
Location: include/net/genetlink.h:264
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
In kernel/taskstats.c (ffffffff811a7fb3)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81942c6d)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
```
```
In net/ethtool/netlink.c (ffffffff81a792bd)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac3170)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b91580)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b928c8)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b9458d)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b95311)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb949a)
Location: include/net/genetlink.h:265
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
In kernel/taskstats.c (ffffffff811d1d73)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff819e772f)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
```
```
In net/ethtool/netlink.c (ffffffff81b3358d)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b80fe1)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5dd20)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f068)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60d6d)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61b41)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/mptcp/pm_netlink.c (ffffffff81c88b6a)
Location: include/net/genetlink.h:265
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
In kernel/taskstats.c (ffffffff81206593)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81b4cfe3)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
```
```
In net/ethtool/netlink.c (ffffffff81cbec3f)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d11460)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81dfffe4)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e01418)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e032dd)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e04141)
Location: include/net/genetlink.h:265
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2f033)
Location: include/net/genetlink.h:265
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
In kernel/taskstats.c (ffffffff8124e8a3)
Location: include/net/genetlink.h:346
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81ce4ce3)
Location: include/net/genetlink.h:346
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
```
```
In net/ethtool/netlink.c (ffffffff81e7d76f)
Location: include/net/genetlink.h:346
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed7210)
Location: include/net/genetlink.h:346
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd4e04)
Location: include/net/genetlink.h:346
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd6268)
Location: include/net/genetlink.h:346
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd825d)
Location: include/net/genetlink.h:346
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd9111)
Location: include/net/genetlink.h:346
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/mptcp/pm_netlink.c (ffffffff82007723)
Location: include/net/genetlink.h:346
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
In kernel/taskstats.c (ffffffff81265c53)
Location: include/net/genetlink.h:346
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81d4d2b3)
Location: include/net/genetlink.h:346
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
```
```
In net/ethtool/netlink.c (ffffffff81ed9d2f)
Location: include/net/genetlink.h:346
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f361ec)
Location: include/net/genetlink.h:346
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82050aa4)
Location: include/net/genetlink.h:346
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82051f28)
Location: include/net/genetlink.h:346
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053f2d)
Location: include/net/genetlink.h:346
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82054de1)
Location: include/net/genetlink.h:346
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/mptcp/pm_netlink.c (ffffffff82083ac3)
Location: include/net/genetlink.h:346
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
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
In kernel/taskstats.c (ffffffff8127fb13)
Location: include/net/genetlink.h:424
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81e03da3)
Location: include/net/genetlink.h:424
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81ebb6ea)
Location: include/net/genetlink.h:424
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_id_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_id_get_doit
```
```
In net/ethtool/netlink.c (ffffffff81f9dabf)
Location: include/net/genetlink.h:424
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffc48c)
Location: include/net/genetlink.h:424
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82123154)
Location: include/net/genetlink.h:424
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82124708)
Location: include/net/genetlink.h:424
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8212670d)
Location: include/net/genetlink.h:424
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff821276c1)
Location: include/net/genetlink.h:424
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/mptcp/pm_netlink.c (ffffffff8215c233)
Location: include/net/genetlink.h:424
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_limits_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_doit
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
In kernel/taskstats.c (ffff80001020d308)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In net/ipv4/tcp_metrics.c (ffff800010c92048)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d66588)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d679c8)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d6980c)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6a948)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
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
In kernel/taskstats.c (c044bc9c)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In net/ipv4/tcp_metrics.c (c0da0d50)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (c0e64db8)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (c0e66358)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e67df8)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (c0e68ee0)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
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
In kernel/taskstats.c (c00000000028b0e0)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In net/ipv4/tcp_metrics.c (c000000000da27b8)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea26f8)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea42b8)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea66a0)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea7d18)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
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
In kernel/taskstats.c (ffffffe00016e42a)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f200c)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a086)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089afde)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089c6e6)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d4ae)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
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
In kernel/taskstats.c (ffffffff8118d463)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197ecec)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a36360)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a37688)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a390ef)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a3a0e3)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
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
In kernel/taskstats.c (ffffffff81180583)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff819387ac)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f2f80)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f42a8)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f5d0f)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6d03)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
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
In kernel/taskstats.c (ffffffff8118b233)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e94bc)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa2210)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa3538)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa4f9f)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa5f93)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
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
In kernel/taskstats.c (ffffffff81198ba3)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f3220)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aae580)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aaf958)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab131f)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab2333)
Location: include/net/genetlink.h:236
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
</details>
</li>
</ul>

## Differences
