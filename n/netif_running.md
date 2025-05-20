# Function: <code>netif_running</code>

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
In drivers/net/tun.c (ffffffff815f03de)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/virtio_net.c (ffffffff815f2956)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_freeze
  - drivers/net/virtio_net.c:virtnet_restore
```
```
In drivers/net/xen-netfront.c (ffffffff815fa878)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
```
In net/core/dev.c (ffffffff81713ae3)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/ethtool.c (ffffffff81721847)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/neighbour.c (ffffffff81724790)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff8172e184)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/link_watch.c (ffffffff81730595)
Location: include/linux/netdevice.h:2881
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81735695)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (ffffffff8173867e)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ethernet/eth.c (ffffffff8173fcb2)
Location: include/linux/netdevice.h:2881
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81741124)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b2cf2)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/addrconf.c (ffffffff817cb860)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/packet/af_packet.c (ffffffff81803757)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
```
In net/wireless/wext-core.c (ffffffff8180a442)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/tun.c (ffffffff8164fbb3)
Location: include/linux/netdevice.h:3104
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/virtio_net.c (ffffffff81653e11)
Location: include/linux/netdevice.h:3104
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_freeze
```
```
In drivers/net/xen-netfront.c (ffffffff8165c7b1)
Location: include/linux/netdevice.h:3104
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
```
In net/core/dev.c (ffffffff8177b8e3)
Location: include/linux/netdevice.h:3104
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/ethtool.c (ffffffff8178b2e6)
Location: include/linux/netdevice.h:3104
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/neighbour.c (ffffffff8178e160)
Location: include/linux/netdevice.h:3104
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff81798fb4)
Location: include/linux/netdevice.h:3104
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff8179ad05)
Location: include/linux/netdevice.h:3104
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff817a187e)
Location: include/linux/netdevice.h:3104
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (ffffffff817a496e)
Location: include/linux/netdevice.h:3104
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffff817ac9f2)
Location: include/linux/netdevice.h:3104
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff817adf44)
Location: include/linux/netdevice.h:3104
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181fd12)
Location: include/linux/netdevice.h:3104
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/addrconf.c (ffffffff81838890)
Location: include/linux/netdevice.h:3104
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/packet/af_packet.c (ffffffff81874997)
Location: include/linux/netdevice.h:3104
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
```
In net/wireless/wext-core.c (ffffffff8187bfac)
Location: include/linux/netdevice.h:3104
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/tun.c (ffffffff81681d69)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff8168a5e0)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
```
```
In net/core/dev.c (ffffffff817a9083)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/ethtool.c (ffffffff817b8713)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/neighbour.c (ffffffff817bbb10)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff817c6d64)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff817c8aa5)
Location: include/linux/netdevice.h:3043
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff817d019e)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (ffffffff817d33de)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffff817dc012)
Location: include/linux/netdevice.h:3043
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff817dd5c4)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/xfrm/xfrm_policy.c (ffffffff81851572)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/addrconf.c (ffffffff8186a3c0)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/packet/af_packet.c (ffffffff818a8ef7)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
```
In net/wireless/wext-core.c (ffffffff818b086c)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/tun.c (ffffffff81696cdd)
Location: include/linux/netdevice.h:3070
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff8169f8a1)
Location: include/linux/netdevice.h:3070
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
```
In net/core/dev.c (ffffffff817c75d3)
Location: include/linux/netdevice.h:3070
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/ethtool.c (ffffffff817d7918)
Location: include/linux/netdevice.h:3070
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/neighbour.c (ffffffff817da29b)
Location: include/linux/netdevice.h:3070
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff817e5674)
Location: include/linux/netdevice.h:3070
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff817e7675)
Location: include/linux/netdevice.h:3070
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff817ef8d5)
Location: include/linux/netdevice.h:3070
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (ffffffff817f2714)
Location: include/linux/netdevice.h:3070
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffff817fb74e)
Location: include/linux/netdevice.h:3070
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/sched/sch_generic.c (ffffffff817fcc03)
Location: include/linux/netdevice.h:3070
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/xfrm/xfrm_policy.c (ffffffff8187381e)
Location: include/linux/netdevice.h:3070
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/addrconf.c (ffffffff8188e91d)
Location: include/linux/netdevice.h:3070
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff81897eed)
Location: include/linux/netdevice.h:3070
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nexthop_info
```
```
In net/packet/af_packet.c (ffffffff818cf887)
Location: include/linux/netdevice.h:3070
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
```
In net/wireless/wext-core.c (ffffffff818d71e9)
Location: include/linux/netdevice.h:3070
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/tun.c (ffffffff81701b76)
Location: include/linux/netdevice.h:3095
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff8170aa36)
Location: include/linux/netdevice.h:3095
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
```
In net/core/dev.c (ffffffff818411b3)
Location: include/linux/netdevice.h:3095
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/core/ethtool.c (ffffffff81851a23)
Location: include/linux/netdevice.h:3095
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/neighbour.c (ffffffff81854a47)
Location: include/linux/netdevice.h:3095
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff81860714)
Location: include/linux/netdevice.h:3095
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff818625b5)
Location: include/linux/netdevice.h:3095
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff8186ae75)
Location: include/linux/netdevice.h:3095
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (ffffffff8186dcd4)
Location: include/linux/netdevice.h:3095
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffff818790fe)
Location: include/linux/netdevice.h:3095
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/sched/sch_generic.c (ffffffff8187a750)
Location: include/linux/netdevice.h:3095
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f4174)
Location: include/linux/netdevice.h:3095
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/addrconf.c (ffffffff8190ff6d)
Location: include/linux/netdevice.h:3095
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff81919272)
Location: include/linux/netdevice.h:3095
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nexthop_info
```
```
In net/packet/af_packet.c (ffffffff819547f7)
Location: include/linux/netdevice.h:3095
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
```
In net/wireless/wext-core.c (ffffffff8195cdbb)
Location: include/linux/netdevice.h:3095
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/tun.c (ffffffff8173df74)
Location: include/linux/netdevice.h:3204
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81749511)
Location: include/linux/netdevice.h:3204
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
```
In net/core/dev.c (ffffffff8188b8c0)
Location: include/linux/netdevice.h:3204
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffffffff8189d382)
Location: include/linux/netdevice.h:3204
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/neighbour.c (ffffffff818a1737)
Location: include/linux/netdevice.h:3204
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff818aa5c4)
Location: include/linux/netdevice.h:3204
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff818ae265)
Location: include/linux/netdevice.h:3204
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff818bb74c)
Location: include/linux/netdevice.h:3204
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (ffffffff818bee22)
Location: include/linux/netdevice.h:3204
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffff818caaee)
Location: include/linux/netdevice.h:3204
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/sched/sch_generic.c (ffffffff818cc730)
Location: include/linux/netdevice.h:3204
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194ab8b)
Location: include/linux/netdevice.h:3204
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/addrconf.c (ffffffff8196737d)
Location: include/linux/netdevice.h:3204
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/wireless/wext-core.c (ffffffff819b65bb)
Location: include/linux/netdevice.h:3204
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/tun.c (ffffffff81761ee0)
Location: include/linux/netdevice.h:3326
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8176d260)
Location: include/linux/netdevice.h:3326
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In net/core/dev.c (ffffffff818aca40)
Location: include/linux/netdevice.h:3326
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffffffff818becd5)
Location: include/linux/netdevice.h:3326
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/neighbour.c (ffffffff818c4677)
Location: include/linux/netdevice.h:3326
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff818d0464)
Location: include/linux/netdevice.h:3326
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff818d24e5)
Location: include/linux/netdevice.h:3326
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff818e24dc)
Location: include/linux/netdevice.h:3326
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (ffffffff818e7c1f)
Location: include/linux/netdevice.h:3326
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffff818f5bbe)
Location: include/linux/netdevice.h:3326
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/sched/sch_generic.c (ffffffff818f7a80)
Location: include/linux/netdevice.h:3326
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d6d3)
Location: include/linux/netdevice.h:3326
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8199c98a)
Location: include/linux/netdevice.h:3326
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/wireless/wext-core.c (ffffffff819ed87b)
Location: include/linux/netdevice.h:3326
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/tun.c (ffffffff8179fbed)
Location: include/linux/netdevice.h:3343
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817ab01d)
Location: include/linux/netdevice.h:3343
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In net/core/dev.c (ffffffff818f81c0)
Location: include/linux/netdevice.h:3343
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffffffff8190c102)
Location: include/linux/netdevice.h:3343
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/neighbour.c (ffffffff819103c5)
Location: include/linux/netdevice.h:3343
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff8191d314)
Location: include/linux/netdevice.h:3343
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff8191f785)
Location: include/linux/netdevice.h:3343
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81931d9c)
Location: include/linux/netdevice.h:3343
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (ffffffff819375a2)
Location: include/linux/netdevice.h:3343
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffff8195527e)
Location: include/linux/netdevice.h:3343
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/sched/sch_generic.c (ffffffff819571c2)
Location: include/linux/netdevice.h:3343
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e6b13)
Location: include/linux/netdevice.h:3343
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a08b61)
Location: include/linux/netdevice.h:3343
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/wireless/wext-core.c (ffffffff81a5ca00)
Location: include/linux/netdevice.h:3343
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/tun.c (ffffffff817c3e7d)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817cea5d)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In net/core/dev.c (ffffffff8192a350)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffffffff8193e6fa)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/neighbour.c (ffffffff81942a35)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff8194f944)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff819519c5)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff819648dc)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (ffffffff8196a462)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffff8198b71e)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/sched/sch_generic.c (ffffffff8198d662)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1db03)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a3f271)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/wireless/wext-core.c (ffffffff81a93680)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/phy/phy.c (ffffffff8187fd55)
Location: include/linux/netdevice.h:3470
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_do_ioctl_running
```
```
In drivers/net/tun.c (ffffffff8188f8d2)
Location: include/linux/netdevice.h:3470
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81898613)
Location: include/linux/netdevice.h:3470
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In net/core/dev.c (ffffffff819fe210)
Location: include/linux/netdevice.h:3470
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/neighbour.c (ffffffff81a12b80)
Location: include/linux/netdevice.h:3470
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff81a21155)
Location: include/linux/netdevice.h:3470
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81a22905)
Location: include/linux/netdevice.h:3470
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/net-sysfs.c (ffffffff81a3829c)
Location: include/linux/netdevice.h:3470
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:testing_show
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:carrier_store
```
```
In net/core/netpoll.c (ffffffff81a3e322)
Location: include/linux/netdevice.h:3470
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffff81a63a92)
Location: include/linux/netdevice.h:3470
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/sched/sch_generic.c (ffffffff81a65355)
Location: include/linux/netdevice.h:3470
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/common.c (ffffffff81a85625)
Location: include/linux/netdevice.h:3470
Inline: True
Inline callers:
  - net/ethtool/common.c:__ethtool_get_link
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f15d)
Location: include/linux/netdevice.h:3470
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/addrconf.c (ffffffff81b34ef1)
Location: include/linux/netdevice.h:3470
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/wireless/wext-core.c (ffffffff81b8eb3b)
Location: include/linux/netdevice.h:3470
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/phy/phy.c (ffffffff8188e605)
Location: include/linux/netdevice.h:3624
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_do_ioctl_running
```
```
In drivers/net/tun.c (ffffffff8189dc56)
Location: include/linux/netdevice.h:3624
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff818a69eb)
Location: include/linux/netdevice.h:3624
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In net/core/dev.c (ffffffff819fde20)
Location: include/linux/netdevice.h:3624
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/core/neighbour.c (ffffffff81a12ed0)
Location: include/linux/netdevice.h:3624
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff81a1f6d4)
Location: include/linux/netdevice.h:3624
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81a22c65)
Location: include/linux/netdevice.h:3624
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/net-sysfs.c (ffffffff81a3a4ec)
Location: include/linux/netdevice.h:3624
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:testing_show
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:carrier_store
```
```
In net/core/netpoll.c (ffffffff81a4112f)
Location: include/linux/netdevice.h:3624
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffff81a6bbf2)
Location: include/linux/netdevice.h:3624
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/sched/sch_generic.c (ffffffff81a6d485)
Location: include/linux/netdevice.h:3624
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/common.c (ffffffff81a8efb5)
Location: include/linux/netdevice.h:3624
Inline: True
Inline callers:
  - net/ethtool/common.c:__ethtool_get_link
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1d44d)
Location: include/linux/netdevice.h:3624
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/addrconf.c (ffffffff81b43b16)
Location: include/linux/netdevice.h:3624
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/wireless/wext-core.c (ffffffff81b9e7db)
Location: include/linux/netdevice.h:3624
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/phy/phy.c (ffffffff81870dd5)
Location: include/linux/netdevice.h:3709
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_do_ioctl_running
```
```
In drivers/net/tun.c (ffffffff818803c6)
Location: include/linux/netdevice.h:3709
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81889f39)
Location: include/linux/netdevice.h:3709
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In net/core/dev.c (ffffffff819e46e0)
Location: include/linux/netdevice.h:3709
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/core/neighbour.c (ffffffff819fa320)
Location: include/linux/netdevice.h:3709
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff81a067a4)
Location: include/linux/netdevice.h:3709
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81a09fe5)
Location: include/linux/netdevice.h:3709
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/net-sysfs.c (ffffffff81a21b41)
Location: include/linux/netdevice.h:3709
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:testing_show
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (ffffffff81a25d92)
Location: include/linux/netdevice.h:3709
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffff81a54382)
Location: include/linux/netdevice.h:3709
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/sched/sch_generic.c (ffffffff81a55d05)
Location: include/linux/netdevice.h:3709
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/common.c (ffffffff81a786b5)
Location: include/linux/netdevice.h:3709
Inline: True
Inline callers:
  - net/ethtool/common.c:__ethtool_get_link
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0bda9)
Location: include/linux/netdevice.h:3709
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/addrconf.c (ffffffff81b31776)
Location: include/linux/netdevice.h:3709
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/wireless/wext-core.c (ffffffff81b8d8bb)
Location: include/linux/netdevice.h:3709
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/phy/phy.c (ffffffff819014b5)
Location: include/linux/netdevice.h:3721
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_do_ioctl_running
```
```
In drivers/net/tun.c (ffffffff81911c5b)
Location: include/linux/netdevice.h:3721
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8191ccdf)
Location: include/linux/netdevice.h:3721
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
```
In net/core/dev.c (ffffffff81a951c0)
Location: include/linux/netdevice.h:3721
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/core/neighbour.c (ffffffff81aad288)
Location: include/linux/netdevice.h:3721
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff81ab8c04)
Location: include/linux/netdevice.h:3721
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81abc4f5)
Location: include/linux/netdevice.h:3721
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/net-sysfs.c (ffffffff81ad6021)
Location: include/linux/netdevice.h:3721
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:testing_show
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (ffffffff81adaaf2)
Location: include/linux/netdevice.h:3721
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffff81b0d072)
Location: include/linux/netdevice.h:3721
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/sched/sch_generic.c (ffffffff81b0ea97)
Location: include/linux/netdevice.h:3721
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/common.c (ffffffff81b327a5)
Location: include/linux/netdevice.h:3721
Inline: True
Inline callers:
  - net/ethtool/common.c:__ethtool_get_link
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bced69)
Location: include/linux/netdevice.h:3721
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/addrconf.c (ffffffff81bf7816)
Location: include/linux/netdevice.h:3721
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/wireless/wext-core.c (ffffffff81c59d0d)
Location: include/linux/netdevice.h:3721
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/phy/phy.c (ffffffff81a52eb5)
Location: include/linux/netdevice.h:3512
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_do_ioctl_running
```
```
In drivers/net/tun.c (ffffffff81a64baa)
Location: include/linux/netdevice.h:3512
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81a72ab4)
Location: include/linux/netdevice.h:3512
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
```
In net/core/dev.c (ffffffff81c0b820)
Location: include/linux/netdevice.h:3512
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/core/neighbour.c (ffffffff81c228b0)
Location: include/linux/netdevice.h:3512
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff81c31e45)
Location: include/linux/netdevice.h:3512
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81c36ef5)
Location: include/linux/netdevice.h:3512
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81c551af)
Location: include/linux/netdevice.h:3512
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:testing_show
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:carrier_store
```
```
In net/core/netpoll.c (ffffffff81c5c1f7)
Location: include/linux/netdevice.h:3512
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffff81c931a2)
Location: include/linux/netdevice.h:3512
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81c9579e)
Location: include/linux/netdevice.h:3512
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/common.c (ffffffff81cbdd15)
Location: include/linux/netdevice.h:3512
Inline: True
Inline callers:
  - net/ethtool/common.c:__ethtool_get_link
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d64d39)
Location: include/linux/netdevice.h:3512
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/addrconf.c (ffffffff81d90cc2)
Location: include/linux/netdevice.h:3512
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/wireless/wext-core.c (ffffffff81dfb564)
Location: include/linux/netdevice.h:3512
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/phy/phy.c (ffffffff81bdd025)
Location: include/linux/netdevice.h:3557
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_do_ioctl_running
```
```
In drivers/net/tun.c (ffffffff81befe34)
Location: include/linux/netdevice.h:3557
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81c05234)
Location: include/linux/netdevice.h:3557
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
```
In net/core/dev.c (ffffffff81dbbab0)
Location: include/linux/netdevice.h:3557
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_device_detach
```
```
In net/core/neighbour.c (ffffffff81dd529e)
Location: include/linux/netdevice.h:3557
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff81de5215)
Location: include/linux/netdevice.h:3557
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81dea525)
Location: include/linux/netdevice.h:3557
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81e0aa5f)
Location: include/linux/netdevice.h:3557
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:testing_show
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:carrier_store
```
```
In net/core/netpoll.c (ffffffff81e126df)
Location: include/linux/netdevice.h:3557
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffff81e4e842)
Location: include/linux/netdevice.h:3557
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81e50a99)
Location: include/linux/netdevice.h:3557
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_carrier_on
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/common.c (ffffffff81e7c505)
Location: include/linux/netdevice.h:3557
Inline: True
Inline callers:
  - net/ethtool/common.c:__ethtool_get_link
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2fbd9)
Location: include/linux/netdevice.h:3557
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/addrconf.c (ffffffff81f5f3e2)
Location: include/linux/netdevice.h:3557
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/wireless/wext-core.c (ffffffff81fcfdf5)
Location: include/linux/netdevice.h:3557
Inline: True
Inline callers:
  - net/wireless/wext-core.c:call_commit_handler
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
In drivers/net/phy/phy.c (ffffffff81c33955)
Location: include/linux/netdevice.h:3621
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_do_ioctl_running
```
```
In drivers/net/tun.c (ffffffff81c483b4)
Location: include/linux/netdevice.h:3621
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81c54495)
Location: include/linux/netdevice.h:3621
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
```
```
In drivers/net/xen-netfront.c (ffffffff81c6a944)
Location: include/linux/netdevice.h:3621
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
```
In drivers/net/net_failover.c (ffffffff81c6fb31)
Location: include/linux/netdevice.h:3621
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_lower_state_changed
  - drivers/net/net_failover.c:net_failover_lower_state_changed
  - drivers/net/net_failover.c:net_failover_lower_state_changed
  - drivers/net/net_failover.c:net_failover_xmit_ready
