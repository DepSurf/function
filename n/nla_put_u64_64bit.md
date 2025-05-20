# Function: <code>nla_put_u64_64bit</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/netlink.c (ffffffff812a2fbd)
Location: include/net/netlink.h:857
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff81797753)
Location: include/net/netlink.h:857
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/ipv4/ipmr.c (ffffffff81815d5f)
Location: include/net/netlink.h:857
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff818689ba)
Location: include/net/netlink.h:857
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
In fs/quota/netlink.c (ffffffff812b899d)
Location: include/net/netlink.h:857
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff817c542d)
Location: include/net/netlink.h:857
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/ipv4/tcp.c (ffffffff818071aa)
Location: include/net/netlink.h:857
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ipmr.c (ffffffff8184750f)
Location: include/net/netlink.h:857
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8189b80a)
Location: include/net/netlink.h:857
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
In fs/quota/netlink.c (ffffffff812c5d6d)
Location: include/net/netlink.h:869
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff817e3e40)
Location: include/net/netlink.h:869
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/ipv4/tcp.c (ffffffff8182779a)
Location: include/net/netlink.h:869
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ipmr.c (ffffffff8186ad26)
Location: include/net/netlink.h:869
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
```
```
In net/ipv6/ip6mr.c (ffffffff818c1be4)
Location: include/net/netlink.h:869
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
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
In fs/quota/netlink.c (ffffffff812e9c1d)
Location: include/net/netlink.h:894
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff8185ed82)
Location: include/net/netlink.h:894
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/ipv4/tcp.c (ffffffff818a6ce6)
Location: include/net/netlink.h:894
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ipmr.c (ffffffff818eb4c2)
Location: include/net/netlink.h:894
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
```
```
In net/ipv6/ip6mr.c (ffffffff81945524)
Location: include/net/netlink.h:894
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
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
In fs/quota/netlink.c (ffffffff81316b1d)
Location: include/net/netlink.h:894
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff818aae82)
Location: include/net/netlink.h:894
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/ipv4/tcp.c (ffffffff818fbde6)
Location: include/net/netlink.h:894
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ipmr.c (ffffffff81941b75)
Location: include/net/netlink.h:894
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff81944585)
Location: include/net/netlink.h:894
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
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
In fs/quota/netlink.c (ffffffff8132dacd)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff818cddf2)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/ipv4/tcp.c (ffffffff81929d66)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ipmr.c (ffffffff819713d5)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff81974825)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
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
In fs/quota/netlink.c (ffffffff8135580c)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff8191ab42)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/devlink.c (ffffffff8194ed73)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
```
```
In net/ipv4/tcp.c (ffffffff8198cf86)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ipmr.c (ffffffff819dab5b)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff819de366)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
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
In fs/quota/netlink.c (ffffffff8136db4c)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff8194d162)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffffffff8197646d)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (ffffffff819833d9)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
```
```
In net/ipv4/tcp.c (ffffffff819c3926)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ipmr.c (ffffffff81a11a07)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff81a15406)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
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
In fs/quota/netlink.c (ffffffff813b567c)
Location: include/net/netlink.h:1347
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff81a1edee)
Location: include/net/netlink.h:1347
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffffffff81a4a1ac)
Location: include/net/netlink.h:1347
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/devlink.c (ffffffff81a5f6a0)
Location: include/net/netlink.h:1347
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_trap_policer_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_size_params_put
  - net/core/devlink.c:devlink_resource_size_params_put
  - net/core/devlink.c:devlink_resource_size_params_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
```
```
In net/netlink/policy.c (ffffffff81a7dd49)
Location: include/net/netlink.h:1347
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
```
```
In net/ipv4/tcp.c (ffffffff81aaf0a6)
Location: include/net/netlink.h:1347
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ipmr.c (ffffffff81b03026)
Location: include/net/netlink.h:1347
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81b063f6)
Location: include/net/netlink.h:1347
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/mptcp/diag.c (ffffffff81bb2b7c)
Location: include/net/netlink.h:1347
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
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
In fs/quota/netlink.c (ffffffff813c6eac)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff81a2010e)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffffffff81a50e1c)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/devlink.c (ffffffff81a67e90)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_trap_policer_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_resource_size_params_put
  - net/core/devlink.c:devlink_resource_size_params_put
  - net/core/devlink.c:devlink_resource_size_params_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
