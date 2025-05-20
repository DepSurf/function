# Function: <code>skb_queue_head_init</code>

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
In kernel/audit.c (ffffffff81f8231a)
Location: include/linux/skbuff.h:1461
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81125397)
Location: include/linux/skbuff.h:1461
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f6208)
Location: include/linux/skbuff.h:1461
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff815fb3e1)
Location: include/linux/skbuff.h:1461
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81700cd7)
Location: include/linux/skbuff.h:1461
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff81fbb09d)
Location: include/linux/skbuff.h:1461
Inline: True
```
```
In net/core/neighbour.c (ffffffff81728577)
Location: include/linux/skbuff.h:1461
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/netpoll.c (ffffffff81fbb42a)
Location: include/linux/skbuff.h:1461
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff817418c6)
Location: include/linux/skbuff.h:1461
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/tcp.c (ffffffff8176580b)
Location: include/linux/skbuff.h:1461
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177ee7c)
Location: include/linux/skbuff.h:1461
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/ipmr.c (ffffffff817a8f89)
Location: include/linux/skbuff.h:1461
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b1685)
Location: include/linux/skbuff.h:1461
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (ffffffff817c26ec)
Location: include/linux/skbuff.h:1461
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (ffffffff817f9cd4)
Location: include/linux/skbuff.h:1461
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff8180984d)
Location: include/linux/skbuff.h:1461
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff81fab894)
Location: include/linux/skbuff.h:1562
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8112d436)
Location: include/linux/skbuff.h:1562
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8165637c)
Location: include/linux/skbuff.h:1562
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff8165b301)
Location: include/linux/skbuff.h:1562
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81767857)
Location: include/linux/skbuff.h:1562
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff81fe8c8c)
Location: include/linux/skbuff.h:1562
Inline: True
```
```
In net/core/neighbour.c (ffffffff817920c9)
Location: include/linux/skbuff.h:1562
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/netpoll.c (ffffffff81fe9040)
Location: include/linux/skbuff.h:1562
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff817ae755)
Location: include/linux/skbuff.h:1562
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/tcp.c (ffffffff817d1d87)
Location: include/linux/skbuff.h:1562
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ec32c)
Location: include/linux/skbuff.h:1562
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/ipmr.c (ffffffff8181679b)
Location: include/linux/skbuff.h:1562
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181e5c5)
Location: include/linux/skbuff.h:1562
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (ffffffff8182f718)
Location: include/linux/skbuff.h:1562
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81869558)
Location: include/linux/skbuff.h:1562
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff8187b34d)
Location: include/linux/skbuff.h:1562
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff81fe7b8a)
Location: include/linux/skbuff.h:1577
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81137166)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81684066)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff81689121)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81794857)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff820274d6)
Location: include/linux/skbuff.h:1577
Inline: True
```
```
In net/core/neighbour.c (ffffffff817bf249)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/netpoll.c (ffffffff8202792d)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/ipv4/tcp.c (ffffffff81801cd3)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181cbfc)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/ipmr.c (ffffffff81847f4b)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff8184fd55)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (ffffffff8186114e)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (ffffffff8189c3a8)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff818afc0d)
Location: include/linux/skbuff.h:1577
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff820c81e0)
Location: include/linux/skbuff.h:1570
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81138447)
Location: include/linux/skbuff.h:1570
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81699096)
Location: include/linux/skbuff.h:1570
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff8169e861)
Location: include/linux/skbuff.h:1570
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff817b2a77)
Location: include/linux/skbuff.h:1570
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff8210aa80)
Location: include/linux/skbuff.h:1570
Inline: True
```
```
In net/core/neighbour.c (ffffffff817dc0c0)
Location: include/linux/skbuff.h:1570
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/netpoll.c (ffffffff8210ae5a)
Location: include/linux/skbuff.h:1570
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/ipv4/tcp.c (ffffffff81821e3f)
Location: include/linux/skbuff.h:1570
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d458)
Location: include/linux/skbuff.h:1570
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/udp.c (ffffffff81844f4d)
Location: include/linux/skbuff.h:1570
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff8186a526)
Location: include/linux/skbuff.h:1570
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81873b15)
Location: include/linux/skbuff.h:1570
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (ffffffff81885894)
Location: include/linux/skbuff.h:1570
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (ffffffff818c276d)
Location: include/linux/skbuff.h:1570
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff818d640d)
Location: include/linux/skbuff.h:1570
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff826d084f)
Location: include/linux/skbuff.h:1652
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81145157)
Location: include/linux/skbuff.h:1652
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/sockmap.c (ffffffff811b122f)
Location: include/linux/skbuff.h:1652
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81705e86)
Location: include/linux/skbuff.h:1652
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff81709a01)
Location: include/linux/skbuff.h:1652
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff8182ad4a)
Location: include/linux/skbuff.h:1652
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff82714423)
Location: include/linux/skbuff.h:1652
Inline: True
```
```
In net/core/neighbour.c (ffffffff8185652c)
Location: include/linux/skbuff.h:1652
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/netpoll.c (ffffffff82714801)
Location: include/linux/skbuff.h:1652
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/ipv4/udp.c (ffffffff818c49dd)
Location: include/linux/skbuff.h:1652
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff818eaca6)
Location: include/linux/skbuff.h:1652
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f44ec)
Location: include/linux/skbuff.h:1652
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (ffffffff81906a44)
Location: include/linux/skbuff.h:1652
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (ffffffff819460ad)
Location: include/linux/skbuff.h:1652
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff8195bfcd)
Location: include/linux/skbuff.h:1652
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff826fafd5)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff81153b01)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/sockmap.c (ffffffff811cd2a0)
Location: include/linux/skbuff.h:1663
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81743bac)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff817484a1)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81874e2d)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff8273e61d)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (ffffffff818a52e0)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/netpoll.c (ffffffff8273e9f2)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/ipv4/udp.c (ffffffff8191a76d)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff8194144c)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194aacc)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (ffffffff8195da50)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (ffffffff8199db85)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff819b583d)
Location: include/linux/skbuff.h:1663
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff828b1f01)
Location: include/linux/skbuff.h:1743
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff81160891)
Location: include/linux/skbuff.h:1743
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8176685c)
Location: include/linux/skbuff.h:1743
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff8176c551)
Location: include/linux/skbuff.h:1743
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff818956ed)
Location: include/linux/skbuff.h:1743
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff828f867c)
Location: include/linux/skbuff.h:1743
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (ffffffff818c4ae5)
Location: include/linux/skbuff.h:1743
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/skmsg.c (ffffffff818e6304)
Location: include/linux/skbuff.h:1743
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff828f8a8f)
Location: include/linux/skbuff.h:1743
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/ipv4/udp.c (ffffffff81948f1d)
Location: include/linux/skbuff.h:1743
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81971c0c)
Location: include/linux/skbuff.h:1743
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d5f4)
Location: include/linux/skbuff.h:1743
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (ffffffff81992590)
Location: include/linux/skbuff.h:1743
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (ffffffff819d474d)
Location: include/linux/skbuff.h:1743
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff819ecafd)
Location: include/linux/skbuff.h:1743
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff828cac9d)
Location: include/linux/skbuff.h:1833
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff8116cf0b)
Location: include/linux/skbuff.h:1833
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a56ad)
Location: include/linux/skbuff.h:1833
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff817aa373)
Location: include/linux/skbuff.h:1833
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff818dfc0d)
Location: include/linux/skbuff.h:1833
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff829140ed)
Location: include/linux/skbuff.h:1833
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (ffffffff819144fb)
Location: include/linux/skbuff.h:1833
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/skmsg.c (ffffffff81935ca4)
Location: include/linux/skbuff.h:1833
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff82914504)
Location: include/linux/skbuff.h:1833
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/ipv4/udp.c (ffffffff819ad56d)
Location: include/linux/skbuff.h:1833
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff819db3a1)
Location: include/linux/skbuff.h:1833
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e6a4b)
Location: include/linux/skbuff.h:1833
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (ffffffff819fdb80)
Location: include/linux/skbuff.h:1833
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81a435cd)
Location: include/linux/skbuff.h:1833
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81a5bccd)
Location: include/linux/skbuff.h:1833
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff828d317f)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff81178dab)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c7d0d)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff817cddd3)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81911dbd)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff8291de70)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (ffffffff81946b6b)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/skmsg.c (ffffffff81968d64)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff8291e299)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff82920af8)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
```
```
In net/ipv4/udp.c (ffffffff819e421d)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81a12275)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1da3b)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (ffffffff81a34770)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81a7a12f)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81a928fd)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff82cf3c10)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff8118c005)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81892450)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff81899eea)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff819e3d6d)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff82d2cf75)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (ffffffff81a132b2)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/skmsg.c (ffffffff81a3cb28)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff82d2d3b1)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff82d2d54a)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
```
```
In net/ipv4/udp.c (ffffffff81ad196d)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81b046c5)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0dfab)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/espintcp.c (ffffffff81b23398)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/unix/garbage.c (ffffffff81b29583)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81b74a7f)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81b8ddad)
Location: include/linux/skbuff.h:1866
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff82fe06e7)
Location: include/linux/skbuff.h:1887
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff8118921b)
Location: include/linux/skbuff.h:1887
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a096b)
Location: include/linux/skbuff.h:1887
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff818a9034)
Location: include/linux/skbuff.h:1887
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff819e36ad)
Location: include/linux/skbuff.h:1887
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff8301ba59)
Location: include/linux/skbuff.h:1887
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (ffffffff81a13692)
Location: include/linux/skbuff.h:1887
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/skmsg.c (ffffffff81a3e6f5)
Location: include/linux/skbuff.h:1887
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff8301be99)
Location: include/linux/skbuff.h:1887
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff8301c032)
Location: include/linux/skbuff.h:1887
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
```
```
In net/ipv4/udp.c (ffffffff81add99d)
Location: include/linux/skbuff.h:1887
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81b12835)
Location: include/linux/skbuff.h:1887
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1c49b)
Location: include/linux/skbuff.h:1887
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/espintcp.c (ffffffff81b31d88)
Location: include/linux/skbuff.h:1887
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/unix/garbage.c (ffffffff81b37eb3)
Location: include/linux/skbuff.h:1887
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81b837ef)
Location: include/linux/skbuff.h:1887
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81b9da5d)
Location: include/linux/skbuff.h:1887
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff831eb2cc)
Location: include/linux/skbuff.h:1903
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff81189fe0)
Location: include/linux/skbuff.h:1903
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81882ff7)
Location: include/linux/skbuff.h:1903
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81888192)
Location: include/linux/skbuff.h:1903
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8188c2b2)
Location: include/linux/skbuff.h:1903
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff819c972d)
Location: include/linux/skbuff.h:1903
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff83226b95)
Location: include/linux/skbuff.h:1903
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (ffffffff819f97a2)
Location: include/linux/skbuff.h:1903
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/netpoll.c (ffffffff83226fda)
Location: include/linux/skbuff.h:1903
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff83227173)
Location: include/linux/skbuff.h:1903
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
```
```
In net/core/skmsg.c (ffffffff81a4c902)
Location: include/linux/skbuff.h:1903
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/ipv4/udp.c (ffffffff81ac8a6d)
Location: include/linux/skbuff.h:1903
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81afff55)
Location: include/linux/skbuff.h:1903
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0a18b)
Location: include/linux/skbuff.h:1903
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/espintcp.c (ffffffff81b1faa8)
Location: include/linux/skbuff.h:1903
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/unix/garbage.c (ffffffff81b25b4b)
Location: include/linux/skbuff.h:1903
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/mcast.c (ffffffff81b624a2)
Location: include/linux/skbuff.h:1903
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff81b7246f)
Location: include/linux/skbuff.h:1903
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81b8cb5d)
Location: include/linux/skbuff.h:1903
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff832cfc0a)
Location: include/linux/skbuff.h:1932
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff811b2a34)
Location: include/linux/skbuff.h:1932
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81914997)
Location: include/linux/skbuff.h:1932
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8191a597)
Location: include/linux/skbuff.h:1932
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8191f670)
Location: include/linux/skbuff.h:1932
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81a78aad)
Location: include/linux/skbuff.h:1932
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff83310ea4)
Location: include/linux/skbuff.h:1932
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (ffffffff81aac7f2)
Location: include/linux/skbuff.h:1932
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/netpoll.c (ffffffff83311335)
Location: include/linux/skbuff.h:1932
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff833114db)
Location: include/linux/skbuff.h:1932
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
```
```
In net/core/skmsg.c (ffffffff81b060a2)
Location: include/linux/skbuff.h:1932
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/ipv4/udp.c (ffffffff81b872ed)
Location: include/linux/skbuff.h:1932
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81bc1085)
Location: include/linux/skbuff.h:1932
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bccfba)
Location: include/linux/skbuff.h:1932
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/espintcp.c (ffffffff81be4748)
Location: include/linux/skbuff.h:1932
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/unix/garbage.c (ffffffff81beb277)
Location: include/linux/skbuff.h:1932
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/mcast.c (ffffffff81c29f32)
Location: include/linux/skbuff.h:1932
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c93f)
Location: include/linux/skbuff.h:1932
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81c58f1d)
Location: include/linux/skbuff.h:1932
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff811dfb6b)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff811e4d94)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a69fad)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6f90d)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_port
```
```
In drivers/net/xen-netfront.c (ffffffff81a746c8)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81bec51d)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff834cac00)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (ffffffff81c2572c)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff834cb105)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff834cb2b6)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
```
```
In net/core/skmsg.c (ffffffff81c8b3f7)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/ipv4/udp.c (ffffffff81d17fbd)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81d55a18)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d62eda)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/espintcp.c (ffffffff81d7bc3d)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/unix/garbage.c (ffffffff81d83663)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/mcast.c (ffffffff81dc7392)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff81ddaecf)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81dfa5ed)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff8122587b)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff8122adb4)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfcbad)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c0274d)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_port
```
```
In drivers/net/xen-netfront.c (ffffffff81c08928)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81d9a39d)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff83f0caaf)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (ffffffff81dd8ac0)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff83f0d395)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff83f0d561)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
```
```
In net/core/skmsg.c (ffffffff81e47802)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/ipv4/udp.c (ffffffff81ede86c)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81f1fd78)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2daa8)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/espintcp.c (ffffffff81f48d0d)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/unix/garbage.c (ffffffff81f50d2e)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/udp.c (ffffffff81f8747c)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_init_sock
```
```
In net/ipv6/mcast.c (ffffffff81f98062)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff81facbdf)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81fced1d)
Location: include/linux/skbuff.h:2141
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff8123be6b)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff812413b4)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c6222d)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c67cd6)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_port
```
```
In drivers/net/xen-netfront.c (ffffffff81c6e088)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81e08bfd)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff83732e4f)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (ffffffff81e49820)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff837339a5)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff83733b71)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
```
```
In net/core/skmsg.c (ffffffff81ea1c92)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/ipv4/udp.c (ffffffff81f3dcac)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81f7f878)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8d778)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/espintcp.c (ffffffff81fa81ad)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/unix/garbage.c (ffffffff81fb068f)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/udp.c (ffffffff81fe77fc)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_init_sock
```
```
In net/ipv6/mcast.c (ffffffff81ff8a52)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff8200d20f)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff8204a67d)
Location: include/linux/skbuff.h:2177
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff81255d3b)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff8125b1e3)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d18c5c)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff81d22978)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81ec566d)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff8396732f)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (ffffffff81f0853f)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff83967ee5)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff839680b1)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
```
```
In net/core/skmsg.c (ffffffff81f65f45)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/ipv4/udp.c (ffffffff82003ddc)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff82045ef8)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205b11f)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/espintcp.c (ffffffff8207549c)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/unix/garbage.c (ffffffff8207dcfe)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/udp.c (ffffffff820b565c)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_init_sock
```
```
In net/ipv6/mcast.c (ffffffff820c66c2)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff820dc1df)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff8211caed)
Location: include/linux/skbuff.h:2184
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffff80001144b764)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffff8000101edee0)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a00358)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffff800010a08688)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffff800010ba9958)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffff8000114ae888)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (ffff800010be25cc)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/skmsg.c (ffff800010c0f7fc)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffff8000114aed40)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffff8000114b1478)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
```
```
In net/ipv4/udp.c (ffff800010c98d34)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffff800010ccbae0)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd9fec)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (ffff800010cf4d48)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (ffff800010d447dc)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffff800010d60614)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (c1525c90)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (c042dff4)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad0eb8)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_register
```
```
In drivers/net/ppp/ppp_generic.c (c0add730)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In net/core/sock.c (c0cc7f00)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (c15b3510)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (c0d01090)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/skmsg.c (c0d264e0)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (c15b39f4)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (c15b66cc)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
```
```
In net/ipv4/udp.c (c0da6a88)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (c0dd687c)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (c0de3d18)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (c0dfb9b8)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (c0e46080)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (c0e60150)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (c000000001371284)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (c0000000002609c4)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa8110)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In net/core/sock.c (c000000000c7ee3c)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (c0000000013be858)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (c000000000cca1cc)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/skmsg.c (c000000000cfa610)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (c0000000013bee24)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (c0000000013c1f6c)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
```
```
In net/ipv4/udp.c (c000000000daa474)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (c000000000dec094)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (c000000000dfca4c)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (c000000000e1ae00)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (c000000000e790a0)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (c000000000e9b798)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffe00000ca8e)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffe000162332)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062caec)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In net/core/sock.c (ffffffe00073ce84)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffe00003daf6)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (ffffffe000769cec)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/skmsg.c (ffffffe00078b37c)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffe00003df92)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffe0000401f6)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
```
```
In net/ipv4/udp.c (ffffffe0007f6cba)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffe000821164)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082a67a)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (ffffffe000840a0a)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (ffffffe00087eece)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffe000895a24)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff828bc030)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff811713cb)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178c7ed)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff817929f3)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff818b1dbd)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff82902b74)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (ffffffff818e6b3b)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/skmsg.c (ffffffff81908d34)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff82902f9d)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff829057fc)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
```
```
In net/ipv4/udp.c (ffffffff8198408d)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff819b1b95)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bd0cb)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (ffffffff819d3e00)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81a197bf)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81a31f8d)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff828b46c3)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff8116456b)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817755bd)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In net/core/sock.c (ffffffff8186bd0d)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff828faec2)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (ffffffff818a097b)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/skmsg.c (ffffffff818c2b44)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff828fb2eb)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff828fdb4a)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
```
```
In net/ipv4/udp.c (ffffffff8193db4d)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff8196e1c5)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81979ebb)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (ffffffff81990bc0)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (ffffffff819d657f)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff819ef17d)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff828cedb3)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff8116f19b)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bcb8d)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff817c2c53)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81902dbd)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff8291817b)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (ffffffff81937b6b)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/skmsg.c (ffffffff81959d64)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff829185a4)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff8291ae03)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
```
```
In net/ipv4/udp.c (ffffffff819ee85d)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81a1c435)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a27b4b)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (ffffffff81a3e880)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81a8423f)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81a9db3d)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff828d41ad)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff8117c98b)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d7798)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff817dcf13)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81923d2d)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff8291eed2)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
```
In net/core/neighbour.c (ffffffff8195933b)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/skmsg.c (ffffffff8197bf84)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff8291f2fb)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff82921b5a)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
```
```
In net/ipv4/udp.c (ffffffff819f88bd)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81a27385)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3317b)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (ffffffff81a4a405)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81a90b6f)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81aa9d3d)
Location: include/linux/skbuff.h:1843
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
```
</details>
</li>
</ul>

## Differences
