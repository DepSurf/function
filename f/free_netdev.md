# Function: <code>free_netdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81716360)
Location: net/core/dev.c:7179
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:xennet_free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81716360-ffffffff81716445: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177e4f0)
Location: net/core/dev.c:7696
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:xennet_free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff8177e4f0-ffffffff8177e5db: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817abcf0)
Location: net/core/dev.c:7867
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:xennet_free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff817abcf0-ffffffff817abddb: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ca280)
Location: net/core/dev.c:8054
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:xennet_free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ethernet/eth.c:devm_free_netdev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff817ca280-ffffffff817ca389: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81843d80)
Location: net/core/dev.c:8233
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:xennet_free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ethernet/eth.c:devm_free_netdev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81843d80-ffffffff81843e89: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81890f80)
Location: net/core/dev.c:8492
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ethernet/eth.c:devm_free_netdev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81890f80-ffffffff818910ab: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b15b0)
Location: net/core/dev.c:9122
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ethernet/eth.c:devm_free_netdev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff818b15b0-ffffffff818b16d9: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fe350)
Location: net/core/dev.c:9227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ethernet/eth.c:devm_free_netdev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff818fe350-ffffffff818fe479: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81930680)
Location: net/core/dev.c:9569
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_free_netdev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81930680-ffffffff819307a9: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a04290)
Location: net/core/dev.c:10024
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/devres.c:devm_free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff81a04290-ffffffff81a043d2: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a062a0)
Location: net/core/dev.c:10722
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/devres.c:devm_free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff81a062a0-ffffffff81a06440: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ecdf0)
Location: net/core/dev.c:10901
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/devres.c:devm_free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff819ecdf0-ffffffff819ecf90: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10908
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/devres.c:devm_free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff81d36256-ffffffff81d3626b: free_netdev.cold (STB_LOCAL)
ffffffff81a9dff0-ffffffff81a9e198: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10685
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/xen-netfront.c:xennet_remove
  - net/devres.c:devm_free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff81f027c1-ffffffff81f027d6: free_netdev.cold (STB_LOCAL)
ffffffff81c127d0-ffffffff81c129b9: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10680
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/xen-netfront.c:xennet_remove
  - net/devres.c:devm_free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff820ab3c7-ffffffff820ab3dc: free_netdev.cold (STB_LOCAL)
ffffffff81dc28e0-ffffffff81dc2ac9: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10696
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/net_failover.c:net_failover_create
  - net/devres.c:devm_free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff8212c9fc-ffffffff8212ca11: free_netdev.cold (STB_LOCAL)
ffffffff81e31d90-ffffffff81e31f79: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10907
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/net_failover.c:net_failover_create
  - net/devres.c:devm_free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_create_link
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff8220e73b-ffffffff8220e750: free_netdev.cold (STB_LOCAL)
ffffffff81ef0210-ffffffff81ef03fc: free_netdev (STB_GLOBAL)
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
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcc5c8)
Location: net/core/dev.c:9569
Inline: False
Direct callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_remove
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_free_netdev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffff800010bcc5c8-ffff800010bcc6d8: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce53c8)
Location: net/core/dev.c:9569
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_free_netdev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
c0ce53c8-c0ce54c0: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cab860)
Location: net/core/dev.c:9569
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_free_netdev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
c000000000cab860-c000000000cab9dc: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075805a)
Location: net/core/dev.c:9569
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_free_netdev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffe00075805a-ffffffe000758166: free_netdev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d0680)
Location: net/core/dev.c:9569
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_free_netdev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff818d0680-ffffffff818d07a9: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188a560)
Location: net/core/dev.c:9569
Inline: False
Direct callers:
  - drivers/net/vxlan.c:vxlan_dev_create
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_free_netdev
  - net/ipv4/ip_tunnel.c:__ip_tunnel_create
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff8188a560-ffffffff8188a689: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81921680)
Location: net/core/dev.c:9569
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_free_netdev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81921680-ffffffff819217a9: free_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193fe20)
Location: net/core/dev.c:9569
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_free_netdev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff8193fe20-ffffffff8193ff43: free_netdev (STB_GLOBAL)
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
