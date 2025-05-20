# Function: <code>in6_dev_finish_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff817ff8e0)
Location: net/ipv6/addrconf_core.c:155
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff817ff8e0-ffffffff817ff991: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81870f90)
Location: net/ipv6/addrconf_core.c:155
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81870f90-ffffffff81871044: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff818a54e0)
Location: net/ipv6/addrconf_core.c:155
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff818a54e0-ffffffff818a5594: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff818cbfb0)
Location: net/ipv6/addrconf_core.c:174
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff818cbfb0-ffffffff818cc02d: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81950d60)
Location: net/ipv6/addrconf_core.c:175
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81950d60-ffffffff81950ddd: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf_core.c (0)
Location: net/ipv6/addrconf_core.c:214
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff819aa462-ffffffff819aa476: in6_dev_finish_destroy.cold.3 (STB_LOCAL)
ffffffff819aa2e0-ffffffff819aa343: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf_core.c (0)
Location: net/ipv6/addrconf_core.c:214
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff819e0f72-ffffffff819e0f86: in6_dev_finish_destroy.cold.3 (STB_LOCAL)
ffffffff819e0df0-ffffffff819e0e53: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf_core.c (0)
Location: net/ipv6/addrconf_core.c:237
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81a4fce9-ffffffff81a4fd36: in6_dev_finish_destroy.cold (STB_LOCAL)
ffffffff81a4fb40-ffffffff81a4fbb1: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf_core.c (0)
Location: net/ipv6/addrconf_core.c:239
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81a86979-ffffffff81a8698d: in6_dev_finish_destroy.cold (STB_LOCAL)
ffffffff81a867e0-ffffffff81a86850: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf_core.c (0)
Location: net/ipv6/addrconf_core.c:240
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81b81c2a-ffffffff81b81c3e: in6_dev_finish_destroy.cold (STB_LOCAL)
ffffffff81b81b70-ffffffff81b81be4: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf_core.c (0)
Location: net/ipv6/addrconf_core.c:248
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81c3318a-ffffffff81c3319e: in6_dev_finish_destroy.cold (STB_LOCAL)
ffffffff81b91270-ffffffff81b912e4: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf_core.c (0)
Location: net/ipv6/addrconf_core.c:255
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_gq_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81c2548e-ffffffff81c254a2: in6_dev_finish_destroy.cold (STB_LOCAL)
ffffffff81b80470-ffffffff81b804e8: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf_core.c (0)
Location: net/ipv6/addrconf_core.c:255
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_gq_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81d41882-ffffffff81d41896: in6_dev_finish_destroy.cold (STB_LOCAL)
ffffffff81c4c490-ffffffff81c4c50d: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf_core.c (0)
Location: net/ipv6/addrconf_core.c:255
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_gq_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81f0e1e9-ffffffff81f0e1fd: in6_dev_finish_destroy.cold (STB_LOCAL)
ffffffff81dec820-ffffffff81dec8ab: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81fc05b0)
Location: net/ipv6/addrconf_core.c:255
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_gq_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81fc05b0-ffffffff81fc064c: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff82021530)
Location: net/ipv6/addrconf_core.c:255
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_gq_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff82021530-ffffffff820215cc: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff820f0660)
Location: net/ipv6/addrconf_core.c:262
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_gq_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_ifdown
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff820f0660-ffffffff820f06fc: in6_dev_finish_destroy (STB_GLOBAL)
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
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffff800010d52ef8)
Location: net/ipv6/addrconf_core.c:239
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffff800010d52ef8-ffff800010d52fb4: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (c0e536e4)
Location: net/ipv6/addrconf_core.c:239
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
c0e536e4-c0e537e0: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (c000000000e8b3d0)
Location: net/ipv6/addrconf_core.c:239
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
c000000000e8b3d0-c000000000e8b4a4: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffe00088abd6)
Location: net/ipv6/addrconf_core.c:239
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffe00088abd6-ffffffe00088ac76: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf_core.c (0)
Location: net/ipv6/addrconf_core.c:239
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81a26009-ffffffff81a2601d: in6_dev_finish_destroy.cold (STB_LOCAL)
ffffffff81a25e70-ffffffff81a25ee0: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf_core.c (0)
Location: net/ipv6/addrconf_core.c:239
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff819e2dc9-ffffffff819e2ddd: in6_dev_finish_destroy.cold (STB_LOCAL)
ffffffff819e2c30-ffffffff819e2ca0: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf_core.c (0)
Location: net/ipv6/addrconf_core.c:239
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81a91bb9-ffffffff81a91bcd: in6_dev_finish_destroy.cold (STB_LOCAL)
ffffffff81a91a20-ffffffff81a91a90: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev *idev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf_core.c (0)
Location: net/ipv6/addrconf_core.c:239
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
**Symbols:**

```
ffffffff81a9dc69-ffffffff81a9dc7d: in6_dev_finish_destroy.cold (STB_LOCAL)
ffffffff81a9dad0-ffffffff81a9db40: in6_dev_finish_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
