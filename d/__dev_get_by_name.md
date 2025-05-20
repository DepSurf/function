# Function: <code>__dev_get_by_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817182a0)
Location: net/core/dev.c:723
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:netdev_boot_base
  - net/core/ethtool.c:dev_ethtool
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff817182a0-ffffffff81718317: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81780af0)
Location: net/core/dev.c:727
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:netdev_boot_base
  - net/core/ethtool.c:dev_ethtool
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81780af0-ffffffff81780b65: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ae040)
Location: net/core/dev.c:726
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:netdev_boot_base
  - net/core/ethtool.c:dev_ethtool
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff817ae040-ffffffff817ae0b5: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cc940)
Location: net/core/dev.c:733
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:netdev_boot_base
  - net/core/ethtool.c:dev_ethtool
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff817cc940-ffffffff817cc9d3: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818462c0)
Location: net/core/dev.c:736
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_base
  - net/core/ethtool.c:dev_ethtool
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff818462c0-ffffffff81846353: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:736
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_base
  - net/core/ethtool.c:dev_ethtool
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81898f46-ffffffff81898f52: __dev_get_by_name.cold.152 (STB_LOCAL)
ffffffff8188f9a0-ffffffff8188fa2b: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:738
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_base
  - net/core/ethtool.c:dev_ethtool
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff818bb3b2-ffffffff818bb3be: __dev_get_by_name.cold.158 (STB_LOCAL)
ffffffff818b0120-ffffffff818b019c: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:734
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_base
  - net/core/ethtool.c:dev_ethtool
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff8190729b-ffffffff819072a7: __dev_get_by_name.cold (STB_LOCAL)
ffffffff818fce50-ffffffff818fcecf: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:652
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_base
  - net/core/ethtool.c:dev_ethtool
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff819398fb-ffffffff81939907: __dev_get_by_name.cold (STB_LOCAL)
ffffffff8192f460-ffffffff8192f4df: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a04fb8)
Location: net/core/dev.c:858
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:netdev_boot_base
Direct callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/addrconf.c:addrconf_set_sit_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81a01ed0-ffffffff81a01ee9: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a055c8)
Location: net/core/dev.c:861
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:netdev_boot_base
Direct callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/addrconf.c:addrconf_set_sit_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81a02510-ffffffff81a02529: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819edb08)
Location: net/core/dev.c:909
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:netdev_boot_base
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff819e9080-ffffffff819e9099: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9ed3d)
Location: net/core/dev.c:786
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81a99eb0-ffffffff81a99ec9: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c13eb0)
Location: net/core/dev.c:733
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81c13eb0-ffffffff81c13ed1: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc4550)
Location: net/core/dev.c:733
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81dc4550-ffffffff81dc4571: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e345b0)
Location: net/core/dev.c:731
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81e345b0-ffffffff81e345d1: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef1f90)
Location: net/core/dev.c:748
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81ef1f90-ffffffff81ef1fb1: __dev_get_by_name (STB_GLOBAL)
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
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bca1e0)
Location: net/core/dev.c:652
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_base
  - net/core/ethtool.c:dev_ethtool
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffff800010bca1e0-ffff800010bca284: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce83d8)
Location: net/core/dev.c:652
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_base
  - net/core/ethtool.c:dev_ethtool
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/core/fib_rules.c:fib_nl2rule
  - net/core/fib_rules.c:fib_nl2rule
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
c0ce83d8-c0ce847c: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca9800)
Location: net/core/dev.c:652
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_base
  - net/core/ethtool.c:dev_ethtool
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
c000000000ca9800-c000000000ca998c: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007571bc)
Location: net/core/dev.c:652
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_boot_base
  - net/core/ethtool.c:dev_ethtool
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffe0007571bc-ffffffe000757236: __dev_get_by_name (STB_GLOBAL)
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
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:652
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_base
  - net/core/ethtool.c:dev_ethtool
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff818d98cb-ffffffff818d98d7: __dev_get_by_name.cold (STB_LOCAL)
ffffffff818cf460-ffffffff818cf4df: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:652
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_base
  - net/core/ethtool.c:dev_ethtool
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff8189370b-ffffffff81893717: __dev_get_by_name.cold (STB_LOCAL)
ffffffff81889580-ffffffff818895ff: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:652
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_base
  - net/core/ethtool.c:dev_ethtool
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff8192a8fb-ffffffff8192a907: __dev_get_by_name.cold (STB_LOCAL)
ffffffff81920460-ffffffff819204df: __dev_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct net_device *__dev_get_by_name(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:652
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_base
  - net/core/ethtool.c:dev_ethtool
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/wireless/wext-core.c:wireless_process_ioctl
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff8194c045-ffffffff8194c051: __dev_get_by_name.cold (STB_LOCAL)
ffffffff819421c0-ffffffff8194223f: __dev_get_by_name (STB_GLOBAL)
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