```
```
In net/netlink/policy.c (ffffffff81a86e16)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/pause.c (ffffffff81a9558d)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_put_stats
  - net/ethtool/pause.c:pause_put_stats
```
```
In net/ipv4/tcp.c (ffffffff81aba15b)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ipmr.c (ffffffff81b10176)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81b145e6)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/mptcp/diag.c (ffffffff81bc6fb1)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
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
In fs/quota/netlink.c (ffffffff813cdf3c)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff81a071de)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffffffff81a35d8b)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/devlink.c (ffffffff81a42ed8)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
```
```
In net/netlink/policy.c (ffffffff81a6fef6)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/pause.c (ffffffff81a7f128)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/stats.c (ffffffff81a825f0)
Location: include/net/netlink.h:1360
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81aa53e0)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/nexthop.c (ffffffff81af6cf5)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81afdd84)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81b023e2)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff81b7d36c)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/mptcp/diag.c (ffffffff81bb7ce0)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
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
In fs/quota/netlink.c (ffffffff8141f26c)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff81ab963e)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffffffff81aeb96c)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/devlink.c (ffffffff81af9348)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
```
```
In net/netlink/policy.c (ffffffff81b29646)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/pause.c (ffffffff81b39188)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/stats.c (ffffffff81b3c170)
Location: include/net/netlink.h:1360
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81b61730)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/nexthop.c (ffffffff81bb6625)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81bbefe7)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc42c8)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/ioam6.c (ffffffff81c38d5d)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/seg6_local.c (ffffffff81c4852d)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/mptcp/diag.c (ffffffff81c87230)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
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
In fs/quota/netlink.c (ffffffff814970ad)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff81c329df)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffffffff81c6e2a6)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/devlink.c (ffffffff81c7c24d)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
```
```
In net/netlink/policy.c (ffffffff81cb27d6)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/pause.c (ffffffff81cc4f89)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/stats.c (ffffffff81cc8664)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ipv4/tcp.c (ffffffff81cf0160)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/nexthop.c (ffffffff81d4a252)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81d53d60)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81d59168)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/ioam6.c (ffffffff81dd69d6)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/seg6_local.c (ffffffff81de7a58)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/mptcp/diag.c (ffffffff81e2da72)
Location: include/net/netlink.h:1360
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
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
In fs/quota/netlink.c (ffffffff8152b108)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff81de5ddf)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffffffff81e25f30)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/devlink.c (ffffffff81e40b1d)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
```
```
In net/netlink/policy.c (ffffffff81e70826)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/pause.c (ffffffff81e84489)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/stats.c (ffffffff81e87de4)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ipv4/tcp.c (ffffffff81eb3490)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/nexthop.c (ffffffff81f138e2)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81f1df31)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81f2376d)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/ioam6.c (ffffffff81fa8326)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/seg6_local.c (ffffffff81fbbc35)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/mptcp/diag.c (ffffffff82006002)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
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
In fs/quota/netlink.c (ffffffff81563498)
Location: include/net/netlink.h:1410
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff81e58a57)
Location: include/net/netlink.h:1410
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/netdev-genl.c (ffffffff81e7ce68)
Location: include/net/netlink.h:1410
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81e9b4d0)
Location: include/net/netlink.h:1410
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/netlink/policy.c (ffffffff81ecc8f2)
Location: include/net/netlink.h:1410
Inline: True
Inline callers:
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/pause.c (ffffffff81ee101f)
Location: include/net/netlink.h:1410
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/stats.c (ffffffff81ee4a84)
Location: include/net/netlink.h:1410
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ethtool/mm.c (ffffffff81ee5a08)
Location: include/net/netlink.h:1410
Inline: True
Inline callers:
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
```
```
In net/ipv4/tcp.c (ffffffff81f11bb0)
Location: include/net/netlink.h:1410
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/nexthop.c (ffffffff81f735b2)
Location: include/net/netlink.h:1410
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81f7da21)
Location: include/net/netlink.h:1410
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81f832ba)
Location: include/net/netlink.h:1410
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/ioam6.c (ffffffff82008cb6)
Location: include/net/netlink.h:1410
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/seg6_local.c (ffffffff8201c535)
Location: include/net/netlink.h:1410
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/devlink/leftover.c (ffffffff820376e1)
Location: include/net/netlink.h:1410
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_region_notify_build
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_dpipe_table_put
```
```
In net/devlink/dev.c (ffffffff82044073)
Location: include/net/netlink.h:1410
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
```
```
In net/devlink/health.c (ffffffff82047249)
Location: include/net/netlink.h:1410
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/mptcp/diag.c (ffffffff8208237b)
Location: include/net/netlink.h:1410
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
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
In fs/quota/netlink.c (ffffffff81599b88)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff81f17d96)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/netdev-genl.c (ffffffff81f3d4fe)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_dev_fill
  - net/core/netdev-genl.c:netdev_nl_dev_fill
  - net/core/netdev-genl.c:netdev_nl_dev_fill
