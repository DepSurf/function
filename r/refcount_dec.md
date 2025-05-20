# Function: <code>refcount_dec</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136cbd5)
Location: include/linux/refcount.h:86
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff817b3c19)
Location: include/linux/refcount.h:86
Inline: True
```
```
In net/core/datagram.c (ffffffff817bf4a6)
Location: include/linux/refcount.h:86
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/netlink/af_netlink.c (ffffffff818098b8)
Location: include/linux/refcount.h:86
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inetpeer.c (ffffffff81813e46)
Location: include/linux/refcount.h:86
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_putpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181f04f)
Location: include/linux/refcount.h:86
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181fbfd)
Location: include/linux/refcount.h:86
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_output.c (ffffffff81836922)
Location: include/linux/refcount.h:86
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/raw.c (ffffffff8184336e)
Location: include/linux/refcount.h:86
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8184761a)
Location: include/linux/refcount.h:86
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8184cde5)
Location: include/linux/refcount.h:86
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff81858c5a)
Location: include/linux/refcount.h:86
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/inet_fragment.c (ffffffff818628cf)
Location: include/linux/refcount.h:86
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff8187cf1d)
Location: include/linux/refcount.h:86
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81882da6)
Location: include/linux/refcount.h:86
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff8189175c)
Location: include/linux/refcount.h:86
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ndisc.c (ffffffff818a4ad8)
Location: include/linux/refcount.h:86
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff818b44dc)
Location: include/linux/refcount.h:86
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff818c4f67)
Location: include/linux/refcount.h:86
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce689)
Location: include/linux/refcount.h:86
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff818d1466)
Location: include/linux/refcount.h:86
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In fs/fuse/dev.c (ffffffff81391855)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff8182be39)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
```
```
In net/core/datagram.c (ffffffff81838e26)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/rtnetlink.c (ffffffff8185bbf2)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
```
In net/netlink/af_netlink.c (ffffffff818887fb)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189dfff)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189eb91)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_output.c (ffffffff818b5fa8)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/raw.c (ffffffff818c2d3e)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff818c707a)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
```
```
In net/ipv4/arp.c (ffffffff818ccafb)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff818d8b3a)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/inet_fragment.c (ffffffff818e29ef)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff818fdcf7)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81905156)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff8191338b)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:addrconf_del_dad_work
```
```
In net/ipv6/ndisc.c (ffffffff819274c2)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff8193725c)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81948015)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81953551)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81956386)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__unregister_prot_hook
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
In fs/fuse/dev.c (ffffffff813c0c11)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff81876029)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
```
```
In net/core/datagram.c (ffffffff81883573)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/netlink/af_netlink.c (ffffffff818dc237)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f29ab)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f35e1)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff818fb83e)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff8190882c)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190df29)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff8191882e)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8191db6a)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81922fdb)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff8192f50a)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/inet_fragment.c (ffffffff819391cf)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff81954867)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff8195a7a1)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff8196aee0)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:addrconf_del_dad_work
```
```
In net/ipv6/ndisc.c (ffffffff8197f85e)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff8198ffdb)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a12dd)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819acf83)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff819b17ac)
Location: arch/x86/include/asm/refcount.h:58
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__unregister_prot_hook
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
In fs/fuse/dev.c (ffffffff813da8d1)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff818968a9)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/core/datagram.c (ffffffff818a3fc3)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/netlink/af_netlink.c (ffffffff81908c06)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff8192041b)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81921101)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff8192979e)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81936a96)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193c319)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff81946ffe)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8194c0ea)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81951dcb)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff8195e9ca)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/inet_fragment.c (ffffffff81968d9c)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff81988f75)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff8198f491)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff8199feb0)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:addrconf_del_dad_work
```
```
In net/ipv6/ndisc.c (ffffffff819b5e4e)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff819c686b)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d7dbd)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e393a)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff819e8b8c)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__unregister_prot_hook
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
In fs/fuse/dev.c (ffffffff81405d4f)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff818e0cb9)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/core/datagram.c (ffffffff818ef2ba)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/devlink.c (ffffffff81946295)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_put
```
```
In net/netlink/af_netlink.c (ffffffff81969d34)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81982d41)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81983ac6)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff8198c85f)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff8199aef8)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a0757)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff819ab682)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819b08d7)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819b668b)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff819c3843)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf86b)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff819f2d94)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff819faca1)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff81a0c16f)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:addrconf_del_dad_work
```
```
In net/ipv6/ndisc.c (ffffffff81a2492f)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81a3569b)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a46dc3)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a52670)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81a58f01)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__unregister_prot_hook
```
```
In net/xdp/xsk.c (ffffffff81a747e9)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In fs/io_uring.c (ffffffff81343bd9)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/fuse/dev.c (ffffffff814208b6)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff81912e79)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/core/datagram.c (ffffffff8192126a)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/devlink.c (ffffffff8197b225)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_put
```
```
In net/netlink/af_netlink.c (ffffffff819a07a4)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b95a1)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba2b2)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff819c31cf)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819d191d)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d7319)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff819e234e)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819e756a)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819ed3ab)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff819fa3e3)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/inet_fragment.c (ffffffff81a063fb)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff81a29c64)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81a31931)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff81a42e1f)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:addrconf_del_dad_work
```
```
In net/ipv6/ndisc.c (ffffffff81a5b3af)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81a6c1db)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a7d973)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a89280)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81a8f011)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__unregister_prot_hook
```
```
In net/xdp/xsk.c (ffffffff81aab19f)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In fs/io_uring.c (ffffffff8137fd42)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - fs/io_uring.c:io_poll_double_wake
  - fs/io_uring.c:io_poll_remove_double
```
```
In fs/io-wq.c (ffffffff8138a9e1)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_manager
```
```
In fs/fuse/dev.c (ffffffff8146f643)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff819e3d36)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/core/sock.c:sk_stop_timer
```
```
In net/core/datagram.c (ffffffff819f4bb8)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/devlink.c (ffffffff81a5a057)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
```
In net/netlink/af_netlink.c (ffffffff81a79fa1)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa4101)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4dd9)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff81aa952a)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0980)
Location: include/linux/refcount.h:307
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81abe8df)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5f48)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff81acf955)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81ad49ba)
Location: include/linux/refcount.h:307
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81adb354)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff81ae8d03)
Location: include/linux/refcount.h:307
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
In net/ipv4/inet_fragment.c (ffffffff81af6197)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1c407)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81b25e3d)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff81b39654)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ndisc.c (ffffffff81b5401c)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81b6523b)
Location: include/linux/refcount.h:307
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
In net/ipv6/xfrm6_policy.c (ffffffff81b78421)
Location: include/linux/refcount.h:307
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b84453)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81b8b3f6)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba7643)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81bac1ed)
Location: include/linux/refcount.h:307
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_sk_clone
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
In fs/io_uring.c (ffffffff8138e878)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - fs/io_uring.c:io_poll_double_wake
  - fs/io_uring.c:io_poll_remove_double
