# Function: <code>write_pnet</code>

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
In drivers/net/loopback.c (ffffffff815e97eb)
Location: include/net/net_namespace.h:246
Inline: True
```
```
In drivers/net/tun.c (ffffffff815f04da)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f8b0d)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/sock.c (ffffffff817013d2)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff817187a5)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/neighbour.c (ffffffff81724b10)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/rtnetlink.c (ffffffff8172a3eb)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/netlink/af_netlink.c (ffffffff8174b872)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:netlink_lookup
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/netlink/genetlink.c (ffffffff8174f626)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/inet_hashtables.c (ffffffff81762a16)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81763570)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff8176b325)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81781e0b)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ipmr.c (ffffffff817a7da6)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b165d)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff817b8148)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/addrlabel.c (ffffffff817d2945)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/ip6mr.c (ffffffff817f8f98)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_new_table
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff818066a0)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In drivers/net/loopback.c (ffffffff81647f3b)
Location: include/net/net_namespace.h:249
Inline: True
```
```
In drivers/net/tun.c (ffffffff8164f8f4)
Location: include/net/net_namespace.h:249
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81658b3d)
Location: include/net/net_namespace.h:249
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/sock.c (ffffffff81767623)
Location: include/net/net_namespace.h:249
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff8178435b)
Location: include/net/net_namespace.h:249
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/neighbour.c (ffffffff81791f47)
Location: include/net/net_namespace.h:249
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff81793e22)
Location: include/net/net_namespace.h:249
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/netlink/af_netlink.c (ffffffff817b8852)
Location: include/net/net_namespace.h:249
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/netlink/genetlink.c (ffffffff817bb605)
Location: include/net/net_namespace.h:249
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/inet_hashtables.c (ffffffff817cec9a)
Location: include/net/net_namespace.h:249
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cfa24)
Location: include/net/net_namespace.h:249
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff817d7aca)
Location: include/net/net_namespace.h:249
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ef2ca)
Location: include/net/net_namespace.h:249
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ipmr.c (ffffffff818906d9)
Location: include/net/net_namespace.h:249
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181e59d)
Location: include/net/net_namespace.h:249
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81825468)
Location: include/net/net_namespace.h:249
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/addrlabel.c (ffffffff81840335)
Location: include/net/net_namespace.h:249
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/ip6mr.c (ffffffff8186a171)
Location: include/net/net_namespace.h:249
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_new_table
```
```
In net/packet/af_packet.c (ffffffff81877201)
Location: include/net/net_namespace.h:249
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In drivers/net/loopback.c (ffffffff8167905b)
Location: include/net/net_namespace.h:250
Inline: True
```
```
In drivers/net/tun.c (ffffffff81681ab3)
Location: include/net/net_namespace.h:250
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff816868c4)
Location: include/net/net_namespace.h:250
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/sock.c (ffffffff8179461f)
Location: include/net/net_namespace.h:250
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff817b196b)
Location: include/net/net_namespace.h:250
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/neighbour.c (ffffffff817bf0c7)
Location: include/net/net_namespace.h:250
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff817c16a2)
Location: include/net/net_namespace.h:250
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/netlink/af_netlink.c (ffffffff817e8302)
Location: include/net/net_namespace.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/netlink/genetlink.c (ffffffff817eb007)
Location: include/net/net_namespace.h:250
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/inet_hashtables.c (ffffffff817feaaa)
Location: include/net/net_namespace.h:250
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ff814)
Location: include/net/net_namespace.h:250
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81807a6a)
Location: include/net/net_namespace.h:250
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181fb1a)
Location: include/net/net_namespace.h:250
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ipmr.c (ffffffff818c4cf3)
Location: include/net/net_namespace.h:250
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8184fd2d)
Location: include/net/net_namespace.h:250
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81856dc8)
Location: include/net/net_namespace.h:250
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/addrlabel.c (ffffffff81871fb5)
Location: include/net/net_namespace.h:250
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/ip6mr.c (ffffffff8189cfc1)
Location: include/net/net_namespace.h:250
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_new_table
```
```
In net/packet/af_packet.c (ffffffff818ac254)
Location: include/net/net_namespace.h:250
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In drivers/net/loopback.c (ffffffff8168d9db)
Location: include/net/net_namespace.h:258
Inline: True
```
```
In drivers/net/tun.c (ffffffff81696a44)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8169bc1b)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/sock.c (ffffffff817b4872)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff817cb6e2)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/neighbour.c (ffffffff817dbf47)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff817dfe74)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/netlink/af_netlink.c (ffffffff81806c9d)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_compare_arg_init
```
```
In net/netlink/genetlink.c (ffffffff8180af74)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181ed88)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181fa22)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff8182841a)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183f727)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ipmr.c (ffffffff81868ef9)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81873aed)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff8187aad8)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/addrlabel.c (ffffffff81896d15)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/ip6mr.c (ffffffff818c3493)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_new_table
```
```
In net/packet/af_packet.c (ffffffff818d232e)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In drivers/net/loopback.c (ffffffff816f758b)
Location: include/net/net_namespace.h:270
Inline: True
```
```
In drivers/net/tun.c (ffffffff817018b2)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81706c96)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/sock.c (ffffffff8182cad2)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff81844f2f)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/neighbour.c (ffffffff818563c7)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff8185a744)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/netlink/af_netlink.c (ffffffff8188597d)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_compare_arg_init
```
```
In net/netlink/genetlink.c (ffffffff81889ec4)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189dd38)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189e99a)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff818a792e)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bfa07)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ipmr.c (ffffffff818ebf37)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:vif_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f44ba)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff818fb5c8)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6mr.c (ffffffff81946729)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_new_table
```
```
In net/packet/af_packet.c (ffffffff81957266)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In drivers/net/loopback.c (ffffffff81734728)
Location: include/net/net_namespace.h:289
Inline: True
```
```
In drivers/net/tun.c (ffffffff8173e0e7)
Location: include/net/net_namespace.h:289
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817459c1)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/sock.c (ffffffff818775ee)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff8188fe58)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/neighbour.c (ffffffff818a5187)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff818a5fd4)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/netlink/af_netlink.c (ffffffff818d931d)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_compare_arg_init
```
```
In net/netlink/genetlink.c (ffffffff818dedab)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f26f6)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f32d5)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff818fcaaf)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff819155ff)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ipmr.c (ffffffff8193faf6)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (ffffffff8194494f)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194aa6c)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81950e7c)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6mr.c (ffffffff8199fbce)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff819b3ccb)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In drivers/net/loopback.c (ffffffff81757868)
Location: include/net/net_namespace.h:292
Inline: True
```
```
In drivers/net/tun.c (ffffffff81762053)
Location: include/net/net_namespace.h:292
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81769ab1)
Location: include/net/net_namespace.h:292
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/sock.c (ffffffff81897a3e)
Location: include/net/net_namespace.h:292
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff818b07c4)
Location: include/net/net_namespace.h:292
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (ffffffff818c498c)
Location: include/net/net_namespace.h:292
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff818c95e8)
Location: include/net/net_namespace.h:292
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/netlink/af_netlink.c (ffffffff81905b0d)
Location: include/net/net_namespace.h:292
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_compare_arg_init
```
```
In net/netlink/genetlink.c (ffffffff8190b76b)
Location: include/net/net_namespace.h:292
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/bpf/test_run.c (ffffffff8190be95)
Location: include/net/net_namespace.h:292
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/inet_hashtables.c (ffffffff819200fb)
Location: include/net/net_namespace.h:292
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81920df5)
Location: include/net/net_namespace.h:292
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff8192ac21)
Location: include/net/net_namespace.h:292
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81943daf)
Location: include/net/net_namespace.h:292
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ipmr.c (ffffffff8196fb36)
Location: include/net/net_namespace.h:292
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81974bef)
Location: include/net/net_namespace.h:292
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197feb4)
Location: include/net/net_namespace.h:292
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff819843cc)
Location: include/net/net_namespace.h:292
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6mr.c (ffffffff819d6851)
Location: include/net/net_namespace.h:292
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff819ead38)
Location: include/net/net_namespace.h:292
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In drivers/net/loopback.c (ffffffff82902e60)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
```
```
In drivers/net/tun.c (ffffffff8179fd6f)
Location: include/net/net_namespace.h:301
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a7555)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/sock.c (ffffffff818e1f5b)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff818fd50f)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (ffffffff8191439c)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff819165c9)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/core/devlink.c (ffffffff8194f732)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81966d5d)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_compare_arg_init
```
```
In net/netlink/genetlink.c (ffffffff8196c50a)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/bpf/test_run.c (ffffffff8196d65e)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/inet_hashtables.c (ffffffff81982a1a)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819837be)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff8198de7e)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a81d4)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ipmr.c (ffffffff819d944e)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (ffffffff819de721)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e9c0a)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff819ee0dc)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6mr.c (ffffffff81a458fe)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81a59e5f)
Location: include/net/net_namespace.h:301
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In drivers/net/loopback.c (ffffffff8290c05d)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
```
```
In drivers/net/tun.c (ffffffff817c3fff)
Location: include/net/net_namespace.h:310
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817cafc5)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/sock.c (ffffffff8191412b)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff8192fb36)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (ffffffff81946a0c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff81948bfc)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/core/devlink.c (ffffffff8198610c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8199d7dd)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_compare_arg_init
```
```
In net/netlink/genetlink.c (ffffffff819a2eba)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/bpf/test_run.c (ffffffff819a40c9)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b927a)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819b9fae)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff819c4a4e)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff819de4c7)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ipmr.c (ffffffff81a101be)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81a157c1)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a20c5a)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81a24f4c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6mr.c (ffffffff81a7c4ee)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81a8ff6f)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In drivers/net/loopback.c (ffffffff82d20f86)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
```
```
In drivers/net/tun.c (ffffffff8188f9f9)
Location: include/net/net_namespace.h:320
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81893e8b)
Location: include/net/net_namespace.h:320
Inline: True
```
```
In net/core/sock.c (ffffffff819e6945)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff81a04d9c)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (ffffffff81a13153)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff81a18a0c)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/core/devlink.c (ffffffff81a56071)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
  - net/core/devlink.c:devlink_net_set
