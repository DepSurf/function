# Function: <code>unregister_netdevice</code>

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
In drivers/net/tun.c (ffffffff815efd2a)
Location: include/linux/netdevice.h:2288
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f5af4)
Location: include/linux/netdevice.h:2288
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/dev.c (ffffffff817179a2)
Location: include/linux/netdevice.h:2288
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff8172cf7d)
Location: include/linux/netdevice.h:2288
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink
```
```
In net/ipv4/ipmr.c (ffffffff817a8243)
Location: include/linux/netdevice.h:2288
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff817fb17e)
Location: include/linux/netdevice.h:2288
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In drivers/net/tun.c (ffffffff8164efd6)
Location: include/linux/netdevice.h:2423
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81658e10)
Location: include/linux/netdevice.h:2423
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffff8177f9c2)
Location: include/linux/netdevice.h:2423
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff81799f21)
Location: include/linux/netdevice.h:2423
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink
```
```
In net/ipv4/ipmr.c (ffffffff81890753)
Location: include/linux/netdevice.h:2423
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff8186aa0c)
Location: include/linux/netdevice.h:2423
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In drivers/net/tun.c (ffffffff81680ce6)
Location: include/linux/netdevice.h:2420
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81686b92)
Location: include/linux/netdevice.h:2420
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffff817acbf2)
Location: include/linux/netdevice.h:2420
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff817c7cc1)
Location: include/linux/netdevice.h:2420
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink
```
```
In net/ipv4/ipmr.c (ffffffff818c4d6d)
Location: include/linux/netdevice.h:2420
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff8189d85c)
Location: include/linux/netdevice.h:2420
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In drivers/net/tun.c (ffffffff81696336)
Location: include/linux/netdevice.h:2435
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8169ba59)
Location: include/linux/netdevice.h:2435
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffff817cb372)
Location: include/linux/netdevice.h:2435
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff817e65b7)
Location: include/linux/netdevice.h:2435
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink
```
```
In net/ipv4/ipmr.c (ffffffff81868f48)
Location: include/linux/netdevice.h:2435
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff818c3de0)
Location: include/linux/netdevice.h:2435
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In drivers/net/tun.c (ffffffff81700ecd)
Location: include/linux/netdevice.h:2460
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81706a40)
Location: include/linux/netdevice.h:2460
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffff81844c02)
Location: include/linux/netdevice.h:2460
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff81861664)
Location: include/linux/netdevice.h:2460
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink
```
```
In net/ipv4/ipmr.c (ffffffff818e99a0)
Location: include/linux/netdevice.h:2460
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffffffff81947079)
Location: include/linux/netdevice.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In drivers/net/tun.c (ffffffff8173fb9a)
Location: include/linux/netdevice.h:2546
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817421ca)
Location: include/linux/netdevice.h:2546
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffff818982e2)
Location: include/linux/netdevice.h:2546
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff818ad218)
Location: include/linux/netdevice.h:2546
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink
```
```
In net/ipv4/ipmr.c (ffffffff8193fc3e)
Location: include/linux/netdevice.h:2546
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffffffff819a001c)
Location: include/linux/netdevice.h:2546
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In drivers/net/tun.c (ffffffff817617ba)
Location: include/linux/netdevice.h:2640
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817662da)
Location: include/linux/netdevice.h:2640
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffff818ba742)
Location: include/linux/netdevice.h:2640
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff818d13f6)
Location: include/linux/netdevice.h:2640
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
```
In net/ipv4/ipmr.c (ffffffff8196fc80)
Location: include/linux/netdevice.h:2640
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffffffff819d6bac)
Location: include/linux/netdevice.h:2640
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In drivers/net/tun.c (ffffffff8179f499)
Location: include/linux/netdevice.h:2629
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a3a72)
Location: include/linux/netdevice.h:2629
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffff818fcc03)
Location: include/linux/netdevice.h:2629
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff8191e2a1)
Location: include/linux/netdevice.h:2629
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
```
In net/ipv4/ipmr.c (ffffffff819d953a)
Location: include/linux/netdevice.h:2629
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffffffff81a45c90)
Location: include/linux/netdevice.h:2629
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In drivers/net/tun.c (ffffffff817c32ea)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c74c2)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffff8192f213)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff819508d1)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
```
In net/ipv4/ipmr.c (ffffffff81a102aa)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffffffff81a7c880)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In drivers/net/tun.c (ffffffff8188c881)
Location: include/linux/netdevice.h:2752
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818920da)
Location: include/linux/netdevice.h:2752
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffff81a0e333)
Location: include/linux/netdevice.h:2752
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff81a1d8e1)
Location: include/linux/netdevice.h:2752
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
```
In net/ipv4/ipmr.c (ffffffff81b012bb)
Location: include/linux/netdevice.h:2752
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffffffff81b73f18)
Location: include/linux/netdevice.h:2752
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
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
In drivers/net/tun.c (ffffffff8189aa34)
Location: include/linux/netdevice.h:2900
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a052a)
Location: include/linux/netdevice.h:2900
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffff81a05ea3)
Location: include/linux/netdevice.h:2900
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff81a1dddc)
Location: include/linux/netdevice.h:2900
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
```
In net/ipv4/ipmr.c (ffffffff81b0f39b)
Location: include/linux/netdevice.h:2900
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffffffff81b82c88)
Location: include/linux/netdevice.h:2900
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
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
In drivers/net/tun.c (ffffffff8187d29b)
Location: include/linux/netdevice.h:2967
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81882d9a)
Location: include/linux/netdevice.h:2967
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffff819ec7d3)
Location: include/linux/netdevice.h:2967
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff81a04be9)
Location: include/linux/netdevice.h:2967
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
```
In net/ipv4/ipmr.c (ffffffff81afd0a7)
Location: include/linux/netdevice.h:2967
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffffffff81b71908)
Location: include/linux/netdevice.h:2967
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
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
In drivers/net/tun.c (ffffffff8190e948)
Location: include/linux/netdevice.h:2987
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8191473a)
Location: include/linux/netdevice.h:2987
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffff81a9d703)
Location: include/linux/netdevice.h:2987
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff81ab71f2)
Location: include/linux/netdevice.h:2987
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
```
In net/ipv4/ipmr.c (ffffffff81bbe869)
Location: include/linux/netdevice.h:2987
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffffffff81c3bd7e)
Location: include/linux/netdevice.h:2987
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
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
In drivers/net/tun.c (ffffffff81a633a5)
Location: include/linux/netdevice.h:3030
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a69d21)
Location: include/linux/netdevice.h:3030
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffff81c16f52)
Location: include/linux/netdevice.h:3030
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff81c2defc)
Location: include/linux/netdevice.h:3030
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink_create
```
```
In net/ipv4/ipmr.c (ffffffff81d537b5)
Location: include/linux/netdevice.h:3030
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffffffff81dda0d0)
Location: include/linux/netdevice.h:3030
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
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
In drivers/net/tun.c (ffffffff81bee782)
Location: include/linux/netdevice.h:3055
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfc8f1)
Location: include/linux/netdevice.h:3055
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffff81dd1a62)
Location: include/linux/netdevice.h:3055
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff81de10ed)
Location: include/linux/netdevice.h:3055
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink_create
```
```
In net/ipv4/ipmr.c (ffffffff81f1d4bd)
Location: include/linux/netdevice.h:3055
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffffffff81fabd7c)
Location: include/linux/netdevice.h:3055
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
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
In drivers/net/tun.c (ffffffff81c46cb2)
Location: include/linux/netdevice.h:3110
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c61f71)
Location: include/linux/netdevice.h:3110
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In drivers/net/net_failover.c (ffffffff81c6f901)
Location: include/linux/netdevice.h:3110
Inline: True
```
```
In net/core/dev.c (ffffffff81e42642)
Location: include/linux/netdevice.h:3110
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff81e527dd)
Location: include/linux/netdevice.h:3110
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink_create
```
```
In net/ipv4/ipmr.c (ffffffff81f7cf6a)
Location: include/linux/netdevice.h:3110
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffffffff8200c51c)
Location: include/linux/netdevice.h:3110
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
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
In drivers/net/netkit.c (ffffffff81ce5dd5)
Location: include/linux/netdevice.h:3191
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_new_link
```
```
In drivers/net/tun.c (ffffffff81cfc5cc)
Location: include/linux/netdevice.h:3191
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d18971)
Location: include/linux/netdevice.h:3191
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In drivers/net/net_failover.c (ffffffff81d241b1)
Location: include/linux/netdevice.h:3191
Inline: True
```
```
In net/core/dev.c (ffffffff81f01272)
Location: include/linux/netdevice.h:3191
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff81f117ad)
Location: include/linux/netdevice.h:3191
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink_create
```
```
In net/ipv4/ipmr.c (ffffffff8204366a)
Location: include/linux/netdevice.h:3191
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffffffff820db4ec)
Location: include/linux/netdevice.h:3191
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
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
In drivers/net/tun.c (ffff8000109ddee0)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000109ffcc4)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffff800010bcc05c)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffff800010bf2324)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
```
In net/ipv4/ipmr.c (ffff800010ccd798)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffff800010d46dc8)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In drivers/net/tun.c (c0ac444c)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (c0adc948)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (c0cea0e8)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (c0d0ac50)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
```
In net/ipv4/ipmr.c (c0dd5508)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (c0e49080)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In drivers/net/tun.c (c000000000aa1268)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa6780)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (c000000000ca8ad8)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (c000000000cd71b0)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
```
In net/ipv4/ipmr.c (c000000000decad4)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (c000000000e7c71c)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In drivers/net/tun.c (ffffffe000626fd0)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062c00a)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffe0007598fc)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffe000773edc)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
```
In net/ipv4/ipmr.c (ffffffe00081e15e)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffffffe0008814e0)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In drivers/net/tun.c (ffffffff81787dba)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178bfa2)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffff818cf213)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff818f08a1)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
```
In net/ipv4/ipmr.c (ffffffff819afcca)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffffffff81a1bf10)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In drivers/net/tun.c (ffffffff8176770a)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/vxlan.c (ffffffff81770064)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/vxlan.c:__vxlan_dev_create
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81774d72)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffff81889333)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff818aa6e1)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
```
In net/ipv4/ip_tunnel.c (ffffffff81968a2a)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_newlink
  - net/ipv4/ip_tunnel.c:ip_tunnel_ioctl
  - net/ipv4/ip_tunnel.c:ip_tunnel_ioctl
```
```
In net/ipv4/ipmr.c (ffffffff8196c2fa)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffffffff819d8cd0)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In drivers/net/tun.c (ffffffff817b816a)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bc342)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffff81920213)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff819418d1)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
```
In net/ipv4/ipmr.c (ffffffff81a1a56a)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffffffff81a86990)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In drivers/net/tun.c (ffffffff817d4bff)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d66e2)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In net/core/dev.c (ffffffff81941f73)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdev
```
```
In net/core/rtnetlink.c (ffffffff819631d1)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
```
In net/ipv4/ipmr.c (ffffffff81a2539a)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv6/ip6mr.c (ffffffff81a93550)
Location: include/linux/netdevice.h:2642
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
</details>
</li>
</ul>

## Differences