```
```
In fs/fuse/dev.c (ffffffff81489db5)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff819e47c6)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/core/sock.c:sk_stop_timer_sync
  - net/core/sock.c:sk_stop_timer
```
```
In net/core/datagram.c (ffffffff819f48a8)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/netlink/af_netlink.c (ffffffff81a82e0c)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aae72a)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf439)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff81ab384a)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81abbac0)
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81aca222)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff81adc235)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81ae0efa)
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81ae7e24)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff81af5c13)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2abc1)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81b347e3)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff81b48354)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ndisc.c (ffffffff81b62631)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81b739db)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93cb2)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81b9a3c6)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81bb64ac)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81bbf834)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc79f0)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff819ca846)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/core/sock.c:sk_stop_timer_sync
  - net/core/sock.c:sk_stop_timer
```
```
In net/core/datagram.c (ffffffff819da978)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/netlink/af_netlink.c (ffffffff81a6bedc)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a9980e)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a749)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff81a9ed2a)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81aa6a80)
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ab50b0)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff81ac71a5)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81acc21b)
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81ad30df)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff81ae1366)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff81b187e7)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81b225f2)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff81b35f38)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ndisc.c (ffffffff81b508e8)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81b62185)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82dc2)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81b8932b)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba546c)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81bb05c5)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb8d6c)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff81a79876)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/core/sock.c:sk_stop_timer_sync
  - net/core/sock.c:sk_stop_timer
