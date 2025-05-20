# Function: <code>netif_device_present</code>

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
In net/core/dev.c (ffffffff81713b68)
Location: include/linux/netdevice.h:3221
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
```
```
In net/core/ethtool.c (ffffffff81720858)
Location: include/linux/netdevice.h:3221
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/rtnetlink.c (ffffffff8172bb35)
Location: include/linux/netdevice.h:3221
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/dev_ioctl.c (ffffffff8173390f)
Location: include/linux/netdevice.h:3221
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (ffffffff81738cc2)
Location: include/linux/netdevice.h:3221
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/sched/sch_generic.c (ffffffff8174111c)
Location: include/linux/netdevice.h:3221
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/8021q/vlan_core.c (ffffffff8180907a)
Location: include/linux/netdevice.h:3221
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
```
```
In net/wireless/wext-core.c (ffffffff818099f6)
Location: include/linux/netdevice.h:3221
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffff8177ba08)
Location: include/linux/netdevice.h:3448
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
```
```
In net/core/ethtool.c (ffffffff8178a05b)
Location: include/linux/netdevice.h:3448
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/rtnetlink.c (ffffffff817953e4)
Location: include/linux/netdevice.h:3448
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/dev_ioctl.c (ffffffff8179f34f)
Location: include/linux/netdevice.h:3448
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (ffffffff817a536f)
Location: include/linux/netdevice.h:3448
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff817adf3c)
Location: include/linux/netdevice.h:3448
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/8021q/vlan_core.c (ffffffff8187abc1)
Location: include/linux/netdevice.h:3448
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
```
```
In net/wireless/wext-core.c (ffffffff8187b4f6)
Location: include/linux/netdevice.h:3448
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffff817a91a8)
Location: include/linux/netdevice.h:3402
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
```
```
In net/core/ethtool.c (ffffffff817b793b)
Location: include/linux/netdevice.h:3402
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/rtnetlink.c (ffffffff817c2c74)
Location: include/linux/netdevice.h:3402
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/dev_ioctl.c (ffffffff817cdd1f)
Location: include/linux/netdevice.h:3402
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (ffffffff817d3ddf)
Location: include/linux/netdevice.h:3402
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff817dd5bc)
Location: include/linux/netdevice.h:3402
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/8021q/vlan_core.c (ffffffff818af481)
Location: include/linux/netdevice.h:3402
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
```
```
In net/wireless/wext-core.c (ffffffff818afdb6)
Location: include/linux/netdevice.h:3402
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffff817c7728)
Location: include/linux/netdevice.h:3448
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
```
```
In net/core/ethtool.c (ffffffff817d6203)
Location: include/linux/netdevice.h:3448
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/rtnetlink.c (ffffffff817e141a)
Location: include/linux/netdevice.h:3448
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/dev_ioctl.c (ffffffff817ed101)
Location: include/linux/netdevice.h:3448
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (ffffffff817f315f)
Location: include/linux/netdevice.h:3448
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff817fcbfb)
Location: include/linux/netdevice.h:3448
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/8021q/vlan_core.c (ffffffff818d5c3b)
Location: include/linux/netdevice.h:3448
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
```
```
In net/wireless/wext-core.c (ffffffff818d67d8)
Location: include/linux/netdevice.h:3448
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffff81841308)
Location: include/linux/netdevice.h:3477
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
```
```
In net/core/ethtool.c (ffffffff81850743)
Location: include/linux/netdevice.h:3477
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/rtnetlink.c (ffffffff8185bf6b)
Location: include/linux/netdevice.h:3477
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/dev_ioctl.c (ffffffff818692f1)
Location: include/linux/netdevice.h:3477
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (ffffffff8186e53b)
Location: include/linux/netdevice.h:3477
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8187a745)
Location: include/linux/netdevice.h:3477
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/8021q/vlan_core.c (ffffffff8195b7eb)
Location: include/linux/netdevice.h:3477
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_vid_add
```
```
In net/wireless/wext-core.c (ffffffff8195c39a)
Location: include/linux/netdevice.h:3477
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffff8188ba18)
Location: include/linux/netdevice.h:3583
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
```
```
In net/core/ethtool.c (ffffffff8189bb1b)
Location: include/linux/netdevice.h:3583
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/rtnetlink.c (ffffffff818a7f11)
Location: include/linux/netdevice.h:3583
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/dev_ioctl.c (ffffffff818b9102)
Location: include/linux/netdevice.h:3583
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (ffffffff818bf6cb)
Location: include/linux/netdevice.h:3583
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff818cc725)
Location: include/linux/netdevice.h:3583
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/8021q/vlan_core.c (ffffffff819b4daf)
Location: include/linux/netdevice.h:3583
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_kill_rx_filter_info
  - net/8021q/vlan_core.c:vlan_add_rx_filter_info
