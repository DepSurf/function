# Function: <code>in6_dev_get</code>

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
In net/ipv6/addrconf.c (ffffffff817d0921)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff817d3294)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
```
```
In net/ipv6/ndisc.c (ffffffff817dec81)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/mcast.c (ffffffff817ebc49)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff817fbd4b)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/ipv6/addrconf.c (ffffffff8183e270)
Location: include/net/addrconf.h:288
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff81febf56)
Location: include/net/addrconf.h:288
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffff8184cfaa)
Location: include/net/addrconf.h:288
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff8185a4a9)
Location: include/net/addrconf.h:288
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8186b61b)
Location: include/net/addrconf.h:288
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/ipv6/addrconf.c (ffffffff8186fe80)
Location: include/net/addrconf.h:290
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff8202a859)
Location: include/net/addrconf.h:290
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffff8187ee3a)
Location: include/net/addrconf.h:290
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff8188c3f5)
Location: include/net/addrconf.h:290
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8189e47b)
Location: include/net/addrconf.h:290
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/ipv6/addrconf.c (ffffffff81894be3)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff8210de63)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffff818a4f85)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff818b2ad7)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff818c49a9)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct inet6_dev *in6_dev_get(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819160c6)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff8191d5d9)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_ifdown
Direct callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
```
```
In net/ipv6/ndisc.c (ffffffff81927981)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81935837)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8194804f)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81921152-ffffffff81921172: in6_dev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct inet6_dev *in6_dev_get(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8196d7d4)
Location: include/net/addrconf.h:361
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81974e6e)
Location: include/net/addrconf.h:361
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
Direct callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
```
```
In net/ipv6/ndisc.c (ffffffff8197fd32)
Location: include/net/addrconf.h:361
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff8198e19d)
Location: include/net/addrconf.h:361
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a10de)
Location: include/net/addrconf.h:361
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81979502-ffffffff81979522: in6_dev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct inet6_dev *in6_dev_get(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819a3339)
Location: include/net/addrconf.h:369
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff819aaaae)
Location: include/net/addrconf.h:369
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
Direct callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
```
```
In net/ipv6/ndisc.c (ffffffff819b6322)
Location: include/net/addrconf.h:369
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff819c4a5c)
Location: include/net/addrconf.h:369
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d7dfe)
Location: include/net/addrconf.h:369
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff819af0e2-ffffffff819af102: in6_dev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct inet6_dev *in6_dev_get(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a0f623)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81a176e7)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
Direct callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
```
```
In net/ipv6/ndisc.c (ffffffff81a24d91)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81a338ac)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a46e01)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81a1d252-ffffffff81a1d26c: in6_dev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct inet6_dev *in6_dev_get(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a46363)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81a4e337)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
Direct callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
```
```
In net/ipv6/ndisc.c (ffffffff81a5b811)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81a6a3fc)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a7d9b1)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81a53f22-ffffffff81a53f3c: in6_dev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct inet6_dev *in6_dev_get(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b3d3c1)
Location: include/net/addrconf.h:352
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81b44131)
Location: include/net/addrconf.h:352
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
Direct callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
```
```
In net/ipv6/ndisc.c (ffffffff81b544f3)
Location: include/net/addrconf.h:352
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81b6331c)
Location: include/net/addrconf.h:352
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b781ca)
Location: include/net/addrconf.h:352
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81b4b5be-ffffffff81b4b60e: in6_dev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct inet6_dev *in6_dev_get(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b4c025)
Location: include/net/addrconf.h:355
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81b53231)
Location: include/net/addrconf.h:355
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
Direct callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
```
```
In net/ipv6/ndisc.c (ffffffff81b62b03)
Location: include/net/addrconf.h:355
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81b71abc)
Location: include/net/addrconf.h:355
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b8711a)
Location: include/net/addrconf.h:355
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81c32cb5-ffffffff81c32d0a: in6_dev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct inet6_dev *in6_dev_get(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b39c25)
Location: include/net/addrconf.h:354
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81b40bc1)
Location: include/net/addrconf.h:354
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
Direct callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
```
```
In net/ipv6/ndisc.c (ffffffff81b50e1a)
Location: include/net/addrconf.h:354
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81b5ee4a)
Location: include/net/addrconf.h:354
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b75dea)
Location: include/net/addrconf.h:354
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81c24fc7-ffffffff81c2501d: in6_dev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct inet6_dev *in6_dev_get(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81c003d2)
Location: include/net/addrconf.h:354
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81c071f1)
Location: include/net/addrconf.h:354
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
Direct callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
```
```
In net/ipv6/ndisc.c (ffffffff81c181ca)
Location: include/net/addrconf.h:354
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81c265ef)
Location: include/net/addrconf.h:354
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81c4085f)
Location: include/net/addrconf.h:354
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81d3fbf5-ffffffff81d3fc4b: in6_dev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct inet6_dev *in6_dev_get(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d99f13)
Location: include/net/addrconf.h:356
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81da188b)
Location: include/net/addrconf.h:356
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
Direct callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
```
```
In net/ipv6/ndisc.c (ffffffff81db41f7)
Location: include/net/addrconf.h:356
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81dc4247)
Location: include/net/addrconf.h:356
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81ddef13)
Location: include/net/addrconf.h:356
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81f0c56e-ffffffff81f0c5d1: in6_dev_get (STB_LOCAL)
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
In net/ipv6/addrconf.c (ffffffff81f68cf3)
Location: include/net/addrconf.h:356
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff83f10fe9)
Location: include/net/addrconf.h:356
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffff81f83ce4)
Location: include/net/addrconf.h:356
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81f943a7)
Location: include/net/addrconf.h:356
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81fb1143)
Location: include/net/addrconf.h:356
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/ipv6/addrconf.c (ffffffff81fc8dcb)
Location: include/net/addrconf.h:356
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff83737639)
Location: include/net/addrconf.h:356
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffff81fe4034)
Location: include/net/addrconf.h:356
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81ff4d27)
Location: include/net/addrconf.h:356
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820117f3)
Location: include/net/addrconf.h:356
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/ipv6/addrconf.c (ffffffff8209654d)
Location: include/net/addrconf.h:364
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff8396bce9)
Location: include/net/addrconf.h:364
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffff820b1f3b)
Location: include/net/addrconf.h:364
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff820c28f7)
Location: include/net/addrconf.h:364
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e09ca)
Location: include/net/addrconf.h:364
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_ifdown
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/ipv6/addrconf.c (ffff800010d08fe8)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffff8000114b4490)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffff800010d206f8)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffff800010d3143c)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d48be8)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/ipv6/addrconf.c (c0e0f574)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (c15b97c0)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (c0e256e4)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (c0e34820)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (c0e49e58)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/ipv6/addrconf.c (c000000000e3359c)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (c0000000013c5f18)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (c000000000e4f680)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (c000000000e63a2c)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7dbd0)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/ipv6/addrconf.c (ffffffe000850d4c)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffe00004327e)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffe00086277a)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffe00086fd32)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffe000881f7a)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct inet6_dev *in6_dev_get(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819e59f3)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff819ed9c7)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
Direct callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
```
```
In net/ipv6/ndisc.c (ffffffff819faea1)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81a09a8c)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a1d041)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff819f35b2-ffffffff819f35cc: in6_dev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct inet6_dev *in6_dev_get(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819a27b3)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff819aa787)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
Direct callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
```
```
In net/ipv6/ndisc.c (ffffffff819b7c61)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff819c684c)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d9e01)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff819b0372-ffffffff819b038c: in6_dev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct inet6_dev *in6_dev_get(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a50473)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81a58447)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
Direct callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
```
```
In net/ipv6/ndisc.c (ffffffff81a65921)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81a7450c)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a87ac1)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81a5e032-ffffffff81a5e04c: in6_dev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct inet6_dev *in6_dev_get(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a5c498)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81a645db)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
Direct callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
```
```
In net/ipv6/ndisc.c (ffffffff81a71eb4)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81a80bac)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a946ba)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
**Symbols:**

```
ffffffff81a6a442-ffffffff81a6a478: in6_dev_get (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
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