```
```
In net/netlink/af_netlink.c (ffffffff81a77d7b)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/netlink/genetlink.c (ffffffff81a7c211)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/bpf/test_run.c (ffffffff81a7ec0d)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa472c)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4a2e)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0b5c)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acc0ee)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcpm_new
```
```
In net/ipv4/ipmr.c (ffffffff81b01177)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81b064e1)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b12b0f)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81b16b7c)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6mr.c (ffffffff81b73cea)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/packet/af_packet.c (ffffffff81b8a54c)
Location: include/net/net_namespace.h:320
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
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
In drivers/net/loopback.c (ffffffff8300ed65)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
```
```
In drivers/net/tun.c (ffffffff8189ddb2)
Location: include/net/net_namespace.h:314
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a24bd)
Location: include/net/net_namespace.h:314
Inline: True
```
```
In net/core/sock.c (ffffffff819e616b)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff81a053bc)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (ffffffff81a13533)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff81a18abc)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/core/devlink.c (ffffffff81a672a1)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_net_set
```
```
In net/netlink/af_netlink.c (ffffffff81a80c4b)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/netlink/genetlink.c (ffffffff81a851f0)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg_doit
```
```
In net/bpf/test_run.c (ffffffff81a88540)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aaed7c)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf08e)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81abbbac)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad80ae)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcpm_new
```
```
In net/ipv4/ipmr.c (ffffffff81b0f257)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81b146d1)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b2108f)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81b24d5c)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6mr.c (ffffffff81b82a5a)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/packet/af_packet.c (ffffffff81b9aad9)
Location: include/net/net_namespace.h:314
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
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
In drivers/net/loopback.c (ffffffff83219d49)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
```
```
In drivers/net/tun.c (ffffffff81880522)
Location: include/net/net_namespace.h:315
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81884995)
Location: include/net/net_namespace.h:315
Inline: True
```
```
In net/core/sock.c (ffffffff819cc222)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff819ed7e2)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (ffffffff819f9643)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff819ff969)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/core/devlink.c (ffffffff81a4a491)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_net_set
```
```
In net/netlink/af_netlink.c (ffffffff81a6a2d5)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/netlink/genetlink.c (ffffffff81a6e1e0)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg_doit
```
```
In net/bpf/test_run.c (ffffffff81a717a0)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a9a020)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a39c)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81aa6b6c)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac347e)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ipmr.c (ffffffff81afcf5d)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81b024d1)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0ecbf)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1297c)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6mr.c (ffffffff81b716c3)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/packet/af_packet.c (ffffffff81b89a08)
Location: include/net/net_namespace.h:315
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
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
In drivers/net/loopback.c (ffffffff8330381e)
Location: include/net/net_namespace.h:317
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
```
```
In drivers/net/tun.c (ffffffff81911dc2)
Location: include/net/net_namespace.h:317
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81916355)
Location: include/net/net_namespace.h:317
Inline: True
```
```
In net/core/sock.c (ffffffff81a7b892)
Location: include/net/net_namespace.h:317
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff81a9ea02)
Location: include/net/net_namespace.h:317
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (ffffffff81aac693)
Location: include/net/net_namespace.h:317
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff81ab1c4b)
Location: include/net/net_namespace.h:317
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/core/devlink.c (ffffffff81af60fa)
Location: include/net/net_namespace.h:317
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc_ns
  - net/core/devlink.c:devlink_reload