```
```
In net/wireless/wext-core.c (ffffffff819b5bc9)
Location: include/linux/netdevice.h:3583
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffff818acb98)
Location: include/linux/netdevice.h:3809
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
```
```
In net/core/ethtool.c (ffffffff818bdf2c)
Location: include/linux/netdevice.h:3809
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/rtnetlink.c (ffffffff818cc081)
Location: include/linux/netdevice.h:3809
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (ffffffff818d24a0)
Location: include/linux/netdevice.h:3809
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/dev_ioctl.c (ffffffff818dfd52)
Location: include/linux/netdevice.h:3809
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (ffffffff818e84eb)
Location: include/linux/netdevice.h:3809
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff818f7a75)
Location: include/linux/netdevice.h:3809
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/8021q/vlan_core.c (ffffffff819ebdff)
Location: include/linux/netdevice.h:3809
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_kill_rx_filter_info
  - net/8021q/vlan_core.c:vlan_add_rx_filter_info
```
```
In net/wireless/wext-core.c (ffffffff819ece89)
Location: include/linux/netdevice.h:3809
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffff818f82e8)
Location: include/linux/netdevice.h:3830
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
```
```
In net/core/ethtool.c (ffffffff8190a91c)
Location: include/linux/netdevice.h:3830
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/rtnetlink.c (ffffffff819191a3)
Location: include/linux/netdevice.h:3830
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (ffffffff8191f740)
Location: include/linux/netdevice.h:3830
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/dev_ioctl.c (ffffffff8192e33a)
Location: include/linux/netdevice.h:3830
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (ffffffff81937cf7)
Location: include/linux/netdevice.h:3830
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81957165)
Location: include/linux/netdevice.h:3830
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/8021q/vlan_core.c (ffffffff81a5af8f)
Location: include/linux/netdevice.h:3830
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_kill_rx_filter_info
  - net/8021q/vlan_core.c:vlan_add_rx_filter_info
```
```
In net/wireless/wext-core.c (ffffffff81a5c05c)
Location: include/linux/netdevice.h:3830
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffff8192a478)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
```
```
In net/core/ethtool.c (ffffffff8193cf2c)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/rtnetlink.c (ffffffff8194b7c3)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (ffffffff81951980)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/dev_ioctl.c (ffffffff819605ba)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (ffffffff8196abb7)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8198d605)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/8021q/vlan_core.c (ffffffff81a91baf)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_kill_rx_filter_info
  - net/8021q/vlan_core.c:vlan_add_rx_filter_info
```
```
In net/wireless/wext-core.c (ffffffff81a92c8c)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffff819fe338)
Location: include/linux/netdevice.h:3999
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
```
```
In net/core/rtnetlink.c (ffffffff81a1c409)
Location: include/linux/netdevice.h:3999
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (ffffffff81a229e0)
Location: include/linux/netdevice.h:3999
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/dev_ioctl.c (ffffffff81a33dba)
Location: include/linux/netdevice.h:3999
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (ffffffff81a3e6f0)
Location: include/linux/netdevice.h:3999
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81a652f8)
Location: include/linux/netdevice.h:3999
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/ioctl.c (ffffffff81a84170)
Location: include/linux/netdevice.h:3999
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
```
In net/ethtool/netlink.c (ffffffff81a85e7e)
Location: include/linux/netdevice.h:3999
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/8021q/vlan_core.c (ffffffff81b8d19f)
Location: include/linux/netdevice.h:3999
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_kill_rx_filter_info
  - net/8021q/vlan_core.c:vlan_add_rx_filter_info
```
```
In net/wireless/wext-core.c (ffffffff81b8e94c)
Location: include/linux/netdevice.h:3999
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffff819fdf48)
Location: include/linux/netdevice.h:4167
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__dev_open
```
```
In net/core/rtnetlink.c (ffffffff81a1c7af)
Location: include/linux/netdevice.h:4167
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (ffffffff81a22d40)
Location: include/linux/netdevice.h:4167
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/dev_ioctl.c (ffffffff81a35f83)
Location: include/linux/netdevice.h:4167
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (ffffffff81a41490)
Location: include/linux/netdevice.h:4167
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81a6d428)
Location: include/linux/netdevice.h:4167
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/ioctl.c (ffffffff81a8dca0)
Location: include/linux/netdevice.h:4167
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
```
In net/ethtool/netlink.c (ffffffff81a8f7f8)
Location: include/linux/netdevice.h:4167
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/8021q/vlan_core.c (ffffffff81b9ce0f)
Location: include/linux/netdevice.h:4167
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_kill_rx_filter_info
  - net/8021q/vlan_core.c:vlan_add_rx_filter_info
