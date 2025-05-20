# Function: <code>nla_put_64bit</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8145d840)
Location: lib/nlattr.c:562
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_basic
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
**Symbols:**

```
ffffffff8145d840-ffffffff8145d89a: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8147c300)
Location: lib/nlattr.c:562
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_basic
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
**Symbols:**

```
ffffffff8147c300-ffffffff8147c35a: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81485620)
Location: lib/nlattr.c:565
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_basic
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff81485620-ffffffff81485662: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814c17b0)
Location: lib/nlattr.c:643
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_basic
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff814c17b0-ffffffff814c17f2: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814f24e0)
Location: lib/nlattr.c:643
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_basic
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff814f24e0-ffffffff814f2521: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81506220)
Location: lib/nlattr.c:818
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_link_ifmap
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff81506220-ffffffff8150625e: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81534be0)
Location: lib/nlattr.c:850
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_link_ifmap
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
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
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff81534be0-ffffffff81534c22: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81555a10)
Location: lib/nlattr.c:850
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_link_ifmap
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
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
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff81555a10-ffffffff81555a52: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815de7a0)
Location: lib/nlattr.c:1002
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_link_ifmap
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
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
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/mptcp/diag.c:subflow_get_info
```
**Symbols:**

```
ffffffff815de7a0-ffffffff815de7e3: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815fbe40)
Location: lib/nlattr.c:1068
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_link_ifmap
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
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
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/ethtool/pause.c:pause_put_stats
  - net/ethtool/pause.c:pause_put_stats
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
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/mptcp/diag.c:subflow_get_info
```
**Symbols:**

```
ffffffff815fbe40-ffffffff815fbe83: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815dea80)
Location: lib/nlattr.c:1068
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_link_ifmap
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
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
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
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
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/mptcp/diag.c:subflow_get_info
```
**Symbols:**

```
ffffffff815dea80-ffffffff815deac3: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8164a600)
Location: lib/nlattr.c:1068
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_link_ifmap
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
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
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
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
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/mptcp/diag.c:subflow_get_info
```
**Symbols:**

```
ffffffff8164a600-ffffffff8164a643: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81761080)
Location: lib/nlattr.c:1068
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
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
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
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
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/mptcp/diag.c:subflow_get_info
```
**Symbols:**

```
ffffffff81761080-ffffffff817610e7: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8188f860)
Location: lib/nlattr.c:1083
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
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
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
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
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/mptcp/diag.c:subflow_get_info
```
**Symbols:**

```
ffffffff8188f860-ffffffff8188f8c7: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff818d1ca0)
Location: lib/nlattr.c:1083
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
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
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
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
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/mptcp/diag.c:subflow_get_info
```
**Symbols:**

```
ffffffff818d1ca0-ffffffff818d1d07: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81923ca0)
Location: lib/nlattr.c:1115
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - drivers/dpll/dpll_netlink.c:dpll_cmd_pin_get_one
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_dplls
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_freq
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_freq
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_freq
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/netdev-genl.c:netdev_nl_dev_fill
  - net/core/netdev-genl.c:netdev_nl_dev_fill
  - net/core/netdev-genl.c:netdev_nl_dev_fill
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
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
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_notify_build
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/mptcp/diag.c:subflow_get_info
```
**Symbols:**

```
ffffffff81923ca0-ffffffff81923d07: nla_put_64bit (STB_GLOBAL)
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
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffff800010661ec8)
Location: lib/nlattr.c:850
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_link_ifmap
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
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
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffff800010661ec8-ffff800010661f14: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c080af48)
Location: lib/nlattr.c:850
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_link_ifmap
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
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
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
c080af48-c080afa4: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c000000000816140)
Location: lib/nlattr.c:850
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_link_ifmap
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
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
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
c000000000816140-c0000000008161a8: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffe00048e80a)
Location: lib/nlattr.c:850
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_link_ifmap
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
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
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffe00048e80a-ffffffe00048e85c: nla_put_64bit (STB_GLOBAL)
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
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8154dff0)
Location: lib/nlattr.c:850
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_link_ifmap
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
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
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff8154dff0-ffffffff8154e032: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8153e2d0)
Location: lib/nlattr.c:850
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_link_ifmap
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
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
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff8153e2d0-ffffffff8153e312: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81549d30)
Location: lib/nlattr.c:850
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_link_ifmap
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
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
  - net/netfilter/nf_conntrack_proto_dccp.c:dccp_to_nlattr
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_timestamp
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_timestamp
  - net/netfilter/nf_conntrack_netlink.c:dump_counters
  - net/netfilter/nf_conntrack_netlink.c:dump_counters
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff81549d30-ffffffff81549d72: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81563b80)
Location: lib/nlattr.c:850
Inline: False
Direct callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_fill_link_ifmap
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
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
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff81563b80-ffffffff81563bc2: nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