```
```
In net/netlink/af_netlink.c (ffffffff81b238d4)
Location: include/net/net_namespace.h:317
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/netlink/genetlink.c (ffffffff81b27860)
Location: include/net/net_namespace.h:317
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg_doit
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b55490)
Location: include/net/net_namespace.h:317
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b5580c)
Location: include/net/net_namespace.h:317
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81b6316c)
Location: include/net/net_namespace.h:317
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b81982)
Location: include/net/net_namespace.h:317
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ipmr.c (ffffffff81bbe712)
Location: include/net/net_namespace.h:317
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc4441)
Location: include/net/net_namespace.h:317
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd20bf)
Location: include/net/net_namespace.h:317
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd681c)
Location: include/net/net_namespace.h:317
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6mr.c (ffffffff81c3bb39)
Location: include/net/net_namespace.h:317
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/packet/af_packet.c (ffffffff81c55b18)
Location: include/net/net_namespace.h:317
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
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
In drivers/net/loopback.c (ffffffff834bc7cd)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
```
```
In drivers/net/tun.c (ffffffff81a64d39)
Location: include/net/net_namespace.h:351
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6c432)
Location: include/net/net_namespace.h:351
Inline: True
```
```
In net/core/sock.c (ffffffff81bef03a)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff81c1772e)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (ffffffff81c2556f)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff81c2af2c)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/core/devlink.c (ffffffff81c76260)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc_ns
  - net/core/devlink.c:devlink_reload
