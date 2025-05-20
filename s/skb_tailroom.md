# Function: <code>skb_tailroom</code>

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
In kernel/audit.c (ffffffff811212aa)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
```
```
In security/selinux/netlink.c (ffffffff8134cb54)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff81415a40)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - lib/nlattr.c:nla_reserve
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_append
```
```
In drivers/connector/connector.c (ffffffff81541dde)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/virtio_net.c (ffffffff815f0fb6)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:page_to_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f691c)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8170985c)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pad
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_try_coalesce
```
```
In net/core/net_namespace.c (ffffffff8170fdc4)
Location: include/linux/skbuff.h:1877
Inline: True
```
```
In net/core/neighbour.c (ffffffff81726456)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8172d1b8)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/fib_rules.c (ffffffff81739d3d)
Location: include/linux/skbuff.h:1877
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817437c0)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81745fd9)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81747203)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tc_dump_action
```
```
In net/netlink/af_netlink.c (ffffffff8174c296)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff8174f276)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff81753b63)
Location: include/linux/skbuff.h:1877
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81790229)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8179d886)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff817a86f8)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc1b3)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/addrconf.c (ffffffff817cb74b)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff817d2503)
Location: include/linux/skbuff.h:1877
Inline: True
```
```
In net/ipv6/route.c (ffffffff817d85fb)
Location: include/linux/skbuff.h:1877
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff817df9ef)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff817f9248)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81809b7e)
Location: include/linux/skbuff.h:1877
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81813d07)
Location: include/linux/skbuff.h:1877
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
In kernel/audit.c (ffffffff81129ec8)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff81382af4)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff8145da00)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
```
```
In drivers/connector/connector.c (ffffffff81593726)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/virtio_net.c (ffffffff81650e0a)
Location: include/linux/skbuff.h:1978
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81656aa0)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8177329d)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_pad
```
```
In net/core/net_namespace.c (ffffffff81777704)
Location: include/linux/skbuff.h:1978
Inline: True
```
```
In net/core/neighbour.c (ffffffff81790d65)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81798fcf)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817a601d)
Location: include/linux/skbuff.h:1978
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817b0661)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff817b2fe9)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff817b4b60)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff817b7fcd)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff817bb256)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff817bfc33)
Location: include/linux/skbuff.h:1978
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff817fdcd5)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81803cc2)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff8180b3d6)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81815e28)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/xfrm/xfrm_output.c (ffffffff818290d8)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/addrconf.c (ffffffff8183877b)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff8183ffc3)
Location: include/linux/skbuff.h:1978
Inline: True
```
```
In net/ipv6/route.c (ffffffff81841fcc)
Location: include/linux/skbuff.h:1978
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff8184f11a)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/mcast.c (ffffffff81858378)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (ffffffff81868a88)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff8187b67e)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81886be7)
Location: include/linux/skbuff.h:1978
Inline: True
```
```
In net/switchdev/switchdev.c (ffffffff8188ad78)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb
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
In kernel/audit.c (ffffffff81133be8)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff81399574)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff8147c4c0)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
```
```
In drivers/connector/connector.c (ffffffff815c0fe6)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81684780)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff817a04ad)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_pad
```
```
In net/core/net_namespace.c (ffffffff817a4784)
Location: include/linux/skbuff.h:1995
Inline: True
```
```
In net/core/neighbour.c (ffffffff817be661)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff817c6d7f)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff817cb5e2)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/fib_rules.c (ffffffff817d4afd)
Location: include/linux/skbuff.h:1995
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817dfda1)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff817e2869)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff817e4420)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff817e7aad)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff817eadc6)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff817f2d3b)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff8182ec35)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81834c57)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff8183c4e6)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff818475d8)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/xfrm/xfrm_output.c (ffffffff8185aab8)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/addrconf.c (ffffffff8186a2ab)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff81871c43)
Location: include/linux/skbuff.h:1995
Inline: True
```
```
In net/ipv6/route.c (ffffffff81873d1c)
Location: include/linux/skbuff.h:1995
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff81881070)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/mcast.c (ffffffff8188a778)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (ffffffff8189b8d8)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff818aff3e)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff818bb457)
Location: include/linux/skbuff.h:1995
Inline: True
```
```
In net/switchdev/switchdev.c (ffffffff818bf148)
Location: include/linux/skbuff.h:1995
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb
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
In kernel/audit.c (ffffffff811350b7)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff813af9e8)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff81485760)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
```
```
In drivers/connector/connector.c (ffffffff815d6b2d)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81699ba2)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff817bac11)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
```
```
In net/core/net_namespace.c (ffffffff817c28c4)
Location: include/linux/skbuff.h:2034
Inline: True
```
```
In net/core/neighbour.c (ffffffff817dd6f5)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff817e568f)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff817eadf8)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/fib_rules.c (ffffffff817f3eb6)
Location: include/linux/skbuff.h:2034
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817ff3fd)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81802158)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81803e62)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81807791)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff8180ad26)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff8181372c)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff8184f1e9)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff818561a9)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff8185dc26)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff8186a94b)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff8187eb84)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/addrconf.c (ffffffff8188e81c)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff818969c3)
Location: include/linux/skbuff.h:2034
Inline: True
```
```
In net/ipv6/route.c (ffffffff81898b46)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff818a70a6)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/mcast.c (ffffffff818b17fd)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (ffffffff818c1c89)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff818d691e)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff818e1e47)
Location: include/linux/skbuff.h:2034
Inline: True
```
```
In net/switchdev/switchdev.c (ffffffff818e5a88)
Location: include/linux/skbuff.h:2034
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb
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
In kernel/audit.c (ffffffff81141e07)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff813d5a98)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff814c18f0)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
```
```
In drivers/connector/connector.c (ffffffff8163d90d)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff816ff270)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8170434e)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81832ce1)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
```
```
In net/core/net_namespace.c (ffffffff8183c204)
Location: include/linux/skbuff.h:2121
Inline: True
```
```
In net/core/neighbour.c (ffffffff81857a75)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8186072f)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff818678d3)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/fib_rules.c (ffffffff8186f616)
Location: include/linux/skbuff.h:2121
Inline: True
```
```
In net/sched/sch_api.c (ffffffff8187d16d)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81880387)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8188249d)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff818862c1)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff81889c76)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff81892d86)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff818cee19)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff818d6039)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff818ddc56)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff818eb0cb)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffc24)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/addrconf.c (ffffffff8190fe6c)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81917e33)
Location: include/linux/skbuff.h:2121
Inline: True
```
```
In net/ipv6/route.c (ffffffff81919e46)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81929b05)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/mcast.c (ffffffff81933b7d)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (ffffffff819455c9)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff8195c4ee)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81967be7)
Location: include/linux/skbuff.h:2121
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
In kernel/audit.c (ffffffff811507d5)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff814060b8)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff814f2620)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
```
In drivers/connector/connector.c (ffffffff81678f18)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8173e9ec)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81742a8b)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8187d228)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/net_namespace.c (ffffffff81886c64)
Location: include/linux/skbuff.h:2132
Inline: True
```
```
In net/core/neighbour.c (ffffffff818a2bee)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818aa5ea)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff818b5703)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
```
```
In net/core/fib_rules.c (ffffffff818c0d70)
Location: include/linux/skbuff.h:2132
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818cf78d)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818d3118)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff818d5fc9)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/netlink/af_netlink.c (ffffffff818d9bf2)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff818dd74a)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff818e6e5f)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff818ecc85)
Location: include/linux/skbuff.h:2132
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81925bd5)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff8192c979)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff819347c0)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff819418ad)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81956528)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81961792)
Location: include/linux/skbuff.h:2132
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81967291)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff8196f4f3)
Location: include/linux/skbuff.h:2132
Inline: True
```
```
In net/ipv6/route.c (ffffffff81971f6e)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81981ca4)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/mcast.c (ffffffff8198c708)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (ffffffff8199d0ce)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819b5d05)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff819c1406)
Location: include/linux/skbuff.h:2132
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
In kernel/audit.c (ffffffff8115d472)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff81421c08)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff81506350)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
```
In drivers/connector/connector.c (ffffffff81697ff5)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8176264d)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817672fc)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8189de12)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/net_namespace.c (ffffffff818a7365)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff818c5890)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818d0487)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff818dc573)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/fib_rules.c (ffffffff818e9b7d)
Location: include/linux/skbuff.h:2210
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818fab2d)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818feaab)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff819027c7)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff81906694)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff8190a107)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff81913d3b)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8191a444)
Location: include/linux/skbuff.h:2210
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81954b6c)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff8195c107)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff8196410d)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81971159)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b36f)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81996033)
Location: include/linux/skbuff.h:2210
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8199c89e)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819a5083)
Location: include/linux/skbuff.h:2210
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a76bb)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff819b8350)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/mcast.c (ffffffff819c2f85)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (ffffffff819d3c2b)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819ecfc5)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff819f8966)
Location: include/linux/skbuff.h:2210
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a04252)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff81169bae)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff8144f7d4)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff81534d20)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
```
```
In drivers/connector/connector.c (ffffffff816d0b6f)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff817a0392)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a4b06)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff818e85e3)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff818f2405)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff819118e0)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8191d337)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff81929683)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/fib_rules.c (ffffffff819395d5)
Location: include/linux/skbuff.h:2298
Inline: True
```
```
In net/core/devlink.c (ffffffff8194f09e)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (ffffffff8195a3e0)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff8195e49e)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81963a2a)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff8196793b)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff8196b50b)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff81970fff)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_output.c (ffffffff8197c65f)
Location: include/linux/skbuff.h:2298
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819b8adc)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff819c0df9)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff819c9cc9)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff819d36d9)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff819da8d9)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff819f67f7)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a024b3)
Location: include/linux/skbuff.h:2298
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a08a7e)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a11523)
Location: include/linux/skbuff.h:2298
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a13d10)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a26da0)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/mcast.c (ffffffff81a31dc6)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (ffffffff81a41eab)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a5c1a5)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81a67c27)
Location: include/linux/skbuff.h:2298
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a734f4)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff81175a4e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff81469644)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff81555b50)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
```
```
In drivers/connector/connector.c (ffffffff816f498f)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff817c5342)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c8c06)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8191a823)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff81924355)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81943f50)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8194f966)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff81955d4d)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
```
```
In net/core/fib_rules.c (ffffffff8196c495)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/core/devlink.c (ffffffff81985e0e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (ffffffff81990880)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81994d6e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8199a5aa)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff8199e3cb)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff819a1ebb)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff819a79ff)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_output.c (ffffffff819b2fff)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819ef7dc)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff819f7999)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81a00889)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81a0a249)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81a1178c)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d46e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a3908b)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a3f18e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a48143)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a4a900)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a5d806)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/mcast.c (ffffffff81a68916)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (ffffffff81a78b0b)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a92dd5)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81a9e587)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa9ce4)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff811881ae)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_buffer_alloc
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff814bd807)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff815de900)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
```
In drivers/connector/connector.c (ffffffff817acfbf)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8188b51c)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8189328a)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff819ece53)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff819f8025)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81a13fc0)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff81a21184)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff81a2d5bd)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
```
```
In net/core/fib_rules.c (ffffffff81a4033d)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/devlink.c (ffffffff81a54860)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
```
In net/sched/sch_api.c (ffffffff81a689c0)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a6da9e)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81a73508)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81a77f7e)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff81a7b6db)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff81a9116a)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_output.c (ffffffff81a9cff9)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/devinet.c (ffffffff81addc1c)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81ae52be)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81aef9fb)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81afada9)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81b04a24)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1fd42)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81b2e7c0)
Location: include/linux/skbuff.h:2335
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b34e0e)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3efe3)
Location: include/linux/skbuff.h:2335
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b44e5c)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81b53b1b)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/mcast.c (ffffffff81b60c3c)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (ffffffff81b744d6)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81b8e0e5)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81b99607)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5ee4)
Location: include/linux/skbuff.h:2335
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff8118553e)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_buffer_alloc
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff814db267)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff815fbfa0)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
```
In drivers/connector/connector.c (ffffffff817c1b4f)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff818996c0)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a157a)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff819ecb13)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff819f7a85)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81a142e0)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff81a1f703)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff81a2ef7d)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
```
```
In net/core/fib_rules.c (ffffffff81a4303d)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/devlink.c (ffffffff81a5b7b9)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
```
In net/sched/sch_api.c (ffffffff81a710d0)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a7645e)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81a7c108)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81a80e30)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81a85728)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
```
```
In net/ipv4/route.c (ffffffff81a9afcf)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_output.c (ffffffff81aa6eb9)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/devinet.c (ffffffff81aea9fc)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81af218d)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81afc93b)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81b08479)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81b12b94)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e652)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81b3d210)
Location: include/linux/skbuff.h:2356
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b43a1e)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b4da63)
Location: include/linux/skbuff.h:2356
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b537dc)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81b6210b)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/mcast.c (ffffffff81b6f3ac)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (ffffffff81b83246)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81b9dd75)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81ba92b7)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb53c4)
Location: include/linux/skbuff.h:2356
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff8118653e)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff814e1bee)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff815debe0)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
```
In drivers/connector/connector.c (ffffffff817a506f)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8187bb30)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81883c0a)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff819d2ffa)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff819ddc05)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff819fac70)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81a067d3)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff81a1920b)
Location: include/linux/skbuff.h:2372
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81a27d9d)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/devlink.c (ffffffff81a49bbd)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
```
In net/sched/sch_api.c (ffffffff81a598a0)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a5e35e)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81a64d39)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81a695e9)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81a6e7e8)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
```
```
In net/ipv4/route.c (ffffffff81a863ef)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_output.c (ffffffff81a92039)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/devinet.c (ffffffff81ad613c)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81add97f)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae813a)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81af6da5)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81b008f2)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c362)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81b2a694)
Location: include/linux/skbuff.h:2372
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b3167e)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3b4f3)
Location: include/linux/skbuff.h:2372
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b40da0)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81b5036b)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/mcast.c (ffffffff81b5d3b9)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (ffffffff81b71ec9)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81b8ce75)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81b98447)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba43c4)
Location: include/linux/skbuff.h:2372
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff811ae92e)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff8153abee)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff8164a760)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
```
In drivers/connector/connector.c (ffffffff818309ef)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8190d060)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff819155b4)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8191a913)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/skbuff.c (ffffffff81a82cea)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff81a8de87)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81aac8b0)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81ab8c33)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff81ac74bb)
Location: include/linux/skbuff.h:2401
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81adcb3d)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/devlink.c (ffffffff81af8748)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
```
In net/sched/sch_api.c (ffffffff81b12960)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81b1753e)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81b1e009)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81b22ba5)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81b27e68)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
```
```
In net/ipv4/route.c (ffffffff81b40b2f)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_output.c (ffffffff81b4d449)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/devinet.c (ffffffff81b94e6c)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81b9ce1a)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba806f)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81bb66d5)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81bc1dd1)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0c92)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81bf0796)
Location: include/linux/skbuff.h:2401
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81bf771e)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81c01d13)
Location: include/linux/skbuff.h:2401
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c08a70)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81c1761b)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/mcast.c (ffffffff81c24b26)
Location: include/linux/skbuff.h:2401
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c379)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81c59215)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81c64f97)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c71f54)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff811df651)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff815d232f)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff81760f20)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
```
In drivers/connector/connector.c (ffffffff81971d80)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff81a62a52)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6ac93)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6fd60)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/skbuff.c (ffffffff81bf7a01)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff81c03ae7)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81c25810)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81c31e74)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff81c43d42)
Location: include/linux/skbuff.h:2769
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81c5e089)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/devlink.c (ffffffff81c84472)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
```
In net/sched/sch_api.c (ffffffff81c9af1a)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81c9f2ee)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81ca59ec)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81cab781)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81cafbb2)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff81ccd5d0)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_output.c (ffffffff81cdac15)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/devinet.c (ffffffff81d26ace)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81d2eeee)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3aa5d)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81d4a30d)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81d56116)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77b46)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81d88e55)
Location: include/linux/skbuff.h:2769
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81d90b8b)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81d9bc53)
Location: include/linux/skbuff.h:2769
Inline: True
```
```
In net/ipv6/route.c (ffffffff81da3521)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81db340b)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/mcast.c (ffffffff81dc1dd5)
Location: include/linux/skbuff.h:2769
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81dda73c)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81dfa975)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81e07b86)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e15ade)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
```
In net/mctp/device.c (ffffffff81e37f03)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff81e391c5)
Location: include/linux/skbuff.h:2769
Inline: True
```
```
In net/mctp/neigh.c (ffffffff81e3b3aa)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
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
In kernel/audit.c (ffffffff81225331)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff816801ef)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff8188fc00)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
```
In drivers/connector/connector.c (ffffffff81add000)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff81beef1b)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfda45)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c02bf0)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/skbuff.c (ffffffff81da6761)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff81db3197)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81dd7a50)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81de5244)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff81df7f32)
Location: include/linux/skbuff.h:2661
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81e148a9)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/devlink.c (ffffffff81e3ca02)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
```
In net/sched/sch_api.c (ffffffff81e573aa)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81e5b51e)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81e63a8c)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81e6c75f)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81e6d8d2)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff81e8d720)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_output.c (ffffffff81e9b42d)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/devinet.c (ffffffff81eee46e)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81ef6f4e)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81f033cd)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81f139ad)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81f20176)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/xfrm/xfrm_output.c (ffffffff81f443cc)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81f56c69)
Location: include/linux/skbuff.h:2661
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81f5f2ab)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81f6a8e3)
Location: include/linux/skbuff.h:2661
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f72961)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81f82d6b)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/mcast.c (ffffffff81f92e35)
Location: include/linux/skbuff.h:2661
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81fac45c)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81fcf125)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81fdd0c6)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81feca8e)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
```
In net/mctp/device.c (ffffffff82011133)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff82012485)
Location: include/linux/skbuff.h:2661
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82014a6a)
Location: include/linux/skbuff.h:2661
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
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
In kernel/audit.c (ffffffff8123b901)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff816b82cf)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff818d2070)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
```
In drivers/connector/connector.c (ffffffff81b2b270)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff81c46fbb)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81c534b6)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:page_to_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c62e17)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c682a0)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/skbuff.c (ffffffff81e15877)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff81e23767)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81e48860)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81e56c64)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff81e67614)
Location: include/linux/skbuff.h:2715
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81e881bd)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/sched/sch_api.c (ffffffff81eb33d5)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81eb7c45)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81ebfb22)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81ec87bf)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81ec99e2)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff81eebe40)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_output.c (ffffffff81ef9e6a)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/devinet.c (ffffffff81f4de2b)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81f569cb)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81f62dad)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81f7367d)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81f7fc76)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3bb8)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81fb66aa)
Location: include/linux/skbuff.h:2715
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fbefde)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81fca917)
Location: include/linux/skbuff.h:2715
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fd2a51)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81fe306b)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/mcast.c (ffffffff81ff30b2)
Location: include/linux/skbuff.h:2715
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8200cbfc)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/devlink/leftover.c (ffffffff82033c43)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_dpipe_entries_get
```
```
In net/devlink/health.c (ffffffff82047465)
Location: include/linux/skbuff.h:2715
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff8204ad55)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff82059196)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82068d2e)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
```
In net/mctp/device.c (ffffffff8208def3)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff8208f275)
Location: include/linux/skbuff.h:2715
Inline: True
```
```
In net/mctp/neigh.c (ffffffff8209188a)
Location: include/linux/skbuff.h:2715
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
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
In kernel/audit.c (ffffffff812557c1)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff816f4cff)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff81924040)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
```
In drivers/connector/connector.c (ffffffff81b82604)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff81cfc8d7)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81d09c66)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:page_to_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d19837)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81ed553b)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ensure_writable_head_tail
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff81ee16c7)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81f07420)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81f15fb7)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff81f267d4)
Location: include/linux/skbuff.h:2722
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81f4a1cd)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/sched/sch_api.c (ffffffff81f75ee5)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81f7ac55)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81f82cd2)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81f8bacc)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81f8cab5)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff81fafe90)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_output.c (ffffffff81fbddac)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/devinet.c (ffffffff82013f5b)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff8201ce6c)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff8202937d)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff82039e6d)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff820462f6)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/xfrm/xfrm_output.c (ffffffff82070ee5)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff82083d5d)
Location: include/linux/skbuff.h:2722
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8208c46e)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff820980b7)
Location: include/linux/skbuff.h:2722
Inline: True
```
```
In net/ipv6/route.c (ffffffff820a0361)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff820b0f8b)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/mcast.c (ffffffff820c0d5f)
Location: include/linux/skbuff.h:2722
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820dbbcc)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/devlink/dpipe.c (ffffffff8210bfe3)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devlink_nl_dpipe_entries_get_doit
```
```
In net/devlink/resource.c (ffffffff8210c8f7)
Location: include/linux/skbuff.h:2722
Inline: True
```
```
In net/devlink/health.c (ffffffff821133a0)
Location: include/linux/skbuff.h:2722
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff8211d1d5)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff8212bd16)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213bfae)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
```
In net/mctp/device.c (ffffffff821643b3)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff82165755)
Location: include/linux/skbuff.h:2722
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82167e2a)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
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
In kernel/audit.c (ffff8000101ea91c)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffff800010557ad0)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffff800010662038)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
```
```
In drivers/connector/connector.c (ffff8000108ddd64)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffff8000109e05bc)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a03034)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffff800010bb4ba0)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (0)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffff800010be3df4)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffff800010bf1678)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffff800010bfd13c)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/fib_rules.c (ffff800010c12d58)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (ffff800010c3cb28)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffff800010c418f8)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/sched/act_api.c (ffff800010c477b8)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffff800010c4b9fc)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffff800010c50b0c)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffff800010c572d8)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_output.c (ffff800010c629dc)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv4/devinet.c (ffff800010ca5680)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffff800010cadb1c)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffff800010cb8ec0)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffff800010cc375c)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffff800010cc9ecc)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffff800010cebf74)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffff800010cf9020)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv6/addrconf.c (ffff800010d02670)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffff800010d0b434)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv6/route.c (ffff800010d0da18)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffff800010d22a98)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/mcast.c (ffff800010d2dfec)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (ffff800010d42288)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffff800010d60bf8)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffff800010d6ef74)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d9b8)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (c042a614)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (c070c9f8)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (c080b0b4)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
```
```
In drivers/connector/connector.c (c09ccdd8)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (c0ac4728)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (c0adde5c)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (c0cd1cac)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (c0cdb7a4)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (c0cfe310)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (c0d09e28)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (c0d17730)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/fib_rules.c (c0d2a668)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/devlink.c (c0d45424)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (c0d4e880)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (c0d53714)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (c0d585b8)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (c0d5c2b0)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (c0d607b8)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (c0d66f44)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_output.c (c0d73384)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/devinet.c (c0db1fb0)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (c0dbab08)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (c0dc45f0)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (c0dcef24)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (c0dd5e20)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (c0df3eac)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (c0e007e0)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
```
```
In net/ipv6/addrconf.c (c0e08494)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (c0e11400)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv6/route.c (c0e14274)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (c0e27040)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/mcast.c (c0e32954)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (c0e44bd4)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (c0e60420)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/dcb/dcbnl.c (c0e6cc38)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (c0e784ec)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (c00000000025bcac)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (c0000000006b5a14)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (c000000000816390)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
```
```
In drivers/connector/connector.c (c000000000971580)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (c000000000aa1964)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa8fc8)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (c000000000c8b6d0)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (c000000000c990dc)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (c000000000cc721c)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (c000000000cd6158)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (c000000000ce5608)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/fib_rules.c (c000000000cffce0)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/core/devlink.c (c000000000d2489c)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (c000000000d37c10)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (c000000000d3d5a4)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (c000000000d44690)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (c000000000d49b58)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (c000000000d4f768)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (c000000000d5882c)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_output.c (c000000000d675e0)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv4/devinet.c (c000000000db9510)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (c000000000dc4cb4)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (c000000000dd1a9c)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (c000000000ddf3bc)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (c000000000de9308)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (c000000000e10040)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (c000000000e20be0)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv6/addrconf.c (c000000000e29ef8)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (c000000000e35a88)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv6/route.c (c000000000e397d8)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (c000000000e52768)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/mcast.c (c000000000e61bbc)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (c000000000e77070)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (c000000000e9bf3c)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (c000000000eac2b8)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebd4f0)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffe00015f2be)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffe0003af41e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffe00048e9cc)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:__nla_reserve_64bit
```
```
In drivers/connector/connector.c (ffffffe000574312)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffe00062a47a)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062d46a)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffe000744c2e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffe00074d58a)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffe00076a854)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffe0007733f4)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffe00077fb3a)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/fib_rules.c (ffffffe00078e79c)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/core/devlink.c (ffffffe0007a0088)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (ffffffe0007ad3b6)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffe0007b12b2)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffe0007b54e6)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffe0007b8f2a)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffe0007bbfc6)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffe0007c1634)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_output.c (ffffffe0007cb426)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv4/devinet.c (ffffffe000800f4a)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffe00080819e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffe00080fca4)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffe0008189fa)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffe00081f3b0)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffe0008397f0)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffe000844e98)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffe00084aab6)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffe0008526a0)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv6/route.c (ffffffe0008556ce)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffe00086459e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/mcast.c (ffffffe00086ea1e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (ffffffe00087d976)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffe000895e58)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/dcb/dcbnl.c (ffffffe0008a0c12)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008ab1d4)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff8116e06e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff81461c24)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff8154e130)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
```
```
In drivers/connector/connector.c (ffffffff816ba17f)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff81789e22)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178d6e6)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff818ba823)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff818c4355)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff818e3f20)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818ef936)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff818f5d1d)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
```
```
In net/core/fib_rules.c (ffffffff8190c465)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/core/devlink.c (ffffffff81925c7e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (ffffffff819306f0)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81934bde)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8193a41a)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff8193e23b)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff81941d2b)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff8194786f)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_output.c (ffffffff81952e6f)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8198f57c)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81997739)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff819a0629)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff819a9fe9)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff819b10e9)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff819ccafe)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819d871b)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819de81e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819e77d3)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv6/route.c (ffffffff819e9f90)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff819fce96)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/mcast.c (ffffffff81a07fa6)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (ffffffff81a1819b)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a32465)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81a3d917)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a49074)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff8116120e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff81452654)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff8153e410)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
```
```
In drivers/connector/connector.c (ffffffff81697dbf)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_transport_fc.c (ffffffff8170f7a8)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_fc.c:fc_host_post_fc_event
```
```
In drivers/net/tun.c (ffffffff81769772)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/vxlan.c (ffffffff8176cd18)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fdb_info
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817764b6)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff81874773)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff8187e295)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff8189dd60)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818a9776)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff818afb4d)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
```
```
In net/core/fib_rules.c (ffffffff818c6225)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/core/devlink.c (ffffffff818dfa2e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (ffffffff818ea1f0)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818ee6de)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff818f3f1a)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff818f7d3b)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff818fb81b)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff8190135f)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_output.c (ffffffff8190c95f)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8194903c)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff819511f9)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff8195a0e9)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81963aa9)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff8196d719)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff819898ee)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819954db)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8199b5de)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819a4593)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a6d50)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff819b9c56)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/mcast.c (ffffffff819c4d66)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (ffffffff819d4f5b)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819ef655)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff819fa507)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a05c64)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff8116be3e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff8145dcc4)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff81549e70)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
```
```
In drivers/connector/connector.c (ffffffff816e864f)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff817ba1c2)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bda86)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8190b823)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff81915355)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81934f50)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81940966)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff81946d4d)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
```
```
In net/core/fib_rules.c (ffffffff8195d495)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/core/devlink.c (ffffffff81976e0e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (ffffffff81981880)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81985d6e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8198b5aa)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff8198f3cb)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff81992ebb)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff81999ad3)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199c8ee)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:nfulnl_log_packet
  - net/netfilter/nfnetlink_log.c:__build_packet_message
  - net/netfilter/nfnetlink_log.c:__build_packet_message
  - net/netfilter/nfnetlink_log.c:__nfulnl_send
  - net/netfilter/nfnetlink_log.c:__nfulnl_send
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ae6bc)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_stat_cpu_dump
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_expect_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_stat_ct
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_ct_stat_cpu_dump
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_fill_info
```
```
In net/ipv4/route.c (ffffffff819b203f)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_output.c (ffffffff819bd63f)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819f9e1c)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81a01fd9)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0aec9)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81a14889)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81a1b989)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81a3757e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a4319b)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a4929e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a52253)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a54a10)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a67916)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/mcast.c (ffffffff81a72a26)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (ffffffff81a82c1b)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a9e015)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81aa97c7)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4f24)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff811795fe)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff81475464)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/nlattr.c (ffffffff81563cc0)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_reserve_64bit
```
```
In drivers/connector/connector.c (ffffffff81702d4f)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff817d26c2)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d82b6)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/skbuff.c (ffffffff8192c943)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff81936535)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81956660)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81962276)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff8196865d)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
```
```
In net/core/fib_rules.c (ffffffff8197f6e5)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/core/devlink.c (ffffffff819992fe)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (ffffffff819a3ded)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff819a8d6e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff819ade1a)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff819b1cab)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff819b59ab)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff819bb6ff)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_output.c (ffffffff819c6f4f)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81a0412c)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81a0c50a)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81a156a9)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81a1f299)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81a2689c)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42f1f)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a4ee3b)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a551be)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a5e243)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a60a00)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a73f05)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/mcast.c (ffffffff81a7f0a6)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/ip6mr.c (ffffffff81a8f4eb)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81aaa215)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81ab5b37)
Location: include/linux/skbuff.h:2312
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac12c4)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
</details>
</li>
</ul>

## Differences