```
```
In net/core/dev.c (ffffffff81e2c240)
Location: include/linux/netdevice.h:3621
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_device_detach
```
```
In net/core/neighbour.c (ffffffff81e461f5)
Location: include/linux/netdevice.h:3621
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff81e56c35)
Location: include/linux/netdevice.h:3621
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81e5bd05)
Location: include/linux/netdevice.h:3621
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81e7ddef)
Location: include/linux/netdevice.h:3621
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:testing_show
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:carrier_store
```
```
In net/core/netpoll.c (ffffffff81e85f1f)
Location: include/linux/netdevice.h:3621
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/failover.c (ffffffff81ea03cb)
Location: include/linux/netdevice.h:3621
Inline: True
Inline callers:
  - net/core/failover.c:failover_event
  - net/core/failover.c:failover_event
```
```
In net/ethernet/eth.c (ffffffff81ea9ee2)
Location: include/linux/netdevice.h:3621
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81eac2a9)
Location: include/linux/netdevice.h:3621
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_carrier_on
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/common.c (ffffffff81ed88a5)
Location: include/linux/netdevice.h:3621
Inline: True
Inline callers:
  - net/ethtool/common.c:__ethtool_get_link
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f90669)
Location: include/linux/netdevice.h:3621
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/addrconf.c (ffffffff81fbf110)
Location: include/linux/netdevice.h:3621
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/wireless/wext-core.c (ffffffff8204b8b5)
Location: include/linux/netdevice.h:3621
Inline: True
Inline callers:
  - net/wireless/wext-core.c:call_commit_handler
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
In drivers/net/phy/phy.c (ffffffff81ce8735)
Location: include/linux/netdevice.h:3710
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_do_ioctl_running
```
```
In drivers/net/tun.c (ffffffff81cfdd31)
Location: include/linux/netdevice.h:3710
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81d0abb3)
Location: include/linux/netdevice.h:3710
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
```
```
In drivers/net/xen-netfront.c (ffffffff81d1f321)
Location: include/linux/netdevice.h:3710
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
```
In drivers/net/net_failover.c (ffffffff81d243db)
Location: include/linux/netdevice.h:3710
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_lower_state_changed
  - drivers/net/net_failover.c:net_failover_lower_state_changed
  - drivers/net/net_failover.c:net_failover_lower_state_changed
  - drivers/net/net_failover.c:net_failover_xmit_ready
```
```
In net/core/dev.c (ffffffff81eea290)
Location: include/linux/netdevice.h:3710
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_device_detach
```
```
In net/core/neighbour.c (ffffffff81f04e95)
Location: include/linux/netdevice.h:3710
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff81f15f87)
Location: include/linux/netdevice.h:3710
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81f1b0c5)
Location: include/linux/netdevice.h:3710
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81f3ecff)
Location: include/linux/netdevice.h:3710
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:testing_show
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:carrier_store
```
```
In net/core/netpoll.c (ffffffff81f47f1f)
Location: include/linux/netdevice.h:3710
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/failover.c (ffffffff81f62b37)
Location: include/linux/netdevice.h:3710
Inline: True
Inline callers:
  - net/core/failover.c:failover_event
  - net/core/failover.c:failover_event
```
```
In net/ethernet/eth.c (ffffffff81f6c9a2)
Location: include/linux/netdevice.h:3710
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81f6ed3c)
Location: include/linux/netdevice.h:3710
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_carrier_on
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/common.c (ffffffff81f9c6b5)
Location: include/linux/netdevice.h:3710
Inline: True
Inline callers:
  - net/ethtool/common.c:__ethtool_get_link
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205e3c9)
Location: include/linux/netdevice.h:3710
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/addrconf.c (ffffffff8208c5a5)
Location: include/linux/netdevice.h:3710
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/wireless/wext-core.c (ffffffff8211dd35)
Location: include/linux/netdevice.h:3710
Inline: True
Inline callers:
  - net/wireless/wext-core.c:call_commit_handler
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
In drivers/net/tun.c (ffff8000109de964)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e45fc)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_get_ethtool_stats
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_ioctl
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ea670)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_ioctl
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_ethtool_stats
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fc030)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_resume
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_suspend
```
```
In drivers/net/xen-netfront.c (ffff800010a07c08)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In net/core/dev.c (ffff800010bc6cc0)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffff800010bdd43c)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/neighbour.c (ffff800010be2a08)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffff800010bf165c)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffff800010bf3550)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/core/net-sysfs.c (ffff800010c0af30)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (ffff800010c11878)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffff800010c3664c)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/sched/sch_generic.c (ffff800010c38b00)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/xfrm/xfrm_policy.c (ffff800010cda0a8)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/ipv6/addrconf.c (ffff800010d0275c)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/wireless/wext-core.c (ffff800010d6180c)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/tun.c (c0ac3bac)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0accae8)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_ioctl
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_ethtool_stats
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad6604)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_resume
  - drivers/net/ethernet/ti/cpsw.c:cpsw_suspend
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
  - drivers/net/ethernet/ti/cpsw.c:cpsw_adjust_link
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
```
```
In drivers/net/ethernet/ti/cpsw_ethtool.c (c0adb294)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_set_channels_common
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_resume_data_pass
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_suspend_data_pass
```
```
In net/core/dev.c (c0ce213c)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (c0cf85b0)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/neighbour.c (c0cfba10)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (c0d09de0)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (c0d0bf20)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/core/net-sysfs.c (c0d24348)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (c0d2859c)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (c0d49064)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/sched/sch_generic.c (c0d4a65c)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/xfrm/xfrm_policy.c (c0de3dec)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/ipv6/addrconf.c (c0e08568)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/wireless/wext-core.c (c0e60c74)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/tun.c (c000000000aa0128)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/core/dev.c (c000000000ca1924)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (c000000000cbdbc0)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/neighbour.c (c000000000cc4f38)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (c000000000cd611c)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (c000000000cd8978)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/core/net-sysfs.c (c000000000cf3b74)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (c000000000cfcdf4)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (c000000000d2e6ac)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/sched/sch_generic.c (c000000000d30bd0)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/xfrm/xfrm_policy.c (c000000000dfb0b0)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/ipv6/addrconf.c (c000000000e2a004)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/wireless/wext-core.c (c000000000e9cb68)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/tun.c (ffffffe000629178)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/core/dev.c (ffffffe0007531de)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffffffe0007649ee)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/neighbour.c (ffffffe000769040)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffe0007733de)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffe000774f68)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/core/net-sysfs.c (ffffffe000786d64)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (ffffffe00078cbea)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffe0007a8042)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/sched/sch_generic.c (ffffffe0007aa0d2)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082c52a)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffe00084ab66)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/wireless/wext-core.c (ffffffe0008963da)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/tun.c (ffffffff8178895d)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8179367d)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In net/core/dev.c (ffffffff818ca350)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffffffff818de6ca)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/neighbour.c (ffffffff818e2a05)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff818ef914)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff818f1995)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff819048ac)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (ffffffff8190a432)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffff8192b58e)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/sched/sch_generic.c (ffffffff8192d4d2)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bd193)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819de901)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/wireless/wext-core.c (ffffffff81a32d10)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/tun.c (ffffffff817682ad)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In drivers/net/vxlan.c (ffffffff81770b70)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_stop
  - drivers/net/vxlan.c:vxlan_cleanup
  - drivers/net/vxlan.c:vxlan_snoop
```
```
In net/core/dev.c (ffffffff81884290)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffffffff8189850a)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/neighbour.c (ffffffff8189c845)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff818a9754)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff818ab7d5)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff818be6dc)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (ffffffff818c42e2)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffff818e533e)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/sched/sch_generic.c (ffffffff818e6fd2)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/xfrm/xfrm_policy.c (ffffffff81979f83)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8199b6c1)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
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
In drivers/net/tun.c (ffffffff817b8cfd)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817c38dd)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In net/core/dev.c (ffffffff8191b350)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffffffff8192f6fa)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/neighbour.c (ffffffff81933a35)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff81940944)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff819429c5)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff819558dc)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (ffffffff8195b462)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffff8197c71e)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/sched/sch_generic.c (ffffffff8197e662)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a27c13)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a49381)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/wireless/wext-core.c (ffffffff81a9e8c0)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
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
In drivers/net/tun.c (ffffffff817d39cd)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817ddb9d)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In net/core/dev.c (ffffffff8193c550)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffffffff81950dca)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/neighbour.c (ffffffff81953edc)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
```
```
In net/core/rtnetlink.c (ffffffff81962254)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff819642c5)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff8197791e)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:dormant_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:change_carrier
```
```
In net/core/netpoll.c (ffffffff8197d682)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ethernet/eth.c (ffffffff8199ec6e)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/sched/sch_generic.c (ffffffff819a036e)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a33243)
Location: include/linux/netdevice.h:3357
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a552a1)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/wireless/wext-core.c (ffffffff81aaaac0)
Location: include/linux/netdevice.h:3357
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
```
</details>
</li>
</ul>

## Differences
