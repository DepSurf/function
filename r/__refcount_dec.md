# Function: <code>__refcount_dec</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138e878)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - fs/io_uring.c:io_poll_double_wake
  - fs/io_uring.c:io_poll_remove_double
```
```
In fs/fuse/dev.c (ffffffff81489db5)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff819e47c6)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/core/sock.c:sk_stop_timer_sync
  - net/core/sock.c:sk_stop_timer
```
```
In net/core/datagram.c (ffffffff819f48a8)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/netlink/af_netlink.c (ffffffff81a82e0c)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aae72a)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf439)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff81ab384a)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81abbac0)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81aca222)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1b69)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff81adc235)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81ae0efa)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81ae7e24)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff81af5c13)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/inet_fragment.c (ffffffff81b0300c)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2abc1)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81b347e3)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff81b48354)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ndisc.c (ffffffff81b62631)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81b739db)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b87386)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93cb2)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81b9a3c6)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81bb64ac)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81bbf834)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc79f0)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
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
In fs/fuse/dev.c (ffffffff8148f9c5)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff819ca846)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/core/sock.c:sk_stop_timer_sync
  - net/core/sock.c:sk_stop_timer
```
```
In net/core/datagram.c (ffffffff819da978)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/netlink/af_netlink.c (ffffffff81a6bedc)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a9980e)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a749)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff81a9ed2a)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81aa6a80)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ab50b0)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abcb88)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff81ac71a5)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81acc21b)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81ad30df)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff81ae1366)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee8fc)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff81b187e7)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81b225f2)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff81b35f38)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ndisc.c (ffffffff81b508e8)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81b62185)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b76058)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82dc2)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81b8932b)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba546c)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81bb05c5)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb8d6c)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
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
In fs/fuse/dev.c (ffffffff814e7435)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff81a79876)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/core/sock.c:sk_stop_timer_sync
  - net/core/sock.c:sk_stop_timer
```
```
In net/core/datagram.c (ffffffff81a8aff8)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/devlink.c (ffffffff81af2ea6)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_rate_nodes_destroy
  - net/core/devlink.c:devlink_rate_leaf_destroy
  - net/core/devlink.c:devlink_nl_cmd_rate_del_doit
  - net/core/devlink.c:devlink_nl_rate_parent_node_set
```
```
In net/netlink/af_netlink.c (ffffffff81b25549)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b54c8e)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55bb9)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff81b5acca)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81b62e70)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81b7208f)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b79918)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff81b859c5)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81b8aaab)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81b91d2f)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff81ba0a26)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/inet_fragment.c (ffffffff81baecce)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff81bdcbd7)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81be9341)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff81bfc698)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ndisc.c (ffffffff81c17c98)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81c29c15)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81c40ac8)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4ee92)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81c5543b)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81c72fec)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81c7e47f)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/pm_netlink.c (ffffffff81c884bc)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff81574346)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff81bed370)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/core/datagram.c (ffffffff81c0077a)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/devlink.c (ffffffff81c76d14)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/core/devlink.c:devl_rate_nodes_destroy
  - net/core/devlink.c:devl_rate_leaf_destroy
  - net/core/devlink.c:devlink_nl_cmd_rate_del_doit
  - net/core/devlink.c:devlink_nl_rate_parent_node_set
```
```
In net/netlink/af_netlink.c (ffffffff81cae04e)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/bpf/test_run.c (ffffffff81cb4a1e)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_kfunc_call_test_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce288f)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3879)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff81ce94bb)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1b35)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81d0178e)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d09690)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff81d19893)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81d23224)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff81d32f12)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41ff4)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff81d7395c)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81d804c5)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff81d95fc9)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ndisc.c (ffffffff81db3cd0)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81dc704f)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81ddf1e9)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def867)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81df51d8)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81e16d76)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81e23886)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2ebdc)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
```
In net/mctp/af_mctp.c (ffffffff81e37c2e)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
**Symbols:**

```
ffffffff81d2f0f0-ffffffff81d2f123: __refcount_dec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff81619bcb)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff81d99640)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/core/datagram.c (ffffffff81db049c)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/devlink.c (ffffffff81e2fae4)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/core/devlink.c:devl_rate_nodes_destroy
  - net/core/devlink.c:devl_rate_leaf_destroy
  - net/core/devlink.c:devlink_nl_cmd_rate_del_doit
  - net/core/devlink.c:devlink_nl_rate_parent_node_set
  - net/core/devlink.c:devlink_nl_rate_parent_node_set