```
```
In net/core/datagram.c (ffffffff81a8aff8)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/devlink.c (ffffffff81af2ea6)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_rate_nodes_destroy
  - net/core/devlink.c:devlink_rate_leaf_destroy
  - net/core/devlink.c:devlink_nl_cmd_rate_del_doit
  - net/core/devlink.c:devlink_nl_rate_parent_node_set
```
```
In net/netlink/af_netlink.c (ffffffff81b25549)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b54c8e)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55bb9)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff81b5acca)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81b62e70)
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81b7208f)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff81b859c5)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81b8aaab)
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81b91d2f)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff81ba0a26)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff81bdcbd7)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81be9341)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff81bfc698)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ndisc.c (ffffffff81c17c98)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81c29c15)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4ee92)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81c5543b)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81c72fec)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81c7e47f)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/pm_netlink.c (ffffffff81c884bc)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
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
In fs/fuse/dev.c (ffffffff81574346)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff81bed370)
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/core/datagram.c (ffffffff81c0077a)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/devlink.c (ffffffff81c76d14)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/core/devlink.c:devl_rate_nodes_destroy
  - net/core/devlink.c:devl_rate_leaf_destroy
  - net/core/devlink.c:devlink_nl_cmd_rate_del_doit
  - net/core/devlink.c:devlink_nl_rate_parent_node_set
