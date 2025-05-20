# Function: <code>nla_nest_cancel</code>

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
In kernel/taskstats.c (ffffffff8113e847)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff817263d6)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff8172d0ad)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/lwtunnel.c (ffffffff8173e33d)
Location: include/net/netlink.h:1210
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81745d3f)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff8174792d)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/ipv4/tcp_metrics.c (ffffffff817814d9)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffffffff817a8679)
Location: include/net/netlink.h:1210
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff817f91ce)
Location: include/net/netlink.h:1210
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81813c53)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getcap
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
In kernel/taskstats.c (ffffffff81146e7c)
Location: include/net/netlink.h:1234
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff8178febd)
Location: include/net/netlink.h:1234
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81799330)
Location: include/net/netlink.h:1234
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/lwtunnel.c (ffffffff817aaca9)
Location: include/net/netlink.h:1234
Inline: True
```
```
In net/sched/cls_api.c (ffffffff817b2c93)
Location: include/net/netlink.h:1234
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff817b57a8)
Location: include/net/netlink.h:1234
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ee9a4)
Location: include/net/netlink.h:1234
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffffffff81815dad)
Location: include/net/netlink.h:1234
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81868a08)
Location: include/net/netlink.h:1234
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81888972)
Location: include/net/netlink.h:1234
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In kernel/taskstats.c (ffffffff81150ccc)
Location: include/net/netlink.h:1244
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff817bd76d)
Location: include/net/netlink.h:1244
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff817c70e0)
Location: include/net/netlink.h:1244
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/lwtunnel.c (ffffffff817d9a49)
Location: include/net/netlink.h:1244
Inline: True
```
```
In net/sched/cls_api.c (ffffffff817e2512)
Location: include/net/netlink.h:1244
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff817e51a8)
Location: include/net/netlink.h:1244
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f3b4)
Location: include/net/netlink.h:1244
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffffffff8184755d)
Location: include/net/netlink.h:1244
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8189b858)
Location: include/net/netlink.h:1244
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff818bd192)
Location: include/net/netlink.h:1244
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In kernel/taskstats.c (ffffffff811532ce)
Location: include/net/netlink.h:1256
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff817dbeb2)
Location: include/net/netlink.h:1256
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff817e59e1)
Location: include/net/netlink.h:1256
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/lwtunnel.c (ffffffff817f8c6e)
Location: include/net/netlink.h:1256
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81801cfa)
Location: include/net/netlink.h:1256
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81804d19)
Location: include/net/netlink.h:1256
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183ff6d)
Location: include/net/netlink.h:1256
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffffffff8186ac13)
Location: include/net/netlink.h:1256
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
```
```
In net/ipv6/ip6mr.c (ffffffff818c1c33)
Location: include/net/netlink.h:1256
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
```
```
In net/dcb/dcbnl.c (ffffffff818e3b49)
Location: include/net/netlink.h:1256
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In kernel/taskstats.c (ffffffff8115face)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff8185694c)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81860a84)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/lwtunnel.c (ffffffff81876551)
Location: include/net/netlink.h:1311
Inline: True
```
```
In net/sched/cls_api.c (ffffffff8187fd6a)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81883a39)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf311)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffffffff818eb3ae)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
```
```
In net/ipv6/ip6mr.c (ffffffff81945573)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
```
```
In net/dcb/dcbnl.c (ffffffff8196995f)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In kernel/taskstats.c (ffffffff8116ea1e)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff818a22a5)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818aa936)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/lwtunnel.c (ffffffff818c7c65)
Location: include/net/netlink.h:1311
Inline: True
```
```
In net/sched/cls_api.c (ffffffff818d5064)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff818d7489)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914fa5)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffffffff81941c3c)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff819445e1)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/dcb/dcbnl.c (ffffffff819c36e4)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819cb14d)
Location: include/net/netlink.h:1311
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/taskstats.c (ffffffff8117c4ee)
Location: include/net/netlink.h:1454
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff818c5482)
Location: include/net/netlink.h:1454
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818d07d3)
Location: include/net/netlink.h:1454
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/lwtunnel.c (ffffffff818f0dc5)
Location: include/net/netlink.h:1454
Inline: True
```
```
In net/sched/cls_api.c (ffffffff818fdf2e)
Location: include/net/netlink.h:1454
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff819040bf)
Location: include/net/netlink.h:1454
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/ipv4/tcp_metrics.c (ffffffff81943755)
Location: include/net/netlink.h:1454
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffffffff819715a9)
Location: include/net/netlink.h:1454
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff81974881)
Location: include/net/netlink.h:1454
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/dcb/dcbnl.c (ffffffff819fa6f4)
Location: include/net/netlink.h:1454
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a03c19)
Location: include/net/netlink.h:1454
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/taskstats.c (ffffffff81189398)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff819114df)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff8191d666)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/lwtunnel.c (ffffffff81942770)
Location: include/net/netlink.h:1732
Inline: True
```
```
In net/core/devlink.c (ffffffff8194ca47)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/cls_api.c (ffffffff8195d8c3)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81965210)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7d16)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffffffff819dad22)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff819de3c2)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/dcb/dcbnl.c (ffffffff81a69c68)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a72f18)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/taskstats.c (ffffffff811952ce)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff81943579)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff8194fcc1)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffffffff819765b5)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffffffff81977695)
Location: include/net/netlink.h:1732
Inline: True
```
```
In net/core/devlink.c (ffffffff81983b9d)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/cls_api.c (ffffffff81993e80)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff8199bd8f)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/ipv4/tcp_metrics.c (ffffffff819deda6)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffffffff81a11be8)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff81a15462)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/dcb/dcbnl.c (ffffffff81aa0b18)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa96f4)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/taskstats.c (ffffffff811aa853)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff81a13bb9)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81a2150d)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_link_af
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_slave_info_fill
```
```
In net/core/drop_monitor.c (ffffffff81a4a20d)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
```
```
In net/core/lwtunnel.c (ffffffff81a4c45b)
Location: include/net/netlink.h:1799
Inline: True
```
```
In net/core/devlink.c (ffffffff81a5f5d4)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_policer_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_metadata_put
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81a61964)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put_all
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/cls_api.c (ffffffff81a718d0)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81a739d4)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_del_walker
```
```
In net/netlink/policy.c (ffffffff81a7da82)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
```
```
In net/ethtool/netlink.c (ffffffff81a85a2f)
Location: include/net/netlink.h:1799
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a875b3)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a881d0)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a8d26e)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acbdc8)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af99be)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_geneve
```
```
In net/ipv4/ipmr.c (ffffffff81b02fb7)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81b06452)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/dcb/dcbnl.c (ffffffff81b9c0d6)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5afb)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81bb2af4)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb30ab)
Location: include/net/netlink.h:1799
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In kernel/taskstats.c (ffffffff811a7e03)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff8195f4b0)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
```
```
In net/core/neighbour.c (ffffffff81a13ed9)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81a1fa9c)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_link_af
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_slave_info_fill
```
```
In net/core/drop_monitor.c (ffffffff81a50e7d)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
```
```
In net/core/lwtunnel.c (ffffffff81a5213e)
Location: include/net/netlink.h:1812
Inline: True
```
```
In net/core/devlink.c (ffffffff81a67dc4)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_policer_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_metadata_put
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81a6a24e)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put_all
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/cls_api.c (ffffffff81a7a350)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81a7c5d4)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_del_walker
```
```
In net/netlink/policy.c (ffffffff81a87423)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81a8f3bc)
Location: include/net/netlink.h:1812
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a90f2e)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a91b5e)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81a95618)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_put_stats
```
```
In net/ethtool/cabletest.c (ffffffff81a969ae)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
```
```
In net/ethtool/tunnels.c (ffffffff81a97412)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7d88)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b0710e)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_geneve
```
```
In net/ipv4/ipmr.c (ffffffff81b10107)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81b14642)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/dcb/dcbnl.c (ffffffff81babde6)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb4fd1)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81bc6f29)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc753c)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In kernel/taskstats.c (ffffffff811a8723)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81942a10)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
```
```
In net/core/neighbour.c (ffffffff819fa749)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81a06b64)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/drop_monitor.c (ffffffff81a35edf)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81a37a53)
Location: include/net/netlink.h:1812
Inline: True
```
```
In net/core/devlink.c (ffffffff81a4302f)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81a529ad)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/cls_api.c (ffffffff81a5f180)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81a65205)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_del_walker
```
```
In net/netlink/policy.c (ffffffff81a704f3)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81a78ab5)
Location: include/net/netlink.h:1812
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a7a72c)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a7b6ff)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81a7f195)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a80477)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
```
```
In net/ethtool/tunnels.c (ffffffff81a80d76)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81a815e6)
Location: include/net/netlink.h:1812
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81a82219)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2f04)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af2917)
Location: include/net/netlink.h:1812
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81af6d4f)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81afdd17)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81b0243e)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff81b7d41d)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/dcb/dcbnl.c (ffffffff81b9af86)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba3fab)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81bb7c59)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb89d6)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In kernel/taskstats.c (ffffffff811d2123)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff819e7410)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
```
```
In net/core/neighbour.c (ffffffff81aabdb9)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81ab8fb2)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/drop_monitor.c (ffffffff81aebad1)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81aed87e)
Location: include/net/netlink.h:1812
Inline: True
```
```
In net/core/devlink.c (ffffffff81af949f)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0b41d)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/cls_api.c (ffffffff81b18040)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81b1e4ff)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_del_walker
```
```
In net/netlink/policy.c (ffffffff81b29c43)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81b32c85)
Location: include/net/netlink.h:1812
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81b34b3c)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81b35ae8)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81b391f5)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81b3a247)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
```
```
In net/ethtool/tunnels.c (ffffffff81b3aab6)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81b3b366)
Location: include/net/netlink.h:1812
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81b3bdd9)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b80ac1)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2e27)
Location: include/net/netlink.h:1812
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81bb667f)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81bbef7a)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc4328)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff81c485de)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/dcb/dcbnl.c (ffffffff81c669f4)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c7190b)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81c871a9)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81c87fa6)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In kernel/taskstats.c (ffffffff81206966)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81b4cbe9)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
```
```
In net/core/neighbour.c (ffffffff81c24b28)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81c3321b)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/drop_monitor.c (ffffffff81c6e412)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81c7015a)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/core/devlink.c (ffffffff81c7c3b7)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81c917ec)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/cls_api.c (ffffffff81ca25ce)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81ca5e7c)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/netlink/policy.c (ffffffff81cb2e5b)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81cbe835)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81cc00ec)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81cc1311)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81cc4ff5)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81cc613c)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
```
```
In net/ethtool/tunnels.c (ffffffff81cc6a28)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81cc729a)
Location: include/net/netlink.h:1812
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81cc8031)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d10ec7)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d4662e)
Location: include/net/netlink.h:1812
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81d4a2b1)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81d53ce6)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81d591d7)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff81de7b13)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/dcb/dcbnl.c (ffffffff81e09958)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e15497)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81e2d9dd)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2e8bf)
Location: include/net/netlink.h:1812
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In kernel/taskstats.c (ffffffff8124e9d6)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81ce48a9)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
```
```
In net/core/neighbour.c (ffffffff81dd6e51)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81de663b)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/drop_monitor.c (ffffffff81e2609b)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81e280ca)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/core/devlink.c (ffffffff81e40c87)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4cda1)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/cls_api.c (ffffffff81e5efee)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81e63f28)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/netlink/policy.c (ffffffff81e70efb)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81e7d321)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81e7ecfc)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81e80051)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81e844f5)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81e8572c)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
```
```
In net/ethtool/tunnels.c (ffffffff81e86081)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81e8691a)
Location: include/net/netlink.h:1861
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81e87751)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed6c47)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0fa2e)
Location: include/net/netlink.h:1861
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f13941)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81f1debb)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81f237e1)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff81fbc00e)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/dcb/dcbnl.c (ffffffff81fdeda8)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81fec411)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff82005f6d)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff82006a3f)
Location: include/net/netlink.h:1861
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In kernel/taskstats.c (ffffffff81265d86)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81d4ce79)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
```
```
In net/core/neighbour.c (ffffffff81e47c81)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81e5760d)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/drop_monitor.c (ffffffff81e9b63b)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81e9d706)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea84c6)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/cls_api.c (ffffffff81eb76fe)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81ebffb8)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/netlink/policy.c (ffffffff81ecd01b)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81ed98e1)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81edb2ef)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81edc78a)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81ee108b)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81ee205c)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
```
```
In net/ethtool/tunnels.c (ffffffff81ee29d4)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81ee336a)
Location: include/net/netlink.h:1862
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81ee43a1)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ethtool/mm.c (ffffffff81ee5b3c)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/ethtool/mm.c:mm_fill_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f35bf1)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f71e)
Location: include/net/netlink.h:1862
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f73611)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81f7d9ab)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81f8332e)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff8201c90e)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/devlink/leftover.c (ffffffff8203784b)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_param_value_fill_one
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_dpipe_action_put
  - net/devlink/leftover.c:devlink_dpipe_match_put
  - net/devlink/leftover.c:devlink_nl_port_fill
