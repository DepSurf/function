# Function: <code>ipv4_is_multicast</code>

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
In net/ipv4/route.c (0)
Location: include/linux/in.h:47
Inline: True
```
```
In net/ipv4/datagram.c (0)
Location: include/linux/in.h:47
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/in.h:47
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/in.h:47
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/in.h:47
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:47
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/in.h:47
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:47
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/in.h:47
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/in.h:47
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:47
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
In net/ipv4/route.c (ffffffff817c25e8)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff817f13a7)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff817f2490)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff817f4f22)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff817fa1d8)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff817fe487)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff81807375)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81808387)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
```
```
In net/ipv4/ping.c (ffffffff818108b5)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff818174a9)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff81836426)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff817f2ffd)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff81821fb7)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff8182326c)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81825fef)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8182b0a8)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff8182f3e7)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff81838405)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81839467)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
```
```
In net/ipv4/ping.c (ffffffff81841db5)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81848d19)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff81867f36)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff8181399c)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff81842c21)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81843db8)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8184677c)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8184c241)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81850854)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff81859835)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff8185a9a7)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
```
```
In net/ipv4/ping.c (ffffffff8186368a)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81868b63)
Location: include/linux/in.h:47
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8188c836)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff81892fff)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff818c2581)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff818c373d)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff818c61ac)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff818cbef1)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff818d0484)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff818d9725)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff818da8d7)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
```
```
In net/ipv4/ping.c (ffffffff818e37ca)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff818eca64)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff8190dbc6)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff818e710b)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff819181cc)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819192f3)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8191b8fb)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819223d6)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff819269d2)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff81930175)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff8193185b)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
```
```
In net/ipv4/ping.c (ffffffff8193a05b)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff819427ea)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff81964e96)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff81913fe8)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff8194691f)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81947b85)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81949ee6)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81951206)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81955a65)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff8195f655)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff819610bb)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
```
```
In net/ipv4/ping.c (ffffffff8196a011)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff819728ba)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff8199a316)
Location: include/linux/in.h:47
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff81971387)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff819aaf7e)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819ac869)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819ae7e0)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819b5abf)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff819ba419)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff819c44e5)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff819c4bff)
Location: include/linux/in.h:43
Inline: True
```
```
In net/ipv4/ping.c (ffffffff819d0ba0)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff819dc35c)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff81a06284)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff819a7da3)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff819e1c4e)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819e3427)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819e54fe)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819ec7df)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff819f0fa9)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff819fb085)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff819fb79f)
Location: include/linux/in.h:43
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81a076fc)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81a1334c)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff81a3cdf4)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff81a9150c)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff81acf4bf)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81ad0ce9)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ad52a9)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ada7d4)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81adef22)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff81ae99b5)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeabb1)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/ping.c (ffffffff81af6f3c)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81b03889)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff81b323e4)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff81a9b38f)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff81adb4bf)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81adcc45)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ae1813)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ae5da5)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_is_multicast
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81aebd24)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff81af6845)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81af7a58)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/ping.c (ffffffff81b03dde)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06d3a)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/ipmr.c (ffffffff81b119fe)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff81b41004)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff81a867ad)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff81ac652f)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81ac7ce5)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81acb239)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ad1085)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_is_multicast
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81ad7384)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff81ae1f95)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae3168)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/ping.c (ffffffff81aefa5e)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af247c)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/ipmr.c (ffffffff81b002ad)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff81b2ef1a)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff81b40eed)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff81b84d3f)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81b86545)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81b89ac9)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81b8faa5)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_is_multicast
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81b96b94)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff81ba1735)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba2a3c)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/ping.c (ffffffff81bafa6e)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb298c)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/ipmr.c (ffffffff81bc239d)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff81bf524a)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff81ccd8a2)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff81d155cf)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81d16f27)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81d1d694)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81d20d95)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_is_multicast
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81d28872)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff81d33cf5)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81d3516a)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/ping.c (ffffffff81d4303b)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d46163)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/ipmr.c (ffffffff81d57184)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff81d8e0ca)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff81e9372a)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff81edb7bf)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81edd712)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ee4794)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ee8035)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_is_multicast
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81ef02b2)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff81efc165)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81efd6ba)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/ping.c (ffffffff81f0c020)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f543)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/ipmr.c (ffffffff81f20822)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff81f5c4aa)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/core/rtnetlink.c (ffffffff81e4e817)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_validate_mdb_entry
```
```
In net/ipv4/route.c (ffffffff81ef1ecf)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff81f3a87f)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81f3c972)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81f440bc)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81f47905)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_is_multicast
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81f4fd02)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff81f5bb95)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5d12a)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/ping.c (ffffffff81f6bcac)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f233)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/ipmr.c (ffffffff81f81042)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff81fbc25a)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/core/rtnetlink.c (ffffffff81f0d577)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_validate_mdb_entry
```
```
In net/ipv4/route.c (ffffffff81fb601f)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff8200096f)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff82002aa1)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8200a042)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8200da45)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_is_multicast
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff82015e7d)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff820220d5)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff820236ba)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/ping.c (ffffffff8203226a)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035963)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/ipmr.c (ffffffff820476c2)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff8208968a)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffff800010c574d8)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffff800010c95e48)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffff800010c98040)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffff800010c9ded4)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffff800010ca2340)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffff800010ca7210)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffff800010cb2bc8)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffff800010cb3664)
Location: include/linux/in.h:43
Inline: True
```
```
In net/ipv4/ping.c (ffff800010cc067c)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffff800010ccd8e0)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffff800010cfe250)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (c0d67194)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (c0da45d8)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da5eb0)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c0da8e00)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (c0daf1ac)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (c0db3930)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (c0dbe678)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (c0dbf8e8)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
```
```
In net/ipv4/ping.c (c0dcc94c)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (c0dd899c)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (c0e05dfc)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (c000000000d58b60)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (c000000000da7024)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c000000000da92c4)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c000000000dafe24)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (c000000000db591c)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (c000000000dbb97c)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (c000000000dc9cd8)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (c000000000dca260)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/ping.c (c000000000ddb980)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (c000000000dea2ec)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (c000000000e266c4)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffe0007c1804)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffe0007f4e44)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffe0007f63c0)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffe0007f7df4)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffe0007fe438)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffe0008023fa)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffe00080b01e)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b354)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
```
```
In net/ipv4/ping.c (ffffffe000816e06)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffe00081fdc6)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffe0008486a2)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff81947c13)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff81981abe)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81983297)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8198536e)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8198c64a)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81990d49)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff8199ae25)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff8199b53f)
Location: include/linux/in.h:43
Inline: True
```
```
In net/ipv4/ping.c (ffffffff819a749c)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff819b2b4c)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff819dc484)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In drivers/net/vxlan.c (ffffffff8176b8d5)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_config_validate
  - drivers/net/vxlan.c:vxlan_config_validate
  - drivers/net/vxlan.c:vxlan_stop
  - drivers/net/vxlan.c:vxlan_open
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit_one
```
```
In net/ipv4/route.c (ffffffff81901703)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff8193b57e)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff8193cd57)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8193ee2e)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8194610a)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff8194a809)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff819548e5)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81954fff)
Location: include/linux/in.h:43
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81960f5c)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ip_tunnel.c (ffffffff81968321)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_changelink
  - net/ipv4/ip_tunnel.c:ip_tunnel_ioctl
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
  - net/ipv4/ip_tunnel.c:ip_tunnel_find
  - net/ipv4/ip_tunnel.c:ip_tunnel_add
  - net/ipv4/ip_tunnel.c:ip_tunnel_lookup
```
```
In net/ipv4/ipmr.c (ffffffff8196f17c)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff81999244)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff819b23e3)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff819ec28e)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819eda67)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819efb3e)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819f6e1f)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff819fb5e9)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff81a056c5)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81a05ddf)
Location: include/linux/in.h:43
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81a11d3c)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81a1d3ec)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff81a46f04)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff819bbaa3)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/datagram.c (ffffffff819f613e)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819f79ab)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819fa37a)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81a0103f)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81a0592c)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/igmp.c (ffffffff81a0fc55)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_sf_allow
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81a103c9)
Location: include/linux/in.h:43
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81a1c6aa)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81a28559)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff81a52c94)
Location: include/linux/in.h:43
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
```
</details>
</li>
</ul>

## Differences