```
```
In net/netlink/af_netlink.c (ffffffff81cae04e)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/bpf/test_run.c (ffffffff81cb4a1e)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_kfunc_call_test_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce288f)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3879)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff81ce94bb)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1b35)
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81d0178e)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff81d19893)
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81d23224)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff81d32f12)
Location: include/linux/refcount.h:357
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
In net/ipv4/inet_fragment.c (ffffffff81d41ff4)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff81d7395c)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81d804c5)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff81d95fc9)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ndisc.c (ffffffff81db3cd0)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81dc704f)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def867)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81df51d8)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81e16d76)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81e23886)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2ebdc)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
```
In net/mctp/af_mctp.c (ffffffff81e37c2e)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
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
In fs/fuse/dev.c (ffffffff81619bcb)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff81d99640)
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/core/datagram.c (ffffffff81db049c)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/devlink.c (ffffffff81e2fae4)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/bpf/test_run.c (ffffffff81e72d9e)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_kfunc_call_test_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea3cfc)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea6197)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff81eac91b)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81eb6385)
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ec68ee)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff81ee01ee)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/arp.c (ffffffff81eea726)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff81efb1d2)
Location: include/linux/refcount.h:357
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
In net/ipv4/inet_fragment.c (ffffffff81f0ae24)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3f992)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81f4b76e)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/addrconf.c (ffffffff81f64879)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ndisc.c (ffffffff81f83690)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81f97cef)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3937)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81fc7b58)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81fee746)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81ffaff4)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/pm_netlink.c (ffffffff82006d7c)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
```
In net/mctp/af_mctp.c (ffffffff82010eb5)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
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
In fs/fuse/dev.c (ffffffff81651d7b)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff81e07960)
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/core/datagram.c (ffffffff81e2094c)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/netlink/af_netlink.c (ffffffff81ec765e)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/bpf/test_run.c (ffffffff81ecedf5)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_kfunc_call_test_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f02568)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04947)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff81f0b14b)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81f147a5)
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81f25070)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff81f3bb47)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81f3f6ae)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/arp.c (ffffffff81f4a076)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff81f5ac62)
Location: include/linux/refcount.h:357
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
In net/ipv4/inet_fragment.c (ffffffff81f6a964)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ping.c (ffffffff81f6b597)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9f2b2)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81fab515)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/addrconf.c (ffffffff81fc4853)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ndisc.c (ffffffff81fe39e0)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81ff86df)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82024782)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff82028aef)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/devlink/leftover.c (ffffffff820331ba)
Location: include/linux/refcount.h:357
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
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff82075f9d)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/pm_netlink.c (ffffffff8208311c)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
```
In net/mctp/af_mctp.c (ffffffff8208dc75)
Location: include/linux/refcount.h:357
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
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
In fs/fuse/dev.c (ffffffff8168b38b)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In drivers/dpll/dpll_core.c (ffffffff81eb747d)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - drivers/dpll/dpll_core.c:dpll_pin_on_pin_unregister
  - drivers/dpll/dpll_core.c:dpll_pin_on_pin_register
```
```
In net/core/sock.c (ffffffff81ec43a0)
Location: include/linux/refcount.h:346
Inline: True
```
```
In net/core/datagram.c (ffffffff81ede81c)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/netlink/af_netlink.c (ffffffff81f8a99e)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/bpf/test_run.c (ffffffff81f92695)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_kfunc_call_test_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc82ba)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8c47)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff81fcee1b)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81fd8c85)
Location: include/linux/refcount.h:346
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81fe994c)
Location: include/linux/refcount.h:346
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
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff82001c67)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff820055de)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/arp.c (ffffffff82010196)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff820211a2)
Location: include/linux/refcount.h:346
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
In net/ipv4/inet_fragment.c (ffffffff82031014)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ping.c (ffffffff82031977)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/xfrm/xfrm_state.c (ffffffff8206c612)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff82078905)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/addrconf.c (ffffffff82091e03)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ndisc.c (ffffffff820b18f0)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff820c6347)
Location: include/linux/refcount.h:346
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
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_ifdown
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3a92)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff820f852f)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/devlink/rate.c (ffffffff82117fca)
Location: include/linux/refcount.h:346
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
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff8214a51f)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/pm_netlink.c (ffffffff821587ac)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
```
In net/mctp/af_mctp.c (ffffffff82164135)
Location: include/linux/refcount.h:346
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050e594)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/fuse/dev.c (c000000000646058)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (c000000000c80a58)
Location: include/linux/refcount.h:104
Inline: True
```
```
In net/core/datagram.c (c000000000c94544)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/devlink.c (c000000000d17638)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
```
In net/netlink/af_netlink.c (c000000000d4d628)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (c000000000d6ffb8)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d71308)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (c000000000d76d24)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (c000000000d90148)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (c000000000d97d68)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (c000000000da790c)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (c000000000dac8e0)
Location: include/linux/refcount.h:104
Inline: True
```
```
In net/ipv4/arp.c (c000000000db6618)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (c000000000dc8a74)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/inet_fragment.c (c000000000dd9db0)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (c000000000e0ba88)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (c000000000e17ff0)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (c000000000e2efbc)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ndisc.c (c000000000e4f0f8)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (c000000000e664a8)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7e054)
Location: include/linux/refcount.h:104
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8f11c)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (c000000000e97c84)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c000000000ebf300)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In fs/io_uring.c (ffffffe0002af886)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/fuse/dev.c (ffffffe00037030e)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffe00073ce54)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/core/sock.c:sk_stop_timer
```
```
In net/core/datagram.c (ffffffe00074a68c)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/devlink.c (ffffffe00079c26a)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
```
In net/netlink/af_netlink.c (ffffffe0007babfc)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d09c6)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d170a)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffe0007d4a98)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffe0007e5f78)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb2d6)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffe0007f53da)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffe0007f99fa)
Location: include/linux/refcount.h:104
Inline: True
```
```
In net/ipv4/arp.c (ffffffe0007fefe0)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffe00080a4bc)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/inet_fragment.c (ffffffe00081507e)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffe000835428)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffe00083e1fa)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffe00084fa02)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ndisc.c (ffffffe000862462)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffe000871e90)
Location: include/linux/refcount.h:104
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
In net/ipv6/xfrm6_policy.c (ffffffe000882242)
Location: include/linux/refcount.h:104
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d906)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffe0008923e0)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffe0008ac224)
Location: include/linux/refcount.h:104
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In fs/io_uring.c (ffffffff8133c1b9)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/fuse/dev.c (ffffffff81418e96)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff818b2e79)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/core/datagram.c (ffffffff818c126a)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/devlink.c (ffffffff8191b095)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_put
```
```
In net/netlink/af_netlink.c (ffffffff81940614)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81959411)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8195a122)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff8196303f)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff8197178d)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81977189)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff819821be)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819873da)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8198d14b)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff8199a183)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/inet_fragment.c (ffffffff819a619b)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff819c92f4)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff819d0fc1)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff819e24af)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:addrconf_del_dad_work
```
```
In net/ipv6/ndisc.c (ffffffff819faa3f)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81a0b86b)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a1d003)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a28910)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81a2e6a1)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__unregister_prot_hook
```
```
In net/xdp/xsk.c (ffffffff81a4a52f)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In fs/io_uring.c (ffffffff8132ce89)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/fuse/dev.c (ffffffff81409916)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff8186cdc9)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/core/datagram.c (ffffffff8187b1aa)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/devlink.c (ffffffff818d4e45)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_put
```
```
In net/netlink/af_netlink.c (ffffffff818fa104)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81912f01)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913c12)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff8191cb2f)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff8192b25d)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81930c49)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff8193bc7e)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81940e9a)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81946c0b)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff81953c43)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fc5b)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff819860e4)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff8198dd81)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff8199f26f)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:addrconf_del_dad_work
```
```
In net/ipv6/ndisc.c (ffffffff819b77ff)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff819c862b)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d9dc3)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e56d0)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff819eb891)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__unregister_prot_hook
```
```
In net/xdp/xsk.c (ffffffff81a0711f)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In fs/io_uring.c (ffffffff81339c89)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/fuse/dev.c (ffffffff81415036)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff81903e79)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/core/datagram.c (ffffffff8191226a)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/devlink.c (ffffffff8196c225)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_put
```
```
In net/netlink/af_netlink.c (ffffffff819917a4)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/netfilter/nf_conntrack_helper.c (ffffffff819a32e5)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_helper.c:nf_conntrack_helper_put
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3be1)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c48f2)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff819cd80f)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819dbf5d)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e1959)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff819ec98e)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819f1baa)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819f79eb)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff81a04a23)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10a3b)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff81a33d74)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81a3ba41)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff81a4cf2f)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:addrconf_del_dad_work
```
```
In net/ipv6/ndisc.c (ffffffff81a654bf)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81a762eb)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a87a83)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a944c0)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81a9a251)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__unregister_prot_hook
```
```
In net/xdp/xsk.c (ffffffff81ab63df)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In fs/io_uring.c (ffffffff8134c8b9)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/fuse/dev.c (ffffffff8142adc2)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In net/core/sock.c (ffffffff81924e89)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/core/datagram.c (ffffffff8193340a)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/devlink.c (ffffffff8198e6a5)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_put
```
```
In net/netlink/af_netlink.c (ffffffff819b423e)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cd634)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce372)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp.c (ffffffff819d739f)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819e5bdd)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eb689)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff819f687e)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819fb49a)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81a01c20)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff81a0efb3)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b2c6)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3f6c4)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81a46d91)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff81a58e9f)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:addrconf_del_dad_work
```
```
In net/ipv6/ndisc.c (ffffffff81a71a47)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81a82a1b)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a9466d)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa0606)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81aa6f81)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__unregister_prot_hook
```
```
In net/xdp/xsk.c (ffffffff81ac24ff)
Location: arch/x86/include/asm/refcount.h:59
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
</ul>

## Differences