```
```
In net/devlink/dev.c (ffffffff82045aaa)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_info_version_put
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
```
```
In net/devlink/health.c (ffffffff82047841)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/dcb/dcbnl.c (ffffffff8205b017)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff820686b1)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff820822e4)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff82082ddf)
Location: include/net/netlink.h:1862
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/handshake/tlshd.c (ffffffff820941b4)
Location: include/net/netlink.h:1862
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
In kernel/taskstats.c (ffffffff8127fc46)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81e03a99)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81eb9217)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_parents
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_freq
```
```
In net/core/neighbour.c (ffffffff81f06931)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81f16963)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/page_pool_user.c (ffffffff81f45d75)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
```
```
In net/core/drop_monitor.c (ffffffff81f5ddab)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81f5fe86)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6af86)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/cls_api.c (ffffffff81f7a4ae)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81f8316b)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/netlink/policy.c (ffffffff81f9084b)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81f9d7a9)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81f9f0af)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81fa055a)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81fa4f1b)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81fa5eec)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
```
```
In net/ethtool/tunnels.c (ffffffff81fa6864)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81fa714a)
Location: include/net/netlink.h:1960
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81fa8181)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ethtool/mm.c (ffffffff81fa991c)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/ethtool/mm.c:mm_fill_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffbca1)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035e4e)
Location: include/net/netlink.h:1960
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff82039e01)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff820441eb)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff820499ae)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff820eb73e)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/devlink/netlink.c (ffffffff82101792)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_put_nested_handle
```
```
In net/devlink/dev.c (ffffffff821053ed)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_info_version_put
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
```
```
In net/devlink/port.c (ffffffff821065a5)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_function_attrs_put
```
```
In net/devlink/dpipe.c (ffffffff8210b82a)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_action_put
  - net/devlink/dpipe.c:devlink_dpipe_match_put