```
```
In net/netlink/af_netlink.c (ffffffff81cac2f1)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/netlink/genetlink.c (ffffffff81cb084c)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg_doit
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce2fc1)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3506)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1e0c)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0a60e)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d11dbc)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/icmp.c (ffffffff81d24593)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/ipmr.c (ffffffff81d536be)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81d592ec)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6866d)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6d0ec)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/icmp.c (ffffffff81dc01bf)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81dd9ea7)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/packet/af_packet.c (ffffffff81df1b51)
Location: include/net/net_namespace.h:351
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
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
In drivers/net/loopback.c (ffffffff83efabc8)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
```
```
In drivers/net/tun.c (ffffffff81beffb4)
Location: include/net/net_namespace.h:373
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bff392)
Location: include/net/net_namespace.h:373
Inline: True
```
```
In net/core/sock.c (ffffffff81d9b87a)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff81dc873e)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (ffffffff81dd88ff)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff81dde86c)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/core/devlink.c (ffffffff81e2e9f4)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc_ns
  - net/core/devlink.c:devlink_reload
```
```
In net/netlink/af_netlink.c (ffffffff81e6b7c9)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/netlink/genetlink.c (ffffffff81e6e7b1)
Location: include/net/net_namespace.h:373
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea535a)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea59d6)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81eb667c)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecfe9e)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed7b8c)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/icmp.c (ffffffff81eebd73)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/ipmr.c (ffffffff81f1d37d)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81f238ec)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f3370d)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3855c)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/icmp.c (ffffffff81f9092f)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81fabb4c)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/packet/af_packet.c (ffffffff81fc5b21)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
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
In drivers/net/loopback.c (ffffffff83720908)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
```
```
In drivers/net/tun.c (ffffffff81c48532)
Location: include/net/net_namespace.h:373
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c64966)
Location: include/net/net_namespace.h:373
Inline: True
```
```
In drivers/net/net_failover.c (ffffffff81c6f540)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_create
```
```
In net/core/sock.c (ffffffff81e09f1a)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff81e38a2a)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (ffffffff81e4965f)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff81e4f8d2)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/netlink/af_netlink.c (ffffffff81ec7815)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_compare_arg_init
```
```
In net/netlink/genetlink.c (ffffffff81eca741)
Location: include/net/net_namespace.h:373
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f03ae9)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04168)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81f14a9c)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2eb4a)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/icmp.c (ffffffff81f4bb4a)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/ipmr.c (ffffffff81f7ce5c)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81f8343c)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92a8d)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81f97f4c)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/icmp.c (ffffffff81ff11af)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff8200c2ec)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/packet/af_packet.c (ffffffff8202a06b)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/devlink/core.c (ffffffff820420d6)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_alloc_ns
```
```
In net/devlink/dev.c (ffffffff8204474f)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_reload
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
In drivers/net/loopback.c (ffffffff839547a8)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
```
```
In drivers/net/tun.c (ffffffff81cfdeb6)
Location: include/net/net_namespace.h:375
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1b386)
Location: include/net/net_namespace.h:375
Inline: True
```
```
In drivers/net/net_failover.c (ffffffff81d23df0)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_create
```
```
In net/core/sock.c (ffffffff81ec690a)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff81ef6bd0)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (ffffffff81f08346)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff81f0e912)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/netlink/af_netlink.c (ffffffff81f8ab77)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_compare_arg_init
```
```
In net/netlink/genetlink.c (ffffffff81f8d103)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg_doit
  - net/netlink/genetlink.c:genl_start
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc7d94)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind2_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc84a5)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff81fd8fbd)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff3964)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/icmp.c (ffffffff82011c5a)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/ipmr.c (ffffffff8204355c)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (ffffffff82049aeb)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205d0e2)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff820652bc)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/icmp.c (ffffffff820bed8d)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff820db2bc)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/packet/af_packet.c (ffffffff820f9b6a)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/devlink/core.c (ffffffff820feb36)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_alloc_ns
```
```
In net/devlink/dev.c (ffffffff82103f5f)
Location: include/net/net_namespace.h:375
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_reload
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
In drivers/net/loopback.c (ffff80001149b87c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
```
```
In drivers/net/tun.c (ffff8000109deabc)
Location: include/net/net_namespace.h:310
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a02a90)
Location: include/net/net_namespace.h:310
Inline: True
```
```
In net/core/sock.c (ffff800010bab128)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffff800010bccfe8)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (ffff800010be24c4)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffff800010bebf90)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/core/devlink.c (ffff800010c25594)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
```
```
In net/netlink/af_netlink.c (ffff800010c4acb4)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_compare_arg_init
```
```
In net/netlink/genetlink.c (ffff800010c510b4)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/bpf/test_run.c (ffff800010c53520)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6a920)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6b944)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffff800010c77464)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffff800010c9290c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ipmr.c (ffff800010ccd694)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (ffff800010cd0930)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (ffff800010cde6a0)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffff800010ce2788)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6mr.c (ffff800010d4662c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffff800010d5d068)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In drivers/net/loopback.c (c159caf4)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
```
```
In drivers/net/tun.c (c0ac3cf8)
Location: include/net/net_namespace.h:310
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (c0adf8d4)
Location: include/net/net_namespace.h:310
Inline: True
```
```
In net/core/sock.c (c0cc9bbc)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (c0ce8a98)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (c0d00f44)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (c0d03258)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/core/devlink.c (c0d41228)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
```
```
In net/netlink/af_netlink.c (c0d5df74)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_lookup
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netlink/genetlink.c (c0d618fc)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/bpf/test_run.c (c0d62e40)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/inet_hashtables.c (c0d799f0)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (c0d7a9c0)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (c0d85a04)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (c0da134c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ipmr.c (c0dd5410)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (c0ddac94)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (c0de6ae8)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (c0deb87c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6mr.c (c0e48c24)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (c0e5e448)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In drivers/net/loopback.c (c0000000013afc3c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
```
```
In drivers/net/tun.c (c000000000aa030c)
Location: include/net/net_namespace.h:310
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aab3b8)
Location: include/net/net_namespace.h:310
Inline: True
```
```
In net/core/sock.c (c000000000c81918)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (c000000000caadf0)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (c000000000cca05c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (c000000000ccd33c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/core/devlink.c (c000000000d262b8)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
```
```
In net/netlink/af_netlink.c (c000000000d48de8)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_compare_arg_init
```
```
In net/netlink/genetlink.c (c000000000d518e8)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/bpf/test_run.c (c000000000d52bd0)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/inet_hashtables.c (c000000000d6fae0)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d70ff8)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (c000000000d7f89c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (c000000000da19c8)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ipmr.c (c000000000dec96c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (c000000000def40c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (c000000000dfe894)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (c000000000e05234)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6mr.c (c000000000e7c094)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (c000000000e98edc)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In drivers/net/loopback.c (ffffffe000034aa0)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
```
```
In drivers/net/tun.c (ffffffe0006292b8)
Location: include/net/net_namespace.h:310
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062f00c)
Location: include/net/net_namespace.h:310
Inline: True
```
```
In net/core/sock.c (ffffffe00073eb14)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffe00075770c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (ffffffe000769bd0)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffe00076e104)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/core/devlink.c (ffffffe00079f6cc)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
```
```
In net/netlink/af_netlink.c (ffffffe0007b8988)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/netlink/genetlink.c (ffffffe0007bc458)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/bpf/test_run.c (ffffffe0007bde02)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d0664)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d1352)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffe0007da5cc)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f175c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ipmr.c (ffffffe00081e070)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (ffffffe0008229e2)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082dbf2)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffe000830e4e)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6mr.c (ffffffe000881106)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffe00089367c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In drivers/net/loopback.c (ffffffff828f3a1a)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
```
```
In drivers/net/tun.c (ffffffff81788adf)
Location: include/net/net_namespace.h:310
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178faa5)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/sock.c (ffffffff818b412b)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff818cfb36)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (ffffffff818e69dc)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff818e8bcc)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/core/devlink.c (ffffffff81925f7c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8193d64d)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_compare_arg_init
```
```
In net/netlink/genetlink.c (ffffffff81942d2a)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/bpf/test_run.c (ffffffff81943f39)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/inet_hashtables.c (ffffffff819590ea)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81959e1e)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff819648be)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197e337)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ipmr.c (ffffffff819afbde)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (ffffffff819b4e51)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c02ea)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff819c45dc)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6mr.c (ffffffff81a1bb7e)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81a2f5ff)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In drivers/net/loopback.c (ffffffff828eaec5)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
```
```
In drivers/net/tun.c (ffffffff8176842f)
Location: include/net/net_namespace.h:310
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81778875)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/sock.c (ffffffff8186e07b)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff81889c56)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (ffffffff818a081c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff818a2a0c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/core/devlink.c (ffffffff818dfd2c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
```
```
In net/netlink/af_netlink.c (ffffffff818f714d)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_compare_arg_init
```
```
In net/netlink/genetlink.c (ffffffff818fc81a)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/bpf/test_run.c (ffffffff818fda29)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/inet_hashtables.c (ffffffff81912bda)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8191390e)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff8191e3ae)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81937df7)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ip_tunnel.c (ffffffff81966dff)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:__ip_tunnel_create
```
```
In net/ipv4/ipmr.c (ffffffff8196c20e)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81971481)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d0da)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff819813cc)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6mr.c (ffffffff819d893e)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff819ec7ef)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In drivers/net/loopback.c (ffffffff82907458)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
```
```
In drivers/net/tun.c (ffffffff817b8e7f)
Location: include/net/net_namespace.h:310
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bfe45)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/sock.c (ffffffff8190512b)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff81920b36)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (ffffffff81937a0c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff81939bfc)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/core/devlink.c (ffffffff8197710c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8198e7dd)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_compare_arg_init
```
```
In net/netlink/genetlink.c (ffffffff81993eba)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/bpf/test_run.c (ffffffff819950c9)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199e34f)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_alloc
  - net/netfilter/nf_conntrack_core.c:nf_ct_tmpl_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c38ba)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c45ee)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff819cf08e)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e8b07)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ipmr.c (ffffffff81a1a47e)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1f6f1)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2ad6a)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f05c)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6mr.c (ffffffff81a865fe)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81a9b1af)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In drivers/net/loopback.c (ffffffff8290d0bf)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
```
```
In drivers/net/tun.c (ffffffff817d3b4f)
Location: include/net/net_namespace.h:310
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817da0ed)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/sock.c (ffffffff819261fb)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff819428c6)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/neighbour.c (ffffffff819591dc)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff8195b2dc)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/core/devlink.c (ffffffff819995fc)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
```
```
In net/netlink/af_netlink.c (ffffffff819b108d)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_compare_arg_init
```
```
In net/netlink/genetlink.c (ffffffff819b69ba)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/bpf/test_run.c (ffffffff819b7c49)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cd2da)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce18e)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/tcp_input.c (ffffffff819d8c1e)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f2867)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/ipmr.c (ffffffff81a252ae)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2abf1)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a363b3)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3a2bc)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/ip6mr.c (ffffffff81a931be)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81aa7f16)
Location: include/net/net_namespace.h:310
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
```
</details>
</li>
</ul>

## Differences