```
```
In net/core/drop_monitor.c (ffffffff81f5dc40)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/netlink/policy.c (ffffffff81f90240)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/pause.c (ffffffff81fa4eaf)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/stats.c (ffffffff81fa8864)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ethtool/mm.c (ffffffff81fa97e8)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
```
```
In net/ipv4/tcp.c (ffffffff81fd5e50)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/nexthop.c (ffffffff82039da2)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff82044261)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff8204993a)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/ioam6.c (ffffffff820d7c26)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/seg6_local.c (ffffffff820eb505)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/devlink/dev.c (ffffffff82103843)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
```
```
In net/devlink/dpipe.c (ffffffff8210b4fe)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
```
```
In net/devlink/resource.c (ffffffff8210c44f)
Location: include/net/netlink.h:1470
Inline: True
```
```
In net/devlink/region.c (ffffffff821113b2)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_notify_build
```
```
In net/devlink/health.c (ffffffff82113179)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/devlink/trap.c (ffffffff82114b11)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
```
```
In net/devlink/rate.c (ffffffff821188b9)
Location: include/net/netlink.h:1470
Inline: True
```
```
In net/mptcp/diag.c (ffffffff821579c4)
Location: include/net/netlink.h:1470
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
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
In fs/quota/netlink.c (ffff8000104375d0)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffff800010bef244)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffff800010c1c938)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (ffff800010c2ba08)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
```
```
In net/ipv4/tcp.c (ffff800010c7650c)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ipmr.c (ffff800010cca0d0)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffff800010cd0b68)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
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
In fs/quota/netlink.c (c05ff210)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (c0d07838)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (c0d3484c)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (c0d4258c)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
```
```
In net/ipv4/tcp.c (c0d84c18)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ipmr.c (c0dd608c)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (c0ddaef0)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
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
In fs/quota/netlink.c (c0000000005499e4)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (c000000000cd314c)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (c000000000d0d91c)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (c000000000d22248)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
```
```
In net/ipv4/tcp.c (c000000000d7e070)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ipmr.c (c000000000de95b8)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (c000000000deed3c)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
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
In fs/quota/netlink.c (ffffffe0002d1814)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffe0007717be)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffffffe000796846)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (ffffffe0007a314e)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
```
```
In net/ipv4/tcp.c (ffffffe0007d968c)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ipmr.c (ffffffe00081f586)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffe000822670)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
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
In fs/quota/netlink.c (ffffffff8136612c)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff818ed132)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffffffff8191643d)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (ffffffff81923249)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
```
```
In net/ipv4/tcp.c (ffffffff81963796)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ipmr.c (ffffffff819b1363)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff819b4a96)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
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
In fs/quota/netlink.c (ffffffff81356dcc)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff818a6f72)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffffffff818d01ed)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (ffffffff818dcff9)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
```
```
In net/ipv4/tcp.c (ffffffff8191d286)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ipmr.c (ffffffff8196d993)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff819710c6)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
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
In fs/quota/netlink.c (ffffffff81363bfc)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff8193e162)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffffffff8196746d)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (ffffffff819743d9)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
```
```
In net/ipv4/tcp.c (ffffffff819cdf66)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ipmr.c (ffffffff81a1bc03)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1f336)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
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
In fs/quota/netlink.c (ffffffff813772ac)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/rtnetlink.c (ffffffff8195f9f2)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffffffff819896fd)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (ffffffff819968c9)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
```
```
In net/ipv4/tcp.c (ffffffff819d7af6)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ipmr.c (ffffffff81a26b17)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2a806)
Location: include/net/netlink.h:1295
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
</details>
</li>
</ul>

## Differences