```
```
In net/devlink/resource.c (ffffffff8210c6ca)
Location: include/net/netlink.h:1960
Inline: True
```
```
In net/devlink/param.c (ffffffff8210dbf1)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/devlink/param.c:devlink_nl_param_value_fill_one
```
```
In net/devlink/region.c (ffffffff82111492)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_read_dumpit
```
```
In net/devlink/health.c (ffffffff8211376e)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/devlink/trap.c (ffffffff82114c7b)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
```
```
In net/devlink/linecard.c (ffffffff82119a47)
Location: include/net/netlink.h:1960
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff8212df8a)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_getapptrust
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213b931)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff8215791c)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff8215844f)
Location: include/net/netlink.h:1960
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/handshake/tlshd.c (ffffffff8216aad4)
Location: include/net/netlink.h:1960
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
In kernel/taskstats.c (ffff80001020d59c)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffff800010be2e50)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffff800010bf1948)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffff800010c1ca88)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffff800010c1e1dc)
Location: include/net/netlink.h:1732
Inline: True
```
```
In net/core/devlink.c (ffff800010c2c1d4)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/cls_api.c (ffff800010c40370)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffff800010c48ef8)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/ipv4/tcp_metrics.c (ffff800010c91f50)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffff800010cca2d0)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffff800010cd0bd8)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/dcb/dcbnl.c (ffff800010d71b60)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d128)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/taskstats.c (c044bf5c)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (c0cfde48)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (c0d0a15c)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (c0d34a18)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (c0d35d48)
Location: include/net/netlink.h:1732
Inline: True
```
```
In net/core/devlink.c (c0d42d50)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/cls_api.c (c0d522a0)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (c0d58a5c)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/ipv4/tcp_metrics.c (c0da0c34)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (c0dd62c4)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (c0ddaf58)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/dcb/dcbnl.c (c0e6efa8)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (c0e77f54)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/taskstats.c (c00000000028b580)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (c000000000cc6cb0)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (c000000000cd6518)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (c000000000d0dab4)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (c000000000d0f94c)
Location: include/net/netlink.h:1732
Inline: True
```
```
In net/core/devlink.c (c000000000d22d40)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/cls_api.c (c000000000d3b04c)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (c000000000d46690)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/ipv4/tcp_metrics.c (c000000000da2660)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (c000000000de9820)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (c000000000deee20)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/dcb/dcbnl.c (c000000000eb08c8)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebcd14)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/taskstats.c (ffffffe00016e640)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffe00076a492)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffe000773654)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffffffe000796964)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffffffe000797bb2)
Location: include/net/netlink.h:1732
Inline: True
```
```
In net/core/devlink.c (ffffffe0007a37aa)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/cls_api.c (ffffffe0007afde0)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffe0007b677e)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1f72)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffffffe00081f73a)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffe0008226c0)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/dcb/dcbnl.c (ffffffe0008a273c)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008aad24)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/taskstats.c (ffffffff8118d8ee)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff818e3549)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818efc91)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffffffff81916585)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffffffff81917505)
Location: include/net/netlink.h:1732
Inline: True
```
```
In net/core/devlink.c (ffffffff81923a0d)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/cls_api.c (ffffffff81933cf0)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff8193bbff)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197ec16)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffffffff819b152a)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff819b4af2)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/dcb/dcbnl.c (ffffffff81a3fea8)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a48a84)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/taskstats.c (ffffffff81180a0e)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff8189d389)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818a9ad1)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffffffff818d0335)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffffffff818d12b5)
Location: include/net/netlink.h:1732
Inline: True
```
```
In net/core/devlink.c (ffffffff818dd7bd)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/cls_api.c (ffffffff818ed7f0)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff818f56ff)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/ipv4/tcp_metrics.c (ffffffff819386d6)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffffffff8196db5a)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff81971122)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/dcb/dcbnl.c (ffffffff819fca98)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a05674)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/taskstats.c (ffffffff8118b6be)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff81934579)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81940cc1)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffffffff819675b5)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffffffff81968695)
Location: include/net/netlink.h:1732
Inline: True
```
```
In net/core/devlink.c (ffffffff81974b9d)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/cls_api.c (ffffffff81984e80)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff8198cd8f)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e93e6)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffffffff81a1bdca)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1f392)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/dcb/dcbnl.c (ffffffff81aabd58)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4934)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/taskstats.c (ffffffff8119902e)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff81955c89)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff819625d1)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/drop_monitor.c (ffffffff81989845)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffffffff8198aa4f)
Location: include/net/netlink.h:1732
Inline: True
```
```
In net/core/devlink.c (ffffffff8199708d)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/cls_api.c (ffffffff819a7670)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff819af61f)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f3146)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ipmr.c (ffffffff81a26cf8)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2a862)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/dcb/dcbnl.c (ffffffff81ab80c8)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac0cd4)
Location: include/net/netlink.h:1732
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
</details>
</li>
</ul>

## Differences