```
```
In net/wireless/wext-core.c (ffffffff81b9e5ec)
Location: include/linux/netdevice.h:4167
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffff819e4808)
Location: include/linux/netdevice.h:4297
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__dev_open
```
```
In net/core/rtnetlink.c (ffffffff81a03593)
Location: include/linux/netdevice.h:4297
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (ffffffff81a0a190)
Location: include/linux/netdevice.h:4297
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/dev_ioctl.c (ffffffff81a1d0e3)
Location: include/linux/netdevice.h:4297
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (ffffffff81a26100)
Location: include/linux/netdevice.h:4297
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81a55ca8)
Location: include/linux/netdevice.h:4297
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/ioctl.c (ffffffff81a76bdb)
Location: include/linux/netdevice.h:4297
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
```
In net/ethtool/netlink.c (ffffffff81a78edb)
Location: include/linux/netdevice.h:4297
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/8021q/vlan_core.c (ffffffff81b8bf1f)
Location: include/linux/netdevice.h:4297
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_kill_rx_filter_info
  - net/8021q/vlan_core.c:vlan_add_rx_filter_info
```
```
In net/wireless/wext-core.c (ffffffff81b8d6ec)
Location: include/linux/netdevice.h:4297
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffff81a952e8)
Location: include/linux/netdevice.h:4320
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__dev_open
```
```
In net/core/rtnetlink.c (ffffffff81ab5b79)
Location: include/linux/netdevice.h:4320
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (ffffffff81abc6a0)
Location: include/linux/netdevice.h:4320
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/dev_ioctl.c (ffffffff81ad08f5)
Location: include/linux/netdevice.h:4320
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff81ad6d93)
Location: include/linux/netdevice.h:4320
Inline: True
Inline callers:
  - net/core/net-sysfs.c:speed_show
```
```
In net/core/netpoll.c (ffffffff81adae70)
Location: include/linux/netdevice.h:4320
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81b0ea33)
Location: include/linux/netdevice.h:4320
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/ioctl.c (ffffffff81b30e24)
Location: include/linux/netdevice.h:4320
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
```
In net/ethtool/netlink.c (ffffffff81b3300e)
Location: include/linux/netdevice.h:4320
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_ops_begin
```
```
In net/8021q/vlan_core.c (ffffffff81c5849f)
Location: include/linux/netdevice.h:4320
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_kill_rx_filter_info
  - net/8021q/vlan_core.c:vlan_add_rx_filter_info
```
```
In net/wireless/wext-core.c (ffffffff81c5976c)
Location: include/linux/netdevice.h:4320
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffff81c1df4c)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__dev_open
```
```
In net/core/rtnetlink.c (ffffffff81c2f6d0)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (ffffffff81c370d9)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/dev_ioctl.c (ffffffff81c4e1cc)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff81c5742b)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/core/net-sysfs.c:speed_show
```
```
In net/core/netpoll.c (ffffffff81c5c330)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81c9575d)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/ioctl.c (ffffffff81cbbd76)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
```
In net/ethtool/netlink.c (ffffffff81cbe1ce)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_ops_begin
```
```
In net/8021q/vlan_core.c (ffffffff81df9909)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_kill_rx_filter_info
  - net/8021q/vlan_core.c:vlan_add_rx_filter_info
```
```
In net/wireless/wext-core.c (ffffffff81dfaf19)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffff81dcf33c)
Location: include/linux/netdevice.h:4228
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__dev_open
```
```
In net/core/rtnetlink.c (ffffffff81de29c0)
Location: include/linux/netdevice.h:4228
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (ffffffff81dea949)
Location: include/linux/netdevice.h:4228
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/dev_ioctl.c (ffffffff81e0325c)
Location: include/linux/netdevice.h:4228
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff81e0d4db)
Location: include/linux/netdevice.h:4228
Inline: True
Inline callers:
  - net/core/net-sysfs.c:speed_show
```
```
In net/core/netpoll.c (ffffffff81e12a0d)
Location: include/linux/netdevice.h:4228
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81e512bd)
Location: include/linux/netdevice.h:4228
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/ioctl.c (ffffffff81e7a366)
Location: include/linux/netdevice.h:4228
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
```
In net/ethtool/netlink.c (ffffffff81e7cc6e)
Location: include/linux/netdevice.h:4228
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_ops_begin
```
```
In net/8021q/vlan_core.c (ffffffff81fce229)
Location: include/linux/netdevice.h:4228
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_kill_rx_filter_info
  - net/8021q/vlan_core.c:vlan_add_rx_filter_info
