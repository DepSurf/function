# Function: <code>dev_net_set</code>

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
Location: include/linux/netdevice.h:1944
Inline: True
```
```
In drivers/net/tun.c (ffffffff815f04da)
Location: include/linux/netdevice.h:1944
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f8b0d)
Location: include/linux/netdevice.h:1944
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/dev.c (ffffffff817187a5)
Location: include/linux/netdevice.h:1944
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/rtnetlink.c (ffffffff8172a3eb)
Location: include/linux/netdevice.h:1944
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff817a7da6)
Location: include/linux/netdevice.h:1944
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff817fa8ea)
Location: include/linux/netdevice.h:1944
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff81647f3b)
Location: include/linux/netdevice.h:2021
Inline: True
```
```
In drivers/net/tun.c (ffffffff8164f8f4)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81658b3d)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/dev.c (ffffffff8178435b)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/rtnetlink.c (ffffffff81793e22)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff818906d9)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff8186a171)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff8167905b)
Location: include/linux/netdevice.h:2003
Inline: True
```
```
In drivers/net/tun.c (ffffffff81681ab3)
Location: include/linux/netdevice.h:2003
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff816868c4)
Location: include/linux/netdevice.h:2003
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/dev.c (ffffffff817b196b)
Location: include/linux/netdevice.h:2003
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/rtnetlink.c (ffffffff817c16a2)
Location: include/linux/netdevice.h:2003
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff818c4cf3)
Location: include/linux/netdevice.h:2003
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff8189cfc1)
Location: include/linux/netdevice.h:2003
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff8168d9db)
Location: include/linux/netdevice.h:2027
Inline: True
```
```
In drivers/net/tun.c (ffffffff81696a44)
Location: include/linux/netdevice.h:2027
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8169bc1b)
Location: include/linux/netdevice.h:2027
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/dev.c (ffffffff817cb6e2)
Location: include/linux/netdevice.h:2027
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/rtnetlink.c (ffffffff817dfe74)
Location: include/linux/netdevice.h:2027
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff81868ef9)
Location: include/linux/netdevice.h:2027
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff818c3493)
Location: include/linux/netdevice.h:2027
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff816f758b)
Location: include/linux/netdevice.h:2043
Inline: True
```
```
In drivers/net/tun.c (ffffffff817018b2)
Location: include/linux/netdevice.h:2043
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81706c96)
Location: include/linux/netdevice.h:2043
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/dev.c (ffffffff81844f2f)
Location: include/linux/netdevice.h:2043
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/rtnetlink.c (ffffffff8185a744)
Location: include/linux/netdevice.h:2043
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff818e95c3)
Location: include/linux/netdevice.h:2043
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff81946729)
Location: include/linux/netdevice.h:2043
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff81734728)
Location: include/linux/netdevice.h:2111
Inline: True
```
```
In drivers/net/tun.c (ffffffff8173e0e7)
Location: include/linux/netdevice.h:2111
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817459c1)
Location: include/linux/netdevice.h:2111
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/dev.c (ffffffff8188fe58)
Location: include/linux/netdevice.h:2111
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/rtnetlink.c (ffffffff818a5fd4)
Location: include/linux/netdevice.h:2111
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff8193faf6)
Location: include/linux/netdevice.h:2111
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff8199fbce)
Location: include/linux/netdevice.h:2111
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff81757868)
Location: include/linux/netdevice.h:2176
Inline: True
```
```
In drivers/net/tun.c (ffffffff81762053)
Location: include/linux/netdevice.h:2176
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81769ab1)
Location: include/linux/netdevice.h:2176
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/dev.c (ffffffff818b07c4)
Location: include/linux/netdevice.h:2176
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (ffffffff818c95e8)
Location: include/linux/netdevice.h:2176
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff8196fb36)
Location: include/linux/netdevice.h:2176
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff819d6851)
Location: include/linux/netdevice.h:2176
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff82902e60)
Location: include/linux/netdevice.h:2167
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
```
```
In drivers/net/tun.c (ffffffff8179fd6f)
Location: include/linux/netdevice.h:2167
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a7555)
Location: include/linux/netdevice.h:2167
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/dev.c (ffffffff818fd50f)
Location: include/linux/netdevice.h:2167
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (ffffffff819165c9)
Location: include/linux/netdevice.h:2167
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff819d944e)
Location: include/linux/netdevice.h:2167
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff81a458fe)
Location: include/linux/netdevice.h:2167
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff8290c05d)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
```
```
In drivers/net/tun.c (ffffffff817c3fff)
Location: include/linux/netdevice.h:2180
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817cafc5)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/dev.c (ffffffff8192fb36)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (ffffffff81948bfc)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff81a101be)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff81a7c4ee)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff82d20f86)
Location: include/linux/netdevice.h:2265
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
```
```
In drivers/net/tun.c (ffffffff8188f9f9)
Location: include/linux/netdevice.h:2265
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81893e8b)
Location: include/linux/netdevice.h:2265
Inline: True
```
```
In net/core/dev.c (ffffffff81a04d9c)
Location: include/linux/netdevice.h:2265
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (ffffffff81a18a0c)
Location: include/linux/netdevice.h:2265
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff81b01177)
Location: include/linux/netdevice.h:2265
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff81b73cea)
Location: include/linux/netdevice.h:2265
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff8300ed65)
Location: include/linux/netdevice.h:2352
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
```
```
In drivers/net/tun.c (ffffffff8189ddb2)
Location: include/linux/netdevice.h:2352
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a24bd)
Location: include/linux/netdevice.h:2352
Inline: True
```
```
In net/core/dev.c (ffffffff81a053bc)
Location: include/linux/netdevice.h:2352
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (ffffffff81a18abc)
Location: include/linux/netdevice.h:2352
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff81b0f257)
Location: include/linux/netdevice.h:2352
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff81b82a5a)
Location: include/linux/netdevice.h:2352
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff83219d49)
Location: include/linux/netdevice.h:2416
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
```
```
In drivers/net/tun.c (ffffffff81880522)
Location: include/linux/netdevice.h:2416
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81884995)
Location: include/linux/netdevice.h:2416
Inline: True
```
```
In net/core/dev.c (ffffffff819ed7e2)
Location: include/linux/netdevice.h:2416
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (ffffffff819ff969)
Location: include/linux/netdevice.h:2416
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff81afcf5d)
Location: include/linux/netdevice.h:2416
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff81b716c3)
Location: include/linux/netdevice.h:2416
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff8330381e)
Location: include/linux/netdevice.h:2436
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
```
```
In drivers/net/tun.c (ffffffff81911dc2)
Location: include/linux/netdevice.h:2436
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81916355)
Location: include/linux/netdevice.h:2436
Inline: True
```
```
In net/core/dev.c (ffffffff81a9ea02)
Location: include/linux/netdevice.h:2436
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (ffffffff81ab1c4b)
Location: include/linux/netdevice.h:2436
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff81bbe712)
Location: include/linux/netdevice.h:2436
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff81c3bb39)
Location: include/linux/netdevice.h:2436
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff834bc7cd)
Location: include/linux/netdevice.h:2514
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
```
```
In drivers/net/tun.c (ffffffff81a64d39)
Location: include/linux/netdevice.h:2514
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6c432)
Location: include/linux/netdevice.h:2514
Inline: True
```
```
In net/core/dev.c (ffffffff81c1772e)
Location: include/linux/netdevice.h:2514
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (ffffffff81c2af2c)
Location: include/linux/netdevice.h:2514
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff81d536be)
Location: include/linux/netdevice.h:2514
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff81dd9ea7)
Location: include/linux/netdevice.h:2514
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff83efabc8)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
```
```
In drivers/net/tun.c (ffffffff81beffb4)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bff392)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/dev.c (ffffffff81dc873e)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (ffffffff81dde86c)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff81f1d37d)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff81fabb4c)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff83720908)
Location: include/linux/netdevice.h:2594
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
```
```
In drivers/net/tun.c (ffffffff81c48532)
Location: include/linux/netdevice.h:2594
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c64966)
Location: include/linux/netdevice.h:2594
Inline: True
```
```
In drivers/net/net_failover.c (ffffffff81c6f540)
Location: include/linux/netdevice.h:2594
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_create
```
```
In net/core/dev.c (ffffffff81e38a2a)
Location: include/linux/netdevice.h:2594
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (ffffffff81e4f8d2)
Location: include/linux/netdevice.h:2594
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff81f7ce5c)
Location: include/linux/netdevice.h:2594
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff8200c2ec)
Location: include/linux/netdevice.h:2594
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff839547a8)
Location: include/linux/netdevice.h:2653
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
```
```
In drivers/net/tun.c (ffffffff81cfdeb6)
Location: include/linux/netdevice.h:2653
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1b386)
Location: include/linux/netdevice.h:2653
Inline: True
```
```
In drivers/net/net_failover.c (ffffffff81d23df0)
Location: include/linux/netdevice.h:2653
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_create
```
```
In net/core/dev.c (ffffffff81ef6bd0)
Location: include/linux/netdevice.h:2653
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (ffffffff81f0e912)
Location: include/linux/netdevice.h:2653
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff8204355c)
Location: include/linux/netdevice.h:2653
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff820db2bc)
Location: include/linux/netdevice.h:2653
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffff80001149b87c)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
```
```
In drivers/net/tun.c (ffff8000109deabc)
Location: include/linux/netdevice.h:2180
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a02a90)
Location: include/linux/netdevice.h:2180
Inline: True
```
```
In net/core/dev.c (ffff800010bccfe8)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (ffff800010bebf90)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffff800010ccd694)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffff800010d4662c)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
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
In drivers/net/loopback.c (c159caf4)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
```
```
In drivers/net/tun.c (c0ac3cf8)
Location: include/linux/netdevice.h:2180
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (c0adf8d4)
Location: include/linux/netdevice.h:2180
Inline: True
```
```
In net/core/dev.c (c0ce8a98)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (c0d03258)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (c0dd5410)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (c0e48c24)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
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
In drivers/net/loopback.c (c0000000013afc3c)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
```
```
In drivers/net/tun.c (c000000000aa030c)
Location: include/linux/netdevice.h:2180
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aab3b8)
Location: include/linux/netdevice.h:2180
Inline: True
```
```
In net/core/dev.c (c000000000caadf0)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (c000000000ccd33c)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (c000000000dec96c)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (c000000000e7c094)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffe000034aa0)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
```
```
In drivers/net/tun.c (ffffffe0006292b8)
Location: include/linux/netdevice.h:2180
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062f00c)
Location: include/linux/netdevice.h:2180
Inline: True
```
```
In net/core/dev.c (ffffffe00075770c)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (ffffffe00076e104)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffe00081e070)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffe000881106)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff828f3a1a)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
```
```
In drivers/net/tun.c (ffffffff81788adf)
Location: include/linux/netdevice.h:2180
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178faa5)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/dev.c (ffffffff818cfb36)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (ffffffff818e8bcc)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff819afbde)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff81a1bb7e)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff828eaec5)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
```
```
In drivers/net/tun.c (ffffffff8176842f)
Location: include/linux/netdevice.h:2180
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81778875)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/dev.c (ffffffff81889c56)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (ffffffff818a2a0c)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ip_tunnel.c (ffffffff81966dff)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:__ip_tunnel_create
```
```
In net/ipv4/ipmr.c (ffffffff8196c20e)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff819d893e)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff82907458)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
```
```
In drivers/net/tun.c (ffffffff817b8e7f)
Location: include/linux/netdevice.h:2180
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bfe45)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/dev.c (ffffffff81920b36)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (ffffffff81939bfc)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff81a1a47e)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff81a865fe)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
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
In drivers/net/loopback.c (ffffffff8290d0bf)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - drivers/net/loopback.c:blackhole_netdev_init
```
```
In drivers/net/tun.c (ffffffff817d3b4f)
Location: include/linux/netdevice.h:2180
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817da0ed)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/dev.c (ffffffff819428c6)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:init_dummy_netdev
```
```
In net/core/rtnetlink.c (ffffffff8195b2dc)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
```
In net/ipv4/ipmr.c (ffffffff81a252ae)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/ip6mr.c (ffffffff81a931be)
Location: include/linux/netdevice.h:2180
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
</details>
</li>
</ul>

## Differences