```
```
In net/netlink/af_netlink.c (ffffffff81e6b61e)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/bpf/test_run.c (ffffffff81e72d9e)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_kfunc_call_test_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea3cfc)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea6197)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff81eac91b)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81eb6385)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ec68ee)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ece94e)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff81ee01ee)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/arp.c (ffffffff81eea726)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff81efb1d2)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0ae24)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3f992)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81f4b76e)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/addrconf.c (ffffffff81f64879)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ndisc.c (ffffffff81f83690)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81f97cef)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81fb1429)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3937)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81fc7b58)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81fee746)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81ffaff4)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/pm_netlink.c (ffffffff82006d7c)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
```
In net/mctp/af_mctp.c (ffffffff82010eb5)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
**Symbols:**

```
ffffffff81ef7170-ffffffff81ef71a3: __refcount_dec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff81651d7b)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff81e07960)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/core/datagram.c (ffffffff81e2094c)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/netlink/af_netlink.c (ffffffff81ec765e)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/bpf/test_run.c (ffffffff81ecedf5)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_kfunc_call_test_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f02568)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04947)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff81f0b14b)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81f147a5)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81f25070)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2dd04)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff81f3bb47)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81f3f6ae)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/arp.c (ffffffff81f4a076)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff81f5ac62)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a964)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ping.c (ffffffff81f6b597)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9f2b2)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81fab515)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/addrconf.c (ffffffff81fc4853)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ndisc.c (ffffffff81fe39e0)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81ff86df)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff82011ad9)
Location: include/linux/refcount.h:336
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82024782)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff82028aef)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/devlink/leftover.c (ffffffff820331ba)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/devlink/leftover.c:devl_rate_nodes_destroy
  - net/devlink/leftover.c:devl_rate_leaf_destroy
  - net/devlink/leftover.c:devlink_nl_cmd_rate_del_doit
  - net/devlink/leftover.c:devlink_nl_rate_parent_node_set
  - net/devlink/leftover.c:devlink_nl_rate_parent_node_set
```
```
In net/xdp/xsk.c (ffffffff8206a84a)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff82075f9d)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/pm_netlink.c (ffffffff8208311c)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
```
In net/mctp/af_mctp.c (ffffffff8208dc75)
Location: include/linux/refcount.h:336
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
**Symbols:**

```
ffffffff81f56bf0-ffffffff81f56c23: __refcount_dec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168b38b)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In drivers/dpll/dpll_core.c (ffffffff81eb747d)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - drivers/dpll/dpll_core.c:dpll_pin_on_pin_unregister
  - drivers/dpll/dpll_core.c:dpll_pin_on_pin_register
```
```
In net/core/sock.c (ffffffff81ec43a0)
Location: include/linux/refcount.h:325
Inline: True
```
```
In net/core/datagram.c (ffffffff81ede81c)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/netlink/af_netlink.c (ffffffff81f8a99e)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/bpf/test_run.c (ffffffff81f92695)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_kfunc_call_test_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc82ba)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8c47)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff81fcee1b)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81fd8c85)
Location: include/linux/refcount.h:325
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81fe994c)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7596)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff82001c67)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff820055de)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/arp.c (ffffffff82010196)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff820211a2)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/inet_fragment.c (ffffffff82031014)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ping.c (ffffffff82031977)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/xfrm/xfrm_state.c (ffffffff8206c612)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff82078905)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/addrconf.c (ffffffff82091e03)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ndisc.c (ffffffff820b18f0)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff820c6347)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e0a71)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_ifdown
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3a92)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff820f852f)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/devlink/rate.c (ffffffff82117fca)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/devlink/rate.c:devl_rate_nodes_destroy
  - net/devlink/rate.c:devl_rate_leaf_destroy
  - net/devlink/rate.c:devlink_nl_rate_del_doit
  - net/devlink/rate.c:devlink_nl_rate_parent_node_set
  - net/devlink/rate.c:devlink_nl_rate_parent_node_set
```
```
In net/xdp/xsk.c (ffffffff8213e47b)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff8214a51f)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/pm_netlink.c (ffffffff821587ac)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
```
In net/mctp/af_mctp.c (ffffffff82164135)
Location: include/linux/refcount.h:325
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
**Symbols:**

```
ffffffff8201d090-ffffffff8201d0c3: __refcount_dec.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