```
```
In net/wireless/wext-core.c (ffffffff81fcfbb4)
Location: include/linux/netdevice.h:4228
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffff81e3ff6c)
Location: include/linux/netdevice.h:4287
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__dev_open
```
```
In net/core/rtnetlink.c (ffffffff81e53e7c)
Location: include/linux/netdevice.h:4287
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (ffffffff81e5c129)
Location: include/linux/netdevice.h:4287
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/dev_ioctl.c (ffffffff81e75b76)
Location: include/linux/netdevice.h:4287
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_eth_ioctl
```
```
In net/core/net-sysfs.c (ffffffff81e8072b)
Location: include/linux/netdevice.h:4287
Inline: True
Inline callers:
  - net/core/net-sysfs.c:speed_show
```
```
In net/core/netpoll.c (ffffffff81e8634d)
Location: include/linux/netdevice.h:4287
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81eacaed)
Location: include/linux/netdevice.h:4287
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/ioctl.c (ffffffff81ed665c)
Location: include/linux/netdevice.h:4287
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
```
In net/ethtool/netlink.c (ffffffff81ed902e)
Location: include/linux/netdevice.h:4287
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_ops_begin
```
```
In net/8021q/vlan_core.c (ffffffff82049b79)
Location: include/linux/netdevice.h:4287
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_kill_rx_filter_info
  - net/8021q/vlan_core.c:vlan_add_rx_filter_info
```
```
In net/wireless/wext-core.c (ffffffff8204abbf)
Location: include/linux/netdevice.h:4287
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffff81efe8cc)
Location: include/linux/netdevice.h:4363
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__dev_open
```
```
In net/core/rtnetlink.c (ffffffff81f131dc)
Location: include/linux/netdevice.h:4363
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (ffffffff81f1b509)
Location: include/linux/netdevice.h:4363
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/dev_ioctl.c (ffffffff81f35a4e)
Location: include/linux/netdevice.h:4363
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_set_hwtstamp
  - net/core/dev_ioctl.c:dev_eth_ioctl
```
```
In net/core/net-sysfs.c (ffffffff81f416eb)
Location: include/linux/netdevice.h:4363
Inline: True
Inline callers:
  - net/core/net-sysfs.c:speed_show
```
```
In net/core/netpoll.c (ffffffff81f48360)
Location: include/linux/netdevice.h:4363
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81f6f5ad)
Location: include/linux/netdevice.h:4363
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/ioctl.c (ffffffff81f9a1dc)
Location: include/linux/netdevice.h:4363
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
```
In net/ethtool/netlink.c (ffffffff81f9cede)
Location: include/linux/netdevice.h:4363
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_ops_begin
```
```
In net/8021q/vlan_core.c (ffffffff8211c1a9)
Location: include/linux/netdevice.h:4363
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_kill_rx_filter_info
  - net/8021q/vlan_core.c:vlan_add_rx_filter_info
```
```
In net/wireless/wext-core.c (ffffffff8211d03f)
Location: include/linux/netdevice.h:4363
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e79ec)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
```
```
In net/core/dev.c (ffff800010bc6e60)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
```
```
In net/core/ethtool.c (ffff800010bdc7b8)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/rtnetlink.c (ffff800010becd30)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (ffff800010bf38a8)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/dev_ioctl.c (ffff800010c0425c)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (ffff800010c111f0)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffff800010c38a0c)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/8021q/vlan_core.c (ffff800010d5f824)
Location: include/linux/netdevice.h:3846
Inline: True
```
```
In net/wireless/wext-core.c (ffff800010d60a78)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In drivers/net/ethernet/freescale/fec_main.c (c0ac98bc)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
```
```
In net/core/dev.c (c0ce2264)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
```
```
In net/core/ethtool.c (c0cf6e4c)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/rtnetlink.c (c0d0526c)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (c0d0beb8)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/dev_ioctl.c (c0d1d46c)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (c0d2905c)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (c0d4a5dc)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/8021q/vlan_core.c (c0e5f3c0)
Location: include/linux/netdevice.h:3846
Inline: True
```
```
In net/wireless/wext-core.c (c0e60f40)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_handle_ioctl
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
In net/core/dev.c (c000000000ca1ae0)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
```
```
In net/core/ethtool.c (c000000000cbc7d8)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/rtnetlink.c (c000000000cd0e00)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (c000000000cd88e0)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/dev_ioctl.c (c000000000cedb24)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (c000000000cfd9b4)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (c000000000d30ae4)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/8021q/vlan_core.c (c000000000e9a44c)
Location: include/linux/netdevice.h:3846
Inline: True
```
```
In net/wireless/wext-core.c (c000000000e9bcdc)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffe000753348)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
```
```
In net/core/ethtool.c (ffffffe000763e02)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/rtnetlink.c (ffffffe00076f3a4)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (ffffffe000774eec)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/dev_ioctl.c (ffffffe000782eb8)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (ffffffe00078d43c)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffe0007aa02a)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/8021q/vlan_core.c (ffffffe000894e58)
Location: include/linux/netdevice.h:3846
Inline: True
```
```
In net/wireless/wext-core.c (ffffffe0008965b0)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_handle_ioctl
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
In net/core/dev.c (ffffffff818ca478)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
```
```
In net/core/ethtool.c (ffffffff818dcefc)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/rtnetlink.c (ffffffff818eb793)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (ffffffff818f1950)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/dev_ioctl.c (ffffffff8190058a)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (ffffffff8190ab87)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8192d475)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/8021q/vlan_core.c (ffffffff81a3123f)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_kill_rx_filter_info
  - net/8021q/vlan_core.c:vlan_add_rx_filter_info
```
```
In net/wireless/wext-core.c (ffffffff81a3231c)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffff818843b8)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
```
```
In net/core/ethtool.c (ffffffff81896d3c)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/rtnetlink.c (ffffffff818a55d3)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (ffffffff818ab790)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/dev_ioctl.c (ffffffff818ba3ba)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (ffffffff818c4927)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff818e6f75)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/8021q/vlan_core.c (ffffffff819ee42f)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_kill_rx_filter_info
  - net/8021q/vlan_core.c:vlan_add_rx_filter_info
```
```
In net/wireless/wext-core.c (ffffffff819ef5a6)
Location: include/linux/netdevice.h:3846
Inline: True
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
In net/core/dev.c (ffffffff8191b478)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
```
```
In net/core/ethtool.c (ffffffff8192df2c)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/rtnetlink.c (ffffffff8193c7c3)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (ffffffff81942980)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/dev_ioctl.c (ffffffff819515ba)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (ffffffff8195bbb7)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8197e605)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/8021q/vlan_core.c (ffffffff81a9cdef)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_kill_rx_filter_info
  - net/8021q/vlan_core.c:vlan_add_rx_filter_info
```
```
In net/wireless/wext-core.c (ffffffff81a9decc)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
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
In net/core/dev.c (ffffffff8193c678)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down
  - net/core/dev.c:dev_change_carrier
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_open
```
```
In net/core/ethtool.c (ffffffff8194f5fc)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/rtnetlink.c (ffffffff8195e033)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/link_watch.c (ffffffff81964280)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/dev_ioctl.c (ffffffff81972faa)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/netpoll.c (ffffffff8197dfb7)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff819a0313)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/8021q/vlan_core.c (ffffffff81aa8fdf)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_kill_rx_filter_info
  - net/8021q/vlan_core.c:vlan_add_rx_filter_info
```
```
In net/wireless/wext-core.c (ffffffff81aaa0cc)
Location: include/linux/netdevice.h:3846
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_process_ioctl
```
</details>
</li>
</ul>

## Differences
